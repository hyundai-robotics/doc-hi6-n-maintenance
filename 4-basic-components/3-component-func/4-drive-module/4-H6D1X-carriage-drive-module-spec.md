# 4.3.4.4. H6D1X (驱动模块; 可选)

驱动模块执行功率放大功能，允许电流根据伺服板的电流命令流向电机的各相。小车驱动模块可以驱动一个电流为100A或以下的电机，配置如下。

![](../../../_assets/그림_4.43_H6D1X용BD658_부품_배치도.png)

图4.24 H6D1X用BD658的部件布置图</br></br>

表4-35 H6D1X的配置

<table>
<thead>
  <tr>
    <th colspan="2">组件</th>
    <th>功能</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td rowspan="3">BD658</br>(IPM板)
</td>
    <td>逻辑部分</td>
    <td>将从驱动模块接收到的6个轴的PWM信号转换为IPM的上下侧驱动信号，并处理错误</td>
  </tr>
  <tr>
    <td>门电源模块</td>
    <td>生成IPM门电源</td>
  </tr>
  <tr>
    <td>电流检测部分</td>
    <td>检测流过电机的电流</td>
  </tr>
  <tr>
    <td rowspan="2">其他部件</td>
    <td>散热器</td>
    <td>将IPM产生的热量释放到外部</td>
  </tr>
  <tr>
    <td>IPM</td>
    <td>转换驱动三相电机的功率</td>
  </tr>
</tbody>
</table>

表4-36 H6D1X连接器的描述

<table>
<thead>
  <tr>
    <th>名称</th>
    <th>使用</th>
    <th>外部设备的连接</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>CNPWM</td>
    <td>PWM信号和错误信号</td>
    <td>驱动模块的CNPWM7或CNPWM8（BD652或BD654）用于6个轴</td>
  </tr>
  <tr>
    <td>CNM</td>
    <td>电机驱动输出</td>
    <td>AMC1或AMC2</td>
  </tr>
  <tr>
    <td>CNFG</td>
    <td>电机的框架接地</td>
    <td>AMC1或AMC2</td>
  </tr>
  <tr>
    <td>CNPN</td>
    <td>驱动直流电源输入</td>
    <td>驱动模块的CNPN7或CNPN8（BD651或BD653）用于6个轴</td>
  </tr>
</tbody>
</table>