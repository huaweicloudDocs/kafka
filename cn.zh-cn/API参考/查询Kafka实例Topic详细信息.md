# 查询Kafka实例Topic详细信息<a name="ZH-CN_TOPIC_0210486911"></a>

## URI<a name="section14909821155917"></a>

GET  /v1.0/\{project\_id\}/instances/\{instance\_id\}/manage/topics/\{topic\}

参数说明如下表所示。

**表 1**  参数说明

<a name="table1191132125915"></a>
<table><thead align="left"><tr id="row15167162255910"><th class="cellrowborder" valign="top" width="19.388061193880613%" id="mcps1.2.5.1.1"><p id="p1016752216593"><a name="p1016752216593"></a><a name="p1016752216593"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="15.308469153084694%" id="mcps1.2.5.1.2"><p id="p1016711227595"><a name="p1016711227595"></a><a name="p1016711227595"></a>类型</p>
</th>
<th class="cellrowborder" valign="top" width="14.288571142885711%" id="mcps1.2.5.1.3"><p id="p12167172214597"><a name="p12167172214597"></a><a name="p12167172214597"></a>必选</p>
</th>
<th class="cellrowborder" valign="top" width="51.01489851014899%" id="mcps1.2.5.1.4"><p id="p1016716223597"><a name="p1016716223597"></a><a name="p1016716223597"></a>说明</p>
</th>
</tr>
</thead>
<tbody><tr id="row10167112219592"><td class="cellrowborder" valign="top" width="19.388061193880613%" headers="mcps1.2.5.1.1 "><p id="p1116792217595"><a name="p1116792217595"></a><a name="p1116792217595"></a>project_id</p>
</td>
<td class="cellrowborder" valign="top" width="15.308469153084694%" headers="mcps1.2.5.1.2 "><p id="p116818224593"><a name="p116818224593"></a><a name="p116818224593"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="14.288571142885711%" headers="mcps1.2.5.1.3 "><p id="p181681322165918"><a name="p181681322165918"></a><a name="p181681322165918"></a>是</p>
</td>
<td class="cellrowborder" valign="top" width="51.01489851014899%" headers="mcps1.2.5.1.4 "><p id="p016882245919"><a name="p016882245919"></a><a name="p016882245919"></a>项目ID。</p>
</td>
</tr>
<tr id="row201681224595"><td class="cellrowborder" valign="top" width="19.388061193880613%" headers="mcps1.2.5.1.1 "><p id="p3168142212598"><a name="p3168142212598"></a><a name="p3168142212598"></a>instance_id</p>
</td>
<td class="cellrowborder" valign="top" width="15.308469153084694%" headers="mcps1.2.5.1.2 "><p id="p16168192285914"><a name="p16168192285914"></a><a name="p16168192285914"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="14.288571142885711%" headers="mcps1.2.5.1.3 "><p id="p31681722145919"><a name="p31681722145919"></a><a name="p31681722145919"></a>是</p>
</td>
<td class="cellrowborder" valign="top" width="51.01489851014899%" headers="mcps1.2.5.1.4 "><p id="p1716812217596"><a name="p1716812217596"></a><a name="p1716812217596"></a>实例ID。</p>
</td>
</tr>
<tr id="row10168172218599"><td class="cellrowborder" valign="top" width="19.388061193880613%" headers="mcps1.2.5.1.1 "><p id="p10168182275918"><a name="p10168182275918"></a><a name="p10168182275918"></a>topic</p>
</td>
<td class="cellrowborder" valign="top" width="15.308469153084694%" headers="mcps1.2.5.1.2 "><p id="p11168922145911"><a name="p11168922145911"></a><a name="p11168922145911"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="14.288571142885711%" headers="mcps1.2.5.1.3 "><p id="p201682226593"><a name="p201682226593"></a><a name="p201682226593"></a>是</p>
</td>
<td class="cellrowborder" valign="top" width="51.01489851014899%" headers="mcps1.2.5.1.4 "><p id="p516802212596"><a name="p516802212596"></a><a name="p516802212596"></a>topic名称。</p>
</td>
</tr>
</tbody>
</table>

## 请求消息<a name="section15910142110592"></a>

**请求参数**

无

**请求示例**

无

## 响应消息<a name="section1893082115914"></a>

**响应参数**

参数说明见[表2](#table1093512175920)。

**表 2**  响应参数说明

<a name="table1093512175920"></a>
<table><thead align="left"><tr id="row181681922175914"><th class="cellrowborder" valign="top" width="29.29%" id="mcps1.2.4.1.1"><p id="p216818221597"><a name="p216818221597"></a><a name="p216818221597"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="16.16%" id="mcps1.2.4.1.2"><p id="p1316872275918"><a name="p1316872275918"></a><a name="p1316872275918"></a>类型</p>
</th>
<th class="cellrowborder" valign="top" width="54.55%" id="mcps1.2.4.1.3"><p id="p1316892275913"><a name="p1316892275913"></a><a name="p1316892275913"></a>说明</p>
</th>
</tr>
</thead>
<tbody><tr id="row18168182225910"><td class="cellrowborder" valign="top" width="29.29%" headers="mcps1.2.4.1.1 "><p id="p51681522125918"><a name="p51681522125918"></a><a name="p51681522125918"></a>topic</p>
</td>
<td class="cellrowborder" valign="top" width="16.16%" headers="mcps1.2.4.1.2 "><p id="p1316816225594"><a name="p1316816225594"></a><a name="p1316816225594"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="54.55%" headers="mcps1.2.4.1.3 "><p id="p151681122205912"><a name="p151681122205912"></a><a name="p151681122205912"></a>topic名称。</p>
</td>
</tr>
<tr id="row1168132212597"><td class="cellrowborder" valign="top" width="29.29%" headers="mcps1.2.4.1.1 "><p id="p6168132214593"><a name="p6168132214593"></a><a name="p6168132214593"></a>partitions</p>
</td>
<td class="cellrowborder" valign="top" width="16.16%" headers="mcps1.2.4.1.2 "><p id="p201681022195912"><a name="p201681022195912"></a><a name="p201681022195912"></a>Array of object partitions</p>
</td>
<td class="cellrowborder" valign="top" width="54.55%" headers="mcps1.2.4.1.3 "><p id="p1168622185918"><a name="p1168622185918"></a><a name="p1168622185918"></a>分区列表。参数查看<a href="#table194272117597">表3</a>。</p>
</td>
</tr>
<tr id="row816872213594"><td class="cellrowborder" valign="top" width="29.29%" headers="mcps1.2.4.1.1 "><p id="p216813224590"><a name="p216813224590"></a><a name="p216813224590"></a>group_subscribed</p>
</td>
<td class="cellrowborder" valign="top" width="16.16%" headers="mcps1.2.4.1.2 "><p id="p21682226591"><a name="p21682226591"></a><a name="p21682226591"></a>Array of String</p>
</td>
<td class="cellrowborder" valign="top" width="54.55%" headers="mcps1.2.4.1.3 "><p id="p141681522195919"><a name="p141681522195919"></a><a name="p141681522195919"></a>订阅该topic的消费组名称列表。</p>
</td>
</tr>
</tbody>
</table>

**表 3**  partitions参数说明

<a name="table194272117597"></a>
<table><thead align="left"><tr id="row11691322165915"><th class="cellrowborder" valign="top" width="18.36816318368163%" id="mcps1.2.4.1.1"><p id="p11699221595"><a name="p11699221595"></a><a name="p11699221595"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="15.308469153084694%" id="mcps1.2.4.1.2"><p id="p81695228596"><a name="p81695228596"></a><a name="p81695228596"></a>类型</p>
</th>
<th class="cellrowborder" valign="top" width="66.32336766323368%" id="mcps1.2.4.1.3"><p id="p1116952255914"><a name="p1116952255914"></a><a name="p1116952255914"></a>说明</p>
</th>
</tr>
</thead>
<tbody><tr id="row10169142235910"><td class="cellrowborder" valign="top" width="18.36816318368163%" headers="mcps1.2.4.1.1 "><p id="p816982212591"><a name="p816982212591"></a><a name="p816982212591"></a>partition</p>
</td>
<td class="cellrowborder" valign="top" width="15.308469153084694%" headers="mcps1.2.4.1.2 "><p id="p201691422185918"><a name="p201691422185918"></a><a name="p201691422185918"></a>Integer</p>
</td>
<td class="cellrowborder" valign="top" width="66.32336766323368%" headers="mcps1.2.4.1.3 "><p id="p13169192211595"><a name="p13169192211595"></a><a name="p13169192211595"></a>分区ID。</p>
</td>
</tr>
<tr id="row111691224596"><td class="cellrowborder" valign="top" width="18.36816318368163%" headers="mcps1.2.4.1.1 "><p id="p1316972285915"><a name="p1316972285915"></a><a name="p1316972285915"></a>leader</p>
</td>
<td class="cellrowborder" valign="top" width="15.308469153084694%" headers="mcps1.2.4.1.2 "><p id="p1316918225592"><a name="p1316918225592"></a><a name="p1316918225592"></a>Integer</p>
</td>
<td class="cellrowborder" valign="top" width="66.32336766323368%" headers="mcps1.2.4.1.3 "><p id="p1316912212593"><a name="p1316912212593"></a><a name="p1316912212593"></a>leader副本所在节点的id。</p>
</td>
</tr>
<tr id="row11169192210596"><td class="cellrowborder" valign="top" width="18.36816318368163%" headers="mcps1.2.4.1.1 "><p id="p91696229594"><a name="p91696229594"></a><a name="p91696229594"></a>leo</p>
</td>
<td class="cellrowborder" valign="top" width="15.308469153084694%" headers="mcps1.2.4.1.2 "><p id="p6169022125912"><a name="p6169022125912"></a><a name="p6169022125912"></a>long</p>
</td>
<td class="cellrowborder" valign="top" width="66.32336766323368%" headers="mcps1.2.4.1.3 "><p id="p4169182255913"><a name="p4169182255913"></a><a name="p4169182255913"></a>分区leader副本的LEO（Log End Offset）。</p>
</td>
</tr>
<tr id="row1916962218595"><td class="cellrowborder" valign="top" width="18.36816318368163%" headers="mcps1.2.4.1.1 "><p id="p15169102295919"><a name="p15169102295919"></a><a name="p15169102295919"></a>hw</p>
</td>
<td class="cellrowborder" valign="top" width="15.308469153084694%" headers="mcps1.2.4.1.2 "><p id="p816922213591"><a name="p816922213591"></a><a name="p816922213591"></a>long</p>
</td>
<td class="cellrowborder" valign="top" width="66.32336766323368%" headers="mcps1.2.4.1.3 "><p id="p101699220597"><a name="p101699220597"></a><a name="p101699220597"></a>分区高水位（HW，High Watermark）。</p>
</td>
</tr>
<tr id="row1816942265914"><td class="cellrowborder" valign="top" width="18.36816318368163%" headers="mcps1.2.4.1.1 "><p id="p616942245918"><a name="p616942245918"></a><a name="p616942245918"></a>lso</p>
</td>
<td class="cellrowborder" valign="top" width="15.308469153084694%" headers="mcps1.2.4.1.2 "><p id="p111694221593"><a name="p111694221593"></a><a name="p111694221593"></a>long</p>
</td>
<td class="cellrowborder" valign="top" width="66.32336766323368%" headers="mcps1.2.4.1.3 "><p id="p13169162215590"><a name="p13169162215590"></a><a name="p13169162215590"></a>分区leader副本的LSO（Log Start Offset）。</p>
</td>
</tr>
<tr id="row16169182295910"><td class="cellrowborder" valign="top" width="18.36816318368163%" headers="mcps1.2.4.1.1 "><p id="p13169022135915"><a name="p13169022135915"></a><a name="p13169022135915"></a>last_update_timestamp</p>
</td>
<td class="cellrowborder" valign="top" width="15.308469153084694%" headers="mcps1.2.4.1.2 "><p id="p101691722195910"><a name="p101691722195910"></a><a name="p101691722195910"></a>long</p>
</td>
<td class="cellrowborder" valign="top" width="66.32336766323368%" headers="mcps1.2.4.1.3 "><p id="p61691822115917"><a name="p61691822115917"></a><a name="p61691822115917"></a>分区上次写入消息的时间。</p>
</td>
</tr>
<tr id="row151691022115915"><td class="cellrowborder" valign="top" width="18.36816318368163%" headers="mcps1.2.4.1.1 "><p id="p1716962214594"><a name="p1716962214594"></a><a name="p1716962214594"></a>replicas</p>
</td>
<td class="cellrowborder" valign="top" width="15.308469153084694%" headers="mcps1.2.4.1.2 "><p id="p41691222195912"><a name="p41691222195912"></a><a name="p41691222195912"></a>Array of object replicas</p>
</td>
<td class="cellrowborder" valign="top" width="66.32336766323368%" headers="mcps1.2.4.1.3 "><p id="p10169822195912"><a name="p10169822195912"></a><a name="p10169822195912"></a>副本列表。参数查看<a href="#table1396572110592">表4</a>。</p>
</td>
</tr>
</tbody>
</table>

**表 4**  replicas参数说明

<a name="table1396572110592"></a>
<table><thead align="left"><tr id="row19170152285912"><th class="cellrowborder" valign="top" width="19.189999999999998%" id="mcps1.2.4.1.1"><p id="p151707222596"><a name="p151707222596"></a><a name="p151707222596"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="15.15%" id="mcps1.2.4.1.2"><p id="p14170182215912"><a name="p14170182215912"></a><a name="p14170182215912"></a>类型</p>
</th>
<th class="cellrowborder" valign="top" width="65.66%" id="mcps1.2.4.1.3"><p id="p91701622145910"><a name="p91701622145910"></a><a name="p91701622145910"></a>说明</p>
</th>
</tr>
</thead>
<tbody><tr id="row1017011227594"><td class="cellrowborder" valign="top" width="19.189999999999998%" headers="mcps1.2.4.1.1 "><p id="p51701622185919"><a name="p51701622185919"></a><a name="p51701622185919"></a>broker</p>
</td>
<td class="cellrowborder" valign="top" width="15.15%" headers="mcps1.2.4.1.2 "><p id="p161701622195918"><a name="p161701622195918"></a><a name="p161701622195918"></a>Integer</p>
</td>
<td class="cellrowborder" valign="top" width="65.66%" headers="mcps1.2.4.1.3 "><p id="p171701922145913"><a name="p171701922145913"></a><a name="p171701922145913"></a>副本所在的节点ID。</p>
</td>
</tr>
<tr id="row3170322165911"><td class="cellrowborder" valign="top" width="19.189999999999998%" headers="mcps1.2.4.1.1 "><p id="p717072295917"><a name="p717072295917"></a><a name="p717072295917"></a>leader</p>
</td>
<td class="cellrowborder" valign="top" width="15.15%" headers="mcps1.2.4.1.2 "><p id="p5170102255920"><a name="p5170102255920"></a><a name="p5170102255920"></a>Boolean</p>
</td>
<td class="cellrowborder" valign="top" width="65.66%" headers="mcps1.2.4.1.3 "><p id="p517082285918"><a name="p517082285918"></a><a name="p517082285918"></a>该副本是否为leader。</p>
</td>
</tr>
<tr id="row2170182225920"><td class="cellrowborder" valign="top" width="19.189999999999998%" headers="mcps1.2.4.1.1 "><p id="p131701622195912"><a name="p131701622195912"></a><a name="p131701622195912"></a>in_sync</p>
</td>
<td class="cellrowborder" valign="top" width="15.15%" headers="mcps1.2.4.1.2 "><p id="p18170162211590"><a name="p18170162211590"></a><a name="p18170162211590"></a>Boolean</p>
</td>
<td class="cellrowborder" valign="top" width="65.66%" headers="mcps1.2.4.1.3 "><p id="p6170172215599"><a name="p6170172215599"></a><a name="p6170172215599"></a>该副本是否在ISR副本中。</p>
</td>
</tr>
<tr id="row1217032210593"><td class="cellrowborder" valign="top" width="19.189999999999998%" headers="mcps1.2.4.1.1 "><p id="p4170102255920"><a name="p4170102255920"></a><a name="p4170102255920"></a>size</p>
</td>
<td class="cellrowborder" valign="top" width="15.15%" headers="mcps1.2.4.1.2 "><p id="p2170422185916"><a name="p2170422185916"></a><a name="p2170422185916"></a>Long</p>
</td>
<td class="cellrowborder" valign="top" width="65.66%" headers="mcps1.2.4.1.3 "><p id="p11170192275912"><a name="p11170192275912"></a><a name="p11170192275912"></a>该副本当前日志大小。</p>
</td>
</tr>
<tr id="row141700227594"><td class="cellrowborder" valign="top" width="19.189999999999998%" headers="mcps1.2.4.1.1 "><p id="p617015228596"><a name="p617015228596"></a><a name="p617015228596"></a>lag</p>
</td>
<td class="cellrowborder" valign="top" width="15.15%" headers="mcps1.2.4.1.2 "><p id="p141701622105910"><a name="p141701622105910"></a><a name="p141701622105910"></a>Long</p>
</td>
<td class="cellrowborder" valign="top" width="65.66%" headers="mcps1.2.4.1.3 "><p id="p15170322195913"><a name="p15170322195913"></a><a name="p15170322195913"></a>该副本当前落后hw的消息数。</p>
</td>
</tr>
</tbody>
</table>

**响应示例**

```
{
    "topic": "test",
    "partitions": [
        {
            "partition": 0,
            "leader": 2,
            "replicas": [
                {
                    "broker": 2,
                    "leader": true,
                    "in_sync": true,
                    "size": 123971146,
                    "lag": 0
                },
                {
                    "broker": 1,
                    "leader": false,
                    "in_sync": true,
                    "size": 123971146,
                    "lag": 0
                },
                {
                    "broker": 0,
                    "leader": false,
                    "in_sync": true,
                    "size": 123971146,
                    "lag": 0
                }
            ],
            "lso": 0,
            "leo": 13598,
            "hw": 13598,
            "last_update_timestamp": 1571477180985
        },
        {
            "partition": 2,
            "leader": 1,
            "replicas": [
                {
                    "broker": 1,
                    "leader": true,
                    "in_sync": true,
                    "size": 123889531,
                    "lag": 0
                },
                {
                    "broker": 0,
                    "leader": false,
                    "in_sync": true,
                    "size": 123889531,
                    "lag": 0
                },
                {
                    "broker": 2,
                    "leader": false,
                    "in_sync": true,
                    "size": 123889531,
                    "lag": 0
                }
            ],
            "lso": 0,
            "leo": 13601,
            "hw": 13601,
            "last_update_timestamp": 1571477077146
        },
        {
            "partition": 1,
            "leader": 0,
            "replicas": [
                {
                    "broker": 0,
                    "leader": true,
                    "in_sync": true,
                    "size": 127245604,
                    "lag": 0
                },
                {
                    "broker": 2,
                    "leader": false,
                    "in_sync": true,
                    "size": 127245604,
                    "lag": 0
                },
                {
                    "broker": 1,
                    "leader": false,
                    "in_sync": true,
                    "size": 127245604,
                    "lag": 0
                }
            ],
            "lso": 0,
            "leo": 13599,
            "hw": 13599,
            "last_update_timestamp": 1571477172959
        }
    ],
    "group_subscribed": [
        "test-consumer-group"
    ]
}
```

## 状态码<a name="section3832217599"></a>

查询成功的状态码[表5](#table1494228595)所示，其他响应见[表1](状态码.md#zh-cn_topic_0128036883_table5210141351517)。

**表 5**  状态码

<a name="table1494228595"></a>
<table><thead align="left"><tr id="row121725229597"><th class="cellrowborder" valign="top" width="15.15%" id="mcps1.2.3.1.1"><p id="p41721122145917"><a name="p41721122145917"></a><a name="p41721122145917"></a>状态码</p>
</th>
<th class="cellrowborder" valign="top" width="84.85000000000001%" id="mcps1.2.3.1.2"><p id="p131722229592"><a name="p131722229592"></a><a name="p131722229592"></a>描述</p>
</th>
</tr>
</thead>
<tbody><tr id="row21731822195917"><td class="cellrowborder" valign="top" width="15.15%" headers="mcps1.2.3.1.1 "><p id="p20173152285914"><a name="p20173152285914"></a><a name="p20173152285914"></a>200</p>
</td>
<td class="cellrowborder" valign="top" width="84.85000000000001%" headers="mcps1.2.3.1.2 "><p id="p10173182211591"><a name="p10173182211591"></a><a name="p10173182211591"></a>查询成功。</p>
</td>
</tr>
</tbody>
</table>

