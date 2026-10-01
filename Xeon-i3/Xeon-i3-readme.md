# Intel Xeon and Core i3 (Kaby Lake)


The [Intel Xeon and Core i3 processor SoMs](https://www.rtd.com/PC104/CM/processor_kb.htm) (Kaby Lakes) support both Windows 10/11 and Linux. Linux has all of the 
required Intel drivers pre-installed as part of the most recent kernel versions for operation. Older versions 
of Linux might require updates to the kernel or to newer versions in order to have the required driver software. 
The only additional software required for full operation in Linux is the aDIO driver made by RTD.

For Windows there are various software packages that are recomended for proper operation that are provided by 
Intel. These packages can be installed through the below methods. 


## The Intel Management Engine (ME) for Windows 10/11
The Kaby Lake Series requires the usage of the Intel management engine driver set for Windows 10/11. The latest version
of the Intel Mangement Engine can be found [here](https://www.intel.com/content/www/us/en/download/682431/intel-management-engine-drivers-for-windows-10-and-windows-11.html). This checks that the firmware of the Intel
management engine is up to date.


## Intel Processor Graphics Drivers for Windows 10/11
The integrated graphics in the Kaby Lake processor has it's own driver provided by intel. The latest version of that
driver can be found [here](https://www.intel.com/content/www/us/en/download/776137/intel-7th-10th-gen-processor-graphics-windows.html). 
It can also be installed via the Windows Update process.

## Intel Chipset Drivers

The chipset drivers include support for peripheral devices. This will enable user features for the memory controller and other devices. 
[Latest Version found here](https://www.intel.com/content/www/us/en/download/776553/intel-server-chipset-driver-for-windows-for-intel-server-boards-and-systems-based-on-intel-741-chipset.html).

## aDIO Connector (CN6) Linux and Windows 10/11
Each of the RTD x86 CPUs have an aDIO connector on it for digital input and output usage. The driver for this is provided
on our GitHub page for both [Linux](https://github.com/RTD-Embedded/aDIO-Linux) and [Windows](https://github.com/RTD-Embedded/aDIO-Windows).
The driver software is provided under the GPL 2.0 License and the RTD EULA.
