# EnOceanWLanGateway
<table><tr>
<td>
<img src="layout.png"
     alt="Markdown Monster icon"
     style="float: left; margin-right: 10px; height: 200px;" />
</td><td>
<img src="front.png"
     alt="Markdown Monster icon"
     style="float: left; margin-right: 10px; height: 200px;" />
</td><td>
 <img src="back.png"
     alt="Markdown Monster icon"
     style="float: left; margin-right: 10px; height: 200px;" />
</td><td>
<img src="circuit.png"
     alt="Markdown Monster icon"
     style="float: left; margin-right: 10px; height: 200px;" />
</td>
</tr><tr>
<td>
<img src="EnoceanGateway_1.jpeg"
     alt="Markdown Monster icon"
     style="float: left; margin-right: 10px; height: 200px;" />
</td><td>
<img src="EnoceanGateway_2.jpeg"
     alt="Markdown Monster icon"
     style="float: left; margin-right: 10px; height: 200px;" />
</td><td>
 <img src="EnoceanGateway_3.jpeg"
     alt="Markdown Monster icon"
     style="float: left; margin-right: 10px; height: 200px;" />
</td><td>
</td>
</tr>
</table>

## Anleitung
* Jeelabs ESP-Link auf den ESP8266 flashen
* uC-Console -> Baudrate auf 57600 stellen
* Pin Assignment setzen
  * Reset: disabled
  * ISP/Flash: disabled
  * Conn. LED: disabled
  * Serial LED: disabled
  * UART Pins: swapped
  * RX pullup: ok
 
FHEM Definition:
<pre>defmod EnOceanGateway TCM ESP3 &#60;ipadresse&#62;:23</pre>
<br>
Den ESP8266 kann man auch direkt auf die Platine löten, dann wird alles insgesamt flacher
