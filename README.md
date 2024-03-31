# pad16_panda

<img src="/images/pcb_front.png" height="400">　<img src="/images/pcb_back.png" height="400">
<br><br><br>


## 説明

pad16_panda は MCP23017 を使用した16キーのマクロパッドです。<br>
A0～A7、B0～B7の全ピンがダイレクト接続となっていてダイオードレスです。<br>
I2C接続にてAZ-COREやえむごっちと接続して使用して下さい。<br>
<br><br>

## IOエキスパンダのアドレス設定

<img src="/images/jumper_setting.png">

## TRRSジャック

<table>
  <tr>
    <td>1</td>
    <td>T</td>
    <td>SCL</td>
    <td rowspan="4"><img src="/images/pj320a.png" width="400"></td>
  </tr>
  <tr>
    <td>2</td>
    <td>R</td>
    <td>SDA</td>
  </tr>
  <tr>
    <td>3</td>
    <td>R</td>
    <td>VCC</td>
  </tr>
  <tr>
    <td>4</td>
    <td>S</td>
    <td>GND</td>
  </tr>
</table>
<br><br>



