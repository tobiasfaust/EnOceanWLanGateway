# EnOceanWLanGateway

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
<pre>defmod EnOceanGateway TCM ESP3 <ipadresse>:23</ipadresse>pre>
