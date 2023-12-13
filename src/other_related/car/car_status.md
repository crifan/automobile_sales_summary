# 车辆状态

从无到有的，车辆的状态，按照流程的先后，分别是：

* **总部库存**
  * **生产中**：接到了（可能是直接来自经销商下面上报到实际客户购买的， 也可能是车厂自己计划生产的）订单
  * **已下线**：从产线生产组装完毕，下了生产线了，进入车厂自己的（总部）库存
* **经销商库存**：在 车厂 批售 给了 经销商 后
  * **在途中**：通过大卡车等从车厂运输到经销商4S店
  * **已到店**：已经到了4S店，进入经销商店库存系统

从左到右就是：

<table>
  <tr>
    <td colspan="2" align="center" style="background-color:#2674BA; color:white; font-weight:700;">总部库存</td>
    <td colspan="2" align="center" style="background-color:#2674BA; color:white; font-weight:700;">经销商库存</td>
  </tr>
  <tr>
    <td>（在产线上）生产中</td>
    <td>已下线（到总部的库存中）</td>
    <td>（用大卡车从总部）在途中（运往经销商4S店）</td>
    <td>已到店（进去4S店的库存）</td>
  </tr>
</table>