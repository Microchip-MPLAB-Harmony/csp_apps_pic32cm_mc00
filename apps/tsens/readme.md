---
parent: Harmony 3 peripheral library application examples for PIC32CM MC00 family
title: TSENS Temperature Measurement 
has_children: false
has_toc: false
---

[![MCHP](https://www.microchip.com/ResourcePackages/Microchip/assets/dist/images/logo.png)](https://www.microchip.com)

# TSENS Temperature Measurement

This example application shows how to measure operating temperature of the device using the TSENS peripheral and displays the measured temprature on a serial terminal.

## Description

In this application, TC is used to genertae trigger for temperature sensor measurement. The converted value is displayed on the console. 

## Downloading and building the application

To clone or download this application from Github, go to the [main page of this repository](https://github.com/Microchip-MPLAB-Harmony/csp_apps_pic32cm_mc00) and then click **Clone** button to clone this repository or download as zip file.
This content can also be downloaded using content manager by following these [instructions](https://github.com/Microchip-MPLAB-Harmony/contentmanager/wiki).

Path of the application within the repository is **apps/adc/adc_sample/firmware** .

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

1. Open the Terminal application (Ex.:Tera term) on the computer
2. Connect to the EDBG Virtual COM port and configure the serial settings as follows:
    - Baud : 115200
    - Data : 8 Bits
    - Parity : None
    - Stop : 1 Bit
    - Flow Control : None
3. Build and Program the application using its IDE

4. Console displays the TSENS count and the Temperature in the console as shown below:

    ![output](images/output_tsens_temp.png)