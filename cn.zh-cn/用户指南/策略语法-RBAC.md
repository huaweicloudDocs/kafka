# 策略语法：RBAC<a name="ZH-CN_TOPIC_0171717055"></a>

## 策略语法<a name="zh-cn_topic_0171356249_section9359105292516"></a>

给用户组选择策略时，单击策略下方的![](figures/zh-cn_image_0171717672.png)，可以查看策略的详细内容，以“DMS Administraor”为例，说明RBAC策略的语法。

![](figures/zh-cn_image_0171817324.png)

```
{
        "Version": "1.0",
        "Statement": [
                {
                        "Effect": "Allow",
                        "Action": [
                                "DMS:Queue:*",
                                "DMS:Consumer_Group:*",
                                "DMS:Message:*",
                                "DMS:Quota:*"
                        ]
                }
        ]
}
```

## 参数说明<a name="zh-cn_topic_0171356249_section1057124415300"></a>

-   Version：策略的版本号，RBAC策略版本为“1.0”，细粒度策略版本为“1.1”。

-   Statement：策略的授权语句，包含Action（授权项）和Effect（作用），Action和Effect结合构成用户具备的权限。
    -   Action（授权项）：操作权限，格式为：服务名:资源类型:操作

        "DMS:Queue:\*"：表示对DMS的所有操作，其中DMS为服务名；“\*”为通配符，表示对DMS队列可以执行所有操作。

    -   Effect（作用）：定义Action中的操作权限是否允许执行。Allow：允许；Deny：拒绝。

-   Depends：策略的依赖关系，给用户组授予该策略时，需要同时勾选依赖的权限，否则该策略不会生效。
    -   catalog：依赖的策略的所属服务。
    -   display\_name：依赖的策略的名称。


