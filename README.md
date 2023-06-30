# Qeteshs AC-Controller

[![CI](https://github.com/Qeteshpony/AC-Controller/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/Qeteshpony/AC-Controller/actions/workflows/ci.yml)

Simple controller for IoT devices with ESP-Home and Home Assistant in mind. This project was mainly started to get better control for our AC system but I guess it can be adapted for about anything. 

The system is based on an ESP32 module, a small LCD and two rotary encoders with optional support for charging and using a LiPo battery. 

The hardware was designed for production by JLCPCB and as many parts as possible were selected from their basic parts library to keep costs low. 

The PCB has two positions for a USB-C port, both are wired in parallel so only one should be soldered in - which one depends on the usecase. 