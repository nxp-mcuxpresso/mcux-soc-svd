# mcux-soc-svd

This repository is for System View Description(SVD) file delivery of MCUXpresso SDK. The SVD file provides detailed information about peripherals, registers, fields, and bit values as well as named interrupts. When using debugger with specified SVD file for the connected device , software developer is able to easily check the peripheral registers, without the need to reference device documentation. For more of the SVD file description and benefits, please check the [System View Description](https://arm-software.github.io/CMSIS_5/SVD/html/index.html).

The suggested user scenarios for the repository are:

* **Download specific SVD file for a device to use with toolchains.** For example, download MIMXRT1052.xml file and use it for debugging evkbimxrt1050 board ARMGCC project with Ozone or vscode Cortex-Debug extension.
* **Use the repository together with MCUXpresso SDK overall delivery on GitHub.** The MCUXpresso SDK overall delivery references the repository as a west project to make the MCUXpresso IDE able to use the SVD files for debugging. To achieve the MCUXpresso SDK delivery which contains shared drivers/components, device support, board support, rtos and middleware support, you may go to the [main repository](https://github.com/NXPmicro/mcux-sdk/).

## License
This project is under BSD-3-Clause license, license copy please check [COPYING_BSD-3](COPYING-BSD-3).
