# Kafka实例创建Topic<a name="ZH-CN_TOPIC_0171829508"></a>

## 功能介绍<a name="zh-cn_topic_0128036928_section281017251256"></a>

该接口用于向Kafka实例创建Topic。

## URI<a name="zh-cn_topic_0128036928_section133368463119"></a>

POST /v1.0/\{project\_id\}/instances/\{instance\_id\}/topics

参数说明见[表1](#zh-cn_topic_0128036928_table5338194611119)。

**表 1**  参数说明

<a name="zh-cn_topic_0128036928_table5338194611119"></a>
<table><thead align="left"><tr id="zh-cn_topic_0128036928_row84911646141118"><th class="cellrowborder" valign="top" width="16%" id="mcps1.2.5.1.1"><p id="zh-cn_topic_0128036928_p1449164691113"><a name="zh-cn_topic_0128036928_p1449164691113"></a><a name="zh-cn_topic_0128036928_p1449164691113"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="13%" id="mcps1.2.5.1.2"><p id="zh-cn_topic_0128036928_p2491164601115"><a name="zh-cn_topic_0128036928_p2491164601115"></a><a name="zh-cn_topic_0128036928_p2491164601115"></a>类型</p>
</th>
<th class="cellrowborder" valign="top" width="12%" id="mcps1.2.5.1.3"><p id="zh-cn_topic_0128036928_p144911646191112"><a name="zh-cn_topic_0128036928_p144911646191112"></a><a name="zh-cn_topic_0128036928_p144911646191112"></a>必选</p>
</th>
<th class="cellrowborder" valign="top" width="59%" id="mcps1.2.5.1.4"><p id="zh-cn_topic_0128036928_p74911246171112"><a name="zh-cn_topic_0128036928_p74911246171112"></a><a name="zh-cn_topic_0128036928_p74911246171112"></a>说明</p>
</th>
</tr>
</thead>
<tbody><tr id="zh-cn_topic_0128036928_row144911946201115"><td class="cellrowborder" valign="top" width="16%" headers="mcps1.2.5.1.1 "><p id="zh-cn_topic_0128036928_p349174618112"><a name="zh-cn_topic_0128036928_p349174618112"></a><a name="zh-cn_topic_0128036928_p349174618112"></a>project_id</p>
</td>
<td class="cellrowborder" valign="top" width="13%" headers="mcps1.2.5.1.2 "><p id="zh-cn_topic_0128036928_p949114651114"><a name="zh-cn_topic_0128036928_p949114651114"></a><a name="zh-cn_topic_0128036928_p949114651114"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="12%" headers="mcps1.2.5.1.3 "><p id="zh-cn_topic_0128036928_p1949117464112"><a name="zh-cn_topic_0128036928_p1949117464112"></a><a name="zh-cn_topic_0128036928_p1949117464112"></a>是</p>
</td>
<td class="cellrowborder" valign="top" width="59%" headers="mcps1.2.5.1.4 "><p id="zh-cn_topic_0128036928_p849114621111"><a name="zh-cn_topic_0128036928_p849114621111"></a><a name="zh-cn_topic_0128036928_p849114621111"></a>项目ID。</p>
</td>
</tr>
<tr id="zh-cn_topic_0128036928_row54910467110"><td class="cellrowborder" valign="top" width="16%" headers="mcps1.2.5.1.1 "><p id="zh-cn_topic_0128036928_p6491174620116"><a name="zh-cn_topic_0128036928_p6491174620116"></a><a name="zh-cn_topic_0128036928_p6491174620116"></a>instance_id</p>
</td>
<td class="cellrowborder" valign="top" width="13%" headers="mcps1.2.5.1.2 "><p id="zh-cn_topic_0128036928_p2491184671114"><a name="zh-cn_topic_0128036928_p2491184671114"></a><a name="zh-cn_topic_0128036928_p2491184671114"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="12%" headers="mcps1.2.5.1.3 "><p id="zh-cn_topic_0128036928_p1549164610114"><a name="zh-cn_topic_0128036928_p1549164610114"></a><a name="zh-cn_topic_0128036928_p1549164610114"></a>是</p>
</td>
<td class="cellrowborder" valign="top" width="59%" headers="mcps1.2.5.1.4 "><p id="zh-cn_topic_0128036928_p3491144613110"><a name="zh-cn_topic_0128036928_p3491144613110"></a><a name="zh-cn_topic_0128036928_p3491144613110"></a>实例ID</p>
</td>
</tr>
</tbody>
</table>

## 请求消息<a name="zh-cn_topic_0128036928_section8345124651115"></a>

**请求参数**

参数说明见[表2](#zh-cn_topic_0128036928_table14347154691119)。

**表 2**  参数说明

<a name="zh-cn_topic_0128036928_table14347154691119"></a>
<table><thead align="left"><tr id="zh-cn_topic_0128036928_row154923465114"><th class="cellrowborder" valign="top" width="17%" id="mcps1.2.5.1.1"><p id="zh-cn_topic_0128036928_p204921146111112"><a name="zh-cn_topic_0128036928_p204921146111112"></a><a name="zh-cn_topic_0128036928_p204921146111112"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="18%" id="mcps1.2.5.1.2"><p id="zh-cn_topic_0128036928_p13492104681119"><a name="zh-cn_topic_0128036928_p13492104681119"></a><a name="zh-cn_topic_0128036928_p13492104681119"></a>类型</p>
</th>
<th class="cellrowborder" valign="top" width="12%" id="mcps1.2.5.1.3"><p id="zh-cn_topic_0128036928_p13492124651111"><a name="zh-cn_topic_0128036928_p13492124651111"></a><a name="zh-cn_topic_0128036928_p13492124651111"></a>是否必选</p>
</th>
<th class="cellrowborder" valign="top" width="53%" id="mcps1.2.5.1.4"><p id="zh-cn_topic_0128036928_p9492154601120"><a name="zh-cn_topic_0128036928_p9492154601120"></a><a name="zh-cn_topic_0128036928_p9492154601120"></a>说明</p>
</th>
</tr>
</thead>
<tbody><tr id="zh-cn_topic_0128036928_row18492646191114"><td class="cellrowborder" valign="top" width="17%" headers="mcps1.2.5.1.1 "><p id="zh-cn_topic_0128036928_p749214615115"><a name="zh-cn_topic_0128036928_p749214615115"></a><a name="zh-cn_topic_0128036928_p749214615115"></a>id</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.2.5.1.2 "><p id="zh-cn_topic_0128036928_p449294631114"><a name="zh-cn_topic_0128036928_p449294631114"></a><a name="zh-cn_topic_0128036928_p449294631114"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="12%" headers="mcps1.2.5.1.3 "><p id="zh-cn_topic_0128036928_p16492846161110"><a name="zh-cn_topic_0128036928_p16492846161110"></a><a name="zh-cn_topic_0128036928_p16492846161110"></a>是</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.2.5.1.4 "><p id="zh-cn_topic_0128036928_p12492124681111"><a name="zh-cn_topic_0128036928_p12492124681111"></a><a name="zh-cn_topic_0128036928_p12492124681111"></a>topic名称，长度为4-64，以字母开头且只支持大小写字母、中横线、下划线以及数字。</p>
</td>
</tr>
<tr id="zh-cn_topic_0128036928_row1749224618119"><td class="cellrowborder" valign="top" width="17%" headers="mcps1.2.5.1.1 "><p id="zh-cn_topic_0128036928_p449224615114"><a name="zh-cn_topic_0128036928_p449224615114"></a><a name="zh-cn_topic_0128036928_p449224615114"></a>partition</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.2.5.1.2 "><p id="zh-cn_topic_0128036928_p164921446121117"><a name="zh-cn_topic_0128036928_p164921446121117"></a><a name="zh-cn_topic_0128036928_p164921446121117"></a>Integer</p>
</td>
<td class="cellrowborder" valign="top" width="12%" headers="mcps1.2.5.1.3 "><p id="zh-cn_topic_0128036928_p12492204613114"><a name="zh-cn_topic_0128036928_p12492204613114"></a><a name="zh-cn_topic_0128036928_p12492204613114"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.2.5.1.4 "><p id="zh-cn_topic_0128036928_p9494846151117"><a name="zh-cn_topic_0128036928_p9494846151117"></a><a name="zh-cn_topic_0128036928_p9494846151117"></a>topic分区数，设置消费的并发数。</p>
<p id="zh-cn_topic_0128036928_p74941746121117"><a name="zh-cn_topic_0128036928_p74941746121117"></a><a name="zh-cn_topic_0128036928_p74941746121117"></a>默认值为3，取值范围为1~20。</p>
</td>
</tr>
<tr id="zh-cn_topic_0128036928_row3494346171114"><td class="cellrowborder" valign="top" width="17%" headers="mcps1.2.5.1.1 "><p id="zh-cn_topic_0128036928_p04947464119"><a name="zh-cn_topic_0128036928_p04947464119"></a><a name="zh-cn_topic_0128036928_p04947464119"></a>replication</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.2.5.1.2 "><p id="zh-cn_topic_0128036928_p154941346121115"><a name="zh-cn_topic_0128036928_p154941346121115"></a><a name="zh-cn_topic_0128036928_p154941346121115"></a>Integer</p>
</td>
<td class="cellrowborder" valign="top" width="12%" headers="mcps1.2.5.1.3 "><p id="zh-cn_topic_0128036928_p1449420463110"><a name="zh-cn_topic_0128036928_p1449420463110"></a><a name="zh-cn_topic_0128036928_p1449420463110"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.2.5.1.4 "><p id="zh-cn_topic_0128036928_p1149414601112"><a name="zh-cn_topic_0128036928_p1149414601112"></a><a name="zh-cn_topic_0128036928_p1149414601112"></a>副本数，配置数据的可靠性</p>
<p id="zh-cn_topic_0128036928_p16494646181112"><a name="zh-cn_topic_0128036928_p16494646181112"></a><a name="zh-cn_topic_0128036928_p16494646181112"></a>默认值为3，取值范围为1~3。</p>
</td>
</tr>
<tr id="zh-cn_topic_0128036928_row5439123414418"><td class="cellrowborder" valign="top" width="17%" headers="mcps1.2.5.1.1 "><p id="zh-cn_topic_0128036928_p126894217446"><a name="zh-cn_topic_0128036928_p126894217446"></a><a name="zh-cn_topic_0128036928_p126894217446"></a>sync_replication</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.2.5.1.2 "><p id="zh-cn_topic_0128036928_p12681342184417"><a name="zh-cn_topic_0128036928_p12681342184417"></a><a name="zh-cn_topic_0128036928_p12681342184417"></a>Boolean</p>
</td>
<td class="cellrowborder" valign="top" width="12%" headers="mcps1.2.5.1.3 "><p id="zh-cn_topic_0128036928_p102687426440"><a name="zh-cn_topic_0128036928_p102687426440"></a><a name="zh-cn_topic_0128036928_p102687426440"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.2.5.1.4 "><p id="zh-cn_topic_0128036928_p62689423441"><a name="zh-cn_topic_0128036928_p62689423441"></a><a name="zh-cn_topic_0128036928_p62689423441"></a>是否开启同步复制，开启后，客户端生产消息时相应的也要设置acks=-1，否则不生效。</p>
<p id="zh-cn_topic_0128036928_p192687429448"><a name="zh-cn_topic_0128036928_p192687429448"></a><a name="zh-cn_topic_0128036928_p192687429448"></a>默认关闭。</p>
</td>
</tr>
<tr id="zh-cn_topic_0128036928_row4494846201111"><td class="cellrowborder" valign="top" width="17%" headers="mcps1.2.5.1.1 "><p id="zh-cn_topic_0128036928_p6494134661119"><a name="zh-cn_topic_0128036928_p6494134661119"></a><a name="zh-cn_topic_0128036928_p6494134661119"></a>retention_time</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.2.5.1.2 "><p id="zh-cn_topic_0128036928_p194941446151118"><a name="zh-cn_topic_0128036928_p194941446151118"></a><a name="zh-cn_topic_0128036928_p194941446151118"></a>Integer</p>
</td>
<td class="cellrowborder" valign="top" width="12%" headers="mcps1.2.5.1.3 "><p id="zh-cn_topic_0128036928_p549413462117"><a name="zh-cn_topic_0128036928_p549413462117"></a><a name="zh-cn_topic_0128036928_p549413462117"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.2.5.1.4 "><p id="zh-cn_topic_0128036928_p8494184661118"><a name="zh-cn_topic_0128036928_p8494184661118"></a><a name="zh-cn_topic_0128036928_p8494184661118"></a>消息老化时间。默认值为72。</p>
<p id="zh-cn_topic_0128036928_p12494546161116"><a name="zh-cn_topic_0128036928_p12494546161116"></a><a name="zh-cn_topic_0128036928_p12494546161116"></a>取值范围1~168，单位小时。</p>
</td>
</tr>
<tr id="zh-cn_topic_0128036928_row1049444651117"><td class="cellrowborder" valign="top" width="17%" headers="mcps1.2.5.1.1 "><p id="zh-cn_topic_0128036928_p114941646151117"><a name="zh-cn_topic_0128036928_p114941646151117"></a><a name="zh-cn_topic_0128036928_p114941646151117"></a>sync_message_flush</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.2.5.1.2 "><p id="zh-cn_topic_0128036928_p2049413469114"><a name="zh-cn_topic_0128036928_p2049413469114"></a><a name="zh-cn_topic_0128036928_p2049413469114"></a>Boolean</p>
</td>
<td class="cellrowborder" valign="top" width="12%" headers="mcps1.2.5.1.3 "><p id="zh-cn_topic_0128036928_p049494615110"><a name="zh-cn_topic_0128036928_p049494615110"></a><a name="zh-cn_topic_0128036928_p049494615110"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="53%" headers="mcps1.2.5.1.4 "><p id="zh-cn_topic_0128036928_p19494144617119"><a name="zh-cn_topic_0128036928_p19494144617119"></a><a name="zh-cn_topic_0128036928_p19494144617119"></a>是否使用同步落盘。默认值为false。同步落盘会导致性能降低。</p>
</td>
</tr>
</tbody>
</table>

**请求示例**

```
{
  "id" : "haha", 
  "partition" : 3, 
  "replication" : 3, 
  "sync_replication " : true, 
  "retention_time" : 10, 
  "sync_message_flush" : true
}
```

## 响应消息<a name="zh-cn_topic_0128036928_section837314461114"></a>

**响应参数**

参数说明见[表3](#zh-cn_topic_0128036928_table113758463117)。

**表 3**  参数说明

<a name="zh-cn_topic_0128036928_table113758463117"></a>
<table><thead align="left"><tr id="zh-cn_topic_0128036928_row049524619114"><th class="cellrowborder" valign="top" width="23.23%" id="mcps1.2.4.1.1"><p id="zh-cn_topic_0128036928_p154951446141113"><a name="zh-cn_topic_0128036928_p154951446141113"></a><a name="zh-cn_topic_0128036928_p154951446141113"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="21.21%" id="mcps1.2.4.1.2"><p id="zh-cn_topic_0128036928_p9495174614117"><a name="zh-cn_topic_0128036928_p9495174614117"></a><a name="zh-cn_topic_0128036928_p9495174614117"></a>类型</p>
</th>
<th class="cellrowborder" valign="top" width="55.559999999999995%" id="mcps1.2.4.1.3"><p id="zh-cn_topic_0128036928_p949515469114"><a name="zh-cn_topic_0128036928_p949515469114"></a><a name="zh-cn_topic_0128036928_p949515469114"></a>说明</p>
</th>
</tr>
</thead>
<tbody><tr id="zh-cn_topic_0128036928_row16495194631111"><td class="cellrowborder" valign="top" width="23.23%" headers="mcps1.2.4.1.1 "><p id="zh-cn_topic_0128036928_p649554610116"><a name="zh-cn_topic_0128036928_p649554610116"></a><a name="zh-cn_topic_0128036928_p649554610116"></a>id</p>
</td>
<td class="cellrowborder" valign="top" width="21.21%" headers="mcps1.2.4.1.2 "><p id="zh-cn_topic_0128036928_p19495184671120"><a name="zh-cn_topic_0128036928_p19495184671120"></a><a name="zh-cn_topic_0128036928_p19495184671120"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="55.559999999999995%" headers="mcps1.2.4.1.3 "><p id="zh-cn_topic_0128036928_p44956464114"><a name="zh-cn_topic_0128036928_p44956464114"></a><a name="zh-cn_topic_0128036928_p44956464114"></a>topic名称</p>
</td>
</tr>
</tbody>
</table>

**响应示例**

```
{  
"id": "haha"
}
```

## 状态码<a name="zh-cn_topic_0128036928_section5381204691118"></a>

操作成功的状态码如[表4](#zh-cn_topic_0128036928_table4381154610118)所示，其他响应见[状态码](状态码.md)。

**表 4**  状态码

<a name="zh-cn_topic_0128036928_table4381154610118"></a>
<table><thead align="left"><tr id="zh-cn_topic_0128036928_row549534661115"><th class="cellrowborder" valign="top" width="15.15%" id="mcps1.2.3.1.1"><p id="zh-cn_topic_0128036928_p13495134691117"><a name="zh-cn_topic_0128036928_p13495134691117"></a><a name="zh-cn_topic_0128036928_p13495134691117"></a>状态码</p>
</th>
<th class="cellrowborder" valign="top" width="84.85000000000001%" id="mcps1.2.3.1.2"><p id="zh-cn_topic_0128036928_p11496174618117"><a name="zh-cn_topic_0128036928_p11496174618117"></a><a name="zh-cn_topic_0128036928_p11496174618117"></a>描述</p>
</th>
</tr>
</thead>
<tbody><tr id="zh-cn_topic_0128036928_row14965461118"><td class="cellrowborder" valign="top" width="15.15%" headers="mcps1.2.3.1.1 "><p id="zh-cn_topic_0128036928_p1449610463118"><a name="zh-cn_topic_0128036928_p1449610463118"></a><a name="zh-cn_topic_0128036928_p1449610463118"></a>200</p>
</td>
<td class="cellrowborder" valign="top" width="84.85000000000001%" headers="mcps1.2.3.1.2 "><p id="zh-cn_topic_0128036928_p14496204612119"><a name="zh-cn_topic_0128036928_p14496204612119"></a><a name="zh-cn_topic_0128036928_p14496204612119"></a>创建成功。</p>
</td>
</tr>
</tbody>
</table>

