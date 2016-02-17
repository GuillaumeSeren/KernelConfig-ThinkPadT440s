KernelConfig-ThinkPadT440s
==========================
My Linux Kernel configuration for a Lenovo ThinkPad T440s

## My 'lspci -nnk':
```
00:00.0 Host bridge [0600]: Intel Corporation Haswell-ULT DRAM Controller [8086:0a04] (rev 0b)
	Subsystem: Lenovo Haswell-ULT DRAM Controller [17aa:220c]
	Kernel driver in use: hsw_uncore
00:02.0 VGA compatible controller [0300]: Intel Corporation Haswell-ULT Integrated Graphics Controller [8086:0a16] (rev 0b)
	Subsystem: Lenovo Haswell-ULT Integrated Graphics Controller [17aa:220c]
	Kernel driver in use: i915
	Kernel modules: i915
00:03.0 Audio device [0403]: Intel Corporation Haswell-ULT HD Audio Controller [8086:0a0c] (rev 0b)
	Subsystem: Lenovo Haswell-ULT HD Audio Controller [17aa:220c]
	Kernel driver in use: snd_hda_intel
	Kernel modules: snd_hda_intel
00:14.0 USB controller [0c03]: Intel Corporation 8 Series USB xHCI HC [8086:9c31] (rev 04)
	Subsystem: Lenovo 8 Series USB xHCI HC [17aa:220c]
	Kernel driver in use: xhci_hcd
	Kernel modules: xhci_pci
00:16.0 Communication controller [0780]: Intel Corporation 8 Series HECI #0 [8086:9c3a] (rev 04)
	Subsystem: Lenovo 8 Series HECI [17aa:220c]
00:16.3 Serial controller [0700]: Intel Corporation 8 Series HECI KT [8086:9c3d] (rev 04)
	Subsystem: Lenovo 8 Series HECI KT [17aa:220c]
00:19.0 Ethernet controller [0200]: Intel Corporation Ethernet Connection I218-LM [8086:155a] (rev 04)
	Subsystem: Lenovo ThinkPad X240 [17aa:2214]
	Kernel driver in use: e1000e
	Kernel modules: e1000e
00:1b.0 Audio device [0403]: Intel Corporation 8 Series HD Audio Controller [8086:9c20] (rev 04)
	Subsystem: Lenovo 8 Series HD Audio Controller [17aa:220c]
	Kernel driver in use: snd_hda_intel
	Kernel modules: snd_hda_intel
00:1c.0 PCI bridge [0604]: Intel Corporation 8 Series PCI Express Root Port 6 [8086:9c1a] (rev e4)
	Kernel driver in use: pcieport
00:1c.1 PCI bridge [0604]: Intel Corporation 8 Series PCI Express Root Port 3 [8086:9c14] (rev e4)
	Kernel driver in use: pcieport
00:1d.0 USB controller [0c03]: Intel Corporation 8 Series USB EHCI #1 [8086:9c26] (rev 04)
	Subsystem: Lenovo 8 Series USB EHCI [17aa:220c]
	Kernel driver in use: ehci-pci
	Kernel modules: ehci_pci
00:1f.0 ISA bridge [0601]: Intel Corporation 8 Series LPC Controller [8086:9c43] (rev 04)
	Subsystem: Lenovo 8 Series LPC Controller [17aa:220c]
	Kernel driver in use: lpc_ich
	Kernel modules: lpc_ich
00:1f.2 SATA controller [0106]: Intel Corporation 8 Series SATA Controller 1 [AHCI mode] [8086:9c03] (rev 04)
	Subsystem: Lenovo 8 Series SATA Controller 1 [AHCI mode] [17aa:220c]
	Kernel driver in use: ahci
00:1f.3 SMBus [0c05]: Intel Corporation 8 Series SMBus Controller [8086:9c22] (rev 04)
	Subsystem: Lenovo 8 Series SMBus Controller [17aa:220c]
	Kernel driver in use: i801_smbus
	Kernel modules: i2c_i801
02:00.0 Unassigned class [ff00]: Realtek Semiconductor Co., Ltd. RTS5227 PCI Express Card Reader [10ec:5227] (rev 01)
	Subsystem: Lenovo RTS5227 PCI Express Card Reader [17aa:220c]
	Kernel driver in use: rtsx_pci
	Kernel modules: rtsx_pci
03:00.0 Network controller [0280]: Intel Corporation Wireless 7260 [8086:08b2] (rev 83)
	Subsystem: Intel Corporation Dual Band Wireless-N 7260 [8086:c260]
	Kernel driver in use: iwlwifi
	Kernel modules: iwlwifi
```

## The 'lsusb'
```
Bus 001 Device 003: ID 04f3:0224 Elan Microelectronics Corp.
Bus 001 Device 002: ID 8087:8000 Intel Corp.
Bus 001 Device 001: ID 1d6b:0002 Linux Foundation 2.0 root hub
Bus 003 Device 002: ID 17ef:1012 Lenovo
Bus 003 Device 001: ID 1d6b:0003 Linux Foundation 3.0 root hub
Bus 002 Device 007: ID 5986:026a Acer, Inc
Bus 002 Device 006: ID 8087:07dc Intel Corp.
Bus 002 Device 005: ID 138a:0017 Validity Sensors, Inc. Fingerprint Reader
Bus 002 Device 003: ID 0bdb:193e Ericsson Business Mobile Networks BV
Bus 002 Device 004: ID 17ef:1011 Lenovo
Bus 002 Device 002: ID 17ef:1012 Lenovo
Bus 002 Device 001: ID 1d6b:0002 Linux Foundation 2.0 root hub
```

## Links
Links form inspirations:
* Gentoo Pappy's Kernel Seeds: https://forums.gentoo.org/viewtopic-t-887894.html
* KernelHub: http://www.kernelhub.org/
* Gentoo Kernel Seeds: https://wiki.gentoo.org/wiki/Kernel/Configuration/Kernel_Seeds
* Funtoo Kernel Seeds: http://www.funtoo.org/Talk:Kernel_Seeds
