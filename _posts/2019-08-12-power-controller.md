---
layout: post
title: "Power Controller"
description: "Power ORing and Battery Charging controller"
date: 2019-08-12
tags: Power HV Controller Charger
comments: false
photo_layout: "layout_3_pic_1"
photo1: "assets/power-controller/controller-assembly_small.jpg"
photo2: "assets/power-controller/controller-unassembled_small.jpg"
photo3: "assets/power-controller/controller-LCD_small.jpg"
---

This board is a general purpose power controller. It fulfills several functions:
- Inrush Current Limiting
- Power Switch Sontrol
- Power ORing
- Battery Charging
- Shunt Regulation
- DC-DC Conversion
- Configuration Interface
- USB Logging
- Current and Voltage sensing

It is intended to handle a 48V supply, but can charge the batteries at a lower voltage using its zero-dropout regulator. The battery charging regulator is current limited to protect the batteries.

Voltage from back-EMF without regulation:
<img src="https://nick-paiva.github.io/assets/power-controller/wo-chopper.PNG">

Voltage with the shunt regulator engaged:
<img src="https://nick-paiva.github.io/assets/power-controller/chopper.PNG">

Test setup:
<img src="https://nick-paiva.github.io/assets/power-controller/test-setup.jpg">

Gallery:
<img src="https://nick-paiva.github.io/assets/power-controller/controller-assembly.jpg">
<img src="https://nick-paiva.github.io/assets/power-controller/controller-unassembled.jpg">
<img src="https://nick-paiva.github.io/assets/power-controller/controller-LCD.jpg">
