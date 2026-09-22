# RTD CPU Support Page
This package includes the full available catalog of RTD CPU manuals, and supported 3rd party software.
The contents are broken up by processor series. 


## Intel x86 Products
RTD's single board computers are named after the former code names for the Intel processors, the Kaby Lake (KB), 
the Bay Trail (BT), and the Chief River (CR). The full list for each series will include the following sequences 
in the part name. A folder with the appropriate manual and 3rd party Windows software is provided in a separate 
folder.

The Intel Xeon and Core i3 (Kaby Lake) series includes:
- CMA34KBD2100
- CMA34KBQ2200
- CMA34KBQ3000
- CMX34KBD2100
- CMX34KBQ2200
- CMX34KBQ3000

The Intel Atom E3800 (Bay Trail) series includes:
- CME34BT
- CMX34BT
- CMA24BT
- CML24BT

The Core i7 (Chief River) series Includes: 
- CMA34CRD...4096/S60GX
- CMA34CRD...8192/S60GX

## Nvidia Jetson Series (CNV36)
The RTD NVIDIA Jetson carrier series provides RTD ruggedization and stackable architecture to several embedded NVIDIA modules.
The NVIDIA Jetson series is a popular 

Jetson AGX Orin
- CNV367JRAGX201HR 






## aDIO Connector (CN6)
Each of the RTD x86 CPUs have an aDIO connector on it for digital input and output usage. The driver for this is provided
on our GitHub page for both [Linux](https://github.com/RTD-Embedded/aDIO-Linux) and [Windows](https://github.com/RTD-Embedded/aDIO-Windows).
The driver software is provided under the GPL 2.0 License and the RTD EULA. The CNV36 Nvidia Series does not have an aDIO connector 
and instead uses GPIO using the standard linux [gpiod](https://libgpiod.readthedocs.io/en/master/) driver for digital input and 
output.
