README for PCI1xxxx Linux Ethernet Backport Driver
Copyright (C) 2024 Microchip Technology Inc.

This ReadMe.txt is for PCI1xxxx LAN743x Ethernet Driver Backport info.
Component Name : lan743x

Version Number : v1

Patch File     : v6.1.78_LAN743x.patch

Copyright      : Microchip Technology Inc.

Ubuntu Version : 20.04

Installation Procedure: Please check below

Kernel Version tested  : v6.1.78

Git Path: git://git.kernel.org/pub/scm/linux/kernel/git/stable/linux-stable.git

Installation Procedure : 
1. Clone the v6.1.78 Linux Kernel Source
2. Apply the v6.1.78_LAN743x patch file on top of the v6.1.78 source.
3. Apply the v6.1.78_LAN743x_PTP_TimeoutDelay patch
4. Compile the source with the LAN743x support
5. Make sure the driver is installed using lsmod 
