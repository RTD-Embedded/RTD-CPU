# NVIDIA Jetson AGX Orin
The NVIDIA Jetson AGX Orin only supports Linux, and a limited number of distributions. The NVIDIA build tool for making an image has
been adopted by RTD to work with the CNV36JRAGX201HR boards. This includes additional hardware breakouts required to use the PCIe-104
form factor. RTD provides software that is required to build the Linux image that includes these changes in a GitHub repository [here](https://github.com/RTD-Embedded/CNV36JRAGX). Carefully follow the instructions using a native Ubuntu 22.04 LTS host computer. To
cross-compile the Linux image.

When purchased from RTD, the CNV36JRAGX will have the latest version of the NVIDIA Linux image on it and include some basic utilities.
Additional software for using the Jetson AGX are provided by NVIDIA [here](https://developer.nvidia.com/embedded/jetson-linux-r363).
