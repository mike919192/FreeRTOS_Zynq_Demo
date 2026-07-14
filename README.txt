
The demo is tested using Xilinx Vitis 2026.1

The zynq port submodule is expected at rtos_test/src/external/freertos_ports

From the project directory, run:

C:\AMDDesignTools\2026.1\Vitis\bin\vitis.bat -s rtos_test_vitis_build.py

Adjust for operating system or install directory

After that open the IDE and set the workspace to this folder

A bif file is provided for boot image generation, but because it uses absolute paths it will need to be edited

If running the build script a second time, the directory must be git cleaned to remove all generated files.  Close the IDE and run "git clean -ffdx"
