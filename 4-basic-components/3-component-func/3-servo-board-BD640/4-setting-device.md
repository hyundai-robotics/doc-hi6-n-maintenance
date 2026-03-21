# 4.3.3.4. 设置设备

{% hint style="info" %}
DIP开关在出厂时设置为OFF模式，用户不应随意更改该设置。
{% endhint %}


表4-12 设置伺服板 (BD640) 的DIP开关 (DS1) 方法

<table>
<thead>
  <tr>
    <th>开关编号</th>
    <th>1</th>
    <th>2</th>
    <th>模式</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>出厂时的设置</td>
    <td>OFF</td>
    <td>OFF</td>
    <td>获取模式</td>
  </tr>
  <tr>
    <td>测试时</td>
    <td>ON</td>
    <td>OFF</td>
    <td>等待模式</td>
  </tr>
  <tr>
    <td>开关外观</td>
    <td colspan="3"></td>
  </tr>
</tbody>
</table>

![](../../../_assets/표4-11_스위치외형.png)</br></br>

{% hint style="info" %}
用户无法随意更改以下项目，需仅在通过FPGA JTAG重新编程时参考。
{% endhint %}


表4-13 伺服板 (BD640) 的跳线 (JP1) 描述

<table>
<thead>
  <tr>
    <th colspan="2" rowspan="2">名称<br>设置内容</th>
    <th colspan="4">JP1</th>
  </tr>
  <tr>
    <th>1</th>
    <th>2</th>
    <th>3</th>
    <th></th>
  </tr>
</thead>
<tbody>
  <tr>
    <td rowspan="2">跳线的设置</td>
    <td>QSPI (闪存) 启动模式</td>
    <td>⊙</td>
    <td>⊙</td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>JTAG编程模式</td>
    <td></td>
    <td>⊙</td>
    <td>⊙</td>
    <td></td>
  </tr>
  <tr>
    <td>出厂时的设置</td>
    <td colspan="5">1, 2 : 短接 / 3 : 开路</td>
  </tr>
</tbody>
</table>