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

# target
希望有一天有人能把它用到Arduino 雕刻机上。
另外PC端用到了一个USR-VCOM的国产软件，可以识别局域网中的TCP串口模拟端口。
值得注意的是，这套代码不仅是为了Arduino Nano而设计的，几乎所有的Arduino都能使用它来实现无线烧录代码，和无线串口传输。
所有的串口通讯都可以被这个ESP8266无线化。

I hope someone can use it on Arduino GRBL machine one day.
In addition, the PC uses a software named USR-VCOM, which can identify the TCP serial port in LAN.
It is worth noting that this set of code is not only designed for Arduino nano, almost all Arduino can use it to realize wireless burning code and wireless serial transmission.
All serial communication can be wireless by this esp8266 software.
