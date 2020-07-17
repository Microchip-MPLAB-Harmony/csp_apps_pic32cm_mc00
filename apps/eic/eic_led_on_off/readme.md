[![MCHP](https://www.microchip.com/ResourcePackages/Microchip/assets/dist/images/logo.png)](https://www.microchip.com)

# EIC Interrupt

This example application demonstrates how to generate interrupt using the EIC on switch press and indicate it through an LED.

## Description

The application registers an event callback with EIC Peripheral library and toggles an LED for every switch press event.

## Downloading and building the application

To download or clone this application from Github, go to the [top level of the repository](https://github.com/Microchip-MPLAB-Harmony/csp_apps_pic32cm_mc00) and click

![clone](../../../docs/images/clone.png)

Path of the application within the repository is **apps/eic/eic_led_on_off/firmware** .

To build the application, refer to the following table and open the project using its IDE.

| Project Name      | Description                                    |
| ----------------- | ---------------------------------------------- |
| pic32cm_mc00_curiosity_pro.X | MPLABX project for [PIC32CM MC00 Curiosity Pro Evaluation Kit](https://www.microchip.com/developmenttools/ProductDetails/) |
|||

## Setting up the hardware

The following table shows the target hardware for the application projects.

| Project Name| Board|
|:---------|:---------:|
| pic32cm_mc00_curiosity_pro.X | [PIC32CM MC00 Curiosity Pro Evaluation Kit](https://www.microchip.com/developmenttools/ProductDetails/)
|||

### Setting up [PIC32CM MC00 Curiosity Pro Evaluation Kit](https://www.microchip.com/developmenttools/ProductDetails/)

- Connect the Debug USB port on the board to the computer using a micro USB cable

## Running the Application

1. Build and Program the application using its IDE
2. LED toggles on every switch release

Following table provides the LED name:

| Board      | Switch Name | LED Name |
| ---------- | ---------| ------------|
| [PIC32CM MC00 Curiosity Pro Evaluation Kit](https://www.microchip.com/developmenttools/ProductDetails/) | SW0 | LED0 |
||||
