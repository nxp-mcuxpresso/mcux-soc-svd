# MCUXpresso SDK : mcux-soc-svd

## Overview
This repository is for System View Description(SVD) file delivery of MCUXpresso SDK. The SVD file provides detailed information about peripherals, registers, fields, and bit values as well as named interrupts. When using debugger with specified SVD file for the connected device , software developer is able to easily check the peripheral registers, without the need to reference device documentation. For more of the SVD file description and benefits, please check the [System View Description](https://arm-software.github.io/CMSIS_5/SVD/html/index.html).

The suggested user scenarios for the repository are:

* **Download specific SVD file for a device to use with toolchains.** For example, download MIMXRT1052.xml file and use it for debugging evkbimxrt1050 board ARMGCC project with Ozone or vscode Cortex-Debug extension.
* **Use the repository together with MCUXpresso SDK overall delivery on GitHub.** The MCUXpresso SDK overall delivery references the repository as a west project to make the MCUXpresso IDE able to use the SVD files for debugging. This repository is part of the MCUXpresso SDK overall delivery which is composed of several sub-repositories/projects. Navigate to the top/parent repository [mcuxsdk-manifests](https://github.com/nxp-mcuxpresso/mcuxsdk-manifests) for the complete delivery of MCUXpresso SDK.

## Documentation
Overall details can be reviewed here: [MCUXpresso SDK Online Documentation](https://mcuxpresso.nxp.com/mcuxsdk/latest/html/introduction/README.html)  

## Setup
Instructions on how to install the MCUXpresso SDK provided from GitHub via west manifest [Getting Started with SDK - Detailed Installation Instructions](https://mcuxpresso.nxp.com/mcuxsdk/latest/html/gsd/installation.html#installation)

## Contribution
Contributions are not currently accepted. Guidelines to contribute will be posted in the future.
