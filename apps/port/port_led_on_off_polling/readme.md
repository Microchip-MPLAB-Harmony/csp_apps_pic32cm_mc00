---
parent: Harmony 3 peripheral library application examples for PIC32CM MC00 family
title: PORT polling 
has_children: false
has_toc: false
---

[![MCHP](https://www.microchip.com/ResourcePackages/Microchip/assets/dist/images/logo.png)](https://www.microchip.com)

# PORT polling

This example application demonstrate how to poll the switch input, and indicate the switch status using the LED.

## Description

This application uses the PORT Peripheral library to read the GPIO pin connected to the switch, and drives the GPIO pin connected to the LED to indicate the switch status. LED is turned ON when the switch is pressed and turned OFF when the switch is released.

## Downloading and building the application

To clone or download this application from Github, go to the [main page of this repository](https://github.com/Microchip-MPLAB-Harmony/csp_apps_pic32cm_mc00) and then click **Clone** button to clone this repository or download as zip file.
This content can also be downloaded using content manager by following these [instructions](https://github.com/Microchip-MPLAB-Harmony/contentmanager/wiki).

Path of the application within the repository is **apps/port/port_led_on_off_polling/firmware** .

To build the application, refer to the following table and open the project using its IDE.

| Project Name      | Description                                    |
| ----------------- | ---------------------------------------------- |
| pic32cm_mc00_curiosity_pro.X | MPLABX project for [PIC32CM MC00 Curiosity Pro Evaluation Kit](https://www.microchip.com/Developmenttools/ProductDetails/EV15N46A) |
|||

## Setting up the hardware

The following table shows the target hardware for the application projects.

| Project Name| Board|
|:---------|:---------:|
| pic32cm_mc00_curiosity_pro.X | [PIC32CM MC00 Curiosity Pro Evaluation Kit](https://www.microchip.com/Developmenttools/ProductDetails/EV15N46A)
|||

### Setting up [PIC32CM MC00 Curiosity Pro Evaluation Kit](https://www.microchip.com/Developmenttools/ProductDetails/EV15N46A)

- Connect the Debug USB port on the board to the computer using a micro USB cable

## Running the Application

1. Build and Program the application using its IDE
2. LED is turned on when the switch is pressed and turned off when the switch is released.

Refer the table below for details of switch and LED

| Board      | Switch Name | LED Name |
| ---------- | ---------| ------------|
| [PIC32CM MC00 Curiosity Pro Evaluation Kit](https://www.microchip.com/Developmenttools/ProductDetails/EV15N46A) | SW0 | LED0 |
||||
