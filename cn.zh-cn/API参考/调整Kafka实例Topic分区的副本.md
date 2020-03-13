# 调整Kafka实例Topic分区的副本<a name="ZH-CN_TOPIC_0210486913"></a>

## URI<a name="section9770155211595"></a>

POST  /v1.0/\{project\_id\}/instances/\{instance\_id\}/manage/topics/\{topic\}/replicas-reassignment

参数说明如下表所示。

**表 1**  参数说明

<a name="table10611131664920"></a>
<table><thead align="left"><tr id="row17611161674910"><th class="cellrowborder" valign="top" width="19.388061193880613%" id="mcps1.2.5.1.1"><p id="p12611516144919"><a name="p12611516144919"></a><a name="p12611516144919"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="15.308469153084694%" id="mcps1.2.5.1.2"><p id="p15611181644912"><a name="p15611181644912"></a><a name="p15611181644912"></a>类型</p>
</th>
<th class="cellrowborder" valign="top" width="14.288571142885711%" id="mcps1.2.5.1.3"><p id="p76110163491"><a name="p76110163491"></a><a name="p76110163491"></a>必选</p>
</th>
<th class="cellrowborder" valign="top" width="51.01489851014899%" id="mcps1.2.5.1.4"><p id="p1661115160492"><a name="p1661115160492"></a><a name="p1661115160492"></a>说明</p>
</th>
</tr>
</thead>
<tbody><tr id="row2611181612493"><td class="cellrowborder" valign="top" width="19.388061193880613%" headers="mcps1.2.5.1.1 "><p id="p4611111619496"><a name="p4611111619496"></a><a name="p4611111619496"></a>project_id</p>
</td>
<td class="cellrowborder" valign="top" width="15.308469153084694%" headers="mcps1.2.5.1.2 "><p id="p12611181674918"><a name="p12611181674918"></a><a name="p12611181674918"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="14.288571142885711%" headers="mcps1.2.5.1.3 "><p id="p12611141617494"><a name="p12611141617494"></a><a name="p12611141617494"></a>是</p>
</td>
<td class="cellrowborder" valign="top" width="51.01489851014899%" headers="mcps1.2.5.1.4 "><p id="p98322520472"><a name="p98322520472"></a><a name="p98322520472"></a>项目ID。</p>
</td>
</tr>
<tr id="row1861191611497"><td class="cellrowborder" valign="top" width="19.388061193880613%" headers="mcps1.2.5.1.1 "><p id="p1612111634920"><a name="p1612111634920"></a><a name="p1612111634920"></a>instance_id</p>
</td>
<td class="cellrowborder" valign="top" width="15.308469153084694%" headers="mcps1.2.5.1.2 "><p id="p4612216174919"><a name="p4612216174919"></a><a name="p4612216174919"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="14.288571142885711%" headers="mcps1.2.5.1.3 "><p id="p14612516114917"><a name="p14612516114917"></a><a name="p14612516114917"></a>是</p>
</td>
<td class="cellrowborder" valign="top" width="51.01489851014899%" headers="mcps1.2.5.1.4 "><p id="p19832115274718"><a name="p19832115274718"></a><a name="p19832115274718"></a>实例ID。</p>
</td>
</tr>
<tr id="row461251610494"><td class="cellrowborder" valign="top" width="19.388061193880613%" headers="mcps1.2.5.1.1 "><p id="p1461281618498"><a name="p1461281618498"></a><a name="p1461281618498"></a>topic</p>
</td>
<td class="cellrowborder" valign="top" width="15.308469153084694%" headers="mcps1.2.5.1.2 "><p id="p861261634913"><a name="p861261634913"></a><a name="p861261634913"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="14.288571142885711%" headers="mcps1.2.5.1.3 "><p id="p9612101614915"><a name="p9612101614915"></a><a name="p9612101614915"></a>是</p>
</td>
<td class="cellrowborder" valign="top" width="51.01489851014899%" headers="mcps1.2.5.1.4 "><p id="p6832952194719"><a name="p6832952194719"></a><a name="p6832952194719"></a>Topic名称。</p>
</td>
</tr>
</tbody>
</table>

## 请求消息<a name="section117717524597"></a>

**请求参数**

**表 2**  参数说明

<a name="table0773452205910"></a>
<table><thead align="left"><tr id="row17899145213598"><th class="cellrowborder" valign="top" width="19.388061193880613%" id="mcps1.2.5.1.1"><p id="p889965225916"><a name="p889965225916"></a><a name="p889965225916"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="15.308469153084694%" id="mcps1.2.5.1.2"><p id="p889985235912"><a name="p889985235912"></a><a name="p889985235912"></a>类型</p>
</th>
<th class="cellrowborder" valign="top" width="14.288571142885711%" id="mcps1.2.5.1.3"><p id="p15899125295916"><a name="p15899125295916"></a><a name="p15899125295916"></a>必选</p>
</th>
<th class="cellrowborder" valign="top" width="51.01489851014899%" id="mcps1.2.5.1.4"><p id="p12899185218591"><a name="p12899185218591"></a><a name="p12899185218591"></a>说明</p>
</th>
</tr>
</thead>
<tbody><tr id="row1900205215918"><td class="cellrowborder" valign="top" width="19.388061193880613%" headers="mcps1.2.5.1.1 "><p id="p7900175211593"><a name="p7900175211593"></a><a name="p7900175211593"></a>partitions</p>
</td>
<td class="cellrowborder" valign="top" width="15.308469153084694%" headers="mcps1.2.5.1.2 "><p id="p890010524597"><a name="p890010524597"></a><a name="p890010524597"></a>Array of object partitions</p>
</td>
<td class="cellrowborder" valign="top" width="14.288571142885711%" headers="mcps1.2.5.1.3 "><p id="p59001452155914"><a name="p59001452155914"></a><a name="p59001452155914"></a>是</p>
</td>
<td class="cellrowborder" valign="top" width="51.01489851014899%" headers="mcps1.2.5.1.4 "><p id="p1590035212597"><a name="p1590035212597"></a><a name="p1590035212597"></a>期望调整的分区副本分配情况。参数参考<a href="#table078816528593">表3</a>。</p>
</td>
</tr>
</tbody>
</table>

**表 3**  partitions参数说明

<a name="table078816528593"></a>
<table><thead align="left"><tr id="row12900145212590"><th class="cellrowborder" valign="top" width="19.388061193880613%" id="mcps1.2.5.1.1"><p id="p6900125225919"><a name="p6900125225919"></a><a name="p6900125225919"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="15.308469153084694%" id="mcps1.2.5.1.2"><p id="p390005215596"><a name="p390005215596"></a><a name="p390005215596"></a>类型</p>
</th>
<th class="cellrowborder" valign="top" width="14.288571142885711%" id="mcps1.2.5.1.3"><p id="p1290014521595"><a name="p1290014521595"></a><a name="p1290014521595"></a>必选</p>
</th>
<th class="cellrowborder" valign="top" width="51.01489851014899%" id="mcps1.2.5.1.4"><p id="p159004527598"><a name="p159004527598"></a><a name="p159004527598"></a>说明</p>
</th>
</tr>
</thead>
<tbody><tr id="row49008521593"><td class="cellrowborder" valign="top" width="19.388061193880613%" headers="mcps1.2.5.1.1 "><p id="p1590015218591"><a name="p1590015218591"></a><a name="p1590015218591"></a>partition</p>
</td>
<td class="cellrowborder" valign="top" width="15.308469153084694%" headers="mcps1.2.5.1.2 "><p id="p59009528598"><a name="p59009528598"></a><a name="p59009528598"></a>Integer</p>
</td>
<td class="cellrowborder" valign="top" width="14.288571142885711%" headers="mcps1.2.5.1.3 "><p id="p8900152125911"><a name="p8900152125911"></a><a name="p8900152125911"></a>是</p>
</td>
<td class="cellrowborder" valign="top" width="51.01489851014899%" headers="mcps1.2.5.1.4 "><p id="p13900952185920"><a name="p13900952185920"></a><a name="p13900952185920"></a>分区ID。</p>
</td>
</tr>
<tr id="row159008523594"><td class="cellrowborder" valign="top" width="19.388061193880613%" headers="mcps1.2.5.1.1 "><p id="p1490085265912"><a name="p1490085265912"></a><a name="p1490085265912"></a>replicas</p>
</td>
<td class="cellrowborder" valign="top" width="15.308469153084694%" headers="mcps1.2.5.1.2 "><p id="p12900165255916"><a name="p12900165255916"></a><a name="p12900165255916"></a>Array of integer</p>
</td>
<td class="cellrowborder" valign="top" width="14.288571142885711%" headers="mcps1.2.5.1.3 "><p id="p79009525593"><a name="p79009525593"></a><a name="p79009525593"></a>是</p>
</td>
<td class="cellrowborder" valign="top" width="51.01489851014899%" headers="mcps1.2.5.1.4 "><p id="p990015524593"><a name="p990015524593"></a><a name="p990015524593"></a>副本期望所在的broker ID。其中Array首位为leader副本，所有分区需要有同样数量的副本，副本数不能大于总broker的数量。</p>
</td>
</tr>
</tbody>
</table>

**请求示例**

```
{
    "partitions": [
        {
            "partition": 1,
            "replicas": [
                1,
                2
            ]
        },
        {
            "partition": 0,
            "replicas": [
                0,
                1
            ]
        }
    ]
}
```

## 响应消息<a name="section108103529595"></a>

**响应参数**

无

**响应示例**

无

## 状态码<a name="section11812352125912"></a>

操作成功的状态码。

**表 4**  状态码

<a name="table178131652145917"></a>
<table><thead align="left"><tr id="row4901952165911"><th class="cellrowborder" valign="top" width="15.15%" id="mcps1.2.3.1.1"><p id="p09011352165912"><a name="p09011352165912"></a><a name="p09011352165912"></a>状态码</p>
</th>
<th class="cellrowborder" valign="top" width="84.85000000000001%" id="mcps1.2.3.1.2"><p id="p1490165295919"><a name="p1490165295919"></a><a name="p1490165295919"></a>描述</p>
</th>
</tr>
</thead>
<tbody><tr id="row6901165212594"><td class="cellrowborder" valign="top" width="15.15%" headers="mcps1.2.3.1.1 "><p id="p29011452175917"><a name="p29011452175917"></a><a name="p29011452175917"></a>204</p>
</td>
<td class="cellrowborder" valign="top" width="84.85000000000001%" headers="mcps1.2.3.1.2 "><p id="p1890195215920"><a name="p1890195215920"></a><a name="p1890195215920"></a>调整副本操作成功。</p>
</td>
</tr>
</tbody>
</table>

