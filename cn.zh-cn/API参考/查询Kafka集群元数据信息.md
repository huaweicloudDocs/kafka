# 查询Kafka集群元数据信息<a name="ZH-CN_TOPIC_0210486906"></a>

## URI<a name="section1445760195713"></a>

GET  /v1.0/\{project\_id\}/instances/\{instance\_id\}/manage/cluster

参数说明如下表所示。

**表 1**  参数说明

<a name="table94611103578"></a>
<table><thead align="left"><tr id="row89131500579"><th class="cellrowborder" valign="top" width="18.36816318368163%" id="mcps1.2.5.1.1"><p id="p191310025718"><a name="p191310025718"></a><a name="p191310025718"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="14.288571142885711%" id="mcps1.2.5.1.2"><p id="p0913703575"><a name="p0913703575"></a><a name="p0913703575"></a>类型</p>
</th>
<th class="cellrowborder" valign="top" width="13.268673132686734%" id="mcps1.2.5.1.3"><p id="p791313055715"><a name="p791313055715"></a><a name="p791313055715"></a>必选</p>
</th>
<th class="cellrowborder" valign="top" width="54.074592540745925%" id="mcps1.2.5.1.4"><p id="p179139055712"><a name="p179139055712"></a><a name="p179139055712"></a>说明</p>
</th>
</tr>
</thead>
<tbody><tr id="row199134017576"><td class="cellrowborder" valign="top" width="18.36816318368163%" headers="mcps1.2.5.1.1 "><p id="p99131045719"><a name="p99131045719"></a><a name="p99131045719"></a>project_id</p>
</td>
<td class="cellrowborder" valign="top" width="14.288571142885711%" headers="mcps1.2.5.1.2 "><p id="p89131014579"><a name="p89131014579"></a><a name="p89131014579"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="13.268673132686734%" headers="mcps1.2.5.1.3 "><p id="p209138016572"><a name="p209138016572"></a><a name="p209138016572"></a>是</p>
</td>
<td class="cellrowborder" valign="top" width="54.074592540745925%" headers="mcps1.2.5.1.4 "><p id="p149138019570"><a name="p149138019570"></a><a name="p149138019570"></a>项目ID。</p>
</td>
</tr>
<tr id="row791318095713"><td class="cellrowborder" valign="top" width="18.36816318368163%" headers="mcps1.2.5.1.1 "><p id="p491330155714"><a name="p491330155714"></a><a name="p491330155714"></a>instance_id</p>
</td>
<td class="cellrowborder" valign="top" width="14.288571142885711%" headers="mcps1.2.5.1.2 "><p id="p109131005714"><a name="p109131005714"></a><a name="p109131005714"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="13.268673132686734%" headers="mcps1.2.5.1.3 "><p id="p1991360175716"><a name="p1991360175716"></a><a name="p1991360175716"></a>是</p>
</td>
<td class="cellrowborder" valign="top" width="54.074592540745925%" headers="mcps1.2.5.1.4 "><p id="p13913706571"><a name="p13913706571"></a><a name="p13913706571"></a>实例ID。</p>
</td>
</tr>
</tbody>
</table>

## 请求消息<a name="section1445918015576"></a>

**请求参数**

无

**请求示例**

无

## 响应消息<a name="section548616010579"></a>

**响应参数**

**表 2**  响应参数说明

<a name="table154988085711"></a>
<table><thead align="left"><tr id="row791318095711"><th class="cellrowborder" valign="top" width="18.18%" id="mcps1.2.4.1.1"><p id="p2091311065711"><a name="p2091311065711"></a><a name="p2091311065711"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="14.14%" id="mcps1.2.4.1.2"><p id="p19134005713"><a name="p19134005713"></a><a name="p19134005713"></a>类型</p>
</th>
<th class="cellrowborder" valign="top" width="67.67999999999999%" id="mcps1.2.4.1.3"><p id="p1691310045712"><a name="p1691310045712"></a><a name="p1691310045712"></a>说明</p>
</th>
</tr>
</thead>
<tbody><tr id="row491418012577"><td class="cellrowborder" valign="top" width="18.18%" headers="mcps1.2.4.1.1 "><p id="p691411035714"><a name="p691411035714"></a><a name="p691411035714"></a>cluster</p>
</td>
<td class="cellrowborder" valign="top" width="14.14%" headers="mcps1.2.4.1.2 "><p id="p79140075717"><a name="p79140075717"></a><a name="p79140075717"></a>Object of cluster</p>
</td>
<td class="cellrowborder" valign="top" width="67.67999999999999%" headers="mcps1.2.4.1.3 "><p id="p991417015575"><a name="p991417015575"></a><a name="p991417015575"></a>集群基本信息。参数请查看<a href="#table155181504573">表3</a>。</p>
</td>
</tr>
</tbody>
</table>

**表 3**  cluster参数说明

<a name="table155181504573"></a>
<table><thead align="left"><tr id="row1691419015719"><th class="cellrowborder" valign="top" width="18.18%" id="mcps1.2.4.1.1"><p id="p3914110125719"><a name="p3914110125719"></a><a name="p3914110125719"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="14.14%" id="mcps1.2.4.1.2"><p id="p191460155713"><a name="p191460155713"></a><a name="p191460155713"></a>类型</p>
</th>
<th class="cellrowborder" valign="top" width="67.67999999999999%" id="mcps1.2.4.1.3"><p id="p1091414015571"><a name="p1091414015571"></a><a name="p1091414015571"></a>说明</p>
</th>
</tr>
</thead>
<tbody><tr id="row1491415015570"><td class="cellrowborder" valign="top" width="18.18%" headers="mcps1.2.4.1.1 "><p id="p1591418013578"><a name="p1591418013578"></a><a name="p1591418013578"></a>controller</p>
</td>
<td class="cellrowborder" valign="top" width="14.14%" headers="mcps1.2.4.1.2 "><p id="p10914601577"><a name="p10914601577"></a><a name="p10914601577"></a>Integer</p>
</td>
<td class="cellrowborder" valign="top" width="67.67999999999999%" headers="mcps1.2.4.1.3 "><p id="p7914150165714"><a name="p7914150165714"></a><a name="p7914150165714"></a>控制器ID。</p>
</td>
</tr>
<tr id="row1391412013579"><td class="cellrowborder" valign="top" width="18.18%" headers="mcps1.2.4.1.1 "><p id="p11914800577"><a name="p11914800577"></a><a name="p11914800577"></a>brokers</p>
</td>
<td class="cellrowborder" valign="top" width="14.14%" headers="mcps1.2.4.1.2 "><p id="p17914707578"><a name="p17914707578"></a><a name="p17914707578"></a>Array Object of brokers</p>
</td>
<td class="cellrowborder" valign="top" width="67.67999999999999%" headers="mcps1.2.4.1.3 "><p id="p14914160135718"><a name="p14914160135718"></a><a name="p14914160135718"></a>节点列表。参数请查看<a href="#table15633015573">表4</a>。</p>
</td>
</tr>
<tr id="row1391430155714"><td class="cellrowborder" valign="top" width="18.18%" headers="mcps1.2.4.1.1 "><p id="p1791513015576"><a name="p1791513015576"></a><a name="p1791513015576"></a>topics_count</p>
</td>
<td class="cellrowborder" valign="top" width="14.14%" headers="mcps1.2.4.1.2 "><p id="p1191510065719"><a name="p1191510065719"></a><a name="p1191510065719"></a>Integer</p>
</td>
<td class="cellrowborder" valign="top" width="67.67999999999999%" headers="mcps1.2.4.1.3 "><p id="p49151808572"><a name="p49151808572"></a><a name="p49151808572"></a>总topic数量。</p>
</td>
</tr>
<tr id="row49155018571"><td class="cellrowborder" valign="top" width="18.18%" headers="mcps1.2.4.1.1 "><p id="p891515075719"><a name="p891515075719"></a><a name="p891515075719"></a>partitions_count</p>
</td>
<td class="cellrowborder" valign="top" width="14.14%" headers="mcps1.2.4.1.2 "><p id="p159151201579"><a name="p159151201579"></a><a name="p159151201579"></a>Integer</p>
</td>
<td class="cellrowborder" valign="top" width="67.67999999999999%" headers="mcps1.2.4.1.3 "><p id="p209157018576"><a name="p209157018576"></a><a name="p209157018576"></a>总分区数。</p>
</td>
</tr>
<tr id="row2915108572"><td class="cellrowborder" valign="top" width="18.18%" headers="mcps1.2.4.1.1 "><p id="p091515025710"><a name="p091515025710"></a><a name="p091515025710"></a>online_partitions_count</p>
</td>
<td class="cellrowborder" valign="top" width="14.14%" headers="mcps1.2.4.1.2 "><p id="p1091518013576"><a name="p1091518013576"></a><a name="p1091518013576"></a>Integer</p>
</td>
<td class="cellrowborder" valign="top" width="67.67999999999999%" headers="mcps1.2.4.1.3 "><p id="p19154055713"><a name="p19154055713"></a><a name="p19154055713"></a>在线分区数。</p>
</td>
</tr>
<tr id="row1691510065714"><td class="cellrowborder" valign="top" width="18.18%" headers="mcps1.2.4.1.1 "><p id="p159154015715"><a name="p159154015715"></a><a name="p159154015715"></a>replicas_count</p>
</td>
<td class="cellrowborder" valign="top" width="14.14%" headers="mcps1.2.4.1.2 "><p id="p091515012570"><a name="p091515012570"></a><a name="p091515012570"></a>Integer</p>
</td>
<td class="cellrowborder" valign="top" width="67.67999999999999%" headers="mcps1.2.4.1.3 "><p id="p13915209571"><a name="p13915209571"></a><a name="p13915209571"></a>总副本数。</p>
</td>
</tr>
<tr id="row1591514013579"><td class="cellrowborder" valign="top" width="18.18%" headers="mcps1.2.4.1.1 "><p id="p1591517015575"><a name="p1591517015575"></a><a name="p1591517015575"></a>isr_replicas_count</p>
</td>
<td class="cellrowborder" valign="top" width="14.14%" headers="mcps1.2.4.1.2 "><p id="p169151402578"><a name="p169151402578"></a><a name="p169151402578"></a>Integer</p>
</td>
<td class="cellrowborder" valign="top" width="67.67999999999999%" headers="mcps1.2.4.1.3 "><p id="p891510012573"><a name="p891510012573"></a><a name="p891510012573"></a>ISR（In-Sync Replicas） 副本总数。</p>
</td>
</tr>
<tr id="row1915200105713"><td class="cellrowborder" valign="top" width="18.18%" headers="mcps1.2.4.1.1 "><p id="p191515095716"><a name="p191515095716"></a><a name="p191515095716"></a>consumers_count</p>
</td>
<td class="cellrowborder" valign="top" width="14.14%" headers="mcps1.2.4.1.2 "><p id="p19915309575"><a name="p19915309575"></a><a name="p19915309575"></a>Integer</p>
</td>
<td class="cellrowborder" valign="top" width="67.67999999999999%" headers="mcps1.2.4.1.3 "><p id="p11915009579"><a name="p11915009579"></a><a name="p11915009579"></a>消费者总数。</p>
</td>
</tr>
</tbody>
</table>

**表 4**  brokers参数说明

<a name="table15633015573"></a>
<table><thead align="left"><tr id="row891616095719"><th class="cellrowborder" valign="top" width="18.18%" id="mcps1.2.4.1.1"><p id="p19160017572"><a name="p19160017572"></a><a name="p19160017572"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="14.14%" id="mcps1.2.4.1.2"><p id="p091615075711"><a name="p091615075711"></a><a name="p091615075711"></a>类型</p>
</th>
<th class="cellrowborder" valign="top" width="67.67999999999999%" id="mcps1.2.4.1.3"><p id="p391612013571"><a name="p391612013571"></a><a name="p391612013571"></a>说明</p>
</th>
</tr>
</thead>
<tbody><tr id="row18916701575"><td class="cellrowborder" valign="top" width="18.18%" headers="mcps1.2.4.1.1 "><p id="p49161904575"><a name="p49161904575"></a><a name="p49161904575"></a>broker_id</p>
</td>
<td class="cellrowborder" valign="top" width="14.14%" headers="mcps1.2.4.1.2 "><p id="p17916907571"><a name="p17916907571"></a><a name="p17916907571"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="67.67999999999999%" headers="mcps1.2.4.1.3 "><p id="p2091614005714"><a name="p2091614005714"></a><a name="p2091614005714"></a>节点id。</p>
</td>
</tr>
<tr id="row11916100195714"><td class="cellrowborder" valign="top" width="18.18%" headers="mcps1.2.4.1.1 "><p id="p891620125714"><a name="p891620125714"></a><a name="p891620125714"></a>is_controller</p>
</td>
<td class="cellrowborder" valign="top" width="14.14%" headers="mcps1.2.4.1.2 "><p id="p2916110155720"><a name="p2916110155720"></a><a name="p2916110155720"></a>Boolean</p>
</td>
<td class="cellrowborder" valign="top" width="67.67999999999999%" headers="mcps1.2.4.1.3 "><p id="p1491612065716"><a name="p1491612065716"></a><a name="p1491612065716"></a>是否为contoller节点。</p>
</td>
</tr>
<tr id="row149161025714"><td class="cellrowborder" valign="top" width="18.18%" headers="mcps1.2.4.1.1 "><p id="p8916107574"><a name="p8916107574"></a><a name="p8916107574"></a>version</p>
</td>
<td class="cellrowborder" valign="top" width="14.14%" headers="mcps1.2.4.1.2 "><p id="p291620019576"><a name="p291620019576"></a><a name="p291620019576"></a>Boolean</p>
</td>
<td class="cellrowborder" valign="top" width="67.67999999999999%" headers="mcps1.2.4.1.3 "><p id="p8916190115717"><a name="p8916190115717"></a><a name="p8916190115717"></a>服务端版本。</p>
</td>
</tr>
<tr id="row199161207576"><td class="cellrowborder" valign="top" width="18.18%" headers="mcps1.2.4.1.1 "><p id="p591790205715"><a name="p591790205715"></a><a name="p591790205715"></a>register_time</p>
</td>
<td class="cellrowborder" valign="top" width="14.14%" headers="mcps1.2.4.1.2 "><p id="p189172025710"><a name="p189172025710"></a><a name="p189172025710"></a>Long</p>
</td>
<td class="cellrowborder" valign="top" width="67.67999999999999%" headers="mcps1.2.4.1.3 "><p id="p2917130165712"><a name="p2917130165712"></a><a name="p2917130165712"></a>broker注册时间，为unix时间戳格式。</p>
</td>
</tr>
<tr id="row209175014577"><td class="cellrowborder" valign="top" width="18.18%" headers="mcps1.2.4.1.1 "><p id="p15917701572"><a name="p15917701572"></a><a name="p15917701572"></a>is_health</p>
</td>
<td class="cellrowborder" valign="top" width="14.14%" headers="mcps1.2.4.1.2 "><p id="p1917507576"><a name="p1917507576"></a><a name="p1917507576"></a>Boolean</p>
</td>
<td class="cellrowborder" valign="top" width="67.67999999999999%" headers="mcps1.2.4.1.3 "><p id="p99172018576"><a name="p99172018576"></a><a name="p99172018576"></a>Kafka实例节点的连通性是否正常。</p>
</td>
</tr>
</tbody>
</table>

**响应示例**

```
{
    "cluster": {
        "controller": "1",
        "brokers": [
            {
                "broker_id": "1",
                "is_controller": true,
                "version": "1.1.0",
                "register_time": 1569059680711,
                "is_health": true
            },
            {
                "broker_id": "2",
                "is_controller": false,
                "version": "1.1.0",
                "register_time": 1569059684548,
                "is_health": true
            }
        ],
        "topics_count": 4,
        "partitions_count": 13,
        "online_partitions_count": 12,
        "replicas_count": 31,
        "isr_replicas_count": 21,
        "consumers_count": 7
    }
}
```

