# 查询实例在CES的监控层级关系<a name="ZH-CN_TOPIC_0210486909"></a>

## URI<a name="section181491738185811"></a>

GET /v1.0/\{project\_id\}/instances/\{instance\_id\}/ceshierarchy

参数说明见[表1](#table115310388582)。

**表 1**  参数说明

<a name="table115310388582"></a>
<table><thead align="left"><tr id="row1150983920583"><th class="cellrowborder" valign="top" width="16%" id="mcps1.2.5.1.1"><p id="p350943975815"><a name="p350943975815"></a><a name="p350943975815"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="13%" id="mcps1.2.5.1.2"><p id="p115091398583"><a name="p115091398583"></a><a name="p115091398583"></a>类型</p>
</th>
<th class="cellrowborder" valign="top" width="12%" id="mcps1.2.5.1.3"><p id="p3509439185810"><a name="p3509439185810"></a><a name="p3509439185810"></a>必选</p>
</th>
<th class="cellrowborder" valign="top" width="59%" id="mcps1.2.5.1.4"><p id="p350917394588"><a name="p350917394588"></a><a name="p350917394588"></a>说明</p>
</th>
</tr>
</thead>
<tbody><tr id="row14509539175816"><td class="cellrowborder" valign="top" width="16%" headers="mcps1.2.5.1.1 "><p id="p18509153920583"><a name="p18509153920583"></a><a name="p18509153920583"></a>project_id</p>
</td>
<td class="cellrowborder" valign="top" width="13%" headers="mcps1.2.5.1.2 "><p id="p85091739205812"><a name="p85091739205812"></a><a name="p85091739205812"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="12%" headers="mcps1.2.5.1.3 "><p id="p3509939115819"><a name="p3509939115819"></a><a name="p3509939115819"></a>是</p>
</td>
<td class="cellrowborder" valign="top" width="59%" headers="mcps1.2.5.1.4 "><p id="p17509183985813"><a name="p17509183985813"></a><a name="p17509183985813"></a>项目ID。</p>
</td>
</tr>
<tr id="row95098393589"><td class="cellrowborder" valign="top" width="16%" headers="mcps1.2.5.1.1 "><p id="p10509193995817"><a name="p10509193995817"></a><a name="p10509193995817"></a>instance_id</p>
</td>
<td class="cellrowborder" valign="top" width="13%" headers="mcps1.2.5.1.2 "><p id="p4509839135814"><a name="p4509839135814"></a><a name="p4509839135814"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="12%" headers="mcps1.2.5.1.3 "><p id="p25093392583"><a name="p25093392583"></a><a name="p25093392583"></a>是</p>
</td>
<td class="cellrowborder" valign="top" width="59%" headers="mcps1.2.5.1.4 "><p id="p250918395586"><a name="p250918395586"></a><a name="p250918395586"></a>实例ID。</p>
</td>
</tr>
</tbody>
</table>

## 请求消息<a name="section21757383588"></a>

**请求参数**

无

**请求示例**

无

## 响应消息<a name="section181781438175818"></a>

**响应参数**

参数说明见[表2](#table221513816589)。

**表 2**  响应参数说明

<a name="table221513816589"></a>
<table><thead align="left"><tr id="row1651013918584"><th class="cellrowborder" valign="top" width="23.23%" id="mcps1.2.4.1.1"><p id="p5510339185810"><a name="p5510339185810"></a><a name="p5510339185810"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="22.220000000000002%" id="mcps1.2.4.1.2"><p id="p6510163995818"><a name="p6510163995818"></a><a name="p6510163995818"></a>类型</p>
</th>
<th class="cellrowborder" valign="top" width="54.55%" id="mcps1.2.4.1.3"><p id="p151033919587"><a name="p151033919587"></a><a name="p151033919587"></a>说明</p>
</th>
</tr>
</thead>
<tbody><tr id="row7510113915585"><td class="cellrowborder" valign="top" width="23.23%" headers="mcps1.2.4.1.1 "><p id="p55101239145815"><a name="p55101239145815"></a><a name="p55101239145815"></a>dimensions</p>
</td>
<td class="cellrowborder" valign="top" width="22.220000000000002%" headers="mcps1.2.4.1.2 "><p id="p1451073945810"><a name="p1451073945810"></a><a name="p1451073945810"></a>Array of object dimensions</p>
</td>
<td class="cellrowborder" valign="top" width="54.55%" headers="mcps1.2.4.1.3 "><p id="p105101039195815"><a name="p105101039195815"></a><a name="p105101039195815"></a>监控维度。参数参考<a href="#table15247183816588">表3</a>。</p>
</td>
</tr>
<tr id="row165102398589"><td class="cellrowborder" valign="top" width="23.23%" headers="mcps1.2.4.1.1 "><p id="p55100397583"><a name="p55100397583"></a><a name="p55100397583"></a>instance_ids</p>
</td>
<td class="cellrowborder" valign="top" width="22.220000000000002%" headers="mcps1.2.4.1.2 "><p id="p105101339125818"><a name="p105101339125818"></a><a name="p105101339125818"></a>Array of object instance_ids</p>
</td>
<td class="cellrowborder" valign="top" width="54.55%" headers="mcps1.2.4.1.3 "><p id="p1251083912584"><a name="p1251083912584"></a><a name="p1251083912584"></a>实例信息。参数参考<a href="#table15291173812580">表4</a>。</p>
</td>
</tr>
<tr id="row4510239155813"><td class="cellrowborder" valign="top" width="23.23%" headers="mcps1.2.4.1.1 "><p id="p1351015397588"><a name="p1351015397588"></a><a name="p1351015397588"></a>nodes</p>
</td>
<td class="cellrowborder" valign="top" width="22.220000000000002%" headers="mcps1.2.4.1.2 "><p id="p145105391583"><a name="p145105391583"></a><a name="p145105391583"></a>Array of object nodes</p>
</td>
<td class="cellrowborder" valign="top" width="54.55%" headers="mcps1.2.4.1.3 "><p id="p4510123965814"><a name="p4510123965814"></a><a name="p4510123965814"></a>节点信息。参数参考<a href="#table533133815815">表5</a>。</p>
</td>
</tr>
<tr id="row251043912583"><td class="cellrowborder" valign="top" width="23.23%" headers="mcps1.2.4.1.1 "><p id="p19510173925812"><a name="p19510173925812"></a><a name="p19510173925812"></a>queues</p>
</td>
<td class="cellrowborder" valign="top" width="22.220000000000002%" headers="mcps1.2.4.1.2 "><p id="p4510123913589"><a name="p4510123913589"></a><a name="p4510123913589"></a>Array of object queues</p>
</td>
<td class="cellrowborder" valign="top" width="54.55%" headers="mcps1.2.4.1.3 "><p id="p451083911588"><a name="p451083911588"></a><a name="p451083911588"></a>队列信息。参数参考<a href="#table16342153865818">表6</a>。</p>
</td>
</tr>
<tr id="row9510173913584"><td class="cellrowborder" valign="top" width="23.23%" headers="mcps1.2.4.1.1 "><p id="p251073995811"><a name="p251073995811"></a><a name="p251073995811"></a>groups</p>
</td>
<td class="cellrowborder" valign="top" width="22.220000000000002%" headers="mcps1.2.4.1.2 "><p id="p145101339145816"><a name="p145101339145816"></a><a name="p145101339145816"></a>Array of object groups</p>
</td>
<td class="cellrowborder" valign="top" width="54.55%" headers="mcps1.2.4.1.3 "><p id="p851003915589"><a name="p851003915589"></a><a name="p851003915589"></a>消费组信息。参数参考<a href="#table1236911381584">表7</a>。</p>
</td>
</tr>
</tbody>
</table>

**表 3**  dimensions参数说明

<a name="table15247183816588"></a>
<table><thead align="left"><tr id="row2510113915581"><th class="cellrowborder" valign="top" width="23.23%" id="mcps1.2.4.1.1"><p id="p11511139195816"><a name="p11511139195816"></a><a name="p11511139195816"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="22.220000000000002%" id="mcps1.2.4.1.2"><p id="p1951103955820"><a name="p1951103955820"></a><a name="p1951103955820"></a>类型</p>
</th>
<th class="cellrowborder" valign="top" width="54.55%" id="mcps1.2.4.1.3"><p id="p185111439155817"><a name="p185111439155817"></a><a name="p185111439155817"></a>说明</p>
</th>
</tr>
</thead>
<tbody><tr id="row7511123918582"><td class="cellrowborder" valign="top" width="23.23%" headers="mcps1.2.4.1.1 "><p id="p1451193945813"><a name="p1451193945813"></a><a name="p1451193945813"></a>name</p>
</td>
<td class="cellrowborder" valign="top" width="22.220000000000002%" headers="mcps1.2.4.1.2 "><p id="p1511193918586"><a name="p1511193918586"></a><a name="p1511193918586"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="54.55%" headers="mcps1.2.4.1.3 "><p id="p2051183995810"><a name="p2051183995810"></a><a name="p2051183995810"></a>监控维度名称。</p>
</td>
</tr>
<tr id="row15511103920584"><td class="cellrowborder" valign="top" width="23.23%" headers="mcps1.2.4.1.1 "><p id="p1651123965816"><a name="p1651123965816"></a><a name="p1651123965816"></a>metrics</p>
</td>
<td class="cellrowborder" valign="top" width="22.220000000000002%" headers="mcps1.2.4.1.2 "><p id="p1051133955810"><a name="p1051133955810"></a><a name="p1051133955810"></a>Array of object metrics</p>
</td>
<td class="cellrowborder" valign="top" width="54.55%" headers="mcps1.2.4.1.3 "><p id="p16511939125817"><a name="p16511939125817"></a><a name="p16511939125817"></a>监控指标名称。参数参考<a href="#table15395838135813">表10</a>。</p>
</td>
</tr>
<tr id="row135111839125818"><td class="cellrowborder" valign="top" width="23.23%" headers="mcps1.2.4.1.1 "><p id="p1511163975811"><a name="p1511163975811"></a><a name="p1511163975811"></a>key_name</p>
</td>
<td class="cellrowborder" valign="top" width="22.220000000000002%" headers="mcps1.2.4.1.2 "><p id="p1351173925811"><a name="p1351173925811"></a><a name="p1351173925811"></a>Array of object key_name</p>
</td>
<td class="cellrowborder" valign="top" width="54.55%" headers="mcps1.2.4.1.3 "><p id="p7511039155815"><a name="p7511039155815"></a><a name="p7511039155815"></a>监控查询使用的key。</p>
</td>
</tr>
<tr id="row1051153911584"><td class="cellrowborder" valign="top" width="23.23%" headers="mcps1.2.4.1.1 "><p id="p125114397585"><a name="p125114397585"></a><a name="p125114397585"></a>dim_router</p>
</td>
<td class="cellrowborder" valign="top" width="22.220000000000002%" headers="mcps1.2.4.1.2 "><p id="p1051113918586"><a name="p1051113918586"></a><a name="p1051113918586"></a>Array of object dim_router</p>
</td>
<td class="cellrowborder" valign="top" width="54.55%" headers="mcps1.2.4.1.3 "><p id="p6511133912585"><a name="p6511133912585"></a><a name="p6511133912585"></a>监控维度路由。</p>
</td>
</tr>
<tr id="row13511193911587"><td class="cellrowborder" valign="top" width="23.23%" headers="mcps1.2.4.1.1 "><p id="p1651113392585"><a name="p1651113392585"></a><a name="p1651113392585"></a>children</p>
</td>
<td class="cellrowborder" valign="top" width="22.220000000000002%" headers="mcps1.2.4.1.2 "><p id="p15117395589"><a name="p15117395589"></a><a name="p15117395589"></a>Array of object children</p>
</td>
<td class="cellrowborder" valign="top" width="54.55%" headers="mcps1.2.4.1.3 "><p id="p1451117399586"><a name="p1451117399586"></a><a name="p1451117399586"></a>子维度列表。参数参考<a href="#table15304113855815">表8</a>。</p>
</td>
</tr>
</tbody>
</table>

**表 4**  instance\_ids参数说明

<a name="table15291173812580"></a>
<table><thead align="left"><tr id="row05112397589"><th class="cellrowborder" valign="top" width="23.23%" id="mcps1.2.4.1.1"><p id="p105112039115816"><a name="p105112039115816"></a><a name="p105112039115816"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="22.220000000000002%" id="mcps1.2.4.1.2"><p id="p1511173905814"><a name="p1511173905814"></a><a name="p1511173905814"></a>类型</p>
</th>
<th class="cellrowborder" valign="top" width="54.55%" id="mcps1.2.4.1.3"><p id="p12511103917588"><a name="p12511103917588"></a><a name="p12511103917588"></a>说明</p>
</th>
</tr>
</thead>
<tbody><tr id="row5511103925811"><td class="cellrowborder" valign="top" width="23.23%" headers="mcps1.2.4.1.1 "><p id="p1251213915584"><a name="p1251213915584"></a><a name="p1251213915584"></a>name</p>
</td>
<td class="cellrowborder" valign="top" width="22.220000000000002%" headers="mcps1.2.4.1.2 "><p id="p85127399583"><a name="p85127399583"></a><a name="p85127399583"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="54.55%" headers="mcps1.2.4.1.3 "><p id="p151210394588"><a name="p151210394588"></a><a name="p151210394588"></a>实例ID。</p>
</td>
</tr>
</tbody>
</table>

**表 5**  nodes参数说明

<a name="table533133815815"></a>
<table><thead align="left"><tr id="row0513539165813"><th class="cellrowborder" valign="top" width="23.23%" id="mcps1.2.4.1.1"><p id="p15513183915815"><a name="p15513183915815"></a><a name="p15513183915815"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="22.220000000000002%" id="mcps1.2.4.1.2"><p id="p19513173911583"><a name="p19513173911583"></a><a name="p19513173911583"></a>类型</p>
</th>
<th class="cellrowborder" valign="top" width="54.55%" id="mcps1.2.4.1.3"><p id="p16513153995819"><a name="p16513153995819"></a><a name="p16513153995819"></a>说明</p>
</th>
</tr>
</thead>
<tbody><tr id="row15513183905812"><td class="cellrowborder" valign="top" width="23.23%" headers="mcps1.2.4.1.1 "><p id="p5513139155812"><a name="p5513139155812"></a><a name="p5513139155812"></a>name</p>
</td>
<td class="cellrowborder" valign="top" width="22.220000000000002%" headers="mcps1.2.4.1.2 "><p id="p165131839125820"><a name="p165131839125820"></a><a name="p165131839125820"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="54.55%" headers="mcps1.2.4.1.3 "><p id="p10513163965818"><a name="p10513163965818"></a><a name="p10513163965818"></a>节点名称。</p>
</td>
</tr>
</tbody>
</table>

**表 6**  queues参数说明

<a name="table16342153865818"></a>
<table><thead align="left"><tr id="row1051383915580"><th class="cellrowborder" valign="top" width="23.23%" id="mcps1.2.4.1.1"><p id="p8513183975815"><a name="p8513183975815"></a><a name="p8513183975815"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="22.220000000000002%" id="mcps1.2.4.1.2"><p id="p651393914582"><a name="p651393914582"></a><a name="p651393914582"></a>类型</p>
</th>
<th class="cellrowborder" valign="top" width="54.55%" id="mcps1.2.4.1.3"><p id="p1513133945820"><a name="p1513133945820"></a><a name="p1513133945820"></a>说明</p>
</th>
</tr>
</thead>
<tbody><tr id="row20513203918589"><td class="cellrowborder" valign="top" width="23.23%" headers="mcps1.2.4.1.1 "><p id="p2513173955814"><a name="p2513173955814"></a><a name="p2513173955814"></a>name</p>
</td>
<td class="cellrowborder" valign="top" width="22.220000000000002%" headers="mcps1.2.4.1.2 "><p id="p1551333915810"><a name="p1551333915810"></a><a name="p1551333915810"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="54.55%" headers="mcps1.2.4.1.3 "><p id="p5513143915811"><a name="p5513143915811"></a><a name="p5513143915811"></a>topic名称。</p>
</td>
</tr>
<tr id="row12513139175814"><td class="cellrowborder" valign="top" width="23.23%" headers="mcps1.2.4.1.1 "><p id="p9513153918589"><a name="p9513153918589"></a><a name="p9513153918589"></a>partitions</p>
</td>
<td class="cellrowborder" valign="top" width="22.220000000000002%" headers="mcps1.2.4.1.2 "><p id="p6513133916585"><a name="p6513133916585"></a><a name="p6513133916585"></a>Array of object partitions</p>
</td>
<td class="cellrowborder" valign="top" width="54.55%" headers="mcps1.2.4.1.3 "><p id="p351333916580"><a name="p351333916580"></a><a name="p351333916580"></a>分区列表。参数参见<a href="#table1358103815582">表9</a>。</p>
</td>
</tr>
</tbody>
</table>

**表 7**  groups参数说明

<a name="table1236911381584"></a>
<table><thead align="left"><tr id="row25141139145811"><th class="cellrowborder" valign="top" width="23.23%" id="mcps1.2.4.1.1"><p id="p85141939145820"><a name="p85141939145820"></a><a name="p85141939145820"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="22.220000000000002%" id="mcps1.2.4.1.2"><p id="p551411391586"><a name="p551411391586"></a><a name="p551411391586"></a>类型</p>
</th>
<th class="cellrowborder" valign="top" width="54.55%" id="mcps1.2.4.1.3"><p id="p175141039135819"><a name="p175141039135819"></a><a name="p175141039135819"></a>说明</p>
</th>
</tr>
</thead>
<tbody><tr id="row7514103935818"><td class="cellrowborder" valign="top" width="23.23%" headers="mcps1.2.4.1.1 "><p id="p1551453915588"><a name="p1551453915588"></a><a name="p1551453915588"></a>name</p>
</td>
<td class="cellrowborder" valign="top" width="22.220000000000002%" headers="mcps1.2.4.1.2 "><p id="p1051419396583"><a name="p1051419396583"></a><a name="p1051419396583"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="54.55%" headers="mcps1.2.4.1.3 "><p id="p95141039175813"><a name="p95141039175813"></a><a name="p95141039175813"></a>消费组名称。</p>
</td>
</tr>
<tr id="row1651413915588"><td class="cellrowborder" valign="top" width="23.23%" headers="mcps1.2.4.1.1 "><p id="p1514339115814"><a name="p1514339115814"></a><a name="p1514339115814"></a>queues</p>
</td>
<td class="cellrowborder" valign="top" width="22.220000000000002%" headers="mcps1.2.4.1.2 "><p id="p1951413905816"><a name="p1951413905816"></a><a name="p1951413905816"></a>Array of object queues</p>
</td>
<td class="cellrowborder" valign="top" width="54.55%" headers="mcps1.2.4.1.3 "><p id="p1051403995814"><a name="p1051403995814"></a><a name="p1051403995814"></a>队列信息。</p>
</td>
</tr>
</tbody>
</table>

**表 8**  children参数说明

<a name="table15304113855815"></a>
<table><thead align="left"><tr id="row65127395582"><th class="cellrowborder" valign="top" width="23.23%" id="mcps1.2.4.1.1"><p id="p13512939155818"><a name="p13512939155818"></a><a name="p13512939155818"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="22.220000000000002%" id="mcps1.2.4.1.2"><p id="p251253917582"><a name="p251253917582"></a><a name="p251253917582"></a>类型</p>
</th>
<th class="cellrowborder" valign="top" width="54.55%" id="mcps1.2.4.1.3"><p id="p35121339195819"><a name="p35121339195819"></a><a name="p35121339195819"></a>说明</p>
</th>
</tr>
</thead>
<tbody><tr id="row13512173920587"><td class="cellrowborder" valign="top" width="23.23%" headers="mcps1.2.4.1.1 "><p id="p12512133985817"><a name="p12512133985817"></a><a name="p12512133985817"></a>name</p>
</td>
<td class="cellrowborder" valign="top" width="22.220000000000002%" headers="mcps1.2.4.1.2 "><p id="p65122394581"><a name="p65122394581"></a><a name="p65122394581"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="54.55%" headers="mcps1.2.4.1.3 "><p id="p145121339145818"><a name="p145121339145818"></a><a name="p145121339145818"></a>子维度名称。</p>
</td>
</tr>
<tr id="row145121739175810"><td class="cellrowborder" valign="top" width="23.23%" headers="mcps1.2.4.1.1 "><p id="p13512839115818"><a name="p13512839115818"></a><a name="p13512839115818"></a>metrics</p>
</td>
<td class="cellrowborder" valign="top" width="22.220000000000002%" headers="mcps1.2.4.1.2 "><p id="p7512163915583"><a name="p7512163915583"></a><a name="p7512163915583"></a>Array of String</p>
</td>
<td class="cellrowborder" valign="top" width="54.55%" headers="mcps1.2.4.1.3 "><p id="p105121739135818"><a name="p105121739135818"></a><a name="p105121739135818"></a>监控指标名称列表。参数参见<a href="#table15395838135813">表10</a>。</p>
</td>
</tr>
<tr id="row19512173913582"><td class="cellrowborder" valign="top" width="23.23%" headers="mcps1.2.4.1.1 "><p id="p751293945811"><a name="p751293945811"></a><a name="p751293945811"></a>key_name</p>
</td>
<td class="cellrowborder" valign="top" width="22.220000000000002%" headers="mcps1.2.4.1.2 "><p id="p115128393585"><a name="p115128393585"></a><a name="p115128393585"></a>Array of String</p>
</td>
<td class="cellrowborder" valign="top" width="54.55%" headers="mcps1.2.4.1.3 "><p id="p8512339125816"><a name="p8512339125816"></a><a name="p8512339125816"></a>监控查询使用的key。</p>
</td>
</tr>
<tr id="row195124398581"><td class="cellrowborder" valign="top" width="23.23%" headers="mcps1.2.4.1.1 "><p id="p155128392581"><a name="p155128392581"></a><a name="p155128392581"></a>dim_router</p>
</td>
<td class="cellrowborder" valign="top" width="22.220000000000002%" headers="mcps1.2.4.1.2 "><p id="p16512113912588"><a name="p16512113912588"></a><a name="p16512113912588"></a>Array of String</p>
</td>
<td class="cellrowborder" valign="top" width="54.55%" headers="mcps1.2.4.1.3 "><p id="p155127399582"><a name="p155127399582"></a><a name="p155127399582"></a>监控维度路由</p>
</td>
</tr>
</tbody>
</table>

**表 9**  partitions参数说明

<a name="table1358103815582"></a>
<table><thead align="left"><tr id="row751323916584"><th class="cellrowborder" valign="top" width="23.23%" id="mcps1.2.4.1.1"><p id="p155131139205820"><a name="p155131139205820"></a><a name="p155131139205820"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="22.220000000000002%" id="mcps1.2.4.1.2"><p id="p1351303955813"><a name="p1351303955813"></a><a name="p1351303955813"></a>类型</p>
</th>
<th class="cellrowborder" valign="top" width="54.55%" id="mcps1.2.4.1.3"><p id="p1513039145817"><a name="p1513039145817"></a><a name="p1513039145817"></a>说明</p>
</th>
</tr>
</thead>
<tbody><tr id="row5513113910582"><td class="cellrowborder" valign="top" width="23.23%" headers="mcps1.2.4.1.1 "><p id="p12513203914586"><a name="p12513203914586"></a><a name="p12513203914586"></a>name</p>
</td>
<td class="cellrowborder" valign="top" width="22.220000000000002%" headers="mcps1.2.4.1.2 "><p id="p175142039145811"><a name="p175142039145811"></a><a name="p175142039145811"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="54.55%" headers="mcps1.2.4.1.3 "><p id="p1251414393582"><a name="p1251414393582"></a><a name="p1251414393582"></a>分区id</p>
</td>
</tr>
</tbody>
</table>

**表 10**  metrics说明

<a name="table15395838135813"></a>
<table><thead align="left"><tr id="row5514439105819"><th class="cellrowborder" valign="top" width="23.23%" id="mcps1.2.4.1.1"><p id="p1951473915588"><a name="p1951473915588"></a><a name="p1951473915588"></a>维度</p>
</th>
<th class="cellrowborder" valign="top" width="22.220000000000002%" id="mcps1.2.4.1.2"><p id="p1451419393581"><a name="p1451419393581"></a><a name="p1451419393581"></a>指标ID</p>
</th>
<th class="cellrowborder" valign="top" width="54.55%" id="mcps1.2.4.1.3"><p id="p451423955818"><a name="p451423955818"></a><a name="p451423955818"></a>说明</p>
</th>
</tr>
</thead>
<tbody><tr id="row19514163914588"><td class="cellrowborder" rowspan="3" valign="top" width="23.23%" headers="mcps1.2.4.1.1 "><p id="p1651419391587"><a name="p1651419391587"></a><a name="p1651419391587"></a>kafka_instance_id</p>
<p id="p85148398585"><a name="p85148398585"></a><a name="p85148398585"></a>（kafka实例维度）</p>
</td>
<td class="cellrowborder" valign="top" width="22.220000000000002%" headers="mcps1.2.4.1.2 "><p id="p19514193911584"><a name="p19514193911584"></a><a name="p19514193911584"></a>current_topics</p>
</td>
<td class="cellrowborder" valign="top" width="54.55%" headers="mcps1.2.4.1.3 "><p id="p185148398582"><a name="p185148398582"></a><a name="p185148398582"></a>topic个数</p>
</td>
</tr>
<tr id="row11514539185815"><td class="cellrowborder" valign="top" headers="mcps1.2.4.1.1 "><p id="p85146394586"><a name="p85146394586"></a><a name="p85146394586"></a>current_partitions</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.4.1.2 "><p id="p851433911585"><a name="p851433911585"></a><a name="p851433911585"></a>分区个数</p>
</td>
</tr>
<tr id="row9514173919584"><td class="cellrowborder" valign="top" headers="mcps1.2.4.1.1 "><p id="p14515163965816"><a name="p14515163965816"></a><a name="p14515163965816"></a>group_messages</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.4.1.2 "><p id="p12515183985819"><a name="p12515183985819"></a><a name="p12515183985819"></a>消费组堆积消息数</p>
</td>
</tr>
<tr id="row10515539195813"><td class="cellrowborder" rowspan="8" valign="top" width="23.23%" headers="mcps1.2.4.1.1 "><p id="p1751513392587"><a name="p1751513392587"></a><a name="p1751513392587"></a>kafka_broker（kafka节点维度）</p>
</td>
<td class="cellrowborder" valign="top" width="22.220000000000002%" headers="mcps1.2.4.1.2 "><p id="p1851543919584"><a name="p1851543919584"></a><a name="p1851543919584"></a>broker_data_size</p>
</td>
<td class="cellrowborder" valign="top" width="54.55%" headers="mcps1.2.4.1.3 "><p id="p55151639205820"><a name="p55151639205820"></a><a name="p55151639205820"></a>节点数据容量</p>
</td>
</tr>
<tr id="row251553917586"><td class="cellrowborder" valign="top" headers="mcps1.2.4.1.1 "><p id="p1051573914583"><a name="p1051573914583"></a><a name="p1051573914583"></a>broker_messages_in_rate</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.4.1.2 "><p id="p6515153913588"><a name="p6515153913588"></a><a name="p6515153913588"></a>消息生产速率，每秒生产的消息数量</p>
</td>
</tr>
<tr id="row1151543920588"><td class="cellrowborder" valign="top" headers="mcps1.2.4.1.1 "><p id="p151583965817"><a name="p151583965817"></a><a name="p151583965817"></a>broker_bytes_out_rate</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.4.1.2 "><p id="p185151239175818"><a name="p185151239175818"></a><a name="p185151239175818"></a>消费流量，每秒消费的字节数</p>
</td>
</tr>
<tr id="row2051513915816"><td class="cellrowborder" valign="top" headers="mcps1.2.4.1.1 "><p id="p851510393588"><a name="p851510393588"></a><a name="p851510393588"></a>broker_bytes_in_rate</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.4.1.2 "><p id="p16515339115812"><a name="p16515339115812"></a><a name="p16515339115812"></a>生产流量，每秒生产的字节数</p>
</td>
</tr>
<tr id="row1851583915584"><td class="cellrowborder" valign="top" headers="mcps1.2.4.1.1 "><p id="p95156396586"><a name="p95156396586"></a><a name="p95156396586"></a>broker_public_bytes_in_rate</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.4.1.2 "><p id="p165153398581"><a name="p165153398581"></a><a name="p165153398581"></a>公网入流量，每秒节点公网访问流入流量</p>
</td>
</tr>
<tr id="row5515113916585"><td class="cellrowborder" valign="top" headers="mcps1.2.4.1.1 "><p id="p5515939105817"><a name="p5515939105817"></a><a name="p5515939105817"></a>broker_public_bytes_out_rate</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.4.1.2 "><p id="p2515193913581"><a name="p2515193913581"></a><a name="p2515193913581"></a>公网出流量，每秒节点公网访问流出流量</p>
</td>
</tr>
<tr id="row851573965817"><td class="cellrowborder" valign="top" headers="mcps1.2.4.1.1 "><p id="p3515539125817"><a name="p3515539125817"></a><a name="p3515539125817"></a>broker_produce_mean</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.4.1.2 "><p id="p20515193917582"><a name="p20515193917582"></a><a name="p20515193917582"></a>消息生产平均处理时长，服务端处理消息生产请求平均时长</p>
</td>
</tr>
<tr id="row251573916584"><td class="cellrowborder" valign="top" headers="mcps1.2.4.1.1 "><p id="p1251593995820"><a name="p1251593995820"></a><a name="p1251593995820"></a>broker_fetch_mean</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.4.1.2 "><p id="p1251563912588"><a name="p1251563912588"></a><a name="p1251563912588"></a>消息消费平均处理时长，服务端处理消息消费请求平均时长</p>
</td>
</tr>
<tr id="row2526239165814"><td class="cellrowborder" rowspan="5" valign="top" width="23.23%" headers="mcps1.2.4.1.1 "><p id="p1152619393589"><a name="p1152619393589"></a><a name="p1152619393589"></a>kafka_topics（kafka topic维度）</p>
</td>
<td class="cellrowborder" valign="top" width="22.220000000000002%" headers="mcps1.2.4.1.2 "><p id="p165262393581"><a name="p165262393581"></a><a name="p165262393581"></a>topic_data_size</p>
</td>
<td class="cellrowborder" valign="top" width="54.55%" headers="mcps1.2.4.1.3 "><p id="p15526113920584"><a name="p15526113920584"></a><a name="p15526113920584"></a>队列数据容量，当前队列的数据容量</p>
</td>
</tr>
<tr id="row85267391586"><td class="cellrowborder" valign="top" headers="mcps1.2.4.1.1 "><p id="p15526163912584"><a name="p15526163912584"></a><a name="p15526163912584"></a>topic_messages_in_rate</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.4.1.2 "><p id="p145266393582"><a name="p145266393582"></a><a name="p145266393582"></a>消息生产速率，每秒钟生产的消息数量</p>
</td>
</tr>
<tr id="row115261839115812"><td class="cellrowborder" valign="top" headers="mcps1.2.4.1.1 "><p id="p1652614395582"><a name="p1652614395582"></a><a name="p1652614395582"></a>topic_bytes_out_rate</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.4.1.2 "><p id="p752614394581"><a name="p752614394581"></a><a name="p752614394581"></a>消费流量，每秒钟消费的字节数</p>
</td>
</tr>
<tr id="row0526163985816"><td class="cellrowborder" valign="top" headers="mcps1.2.4.1.1 "><p id="p25261939155814"><a name="p25261939155814"></a><a name="p25261939155814"></a>topic_bytes_in_rate</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.4.1.2 "><p id="p7526139205817"><a name="p7526139205817"></a><a name="p7526139205817"></a>生产流量，每秒钟生产的字节数</p>
</td>
</tr>
<tr id="row8526639155813"><td class="cellrowborder" valign="top" headers="mcps1.2.4.1.1 "><p id="p1352619397587"><a name="p1352619397587"></a><a name="p1352619397587"></a>topic_messages</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.4.1.2 "><p id="p1252643915813"><a name="p1252643915813"></a><a name="p1252643915813"></a>队列消息总数，当前队列的总消息数</p>
</td>
</tr>
<tr id="row11527339175817"><td class="cellrowborder" rowspan="4" valign="top" width="23.23%" headers="mcps1.2.4.1.1 "><p id="p65279398586"><a name="p65279398586"></a><a name="p65279398586"></a>kafka_partitions（kafka分区维度）</p>
</td>
<td class="cellrowborder" valign="top" width="22.220000000000002%" headers="mcps1.2.4.1.2 "><p id="p25271839195818"><a name="p25271839195818"></a><a name="p25271839195818"></a>produced_messages</p>
</td>
<td class="cellrowborder" valign="top" width="54.55%" headers="mcps1.2.4.1.3 "><p id="p14527113918582"><a name="p14527113918582"></a><a name="p14527113918582"></a>生产消息数，已经生产的消息数</p>
</td>
</tr>
<tr id="row25273391585"><td class="cellrowborder" valign="top" headers="mcps1.2.4.1.1 "><p id="p452719391585"><a name="p452719391585"></a><a name="p452719391585"></a>partition_messages</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.4.1.2 "><p id="p105273397583"><a name="p105273397583"></a><a name="p105273397583"></a>分区消息数，分区当前的消息数</p>
</td>
</tr>
<tr id="row1652733995812"><td class="cellrowborder" valign="top" headers="mcps1.2.4.1.1 "><p id="p1952713965817"><a name="p1952713965817"></a><a name="p1952713965817"></a>messages_consumed</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.4.1.2 "><p id="p15527123920587"><a name="p15527123920587"></a><a name="p15527123920587"></a>分区已消费消息数，当前消费组已经消费的消息个数</p>
</td>
</tr>
<tr id="row15527163965811"><td class="cellrowborder" valign="top" headers="mcps1.2.4.1.1 "><p id="p19527039165815"><a name="p19527039165815"></a><a name="p19527039165815"></a>messages_remained</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.4.1.2 "><p id="p252773915589"><a name="p252773915589"></a><a name="p252773915589"></a>分区剩余可消费数，消费组剩余可消费的消息个数</p>
</td>
</tr>
<tr id="row8527123925819"><td class="cellrowborder" rowspan="2" valign="top" width="23.23%" headers="mcps1.2.4.1.1 "><p id="p19527339175812"><a name="p19527339175812"></a><a name="p19527339175812"></a>kafka_groups_partitions（kafka消费组维度）</p>
</td>
<td class="cellrowborder" valign="top" width="22.220000000000002%" headers="mcps1.2.4.1.2 "><p id="p652793910585"><a name="p652793910585"></a><a name="p652793910585"></a>messages_consumed</p>
</td>
<td class="cellrowborder" valign="top" width="54.55%" headers="mcps1.2.4.1.3 "><p id="p1352763913586"><a name="p1352763913586"></a><a name="p1352763913586"></a>分区已消费消息数，当前消费组已经消费的消息个数</p>
</td>
</tr>
<tr id="row1952763975820"><td class="cellrowborder" valign="top" headers="mcps1.2.4.1.1 "><p id="p1552773915582"><a name="p1552773915582"></a><a name="p1552773915582"></a>messages_remained</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.4.1.2 "><p id="p952773915585"><a name="p952773915585"></a><a name="p952773915585"></a>分区剩余可消费消息数，当前消费组剩余可消费的消息个数</p>
</td>
</tr>
</tbody>
</table>

**响应示例**

```
{
	"dimensions": [{
		"name": "kafka_instance_id",
		"metrics": ["current_partitions",
		"current_topics",
		"group_messages"],
		"key_name": ["instance_ids"],
		"dim_router": ["kafka_instance_id"]
	},
	{
		"name": "kafka_broker",
		"metrics": ["broker_data_size",
		"broker_messages_in_rate",
		"broker_bytes_out_rate",
		"broker_bytes_in_rate",
		"broker_produce_mean",
		"broker_fetch_mean"],
		"key_name": ["nodes"],
		"dim_router": ["kafka_instance_id",
		"kafka_broker"]
	},
	{
		"name": "kafka_rest",
		"metrics": ["rest_produce_success",
		"rest_produce_failed",
		"rest_produce_latency",
		"rest_produce_msg_num",
		"rest_produce_flow",
		"rest_consume_success",
		"rest_consume_failed",
		"rest_consume_latency",
		"rest_consume_msg_num",
		"rest_consume_flow",
		"rest_commit_success",
		"rest_commit_failed",
		"rest_commit_latency",
		"rest_commit_msg_num",
		"rest_commit_flow"],
		"key_name": ["nodes"],
		"dim_router": ["kafka_instance_id",
		"kafka_rest"]
	},
	{
		"name": "kafka_topics",
		"metrics": ["topic_data_size",
		"topic_messages_in_rate",
		"topic_bytes_out_rate",
		"topic_bytes_in_rate",
		"topic_messages"],
		"key_name": ["queues"],
		"dim_router": ["kafka_instance_id",
		"kafka_topics"],
		"children": [{
			"name": "kafka_partitions",
			"metrics": ["produced_messages",
			"partition_messages"],
			"key_name": ["queues",
			"partitions"],
			"dim_router": ["kafka_instance_id",
			"kafka_topics",
			"kafka_partitions"]
		}]
	},
	{
		"name": "kafka_groups_partitions",
		"metrics": ["messages_consumed",
		"messages_remained"],
		"key_name": ["groups",
		"queues",
		"partitions"],
		"dim_router": ["kafka_instance_id",
		"kafka_groups",
		"kafka_groups_topics",
		"kafka_groups_partitions"]
	}],
	"instance_ids": [{
		"name": "68f3f6a0-3741-453b-bda9-a6ff6b5bb6f7"
	}],
	"nodes": [{
		"name": "broker-0"
	},
	{
		"name": "broker-1"
	},
	{
		"name": "broker-2"
	}],
	"queues": [{
		"name": "aaaa",
		"partitions": [{
			"name": "0"
		}]
	},
	{
		"name": "mytest",
		"partitions": [{
			"name": "0"
		},
		{
			"name": "1"
		},
		{
			"name": "2"
		}]
	},
	{
		"name": "topic-84234378",
		"partitions": [{
			"name": "0"
		},
		{
			"name": "1"
		},
		{
			"name": "2"
		}]
	}],
	"groups": [{
		"name": "test-consumer-group",
		"queues": [{
			"name": "mytest",
			"partitions": [{
				"name": "0"
			},
			{
				"name": "1"
			},
			{
				"name": "2"
			}]
		}]
	}]
}
```

## 状态码<a name="section10900163819586"></a>

查询成功的状态码如[表11](#table990323885818)所示，其他响应见[表1](状态码.md#zh-cn_topic_0128036883_table5210141351517)。

**表 11**  状态码

<a name="table990323885818"></a>
<table><thead align="left"><tr id="row1453112391588"><th class="cellrowborder" valign="top" width="15.15%" id="mcps1.2.3.1.1"><p id="p10531539175816"><a name="p10531539175816"></a><a name="p10531539175816"></a>状态码</p>
</th>
<th class="cellrowborder" valign="top" width="84.85000000000001%" id="mcps1.2.3.1.2"><p id="p185311639195814"><a name="p185311639195814"></a><a name="p185311639195814"></a>描述</p>
</th>
</tr>
</thead>
<tbody><tr id="row1531183916589"><td class="cellrowborder" valign="top" width="15.15%" headers="mcps1.2.3.1.1 "><p id="p1653113394584"><a name="p1653113394584"></a><a name="p1653113394584"></a>200</p>
</td>
<td class="cellrowborder" valign="top" width="84.85000000000001%" headers="mcps1.2.3.1.2 "><p id="p353193915587"><a name="p353193915587"></a><a name="p353193915587"></a>查询成功。</p>
</td>
</tr>
</tbody>
</table>

