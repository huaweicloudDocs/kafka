# 重置Kafka Manager密码<a name="kafka-ug-190131001"></a>

## 操作场景<a name="section33628036"></a>

如果您忘记了创建实例时设置的Kafka Manager密码，通过重置Manager密码功能，重新设置一个新的密码，可使用新密码登录Kafka Manager。

>![](public_sys-resources/icon-note.gif) **说明：** 
>只有处于“运行中”状态的Kafka专享实例支持重置Manager密码。

## 前提条件<a name="section34216874"></a>

已成功创建Kafka专享实例。

## 操作步骤<a name="section12258217288"></a>

1.  登录管理控制台。
2.  在管理控制台左上角单击![](figures/icon-region.png)，选择区域。

    >![](public_sys-resources/icon-note.gif) **说明：** 
    >此处请选择与您的应用服务相同的区域。

3.  在管理控制台左上角单击![](figures/icon-list.png)，选择“应用中间件 \> 分布式消息服务Kafka版”，进入分布式消息服务Kafka专享版页面。
4.  在需要重置Manager密码的Kafka专享实例右侧，单击“更多 \> 重置Manager密码”，弹出“重置Manager密码”对话框。
5.  输入“新密码”和“确认密码”。
6.  单击“确定”，完成密码重置。

    -   重置Manager密码成功，界面提示重置实例的密码成功。
    -   重置Manager密码失败，界面提示重置实例的密码失败，请重新尝试重置密码操作。如果多次重置失败，请联系客服处理。

    >![](public_sys-resources/icon-note.gif) **说明：** 
    >只有所有代理都重置密码成功，系统才会提示重置密码成功，否则会提示重置失败。


