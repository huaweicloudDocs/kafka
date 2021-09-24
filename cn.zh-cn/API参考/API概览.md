# API概览<a name="kafka-api-180423002"></a>

**表 1**  实例管理类接口

<a name="zh-cn_topic_0172515004_zh-cn_topic_0171836020_zh-cn_topic_0166889586_table88711342351"></a>
<table><thead align="left"><tr id="zh-cn_topic_0172515004_zh-cn_topic_0171836020_zh-cn_topic_0166889586_row88716427513"><th class="cellrowborder" valign="top" width="30.17%" id="mcps1.2.3.1.1"><p id="zh-cn_topic_0172515004_zh-cn_topic_0171836020_zh-cn_topic_0166889586_p1871442156"><a name="zh-cn_topic_0172515004_zh-cn_topic_0171836020_zh-cn_topic_0166889586_p1871442156"></a><a name="zh-cn_topic_0172515004_zh-cn_topic_0171836020_zh-cn_topic_0166889586_p1871442156"></a>API</p>
</th>
<th class="cellrowborder" valign="top" width="69.83%" id="mcps1.2.3.1.2"><p id="zh-cn_topic_0172515004_zh-cn_topic_0171836020_zh-cn_topic_0166889586_p12871194215516"><a name="zh-cn_topic_0172515004_zh-cn_topic_0171836020_zh-cn_topic_0166889586_p12871194215516"></a><a name="zh-cn_topic_0172515004_zh-cn_topic_0171836020_zh-cn_topic_0166889586_p12871194215516"></a>说明</p>
</th>
</tr>
</thead>
<tbody><tr id="zh-cn_topic_0172515004_zh-cn_topic_0171836020_zh-cn_topic_0166889586_row08723421515"><td class="cellrowborder" valign="top" width="30.17%" headers="mcps1.2.3.1.1 "><p id="p797653914012"><a name="p797653914012"></a><a name="p797653914012"></a><a href="生命周期管理.md">生命周期管理</a></p>
</td>
<td class="cellrowborder" valign="top" width="69.83%" headers="mcps1.2.3.1.2 "><p id="p179753394013"><a name="p179753394013"></a><a name="p179753394013"></a>包括创建实例（按需）、修改实例信息、查询实例、删除实例。</p>
</td>
</tr>
<tr id="zh-cn_topic_0172515004_zh-cn_topic_0171836020_zh-cn_topic_0166889586_row1187211423510"><td class="cellrowborder" valign="top" width="30.17%" headers="mcps1.2.3.1.1 "><p id="p1497415395017"><a name="p1497415395017"></a><a name="p1497415395017"></a><a href="实例管理.md">实例管理</a></p>
</td>
<td class="cellrowborder" valign="top" width="69.83%" headers="mcps1.2.3.1.2 "><p id="p1197310392010"><a name="p1197310392010"></a><a name="p1197310392010"></a>包括重置密码、重置Manager密码、重启Manager、开启或关闭实例自动创建Topic功能、修改实例跨VPC访问的内网IP、查询Kafka集群元数据信息、查询消费组信息、重置消费组消费进度到指定位置、查询Kafka实例的协调器信息、新增Kafka实例指定Topic分区、修改分区的副本、查询Topic的磁盘存储情况。</p>
</td>
</tr>
<tr id="zh-cn_topic_0172515004_zh-cn_topic_0171836020_zh-cn_topic_0166889586_row2087254219512"><td class="cellrowborder" valign="top" width="30.17%" headers="mcps1.2.3.1.1 "><p id="p157086354420"><a name="p157086354420"></a><a name="p157086354420"></a><a href="转储管理.md">转储管理</a></p>
</td>
<td class="cellrowborder" valign="top" width="69.83%" headers="mcps1.2.3.1.2 "><p id="p11969439004"><a name="p11969439004"></a><a name="p11969439004"></a>包括创建实例的转储节点、创建转储任务、查询转储任务列表、修改转储任务的配额、查询单个转储任务、删除单个转储任务。</p>
</td>
</tr>
<tr id="zh-cn_topic_0172515004_zh-cn_topic_0171836020_zh-cn_topic_0166889586_row6873942558"><td class="cellrowborder" valign="top" width="30.17%" headers="mcps1.2.3.1.1 "><p id="p27061535184219"><a name="p27061535184219"></a><a name="p27061535184219"></a><a href="规格变更管理.md">规格变更管理</a></p>
</td>
<td class="cellrowborder" valign="top" width="69.83%" headers="mcps1.2.3.1.2 "><p id="p1496716391603"><a name="p1496716391603"></a><a name="p1496716391603"></a>包括查询实例的扩容规格列表、实例规格变更。</p>
</td>
</tr>
<tr id="zh-cn_topic_0172515004_zh-cn_topic_0171836020_zh-cn_topic_0166889586_row1045818383121"><td class="cellrowborder" valign="top" width="30.17%" headers="mcps1.2.3.1.1 "><p id="p1569923513428"><a name="p1569923513428"></a><a name="p1569923513428"></a><a href="主题管理.md">主题管理</a></p>
</td>
<td class="cellrowborder" valign="top" width="69.83%" headers="mcps1.2.3.1.2 "><p id="p19965193910010"><a name="p19965193910010"></a><a name="p19965193910010"></a>包括查询Topic、创建Topic、修改Topic、批量删除Topic、查询Topic详细信息。</p>
</td>
</tr>
<tr id="row1259614266181"><td class="cellrowborder" valign="top" width="30.17%" headers="mcps1.2.3.1.1 "><p id="p20597172681810"><a name="p20597172681810"></a><a name="p20597172681810"></a><a href="用户管理.md">用户管理</a></p>
</td>
<td class="cellrowborder" valign="top" width="69.83%" headers="mcps1.2.3.1.2 "><p id="p65971026151811"><a name="p65971026151811"></a><a name="p65971026151811"></a>包括查询消息、查询分区指定偏移量的消息、查询分区指定时间段的消息、查询分区最新消息的位置、查询分区最早消息的位置。</p>
</td>
</tr>
<tr id="row881532917182"><td class="cellrowborder" valign="top" width="30.17%" headers="mcps1.2.3.1.1 "><p id="p158162292181"><a name="p158162292181"></a><a name="p158162292181"></a><a href="消息查询.md">消息查询</a></p>
</td>
<td class="cellrowborder" valign="top" width="69.83%" headers="mcps1.2.3.1.2 "><p id="p1781682917186"><a name="p1781682917186"></a><a name="p1781682917186"></a>包括查询实例的后台任务列表、查询后台任务管理中的指定记录、删除后台任务管理中的指定记录。</p>
</td>
</tr>
<tr id="row1981933211188"><td class="cellrowborder" valign="top" width="30.17%" headers="mcps1.2.3.1.1 "><p id="p11819193211189"><a name="p11819193211189"></a><a name="p11819193211189"></a><a href="后台任务管理.md">后台任务管理</a></p>
</td>
<td class="cellrowborder" valign="top" width="69.83%" headers="mcps1.2.3.1.2 "><p id="p1181916322181"><a name="p1181916322181"></a><a name="p1181916322181"></a>包括批量添加或删除实例标签、查询实例标签、查询项目标签。</p>
</td>
</tr>
<tr id="row917763641819"><td class="cellrowborder" valign="top" width="30.17%" headers="mcps1.2.3.1.1 "><p id="p417753601817"><a name="p417753601817"></a><a name="p417753601817"></a><a href="标签管理.md">标签管理</a></p>
</td>
<td class="cellrowborder" valign="top" width="69.83%" headers="mcps1.2.3.1.2 "><p id="p9177736191815"><a name="p9177736191815"></a><a name="p9177736191815"></a>包括查询产品规格列表、查询可用区信息、查询维护时间窗、查询实例在CES的监控层级关系。</p>
</td>
</tr>
</tbody>
</table>

