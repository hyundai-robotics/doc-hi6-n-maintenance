# 4.3.2.4. 设定设备

![](../../../_assets/그림_4.31_BD632(Safety_IO_Board)의_설정장치_설명.png)

Figure 4.11 BD632（安全IO板）的设定设备说明

{% hint style="warning" %}
当安全相关输入连接并激活时，您必须通过参考“1.11 操作机器人时的安全措施”来检查功能是否正常运行。
{% endhint %}

表4-9 BD632（安全IO模块）SW1、SW2、SW3、SW4和SW7设定设备的说明

<table>
<thead>
  <tr>
    <th colspan="2">开关</th>
    <th rowspan="2">SW1</th>
    <th rowspan="2">SW2</th>
    <th rowspan="2">SW3</th>
    <th rowspan="2">SW4</th>
    <th rowspan="2">SW7</th>
  </tr>
  <tr>
    <th colspan="2">编号</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td colspan="2">用途</td>
    <td>设定是否安装操作面板（OP）（链1）</td>
    <td>设定是否安装操作面板（OP）（链2）</td>
    <td>设定是否安装OVT6、LS、OVT7（附加轴）和OVT8（扩展轴）（链1）</td>
    <td>设定是否安装OVT6、LS、OVT7（附加轴）和OVT8（扩展轴）（链2）</td>
    <td>设定是否安装PLC ES、SG（链1，链2）
</td>
  </tr>
  <tr>
    <td rowspan="2">设定内容</td>
    <td>关闭</td>
    <td>不安装</td>
    <td>不安装</td>
    <td>1：安装OVT6</br>2：安装LS<br>3：安装OVT7</br>4：安装OVT8
</td>
    <td>1：安装OVT6</br>2：安装LS</br>3：安装OVT7</br>4：安装OVT8</br>
</td>
    <td>1：安装ES（链1）</br>2：安装SG（链1）</br>3：安装ES（链2）</br>4：安装SG（链2）</br>
</td>
  </tr>
  <tr>
    <td>打开</td>
    <td>安装</td>
    <td>安装</td>
    <td>1：不安装OVT6</br>2：不安装LS</br>3：不安装OVT7</br>4：不安装OVT8</br>
</td>
    <td>1：不安装OVT6</br>2：不安装LS</br>3：不安装OVT7</br>4：不安装OVT8</br>
</td>
    <td>1：不安装ES（链1）</br>2：不安装SG（链1）</br>3：不安装ES（链2）</br>4：不安装SG（链2）</br>
</td>
  </tr>
  <tr>
    <td colspan="2">出厂时的设定</td>
    <td>不安装（关闭）</td>
    <td>不安装（关闭）</td>
    <td>1：关闭</br>2：关闭</br>3：开启（连接附加轴OVT时关闭）</br>4：开启（连接扩展轴OVT时关闭）</br>
</td>
    <td>1：关闭</br>2：关闭</br>3：开启（连接附加轴OVT时关闭）</br>4：开启（连接扩展轴OVT时关闭）</br>
</td>
    <td>1：不安装ES（链1）</br>2：不安装SG（链1）</br>3：不安装ES（链2）</br>4：不安装SG（链2）</br>
</td>
  </tr>
</tbody>
</table>