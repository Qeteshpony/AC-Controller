# Qeteshs AC-Controller

[![CI](https://github.com/Qeteshpony/AC-Controller/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/Qeteshpony/AC-Controller/actions/workflows/ci.yml)

![3D Render](https://qeteshpony.github.io/AC-Controller/3D/AC-Controller-3D_top.png)

[Hardware Documentation](https://qeteshpony.github.io/AC-Controller)

Simple controller for IoT devices with ESP-Home and Home Assistant in mind. This project was mainly started to get better control for our AC system but I guess it can be adapted for about anything. 

The system is based on an ESP32 module, a small LCD and two rotary encoders with optional support for charging and using a LiPo battery. 

The hardware was designed for production by JLCPCB and as many parts as possible were selected from their basic parts library to keep costs low. 

The PCB has two positions for a USB-C port, both are wired in parallel so only one should be soldered in - which one depends on the usecase. 

The display I use is the `DEM 16226 SYH-LY` which is smaller than most 16x2 character displays and available from several retailers. The board most likely needs major changes to be used with another display since the connector is in a different position to most.

I also got shorter 2.54mm pins that only raise the display by about 8mm from the main board so everything is more compact.

The battery used is a 2500 mAH LiPo cell calles `LP-785060` with built in protection circuit and about the same measurements as the board so it fits neatly underneath it. 