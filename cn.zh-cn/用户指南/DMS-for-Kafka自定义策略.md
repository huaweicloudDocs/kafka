# DMS for Kafka自定义策略<a name="CreatingCustomPolicy"></a>

如果系统预置的DMS for Kafka权限，不满足您的授权要求，可以创建自定义策略。自定义策略中可以添加的授权项（Action）请参考[细粒度策略支持的授权项](https://support.huaweicloud.com/api-kafka/api-grant-policy.html)。

目前华为云支持以下两种方式创建自定义策略：

-   可视化视图创建自定义策略：无需了解策略语法，按可视化视图导航栏选择云服务、操作、资源、条件等策略内容，可自动生成策略。
-   JSON视图创建自定义策略：可以在选择策略模板后，根据具体需求编辑策略内容；也可以直接在编辑框内编写JSON格式的策略内容。

具体创建步骤请参见：[创建自定义策略](https://support.huaweicloud.com/usermanual-iam/iam_01_0605.html)。本章为您介绍常用的DMS for Kafka自定义策略样例。

>![](public_sys-resources/icon-note.gif) **说明：** 
>-   DMS for Kafka的权限与策略基于分布式消息服务DMS，因此在IAM服务中为DMS for Kafka分配用户与权限时，请选择并使用“DMS”的权限与策略。
>-   由于缓存的存在，对用户、用户组以及企业项目授予OBS相关的细粒度策略后，大概需要等待5分钟细粒度策略才能生效。

## DMS自定义策略样例<a name="zh-cn_topic_0170877288_section7529733164812"></a>

-   示例1：授权用户删除实例和重启实例

    ```
    {
        "Version": "1.1",
        "Statement": [
            {
                "Effect": "Allow",
                "Action": [
                    "
                         dms:instance:delete
                         dms:instance:modifyStatus
                     "
                ]
            }
        ]
    }
    ```

-   示例2：拒绝用户删除实例

    拒绝策略需要同时配合其他策略使用，否则没有实际作用。用户被授予的策略中，一个授权项的作用如果同时存在Allow和Deny，则遵循Deny优先。

    如果您给用户授予DMS FullAccess的系统策略，但不希望用户拥有DMS FullAccess中定义的删除实例权限，您可以创建一条拒绝删除实例的自定义策略，然后同时将DMS FullAccess和拒绝策略授予用户，根据Deny优先原则，则用户可以对DMS for Kafka执行除了删除实例外的所有操作。拒绝策略示例如下：

    ```
    {
            "Version": "1.1",
            "Statement": [
                    {
                            "Effect": "Deny",
                            "Action": [
                                    "dms:instance:delete"
                            ]
                    }
            ]
    }
    ```


