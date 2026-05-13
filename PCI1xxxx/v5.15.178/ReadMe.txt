README for PCI1xxxx Linux Ethernet Backport Driver
Copyright (C) 2025 - 26 Microchip Technology Inc.

This ReadMe.txt is for PCI1xxxx LAN743x Ethernet Backport info.
Component Name : lan743x

Version Number : v1

Patch File     : v5.15.178_LAN743x.patch

Copyright      : Microchip Technology Inc.

Ubuntu Version : 20.04

Installation Procedure: Please check below

Kernel Version tested  : v5.15.178

Git Path: git://git.kernel.org/pub/scm/linux/kernel/git/stable/linux-stable.git

Installation Procedure : 
1. Clone the v5.15.120 Linux Kernel Source
2. Apply the v5.15.178_LAN743x patch file on top of the v5.15.178 source.
4. Compile the source with the LAN743x support
5. Make sure the driver is installed using lsmod 

