# Kafka实例查询Topic<a name="kafka-api-180614002"></a>

>![](public_sys-resources/icon-note.gif) **说明：** 
>当前页面API为历史版本API，未来可能停止维护。请使用[Kafka实例查询Topic](Kafka实例查询Topic.md)。

## 功能介绍<a name="zh-cn_topic_0128036881_section281017251256"></a>

该接口用于查询指定Kafka实例的Topic详情。

## URI<a name="zh-cn_topic_0128036881_section153934371214"></a>

GET /v1.0/\{project\_id\}/instances/\{instance\_id\}/topics

参数说明见[表1](#zh-cn_topic_0128036881_table163952313129)。

**表 1**  参数说明

<a name="zh-cn_topic_0128036881_table163952313129"></a>
<table><thead align="left"><tr id="zh-cn_topic_0128036881_row2493193181217"><th class="cellrowborder" valign="top" width="16%" id="mcps1.2.5.1.1"><p id="zh-cn_topic_0128036881_p249343171215"><a name="zh-cn_topic_0128036881_p249343171215"></a><a name="zh-cn_topic_0128036881_p249343171215"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="13%" id="mcps1.2.5.1.2"><p id="zh-cn_topic_0128036881_p1549383101214"><a name="zh-cn_topic_0128036881_p1549383101214"></a><a name="zh-cn_topic_0128036881_p1549383101214"></a>类型</p>
</th>
<th class="cellrowborder" valign="top" width="12%" id="mcps1.2.5.1.3"><p id="zh-cn_topic_0128036881_p1249323141214"><a name="zh-cn_topic_0128036881_p1249323141214"></a><a name="zh-cn_topic_0128036881_p1249323141214"></a>必选</p>
</th>
<th class="cellrowborder" valign="top" width="59%" id="mcps1.2.5.1.4"><p id="zh-cn_topic_0128036881_p44932341212"><a name="zh-cn_topic_0128036881_p44932341212"></a><a name="zh-cn_topic_0128036881_p44932341212"></a>说明</p>
</th>
</tr>
</thead>
<tbody><tr id="zh-cn_topic_0128036881_row2493031124"><td class="cellrowborder" valign="top" width="16%" headers="mcps1.2.5.1.1 "><p id="zh-cn_topic_0128036881_p8493153191215"><a name="zh-cn_topic_0128036881_p8493153191215"></a><a name="zh-cn_topic_0128036881_p8493153191215"></a>project_id</p>
</td>
<td class="cellrowborder" valign="top" width="13%" headers="mcps1.2.5.1.2 "><p id="zh-cn_topic_0128036881_p18493103191215"><a name="zh-cn_topic_0128036881_p18493103191215"></a><a name="zh-cn_topic_0128036881_p18493103191215"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="12%" headers="mcps1.2.5.1.3 "><p id="zh-cn_topic_0128036881_p11493634127"><a name="zh-cn_topic_0128036881_p11493634127"></a><a name="zh-cn_topic_0128036881_p11493634127"></a>是</p>
</td>
<td class="cellrowborder" valign="top" width="59%" headers="mcps1.2.5.1.4 "><p id="zh-cn_topic_0128036881_p114938311210"><a name="zh-cn_topic_0128036881_p114938311210"></a><a name="zh-cn_topic_0128036881_p114938311210"></a>项目ID。</p>
</td>
</tr>
<tr id="zh-cn_topic_0128036881_row74931936127"><td class="cellrowborder" valign="top" width="16%" headers="mcps1.2.5.1.1 "><p id="zh-cn_topic_0128036881_p049393171212"><a name="zh-cn_topic_0128036881_p049393171212"></a><a name="zh-cn_topic_0128036881_p049393171212"></a>instance_id</p>
</td>
<td class="cellrowborder" valign="top" width="13%" headers="mcps1.2.5.1.2 "><p id="zh-cn_topic_0128036881_p1849319381212"><a name="zh-cn_topic_0128036881_p1849319381212"></a><a name="zh-cn_topic_0128036881_p1849319381212"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="12%" headers="mcps1.2.5.1.3 "><p id="zh-cn_topic_0128036881_p94938319125"><a name="zh-cn_topic_0128036881_p94938319125"></a><a name="zh-cn_topic_0128036881_p94938319125"></a>是</p>
</td>
<td class="cellrowborder" valign="top" width="59%" headers="mcps1.2.5.1.4 "><p id="zh-cn_topic_0128036881_p1949316301217"><a name="zh-cn_topic_0128036881_p1949316301217"></a><a name="zh-cn_topic_0128036881_p1949316301217"></a>实例ID</p>
</td>
</tr>
</tbody>
</table>

## 请求消息<a name="zh-cn_topic_0128036881_section540483191220"></a>

**请求参数**

无。

**请求示例**

无。

## 响应消息<a name="zh-cn_topic_0128036881_section1740614351212"></a>

**响应参数**

参数说明见[表2](#zh-cn_topic_0128036881_table2407333125)。

**表 2**  参数说明

<a name="zh-cn_topic_0128036881_table2407333125"></a>
<table><thead align="left"><tr id="zh-cn_topic_0128036881_row20493934122"><th class="cellrowborder" valign="top" width="23.23%" id="mcps1.2.4.1.1"><p id="zh-cn_topic_0128036881_p16493437123"><a name="zh-cn_topic_0128036881_p16493437123"></a><a name="zh-cn_topic_0128036881_p16493437123"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="22.220000000000002%" id="mcps1.2.4.1.2"><p id="zh-cn_topic_0128036881_p1849315317125"><a name="zh-cn_topic_0128036881_p1849315317125"></a><a name="zh-cn_topic_0128036881_p1849315317125"></a>类型</p>
</th>
<th class="cellrowborder" valign="top" width="54.55%" id="mcps1.2.4.1.3"><p id="zh-cn_topic_0128036881_p114931631122"><a name="zh-cn_topic_0128036881_p114931631122"></a><a name="zh-cn_topic_0128036881_p114931631122"></a>说明</p>
</th>
</tr>
</thead>
<tbody><tr id="row228343844"><td class="cellrowborder" valign="top" width="23.23%" headers="mcps1.2.4.1.1 "><p id="p1119016260425"><a name="p1119016260425"></a><a name="p1119016260425"></a>total</p>
</td>
<td class="cellrowborder" valign="top" width="22.220000000000002%" headers="mcps1.2.4.1.2 "><p id="p121919269427"><a name="p121919269427"></a><a name="p121919269427"></a>Integer</p>
</td>
<td class="cellrowborder" valign="top" width="54.55%" headers="mcps1.2.4.1.3 "><p id="p91911026124217"><a name="p91911026124217"></a><a name="p91911026124217"></a>topic总数。</p>
</td>
</tr>
<tr id="row1603517475"><td class="cellrowborder" valign="top" width="23.23%" headers="mcps1.2.4.1.1 "><p id="p3192102610426"><a name="p3192102610426"></a><a name="p3192102610426"></a>size</p>
</td>
<td class="cellrowborder" valign="top" width="22.220000000000002%" headers="mcps1.2.4.1.2 "><p id="p16192142684219"><a name="p16192142684219"></a><a name="p16192142684219"></a>Integer</p>
</td>
<td class="cellrowborder" valign="top" width="54.55%" headers="mcps1.2.4.1.3 "><p id="p919332614217"><a name="p919332614217"></a><a name="p919332614217"></a>分页查询的大小。</p>
</td>
</tr>
<tr id="row17199198124716"><td class="cellrowborder" valign="top" width="23.23%" headers="mcps1.2.4.1.1 "><p id="p13194172624219"><a name="p13194172624219"></a><a name="p13194172624219"></a>remain_partitions</p>
</td>
<td class="cellrowborder" valign="top" width="22.220000000000002%" headers="mcps1.2.4.1.2 "><p id="p319522611423"><a name="p319522611423"></a><a name="p319522611423"></a>Integer</p>
</td>
<td class="cellrowborder" valign="top" width="54.55%" headers="mcps1.2.4.1.3 "><p id="p21963261422"><a name="p21963261422"></a><a name="p21963261422"></a>剩余分区数。</p>
</td>
</tr>
<tr id="row48551820478"><td class="cellrowborder" valign="top" width="23.23%" headers="mcps1.2.4.1.1 "><p id="p181985264421"><a name="p181985264421"></a><a name="p181985264421"></a>max_partitions</p>
</td>
<td class="cellrowborder" valign="top" width="22.220000000000002%" headers="mcps1.2.4.1.2 "><p id="p419832613421"><a name="p419832613421"></a><a name="p419832613421"></a>Integer</p>
</td>
<td class="cellrowborder" valign="top" width="54.55%" headers="mcps1.2.4.1.3 "><p id="p1219918269421"><a name="p1219918269421"></a><a name="p1219918269421"></a>分区总数。</p>
</td>
</tr>
<tr id="zh-cn_topic_0128036881_row349318361214"><td class="cellrowborder" valign="top" width="23.23%" headers="mcps1.2.4.1.1 "><p id="zh-cn_topic_0128036881_p149316320122"><a name="zh-cn_topic_0128036881_p149316320122"></a><a name="zh-cn_topic_0128036881_p149316320122"></a>topics</p>
</td>
<td class="cellrowborder" valign="top" width="22.220000000000002%" headers="mcps1.2.4.1.2 "><p id="zh-cn_topic_0128036881_p1949514321211"><a name="zh-cn_topic_0128036881_p1949514321211"></a><a name="zh-cn_topic_0128036881_p1949514321211"></a>Array</p>
</td>
<td class="cellrowborder" valign="top" width="54.55%" headers="mcps1.2.4.1.3 "><p id="zh-cn_topic_0128036881_p144951938128"><a name="zh-cn_topic_0128036881_p144951938128"></a><a name="zh-cn_topic_0128036881_p144951938128"></a>Topic列表。</p>
</td>
</tr>
</tbody>
</table>

**表 3**  参数说明

<a name="zh-cn_topic_0128036881_table721516381617"></a>
<table><thead align="left"><tr id="zh-cn_topic_0128036881_row521819351615"><th class="cellrowborder" valign="top" width="23.23%" id="mcps1.2.4.1.1"><p id="zh-cn_topic_0128036881_p1421916319160"><a name="zh-cn_topic_0128036881_p1421916319160"></a><a name="zh-cn_topic_0128036881_p1421916319160"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="22.220000000000002%" id="mcps1.2.4.1.2"><p id="zh-cn_topic_0128036881_p19220193181611"><a name="zh-cn_topic_0128036881_p19220193181611"></a><a name="zh-cn_topic_0128036881_p19220193181611"></a>类型</p>
</th>
<th class="cellrowborder" valign="top" width="54.55%" id="mcps1.2.4.1.3"><p id="zh-cn_topic_0128036881_p42211734161"><a name="zh-cn_topic_0128036881_p42211734161"></a><a name="zh-cn_topic_0128036881_p42211734161"></a>说明</p>
</th>
</tr>
</thead>
<tbody><tr id="row177251838135014"><td class="cellrowborder" valign="top" width="23.23%" headers="mcps1.2.4.1.1 "><p id="p2205152611429"><a name="p2205152611429"></a><a name="p2205152611429"></a>policiesOnly</p>
</td>
<td class="cellrowborder" valign="top" width="22.220000000000002%" headers="mcps1.2.4.1.2 "><p id="p11206182610429"><a name="p11206182610429"></a><a name="p11206182610429"></a>Boolean</p>
</td>
<td class="cellrowborder" valign="top" width="54.55%" headers="mcps1.2.4.1.3 "><p id="p10206142616425"><a name="p10206142616425"></a><a name="p10206142616425"></a>是否为默认策略。</p>
</td>
</tr>
<tr id="zh-cn_topic_0128036881_row182259318164"><td class="cellrowborder" valign="top" width="23.23%" headers="mcps1.2.4.1.1 "><p id="zh-cn_topic_0128036881_p82278351616"><a name="zh-cn_topic_0128036881_p82278351616"></a><a name="zh-cn_topic_0128036881_p82278351616"></a>id</p>
</td>
<td class="cellrowborder" valign="top" width="22.220000000000002%" headers="mcps1.2.4.1.2 "><p id="zh-cn_topic_0128036881_p7227153111619"><a name="zh-cn_topic_0128036881_p7227153111619"></a><a name="zh-cn_topic_0128036881_p7227153111619"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="54.55%" headers="mcps1.2.4.1.3 "><p id="zh-cn_topic_0128036881_p52277361617"><a name="zh-cn_topic_0128036881_p52277361617"></a><a name="zh-cn_topic_0128036881_p52277361617"></a>Topic名称</p>
</td>
</tr>
<tr id="row17458933085"><td class="cellrowborder" valign="top" width="23.23%" headers="mcps1.2.4.1.1 "><p id="zh-cn_topic_0128036881_p723243121615"><a name="zh-cn_topic_0128036881_p723243121615"></a><a name="zh-cn_topic_0128036881_p723243121615"></a>replication</p>
</td>
<td class="cellrowborder" valign="top" width="22.220000000000002%" headers="mcps1.2.4.1.2 "><p id="zh-cn_topic_0128036881_p52321939169"><a name="zh-cn_topic_0128036881_p52321939169"></a><a name="zh-cn_topic_0128036881_p52321939169"></a>Integer</p>
</td>
<td class="cellrowborder" valign="top" width="54.55%" headers="mcps1.2.4.1.3 "><p id="zh-cn_topic_0128036881_p52349310161"><a name="zh-cn_topic_0128036881_p52349310161"></a><a name="zh-cn_topic_0128036881_p52349310161"></a>副本数，配置数据的可靠性</p>
</td>
</tr>
<tr id="zh-cn_topic_0128036881_row622718313161"><td class="cellrowborder" valign="top" width="23.23%" headers="mcps1.2.4.1.1 "><p id="zh-cn_topic_0128036881_p132281318163"><a name="zh-cn_topic_0128036881_p132281318163"></a><a name="zh-cn_topic_0128036881_p132281318163"></a>partition</p>
</td>
<td class="cellrowborder" valign="top" width="22.220000000000002%" headers="mcps1.2.4.1.2 "><p id="zh-cn_topic_0128036881_p92304331618"><a name="zh-cn_topic_0128036881_p92304331618"></a><a name="zh-cn_topic_0128036881_p92304331618"></a>Integer</p>
</td>
<td class="cellrowborder" valign="top" width="54.55%" headers="mcps1.2.4.1.3 "><p id="zh-cn_topic_0128036881_p1023023101615"><a name="zh-cn_topic_0128036881_p1023023101615"></a><a name="zh-cn_topic_0128036881_p1023023101615"></a>Topic分区数，设置消费的并发数。</p>
</td>
</tr>
<tr id="zh-cn_topic_0128036881_row102302321617"><td class="cellrowborder" valign="top" width="23.23%" headers="mcps1.2.4.1.1 "><p id="zh-cn_topic_0128036881_p1423419319167"><a name="zh-cn_topic_0128036881_p1423419319167"></a><a name="zh-cn_topic_0128036881_p1423419319167"></a>retention_time</p>
</td>
<td class="cellrowborder" valign="top" width="22.220000000000002%" headers="mcps1.2.4.1.2 "><p id="zh-cn_topic_0128036881_p1023616315167"><a name="zh-cn_topic_0128036881_p1023616315167"></a><a name="zh-cn_topic_0128036881_p1023616315167"></a>Integer</p>
</td>
<td class="cellrowborder" valign="top" width="54.55%" headers="mcps1.2.4.1.3 "><p id="zh-cn_topic_0128036881_p1923619351613"><a name="zh-cn_topic_0128036881_p1923619351613"></a><a name="zh-cn_topic_0128036881_p1923619351613"></a>消息老化时间。</p>
</td>
</tr>
<tr id="zh-cn_topic_0128036881_row1994501616482"><td class="cellrowborder" valign="top" width="23.23%" headers="mcps1.2.4.1.1 "><p id="zh-cn_topic_0128036881_p126894217446"><a name="zh-cn_topic_0128036881_p126894217446"></a><a name="zh-cn_topic_0128036881_p126894217446"></a>sync_replication</p>
</td>
<td class="cellrowborder" valign="top" width="22.220000000000002%" headers="mcps1.2.4.1.2 "><p id="zh-cn_topic_0128036881_p12681342184417"><a name="zh-cn_topic_0128036881_p12681342184417"></a><a name="zh-cn_topic_0128036881_p12681342184417"></a>Boolean</p>
</td>
<td class="cellrowborder" valign="top" width="54.55%" headers="mcps1.2.4.1.3 "><p id="zh-cn_topic_0128036881_p62689423441"><a name="zh-cn_topic_0128036881_p62689423441"></a><a name="zh-cn_topic_0128036881_p62689423441"></a>是否开启同步复制，开启后，客户端生产消息时相应的也要设置acks=-1，否则不生效。</p>
<p id="zh-cn_topic_0128036881_p192687429448"><a name="zh-cn_topic_0128036881_p192687429448"></a><a name="zh-cn_topic_0128036881_p192687429448"></a>默认关闭。</p>
</td>
</tr>
<tr id="zh-cn_topic_0128036881_row62340310167"><td class="cellrowborder" valign="top" width="23.23%" headers="mcps1.2.4.1.1 "><p id="zh-cn_topic_0128036881_p1123719314161"><a name="zh-cn_topic_0128036881_p1123719314161"></a><a name="zh-cn_topic_0128036881_p1123719314161"></a>sync_message_flush</p>
</td>
<td class="cellrowborder" valign="top" width="22.220000000000002%" headers="mcps1.2.4.1.2 "><p id="zh-cn_topic_0128036881_p3237235167"><a name="zh-cn_topic_0128036881_p3237235167"></a><a name="zh-cn_topic_0128036881_p3237235167"></a>Boolean</p>
</td>
<td class="cellrowborder" valign="top" width="54.55%" headers="mcps1.2.4.1.3 "><p id="zh-cn_topic_0128036881_p1923911315167"><a name="zh-cn_topic_0128036881_p1923911315167"></a><a name="zh-cn_topic_0128036881_p1923911315167"></a>是否使用同步落盘。同步落盘会导致性能降低。</p>
</td>
</tr>
<tr id="row177601528105014"><td class="cellrowborder" valign="top" width="23.23%" headers="mcps1.2.4.1.1 "><p id="p1216426184219"><a name="p1216426184219"></a><a name="p1216426184219"></a>external_configs</p>
</td>
<td class="cellrowborder" valign="top" width="22.220000000000002%" headers="mcps1.2.4.1.2 "><p id="p10217526154219"><a name="p10217526154219"></a><a name="p10217526154219"></a>Object</p>
</td>
<td class="cellrowborder" valign="top" width="54.55%" headers="mcps1.2.4.1.3 "><p id="p18217526114211"><a name="p18217526114211"></a><a name="p18217526114211"></a>扩展配置。</p>
</td>
</tr>
<tr id="row1252633216502"><td class="cellrowborder" valign="top" width="23.23%" headers="mcps1.2.4.1.1 "><p id="p19218112674216"><a name="p19218112674216"></a><a name="p19218112674216"></a>topic_type</p>
</td>
<td class="cellrowborder" valign="top" width="22.220000000000002%" headers="mcps1.2.4.1.2 "><p id="p921882654212"><a name="p921882654212"></a><a name="p921882654212"></a>Integer</p>
</td>
<td class="cellrowborder" valign="top" width="54.55%" headers="mcps1.2.4.1.3 "><p id="p192181926104210"><a name="p192181926104210"></a><a name="p192181926104210"></a>topic类型。</p>
</td>
</tr>
</tbody>
</table>

**响应示例**

```
{
 "count": 1,
 "topics": [
  {
   "id": "topic-test",
   "replication": 3,
   "partition": 4,
   "retention_time": 72,
   "sync_replication": "false",
   "sync_message_flush": "false"
  }
 ]
}
```

## 状态码<a name="zh-cn_topic_0128036881_section17430153151212"></a>

操作成功的状态码如[表4](#zh-cn_topic_0128036881_table64308351212)所示，其他响应见[状态码](状态码.md)。

**表 4**  状态码

<a name="zh-cn_topic_0128036881_table64308351212"></a>
<table><thead align="left"><tr id="zh-cn_topic_0128036881_row204961735122"><th class="cellrowborder" valign="top" width="15.15%" id="mcps1.2.3.1.1"><p id="zh-cn_topic_0128036881_p3496133121"><a name="zh-cn_topic_0128036881_p3496133121"></a><a name="zh-cn_topic_0128036881_p3496133121"></a>状态码</p>
</th>
<th class="cellrowborder" valign="top" width="84.85000000000001%" id="mcps1.2.3.1.2"><p id="zh-cn_topic_0128036881_p0496103161220"><a name="zh-cn_topic_0128036881_p0496103161220"></a><a name="zh-cn_topic_0128036881_p0496103161220"></a>描述</p>
</th>
</tr>
</thead>
<tbody><tr id="zh-cn_topic_0128036881_row949618381217"><td class="cellrowborder" valign="top" width="15.15%" headers="mcps1.2.3.1.1 "><p id="zh-cn_topic_0128036881_p849618371213"><a name="zh-cn_topic_0128036881_p849618371213"></a><a name="zh-cn_topic_0128036881_p849618371213"></a>200</p>
</td>
<td class="cellrowborder" valign="top" width="84.85000000000001%" headers="mcps1.2.3.1.2 "><p id="zh-cn_topic_0128036881_p24961391213"><a name="zh-cn_topic_0128036881_p24961391213"></a><a name="zh-cn_topic_0128036881_p24961391213"></a>查询成功。</p>
</td>
</tr>
</tbody>
</table>

