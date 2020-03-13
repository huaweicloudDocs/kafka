# 新增Kafka实例指定Topic分区<a name="ZH-CN_TOPIC_0210486912"></a>

## URI<a name="section12435153735914"></a>

POST /v1.0/\{project\_id\}/instances/\{instance\_id\}/manage/topics/\{topic\}/partitions-reassignment

参数说明如下表所示。

**表 1**  参数说明

<a name="table3831205210475"></a>
<table><thead align="left"><tr id="row1283245214472"><th class="cellrowborder" valign="top" width="19.388061193880613%" id="mcps1.2.5.1.1"><p id="p783211525471"><a name="p783211525471"></a><a name="p783211525471"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="15.308469153084694%" id="mcps1.2.5.1.2"><p id="p4832152184716"><a name="p4832152184716"></a><a name="p4832152184716"></a>类型</p>
</th>
<th class="cellrowborder" valign="top" width="14.288571142885711%" id="mcps1.2.5.1.3"><p id="p1283285264711"><a name="p1283285264711"></a><a name="p1283285264711"></a>必选</p>
</th>
<th class="cellrowborder" valign="top" width="51.01489851014899%" id="mcps1.2.5.1.4"><p id="p128321952134718"><a name="p128321952134718"></a><a name="p128321952134718"></a>说明</p>
</th>
</tr>
</thead>
<tbody><tr id="row9832452174711"><td class="cellrowborder" valign="top" width="19.388061193880613%" headers="mcps1.2.5.1.1 "><p id="p1983285294711"><a name="p1983285294711"></a><a name="p1983285294711"></a>project_id</p>
</td>
<td class="cellrowborder" valign="top" width="15.308469153084694%" headers="mcps1.2.5.1.2 "><p id="p1183235254710"><a name="p1183235254710"></a><a name="p1183235254710"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="14.288571142885711%" headers="mcps1.2.5.1.3 "><p id="p1883245210475"><a name="p1883245210475"></a><a name="p1883245210475"></a>是</p>
</td>
<td class="cellrowborder" valign="top" width="51.01489851014899%" headers="mcps1.2.5.1.4 "><p id="p98322520472"><a name="p98322520472"></a><a name="p98322520472"></a>项目ID。</p>
</td>
</tr>
<tr id="row88326521473"><td class="cellrowborder" valign="top" width="19.388061193880613%" headers="mcps1.2.5.1.1 "><p id="p14832195204710"><a name="p14832195204710"></a><a name="p14832195204710"></a>instance_id</p>
</td>
<td class="cellrowborder" valign="top" width="15.308469153084694%" headers="mcps1.2.5.1.2 "><p id="p6832115204712"><a name="p6832115204712"></a><a name="p6832115204712"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="14.288571142885711%" headers="mcps1.2.5.1.3 "><p id="p10832352124714"><a name="p10832352124714"></a><a name="p10832352124714"></a>是</p>
</td>
<td class="cellrowborder" valign="top" width="51.01489851014899%" headers="mcps1.2.5.1.4 "><p id="p19832115274718"><a name="p19832115274718"></a><a name="p19832115274718"></a>实例ID。</p>
</td>
</tr>
<tr id="row6832752114711"><td class="cellrowborder" valign="top" width="19.388061193880613%" headers="mcps1.2.5.1.1 "><p id="p1783214520474"><a name="p1783214520474"></a><a name="p1783214520474"></a>topic</p>
</td>
<td class="cellrowborder" valign="top" width="15.308469153084694%" headers="mcps1.2.5.1.2 "><p id="p28321452164717"><a name="p28321452164717"></a><a name="p28321452164717"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="14.288571142885711%" headers="mcps1.2.5.1.3 "><p id="p1883225214713"><a name="p1883225214713"></a><a name="p1883225214713"></a>是</p>
</td>
<td class="cellrowborder" valign="top" width="51.01489851014899%" headers="mcps1.2.5.1.4 "><p id="p6832952194719"><a name="p6832952194719"></a><a name="p6832952194719"></a>Topic名称。</p>
</td>
</tr>
</tbody>
</table>

## 请求消息<a name="section204361137195920"></a>

**请求参数**

**表 2**  参数说明

<a name="table10437143775918"></a>
<table><thead align="left"><tr id="row35071537175917"><th class="cellrowborder" valign="top" width="19.388061193880613%" id="mcps1.2.5.1.1"><p id="p1150803719591"><a name="p1150803719591"></a><a name="p1150803719591"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="15.308469153084694%" id="mcps1.2.5.1.2"><p id="p7508163725910"><a name="p7508163725910"></a><a name="p7508163725910"></a>类型</p>
</th>
<th class="cellrowborder" valign="top" width="14.288571142885711%" id="mcps1.2.5.1.3"><p id="p750818379597"><a name="p750818379597"></a><a name="p750818379597"></a>必选</p>
</th>
<th class="cellrowborder" valign="top" width="51.01489851014899%" id="mcps1.2.5.1.4"><p id="p250843711599"><a name="p250843711599"></a><a name="p250843711599"></a>说明</p>
</th>
</tr>
</thead>
<tbody><tr id="row6508173765915"><td class="cellrowborder" valign="top" width="19.388061193880613%" headers="mcps1.2.5.1.1 "><p id="p16508123710592"><a name="p16508123710592"></a><a name="p16508123710592"></a>partition</p>
</td>
<td class="cellrowborder" valign="top" width="15.308469153084694%" headers="mcps1.2.5.1.2 "><p id="p115081937115913"><a name="p115081937115913"></a><a name="p115081937115913"></a>Integer</p>
</td>
<td class="cellrowborder" valign="top" width="14.288571142885711%" headers="mcps1.2.5.1.3 "><p id="p145086370592"><a name="p145086370592"></a><a name="p145086370592"></a>是</p>
</td>
<td class="cellrowborder" valign="top" width="51.01489851014899%" headers="mcps1.2.5.1.4 "><p id="p95084372593"><a name="p95084372593"></a><a name="p95084372593"></a>期望调整分区后的数量，必须大于当前分区数量，小于等于20。</p>
</td>
</tr>
</tbody>
</table>

**请求示例**

```
{
    "partition": 3
}
```

## 响应消息<a name="section114491837175910"></a>

**响应参数**

无

**响应示例**

无

## 状态码<a name="section3449163715916"></a>

操作成功的状态码。

**表 3**  状态码

<a name="table545012370590"></a>
<table><thead align="left"><tr id="row5509193795911"><th class="cellrowborder" valign="top" width="15.15%" id="mcps1.2.3.1.1"><p id="p16509103714590"><a name="p16509103714590"></a><a name="p16509103714590"></a>状态码</p>
</th>
<th class="cellrowborder" valign="top" width="84.85000000000001%" id="mcps1.2.3.1.2"><p id="p5509113714597"><a name="p5509113714597"></a><a name="p5509113714597"></a>描述</p>
</th>
</tr>
</thead>
<tbody><tr id="row950903775910"><td class="cellrowborder" valign="top" width="15.15%" headers="mcps1.2.3.1.1 "><p id="p10509113711590"><a name="p10509113711590"></a><a name="p10509113711590"></a>204</p>
</td>
<td class="cellrowborder" valign="top" width="84.85000000000001%" headers="mcps1.2.3.1.2 "><p id="p145091537125911"><a name="p145091537125911"></a><a name="p145091537125911"></a>新增分区操作成功。</p>
</td>
</tr>
</tbody>
</table>

