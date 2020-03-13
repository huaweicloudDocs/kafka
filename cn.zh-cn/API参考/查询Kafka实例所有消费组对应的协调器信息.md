# 查询Kafka实例所有消费组对应的协调器信息<a name="ZH-CN_TOPIC_0210486910"></a>

## URI<a name="section450410584581"></a>

GET  /v1.0/\{project\_id\}/instances/\{instance\_id\}/manage/coordinators

参数说明如下表所示。

**表 1**  参数说明

<a name="table105061758205811"></a>
<table><thead align="left"><tr id="row10597958145818"><th class="cellrowborder" valign="top" width="16%" id="mcps1.2.5.1.1"><p id="p15971058185810"><a name="p15971058185810"></a><a name="p15971058185810"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="13%" id="mcps1.2.5.1.2"><p id="p1459715875819"><a name="p1459715875819"></a><a name="p1459715875819"></a>类型</p>
</th>
<th class="cellrowborder" valign="top" width="12%" id="mcps1.2.5.1.3"><p id="p19597195875820"><a name="p19597195875820"></a><a name="p19597195875820"></a>必选</p>
</th>
<th class="cellrowborder" valign="top" width="59%" id="mcps1.2.5.1.4"><p id="p12597135818581"><a name="p12597135818581"></a><a name="p12597135818581"></a>说明</p>
</th>
</tr>
</thead>
<tbody><tr id="row11597958145816"><td class="cellrowborder" valign="top" width="16%" headers="mcps1.2.5.1.1 "><p id="p13597658105812"><a name="p13597658105812"></a><a name="p13597658105812"></a>project_id</p>
</td>
<td class="cellrowborder" valign="top" width="13%" headers="mcps1.2.5.1.2 "><p id="p1959719581581"><a name="p1959719581581"></a><a name="p1959719581581"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="12%" headers="mcps1.2.5.1.3 "><p id="p12597145820585"><a name="p12597145820585"></a><a name="p12597145820585"></a>是</p>
</td>
<td class="cellrowborder" valign="top" width="59%" headers="mcps1.2.5.1.4 "><p id="p7597125810587"><a name="p7597125810587"></a><a name="p7597125810587"></a>项目ID。</p>
</td>
</tr>
<tr id="row1859725835815"><td class="cellrowborder" valign="top" width="16%" headers="mcps1.2.5.1.1 "><p id="p1159715845811"><a name="p1159715845811"></a><a name="p1159715845811"></a>instance_id</p>
</td>
<td class="cellrowborder" valign="top" width="13%" headers="mcps1.2.5.1.2 "><p id="p1459715588587"><a name="p1459715588587"></a><a name="p1459715588587"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="12%" headers="mcps1.2.5.1.3 "><p id="p165971758175813"><a name="p165971758175813"></a><a name="p165971758175813"></a>是</p>
</td>
<td class="cellrowborder" valign="top" width="59%" headers="mcps1.2.5.1.4 "><p id="p14597135814582"><a name="p14597135814582"></a><a name="p14597135814582"></a>实例ID。</p>
</td>
</tr>
</tbody>
</table>

## 请求消息<a name="section185056589583"></a>

**请求参数**

无

**请求示例**

无

## 响应消息<a name="section9511105885810"></a>

**响应参数**

参数说明见[表2](#table05131858175815)。

**表 2**  参数说明

<a name="table05131858175815"></a>
<table><thead align="left"><tr id="row13597458105816"><th class="cellrowborder" valign="top" width="29.29%" id="mcps1.2.4.1.1"><p id="p1259795895815"><a name="p1259795895815"></a><a name="p1259795895815"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="11.110000000000001%" id="mcps1.2.4.1.2"><p id="p9597165814587"><a name="p9597165814587"></a><a name="p9597165814587"></a>类型</p>
</th>
<th class="cellrowborder" valign="top" width="59.599999999999994%" id="mcps1.2.4.1.3"><p id="p35971658125815"><a name="p35971658125815"></a><a name="p35971658125815"></a>说明</p>
</th>
</tr>
</thead>
<tbody><tr id="row1159795855816"><td class="cellrowborder" valign="top" width="29.29%" headers="mcps1.2.4.1.1 "><p id="p1597858145812"><a name="p1597858145812"></a><a name="p1597858145812"></a>coordinators</p>
</td>
<td class="cellrowborder" valign="top" width="11.110000000000001%" headers="mcps1.2.4.1.2 "><p id="p759714586582"><a name="p759714586582"></a><a name="p759714586582"></a>Array</p>
</td>
<td class="cellrowborder" valign="top" width="59.599999999999994%" headers="mcps1.2.4.1.3 "><p id="p13597458205814"><a name="p13597458205814"></a><a name="p13597458205814"></a>所有消费组对应的协调器列表。参数参见<a href="#table12517115825814">表3</a>。</p>
</td>
</tr>
</tbody>
</table>

**表 3**  coordinators参数说明

<a name="table12517115825814"></a>
<table><thead align="left"><tr id="row1598258105814"><th class="cellrowborder" valign="top" width="19.388061193880613%" id="mcps1.2.4.1.1"><p id="p75987587585"><a name="p75987587585"></a><a name="p75987587585"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="15.308469153084694%" id="mcps1.2.4.1.2"><p id="p959885845819"><a name="p959885845819"></a><a name="p959885845819"></a>类型</p>
</th>
<th class="cellrowborder" valign="top" width="65.3034696530347%" id="mcps1.2.4.1.3"><p id="p7598858145818"><a name="p7598858145818"></a><a name="p7598858145818"></a>说明</p>
</th>
</tr>
</thead>
<tbody><tr id="row1598858125817"><td class="cellrowborder" valign="top" width="19.388061193880613%" headers="mcps1.2.4.1.1 "><p id="p459845845818"><a name="p459845845818"></a><a name="p459845845818"></a>group_id</p>
</td>
<td class="cellrowborder" valign="top" width="15.308469153084694%" headers="mcps1.2.4.1.2 "><p id="p115981658195817"><a name="p115981658195817"></a><a name="p115981658195817"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="65.3034696530347%" headers="mcps1.2.4.1.3 "><p id="p65981258155812"><a name="p65981258155812"></a><a name="p65981258155812"></a>消费组ID。</p>
</td>
</tr>
<tr id="row459855875820"><td class="cellrowborder" valign="top" width="19.388061193880613%" headers="mcps1.2.4.1.1 "><p id="p1759875818583"><a name="p1759875818583"></a><a name="p1759875818583"></a>id</p>
</td>
<td class="cellrowborder" valign="top" width="15.308469153084694%" headers="mcps1.2.4.1.2 "><p id="p959845885814"><a name="p959845885814"></a><a name="p959845885814"></a>Integer</p>
</td>
<td class="cellrowborder" valign="top" width="65.3034696530347%" headers="mcps1.2.4.1.3 "><p id="p659815588585"><a name="p659815588585"></a><a name="p659815588585"></a>对应协调器的broker id。</p>
</td>
</tr>
<tr id="row17598258135814"><td class="cellrowborder" valign="top" width="19.388061193880613%" headers="mcps1.2.4.1.1 "><p id="p1359895885810"><a name="p1359895885810"></a><a name="p1359895885810"></a>host</p>
</td>
<td class="cellrowborder" valign="top" width="15.308469153084694%" headers="mcps1.2.4.1.2 "><p id="p25981058195815"><a name="p25981058195815"></a><a name="p25981058195815"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="65.3034696530347%" headers="mcps1.2.4.1.3 "><p id="p659812587581"><a name="p659812587581"></a><a name="p659812587581"></a>对应协调器的地址。</p>
</td>
</tr>
<tr id="row55983587581"><td class="cellrowborder" valign="top" width="19.388061193880613%" headers="mcps1.2.4.1.1 "><p id="p105981158105810"><a name="p105981158105810"></a><a name="p105981158105810"></a>port</p>
</td>
<td class="cellrowborder" valign="top" width="15.308469153084694%" headers="mcps1.2.4.1.2 "><p id="p859885815581"><a name="p859885815581"></a><a name="p859885815581"></a>Integer</p>
</td>
<td class="cellrowborder" valign="top" width="65.3034696530347%" headers="mcps1.2.4.1.3 "><p id="p15981258155818"><a name="p15981258155818"></a><a name="p15981258155818"></a>端口号。</p>
</td>
</tr>
</tbody>
</table>

**响应示例**

```
{
    "coordinators": [
        {
            "group_id": "XXXX",
            "id": 2,
            "host": "172.31.1.15",
            "port": 9091
        },
        {
            "group_id": "XXXX",
            "id": 2,
            "host": "172.31.1.15",
            "port": 9092
        },
        {
            "group_id": "XXXX",
            "id": 2,
            "host": "172.31.1.15",
            "port": 9092
        }
    ]
}
```

## 状态码<a name="section353095855814"></a>

查询成功的状态码如[表4](#table2530105835818)所示，其他响应见[表1](状态码.md#zh-cn_topic_0128036883_table5210141351517)。

**表 4**  状态码

<a name="table2530105835818"></a>
<table><thead align="left"><tr id="row135991758175815"><th class="cellrowborder" valign="top" width="15.15%" id="mcps1.2.3.1.1"><p id="p1259945835815"><a name="p1259945835815"></a><a name="p1259945835815"></a>状态码</p>
</th>
<th class="cellrowborder" valign="top" width="84.85000000000001%" id="mcps1.2.3.1.2"><p id="p259985875813"><a name="p259985875813"></a><a name="p259985875813"></a>描述</p>
</th>
</tr>
</thead>
<tbody><tr id="row15599758145815"><td class="cellrowborder" valign="top" width="15.15%" headers="mcps1.2.3.1.1 "><p id="p6599195855812"><a name="p6599195855812"></a><a name="p6599195855812"></a>200</p>
</td>
<td class="cellrowborder" valign="top" width="84.85000000000001%" headers="mcps1.2.3.1.2 "><p id="p13599758185818"><a name="p13599758185818"></a><a name="p13599758185818"></a>查询成功。</p>
</td>
</tr>
</tbody>
</table>

