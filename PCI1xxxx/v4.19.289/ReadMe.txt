README for PCI1xxxx Linux Ethernet Backport Driver
Copyright (C) 2022 - 23 Microchip Technology Inc.

This ReadMe.txt is for PCI1xxxx LAN743x Ethernet Driver Backport info.
Component Name : lan743x

Version Number : v1

Patch File     : v4.19.289_LAN743x.patch

Copyright      : Microchip Technology Inc.

Ubuntu Version : 20.04

Installation Procedure: Please check below

Kernel Version tested  : v4.19.289

Git Path: git://git.kernel.org/pub/scm/linux/kernel/git/stable/linux-stable.git
 

Installation Procedure : 
1. Clone the v4.19.289 Linux Kernel Source
2. Apply the patch file on top of the v4.19.289 source
3. Compile the source with the LAN743x support
4. Make sure the driver is installed using lsmod 
