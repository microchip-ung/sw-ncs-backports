README for PCI1xxxx Linux Ethernet Backport Driver
Copyright (C) 2022 - 23 Microchip Technology Inc.

This ReadMe.txt is for PCI1xxxx LAN743x Ethernet Driver Backport info.
Component Name : lan743x

Version Number : v1

Patch File     : 1.v5.4.249_LAN743x.patch
		 2.v5.4.249_LAN743x_SGMII.patch

Copyright      : Microchip Technology Inc.

Ubuntu Version : 20.04

Installation Procedure: Please check below

Kernel Version tested  : v5.4.249

Git Path: git://git.kernel.org/pub/scm/linux/kernel/git/stable/linux-stable.git 

Installation Procedure : 
1. Clone the v5.4.249 Linux Kernel Source
2. Apply the  v5.4.249_LAN743x.patch file on top of the v5.4.249 source
3. Apply the v5.4.249_LAN743x_SGMII patch and then apply the ETHTOOL_UPDATES_PATCH.
4. If you plan to test using the GPY211 PHY, apply the GPY_PHY patch.
5. Compile the source with the LAN743x and MAXLINEAR_GPY_PHY support.
6. Make sure the driver is installed using lsmod 
