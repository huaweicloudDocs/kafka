# 连接和查看Kafka Manager<a name="ZH-CN_TOPIC_0171821733"></a>

Kafka Manager是开源的kafka集群管理工具，需要通过浏览器才能访问Kafka Manager的地址。在Kafka Manager页面，您可以查看Kafka集群的监控、节点等信息。

如果Kafka专享版实例未开启公网访问，您需要通过一台与Kafka专享实例相同VPC和相同安全组的Windows弹性云服务器访问。

如果Kafka专享版实例已经开启公网访问，您可以直接在本地浏览器中访问。

本文以Kafka专享版实例未开启公网访问为例。

## 登录Kafka Manager<a name="zh-cn_topic_0143117163_section14321822182915"></a>

1.  创建一台与Kafka专享实例相同VPC和相同安全组的Windows服务器，详细步骤请参考《[购买并登录Windows弹性云服务器](https://support.huaweicloud.com/qs-ecs/zh-cn_topic_0021831611.html)》。
2.  获取Kafka Manager地址。

    如[图1](#zh-cn_topic_0143117163_fig181443461517)所示，在实例详情信息页面，获取Kafka Manager的地址。

    **图 1**  获取Kafka Manager地址<a name="zh-cn_topic_0143117163_fig181443461517"></a>  
    ![](figures/获取Kafka-Manager地址.png "获取Kafka-Manager地址")

3.  登录Windows服务器，然后在浏览器中输入Kafka Manager的地址，进入Kafka Manager登录页面。
4.  输入创建实例时设置的Kafka Manager用户名和密码，即可管理Kafka集群。

## 查看Kafka Manager<a name="zh-cn_topic_0143117163_section1250619492116"></a>

在进入Kafka Manger集群管理页面后，您可以查看Kafka集群的监控、节点等信息。

-   集群信息页

    单击**Clusters**中的集群列表，即可进入集群信息页。如[图2](#zh-cn_topic_0143117163_fig5401930101911)所示。

    -   图中①区域表示功能导航栏
        -   **Cluster**: 集群，统计集群列表和集群详情。
        -   **Brokers**: 节点，统计当前集群中各节点的状态信息。
        -   **Topic**: 队列，统计当前集群中的kafka队列。
        -   **Perferred Replica Election**: 强制进行一次队列leader的最优选举（不建议用户操作）。
        -   **Reassign Partitions**: 进行分区副本的重分配（不建议用户操作）。
        -   **Consumers**: 统计集群中的消费组状态。

    -   图中②区域表示集群信息统计，包含集群的topic数和集群的节点数。

        **图 2**  集群信息页<a name="zh-cn_topic_0143117163_fig5401930101911"></a>  
        ![](figures/集群信息页.png "集群信息页")


-   集群所有节点统计页

    单击功能导航栏中的**Brokers**，即可进入节点统计页。如[图3](#zh-cn_topic_0143117163_fig850454717515)所示。

    -   图中①区域节点列表，包含总的字节流入和字节流出。
    -   图中②集群监控信息。

        **图 3**  所有节点统计页<a name="zh-cn_topic_0143117163_fig850454717515"></a>  
        ![](figures/所有节点统计页.png "所有节点统计页")


-   具体节点统计页

    单击id列表中具体的Broker节点，即可查看对应节点的统计信息。如[图4](#zh-cn_topic_0143117163_fig1833012481468)所示。

    -   图中①区域表示对应节点总的统计信息，包括队列数、分区数、分区leader数、消息速率占比、写入字节占比以及流出字节占比。
    -   图中②区域表示节点监控信息。

        **图 4**  具体Broker节点信息<a name="zh-cn_topic_0143117163_fig1833012481468"></a>  
        ![](figures/具体Broker节点信息.png "具体Broker节点信息")


-   查看实例的Topic

    在导航栏选择**Topic**，并在下拉列表中选择**List**。页面如[图5](#zh-cn_topic_0143117163_fig197812565918)所示，展示了队列列表以及分区数等。

    >![](public_sys-resources/icon-warning.gif) **警告：**   
    >列表中以“\_\_”开头的队列为内部队列，严禁操作，否则可能导致业务问题。  

    **图 5**  查看实例的Topic<a name="zh-cn_topic_0143117163_fig197812565918"></a>  
    ![](figures/查看实例的Topic.png "查看实例的Topic")

-   队列详情页

    单击具体的Topic名称，进入如[图6](#zh-cn_topic_0143117163_fig17368181052113)所示页面。

    -   图中①区域表示队列基本信息，包括副本数\(Replication\)，分区数\(Number of Partitions\)，消息数\(Sum of partition offsets\)等。
    -   图中②区域表示节点与队列分区的对应关系。
    -   图中③区域表示该队列的消费组列表。单击消费组名称可进入该消费组的详情页。
    -   图中④区域表示队列的配置信息。详情参考kafka队列官方配置文档\([http://kafka.apache.org/documentation/\#topicconfigs](http://kafka.apache.org/documentation/#topicconfigs)\)。
    -   图中⑤区域表示队列监控数据统计。
    -   图中⑥区域表示队列分区信息，包括分区消息数\(Latest Offset\)，分区leader\(Leader\)，副本列表\(Replicas\)，同步副本列表\(In Sync Replicas\)。

        **图 6**  队列详情页<a name="zh-cn_topic_0143117163_fig17368181052113"></a>  
        ![](figures/队列详情页.png "队列详情页")


-   查看消费组列表

    导航栏中单击**Consumers**页签，即可查看当前集群中的消费组列表。

    **图 7**  集群的消费组列表<a name="zh-cn_topic_0143117163_fig14273713142916"></a>  
    ![](figures/集群的消费组列表.png "集群的消费组列表")

-   查看消费组详情页

    单击消费组名称可进入消费组详情页面，展示消费组消费的所有队列列表以及每个队列的可消费数\(Total Lag\)。

    **图 8**  消费组详情页面<a name="zh-cn_topic_0143117163_fig1946187163013"></a>  
    ![](figures/消费组详情页面.png "消费组详情页面")

-   查看消费组队列详情页

    单击队列名称，即可进入详情页面，查看消费组消费在队列中每个分区的消费状态。包括分区编号\(Partition\)，分区消息数\(LogSize\)，分区消费进度\(Consumer Offset\)，分区剩余可消费数\(Lag\)，最近消费该分区的消费者\(Consumer Instance Owner\)。

    **图 9**  消费组队列详情页面<a name="zh-cn_topic_0143117163_fig15320163672920"></a>  
    ![](figures/消费组队列详情页面.png "消费组队列详情页面")


