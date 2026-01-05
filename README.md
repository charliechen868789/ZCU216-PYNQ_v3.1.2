# ZCU216-PYNQ

Board repo for ZCU216 RFSOC. Contains

* ZCU216 board folder with updated device tree. 
* tics folder with files that program the LMK/LMX PLLs for the ZCU216 RFDCs. 

The user has to also download the prebuilt rootfs file `jammy.aarch64.3.1.0.tar` as well as the ZCU216 Petalinux 2024.1 BSP from the Xilinx website. 

How to make image. 

Method #1: Run the `build_ZCU216.sh` script after changing the path names for the BSP and rootfs files as indicated within the script. This method automatically places the correct tics files into the correct folder as indicated above. It should take about 4 hours to build the board.
•	PYNQ version is v3.1.2
•	Vivado/Vitis/Petalinux 2024.1
•	Host Env is Ubuntu 22.04
•	Python 3.10 


