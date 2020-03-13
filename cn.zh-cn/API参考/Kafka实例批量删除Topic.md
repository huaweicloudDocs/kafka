# Kafka实例批量删除Topic<a name="ZH-CN_TOPIC_0171829503"></a>

## 功能介绍<a name="zh-cn_topic_0128036887_section281017251256"></a>

该接口用于向Kafka实例批量删除Topic。

## URI<a name="zh-cn_topic_0128036887_section2989194312512"></a>

POST /v1.0/\{project\_id\}/instances/\{instance\_id\}/topics/delete

参数说明见[表1](#zh-cn_topic_0128036887_table999074314516)。

**表 1**  参数说明

<a name="zh-cn_topic_0128036887_table999074314516"></a>
<table><thead align="left"><tr id="zh-cn_topic_0128036887_row1611514441455"><th class="cellrowborder" valign="top" width="16%" id="mcps1.2.5.1.1"><p id="zh-cn_topic_0128036887_p121151744458"><a name="zh-cn_topic_0128036887_p121151744458"></a><a name="zh-cn_topic_0128036887_p121151744458"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="13%" id="mcps1.2.5.1.2"><p id="zh-cn_topic_0128036887_p7115114415513"><a name="zh-cn_topic_0128036887_p7115114415513"></a><a name="zh-cn_topic_0128036887_p7115114415513"></a>类型</p>
</th>
<th class="cellrowborder" valign="top" width="12%" id="mcps1.2.5.1.3"><p id="zh-cn_topic_0128036887_p111517441957"><a name="zh-cn_topic_0128036887_p111517441957"></a><a name="zh-cn_topic_0128036887_p111517441957"></a>必选</p>
</th>
<th class="cellrowborder" valign="top" width="59%" id="mcps1.2.5.1.4"><p id="zh-cn_topic_0128036887_p6115174418512"><a name="zh-cn_topic_0128036887_p6115174418512"></a><a name="zh-cn_topic_0128036887_p6115174418512"></a>说明</p>
</th>
</tr>
</thead>
<tbody><tr id="zh-cn_topic_0128036887_row121155447517"><td class="cellrowborder" valign="top" width="16%" headers="mcps1.2.5.1.1 "><p id="zh-cn_topic_0128036887_p15115944853"><a name="zh-cn_topic_0128036887_p15115944853"></a><a name="zh-cn_topic_0128036887_p15115944853"></a>project_id</p>
</td>
<td class="cellrowborder" valign="top" width="13%" headers="mcps1.2.5.1.2 "><p id="zh-cn_topic_0128036887_p17115244354"><a name="zh-cn_topic_0128036887_p17115244354"></a><a name="zh-cn_topic_0128036887_p17115244354"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="12%" headers="mcps1.2.5.1.3 "><p id="zh-cn_topic_0128036887_p161154441252"><a name="zh-cn_topic_0128036887_p161154441252"></a><a name="zh-cn_topic_0128036887_p161154441252"></a>是</p>
</td>
<td class="cellrowborder" valign="top" width="59%" headers="mcps1.2.5.1.4 "><p id="zh-cn_topic_0128036887_p8115134420510"><a name="zh-cn_topic_0128036887_p8115134420510"></a><a name="zh-cn_topic_0128036887_p8115134420510"></a>项目ID。</p>
</td>
</tr>
<tr id="zh-cn_topic_0128036887_row171159441358"><td class="cellrowborder" valign="top" width="16%" headers="mcps1.2.5.1.1 "><p id="zh-cn_topic_0128036887_p12117204415518"><a name="zh-cn_topic_0128036887_p12117204415518"></a><a name="zh-cn_topic_0128036887_p12117204415518"></a>instance_id</p>
</td>
<td class="cellrowborder" valign="top" width="13%" headers="mcps1.2.5.1.2 "><p id="zh-cn_topic_0128036887_p411717442510"><a name="zh-cn_topic_0128036887_p411717442510"></a><a name="zh-cn_topic_0128036887_p411717442510"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="12%" headers="mcps1.2.5.1.3 "><p id="zh-cn_topic_0128036887_p111784412519"><a name="zh-cn_topic_0128036887_p111784412519"></a><a name="zh-cn_topic_0128036887_p111784412519"></a>是</p>
</td>
<td class="cellrowborder" valign="top" width="59%" headers="mcps1.2.5.1.4 "><p id="zh-cn_topic_0128036887_p1911784411513"><a name="zh-cn_topic_0128036887_p1911784411513"></a><a name="zh-cn_topic_0128036887_p1911784411513"></a>实例ID</p>
</td>
</tr>
</tbody>
</table>

## 请求消息<a name="zh-cn_topic_0128036887_section101441458"></a>

**请求参数**

参数说明见[表2](#zh-cn_topic_0128036887_table192144257)。

**表 2**  参数说明

<a name="zh-cn_topic_0128036887_table192144257"></a>
<table><thead align="left"><tr id="zh-cn_topic_0128036887_row141190441157"><th class="cellrowborder" valign="top" width="15%" id="mcps1.2.5.1.1"><p id="zh-cn_topic_0128036887_p11191144155"><a name="zh-cn_topic_0128036887_p11191144155"></a><a name="zh-cn_topic_0128036887_p11191144155"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="20%" id="mcps1.2.5.1.2"><p id="zh-cn_topic_0128036887_p61195448514"><a name="zh-cn_topic_0128036887_p61195448514"></a><a name="zh-cn_topic_0128036887_p61195448514"></a>类型</p>
</th>
<th class="cellrowborder" valign="top" width="12%" id="mcps1.2.5.1.3"><p id="zh-cn_topic_0128036887_p11119104414518"><a name="zh-cn_topic_0128036887_p11119104414518"></a><a name="zh-cn_topic_0128036887_p11119104414518"></a>是否必选</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.2.5.1.4"><p id="zh-cn_topic_0128036887_p111915441953"><a name="zh-cn_topic_0128036887_p111915441953"></a><a name="zh-cn_topic_0128036887_p111915441953"></a>说明</p>
</th>
</tr>
</thead>
<tbody><tr id="zh-cn_topic_0128036887_row1911984410515"><td class="cellrowborder" valign="top" width="15%" headers="mcps1.2.5.1.1 "><p id="zh-cn_topic_0128036887_p8119154410515"><a name="zh-cn_topic_0128036887_p8119154410515"></a><a name="zh-cn_topic_0128036887_p8119154410515"></a>topics</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.5.1.2 "><p id="zh-cn_topic_0128036887_p5119154417519"><a name="zh-cn_topic_0128036887_p5119154417519"></a><a name="zh-cn_topic_0128036887_p5119154417519"></a>Array</p>
</td>
<td class="cellrowborder" valign="top" width="12%" headers="mcps1.2.5.1.3 "><p id="zh-cn_topic_0128036887_p51191544556"><a name="zh-cn_topic_0128036887_p51191544556"></a><a name="zh-cn_topic_0128036887_p51191544556"></a>是</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.2.5.1.4 "><p id="zh-cn_topic_0128036887_p51191844655"><a name="zh-cn_topic_0128036887_p51191844655"></a><a name="zh-cn_topic_0128036887_p51191844655"></a>待删除的topic列表</p>
</td>
</tr>
</tbody>
</table>

**请求示例**

```
 {
  "topics" : ["hah", "aabb"]
 }
```

## 响应消息<a name="zh-cn_topic_0128036887_section19101644156"></a>

**响应参数**

参数说明见[表3](#zh-cn_topic_0128036887_table10111744455)。

**表 3**  参数说明

<a name="zh-cn_topic_0128036887_table10111744455"></a>
<table><thead align="left"><tr id="zh-cn_topic_0128036887_row41192441858"><th class="cellrowborder" valign="top" width="23.23%" id="mcps1.2.4.1.1"><p id="zh-cn_topic_0128036887_p121201944354"><a name="zh-cn_topic_0128036887_p121201944354"></a><a name="zh-cn_topic_0128036887_p121201944354"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="22.220000000000002%" id="mcps1.2.4.1.2"><p id="zh-cn_topic_0128036887_p1812011441515"><a name="zh-cn_topic_0128036887_p1812011441515"></a><a name="zh-cn_topic_0128036887_p1812011441515"></a>类型</p>
</th>
<th class="cellrowborder" valign="top" width="54.55%" id="mcps1.2.4.1.3"><p id="zh-cn_topic_0128036887_p51207446518"><a name="zh-cn_topic_0128036887_p51207446518"></a><a name="zh-cn_topic_0128036887_p51207446518"></a>说明</p>
</th>
</tr>
</thead>
<tbody><tr id="zh-cn_topic_0128036887_row15120184418519"><td class="cellrowborder" valign="top" width="23.23%" headers="mcps1.2.4.1.1 "><p id="zh-cn_topic_0128036887_p1112013442053"><a name="zh-cn_topic_0128036887_p1112013442053"></a><a name="zh-cn_topic_0128036887_p1112013442053"></a>topics</p>
</td>
<td class="cellrowborder" valign="top" width="22.220000000000002%" headers="mcps1.2.4.1.2 "><p id="zh-cn_topic_0128036887_p1812019441651"><a name="zh-cn_topic_0128036887_p1812019441651"></a><a name="zh-cn_topic_0128036887_p1812019441651"></a>Array</p>
</td>
<td class="cellrowborder" valign="top" width="54.55%" headers="mcps1.2.4.1.3 "><p id="zh-cn_topic_0128036887_p10120244959"><a name="zh-cn_topic_0128036887_p10120244959"></a><a name="zh-cn_topic_0128036887_p10120244959"></a>Topic列表</p>
</td>
</tr>
</tbody>
</table>

**表 4**  topics参数说明

<a name="zh-cn_topic_0128036887_table046213306109"></a>
<table><thead align="left"><tr id="zh-cn_topic_0128036887_row2046612306104"><th class="cellrowborder" valign="top" width="23.23%" id="mcps1.2.4.1.1"><p id="zh-cn_topic_0128036887_p1646783041010"><a name="zh-cn_topic_0128036887_p1646783041010"></a><a name="zh-cn_topic_0128036887_p1646783041010"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="22.220000000000002%" id="mcps1.2.4.1.2"><p id="zh-cn_topic_0128036887_p9468113091015"><a name="zh-cn_topic_0128036887_p9468113091015"></a><a name="zh-cn_topic_0128036887_p9468113091015"></a>类型</p>
</th>
<th class="cellrowborder" valign="top" width="54.55%" id="mcps1.2.4.1.3"><p id="zh-cn_topic_0128036887_p1846903011104"><a name="zh-cn_topic_0128036887_p1846903011104"></a><a name="zh-cn_topic_0128036887_p1846903011104"></a>说明</p>
</th>
</tr>
</thead>
<tbody><tr id="zh-cn_topic_0128036887_row64765308104"><td class="cellrowborder" valign="top" width="23.23%" headers="mcps1.2.4.1.1 "><p id="zh-cn_topic_0128036887_p347823071014"><a name="zh-cn_topic_0128036887_p347823071014"></a><a name="zh-cn_topic_0128036887_p347823071014"></a>id</p>
</td>
<td class="cellrowborder" valign="top" width="22.220000000000002%" headers="mcps1.2.4.1.2 "><p id="zh-cn_topic_0128036887_p15479730111010"><a name="zh-cn_topic_0128036887_p15479730111010"></a><a name="zh-cn_topic_0128036887_p15479730111010"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="54.55%" headers="mcps1.2.4.1.3 "><p id="zh-cn_topic_0128036887_p848023015100"><a name="zh-cn_topic_0128036887_p848023015100"></a><a name="zh-cn_topic_0128036887_p848023015100"></a>Topic名称</p>
</td>
</tr>
<tr id="zh-cn_topic_0128036887_row248183016109"><td class="cellrowborder" valign="top" width="23.23%" headers="mcps1.2.4.1.1 "><p id="zh-cn_topic_0128036887_p19482163018103"><a name="zh-cn_topic_0128036887_p19482163018103"></a><a name="zh-cn_topic_0128036887_p19482163018103"></a>success</p>
</td>
<td class="cellrowborder" valign="top" width="22.220000000000002%" headers="mcps1.2.4.1.2 "><p id="zh-cn_topic_0128036887_p3483153041011"><a name="zh-cn_topic_0128036887_p3483153041011"></a><a name="zh-cn_topic_0128036887_p3483153041011"></a>Boolean</p>
</td>
<td class="cellrowborder" valign="top" width="54.55%" headers="mcps1.2.4.1.3 "><p id="zh-cn_topic_0128036887_p1348413061012"><a name="zh-cn_topic_0128036887_p1348413061012"></a><a name="zh-cn_topic_0128036887_p1348413061012"></a>是否删除成功。</p>
</td>
</tr>
</tbody>
</table>

**响应示例**

```
{
  "topics" : [{
      "id" : "haha",
      "success" : true
    }, {
      "id" : "aabb",
      "success" : true
    }
  ]
}
```

## 状态码<a name="zh-cn_topic_0128036887_section92216442511"></a>

操作成功的状态码如[表5](#zh-cn_topic_0128036887_table6231844656)所示，其他响应见[状态码](状态码.md)。

**表 5**  状态码

<a name="zh-cn_topic_0128036887_table6231844656"></a>
<table><thead align="left"><tr id="zh-cn_topic_0128036887_row1512019448511"><th class="cellrowborder" valign="top" width="15.15%" id="mcps1.2.3.1.1"><p id="zh-cn_topic_0128036887_p1120144453"><a name="zh-cn_topic_0128036887_p1120144453"></a><a name="zh-cn_topic_0128036887_p1120144453"></a>状态码</p>
</th>
<th class="cellrowborder" valign="top" width="84.85000000000001%" id="mcps1.2.3.1.2"><p id="zh-cn_topic_0128036887_p2012019445514"><a name="zh-cn_topic_0128036887_p2012019445514"></a><a name="zh-cn_topic_0128036887_p2012019445514"></a>描述</p>
</th>
</tr>
</thead>
<tbody><tr id="zh-cn_topic_0128036887_row912012447517"><td class="cellrowborder" valign="top" width="15.15%" headers="mcps1.2.3.1.1 "><p id="zh-cn_topic_0128036887_p912044411514"><a name="zh-cn_topic_0128036887_p912044411514"></a><a name="zh-cn_topic_0128036887_p912044411514"></a>200</p>
</td>
<td class="cellrowborder" valign="top" width="84.85000000000001%" headers="mcps1.2.3.1.2 "><p id="zh-cn_topic_0128036887_p71201441758"><a name="zh-cn_topic_0128036887_p71201441758"></a><a name="zh-cn_topic_0128036887_p71201441758"></a>删除成功。</p>
</td>
</tr>
</tbody>
</table>

