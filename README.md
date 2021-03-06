# WiFi-Grbl
将ESP8266作为串行端口处理器并与Gcode处理器Arduino nano 结合
combine ESP8266 as serial to port processer with Arduino as Grbl Gcode processer
# PCB TODO
以前，我一直以为A4988可以提供5V电压，是我错了。
母板有缺少一个5V稳压模块，所以焊接以后又在板子反面补上了一个小稳压模块。
其实是直接一个AMS1117加10uF电容就可以解决的事情，下次又时间再补上去。

I always thought that A4988 could provide 5V voltage, but I was wrong.

The motherboard lacks a 5V voltage regulator module, so a small voltage regulator module should be added on the reverse side of the board.

In fact, it's something that can be solved by directly adding 10uF capacitor and AMS1117-5.0.
