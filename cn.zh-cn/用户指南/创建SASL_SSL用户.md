# 创建SASL\_SSL用户<a name="kafka-ug-0003"></a>

Kafka专享版实例开启SASL\_SSL后，参考本章节创建SASL\_SSL用户，并在Topic中为SASL\_SSL用户设置不同的权限，以达到SASL\_SSL用户之间的权限隔离。

## 前提条件<a name="section10943454010"></a>

创建Kafka专享版实例时，已开启SASL\_SSL功能。

## 操作步骤<a name="section1516984134111"></a>

1.  登录管理控制台。
2.  在管理控制台左上角单击![](figures/icon-region.png)，选择区域。

    >![](public_sys-resources/icon-note.gif) **说明：** 
    >此处请选择与您的应用服务相同的区域。

3.  在管理控制台左上角单击![](figures/icon-list.png)，选择“应用中间件 \> 分布式消息服务Kafka版”，进入分布式消息服务Kafka专享版页面。
4.  单击Kafka专享版实例名称，进入实例详情页面。
5.  在“用户管理”页签，单击“创建用户”，弹出“创建用户”对话框。
6.  设置用户名和密码，单击“确认”，完成用户的创建。

    SASL\_SSL用户创建成功后，参考[授权SASL\_SSL用户](授权SASL_SSL用户.md)为SASL\_SSL用户授权。

7.  （可选）如果忘记了SASL\_SSL用户的密码，请在SASL\_SSL用户所在行，单击“重置密码”，修改SASL\_SSL用户密码。
8.  （可选）如果SASL\_SSL用户已经不再需要，请在SASL\_SSL用户所在行，单击“删除”，删除此SASL\_SSL用户。

    >![](public_sys-resources/icon-note.gif) **说明：** 
    >创建Kafka专享版实例时，设置的SASL\_SSL用户无法删除。


