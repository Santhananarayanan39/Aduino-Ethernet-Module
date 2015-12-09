Web Remote control of LED

This program webRemote_led_ctrl.ino illustates to control a LED from internet. The Led is connected to the Arduino board with pin 9 and the board is connected with ethernet module ENC28J60 which is connected to internet through th physical connection between router and it. We are using two libraries here in program to get connection to internet are ETHER_28J60.h and etherShield.h

For brief domanstration see this link (http://www.trollmaker.com/article11/arduino-1-0-with-enc28j60-ethernet-shield-v1-1) and this Youtube video (https://www.youtube.com/watch?v=vKE8SHywZmo&feature=youtu.be)

Pin connections description for Arduino and Ethernet module

Arduino Ethernet module 10 CS 11 SI 12 SO 13 SCK 3.3v 3.3v Gnd Gnd