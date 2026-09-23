# RTD CPU Support Page
This package includes the full available catalog of RTD CPU manuals, and supported 3rd party software.
The contents are broken up by processor series. In general, all manuals include information about all
versions of the products including variations for our [IDAN and HiDAN](https://www.rtd.com/systems/default.htm)
enclosures. The full list for each series will include the following sequences in the part name, in 
addition to other numbers and letters. 

If your RTD processor is not found here, such as our legacy devices. More information can 
be found on our [website](https://www.rtd.com/PC104/PC104_cpuModule.htm#gsc.tab=0), or by contacting RTD.

## Intel x86 Products
RTD's single board computers are named after the former code names for the Intel processors, the Kaby Lake (KB), 
the Bay Trail (BT), and the Chief River (CR). A folder with the appropriate manual and 3rd party Windows software 
is provided in a separate folder. 

The [Intel Xeon and Core i3](Xeon-i3/Xeon-i3-readme.md) (Kaby Lake) series includes:
- CMA34KBD2100
- CMA34KBQ2200
- CMA34KBQ3000
- CMX34KBD2100
- CMX34KBQ2200
- CMX34KBQ3000


The [Intel Atom E3800](Atom-3800/Atom-3800-readme.md) (Bay Trail) series includes:
- CME34BT
- CMX34BT
- CMA24BT
- CML24BT

The [Core i7](Core-i7/Core-i7-3800-readme.md) (Chief River) series Includes: 
- CMA34CRD...4096/S60GX
- CMA34CRD...8192/S60GX


## Nvidia Jetson Series (CNV36)
The RTD NVIDIA Jetson carrier series provides RTD ruggedization and stackable architecture to NVIDIA's popular Jetson line. 


[Jetson AGX Orin Carrier](Jetson-AGX-Orin/AGX-Orin-readme.md)
- CNV36JRAGX201HR 

[Jetson Orin NX & Orin Nano Carrier](Jetson-Orin-NX-Nano/Orin-NX-Nano-readme.md)
- CNV36JRN201HR

[Jetson Xavier NX Carrier](Jetson-Xavier-NX/Xavier-NX-readme.md)
- CNV36JXNX68201HR


## aDIO Connector (CN6)
Each of the RTD x86 CPUs have an aDIO connector on it for digital input and output usage. The driver for this is provided
on our GitHub page for both [Linux](https://github.com/RTD-Embedded/aDIO-Linux) and [Windows](https://github.com/RTD-Embedded/aDIO-Windows).
The driver software is provided under the GPL 2.0 License and the RTD EULA. The CNV36 Nvidia Series does not have an aDIO connector 
and instead uses GPIO using the standard linux [gpiod](https://libgpiod.readthedocs.io/en/master/) driver for digital input and 
output on CN6.


## Recommended Accessories

For all of the above CPUs, when purchased without our IDAN or HIDAN enclosures, it is recommended to purchase a [XK-CM107](https://www.rtd.com/Cables/XK-CM107.htm) 
cable kit. This kit provide power and reset buttons, a CMOS battery, and two USB 2.0 Type A connections. Without a battery, some
settings and the real-time clock are lost when power is disconnected completely.


## Getting Technical Support

If you require additional support with these products from RTD Embedded Technologies, contact us using the information below:

RTD Embedded Technologies, Inc.\
103 Innovation Boulevard\
State College, PA 16803 USA


Telephone: (814) 234-8087\
Fax: (814) 234-5218\
Sales Information and Quotes: sales@rtd.com\
Technical Assistance: techsupport@rtd.com\
Website: [https://www.rtd.com](https://www.rtd.com)
