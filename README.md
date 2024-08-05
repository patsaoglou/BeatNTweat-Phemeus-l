# Overview
This is an Audio preamplifier featuring a NE5532 voltage stage, Class A output stage and features like Input/Output selection, headphones output and soft start.

Haven't completed the in-depth Readme going through the design...
![bnt-phemious-l](https://github.com/user-attachments/assets/6542af92-68f6-4ec9-97df-573058a1f1ae)


# Firmware Implementatin
In the firmware directory(main.c) you can find the full cubeIDE project where I implement all the microcontroller functionality like softstart delay, the input/output switching and the user's last configuration save/loadup at startup from the MCU flash.

![MCU Pinout](https://github.com/user-attachments/assets/1145fb85-1673-45a7-9e71-a2233c1f748c)
