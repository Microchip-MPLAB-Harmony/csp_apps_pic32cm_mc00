[![MCHP](https://www.microchip.com/ResourcePackages/Microchip/assets/dist/images/logo.png)](https://www.microchip.com)

# DIVAS accelerate computations

This example application demonstrates how to use the DIVAS accelerator to compute square room, and perform a division and modulus operation.

## Description

The Divide and Square Root Accelerator (DIVAS) is a programmable 32-bit signed or unsigned hardware divider and a 32-bit unsigned square root hardware engine. The DIVAS takes dividend and divisor values and returns the quotient and remainder when it is used as divider. The DIVAS takes unsigned input value and returns its square root and remainder when it is used as square root function.

## Downloading and building the application

To download or clone this application from Github, go to the [top level of the repository](https://github.com/Microchip-MPLAB-Harmony/csp_apps_pic32cm_mc00) and click

![clone](../../../docs/images/clone.png)

Path of the application within the repository is **apps/divas/divas_accelerate_computations/firmware** .

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

1. Open the Terminal application (Ex.:Tera term) on the computer
2. Connect to the EDBG Virtual COM port and configure the serial settings as follows:
    - Baud : 115200
    - Data : 8 Bits
    - Parity : None
    - Stop : 1 Bit
    - Flow Control : None
3. Build and Program the application using its IDE
4. Observe output message in console as follows:

    ![output](images/output_divas_acceralate_computations.png)