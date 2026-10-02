# Intel Core i7 (Chief River)
The Intel Core i7 processor SoMs (Chief River) support both Windows 10 and Linux. Linux has all of the 
required Intel drivers pre-installed as part of the most recent kernel versions for operation. Older versions 
of Linux might require updates to the kernel or to newer versions in order to have the required driver software. 
The only additional software required for full operation in Linux is the aDIO driver made by RTD.

For Windows there are various software packages that are recomended for proper operation that are provided by 
Intel. These packages can be installed through the below methods. 

## Chipset
RTD redistributes the Intel Chipset as a intel_chipset_windows_v10.0.13.zip. Simply extract the folder and 
follow the instructions to have the chipset installed.

## aDIO Connector (CN6) Linux and Windows 10
Each of the RTD x86 CPUs have an aDIO connector on it for digital input and output usage. The driver for this is provided
on our GitHub page for both [Linux](https://github.com/RTD-Embedded/aDIO-Linux) and [Windows](https://github.com/RTD-Embedded/aDIO-Windows).
The driver software is provided under the GPL 2.0 License and the RTD EULA.
