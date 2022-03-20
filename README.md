PCI Devices Population
======================

This is a project to estimate population of PCI devices in the world by
the analysis of hardware probes collected by Linux users at https://linux-hardware.org.

Everyone can contribute to this report by uploading probes of their computers by
the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Contents
--------

* [ Access bus ](#access-bus-pci)
* [ Bluetooth ](#bluetooth-pci)
* [ Bridge ](#bridge-pci)
* [ Card reader ](#card-reader-pci)
* [ Co-processor ](#co-processor-pci)
* [ Communication controller ](#communication-controller-pci)
* [ Digitizer pen ](#digitizer-pen-pci)
* [ Dma controller ](#dma-controller-pci)
* [ Docking station ](#docking-station-pci)
* [ Dpio module ](#dpio-module-pci)
* [ Dvb card ](#dvb-card-pci)
* [ Encryption controller ](#encryption-controller-pci)
* [ Entertainment encryption device ](#entertainment-encryption-device-pci)
* [ Firewire controller ](#firewire-controller-pci)
* [ Flash memory ](#flash-memory-pci)
* [ Generic system peripheral ](#generic-system-peripheral-pci)
* [ Graphics card ](#graphics-card-pci)
* [ I/o card ](#io-card-pci)
* [ Input device controller ](#input-device-controller-pci)
* [ Iommu ](#iommu-pci)
* [ Ipmi smic interface ](#ipmi-smic-interface-pci)
* [ Isdn adapter ](#isdn-adapter-pci)
* [ Memory controller ](#memory-controller-pci)
* [ Modem ](#modem-pci)
* [ Multimedia ](#multimedia-pci)
* [ Multimedia controller ](#multimedia-controller-pci)
* [ Multiport serial controller ](#multiport-serial-controller-pci)
* [ Net/ethernet ](#netethernet-pci)
* [ Net/other ](#netother-pci)
* [ Net/wireless ](#netwireless-pci)
* [ Network and computing encryption device ](#network-and-computing-encryption-device-pci)
* [ Non-essential instrumentation ](#non-essential-instrumentation-pci)
* [ Non-vga unclassified device ](#non-vga-unclassified-device-pci)
* [ Parallel controller ](#parallel-controller-pci)
* [ Performance counters ](#performance-counters-pci)
* [ Pic ](#pic-pci)
* [ Power pc ](#power-pc-pci)
* [ Processing accelerators ](#processing-accelerators-pci)
* [ Rf controller ](#rf-controller-pci)
* [ Sd host controller ](#sd-host-controller-pci)
* [ Serial bus controller ](#serial-bus-controller-pci)
* [ Serial controller ](#serial-controller-pci)
* [ Signal processing controller ](#signal-processing-controller-pci)
* [ Signal processing management ](#signal-processing-management-pci)
* [ Smbus ](#smbus-pci)
* [ Sound ](#sound-pci)
* [ Storage/ata ](#storageata-pci)
* [ Storage/ide ](#storageide-pci)
* [ Storage/nvme ](#storagenvme-pci)
* [ Storage/other ](#storageother-pci)
* [ Storage/raid ](#storageraid-pci)
* [ Storage/sas ](#storagesas-pci)
* [ Storage/scsi ](#storagescsi-pci)
* [ System peripheral ](#system-peripheral-pci)
* [ Tv card ](#tv-card-pci)
* [ Unknown ](#unknown-pci)
* [ Usb controller ](#usb-controller-pci)

### Access bus (PCI)

Total devices: 1

| ID            | MFG         | Name                         | Count |
|---------------|-------------|------------------------------|-------|
| pci:1106-303a | VIA Tech... | ACCESS Bus                   | 1     |

### Bluetooth (PCI)

Total devices: 817

| ID            | MFG         | Name                         | Count |
|---------------|-------------|------------------------------|-------|
| pci:1814-3298 | Ralink      | RT3290 Bluetooth             | 817   |

### Bridge (PCI)

Total devices: 1093787

| ID            | MFG         | Name                         | Count |
|---------------|-------------|------------------------------|-------|
| pci:8086-244e | Intel       | 82801 PCI Bridge             | 19130 |
| pci:1022-790e | AMD         | FCH LPC Bridge               | 15116 |
| pci:8086-2448 | Intel       | 82801 Mobile PCI Bridge      | 13851 |
| pci:8086-1c10 | Intel       | 6 Series/C200 Series Chip... | 10783 |
| pci:8086-1901 | Intel       | 6th-10th Gen Core Process... | 10696 |
| pci:8086-1e10 | Intel       | 7 Series/C216 Chipset Fam... | 10331 |
| pci:1002-4384 | AMD         | SBx00 PCI to PCI Bridge      | 8071  |
| pci:1002-439d | AMD         | SB7x0/SB8x0/SB9x0 LPC hos... | 7417  |
| pci:8086-0104 | Intel       | 2nd Generation Core Proce... | 7155  |
| pci:8086-27d0 | Intel       | NM10/ICH7 Family PCI Expr... | 7034  |
| pci:1022-1452 | AMD         | Family 17h (Models 00h-1f... | 6957  |
| pci:8086-0154 | Intel       | 3rd Gen Core processor DR... | 6570  |
| pci:8086-1e12 | Intel       | 7 Series/C210 Series Chip... | 6565  |
| pci:8086-0101 | Intel       | Xeon E3-1200/2nd Generati... | 6382  |
| pci:8086-9d14 | Intel       | Sunrise Point-LP PCI Expr... | 6241  |
| pci:8086-8c10 | Intel       | 8 Series/C220 Series Chip... | 5941  |
| pci:8086-1c12 | Intel       | 6 Series/C200 Series Chip... | 5902  |
| pci:8086-9d10 | Intel       | Sunrise Point-LP PCI Expr... | 5869  |
| pci:8086-0151 | Intel       | Xeon E3-1200 v2/3rd Gen C... | 5785  |
| pci:8086-3b42 | Intel       | 5 Series/3400 Series Chip... | 5517  |
| pci:1022-780e | AMD         | FCH LPC Bridge               | 5475  |
| pci:8086-27d2 | Intel       | NM10/ICH7 Family PCI Expr... | 5388  |
| pci:8086-2940 | Intel       | 82801I (ICH9 Family) PCI ... | 5295  |
| pci:8086-0c01 | Intel       | Xeon E3-1200 v3/4th Gen C... | 5250  |
| pci:8086-1c16 | Intel       | 6 Series/C200 Series Chip... | 5222  |
| pci:8086-9d15 | Intel       | Sunrise Point-LP PCI Expr... | 5190  |
| pci:8086-0c00 | Intel       | 4th Gen Core Processor DR... | 5140  |
| pci:8086-9d4e | Intel       | Sunrise Point LPC Control... | 5113  |
| pci:1022-1200 | AMD         | Family 10h Processor Hype... | 4673  |
| pci:1022-1201 | AMD         | Family 10h Processor Addr... | 4673  |
| pci:1022-1202 | AMD         | Family 10h Processor DRAM... | 4673  |
| pci:1022-1203 | AMD         | Family 10h Processor Misc... | 4673  |
| pci:1022-1204 | AMD         | Family 10h Processor Link... | 4673  |
| pci:8086-1e14 | Intel       | 7 Series/C210 Series Chip... | 4664  |
| pci:8086-2d01 | Intel       | Core Processor QuickPath ... | 4638  |
| pci:8086-2d10 | Intel       | Core Processor QPI Link 0    | 4638  |
| pci:8086-2d11 | Intel       | 1st Generation Core i3/5/... | 4638  |
| pci:8086-2d12 | Intel       | 1st Generation Core i3/5/... | 4638  |
| pci:8086-2d13 | Intel       | 1st Generation Core i3/5/... | 4638  |
| pci:8086-27b8 | Intel       | 82801GB/GR (ICH7 Family) ... | 4357  |
| pci:8086-0100 | Intel       | 2nd Generation Core Proce... | 4235  |
| pci:8086-1c14 | Intel       | 6 Series/C200 Series Chip... | 4028  |
| pci:8086-1c18 | Intel       | 6 Series/C200 Series Chip... | 4002  |
| pci:8086-2a40 | Intel       | Mobile 4 Series Chipset M... | 3938  |
| pci:1022-15d0 | AMD         | Raven/Raven2 Root Complex    | 3936  |
| pci:1022-15db | AMD         | Raven/Raven2 Internal PCI... | 3936  |
| pci:1022-15e8 | AMD         | Raven/Raven2 Device 24: F... | 3936  |
| pci:1022-15e9 | AMD         | Raven/Raven2 Device 24: F... | 3936  |
| pci:1022-15ea | AMD         | Raven/Raven2 Device 24: F... | 3936  |
| pci:1022-15eb | AMD         | Raven/Raven2 Device 24: F... | 3936  |
| pci:1022-15ec | AMD         | Raven/Raven2 Device 24: F... | 3936  |
| pci:1022-15ed | AMD         | Raven/Raven2 Device 24: F... | 3936  |
| pci:1022-15ee | AMD         | Raven/Raven2 Device 24: F... | 3936  |
| pci:1022-15ef | AMD         | Raven/Raven2 Device 24: F... | 3936  |
| pci:8086-0150 | Intel       | Xeon E3-1200 v2/3rd Gen C... | 3930  |
| pci:8086-9d18 | Intel       | Sunrise Point-LP PCI Expr... | 3912  |
| pci:8086-8c14 | Intel       | 8 Series/C220 Series Chip... | 3891  |
| pci:1022-15d3 | AMD         | Raven/Raven2 PCIe GPP Bri... | 3846  |
| pci:8086-3b44 | Intel       | 5 Series/3400 Series Chip... | 3823  |
| pci:8086-1e16 | Intel       | 7 Series/C216 Chipset Fam... | 3822  |
| pci:8086-0044 | Intel       | Core Processor DRAM Contr... | 3818  |
| pci:8086-2c62 | Intel       | Core Processor QuickPath ... | 3802  |
| pci:1022-780f | AMD         | FCH PCI Bridge               | 3740  |
| pci:8086-1c49 | Intel       | HM65 Express Chipset LPC ... | 3655  |
| pci:1022-1480 | AMD         | Starship/Matisse Root Com... | 3647  |
| pci:1022-1482 | AMD         | Starship/Matisse PCIe Dum... | 3647  |
| pci:1022-1483 | AMD         | Starship/Matisse GPP Bridge  | 3647  |
| pci:1022-1484 | AMD         | Starship/Matisse Internal... | 3647  |
| pci:8086-1c1a | Intel       | 6 Series/C200 Series Chip... | 3622  |
| pci:1b21-1080 | ASMedia ... | ASM1083/1085 PCIe to PCI ... | 3525  |
| pci:8086-2942 | Intel       | 82801I (ICH9 Family) PCI ... | 3513  |
| pci:1022-1440 | AMD         | Matisse/Vermeer Data Fabr... | 3502  |
| pci:1022-1441 | AMD         | Matisse/Vermeer Data Fabr... | 3502  |
| pci:1022-1442 | AMD         | Matisse/Vermeer Data Fabr... | 3502  |
| pci:1022-1443 | AMD         | Matisse/Vermeer Data Fabr... | 3502  |
| pci:1022-1444 | AMD         | Matisse/Vermeer Data Fabr... | 3502  |
| pci:1022-1445 | AMD         | Matisse/Vermeer Data Fabr... | 3502  |
| pci:1022-1446 | AMD         | Matisse/Vermeer Data Fabr... | 3502  |
| pci:1022-1447 | AMD         | Matisse/Vermeer Data Fabr... | 3502  |
| pci:8086-0a04 | Intel       | Haswell-ULT DRAM Controller  | 3460  |
| pci:8086-5904 | Intel       | Xeon E3-1200 v6/7th Gen C... | 3291  |
| pci:1022-43c6 | AMD         | 400 Series Chipset PCIe B... | 3218  |
| pci:1022-43c7 | AMD         | 400 Series Chipset PCIe Port | 3218  |
| pci:8086-a330 | Intel       | Cannon Lake PCH PCI Expre... | 3141  |
| pci:8086-5914 | Intel       | Xeon E3-1200 v6/7th Gen C... | 3127  |
| pci:8086-2919 | Intel       | ICH9M LPC Interface Contr... | 3041  |
| pci:1022-1450 | AMD         | Family 17h (Models 00h-0f... | 3026  |
| pci:1022-1453 | AMD         | Family 17h (Models 00h-0f... | 3026  |
| pci:1022-1454 | AMD         | Family 17h (Models 00h-0f... | 3026  |
| pci:1022-1460 | AMD         | Family 17h (Models 00h-0f... | 3026  |
| pci:1022-1461 | AMD         | Family 17h (Models 00h-0f... | 3026  |
| pci:1022-1462 | AMD         | Family 17h (Models 00h-0f... | 3026  |
| pci:1022-1463 | AMD         | Family 17h (Models 00h-0f... | 3026  |
| pci:1022-1464 | AMD         | Family 17h (Models 00h-0f... | 3026  |
| pci:1022-1465 | AMD         | Family 17h (Models 00h-0f... | 3026  |
| pci:1022-1466 | AMD         | Family 17h (Models 00h-0f... | 3026  |
| pci:1022-1467 | AMD         | Family 17h (Models 00h-0f... | 3026  |
| pci:8086-1e59 | Intel       | HM76 Express Chipset LPC ... | 2984  |
| pci:8086-1c5c | Intel       | H61 Express Chipset LPC C... | 2959  |
| pci:8086-9c43 | Intel       | 8 Series LPC Controller      | 2951  |
| pci:8086-283f | Intel       | 82801H (ICH8 Family) PCI ... | 2919  |
| pci:1022-1630 | AMD         | Renoir/Cezanne Root Complex  | 2866  |
| pci:1022-1632 | AMD         | Renoir PCIe Dummy Host Br... | 2866  |
| pci:1022-1635 | AMD         | Renoir Internal PCIe GPP ... | 2866  |
| pci:1022-1634 | AMD         | Renoir/Cezanne PCIe GPP B... | 2865  |
| pci:8086-1904 | Intel       | Xeon E3-1200 v5/E3-1500 v... | 2865  |
| pci:8086-a114 | Intel       | 100 Series/C230 Series Ch... | 2862  |
| pci:1022-15dc | AMD         | Raven/Raven2 Internal PCI... | 2847  |
| pci:8086-9d48 | Intel       | Sunrise Point-LP LPC Cont... | 2812  |
| pci:8086-a118 | Intel       | 100 Series/C230 Series Ch... | 2784  |
| pci:8086-9c14 | Intel       | 8 Series PCI Express Root... | 2725  |
| pci:8086-1604 | Intel       | Broadwell-U Host Bridge -OPI | 2706  |
| pci:1022-1600 | AMD         | Family 15h Processor Func... | 2701  |
| pci:1022-1601 | AMD         | Family 15h Processor Func... | 2701  |
| pci:1022-1602 | AMD         | Family 15h Processor Func... | 2701  |
| pci:1022-1603 | AMD         | Family 15h Processor Func... | 2701  |
| pci:1022-1604 | AMD         | Family 15h Processor Func... | 2701  |
| pci:1022-1605 | AMD         | Family 15h Processor Func... | 2701  |
| pci:8086-9c16 | Intel       | 8 Series PCI Express Root... | 2656  |
| pci:8086-8c16 | Intel       | 8 Series/C220 Series Chip... | 2653  |
| pci:8086-9d84 | Intel       | Cannon Point-LP LPC Contr... | 2610  |
| pci:8086-3b09 | Intel       | HM55 Chipset LPC Interfac... | 2587  |
| pci:8086-2948 | Intel       | 82801I (ICH9 Family) PCI ... | 2586  |
| pci:8086-29c0 | Intel       | 82G33/G31/P35/P31 Express... | 2528  |
| pci:1022-1100 | AMD         | K8 [Athlon64/Opteron] Hyp... | 2484  |
| pci:1022-1101 | AMD         | K8 [Athlon64/Opteron] Add... | 2484  |
| pci:1022-1102 | AMD         | K8 [Athlon64/Opteron] DRA... | 2484  |
| pci:1022-1103 | AMD         | K8 [Athlon64/Opteron] Mis... | 2484  |
| pci:8086-2280 | Intel       | Atom/Celeron/Pentium Proc... | 2438  |
| pci:8086-229c | Intel       | Atom/Celeron/Pentium Proc... | 2438  |
| pci:1022-43b4 | AMD         | 300 Series Chipset PCIe Port | 2435  |
| pci:8086-2944 | Intel       | 82801I (ICH9 Family) PCI ... | 2355  |
| pci:8086-9c10 | Intel       | 8 Series PCI Express Root... | 2342  |
| pci:8086-27d4 | Intel       | NM10/ICH7 Family PCI Expr... | 2331  |
| pci:8086-3b46 | Intel       | 5 Series/3400 Series Chip... | 2316  |
| pci:1002-43a0 | AMD         | SB700/SB800/SB900 PCI to ... | 2309  |
| pci:8086-2a00 | Intel       | Mobile PM965/GM965/GL960 ... | 2291  |
| pci:1022-1448 | AMD         | Renoir Device 24: Function 0 | 2272  |
| pci:1022-1449 | AMD         | Renoir Device 24: Function 1 | 2272  |
| pci:1022-144a | AMD         | Renoir Device 24: Function 2 | 2272  |
| pci:1022-144b | AMD         | Renoir Device 24: Function 3 | 2272  |
| pci:1022-144c | AMD         | Renoir Device 24: Function 4 | 2272  |
| pci:1022-144d | AMD         | Renoir Device 24: Function 5 | 2272  |
| pci:1022-144e | AMD         | Renoir Device 24: Function 6 | 2272  |
| pci:1022-144f | AMD         | Renoir Device 24: Function 7 | 2272  |
| pci:8086-3e34 | Intel       | Coffee Lake HOST and DRAM... | 2269  |
| pci:8086-9c90 | Intel       | Wildcat Point-LP PCI Expr... | 2217  |
| pci:8086-2946 | Intel       | 82801I (ICH9 Family) PCI ... | 2211  |
| pci:8086-0c04 | Intel       | Xeon E3-1200 v3/4th Gen C... | 2206  |
| pci:1022-1700 | AMD         | Family 12h/14h Processor ... | 2193  |
| pci:1022-1701 | AMD         | Family 12h/14h Processor ... | 2193  |
| pci:1022-1702 | AMD         | Family 12h/14h Processor ... | 2193  |
| pci:1022-1703 | AMD         | Family 12h/14h Processor ... | 2193  |
| pci:1022-1704 | AMD         | Family 12h/14h Processor ... | 2193  |
| pci:1022-1716 | AMD         | Family 12h/14h Processor ... | 2193  |
| pci:1022-1718 | AMD         | Family 12h/14h Processor ... | 2193  |
| pci:1022-1719 | AMD         | Family 12h/14h Processor ... | 2193  |
| pci:8086-3b48 | Intel       | 5 Series/3400 Series Chip... | 2178  |
| pci:8086-0f00 | Intel       | Atom Processor Z36xxx/Z37... | 2175  |
| pci:8086-0f1c | Intel       | Atom Processor Z36xxx/Z37... | 2175  |
| pci:1022-9600 | AMD         | RS780 Host Bridge            | 2161  |
| pci:8086-9c94 | Intel       | Wildcat Point-LP PCI Expr... | 2138  |
| pci:1022-9603 | AMD         | RS780 PCI to PCI bridge (... | 2133  |
| pci:8086-3ec4 | Intel       | 8th Gen Core Processor Ho... | 2090  |
| pci:8086-3b4a | Intel       | 5 Series/3400 Series Chip... | 2086  |
| pci:8086-2815 | Intel       | 82801HM (ICH8M) LPC Inter... | 2078  |
| pci:8086-9cc3 | Intel       | Wildcat Point-LP LPC Cont... | 2068  |
| pci:8086-a30d | Intel       | HM470 Chipset LPC/eSPI Co... | 2068  |
| pci:8086-9db0 | Intel       | Cannon Point-LP PCI Expre... | 2055  |
| pci:8086-3a40 | Intel       | 82801JI (ICH10 Family) PC... | 2031  |
| pci:8086-2841 | Intel       | 82801H (ICH8 Family) PCI ... | 2024  |
| pci:8086-294a | Intel       | 82801I (ICH9 Family) PCI ... | 1992  |
| pci:8086-1e57 | Intel       | HM77 Express Chipset LPC ... | 1982  |
| pci:8086-a110 | Intel       | 100 Series/C230 Series Ch... | 1978  |
| pci:1002-5a14 | AMD         | RD9x0/RX980 Host Bridge      | 1930  |
| pci:1002-5a16 | AMD         | RD890/RD9x0/RX980 PCI to ... | 1928  |
| pci:8086-29c1 | Intel       | 82G33/G31/P35/P31 Express... | 1920  |
| pci:8086-3b4c | Intel       | 5 Series/3400 Series Chip... | 1867  |
| pci:8086-22c8 | Intel       | Atom/Celeron/Pentium Proc... | 1845  |
| pci:8086-27d6 | Intel       | NM10/ICH7 Family PCI Expr... | 1833  |
| pci:1022-1400 | AMD         | Family 15h (Models 10h-1f... | 1815  |
| pci:1022-1401 | AMD         | Family 15h (Models 10h-1f... | 1815  |
| pci:1022-1402 | AMD         | Family 15h (Models 10h-1f... | 1815  |
| pci:1022-1403 | AMD         | Family 15h (Models 10h-1f... | 1815  |
| pci:1022-1404 | AMD         | Family 15h (Models 10h-1f... | 1815  |
| pci:1022-1405 | AMD         | Family 15h (Models 10h-1f... | 1815  |
| pci:1022-1410 | AMD         | Family 15h (Models 10h-1f... | 1815  |
| pci:8086-0284 | Intel       | Comet Lake PCH-LP LPC Pre... | 1813  |
| pci:8086-a082 | Intel       | Tiger Lake-LP LPC Controller | 1805  |
| pci:8086-9c96 | Intel       | Wildcat Point-LP PCI Expr... | 1803  |
| pci:8086-0f48 | Intel       | Atom Processor E3800 Seri... | 1798  |
| pci:1022-43a0 | AMD         | Hudson PCI to PCI bridge ... | 1763  |
| pci:8086-8c5c | Intel       | H81 Express LPC Controller   | 1747  |
| pci:8086-0045 | Intel       | Core Processor PCI Expres... | 1739  |
| pci:1022-1439 | AMD         | Family 16h Processor Func... | 1735  |
| pci:1022-1576 | AMD         | Family 15h (Models 60h-6f... | 1724  |
| pci:1022-157b | AMD         | Family 15h (Models 60h-6f... | 1724  |
| pci:1022-157d | AMD         | Carrizo Audio Dummy Host ... | 1724  |
| pci:8086-9db4 | Intel       | Cannon Point-LP PCI Expre... | 1718  |
| pci:1022-157c | AMD         | Family 15h (Models 60h-6f... | 1717  |
| pci:1022-57a4 | AMD         | Matisse PCIe GPP Bridge      | 1717  |
| pci:1022-57ad | AMD         | Matisse Switch Upstream      | 1717  |
| pci:1022-57a3 | AMD         | Matisse PCIe GPP Bridge      | 1712  |
| pci:8086-9a14 | Intel       | 11th Gen Core Processor H... | 1671  |
| pci:8086-8c18 | Intel       | 8 Series/C220 Series Chip... | 1649  |
| pci:8086-1e18 | Intel       | 7 Series/C210 Series Chip... | 1640  |
| pci:8086-191f | Intel       | Xeon E3-1200 v5/E3-1500 v... | 1638  |
| pci:8086-9c18 | Intel       | 8 Series PCI Express Root... | 1631  |
| pci:8086-3ec2 | Intel       | 8th Gen Core Processor Ho... | 1628  |
| pci:8086-1c1e | Intel       | 6 Series/C200 Series Chip... | 1620  |
| pci:8086-a294 | Intel       | 200 Series PCH PCI Expres... | 1567  |
| pci:8086-2e30 | Intel       | 4 Series Chipset DRAM Con... | 1559  |
| pci:10de-03f3 | Nvidia      | MCP61 PCI bridge             | 1550  |
| pci:1002-5a18 | AMD         | RD890/RD9x0/RX980 PCI to ... | 1537  |
| pci:1022-9601 | AMD         | RS880 Host Bridge            | 1530  |
| pci:8086-a340 | Intel       | Cannon Lake PCH PCI Expre... | 1530  |
| pci:8086-9dbc | Intel       | Cannon Point-LP PCI Expre... | 1526  |
| pci:8086-1e1a | Intel       | 7 Series/C210 Series Chip... | 1523  |
| pci:8086-a112 | Intel       | 100 Series/C230 Series Ch... | 1510  |
| pci:8086-9b61 | Intel       | Comet Lake-U v1 4c Host B... | 1509  |
| pci:8086-1e55 | Intel       | QM77 Express Chipset LPC ... | 1498  |
| pci:10de-03e8 | Nvidia      | MCP61 PCI Express bridge     | 1484  |
| pci:8086-27b9 | Intel       | 82801GBM (ICH7-M) LPC Int... | 1474  |
| pci:8086-02b0 | Intel       | Comet Lake PCI Express Ro... | 1457  |
| pci:1180-0476 | Ricoh       | RL5c476 II                   | 1439  |
| pci:1022-9604 | AMD         | RS780/RS880 PCI to PCI br... | 1437  |
| pci:1022-1510 | AMD         | Family 14h Processor Root... | 1410  |
| pci:8086-3a16 | Intel       | 82801JIR (ICH10R) LPC Int... | 1400  |
| pci:8086-31f0 | Intel       | Gemini Lake Host Bridge      | 1396  |
| pci:8086-a298 | Intel       | 200 Series PCH PCI Expres... | 1394  |
| pci:8086-27bc | Intel       | NM10 Family LPC Controller   | 1384  |
| pci:8086-2847 | Intel       | 82801H (ICH8 Family) PCI ... | 1382  |
| pci:8086-31e8 | Intel       | Celeron/Pentium Silver Pr... | 1382  |
| pci:8086-9d12 | Intel       | Sunrise Point-LP PCI Expr... | 1361  |
| pci:8086-1c4f | Intel       | QM67 Express Chipset LPC ... | 1358  |
| pci:8086-9c98 | Intel       | Wildcat Point-LP PCI Expr... | 1352  |
| pci:8086-2a41 | Intel       | Mobile 4 Series Chipset P... | 1348  |
| pci:8086-a335 | Intel       | Cannon Lake PCH PCI Expre... | 1341  |
| pci:8086-3a4a | Intel       | 82801JI (ICH10 Family) PC... | 1337  |
| pci:10de-03e9 | Nvidia      | MCP61 PCI Express bridge     | 1325  |
| pci:8086-1c1c | Intel       | 6 Series/C200 Series Chip... | 1321  |
| pci:8086-02b4 | Intel       | Comet Lake PCI Express Ro... | 1304  |
| pci:1022-9606 | AMD         | RS780 PCI to PCI bridge (... | 1291  |
| pci:8086-a338 | Intel       | Cannon Lake PCH PCI Expre... | 1289  |
| pci:8086-0f4c | Intel       | Atom Processor E3800 Seri... | 1287  |
| pci:8086-a32c | Intel       | Cannon Lake PCH PCI Expre... | 1283  |
| pci:1022-9605 | AMD         | RS780/RS880 PCI to PCI br... | 1259  |
| pci:8086-0f4a | Intel       | Atom Processor E3800 Seri... | 1255  |
| pci:8086-2843 | Intel       | 82801H (ICH8 Family) PCI ... | 1244  |
| pci:1002-1478 | AMD         | Navi 10 XL Upstream Port ... | 1232  |
| pci:1002-1479 | AMD         | Navi 10 XL Downstream Por... | 1231  |
| pci:1002-5a1c | AMD         | RD890/RD9x0/RX980 PCI to ... | 1227  |
| pci:8086-9d58 | Intel       | Sunrise Point-LP LPC Cont... | 1226  |
| pci:8086-0f4e | Intel       | Atom Processor E3800 Seri... | 1212  |
| pci:8086-3a48 | Intel       | 82801JI (ICH10 Family) PC... | 1199  |
| pci:8086-5910 | Intel       | Xeon E3-1200 v6/7th Gen C... | 1191  |
| pci:1022-9609 | AMD         | RS780/RS880 PCI to PCI br... | 1182  |
| pci:8086-2845 | Intel       | 82801H (ICH8 Family) PCI ... | 1166  |
| pci:8086-8c12 | Intel       | 8 Series/C220 Series Chip... | 1157  |
| pci:8086-591f | Intel       | Xeon E3-1200 v6/7th Gen C... | 1135  |
| pci:8086-2770 | Intel       | 82945G/GZ/P/PL Memory Con... | 1129  |
| pci:8086-2e20 | Intel       | 4 Series Chipset DRAM Con... | 1100  |
| pci:1022-1414 | AMD         | Family 15h (Models 10h-1f... | 1098  |
| pci:1002-43a1 | AMD         | SB700/SB800/SB900 PCI to ... | 1087  |
| pci:8086-9a23 | Intel       | Tiger Lake-LP Thunderbolt... | 1081  |
| pci:8086-a143 | Intel       | H110 Chipset LPC/eSPI Con... | 1075  |
| pci:8086-340a | Intel       | 5520/5500/X58 I/O Hub PCI... | 1074  |
| pci:8086-27a0 | Intel       | Mobile 945GM/PM/GMS, 943/... | 1072  |
| pci:8086-06b0 | Intel       | Comet Lake PCI Express Ro... | 1069  |
| pci:8086-3408 | Intel       | 5520/5500/X58 I/O Hub PCI... | 1066  |
| pci:8086-a115 | Intel       | 100 Series/C230 Series Ch... | 1064  |
| pci:8086-a33c | Intel       | Cannon Lake PCH PCI Expre... | 1045  |
| pci:8086-a336 | Intel       | Cannon Lake PCH PCI Expre... | 1025  |
| pci:8086-340e | Intel       | 5520/5500/X58 I/O Hub PCI... | 1022  |
| pci:8086-a116 | Intel       | 100 Series/C230 Series Ch... | 1017  |
| pci:8086-a290 | Intel       | 200 Series PCH PCI Expres... | 1017  |
| pci:1022-15b0 | AMD         | Stoney HT Configuration      | 1012  |
| pci:1022-15b1 | AMD         | Stoney Address Maps          | 1012  |
| pci:1022-15b2 | AMD         | Stoney DRAM Configuration    | 1012  |
| pci:1022-15b3 | AMD         | Stoney Miscellaneous Conf... | 1012  |
| pci:1022-15b4 | AMD         | Stoney PM Configuration      | 1012  |
| pci:1022-15b5 | AMD         | Stoney NB Performance Mon... | 1012  |
| pci:8086-31d8 | Intel       | Gemini Lake PCI Express R... | 1008  |
| pci:8086-a152 | Intel       | HM175 Chipset LPC/eSPI Co... | 1007  |
| pci:1022-1566 | AMD         | Family 16h (Models 30h-3f... | 1005  |
| pci:1022-156b | AMD         | Family 16h (Models 30h-3f... | 1005  |
| pci:1022-1580 | AMD         | Family 16h (Models 30h-3f... | 1005  |
| pci:1022-1581 | AMD         | Family 16h (Models 30h-3f... | 1005  |
| pci:1022-1582 | AMD         | Family 16h (Models 30h-3f... | 1005  |
| pci:1022-1583 | AMD         | Family 16h (Models 30h-3f... | 1005  |
| pci:1022-1584 | AMD         | Family 16h (Models 30h-3f... | 1005  |
| pci:1022-1585 | AMD         | Family 16h (Models 30h-3f... | 1005  |
| pci:8086-3482 | Intel       | Ice Lake-LP LPC Controller   | 1003  |
| pci:8086-a0b0 | Intel       | Tiger Lake-LP PCI Express... | 1000  |
| pci:8086-8c90 | Intel       | 9 Series Chipset Family P... | 997   |
| pci:8086-d138 | Intel       | Core Processor PCI Expres... | 990   |
| pci:1022-43e9 | AMD         | 500 Series Chipset Switch... | 989   |
| pci:1022-43ea | AMD         | Starship/Matisse PCIe Dow... | 989   |
| pci:8086-2c81 | Intel       | Core Processor QuickPath ... | 983   |
| pci:8086-2c90 | Intel       | Core Processor QPI Link 0    | 983   |
| pci:8086-2c91 | Intel       | Core Processor QPI Physic... | 983   |
| pci:8086-2c98 | Intel       | Core Processor Integrated... | 983   |
| pci:8086-2c99 | Intel       | Core Processor Integrated... | 983   |
| pci:8086-2c9c | Intel       | Core Processor Integrated... | 983   |
| pci:8086-2ca0 | Intel       | Core Processor Integrated... | 983   |
| pci:8086-2ca1 | Intel       | Core Processor Integrated... | 983   |
| pci:8086-2ca2 | Intel       | Core Processor Integrated... | 983   |
| pci:8086-2ca3 | Intel       | Core Processor Integrated... | 983   |
| pci:8086-2ca8 | Intel       | Core Processor Integrated... | 983   |
| pci:8086-2ca9 | Intel       | Core Processor Integrated... | 983   |
| pci:8086-2caa | Intel       | Core Processor Integrated... | 983   |
| pci:8086-2cab | Intel       | Core Processor Integrated... | 983   |
| pci:8086-a113 | Intel       | 100 Series/C230 Series Ch... | 983   |
| pci:1022-1633 | AMD         | Renoir PCIe GPP Bridge       | 982   |
| pci:8086-1e44 | Intel       | Z77 Express Chipset LPC C... | 982   |
| pci:1022-43a1 | AMD         | Hudson PCI to PCI bridge ... | 971   |
| pci:8086-5ae8 | Intel       | Celeron N3350/Pentium N42... | 971   |
| pci:8086-5af0 | Intel       | Celeron N3350/Pentium N42... | 971   |
| pci:8086-2e31 | Intel       | 4 Series Chipset PCI Expr... | 969   |
| pci:8086-8c49 | Intel       | HM86 Express LPC Controller  | 955   |
| pci:8086-9d1a | Intel       | Sunrise Point-LP PCI Expr... | 942   |
| pci:8086-8c1a | Intel       | 8 Series/C220 Series Chip... | 939   |
| pci:8086-9a09 | Intel       | 11th Gen Core Processor P... | 938   |
| pci:8086-2e21 | Intel       | 4 Series Chipset PCI Expr... | 936   |
| pci:1022-9602 | AMD         | RS780/RS880 PCI to PCI br... | 934   |
| pci:1022-9607 | AMD         | RS780/RS880 PCI to PCI br... | 923   |
| pci:8086-3b07 | Intel       | QM57 Chipset LPC Interfac... | 922   |
| pci:8086-02bc | Intel       | Comet Lake PCI Express Ro... | 921   |
| pci:8086-9d13 | Intel       | Sunrise Point-LP PCI Expr... | 915   |
| pci:1022-43b2 | AMD         | FCH PCIe Port C (Switch USP) | 905   |
| pci:8086-2917 | Intel       | ICH9M-E LPC Interface Con... | 905   |
| pci:8086-22cc | Intel       | Atom/Celeron/Pentium Proc... | 904   |
| pci:1022-43a2 | AMD         | Hudson PCI to PCI bridge ... | 899   |
| pci:8086-15d3 | Intel       | JHL6540 Thunderbolt 3 Bri... | 892   |
| pci:1022-1412 | AMD         | Family 15h (Models 10h-1f... | 888   |
| pci:8086-a30e | Intel       | Cannon Lake LPC Controller   | 887   |
| pci:8086-15ea | Intel       | JHL7540 Thunderbolt 3 Bri... | 884   |
| pci:1002-43a3 | AMD         | SB900 PCI to PCI bridge (... | 882   |
| pci:8086-2a01 | Intel       | Mobile PM965/GM965/GL960 ... | 882   |
| pci:8086-9db8 | Intel       | Cannon Point-LP PCI Expre... | 878   |
| pci:8086-1910 | Intel       | Xeon E3-1200 v5/E3-1500 v... | 876   |
| pci:1022-43b3 | AMD         | FCH PCIe Port D (Switch USP) | 870   |
| pci:8086-2849 | Intel       | 82801H (ICH8 Family) PCI ... | 866   |
| pci:8086-a2e7 | Intel       | 200 Series PCH PCI Expres... | 853   |
| pci:8086-0040 | Intel       | Core Processor DRAM Contr... | 847   |
| pci:8086-1e5e | Intel       | HM70 Express Chipset LPC ... | 845   |
| pci:8086-2c61 | Intel       | Core Processor QuickPath ... | 836   |
| pci:104c-8039 | Texas In... | PCIxx12 Cardbus Controller   | 821   |
| pci:8086-1d41 | Intel       | C600/X79 series chipset L... | 814   |
| pci:8086-a010 | Intel       | Atom Processor D4xx/D5xx/... | 811   |
| pci:8086-8a12 | Intel       | Ice Lake-LP Processor Hos... | 806   |
| pci:8086-1e49 | Intel       | B75 Express Chipset LPC C... | 805   |
| pci:8086-22ce | Intel       | Atom/Celeron/Pentium Proc... | 802   |
| pci:8086-1e1e | Intel       | 7 Series/C210 Series Chip... | 798   |
| pci:8086-a145 | Intel       | Z170 Chipset LPC/eSPI Con... | 797   |
| pci:8086-15da | Intel       | JHL6340 Thunderbolt 3 Bri... | 795   |
| pci:8086-1d3e | Intel       | C600/X79 series chipset P... | 790   |
| pci:8086-8c4b | Intel       | HM87 Express LPC Controller  | 790   |
| pci:8086-2e10 | Intel       | 4 Series Chipset DRAM Con... | 789   |
| pci:8086-9c9a | Intel       | Wildcat Point-LP PCI Expr... | 788   |
| pci:10de-03e0 | Nvidia      | MCP61 LPC Bridge             | 787   |
| pci:1022-1705 | AMD         | Family 12h Processor Root... | 783   |
| pci:8086-3e10 | Intel       | 8th Gen Core 4-core Proce... | 783   |
| pci:1002-43a2 | AMD         | SB900 PCI to PCI bridge (... | 772   |
| pci:8086-a296 | Intel       | 200 Series PCH PCI Expres... | 769   |
| pci:8086-9c1a | Intel       | 8 Series PCI Express Root... | 768   |
| pci:10de-03e1 | Nvidia      | MCP61 LPC Bridge             | 763   |
| pci:8086-a167 | Intel       | 100 Series/C230 Series Ch... | 759   |
| pci:1283-8892 | Integrat... | IT8892E PCIe to PCI Bridge   | 757   |
| pci:8086-8c1c | Intel       | 8 Series/C220 Series Chip... | 753   |
| pci:8086-8cc4 | Intel       | Z97 Chipset LPC Controller   | 752   |
| pci:8086-a111 | Intel       | 100 Series/C230 Series Ch... | 748   |
| pci:8086-3a18 | Intel       | 82801JIB (ICH10) LPC Inte... | 740   |
| pci:8086-34b0 | Intel       | Ice Lake-LP PCI Express R... | 732   |
| pci:1022-1530 | AMD         | Family 16h Processor Func... | 730   |
| pci:1022-1531 | AMD         | Family 16h Processor Func... | 730   |
| pci:1022-1532 | AMD         | Family 16h Processor Func... | 730   |
| pci:1022-1533 | AMD         | Family 16h Processor Func... | 730   |
| pci:1022-1534 | AMD         | Family 16h Processor Func... | 730   |
| pci:1022-1535 | AMD         | Family 16h Processor Func... | 730   |
| pci:1022-1536 | AMD         | Family 16h Processor Root... | 730   |
| pci:1022-1538 | AMD         | Family 16h Processor Func... | 730   |
| pci:8086-1e47 | Intel       | Q77 Express Chipset LPC C... | 722   |
| pci:8086-15e7 | Intel       | JHL7540 Thunderbolt 3 Bri... | 719   |
| pci:1022-1570 | AMD         | Family 15h (Models 60h-6f... | 712   |
| pci:1022-1571 | AMD         | Family 15h (Models 60h-6f... | 712   |
| pci:1022-1572 | AMD         | Family 15h (Models 60h-6f... | 712   |
| pci:1022-1573 | AMD         | Family 15h (Models 60h-6f... | 712   |
| pci:1022-1574 | AMD         | Family 15h (Models 60h-6f... | 712   |
| pci:1022-1575 | AMD         | Family 15h (Models 60h-6f... | 712   |
| pci:8086-a2eb | Intel       | 200 Series PCH PCI Expres... | 702   |
| pci:8086-8c50 | Intel       | B85 Express LPC Controller   | 701   |
| pci:1002-5a19 | AMD         | RD890/RD9x0/RX980 PCI to ... | 698   |
| pci:1022-1512 | AMD         | Family 14h Processor Root... | 696   |
| pci:8086-2916 | Intel       | 82801IR (ICH9R) LPC Inter... | 695   |
| pci:8086-8c1e | Intel       | 8 Series/C220 Series Chip... | 687   |
| pci:8086-9c92 | Intel       | Wildcat Point-LP PCI Expr... | 685   |
| pci:8086-a117 | Intel       | 100 Series/C230 Series Ch... | 678   |
| pci:1002-5978 | AMD         | RX780/RD790 PCI to PCI br... | 676   |
| pci:8086-3a70 | Intel       | 82801JD/DO (ICH10 Family)... | 674   |
| pci:8086-a297 | Intel       | 200 Series PCH PCI Expres... | 670   |
| pci:8086-9d1b | Intel       | Skylake-U/Y PCIe Port #12    | 668   |
| pci:1022-141a | AMD         | Family 15h (Models 30h-3f... | 667   |
| pci:1022-141b | AMD         | Family 15h (Models 30h-3f... | 667   |
| pci:1022-141c | AMD         | Family 15h (Models 30h-3f... | 667   |
| pci:1022-141d | AMD         | Family 15h (Models 30h-3f... | 667   |
| pci:1022-141e | AMD         | Family 15h (Models 30h-3f... | 667   |
| pci:1022-141f | AMD         | Family 15h (Models 30h-3f... | 667   |
| pci:1022-1422 | AMD         | Family 15h (Models 30h-3f... | 667   |
| pci:1022-1424 | AMD         | Family 15h (Models 30h-3f... | 667   |
| pci:8086-1e1c | Intel       | 7 Series/C210 Series Chip... | 667   |
| pci:1002-438d | AMD         | SB600 PCI to LPC Bridge      | 654   |
| pci:8086-2771 | Intel       | 82945G/GZ/P/PL PCI Expres... | 651   |
| pci:8086-9c12 | Intel       | 8 Series PCI Express Root... | 639   |
| pci:14e4-2711 | Broadcom    | BCM2711 PCIe Bridge          | 636   |
| pci:8086-a0bc | Intel       | PCI bridge                   | 635   |
| pci:8086-8d10 | Intel       | C610/X99 series chipset P... | 633   |
| pci:1002-5a1b | AMD         | RD890/RD9x0/RX980 PCI to ... | 632   |
| pci:8086-8c4f | Intel       | QM87 Express LPC Controller  | 626   |
| pci:1002-5a1d | AMD         | RD890/RD9x0/RX980 PCI to ... | 618   |
| pci:8086-8c4e | Intel       | Q87 Express LPC Controller   | 614   |
| pci:8086-a305 | Intel       | Z390 Chipset LPC/eSPI Con... | 612   |
| pci:8086-3405 | Intel       | 5520/5500/X58 I/O Hub to ... | 611   |
| pci:8086-a14e | Intel       | HM170 Chipset LPC/eSPI Co... | 606   |
| pci:8086-1d10 | Intel       | C600/X79 series chipset P... | 595   |
| pci:1022-166a | AMD         | Cezanne Data Fabric; Func... | 594   |
| pci:1022-166b | AMD         | Cezanne Data Fabric; Func... | 594   |
| pci:1022-166c | AMD         | Cezanne Data Fabric; Func... | 594   |
| pci:1022-166d | AMD         | Cezanne Data Fabric; Func... | 594   |
| pci:1022-166e | AMD         | Cezanne Data Fabric; Func... | 594   |
| pci:1022-166f | AMD         | Cezanne Data Fabric; Func... | 594   |
| pci:1022-1670 | AMD         | Cezanne Data Fabric; Func... | 594   |
| pci:1022-1671 | AMD         | Cezanne Data Fabric; Func... | 594   |
| pci:1022-1709 | AMD         | Family 12h Processor Root... | 593   |
| pci:8086-068d | Intel       | Comet Lake LPC Controller    | 592   |
| pci:8086-8c44 | Intel       | Z87 Express LPC Controller   | 591   |
| pci:8086-d131 | Intel       | Core Processor DMI           | 589   |
| pci:8086-a2c9 | Intel       | Z370 Chipset LPC/eSPI Con... | 581   |
| pci:8086-15c0 | Intel       | JHL6240 Thunderbolt 3 Bri... | 578   |
| pci:8086-2c51 | Intel       | Core Processor QuickPath ... | 577   |
| pci:8086-06c0 | Intel       | Comet Lake PCI Express Ro... | 575   |
| pci:8086-9db1 | Intel       | Cannon Point-LP PCI Expre... | 570   |
| pci:10de-0aab | Nvidia      | MCP79 PCI Bridge             | 564   |
| pci:8086-3e30 | Intel       | 8th/9th Gen Core 8-core D... | 563   |
| pci:8086-1c4b | Intel       | HM67 Express Chipset LPC ... | 562   |
| pci:8086-a11c | Intel       | 100 Series/C230 Series Ch... | 560   |
| pci:1002-5957 | AMD         | RX780/RX790 Host Bridge      | 558   |
| pci:8086-9cc5 | Intel       | Wildcat Point-LP LPC Cont... | 557   |
| pci:8086-31d7 | Intel       | Gemini Lake PCI Express R... | 556   |
| pci:8086-1905 | Intel       | Xeon E3-1200 v5/E3-1500 v... | 554   |
| pci:8086-3a14 | Intel       | 82801JDO (ICH10DO) LPC In... | 553   |
| pci:8086-8c96 | Intel       | 9 Series Chipset Family P... | 550   |
| pci:8086-0041 | Intel       | Core Processor PCI Expres... | 549   |
| pci:8086-2c01 | Intel       | Xeon 5500/Core i7 QuickPa... | 548   |
| pci:8086-2c10 | Intel       | Xeon 5500/Core i7 QPI Link 0 | 548   |
| pci:8086-2c11 | Intel       | Xeon 5500/Core i7 QPI Phy... | 548   |
| pci:8086-2c18 | Intel       | Xeon 5500/Core i7 Integra... | 548   |
| pci:8086-2c19 | Intel       | Xeon 5500/Core i7 Integra... | 548   |
| pci:8086-2c1c | Intel       | Xeon 5500/Core i7 Integra... | 548   |
| pci:8086-2c20 | Intel       | Xeon 5500/Core i7 Integra... | 548   |
| pci:8086-2c21 | Intel       | Xeon 5500/Core i7 Integra... | 548   |
| pci:8086-2c22 | Intel       | Xeon 5500/Core i7 Integra... | 548   |
| pci:8086-2c23 | Intel       | Xeon 5500/Core i7 Integra... | 548   |
| pci:8086-2c28 | Intel       | Xeon 5500/Core i7 Integra... | 548   |
| pci:8086-2c29 | Intel       | Xeon 5500/Core i7 Integra... | 548   |
| pci:8086-2c2a | Intel       | Xeon 5500/Core i7 Integra... | 548   |
| pci:8086-2c2b | Intel       | Xeon 5500/Core i7 Integra... | 548   |
| pci:8086-2c30 | Intel       | Xeon 5500/Core i7 Integra... | 548   |
| pci:8086-2c31 | Intel       | Xeon 5500/Core i7 Integra... | 548   |
| pci:8086-2c32 | Intel       | Xeon 5500/Core i7 Integra... | 548   |
| pci:8086-2c33 | Intel       | Xeon 5500/Core i7 Integra... | 548   |
| pci:8086-34b4 | Intel       | Ice Lake-LP PCIe Port #13    | 548   |
| pci:8086-06b8 | Intel       | 400 Series Chipset Family... | 547   |
| pci:8086-a292 | Intel       | 200 Series PCH PCI Expres... | 544   |
| pci:8086-3c00 | Intel       | Xeon E5/Core i7 DMI2         | 542   |
| pci:8086-1c4a | Intel       | H67 Express Chipset LPC C... | 539   |
| pci:8086-3c08 | Intel       | Xeon E5/Core i7 IIO PCI E... | 539   |
| pci:10de-0ac6 | Nvidia      | MCP79 PCI Express Bridge     | 537   |
| pci:8086-3b06 | Intel       | H55 Chipset LPC Interface... | 535   |
| pci:8086-190f | Intel       | Xeon E3-1200 v5/E3-1500 v... | 529   |
| pci:8086-3c02 | Intel       | Xeon E5/Core i7 IIO PCI E... | 529   |
| pci:8086-9d16 | Intel       | Sunrise Point-LP PCI Expr... | 529   |
| pci:8086-5ad8 | Intel       | Celeron N3350/Pentium N42... | 527   |
| pci:8086-9b54 | Intel       | 10th Gen Core Processor H... | 524   |
| pci:8086-31da | Intel       | Gemini Lake PCI Express R... | 522   |
| pci:8086-31d6 | Intel       | Gemini Lake PCI Express R... | 520   |
| pci:1022-9608 | AMD         | RS780/RS880 PCI to PCI br... | 517   |
| pci:8086-9c45 | Intel       | 8 Series LPC Controller      | 516   |
| pci:8086-9a27 | Intel       | Tiger Lake-LP Thunderbolt... | 514   |
| pci:8086-2f00 | Intel       | Xeon E7 v3/Xeon E5 v3/Cor... | 511   |
| pci:8086-3a42 | Intel       | 82801JI (ICH10 Family) PC... | 511   |
| pci:8086-3c04 | Intel       | Xeon E5/Core i7 IIO PCI E... | 510   |
| pci:8086-2f08 | Intel       | Xeon E7 v3/Xeon E5 v3/Cor... | 508   |
| pci:8086-1513 | Intel       | CV82524 Thunderbolt Contr... | 500   |
| pci:8086-2918 | Intel       | 82801IB (ICH9) LPC Interf... | 499   |
| pci:8086-2f02 | Intel       | Xeon E7 v3/Xeon E5 v3/Cor... | 499   |
| pci:8086-1c44 | Intel       | Z68 Express Chipset LPC C... | 498   |
| pci:8086-a33d | Intel       | Cannon Lake PCH PCI Expre... | 498   |
| pci:8086-9a25 | Intel       | Tiger Lake-LP Thunderbolt... | 492   |
| pci:1022-1415 | AMD         | Family 15h (Models 10h-1f... | 490   |
| pci:8086-a334 | Intel       | Cannon Lake PCH PCI Expre... | 490   |
| pci:8086-1d14 | Intel       | C600/X79 series chipset P... | 487   |
| pci:10de-0ac7 | Nvidia      | MCP79 PCI Express Bridge     | 480   |
| pci:8086-a308 | Intel       | 300 Series Chipset Family... | 479   |
| pci:8086-3a44 | Intel       | 82801JI (ICH10 Family) PC... | 476   |
| pci:1022-43b0 | AMD         | X370 Series Chipset PCIe ... | 475   |
| pci:10de-0aa0 | Nvidia      | MCP79 PCI Express Bridge     | 461   |
| pci:8086-3b02 | Intel       | P55 Chipset LPC Interface... | 458   |
| pci:1022-1426 | AMD         | Family 15h (Models 30h-3f... | 456   |
| pci:8086-590f | Intel       | Xeon E3-1200 v6/7th Gen C... | 449   |
| pci:8086-2e11 | Intel       | 4 Series Chipset PCI Expr... | 447   |
| pci:8086-2c41 | Intel       | Xeon 5500/Core i7 QuickPa... | 444   |
| pci:1002-597f | AMD         | RD790 PCI to PCI bridge (... | 441   |
| pci:8086-22ca | Intel       | Atom/Celeron/Pentium Proc... | 440   |
| pci:8086-a295 | Intel       | 200 Series PCH PCI Expres... | 437   |
| pci:1022-1707 | AMD         | Family 12h Processor Root... | 436   |
| pci:8086-8c94 | Intel       | 9 Series Chipset Family P... | 436   |
| pci:10de-0aae | Nvidia      | MCP79 LPC Bridge             | 432   |
| pci:8086-1d18 | Intel       | C600/X79 series chipset P... | 430   |
| pci:8086-2d81 | Intel       | Xeon 5600 Series QuickPat... | 430   |
| pci:8086-2d90 | Intel       | Xeon 5600 Series QPI Link 0  | 430   |
| pci:8086-2d91 | Intel       | Xeon 5600 Series QPI Phys... | 430   |
| pci:8086-2d92 | Intel       | Xeon 5600 Series Mirror P... | 430   |
| pci:8086-2d93 | Intel       | Xeon 5600 Series Mirror P... | 430   |
| pci:8086-2d98 | Intel       | Xeon 5600 Series Integrat... | 430   |
| pci:8086-2d99 | Intel       | Xeon 5600 Series Integrat... | 430   |
| pci:8086-2d9c | Intel       | Xeon 5600 Series Integrat... | 430   |
| pci:8086-2da0 | Intel       | Xeon 5600 Series Integrat... | 430   |
| pci:8086-2da1 | Intel       | Xeon 5600 Series Integrat... | 430   |
| pci:8086-2da2 | Intel       | Xeon 5600 Series Integrat... | 430   |
| pci:8086-2da3 | Intel       | Xeon 5600 Series Integrat... | 430   |
| pci:8086-2da8 | Intel       | Xeon 5600 Series Integrat... | 430   |
| pci:8086-2da9 | Intel       | Xeon 5600 Series Integrat... | 430   |
| pci:8086-2daa | Intel       | Xeon 5600 Series Integrat... | 430   |
| pci:8086-2dab | Intel       | Xeon 5600 Series Integrat... | 430   |
| pci:8086-2db0 | Intel       | Xeon 5600 Series Integrat... | 430   |
| pci:8086-2db1 | Intel       | Xeon 5600 Series Integrat... | 430   |
| pci:8086-2db2 | Intel       | Xeon 5600 Series Integrat... | 430   |
| pci:8086-2db3 | Intel       | Xeon 5600 Series Integrat... | 430   |
| pci:8086-3b4e | Intel       | 5 Series/3400 Series Chip... | 430   |
| pci:8086-3b50 | Intel       | 5 Series/3400 Series Chip... | 429   |
| pci:8086-1c4e | Intel       | Q67 Express Chipset LPC C... | 426   |
| pci:8086-3a72 | Intel       | 82801JD/DO (ICH10 Family)... | 424   |
| pci:8086-27ac | Intel       | Mobile 945GSE Express Mem... | 422   |
| pci:8086-9d11 | Intel       | Sunrise Point-LP PCI Expr... | 420   |
| pci:1002-5a1a | AMD         | RD890/RD9x0/RX980 PCI to ... | 419   |
| pci:8086-3a46 | Intel       | 82801JI (ICH10 Family) PC... | 415   |
| pci:8086-1578 | Intel       | DSL6540 Thunderbolt 3 Bri... | 413   |
| pci:8086-1d12 | Intel       | C600/X79 series chipset P... | 413   |
| pci:8086-06ac | Intel       | Comet Lake PCI Express Ro... | 411   |
| pci:8086-1e4a | Intel       | H77 Express Chipset LPC C... | 408   |
| pci:8086-a2c8 | Intel       | 200 Series PCH LPC Contro... | 408   |
| pci:8086-0105 | Intel       | Xeon E3-1200/2nd Generati... | 406   |
| pci:8086-31db | Intel       | Gemini Lake PCI Express R... | 406   |
| pci:8086-3e1f | Intel       | 8th Gen Core 4-core Deskt... | 403   |
| pci:8086-8d18 | Intel       | C610/X99 series chipset P... | 399   |
| pci:8086-2810 | Intel       | 82801HB/HR (ICH8/R) LPC I... | 397   |
| pci:8086-a2e9 | Intel       | 200 Series PCH PCI Expres... | 395   |
| pci:8086-8d44 | Intel       | C610/X99 series chipset L... | 394   |
| pci:10de-0a82 | Nvidia      | MCP79 Host Bridge            | 390   |
| pci:8086-a2c5 | Intel       | 200 Series PCH LPC Contro... | 389   |
| pci:1022-170a | AMD         | Family 12h Processor Root... | 386   |
| pci:8086-2c70 | Intel       | Xeon 5600 Series QuickPat... | 386   |
| pci:8086-27a1 | Intel       | Mobile 945GM/PM/GMS, 943/... | 384   |
| pci:8086-3410 | Intel       | 7500/5520/5500/X58 I/O Hu... | 383   |
| pci:8086-3b0b | Intel       | HM57 Chipset LPC Interfac... | 383   |
| pci:8086-1d16 | Intel       | C600/X79 series chipset P... | 378   |
| pci:1039-0671 | Silicon ... | 671MX                        | 376   |
| pci:1039-0968 | Silicon ... | SiS968 [MuTIOL Media IO]     | 376   |
| pci:8086-2660 | Intel       | 82801FB/FBM/FR/FW/FRW (IC... | 376   |
| pci:1002-5a3f | AMD         | RC4xx/RS4xx PCI Bridge [i... | 375   |
| pci:1b21-1184 | ASMedia ... | ASM1184e 4-Port PCIe x1 G... | 368   |
| pci:8086-5ad7 | Intel       | Celeron N3350/Pentium N42... | 364   |
| pci:8086-3406 | Intel       | 5520 I/O Hub to ESI Port     | 363   |
| pci:8086-a119 | Intel       | 100 Series/C230 Series Ch... | 363   |
| pci:8086-a33f | Intel       | Cannon Lake PCH PCI Expre... | 362   |
| pci:8086-06b6 | Intel       | 400 Series Chipset Family... | 361   |
| pci:1283-8893 | Integrat... | IT8893E PCIe to PCI Bridge   | 360   |
| pci:1a03-1150 | ASPEED T... | AST1150 PCI-to-PCI Bridge    | 359   |
| pci:8086-2d94 | Intel       | Xeon 5600 Series QPI Link 1  | 358   |
| pci:8086-2d95 | Intel       | Xeon 5600 Series QPI Phys... | 358   |
| pci:8086-2d9a | Intel       | Xeon 5600 Series Integrat... | 358   |
| pci:8086-5ada | Intel       | Celeron N3350/Pentium N42... | 358   |
| pci:1043-9602 | ASUSTek ... | AMD RS780/RS880 PCI to PC... | 357   |
| pci:8086-02b8 | Intel       | Comet Lake PCI Express Ro... | 357   |
| pci:1039-000a | Silicon ... | PCI-to-PCI bridge            | 356   |
| pci:8086-2f04 | Intel       | Xeon E7 v3/Xeon E5 v3/Cor... | 355   |
| pci:10de-075a | Nvidia      | MCP78S [GeForce 8200] PCI... | 348   |
| pci:8086-0e00 | Intel       | Xeon E7 v2/Xeon E5 v2/Cor... | 348   |
| pci:8086-0e08 | Intel       | Xeon E7 v2/Xeon E5 v2/Cor... | 346   |
| pci:8086-0e02 | Intel       | Xeon E7 v2/Xeon E5 v2/Cor... | 342   |
| pci:8086-1c46 | Intel       | P67 Express Chipset LPC C... | 340   |
| pci:8086-9b53 | Intel       | Comet Lake-S 6c Host Brid... | 340   |
| pci:8086-068e | Intel       | CM256 Chipset LPC Control... | 339   |
| pci:8086-1c4c | Intel       | Q65 Express Chipset LPC C... | 337   |
| pci:8086-0e04 | Intel       | Xeon E7 v2/Xeon E5 v2/Cor... | 336   |
| pci:8086-a29a | Intel       | 200 Series PCH PCI Expres... | 336   |
| pci:8086-a337 | Intel       | Cannon Lake PCH PCI Expre... | 336   |
| pci:1039-0003 | Silicon ... | AGP Port (virtual PCI-to-... | 332   |
| pci:8086-5ad9 | Intel       | Celeron N3350/Pentium N42... | 326   |
| pci:8086-02b1 | Intel       | Comet Lake PCI Express Ro... | 325   |
| pci:8086-1d1e | Intel       | C600/X79 series chipset P... | 323   |
| pci:8086-29b0 | Intel       | 82Q35 Express DRAM Contro... | 322   |
| pci:8086-2914 | Intel       | 82801IO (ICH9DO) LPC Inte... | 320   |
| pci:8086-29a0 | Intel       | 82P965/G965 Memory Contro... | 317   |
| pci:8086-a33e | Intel       | Cannon Lake PCH PCI Expre... | 317   |
| pci:8086-2020 | Intel       | Sky Lake-E DMI3 Registers    | 315   |
| pci:1022-1300 | AMD         | Family 11h Processor Hype... | 314   |
| pci:1022-1301 | AMD         | Family 11h Processor Addr... | 314   |
| pci:1022-1302 | AMD         | Family 11h Processor DRAM... | 314   |
| pci:1022-1303 | AMD         | Family 11h Processor Misc... | 314   |
| pci:1022-1304 | AMD         | Family 11h Processor Link... | 314   |
| pci:8086-8c4a | Intel       | H87 Express LPC Controller   | 314   |
| pci:1022-1425 | AMD         | Kaveri P2P Bridge for GFX... | 313   |
| pci:8086-2c52 | Intel       | Core Processor QuickPath ... | 313   |
| pci:8086-d132 | Intel       | Core Processor DMI           | 313   |
| pci:104c-8240 | Texas In... | XIO2001 PCI Express-to-PC... | 312   |
| pci:8086-43bc | Intel       | Tiger Lake-H PCI Express ... | 312   |
| pci:1002-7910 | AMD         | RS690 Host Bridge            | 310   |
| pci:8086-a2ca | Intel       | 200 Series Chipset Family... | 310   |
| pci:8086-156d | Intel       | DSL5520 Thunderbolt 2 Bri... | 308   |
| pci:8086-1e5d | Intel       | HM75 Express Chipset LPC ... | 308   |
| pci:8086-a293 | Intel       | 200 Series PCH PCI Expres... | 305   |
| pci:10de-077a | Nvidia      | MCP78S [GeForce 8200] PCI... | 304   |
| pci:8086-2f03 | Intel       | Xeon E7 v3/Xeon E5 v3/Cor... | 304   |
| pci:1002-5a1f | AMD         | RD890/RD990 PCI to PCI br... | 303   |
| pci:8086-2030 | Intel       | Sky Lake-E PCI Express Ro... | 302   |
| pci:8086-2811 | Intel       | 82801HEM (ICH8M-E) LPC In... | 301   |
| pci:8086-a0b8 | Intel       | PCI bridge                   | 300   |
| pci:104c-823e | Texas In... | XIO2213A/B/XIO2221 PCI Ex... | 298   |
| pci:10de-0ac4 | Nvidia      | MCP79 PCI Express Bridge     | 298   |
| pci:1106-b198 | VIA Tech... | VT8237/CX700/VX700-Series... | 297   |
| pci:8086-24d0 | Intel       | 82801EB/ER (ICH5/ICH5R) L... | 297   |
| pci:8086-3c03 | Intel       | Xeon E5/Core i7 IIO PCI E... | 293   |
| pci:1022-1470 | AMD         | Vega 10 PCIe Bridge          | 292   |
| pci:1022-1471 | AMD         | Vega 10 PCIe Bridge          | 292   |
| pci:10de-026f | Nvidia      | MCP51 PCI Bridge             | 292   |
| pci:8086-29a1 | Intel       | 82P965/G965 PCI Express R... | 290   |
| pci:1039-0004 | Silicon ... | PCI-to-PCI bridge            | 288   |
| pci:1002-5950 | AMD         | RS480/RS482/RS485 Host Br... | 284   |
| pci:8086-0c05 | Intel       | Xeon E3-1200 v3/4th Gen C... | 283   |
| pci:8086-3409 | Intel       | 5520/5500/X58 I/O Hub PCI... | 282   |
| pci:8086-8cc6 | Intel       | H97 Chipset LPC Controller   | 282   |
| pci:8086-8d16 | Intel       | C610/X99 series chipset P... | 279   |
| pci:8086-9d17 | Intel       | Sunrise Point-LP PCI Expr... | 278   |
| pci:8086-a169 | Intel       | 100 Series/C230 Series Ch... | 278   |
| pci:8086-8d47 | Intel       | C610/X99 series chipset L... | 275   |
| pci:1002-5a1e | AMD         | RD890/RD9x0/RX980 PCI to ... | 274   |
| pci:8086-a148 | Intel       | B150 Chipset LPC/eSPI Con... | 273   |
| pci:8086-06bc | Intel       | 400 Series Chipset Family... | 271   |
| pci:10de-0778 | Nvidia      | MCP78S [GeForce 8200] PCI... | 270   |
| pci:1217-7135 | O2 Micro    | Cardbus bridge               | 270   |
| pci:8086-06b5 | Intel       | 400 Series Chipset Family... | 268   |
| pci:8086-2570 | Intel       | 82865G/PE/P DRAM Controll... | 268   |
| pci:8086-2590 | Intel       | Mobile 915GM/PM/GMS/910GM... | 267   |
| pci:8086-2641 | Intel       | 82801FBM (ICH6M) LPC Inte... | 267   |
| pci:1022-1417 | AMD         | Family 15h (Models 10h-1f... | 263   |
| pci:1022-1513 | AMD         | Family 14h Processor Root... | 262   |
| pci:1022-43a3 | AMD         | Hudson PCI to PCI bridge ... | 260   |
| pci:8086-43b0 | Intel       | Tiger Lake-H PCI Express ... | 260   |
| pci:1002-4371 | AMD         | IXP SB4x0 PCI-PCI Bridge     | 259   |
| pci:1002-4377 | AMD         | IXP SB4x0 PCI-ISA Bridge     | 259   |
| pci:8086-8a1d | Intel       | Ice Lake Thunderbolt 3 PC... | 257   |
| pci:1022-170b | AMD         | Family 12h Processor Root... | 255   |
| pci:8086-3b08 | Intel       | H57 Chipset LPC Interface... | 254   |
| pci:8086-9b44 | Intel       | 10th Gen Core Processor H... | 254   |
| pci:8086-a11e | Intel       | 100 Series/C230 Series Ch... | 254   |
| pci:10de-0260 | Nvidia      | MCP51 LPC Bridge             | 252   |
| pci:1002-5a37 | AMD         | RC4xx/RS4xx PCI Express P... | 250   |
| pci:1106-287e | VIA Tech... | VT8237/8251 Ultra VLINK C... | 250   |
| pci:8086-a150 | Intel       | CM236 Chipset LPC/eSPI Co... | 249   |
| pci:8086-1909 | Intel       | Xeon E3-1200 v5/E3-1500 v... | 248   |
| pci:8086-a3c8 | Intel       | B460 Chipset LPC/eSPI Con... | 247   |
| pci:8086-1547 | Intel       | DSL3510 Thunderbolt Contr... | 246   |
| pci:1002-7912 | AMD         | RS690/RS740 PCI to PCI Br... | 245   |
| pci:8086-2640 | Intel       | 82801FB/FR (ICH6/ICH6R) L... | 244   |
| pci:8086-0685 | Intel       | Z490 Chipset LPC Controll... | 243   |
| pci:1022-145d | AMD         | Zeppelin Switch Upstream ... | 241   |
| pci:8086-3a1a | Intel       | 82801JD (ICH10D) LPC Inte... | 241   |
| pci:8086-1e5f | Intel       | NM70 Express Chipset LPC ... | 240   |
| pci:8086-34b1 | Intel       | Ice Lake-LP PCIe Port #10    | 240   |
| pci:8086-a304 | Intel       | H370 Chipset LPC/eSPI Con... | 238   |
| pci:8086-9d19 | Intel       | Sunrise Point-LP PCI Expr... | 237   |
| pci:1002-597e | AMD         | RD790 PCI to PCI bridge (... | 236   |
| pci:8086-2990 | Intel       | 82Q963/Q965 Memory Contro... | 236   |
| pci:8086-a16a | Intel       | 100 Series/C230 Series Ch... | 236   |
| pci:1002-7916 | AMD         | RS690 PCI to PCI Bridge (... | 235   |
| pci:1106-337b | VIA Tech... | VT8237A Host Bridge          | 235   |
| pci:8086-8c98 | Intel       | 9 Series Chipset Family P... | 235   |
| pci:1180-e476 | Ricoh       | CardBus bridge               | 234   |
| pci:8086-3e35 | Intel       | Coffee Lake Host Bridge/D... | 234   |
| pci:10de-075b | Nvidia      | MCP78S [GeForce 8200] PCI... | 233   |
| pci:10de-075c | Nvidia      | MCP78S [GeForce 8200] LPC... | 233   |
| pci:8086-1d1a | Intel       | C600/X79 series chipset P... | 233   |
| pci:8086-5ad6 | Intel       | Celeron N3350/Pentium N42... | 233   |
| pci:8086-a144 | Intel       | H170 Chipset LPC/eSPI Con... | 233   |
| pci:8086-a0be | Intel       | PCI bridge                   | 229   |
| pci:10de-0370 | Nvidia      | MCP55 PCI bridge             | 225   |
| pci:8086-31d9 | Intel       | Gemini Lake PCI Express R... | 225   |
| pci:8086-5adb | Intel       | Celeron N3350/Pentium N42... | 224   |
| pci:8086-156b | Intel       | DSL5320 Thunderbolt 2 Bri... | 223   |
| pci:8086-0155 | Intel       | Xeon E3-1200 v2/3rd Gen C... | 221   |
| pci:8086-9db6 | Intel       | Cannon Point-LP PCI Expre... | 220   |
| pci:8086-2580 | Intel       | 82915G/P/GV/GL/PL/910GL M... | 219   |
| pci:8086-9b43 | Intel       | Comet Lake-S 8c Host Brid... | 219   |
| pci:8086-a0b1 | Intel       | PCI bridge                   | 219   |
| pci:8086-8c9c | Intel       | 9 Series Chipset Family P... | 218   |
| pci:8086-2670 | Intel       | 631xESB/632xESB/3100 Chip... | 217   |
| pci:8086-3500 | Intel       | 6311ESB/6321ESB PCI Expre... | 215   |
| pci:8086-350c | Intel       | 6311ESB/6321ESB PCI Expre... | 215   |
| pci:8086-3510 | Intel       | 6311ESB/6321ESB PCI Expre... | 215   |
| pci:8086-a000 | Intel       | Atom Processor D4xx/D5xx/... | 212   |
| pci:8086-0bf1 | Intel       | Atom Processor D2xxx/N2xx... | 211   |
| pci:1002-597c | AMD         | RD790 PCI to PCI bridge (... | 209   |
| pci:8086-a2ea | Intel       | 200 Series PCH PCI Expres... | 208   |
| pci:8086-3b0a | Intel       | Q57 Chipset LPC Interface... | 207   |
| pci:8086-2690 | Intel       | 631xESB/632xESB/3100 Chip... | 203   |
| pci:8086-9dbf | Intel       | Cannon Point PCI Express ... | 203   |
| pci:10de-02fd | Nvidia      | C51 PCI Express Bridge       | 202   |
| pci:8086-2662 | Intel       | 82801FB/FBM/FR/FW/FRW (IC... | 202   |
| pci:8086-3a78 | Intel       | 82801JD/DO (ICH10 Family)... | 202   |
| pci:8086-6f00 | Intel       | Xeon E7 v4/Xeon E5 v4/Xeo... | 202   |
| pci:8086-6f08 | Intel       | Xeon E7 v4/Xeon E5 v4/Xeo... | 202   |
| pci:8086-29b1 | Intel       | 82Q35 Express PCI Express... | 198   |
| pci:8086-9a01 | Intel       | 11th Gen Core Processor P... | 198   |
| pci:8086-8a02 | Intel       | Ice Lake-U Host Bridge/DR... | 197   |
| pci:8086-8d14 | Intel       | C610/X99 series chipset P... | 197   |
| pci:8086-9a36 | Intel       | 11th Gen Core Processor H... | 197   |
| pci:1002-7917 | AMD         | RS690 PCI to PCI Bridge (... | 196   |
| pci:10de-005c | Nvidia      | CK804 PCI Bridge             | 195   |
| pci:10de-005d | Nvidia      | CK804 PCIE Bridge            | 195   |
| pci:8086-0c08 | Intel       | Xeon E3-1200 v3 Processor... | 195   |
| pci:8086-15ef | Intel       | JHL7540 Thunderbolt 3 Bri... | 194   |
| pci:8086-2571 | Intel       | 82865G/PE/P AGP Bridge       | 194   |
| pci:8086-6f02 | Intel       | Xeon E7 v4/Xeon E5 v4/Xeo... | 194   |
| pci:8086-3514 | Intel       | 6311ESB/6321ESB PCI Expre... | 192   |
| pci:8086-a11a | Intel       | 100 Series/C230 Series Ch... | 189   |
| pci:8086-a154 | Intel       | CM238 Chipset LPC/eSPI Co... | 189   |
| pci:10b5-8608 | PLX Tech... | PEX 8608 8-lane, 8-Port P... | 188   |
| pci:1002-7913 | AMD         | RS690 PCI to PCI Bridge (... | 187   |
| pci:10de-02fb | Nvidia      | C51 PCI Express Bridge       | 187   |
| pci:1106-3337 | VIA Tech... | VT8237A PCI to ISA Bridge    | 187   |
| pci:8086-590c | Intel       | Xeon E3-1200 v6/7th Gen C... | 187   |
| pci:8086-06be | Intel       | 400 Series Chipset Family... | 186   |
| pci:8086-340c | Intel       | 5520/X58 I/O Hub PCI Expr... | 186   |
| pci:1022-43b1 | AMD         | X399 Series Chipset PCIe ... | 185   |
| pci:8086-0e03 | Intel       | Xeon E7 v2/Xeon E5 v2/Cor... | 184   |
| pci:10de-0050 | Nvidia      | CK804 ISA Bridge             | 182   |
| pci:8086-a394 | Intel       | Comet Lake PCI Express Ro... | 182   |
| pci:1002-5a38 | AMD         | RC4xx/RS4xx PCI Express P... | 181   |
| pci:10de-0377 | Nvidia      | MCP55 PCI Express bridge     | 179   |
| pci:10de-02fc | Nvidia      | C51 PCI Express Bridge       | 178   |
| pci:8086-1576 | Intel       | DSL6340 Thunderbolt 3 Bri... | 178   |
| pci:8086-a146 | Intel       | Q170 Chipset LPC/eSPI Con... | 178   |
| pci:1106-337a | VIA Tech... | VT8237A PCI to PCI Bridge    | 177   |
| pci:8086-3b03 | Intel       | PM55 Chipset LPC Interfac... | 175   |
| pci:8086-a0b3 | Intel       | PCI bridge                   | 175   |
| pci:8086-1e48 | Intel       | Q75 Express Chipset LPC C... | 174   |
| pci:8086-2032 | Intel       | Sky Lake-E PCI Express Ro... | 174   |
| pci:8086-8c4c | Intel       | Q85 Express LPC Controller   | 174   |
| pci:8086-a2cc | Intel       | 200 Series Chipset Family... | 173   |
| pci:8086-a33a | Intel       | Cannon Lake PCH PCI Expre... | 172   |
| pci:8086-a398 | Intel       | Comet Lake PCI Express Ro... | 172   |
| pci:8086-a0bf | Intel       | Tiger Lake-LP PCI Express... | 171   |
| pci:10b5-8112 | PLX Tech... | PEX8112 x1 Lane PCI Expre... | 170   |
| pci:10de-0548 | Nvidia      | MCP67 ISA Bridge             | 170   |
| pci:10de-0561 | Nvidia      | MCP67 PCI Bridge             | 170   |
| pci:8086-3e0f | Intel       | Coffee Lake Host Bridge/D... | 170   |
| pci:8086-9b71 | Intel       | Comet Lake-U v1 2c Host B... | 170   |
| pci:10de-0563 | Nvidia      | MCP67 PCI Express Bridge     | 169   |
| pci:1002-7915 | AMD         | RS690 PCI to PCI Bridge (... | 168   |
| pci:10de-0360 | Nvidia      | MCP55 LPC Bridge             | 168   |
| pci:8086-a303 | Intel       | H310 Chipset LPC/eSPI Con... | 168   |
| pci:1002-5a36 | AMD         | RC4xx/RS4xx PCI Express P... | 166   |
| pci:10de-0569 | Nvidia      | MCP78S [GeForce 8200] PCI... | 165   |
| pci:8086-9b51 | Intel       | Comet Lake-U v1 6c Host B... | 165   |
| pci:8086-34bc | Intel       | Ice Lake-LP PCI Express R... | 164   |
| pci:8086-9d4b | Intel       | Skylake-U/Y LPC/eSPI Cont... | 163   |
| pci:8086-06bd | Intel       | Comet Lake PCIe Port #6      | 161   |
| pci:1524-1412 | ENE Tech... | CB-712/4 Cardbus Controller  | 160   |
| pci:8086-a11b | Intel       | 100 Series/C230 Series Ch... | 160   |
| pci:8086-6f04 | Intel       | Xeon E7 v4/Xeon E5 v4/Xeo... | 158   |
| pci:8086-02be | Intel       | Comet Lake PCH-LP PCIe Po... | 157   |
| pci:8086-a343 | Intel       | Cannon Lake PCH PCI Expre... | 157   |
| pci:8086-06b4 | Intel       | 400 Series Chipset Family... | 156   |
| pci:8086-a149 | Intel       | C236 Chipset LPC/eSPI Con... | 156   |
| pci:8086-8c56 | Intel       | C226 Series Chipset Famil... | 155   |
| pci:8086-9b64 | Intel       | 10th Gen Core Processor H... | 155   |
| pci:8086-a190 | Intel       | C620 Series Chipset Famil... | 155   |
| pci:8086-a2c4 | Intel       | 200 Series PCH LPC Contro... | 154   |
| pci:8086-9b63 | Intel       | 10th Gen Core Processor H... | 152   |
| pci:8086-a291 | Intel       | 200 Series PCH PCI Expres... | 152   |
| pci:8086-29e0 | Intel       | 82X38/X48 Express DRAM Co... | 149   |
| pci:10de-056d | Nvidia      | MCP73 PCI Express bridge     | 148   |
| pci:10de-07d7 | Nvidia      | MCP73 LPC Bridge             | 148   |
| pci:8086-9db2 | Intel       | Cannon Point-LP PCI Expre... | 148   |
| pci:8086-a332 | Intel       | Cannon Lake PCH PCI Expre... | 148   |
| pci:8086-8d1e | Intel       | C610/X99 series chipset P... | 147   |
| pci:8086-a306 | Intel       | Q370 Chipset LPC/eSPI Con... | 146   |
| pci:104c-8031 | Texas In... | PCIxx21/PCIxx11/PCIx515 P... | 142   |
| pci:10de-056e | Nvidia      | MCP73 PCI Express bridge     | 142   |
| pci:8086-29e1 | Intel       | 82X38/X48 Express Host-Pr... | 142   |
| pci:1022-1490 | AMD         | Starship Device 24; Funct... | 141   |
| pci:1022-1491 | AMD         | Starship Device 24; Funct... | 141   |
| pci:1022-1492 | AMD         | Starship Device 24; Funct... | 141   |
| pci:1022-1493 | AMD         | Starship Device 24; Funct... | 141   |
| pci:1022-1494 | AMD         | Starship Device 24; Funct... | 141   |
| pci:1022-1495 | AMD         | Starship Device 24; Funct... | 141   |
| pci:1022-1496 | AMD         | Starship Device 24; Funct... | 141   |
| pci:1022-1497 | AMD         | Starship Device 24; Funct... | 141   |
| pci:8086-1e56 | Intel       | QS77 Express Chipset LPC ... | 140   |
| pci:10de-056f | Nvidia      | MCP73 PCI Express bridge     | 139   |
| pci:8086-190c | Intel       | Xeon E3-1200 v5/E3-1500 v... | 139   |
| pci:8086-9d46 | Intel       | LPC/eSPI Controller          | 139   |
| pci:1106-0364 | VIA Tech... | CN896/VN896/P4M900 Host B... | 138   |
| pci:1106-1364 | VIA Tech... | CN896/VN896/P4M900 Host B... | 138   |
| pci:1106-2364 | VIA Tech... | CN896/VN896/P4M900 Host B... | 138   |
| pci:1106-3227 | VIA Tech... | VT8237 ISA bridge [KT600/... | 138   |
| pci:1106-3364 | VIA Tech... | CN896/VN896/P4M900 Host B... | 138   |
| pci:1106-4364 | VIA Tech... | CN896/VN896/P4M900 Host B... | 138   |
| pci:1106-6364 | VIA Tech... | CN896/VN896/P4M900 Securi... | 138   |
| pci:1106-7364 | VIA Tech... | CN896/VN896/P4M900 Host B... | 138   |
| pci:8086-2581 | Intel       | 82915G/P/GV/GL/PL/910GL P... | 137   |
| pci:8086-3e20 | Intel       | Coffee Lake Host Bridge/D... | 136   |
| pci:8086-8d12 | Intel       | C610/X99 series chipset P... | 136   |
| pci:8086-9b33 | Intel       | Comet Lake-S 6c Host Brid... | 136   |
| pci:1106-a364 | VIA Tech... | CN896/VN896/P4M900 PCI to... | 134   |
| pci:8086-9a04 | Intel       | Host bridge                  | 134   |
| pci:103c-9602 | Hewlett-... | AMD RS780/RS880 PCI to PC... | 133   |
| pci:8086-9a0f | Intel       | 11th Gen Core Processor P... | 133   |
| pci:8086-a29b | Intel       | 200 Series PCH PCI Expres... | 133   |
| pci:8086-3ed0 | Intel       | 8th Gen Core Processor Ho... | 132   |
| pci:8086-9dbe | Intel       | Cannon Point-LP PCI Expre... | 132   |
| pci:8086-1c4d | Intel       | QS67 Express Chipset LPC ... | 131   |
| pci:1106-c364 | VIA Tech... | CN896/VN896/P4M900 PCI to... | 130   |
| pci:8086-43be | Intel       | 500 Series Chipset Family... | 128   |
| pci:1002-7914 | AMD         | PCI standard PCI-to-PCI b... | 127   |
| pci:8086-4c01 | Intel       | Core i7/i5/i3 PCIe Contro... | 127   |
| pci:8086-0d04 | Intel       | Crystal Well DRAM Controller | 126   |
| pci:1002-597d | AMD         | RX780/RD790 PCI to PCI br... | 125   |
| pci:1002-5a34 | AMD         | RS4xx PCI Express Port [e... | 125   |
| pci:8086-438b | Intel       | Tiger Lake-H LPC/eSPI Con... | 123   |
| pci:8086-a0bb | Intel       | PCI bridge                   | 122   |
| pci:1002-5a39 | AMD         | RC4xx/RS4xx PCI Express P... | 121   |
| pci:8086-2033 | Intel       | Sky Lake-E PCI Express Ro... | 121   |
| pci:8086-27e0 | Intel       | 82801GR/GH/GHM (ICH7 Fami... | 121   |
| pci:8086-27e2 | Intel       | 82801GR/GH/GHM (ICH7 Fami... | 121   |
| pci:8086-4385 | Intel       | 500 Series Chipset Family... | 120   |
| pci:8086-9a2b | Intel       | Tiger Lake-H Thunderbolt ... | 120   |
| pci:8086-a3eb | Intel       | Comet Lake PCI Express Ro... | 120   |
| pci:8086-2991 | Intel       | 82Q963/Q965 PCI Express R... | 119   |
| pci:8086-a2d2 | Intel       | X299 Chipset LPC/eSPI Con... | 119   |
| pci:10de-0449 | Nvidia      | MCP65 PCI bridge             | 118   |
| pci:10de-0458 | Nvidia      | MCP65 PCI Express bridge     | 118   |
| pci:8086-25f0 | Intel       | 5000 Series Chipset FSB R... | 118   |
| pci:8086-25f1 | Intel       | 5000 Series Chipset Reser... | 118   |
| pci:8086-25f3 | Intel       | 5000 Series Chipset Reser... | 118   |
| pci:8086-25f5 | Intel       | 5000 Series Chipset FBD R... | 118   |
| pci:8086-25f6 | Intel       | 5000 Series Chipset FBD R... | 118   |
| pci:1002-5a31 | AMD         | RC410 Host Bridge            | 117   |
| pci:1022-1515 | AMD         | Family 14h Processor Root... | 116   |
| pci:10b5-8747 | PLX Tech... | PEX 8747 48-Lane, 5-Port ... | 116   |
| pci:10de-0d60 | Nvidia      | MCP89 HOST Bridge            | 116   |
| pci:10de-0d76 | Nvidia      | MCP89 PCI Express Bridge     | 116   |
| pci:10de-0d80 | Nvidia      | MCP89 LPC Bridge             | 116   |
| pci:10de-0d9b | Nvidia      | MCP89 PCIe Bridge            | 116   |
| pci:8086-1d1c | Intel       | C600/X79 series chipset P... | 116   |
| pci:8086-0d01 | Intel       | Crystal Well PCI Express ... | 115   |
| pci:8086-341c | Intel       | 7500/5520/5500/X58 Unknown   | 115   |
| pci:8086-341d | Intel       | 7500/5520/5500/X58 Unknown   | 115   |
| pci:8086-341e | Intel       | 7500/5520/5500/X58 Unknown   | 115   |
| pci:8086-0158 | Intel       | Xeon E3-1200 v2/Ivy Bridg... | 114   |
| pci:8086-06bf | Intel       | 400 Series Chipset Family... | 114   |
| pci:8086-2f0a | Intel       | Xeon E7 v3/Xeon E5 v3/Cor... | 114   |
| pci:8086-43c0 | Intel       | 500 Series Chipset Family... | 114   |
| pci:8086-3418 | Intel       | 7500/5520/5500/X58 Physic... | 113   |
| pci:8086-3419 | Intel       | 7500/5520/5500 Physical L... | 113   |
| pci:8086-341a | Intel       | 7500/5520/5500/X58 Unknown   | 113   |
| pci:8086-3439 | Intel       | 7500/5520/5500/X58 Unknown   | 113   |
| pci:8086-343a | Intel       | 7500/5520/5500/X58 Unknown   | 113   |
| pci:8086-343b | Intel       | 7500/5520/5500/X58 Unknown   | 113   |
| pci:8086-343c | Intel       | 7500/5520/5500/X58 Unknown   | 113   |
| pci:8086-343d | Intel       | 7500/5520/5500/X58 Unknown   | 113   |
| pci:1524-1410 | ENE Tech... | CB1410 Cardbus Controller    | 112   |
| pci:10de-0375 | Nvidia      | MCP55 PCI Express bridge     | 111   |
| pci:8086-25e3 | Intel       | 5000 Series Chipset PCI E... | 111   |
| pci:8086-43b8 | Intel       | 500 Series Chipset Family... | 111   |
| pci:8086-a0ba | Intel       | PCI bridge                   | 111   |
| pci:8086-0684 | Intel       | H470 Chipset LPC/eSPI Con... | 110   |
| pci:8086-2664 | Intel       | 82801FB/FBM/FR/FW/FRW (IC... | 110   |
| pci:8086-4c09 | Intel       | PCI bridge                   | 110   |
| pci:8086-a0bd | Intel       | Tigerlake PCH-LP PCI Expr... | 110   |
| pci:8086-a1c1 | Intel       | C621 Series Chipset LPC/e... | 109   |
| pci:8086-a392 | Intel       | Comet Lake PCH-V PCIe Por... | 109   |
| pci:8086-43c4 | Intel       | 500 Series Chipset Family... | 108   |
| pci:8086-a2c6 | Intel       | 200 Series PCH LPC Contro... | 108   |
| pci:8086-3518 | Intel       | 6311ESB/6321ESB PCI Expre... | 107   |
| pci:8086-9a29 | Intel       | Tiger Lake-LP Thunderbolt... | 107   |
| pci:8086-d130 | Intel       | Core Processor DMI           | 106   |
| pci:1022-1514 | AMD         | Family 14h Processor Root... | 105   |
| pci:8086-4c53 | Intel       | Host bridge                  | 105   |
| pci:8086-2c14 | Intel       | Xeon 5500/Core i7 QPI Link 1 | 104   |
| pci:8086-2c15 | Intel       | Xeon 5500/Core i7 QPI Phy... | 104   |
| pci:8086-2c1a | Intel       | Xeon 5500/Core i7 Integra... | 104   |
| pci:8086-2c40 | Intel       | Xeon 5500/Core i7 QuickPa... | 104   |
| pci:8086-341f | Intel       | 7500/5520/5500/X58 Unknown   | 104   |
| pci:8086-4387 | Intel       | 500 Series Chipset Family... | 104   |
| pci:1002-7911 | AMD         | RS690/RS740 Host Bridge      | 103   |
| pci:8086-2814 | Intel       | 82801HO (ICH8DO) LPC Inte... | 103   |
| pci:8086-a3e9 | Intel       | Comet Lake PCH-V PCIe Por... | 103   |
| pci:8086-06b7 | Intel       | 400 Series Chipset Family... | 102   |
| pci:8086-25e5 | Intel       | 5000 Series Chipset PCI E... | 102   |
| pci:8086-4c43 | Intel       | Rocket Lake-S Host Bridge... | 102   |
| pci:8086-a342 | Intel       | Cannon Lake PCH PCI Expre... | 102   |
| pci:8086-1918 | Intel       | Xeon E3-1200 v5/E3-1500 v... | 101   |
| pci:8086-8a21 | Intel       | Ice Lake Thunderbolt 3 PC... | 101   |
| pci:10de-0378 | Nvidia      | MCP55 PCI Express bridge     | 99    |
| pci:8086-8a1f | Intel       | Ice Lake Thunderbolt 3 PC... | 99    |
| pci:104c-ac56 | Texas In... | PCI1510 PC card Cardbus C... | 98    |
| pci:1849-9602 | ASRock I... | RS780 PCI to PCI Bridge (... | 98    |
| pci:8086-9db3 | Intel       | 300 Series Chipset PCIe P... | 98    |
| pci:10de-045a | Nvidia      | MCP65 PCI Express bridge     | 97    |
| pci:8086-25e7 | Intel       | 5000 Series Chipset PCI E... | 97    |
| pci:8086-3411 | Intel       | 7500/5520/5500/X58 I/O Hu... | 97    |
| pci:1002-597a | AMD         | RD790 PCI to PCI bridge (... | 96    |
| pci:10de-0441 | Nvidia      | MCP65 LPC Bridge             | 96    |
| pci:10de-0459 | Nvidia      | MCP65 PCI Express bridge     | 96    |
| pci:8086-4021 | Intel       | 5400 Chipset PCI Express ... | 96    |
| pci:8086-4025 | Intel       | 5400 Chipset PCI Express ... | 96    |
| pci:8086-4030 | Intel       | 5400 Chipset FSB Registers   | 96    |
| pci:8086-4031 | Intel       | 5400 Chipset CE/SF Registers | 96    |
| pci:8086-4035 | Intel       | 5400 Chipset FBD Registers   | 96    |
| pci:8086-4036 | Intel       | 5400 Chipset FBD Registers   | 96    |
| pci:10de-045b | Nvidia      | MCP65 PCI Express bridge     | 95    |
| pci:8086-4029 | Intel       | 5400 Chipset PCI Express ... | 95    |
| pci:8086-4388 | Intel       | 500 Series Chipset Family... | 95    |
| pci:8086-0108 | Intel       | Xeon E3-1200 Processor Fa... | 94    |
| pci:8086-4389 | Intel       | 500 Series Chipset Family... | 94    |
| pci:8086-8c9e | Intel       | 9 Series Chipset Family P... | 94    |
| pci:8086-d13a | Intel       | Core Processor PCI Expres... | 94    |
| pci:10de-03b7 | Nvidia      | C55 PCI Express bridge       | 93    |
| pci:8086-2970 | Intel       | 82946GZ/PL/GL Memory Cont... | 93    |
| pci:8086-2c50 | Intel       | Core Processor QuickPath ... | 93    |
| pci:8086-2c9a | Intel       | Core Processor Integrated... | 93    |
| pci:8086-02bf | Intel       | Comet Lake PCH-LP PCIe Po... | 92    |
| pci:8086-8d1c | Intel       | C610/X99 series chipset P... | 92    |
| pci:1106-b188 | VIA Tech... | VT8237/8251 PCI bridge [K... | 91    |
| pci:8086-02b5 | Intel       | Comet Lake PCH-LP PCIe Po... | 91    |
| pci:1022-960b | AMD         | RS780 PCI to PCI bridge (... | 90    |
| pci:10de-0562 | Nvidia      | MCP67 PCI Express Bridge     | 90    |
| pci:8086-6f03 | Intel       | Xeon E7 v4/Xeon E5 v4/Xeo... | 90    |
| pci:10de-07c1 | Nvidia      | MCP73 Host Bridge            | 89    |
| pci:8086-3c0a | Intel       | Xeon E5/Core i7 IIO PCI E... | 89    |
| pci:8086-2692 | Intel       | 631xESB/632xESB/3100 Chip... | 88    |
| pci:8086-27b0 | Intel       | 82801GH (ICH7DH) LPC Inte... | 88    |
| pci:1022-1416 | AMD         | Family 15h (Models 10h-1f... | 87    |
| pci:1022-1708 | AMD         | Family 12h Processor Root... | 87    |
| pci:8086-2591 | Intel       | Mobile 915GM/PM Express P... | 87    |
| pci:10de-0376 | Nvidia      | MCP55 PCI Express bridge     | 86    |
| pci:8086-29e9 | Intel       | 82X38/X48 Express Host-Se... | 86    |
| pci:8086-a194 | Intel       | C620 Series Chipset Famil... | 86    |
| pci:8086-a309 | Intel       | Cannon Point-LP LPC Contr... | 86    |
| pci:1b21-1187 | ASMedia ... | ASM1187e PCIe Switch         | 85    |
| pci:8086-34b8 | Intel       | Ice Lake-LP PCIe Port #1     | 85    |
| pci:8086-a3da | Intel       | H410 Chipset LPC/eSPI Con... | 84    |
| pci:10de-0374 | Nvidia      | MCP55 PCI Express bridge     | 83    |
| pci:1912-0012 | Renesas ... | SH7757 PCIe-PCI Bridge [PPB] | 83    |
| pci:1912-0013 | Renesas ... | SH7757 PCIe Switch [PS]      | 83    |
| pci:8086-4003 | Intel       | 5400 Chipset Memory Contr... | 83    |
| pci:8086-340b | Intel       | 5520/X58 I/O Hub PCI Expr... | 82    |
| pci:1002-5958 | AMD         | RD780 Host Bridge            | 81    |
| pci:8086-34b7 | Intel       | Ice Lake-LP PCI Express R... | 81    |
| pci:8086-37c0 | Intel       | PCI bridge                   | 81    |
| pci:8086-9cc7 | Intel       | Wildcat Point-LP LPC Cont... | 81    |
| pci:8086-a397 | Intel       | Comet Lake PCI Express Ro... | 81    |
| pci:10de-075e | Nvidia      | MCP78S [GeForce 8200] LPC... | 80    |
| pci:8086-3403 | Intel       | 5500 I/O Hub to ESI Port     | 80    |
| pci:8086-3c01 | Intel       | Xeon E5/Core i7 DMI2 in P... | 80    |
| pci:8086-43bf | Intel       | 500 Series Chipset Family... | 80    |
| pci:8086-340f | Intel       | 5520/5500/X58 I/O Hub PCI... | 79    |
| pci:8086-9d50 | Intel       | Sunrise Point LPC Controller | 79    |
| pci:8086-0d05 | Intel       | Crystal Well PCI Express ... | 78    |
| pci:8086-340d | Intel       | 5520/X58 I/O Hub PCI Expr... | 77    |
| pci:10de-0aac | Nvidia      | MCP79 LPC Bridge             | 76    |
| pci:1002-597b | AMD         | RX780/RD790 PCI to PCI br... | 75    |
| pci:8086-2031 | Intel       | Sky Lake-E PCI Express Ro... | 75    |
| pci:8086-2a10 | Intel       | Mobile GME965/GLE960 Memo... | 75    |
| pci:8086-3b0f | Intel       | QS57 Chipset LPC Interfac... | 73    |
| pci:8086-9d85 | Intel       | 300 Series Chipset LPC Co... | 73    |
| pci:1106-3208 | VIA Tech... | PT890 Host Bridge            | 72    |
| pci:8086-8c9a | Intel       | 9 Series Chipset Family P... | 72    |
| pci:8086-9dba | Intel       | 300 Series Chipset PCIe P... | 72    |
| pci:1102-7006 | Creative... | [SB X-Fi Xtreme Audio] CA... | 71    |
| pci:1217-6972 | O2 Micro    | OZ601/6912/711E0 CardBus/... | 71    |
| pci:8086-2971 | Intel       | 82946GZ/PL/GL PCI Express... | 71    |
| pci:8086-34bf | Intel       | Ice Lake-LP PCIe Port #8     | 71    |
| pci:8086-4d87 | Intel       | Jasper Lake LPC Controlle... | 71    |
| pci:8086-24cc | Intel       | 82801DBM (ICH4-M) LPC Int... | 70    |
| pci:8086-25c0 | Intel       | 5000X Chipset Memory Cont... | 70    |
| pci:8086-a393 | Intel       | Comet Lake PCH-V PCIe Por... | 70    |
| pci:1002-5a33 | AMD         | RS400 Host Bridge            | 69    |
| pci:1025-9602 | Acer Inc... | AMD RS780/RS880 PCI to PC... | 69    |
| pci:8086-2666 | Intel       | 82801FB/FBM/FR/FW/FRW (IC... | 69    |
| pci:8086-9a2f | Intel       | Tiger Lake-H Thunderbolt ... | 69    |
| pci:8086-a333 | Intel       | Cannon Lake PCH PCI Expre... | 69    |
| pci:1002-7930 | AMD         | RS600 Host Bridge            | 68    |
| pci:8086-2694 | Intel       | 631xESB/632xESB/3100 Chip... | 68    |
| pci:8086-8100 | Intel       | US15W/US15X SCH [Poulsbo]... | 68    |
| pci:8086-8110 | Intel       | US15W/US15X/US15L/UL11L S... | 68    |
| pci:8086-8119 | Intel       | US15W/US15X/US15L/UL11L S... | 68    |
| pci:8086-9a2d | Intel       | Tiger Lake-H Thunderbolt ... | 68    |
| pci:1b21-1182 | ASMedia ... | ASM1182e 2-Port PCIe x1 G... | 67    |
| pci:8086-02b6 | Intel       | Comet Lake PCH-LP PCIe Po... | 67    |
| pci:8086-0bf2 | Intel       | Atom Processor D2xxx/N2xx... | 67    |
| pci:8086-3c06 | Intel       | Xeon E5/Core i7 IIO PCI E... | 67    |
| pci:1217-7136 | O2 Micro    | OZ711SP1 Memory CardBus C... | 66    |
| pci:8086-34b2 | Intel       | Ice Lake-LP PCIe Port #11    | 66    |
| pci:8086-8112 | Intel       | US15W/US15X/US15L/UL11L S... | 66    |
| pci:8086-9a31 | Intel       | Tiger Lake-H Thunderbolt ... | 66    |
| pci:8086-9db7 | Intel       | 300 Series Chipset PCIe P... | 66    |
| pci:8086-0bf3 | Intel       | Atom Processor D2xxx/N2xx... | 65    |
| pci:8086-a339 | Intel       | Cannon Lake PCH PCI Expre... | 65    |
| pci:8086-a39a | Intel       | Comet Lake PCI Express Ro... | 65    |
| pci:1002-14a0 | AMD         | PCI bridge                   | 64    |
| pci:1002-14a1 | AMD         | PCI bridge                   | 64    |
| pci:10de-03a3 | Nvidia      | C55 Host Bridge              | 64    |
| pci:10de-0d9a | Nvidia      | PCI bridge                   | 64    |
| pci:1166-0103 | Broadcom    | EPB PCI-Express to PCI-X ... | 64    |
| pci:8086-25e6 | Intel       | 5000 Series Chipset PCI E... | 64    |
| pci:8086-2812 | Intel       | 82801HH (ICH8DH) LPC Inte... | 64    |
| pci:8086-43bd | Intel       | 500 Series Chipset Family... | 64    |
| pci:8086-6f0a | Intel       | Xeon E7 v4/Xeon E5 v4/Xeo... | 64    |
| pci:8086-a0b2 | Intel       | PCI bridge                   | 64    |
| pci:12d8-e130 | Pericom ... | PCI Express to PCI-XPI7C9... | 63    |
| pci:8086-2696 | Intel       | 631xESB/632xESB/3100 Chip... | 63    |
| pci:8086-37c5 | Intel       | PCI bridge                   | 62    |
| pci:1002-5956 | AMD         | RD790 Host Bridge            | 61    |
| pci:1002-5a17 | AMD         | RD890/RD9x0 PCI to PCI br... | 61    |
| pci:111d-8061 | Integrat... | PES12T3G2 PCI Express Gen... | 61    |
| pci:8086-29d0 | Intel       | 82Q33 Express DRAM Contro... | 61    |
| pci:1002-7936 | AMD         | RS600 PCI to PCI Bridge (... | 60    |
| pci:1106-0327 | VIA Tech... | P4M890 Host Bridge           | 60    |
| pci:1106-1327 | VIA Tech... | P4M890 Host Bridge           | 60    |
| pci:1106-2327 | VIA Tech... | P4M890 Host Bridge           | 60    |
| pci:1106-3327 | VIA Tech... | P4M890 Host Bridge           | 60    |
| pci:1106-4327 | VIA Tech... | P4M890 Host Bridge           | 60    |
| pci:1106-6327 | VIA Tech... | P4M890 Security Device       | 60    |
| pci:1106-7327 | VIA Tech... | P4M890 Host Bridge           | 60    |
| pci:8086-3b14 | Intel       | 3420 Chipset LPC Interfac... | 60    |
| pci:8086-43b4 | Intel       | 500 Series Chipset Family... | 60    |
| pci:8086-7ab8 | Intel       | 600 Series Chipset Family... | 60    |
| pci:10de-0a80 | Nvidia      | MCP79 Host Bridge            | 59    |
| pci:8086-25e2 | Intel       | 5000 Series Chipset PCI E... | 59    |
| pci:8086-25f7 | Intel       | 5000 Series Chipset PCI E... | 59    |
| pci:8086-34be | Intel       | Ice Lake-LP PCIe Port #7     | 59    |
| pci:8086-a11d | Intel       | 100 Series/C230 Series Ch... | 59    |
| pci:1022-170c | AMD         | Family 12h Processor Root... | 58    |
| pci:1039-0964 | Silicon ... | SiS964 [MuTIOL Media IO] ... | 58    |
| pci:8086-43b2 | Intel       | 500 Series Chipset Family... | 57    |
| pci:8086-7a84 | Intel       | Z690 Chipset LPC/eSPI Con... | 57    |
| pci:10de-05b1 | Nvidia      | NF200 PCIe 2.0 switch        | 56    |
| pci:8086-0109 | Intel       | Xeon E3-1200/2nd Generati... | 56    |
| pci:8086-0e0a | Intel       | Xeon E7 v2/Xeon E5 v2/Cor... | 56    |
| pci:8086-25fa | Intel       | 5000X Chipset PCI Express... | 56    |
| pci:8086-2912 | Intel       | 82801IH (ICH9DH) LPC Inte... | 55    |
| pci:8086-2f06 | Intel       | Xeon E7 v3/Xeon E5 v3/Cor... | 55    |
| pci:8086-02b2 | Intel       | Comet Lake PCH-LP PCIe Po... | 54    |
| pci:8086-277c | Intel       | 82975X Memory Controller Hub | 54    |
| pci:8086-a147 | Intel       | Q150 Chipset LPC/eSPI Con... | 54    |
| pci:8086-a29c | Intel       | 200 Series PCH PCI Expres... | 54    |
| pci:10e3-8111 | Tundra S... | Tsi381 PCIe to PCI Bridge    | 53    |
| pci:1106-c327 | VIA Tech... | P4M890 PCI to PCI Bridge ... | 53    |
| pci:8086-2f09 | Intel       | Xeon E7 v3/Xeon E5 v3/Cor... | 53    |
| pci:8086-5918 | Intel       | Xeon E3-1200 v6/7th Gen C... | 53    |
| pci:8086-9d43 | Intel       | Sunrise Point-LP LPC Cont... | 53    |
| pci:111d-8018 | Integrat... | PES12N3A 12-lane 3-Port P... | 52    |
| pci:8086-1c54 | Intel       | C204 Chipset LPC Controller  | 52    |
| pci:8086-277d | Intel       | 82975X PCI Express Root Port | 52    |
| pci:8086-464d | Intel       | 12th Gen Core Processor P... | 52    |
| pci:8086-a33b | Intel       | Cannon Lake PCH PCI Expre... | 52    |
| pci:8086-a395 | Intel       | Comet Lake PCH-V PCIe Por... | 52    |
| pci:1002-7935 | AMD         | RS600 PCI to PCI Bridge (... | 51    |
| pci:8086-24c0 | Intel       | 82801DB/DBL (ICH4/ICH4-L)... | 51    |
| pci:8086-341b | Intel       | 7500/5520/5500/X58 Unknown   | 51    |
| pci:8086-a299 | Intel       | 200 Series PCH PCI Expres... | 51    |
| pci:1002-5a11 | AMD         | RD890 Northbridge only si... | 50    |
| pci:1106-a327 | VIA Tech... | P4M890 PCI to PCI Bridge ... | 50    |
| pci:10de-0a86 | Nvidia      | MCP79 Host Bridge            | 49    |
| pci:10de-0aad | Nvidia      | MCP79 LPC Bridge             | 49    |
| pci:8086-1549 | Intel       | DSL2210 Thunderbolt Contr... | 49    |
| pci:8086-1c56 | Intel       | C206 Chipset LPC Controller  | 49    |
| pci:8086-a195 | Intel       | C620 Series Chipset Famil... | 49    |
| pci:10de-0a83 | Nvidia      | MCP79 Host Bridge            | 48    |
| pci:1106-3372 | VIA Tech... | VT8237S PCI to ISA Bridge    | 48    |
| pci:8086-2f0b | Intel       | Xeon E7 v3/Xeon E5 v3/Cor... | 48    |
| pci:10b5-8605 | PLX Tech... | PEX 8605 PCI Express 4-po... | 47    |
| pci:1106-0314 | VIA Tech... | CN700/VN800/P4M800CE/Pro ... | 47    |
| pci:1106-1314 | VIA Tech... | CN700/VN800/P4M800CE/Pro ... | 47    |
| pci:1106-2314 | VIA Tech... | CN700/VN800/P4M800CE/Pro ... | 47    |
| pci:1106-4314 | VIA Tech... | CN700/VN800/P4M800CE/Pro ... | 47    |
| pci:1106-7314 | VIA Tech... | CN700/VN800/P4M800CE/Pro ... | 47    |
| pci:8086-0159 | Intel       | Xeon E3-1200 v2/3rd Gen C... | 47    |
| pci:8086-7aba | Intel       | 600 Series Chipset Family... | 47    |
| pci:1033-0125 | NEC Comp... | uPD720400 PCI Express - P... | 46    |
| pci:1039-0963 | Silicon ... | SiS963 [MuTIOL Media IO] ... | 46    |
| pci:8086-3ecc | Intel       | Coffee Lake Host Bridge/D... | 46    |
| pci:8086-4e26 | Intel       | Host bridge                  | 46    |
| pci:8086-6f06 | Intel       | Xeon E7 v4/Xeon E5 v4/Xeo... | 46    |
| pci:8086-a198 | Intel       | C620 Series Chipset Famil... | 46    |
| pci:1002-7932 | AMD         | RS600 PCI to PCI Bridge (... | 45    |
| pci:10de-0faf | Nvidia      | PCI bridge                   | 45    |
| pci:1179-9602 | Toshiba ... | Toshiba America Info PCI ... | 45    |
| pci:1002-7937 | AMD         | RS690 PCI to PCI Bridge (... | 44    |
| pci:10de-00e0 | Nvidia      | nForce3 250Gb LPC Bridge     | 44    |
| pci:10de-00e1 | Nvidia      | nForce3 250Gb Host Bridge    | 44    |
| pci:10de-00e2 | Nvidia      | nForce3 250Gb AGP Host to... | 44    |
| pci:10de-00ed | Nvidia      | nForce3 250Gb PCI-to-PCI ... | 44    |
| pci:8086-2c71 | Intel       | Core i7/Xeon Generic Non-... | 44    |
| pci:12d8-2404 | Pericom ... | PI7C9X2G404 EL/SL PCIe2 4... | 43    |
| pci:8086-02b3 | Intel       | Comet Lake PCI Express Ro... | 43    |
| pci:8086-2f07 | Intel       | Xeon E7 v3/Xeon E5 v3/Cor... | 43    |
| pci:8086-a2d3 | Intel       | C422 Chipset LPC/eSPI Con... | 43    |
| pci:8086-a313 | Intel       | 300 Series Chipset Family... | 43    |
| pci:1039-0661 | Silicon ... | 661FX/M661FX/M661MX Host     | 42    |
| pci:1106-0204 | VIA Tech... | K8M800 Host Bridge           | 42    |
| pci:1106-1204 | VIA Tech... | K8M800 Host Bridge           | 42    |
| pci:1106-2204 | VIA Tech... | K8M800 Host Bridge           | 42    |
| pci:1106-3204 | VIA Tech... | K8M800 Host Bridge           | 42    |
| pci:1106-4204 | VIA Tech... | K8M800 Host Bridge           | 42    |
| pci:1106-7204 | VIA Tech... | K8M800 Host Bridge           | 42    |
| pci:8086-0e06 | Intel       | Xeon E7 v2/Xeon E5 v2/Cor... | 42    |
| pci:1106-a238 | VIA Tech... | K8T890 PCI to PCI Bridge ... | 41    |
| pci:1106-c238 | VIA Tech... | K8T890 PCI to PCI Bridge ... | 41    |
| pci:12d8-2304 | Pericom ... | PI7C9X2G304 EL/SL PCIe2 3... | 41    |
| pci:1912-001a | Renesas ... | SH7758 PCIe-PCI Bridge [PPB] | 41    |
| pci:1912-001d | Renesas ... | SH7758 PCIe Switch [PS]      | 41    |
| pci:8086-1e53 | Intel       | C216 Series Chipset LPC C... | 41    |
| pci:8086-25f8 | Intel       | 5000 Series Chipset PCI E... | 41    |
| pci:10de-0261 | Nvidia      | MCP51 LPC Bridge             | 40    |
| pci:1217-7134 | O2 Micro    | OZ711MP1/MS1 MemoryCardBu... | 40    |
| pci:8086-9a07 | Intel       | PCI bridge                   | 40    |
| pci:10b9-7101 | ULi Elec... | M7101 Power Management Co... | 39    |
| pci:10de-03bb | Nvidia      | C55 PCI Express bridge       | 39    |
| pci:8086-1c52 | Intel       | C202 Chipset LPC Controller  | 39    |
| pci:8086-2560 | Intel       | 82845G/GL[Brookdale-G]/GE... | 39    |
| pci:8086-4dbc | Intel       | Jasper Lake PCIe Port #5     | 39    |
| pci:8086-7ac8 | Intel       | 600 Series Chipset Family... | 39    |
| pci:1039-0002 | Silicon ... | AGP Port (virtual PCI-to-... | 38    |
| pci:8086-3c09 | Intel       | Xeon E5/Core i7 IIO PCI E... | 38    |
| pci:8086-43ba | Intel       | 500 Series Chipset Family... | 38    |
| pci:8086-a1c2 | Intel       | C622 Series Chipset LPC/e... | 38    |
| pci:8086-151a | Intel       | DSL2310 Thunderbolt Contr... | 37    |
| pci:8086-25f9 | Intel       | 5000 Series Chipset PCI E... | 37    |
| pci:8086-460d | Intel       | 12th Gen Core Processor P... | 37    |
| pci:8086-0c09 | Intel       | Xeon E3-1200 v3/4th Gen C... | 36    |
| pci:8086-3340 | Intel       | 82855PM Processor to I/O ... | 36    |
| pci:8086-3341 | Intel       | 82855PM Processor to AGP ... | 36    |
| pci:8086-3580 | Intel       | 82852/82855 GM/GME/PM/GMV... | 36    |
| pci:8086-3c0b | Intel       | Xeon E5/Core i7 IIO PCI E... | 36    |
| pci:10b9-5249 | ULi Elec... | M5249 HTT to PCI Bridge      | 35    |
| pci:10de-075d | Nvidia      | MCP78S [GeForce 8200] LPC... | 35    |
| pci:1217-8134 | O2 Micro    | CardBus bridge               | 35    |
| pci:12d8-e111 | Pericom ... | PI7C9X111SL PCIe-to-PCI R... | 35    |
| pci:1556-be00 | PLDA        | PCI Express Bridge           | 35    |
| pci:8086-015d | Intel       | Xeon E3-1200 v2/3rd Gen C... | 35    |
| pci:8086-1136 | Intel       | Thunderbolt 4 Bridge [Map... | 35    |
| pci:8086-9a05 | Intel       | PCI bridge                   | 35    |
| pci:8086-a153 | Intel       | QM175 Chipset LPC/eSPI Co... | 35    |
| pci:8086-a2ed | Intel       | 200 Series PCH PCI Expres... | 35    |
| pci:1028-9602 | Dell        | PCI bridge                   | 34    |
| pci:1106-3177 | VIA Tech... | VT8235 ISA Bridge            | 34    |
| pci:8086-a29e | Intel       | 200 Series PCH PCI Expres... | 34    |
| pci:104c-8231 | Texas In... | XIO2000(A)/XIO2200A PCI E... | 33    |
| pci:8086-06bb | Intel       | 400 Series Chipset Family... | 32    |
| pci:8086-9b73 | Intel       | Host bridge                  | 32    |
| pci:10de-03a1 | Nvidia      | C55 Host Bridge              | 31    |
| pci:10de-03b9 | Nvidia      | C55 PCI Express bridge       | 31    |
| pci:1106-0336 | VIA Tech... | K8M890CE Host Bridge         | 31    |
| pci:1106-1336 | VIA Tech... | K8M890CE Host Bridge         | 31    |
| pci:1106-2336 | VIA Tech... | K8M890CE Host Bridge         | 31    |
| pci:1106-3336 | VIA Tech... | K8M890CE Host Bridge         | 31    |
| pci:1106-4336 | VIA Tech... | K8M890CE Host Bridge         | 31    |
| pci:1106-7336 | VIA Tech... | K8M890CE Host Bridge         | 31    |
| pci:8086-0285 | Intel       | Comet Lake PCH-LP LPC Sta... | 31    |
| pci:8086-0687 | Intel       | Q470 Chipset LPC/eSPI Con... | 31    |
| pci:8086-06c2 | Intel       | 400 Series Chipset Family... | 31    |
| pci:8086-0e01 | Intel       | Xeon E7 v2/Xeon E5 v2/Cor... | 31    |
| pci:8086-1e46 | Intel       | Z75 Express Chipset LPC C... | 31    |
| pci:8086-25d8 | Intel       | 5000P Chipset Memory Cont... | 31    |
| pci:8086-43c2 | Intel       | 500 Series Chipset Family... | 31    |
| pci:8086-010d | Intel       | Xeon E3-1200/2nd Generati... | 30    |
| pci:8086-02bd | Intel       | Comet Lake PCH-LP PCIe Po... | 30    |
| pci:8086-1601 | Intel       | Broadwell-U PCI Express x... | 30    |
| pci:8086-9d56 | Intel       | Sunrise Point-LP LPC Cont... | 30    |
| pci:1002-5a10 | AMD         | RD890 Northbridge only du... | 29    |
| pci:8086-032c | Intel       | 6702PXH PCI Express-to-PC... | 29    |
| pci:10de-07c3 | Nvidia      | MCP73 Host Bridge            | 28    |
| pci:8086-0d09 | Intel       | Crystal Well PCI Express ... | 28    |
| pci:8086-8c52 | Intel       | C222 Series Chipset Famil... | 28    |
| pci:8086-8c54 | Intel       | C224 Series Chipset Famil... | 28    |
| pci:8086-a14d | Intel       | QM170 Chipset LPC/eSPI Co... | 28    |
| pci:8086-a396 | Intel       | Comet Lake PCH-V PCIe Por... | 28    |
| pci:1b21-118f | ASMedia ... | PCIe Switch                  | 27    |
| pci:8086-7ab0 | Intel       | 600 Series Chipset Family... | 27    |
| pci:8086-7abc | Intel       | 600 Series Chipset Family... | 27    |
| pci:10de-0363 | Nvidia      | MCP55 LPC Bridge             | 26    |
| pci:8086-02b7 | Intel       | Comet Lake PCH-LP PCIe Po... | 26    |
| pci:8086-06b3 | Intel       | 400 Series Chipset Family... | 26    |
| pci:8086-06ba | Intel       | 400 Series Chipset Family... | 26    |
| pci:8086-6f0b | Intel       | Xeon E7 v4/Xeon E5 v4/Xeo... | 26    |
| pci:1002-7933 | AMD         | RS600 PCI to PCI Bridge (... | 25    |
| pci:1039-0001 | Silicon ... | AGP Port (virtual PCI-to-... | 25    |
| pci:10e3-8113 | Tundra S... | Tundra PCI bridge            | 25    |
| pci:1106-0308 | VIA Tech... | PT880 Ultra/PT894 Host Br... | 25    |
| pci:1106-1308 | VIA Tech... | PT894 Host Bridge            | 25    |
| pci:1106-2308 | VIA Tech... | PT894 Host Bridge            | 25    |
| pci:1106-4308 | VIA Tech... | PT894 Host Bridge            | 25    |
| pci:1106-7308 | VIA Tech... | PT894 Host Bridge            | 25    |
| pci:8086-0bf4 | Intel       | Atom Processor D2xxx/N2xx... | 25    |
| pci:8086-34bb | Intel       | Ice Lake-LP PCIe Port #4     | 25    |
| pci:8086-3c05 | Intel       | Xeon E5/Core i7 IIO PCI E... | 25    |
| pci:8086-3c07 | Intel       | Xeon E5/Core i7 IIO PCI E... | 25    |
| pci:8086-43c3 | Intel       | 500 Series Chipset Family... | 25    |
| pci:8086-1a30 | Intel       | 82845 845 [Brookdale] Chi... | 24    |
| pci:8086-1a31 | Intel       | 82845 845 [Brookdale] Chi... | 24    |
| pci:8086-29f0 | Intel       | 3200/3210 Chipset DRAM Co... | 24    |
| pci:8086-3595 | Intel       | E7525/E7520/E7320 PCI Exp... | 24    |
| pci:8086-a196 | Intel       | C620 Series Chipset Famil... | 24    |
| pci:8086-a197 | Intel       | C620 Series Chipset Famil... | 24    |
| pci:8086-a39b | Intel       | Comet Lake PCH-V PCIe Por... | 24    |
| pci:1002-5a20 | AMD         | RD890/RD990 PCI to PCI br... | 23    |
| pci:1022-1413 | AMD         | Family 15h (Models 10h-1f... | 23    |
| pci:1039-0760 | Silicon ... | 760/M760 Host                | 23    |
| pci:10de-01e0 | Nvidia      | nForce2 IGP2                 | 23    |
| pci:10de-01e8 | Nvidia      | nForce2 AGP                  | 23    |
| pci:8086-0329 | Intel       | 6700PXH PCI Express-to-PC... | 23    |
| pci:8086-032a | Intel       | 6700PXH PCI Express-to-PC... | 23    |
| pci:8086-1d3f | Intel       | C608/C606/X79 series chip... | 23    |
| pci:8086-1d74 | Intel       | C608/C606/X79 series chip... | 23    |
| pci:8086-2561 | Intel       | 82845G/GL[Brookdale-G]/GE... | 23    |
| pci:8086-2e29 | Intel       | 4 Series Chipset PCI Expr... | 23    |
| pci:8086-7ac0 | Intel       | 600 Series Chipset Family... | 23    |
| pci:8086-a14a | Intel       | C232 Chipset LPC/eSPI Con... | 23    |
| pci:1002-5980 | AMD         | RD790 PCI to PCI bridge (... | 22    |
| pci:1002-5a12 | AMD         | RD890 Northbridge only du... | 22    |
| pci:1106-a353 | VIA Tech... | VX8xx/900 Series South-No... | 22    |
| pci:8086-06b9 | Intel       | 400 Series Chipset Family... | 22    |
| pci:8086-3400 | Intel       | 5520/5500/X58 I/O Hub to ... | 22    |
| pci:8086-4660 | Intel       | 12th Gen Core Processor H... | 22    |
| pci:8086-6f09 | Intel       | Xeon E7 v4/Xeon E5 v4/Xeo... | 22    |
| pci:10b9-1573 | ULi Elec... | PCI to LPC Controller        | 21    |
| pci:10de-0060 | Nvidia      | nForce2 ISA Bridge           | 21    |
| pci:10de-006c | Nvidia      | nForce2 External PCI Bridge  | 21    |
| pci:8086-0e0b | Intel       | Xeon E7 v2/Xeon E5 v2/Cor... | 21    |
| pci:8086-2584 | Intel       | 82925X/XE Memory Controll... | 21    |
| pci:8086-2585 | Intel       | 82925X/XE PCI Express Roo... | 21    |
| pci:8086-27bd | Intel       | 82801GHM (ICH7-M DH) LPC ... | 21    |
| pci:8086-3597 | Intel       | E7525/E7520 PCI Express P... | 21    |
| pci:8086-4386 | Intel       | 500 Series Chipset Family... | 21    |
| pci:8086-43b6 | Intel       | 500 Series Chipset Family... | 21    |
| pci:8086-4668 | Intel       | Host bridge                  | 21    |
| pci:8086-8a23 | Intel       | Ice Lake Thunderbolt 3 PC... | 21    |
| pci:8086-8d1a | Intel       | C610/X99 series chipset P... | 21    |
| pci:1039-0962 | Silicon ... | SiS962 [MuTIOL Media IO] ... | 20    |
| pci:104c-ac50 | Texas In... | PCI1410 PC card Cardbus C... | 20    |
| pci:10de-0364 | Nvidia      | MCP55 LPC Bridge             | 20    |
| pci:10de-0fae | Nvidia      | PCI bridge                   | 20    |
| pci:1106-b353 | VIA Tech... | VX855/VX875/VX900 PCI to ... | 20    |
| pci:1180-0475 | Ricoh       | RL5c475                      | 20    |
| pci:8086-0e09 | Intel       | Xeon E7 v2/Xeon E5 v2/Cor... | 20    |
| pci:8086-2980 | Intel       | 82G35 Express DRAM Contro... | 20    |
| pci:8086-29d1 | Intel       | 82Q33 Express PCI Express... | 20    |
| pci:8086-34b6 | Intel       | Ice Lake-LP PCIe Port #15    | 20    |
| pci:8086-9a26 | Intel       | 11th Gen Core Processor H... | 20    |
| pci:8086-9dbb | Intel       | 300 Series Chipset PCIe P... | 20    |
| pci:1106-a208 | VIA Tech... | PT890 PCI to PCI Bridge C... | 19    |
| pci:144d-9602 | Samsung ... | Electronics PCI bridge       | 19    |
| pci:8086-0d00 | Intel       | Crystal Well DRAM Controller | 19    |
| pci:8086-2f01 | Intel       | Xeon E7 v3/Xeon E5 v3/Cor... | 19    |
| pci:8086-3420 | Intel       | 7500/5520/5500/X58 I/O Hu... | 19    |
| pci:8086-3e18 | Intel       | 8th Gen Core 4-core Works... | 19    |
| pci:8086-3ec6 | Intel       | 8th Gen Core Processor Ho... | 19    |
| pci:8086-a19c | Intel       | C620 Series Chipset Famil... | 19    |
| pci:104c-8036 | Texas In... | PCI6515 Cardbus Controller   | 18    |
| pci:104c-ac44 | Texas In... | PCI4510 PC card Cardbus C... | 18    |
| pci:10de-07c5 | Nvidia      | MCP73 Host Bridge            | 18    |
| pci:10de-0a84 | Nvidia      | MCP79 Host Bridge            | 18    |
| pci:8086-0370 | Intel       | 80333 Segment-A PCIe Expr... | 18    |
| pci:8086-0372 | Intel       | 80333 Segment-B PCIe Expr... | 18    |
| pci:8086-06c3 | Intel       | 400 Series Chipset Family... | 18    |
| pci:8086-0e07 | Intel       | Xeon E7 v2/Xeon E5 v2/Cor... | 18    |
| pci:8086-1c50 | Intel       | B65 Express Chipset LPC C... | 18    |
| pci:8086-43b5 | Intel       | 500 Series Chipset Family... | 18    |
| pci:8086-4648 | Intel       | Host bridge                  | 18    |
| pci:8086-a3ea | Intel       | Comet Lake PCH-V PCIe Por... | 18    |
| pci:1002-5979 | AMD         | RD790 PCI to PCI bridge (... | 17    |
| pci:101b-0452 | Vitesse ... | VSC452 [SuperBMC]            | 17    |
| pci:1039-0648 | Silicon ... | 645xx                        | 17    |
| pci:10de-05bf | Nvidia      | PCI bridge                   | 17    |
| pci:8086-02ba | Intel       | Comet Lake PCH-LP PCIe Po... | 17    |
| pci:8086-0697 | Intel       | 400 Series Chipset Family... | 17    |
| pci:8086-1614 | Intel       | Broadwell-U Host Bridge -... | 17    |
| pci:8086-4db8 | Intel       | Jasper Lake PCIe Port #1     | 17    |
| pci:8086-4db9 | Intel       | Jasper Lake PCIe Port #2     | 17    |
| pci:8086-9a12 | Intel       | Host bridge                  | 17    |
| pci:8086-a087 | Intel       | ISA bridge                   | 17    |
| pci:8086-a11f | Intel       | 100 Series/C230 Series Ch... | 17    |
| pci:10de-0442 | Nvidia      | MCP65 LPC Bridge             | 16    |
| pci:8086-06b2 | Intel       | 400 Series Chipset Family... | 16    |
| pci:8086-0e05 | Intel       | Xeon E7 v2/Xeon E5 v2/Cor... | 16    |
| pci:8086-2e40 | Intel       | 4 Series Chipset DRAM Con... | 16    |
| pci:8086-34bd | Intel       | Ice Lake-LP PCIe Port #6     | 16    |
| pci:8086-3596 | Intel       | E7525/E7520/E7320 PCI Exp... | 16    |
| pci:8086-38b8 | Intel       | PCIe Root Port #1            | 16    |
| pci:8086-38bc | Intel       | PCIe Root Port #5            | 16    |
| pci:8086-3b16 | Intel       | 3450 Chipset LPC Interfac... | 16    |
| pci:8086-7abb | Intel       | 600 Series Chipset Family... | 16    |
| pci:8086-a29d | Intel       | 200 Series PCH PCI Expres... | 16    |
| pci:1002-5951 | AMD         | RX480/RX482 Host Bridge      | 15    |
| pci:104c-ac8e | Texas In... | PCI7420 CardBus Controller   | 15    |
| pci:10b5-8723 | PLX Tech... | PCI bridge                   | 15    |
| pci:1106-287b | VIA Tech... | VT8251 Host Bridge           | 15    |
| pci:1106-3287 | VIA Tech... | VT8251 PCI to ISA Bridge     | 15    |
| pci:1106-b999 | VIA Tech... | [K8T890 North / VT8237 So... | 15    |
| pci:1166-0104 | Broadcom    | BCM5785 [HT1000] PCI/PCI-... | 15    |
| pci:8086-2440 | Intel       | 82801BA ISA Bridge (LPC)     | 15    |
| pci:8086-43b3 | Intel       | 500 Series Chipset Family... | 15    |
| pci:8086-a2ee | Intel       | 200 Series PCH PCI Expres... | 15    |
| pci:8086-a341 | Intel       | Cannon Lake PCH PCI Expre... | 15    |
| pci:1039-0761 | Silicon ... | 761/M761 Host                | 14    |
| pci:10de-05be | Nvidia      | NF200 PCIe 2.0 switch for... | 14    |
| pci:1106-287c | VIA Tech... | VT8251 PCIE Root Port        | 14    |
| pci:1106-287d | VIA Tech... | VT8251 PCIE Root Port        | 14    |
| pci:12d8-2608 | Pericom ... | PI7C9X2G608GP PCIe2 6-Por... | 14    |
| pci:19a2-0120 | Emulex      | x1 PCIe Gen2 Bridge[Pilot4]  | 14    |
| pci:1ae9-0101 | Wilocity    | Wil6200 PCI Express Upstr... | 14    |
| pci:1ae9-0201 | Wilocity    | Wil6200 Wireless PCI Expr... | 14    |
| pci:8086-248c | Intel       | 82801CAM ISA Bridge (LPC)    | 14    |
| pci:8086-2578 | Intel       | 82875P/E7210 Memory Contr... | 14    |
| pci:8086-2579 | Intel       | 82875P Processor to AGP C... | 14    |
| pci:8086-2778 | Intel       | E7230/3000/3010 Memory Co... | 14    |
| pci:8086-29f1 | Intel       | 3200/3210 Chipset Host-Pr... | 14    |
| pci:8086-3197 | Intel       | Celeron/Pentium Silver Pr... | 14    |
| pci:8086-3882 | Intel       | Ice Lake LPC Controller      | 14    |
| pci:8086-43bb | Intel       | 500 Series Chipset Family... | 14    |
| pci:8086-6f07 | Intel       | Xeon E7 v4/Xeon E5 v4/Xeo... | 14    |
| pci:8086-8a14 | Intel       | Ice Lake Processor Host B... | 14    |
| pci:8086-a2ec | Intel       | 200 Series PCH PCI Expres... | 14    |
| pci:10b5-8114 | PLX Tech... | PEX 8114 PCI Express-to-P... | 13    |
| pci:10de-0051 | Nvidia      | CK804 ISA Bridge             | 13    |
| pci:1106-0410 | VIA Tech... | VX900 Series Host Bridge:... | 13    |
| pci:1106-1410 | VIA Tech... | VX900 Series Error Reporting | 13    |
| pci:1106-2410 | VIA Tech... | VX900 Series CPU Bus Cont... | 13    |
| pci:1106-287a | VIA Tech... | VT8251 PCI to PCI Bridge     | 13    |
| pci:1106-3410 | VIA Tech... | VX900 Series DRAM Bus Con... | 13    |
| pci:1106-4410 | VIA Tech... | VX900 Series Power Manage... | 13    |
| pci:1106-5410 | VIA Tech... | VX900 Series APIC and Cen... | 13    |
| pci:1106-6410 | VIA Tech... | VX900 Series Scratch Regi... | 13    |
| pci:1106-7410 | VIA Tech... | VX900 Series North-South ... | 13    |
| pci:1106-8410 | VIA Tech... | VX900 Series Bus Control ... | 13    |
| pci:1106-a410 | VIA Tech... | VX900 Series PCI Express ... | 13    |
| pci:1106-b410 | VIA Tech... | VX900 Series PCI Express ... | 13    |
| pci:1106-c410 | VIA Tech... | VX900 Series PCI Express ... | 13    |
| pci:1106-d410 | VIA Tech... | VX900 Series PCI Express ... | 13    |
| pci:1106-e410 | VIA Tech... | VX900 Series PCI Express ... | 13    |
| pci:8086-02b9 | Intel       | Comet Lake PCH-LP PCIe Po... | 13    |
| pci:8086-0bf5 | Intel       | Atom Processor D2xxx/N2xx... | 13    |
| pci:8086-1610 | Intel       | Broadwell-U Host Bridge -... | 13    |
| pci:8086-1f14 | Intel       | Atom processor C2000 RAS     | 13    |
| pci:8086-1f38 | Intel       | Atom processor C2000 PCU     | 13    |
| pci:8086-2774 | Intel       | 82955X Memory Controller Hub | 13    |
| pci:8086-4001 | Intel       | 5400 Chipset Memory Contr... | 13    |
| pci:8086-4e22 | Intel       | Host bridge                  | 13    |
| pci:8086-8c92 | Intel       | 9 Series Chipset Family P... | 13    |
| pci:8086-a32d | Intel       | Cannon Lake PCH PCI Expre... | 13    |
| pci:1002-4342 | AMD         | SB200 PCI to PCI Bridge      | 12    |
| pci:1002-434c | AMD         | SB200 PCI to LPC Bridge      | 12    |
| pci:1002-7934 | AMD         | PCI bridge                   | 12    |
| pci:104c-ac46 | Texas In... | PCI4520 PC card Cardbus C... | 12    |
| pci:1106-b091 | VIA Tech... | VT8633 [Apollo Pro266 AGP]   | 12    |
| pci:111d-8039 | Microsem... | PES3T3 PCI Express Switch    | 12    |
| pci:17a0-7163 | Genesys ... | GL9701 PCIe to PCI Bridge    | 12    |
| pci:17aa-9602 | Lenovo      | PCI bridge                   | 12    |
| pci:8086-1605 | Intel       | Broadwell-U PCI Express x... | 12    |
| pci:8086-1c47 | Intel       | UM67 Express Chipset LPC ... | 12    |
| pci:8086-1f10 | Intel       | Atom processor C2000 PCIe... | 12    |
| pci:8086-1f12 | Intel       | Atom processor C2000 PCIe... | 12    |
| pci:8086-25d4 | Intel       | 5000V Chipset Memory Cont... | 12    |
| pci:8086-2775 | Intel       | 82955X PCI Express Root Port | 12    |
| pci:8086-2b00 | Intel       | Xeon Processor E7 Product... | 12    |
| pci:8086-2b02 | Intel       | Xeon Processor E7 Product... | 12    |
| pci:8086-2b04 | Intel       | Xeon Processor E7 Product... | 12    |
| pci:8086-2b08 | Intel       | Xeon Processor E7 Product... | 12    |
| pci:8086-2b0c | Intel       | Xeon Processor E7 Product... | 12    |
| pci:8086-2b10 | Intel       | Xeon Processor E7 Product... | 12    |
| pci:8086-2b13 | Intel       | Xeon Processor E7 Product... | 12    |
| pci:8086-2b14 | Intel       | Xeon Processor E7 Product... | 12    |
| pci:8086-2b16 | Intel       | Xeon Processor E7 Product... | 12    |
| pci:8086-2b18 | Intel       | Xeon Processor E7 Product... | 12    |
| pci:8086-2b1b | Intel       | Xeon Processor E7 Product... | 12    |
| pci:8086-2b1c | Intel       | Xeon Processor E7 Product... | 12    |
| pci:8086-2b1e | Intel       | Xeon Processor E7 Product... | 12    |
| pci:8086-2b20 | Intel       | Xeon Processor E7 Product... | 12    |
| pci:8086-2b22 | Intel       | Xeon Processor E7 Product... | 12    |
| pci:8086-2b24 | Intel       | Xeon Processor E7 Product... | 12    |
| pci:8086-2b28 | Intel       | Xeon Processor E7 Product... | 12    |
| pci:8086-2b2a | Intel       | Xeon Processor E7 Product... | 12    |
| pci:8086-2b2c | Intel       | Xeon Processor E7 Product... | 12    |
| pci:8086-2b30 | Intel       | Xeon Processor E7 Product... | 12    |
| pci:8086-2b32 | Intel       | Xeon MP Unknown              | 12    |
| pci:8086-2b34 | Intel       | Xeon Processor E7 Product... | 12    |
| pci:8086-2b36 | Intel       | Xeon MP Unknown              | 12    |
| pci:8086-2b38 | Intel       | Xeon Processor E7 Product... | 12    |
| pci:8086-2b3a | Intel       | Xeon MP Unknown              | 12    |
| pci:8086-2b3c | Intel       | Xeon Processor E7 Product... | 12    |
| pci:8086-2b3e | Intel       | Xeon MP Unknown              | 12    |
| pci:8086-2b40 | Intel       | Xeon Processor E7 Product... | 12    |
| pci:8086-2b42 | Intel       | Xeon Processor E7 Product... | 12    |
| pci:8086-2b44 | Intel       | Xeon Processor E7 Product... | 12    |
| pci:8086-2b46 | Intel       | Xeon Processor E7 Product... | 12    |
| pci:8086-2b48 | Intel       | Xeon Processor E7 Product... | 12    |
| pci:8086-2b4c | Intel       | Xeon Processor E7 Product... | 12    |
| pci:8086-2b50 | Intel       | Xeon Processor E7 Product... | 12    |
| pci:8086-2b52 | Intel       | Xeon Processor E7 Product... | 12    |
| pci:8086-2b54 | Intel       | Xeon Processor E7 Product... | 12    |
| pci:8086-2b56 | Intel       | Xeon Processor E7 Product... | 12    |
| pci:8086-2b60 | Intel       | Xeon Processor E7 Product... | 12    |
| pci:8086-2b62 | Intel       | Xeon Processor E7 Product... | 12    |
| pci:8086-2b64 | Intel       | Xeon Processor E7 Product... | 12    |
| pci:8086-2b66 | Intel       | Xeon Processor E7 Product... | 12    |
| pci:8086-2f05 | Intel       | Xeon E7 v3/Xeon E5 v3/Cor... | 12    |
| pci:8086-3407 | Intel       | 5520/5500/X58 I/O Hub to ... | 12    |
| pci:8086-6f01 | Intel       | Xeon E7 v4/Xeon E5 v4/Xeo... | 12    |
| pci:8086-a32e | Intel       | Cannon Lake PCH PCI Expre... | 12    |
| pci:1002-5838 | AMD         | RS300 AGP Bridge             | 11    |
| pci:1002-5a13 | AMD         | RD890S/SR5650 Host Bridge    | 11    |
| pci:104d-9602 | Sony        | PCI bridge                   | 11    |
| pci:10b5-8624 | PLX Tech... | PEX 8624 24-lane, 6-Port ... | 11    |
| pci:10de-01b3 | Nvidia      | nForce PCIe Bridge           | 11    |
| pci:10de-0362 | Nvidia      | MCP55 LPC Bridge             | 11    |
| pci:10de-0815 | Nvidia      | nForce 790i PCIe Bridge 1    | 11    |
| pci:1106-e238 | VIA Tech... | K8T890 PCI to PCI Bridge ... | 11    |
| pci:1217-7175 | O2 Micro    | O2Micro OZ128 Peripheral ... | 11    |
| pci:1462-9602 | Micro-St... | PCI bridge                   | 11    |
| pci:1ae9-0200 | Wilocity    | Wil6200 PCI Express Port     | 11    |
| pci:3388-0021 | Hint        | HB6 Universal PCI-PCI bri... | 11    |
| pci:8086-2b58 | Intel       | Xeon Processor E7 Product... | 11    |
| pci:8086-2b5a | Intel       | Xeon Processor E7 Product... | 11    |
| pci:8086-2b5c | Intel       | Xeon Processor E7 Product... | 11    |
| pci:8086-2b5e | Intel       | Xeon Processor E7 Product... | 11    |
| pci:8086-3590 | Intel       | E7520 Memory Controller Hub  | 11    |
| pci:8086-359e | Intel       | E7525 Memory Controller Hub  | 11    |
| pci:8086-4023 | Intel       | 5400 Chipset PCI Express ... | 11    |
| pci:8086-4dbe | Intel       | Jasper Lake PCIe Port #7     | 11    |
| pci:8086-a193 | Intel       | C620 Series Chipset Famil... | 11    |
| pci:8086-a1c3 | Intel       | C624 Series Chipset LPC/e... | 11    |
| pci:8086-a30a | Intel       | 300 Series Chipset Family... | 11    |
| pci:1039-0651 | Silicon ... | 651 Host                     | 10    |
| pci:10de-07c7 | Nvidia      | MCP73V Host Bridge           | 10    |
| pci:1106-0282 | VIA Tech... | K8T800Pro Host Bridge        | 10    |
| pci:1106-1282 | VIA Tech... | K8T800Pro Host Bridge        | 10    |
| pci:1106-2282 | VIA Tech... | K8T800Pro Host Bridge        | 10    |
| pci:1106-3189 | VIA Tech... | VT8377 [KT400/KT600 AGP] ... | 10    |
| pci:1106-3282 | VIA Tech... | K8T800Pro Host Bridge        | 10    |
| pci:1106-4282 | VIA Tech... | K8T800Pro Host Bridge        | 10    |
| pci:1106-7282 | VIA Tech... | K8T800Pro Host Bridge        | 10    |
| pci:1106-d238 | VIA Tech... | K8T890 PCI to PCI Bridge ... | 10    |
| pci:1106-f238 | VIA Tech... | K8T890 PCI to PCI Bridge ... | 10    |
| pci:12d8-e113 | Pericom ... | Pericom PCI bridge           | 10    |
| pci:1d87-0100 | Fuzhou R... | RK3399 PCI Express Root Port | 10    |
| pci:8086-0043 | Intel       | Core Processor Secondary ... | 10    |
| pci:8086-0340 | Intel       | 41210 [Lanai] Serial to P... | 10    |
| pci:8086-0341 | Intel       | 41210 [Lanai] Serial to P... | 10    |
| pci:8086-06c1 | Intel       | 400 Series Chipset Family... | 10    |
| pci:8086-1e58 | Intel       | UM77 Express Chipset LPC ... | 10    |
| pci:8086-2573 | Intel       | 82865G/PE/P PCI to CSA Br... | 10    |
| pci:8086-25e4 | Intel       | 5000 Series Chipset PCI E... | 10    |
| pci:8086-2b53 | Intel       | Xeon MP Unknown              | 10    |
| pci:8086-2b5b | Intel       | Xeon MP Unknown              | 10    |
| pci:8086-2b68 | Intel       | Xeon Processor E7 Product... | 10    |
| pci:8086-2b6c | Intel       | Xeon Processor E7 Product... | 10    |
| pci:8086-a192 | Intel       | C620 Series Chipset Famil... | 10    |
| pci:104c-ac55 | Texas In... | PCI1520 PC card Cardbus C... | 9     |
| pci:10b5-8718 | PLX Tech... | PEX 8718 16-Lane, 5-Port ... | 9     |
| pci:10b9-1575 | ULi Elec... | M1575 South Bridge           | 9     |
| pci:10de-007e | Nvidia      | nForce4 Intel Edition PCI... | 9     |
| pci:10de-0800 | Nvidia      | nForce 790i Host Bridge      | 9     |
| pci:10de-0817 | Nvidia      | nForce 790i PCIe Bridge 3    | 9     |
| pci:1106-0259 | VIA Tech... | CN333/CN400/PM880 Host Br... | 9     |
| pci:1106-1259 | VIA Tech... | CN333/CN400/PM880 Host Br... | 9     |
| pci:1106-2259 | VIA Tech... | CN333/CN400/PM880 CPU Hos... | 9     |
| pci:1106-3259 | VIA Tech... | CN333/CN400/PM880 Host Br... | 9     |
| pci:1106-4259 | VIA Tech... | CN333/CN400/PM880 Host Br... | 9     |
| pci:1106-7259 | VIA Tech... | CN333/CN400/PM880 Host Br... | 9     |
| pci:8086-257b | Intel       | 82875P/E7210 Processor to... | 9     |
| pci:8086-2779 | Intel       | E7230/3000/3010 PCI Expre... | 9     |
| pci:8086-2981 | Intel       | 82G35 Express PCI Express... | 9     |
| pci:8086-3a74 | Intel       | 82801JD/DO (ICH10 Family)... | 9     |
| pci:8086-3a76 | Intel       | 82801JD/DO (ICH10 Family)... | 9     |
| pci:8086-3b0c | Intel       | 5 Series Chipset LPC Inte... | 9     |
| pci:8086-43b9 | Intel       | 500 Series Chipset Family... | 9     |
| pci:8086-43c7 | Intel       | 500 Series Chipset Family... | 9     |
| pci:8086-7110 | Intel       | 82371AB/EB/MB PIIX4 ISA      | 9     |
| pci:8086-7113 | Intel       | 82371AB/EB/MB PIIX4 ACPI     | 9     |
| pci:8086-7ab9 | Intel       | 600 Series Chipset Family... | 9     |
| pci:8086-7ac4 | Intel       | 600 Series Chipset Family... | 9     |
| pci:8086-a331 | Intel       | Cannon Lake PCH PCI Expre... | 9     |
| pci:1002-5952 | AMD         | RD580 Host Bridge            | 8     |
| pci:1039-0650 | Silicon ... | 650/M650 Host                | 8     |
| pci:10b5-8647 | PLX Tech... | PEX 8647 48-Lane, 3-Port ... | 8     |
| pci:10b5-8780 | PLX Tech... | PCI bridge                   | 8     |
| pci:10de-0071 | Nvidia      | nForce4 Intel Edition CPU... | 8     |
| pci:10de-00d0 | Nvidia      | nForce3 LPC Bridge           | 8     |
| pci:10de-00d1 | Nvidia      | nForce3 Host Bridge          | 8     |
| pci:10de-00d2 | Nvidia      | nForce3 AGP Bridge           | 8     |
| pci:10de-00dd | Nvidia      | nForce3 PCI Bridge           | 8     |
| pci:10de-03b8 | Nvidia      | C55 PCI Express bridge       | 8     |
| pci:10de-1ad1 | Nvidia      | Tegra PCIe x4/x8 Endpoint... | 8     |
| pci:1106-0353 | VIA Tech... | VX800/820-Series Chipset ... | 8     |
| pci:1106-1353 | VIA Tech... | VX800/VX820 Error Reporting  | 8     |
| pci:1106-2353 | VIA Tech... | VX800/VX820 Host Bus Control | 8     |
| pci:1106-3099 | VIA Tech... | VT8366/A/7 [Apollo KT266/... | 8     |
| pci:1106-3148 | VIA Tech... | P4M266 Host Bridge           | 8     |
| pci:1106-3353 | VIA Tech... | VX800/820 PCI to PCI Bridge  | 8     |
| pci:1106-4353 | VIA Tech... | VX800/VX820 Power Managem... | 8     |
| pci:1106-6353 | VIA Tech... | VX800/VX820 Scratch Regis... | 8     |
| pci:1106-7353 | VIA Tech... | VX800/VX820 North-South M... | 8     |
| pci:1106-8353 | VIA Tech... | VX800/VX820 Bus Control a... | 8     |
| pci:1106-b099 | VIA Tech... | VT8366/A/7 [Apollo KT266/... | 8     |
| pci:1179-0617 | Toshiba ... | ToPIC100 PCI to Cardbus B... | 8     |
| pci:12d8-400c | Pericom ... | PCI standard PCI-to-PCI b... | 8     |
| pci:8086-0b26 | Intel       | Thunderbolt 4 Bridge [Gos... | 8     |
| pci:8086-1980 | Intel       | Atom Processor C3000 Seri... | 8     |
| pci:8086-19a1 | Intel       | Atom Processor C3000 Seri... | 8     |
| pci:8086-19a3 | Intel       | Atom Processor C3000 Seri... | 8     |
| pci:8086-19dc | Intel       | Atom Processor C3000 Seri... | 8     |
| pci:8086-1e25 | Intel       | 7 Series/C210 Series Chip... | 8     |
| pci:8086-1f11 | Intel       | Atom processor C2000 PCIe... | 8     |
| pci:8086-3599 | Intel       | E7520 PCI Express Port C     | 8     |
| pci:8086-3e33 | Intel       | 8th/9th Gen Core Processo... | 8     |
| pci:8086-490f | Intel       | PCI Express Downstream Sw... | 8     |
| pci:8086-4910 | Intel       | PCI Express Upstream Swit... | 8     |
| pci:8086-4c05 | Intel       | Core i7/i5/i3 PCIe Contro... | 8     |
| pci:8086-6f05 | Intel       | Xeon E7 v4/Xeon E5 v4/Xeo... | 8     |
| pci:8086-7ab4 | Intel       | Alder Lake-S PCH PCI Expr... | 8     |
| pci:8086-a151 | Intel       | Sunrise Point-H LPC Contr... | 8     |
| pci:8086-a199 | Intel       | C620 Series Chipset Famil... | 8     |
| pci:8086-a32f | Intel       | Cannon Lake PCH PCI Expre... | 8     |
| pci:1002-5833 | AMD         | RS300 Host Bridge            | 7     |
| pci:1022-7450 | AMD         | AMD-8131 PCI-X Bridge        | 7     |
| pci:1039-0965 | Silicon ... | SiS965 [MuTIOL Media IO]     | 7     |
| pci:10b5-8604 | PLX Tech... | PEX 8604 4-lane, 4-Port P... | 7     |
| pci:10b5-8613 | PLX Tech... | PEX 8613 12-lane, 3-Port ... | 7     |
| pci:10b5-8733 | PLX Tech... | PCI bridge                   | 7     |
| pci:10de-0aaf | Nvidia      | MCP79 LPC Bridge             | 7     |
| pci:10de-0ac5 | Nvidia      | MCP79 PCI Express Bridge     | 7     |
| pci:10de-1ad0 | Nvidia      | Tegra PCIe x8 Endpoint       | 7     |
| pci:1106-0296 | VIA Tech... | P4M800 Host Bridge           | 7     |
| pci:1106-1296 | VIA Tech... | P4M800 Host Bridge           | 7     |
| pci:1106-2296 | VIA Tech... | P4M800 Host Bridge           | 7     |
| pci:1106-3188 | VIA Tech... | VT8385 [K8T800 AGP] Host ... | 7     |
| pci:1106-3296 | VIA Tech... | P4M800 Host Bridge           | 7     |
| pci:1106-4296 | VIA Tech... | P4M800 Host Bridge           | 7     |
| pci:1106-7296 | VIA Tech... | P4M800 Host Bridge           | 7     |
| pci:1106-e353 | VIA Tech... | VX800/820-Series PCI-Expr... | 7     |
| pci:1166-0036 | Broadcom    | BCM5785 [HT1000] PCI/PCI-... | 7     |
| pci:1166-0205 | Broadcom    | BCM5785 [HT1000] Legacy S... | 7     |
| pci:1166-0234 | Broadcom    | BCM5785 [HT1000] LPC         | 7     |
| pci:1217-7113 | O2 Micro    | OZ711EC1 SmartCardBus Con... | 7     |
| pci:1734-9602 | Fujitsu ... | RS780 PCI to PCI Bridge (... | 7     |
| pci:19e5-a120 | Huawei T... | HiSilicon PCIe Root Port ... | 7     |
| pci:19e5-a121 | Huawei T... | HiSilicon PCI-PCI Bridge     | 7     |
| pci:8086-0069 | Intel       | Core Processor DRAM Contr... | 7     |
| pci:8086-06af | Intel       | 400 Series Chipset Family... | 7     |
| pci:8086-19d1 | Intel       | Atom Processor C3000 Seri... | 7     |
| pci:8086-19d2 | Intel       | Atom Processor C3000 Seri... | 7     |
| pci:8086-3598 | Intel       | E7520 PCI Express Port B1    | 7     |
| pci:8086-3eca | Intel       | 8th Gen Core Processor Ho... | 7     |
| pci:8086-438f | Intel       | 500 Series Chipset Family... | 7     |
| pci:8086-4c07 | Intel       | PCI bridge                   | 7     |
| pci:8086-4dba | Intel       | Jasper Lake PCIe Port #3     | 7     |
| pci:8086-7190 | Intel       | 440BX/ZX/DX - 82443BX/ZX/... | 7     |
| pci:8086-7191 | Intel       | 440BX/ZX/DX - 82443BX/ZX/... | 7     |
| pci:8086-7a86 | Intel       | 600 Series Chipset Family... | 7     |
| pci:8086-8cc3 | Intel       | HM97 Chipset LPC Controller  | 7     |
| pci:8086-a399 | Intel       | Comet Lake PCH-V PCIe Por... | 7     |
| pci:10b5-8606 | PLX Tech... | PEX 8606 6 Lane, 6 Port P... | 6     |
| pci:10de-0440 | Nvidia      | MCP65 LPC Bridge             | 6     |
| pci:10de-0779 | Nvidia      | PCI bridge                   | 6     |
| pci:1106-0351 | VIA Tech... | K8T890CF Host Bridge         | 6     |
| pci:1106-1351 | VIA Tech... | VT3351 Host Bridge           | 6     |
| pci:1106-2351 | VIA Tech... | VT3351 Host Bridge           | 6     |
| pci:1106-3205 | VIA Tech... | VT8378 [KM400/A] Chipset ... | 6     |
| pci:1106-3351 | VIA Tech... | VT3351 Host Bridge           | 6     |
| pci:1106-4351 | VIA Tech... | VT3351 Host Bridge           | 6     |
| pci:1106-7351 | VIA Tech... | VT3351 Host Bridge           | 6     |
| pci:1524-1411 | ENE Tech... | CB-710/2/4 Cardbus Contro... | 6     |
| pci:393e-9602 | Unknown     | PCI bridge                   | 6     |
| pci:8086-02bb | Intel       | Comet Lake PCH-LP PCIe Po... | 6     |
| pci:8086-1130 | Intel       | 82815 815 Chipset Host Br... | 6     |
| pci:8086-1131 | Intel       | 82815 815 Chipset AGP Bridge | 6     |
| pci:8086-19a4 | Intel       | Atom Processor C3000 Seri... | 6     |
| pci:8086-25a1 | Intel       | 6300ESB LPC Interface Con... | 6     |
| pci:8086-25ae | Intel       | 6300ESB 64-bit PCI-X Bridge  | 6     |
| pci:8086-590d | Intel       | Kaby Lake-Y Host Bridge/D... | 6     |
| pci:8086-9db5 | Intel       | 300 Series Chipset PCIe P... | 6     |
| pci:8086-a19a | Intel       | C620 Series Chipset Famil... | 6     |
| pci:1002-7010 | AMD         | RS200/RS250 AGP Bridge       | 5     |
| pci:1019-9602 | Elitegro... | Elitegroup PCI bridge        | 5     |
| pci:1039-0646 | Silicon ... | SiS645DX Host & Memory & ... | 5     |
| pci:1039-0741 | Silicon ... | 741/741GX/M741 Host          | 5     |
| pci:1039-0756 | Silicon ... | 755FX CPU to PCI Bridge      | 5     |
| pci:1039-0966 | Silicon ... | SiS966 [MuTIOL Media IO]     | 5     |
| pci:104c-ac54 | Texas In... | PCI1620 PC Card Controller   | 5     |
| pci:106b-0034 | Apple       | UniNorth 2 AGP               | 5     |
| pci:106b-0035 | Apple       | UniNorth 2 PCI               | 5     |
| pci:106b-0036 | Apple       | UniNorth 2 Internal PCI      | 5     |
| pci:10b5-8111 | PLX Tech... | PEX 8111 PCI Express-to-P... | 5     |
| pci:10b5-8603 | PLX Tech... | PEX 8603 3-lane, 3-Port P... | 5     |
| pci:10b9-1563 | ULi Elec... | M1563 HyperTransport Sout... | 5     |
| pci:10b9-1689 | ULi Elec... | M1689 K8 Northbridge [Sup... | 5     |
| pci:10b9-5246 | ULi Elec... | AGP8X Controller             | 5     |
| pci:10de-05b8 | Nvidia      | NF200 PCIe 2.0 switch for... | 5     |
| pci:1106-0238 | VIA Tech... | K8T890 Host Bridge           | 5     |
| pci:1106-1238 | VIA Tech... | K8T890 Host Bridge           | 5     |
| pci:1106-2238 | VIA Tech... | K8T890 Host Bridge           | 5     |
| pci:1106-3238 | VIA Tech... | K8T890 Host Bridge           | 5     |
| pci:1106-4238 | VIA Tech... | K8T890 Host Bridge           | 5     |
| pci:1106-6238 | VIA Tech... | Host bridge                  | 5     |
| pci:1106-6290 | VIA Tech... | K8M890CE Host Bridge         | 5     |
| pci:1106-7238 | VIA Tech... | K8T890 Host Bridge           | 5     |
| pci:1106-f353 | VIA Tech... | VX800/820-Series PCI-Expr... | 5     |
| pci:12d8-2308 | Pericom ... | PI7C9X2G308GP 8-lane PCI ... | 5     |
| pci:1415-9511 | Oxford S... | OX16PCI954 (Quad 16950 UA... | 5     |
| pci:16c3-abcd | Synopsys    | DWC_usb3 / PCIe bridge       | 5     |
| pci:1b21-2824 | ASMedia ... | ASM2824 PCIe Gen3 Packet ... | 5     |
| pci:8086-157e | Intel       | DSL5110 Thunderbolt 2 Bri... | 5     |
| pci:8086-19aa | Intel       | Atom Processor C3000 Seri... | 5     |
| pci:8086-19ab | Intel       | Atom Processor C3000 Seri... | 5     |
| pci:8086-1f13 | Intel       | Atom processor C2000 PCIe... | 5     |
| pci:8086-25d0 | Intel       | 5000Z Chipset Memory Cont... | 5     |
| pci:8086-34b5 | Intel       | Ice Lake-LP PCIe Port #14    | 5     |
| pci:8086-34ba | Intel       | Ice Lake-LP PCI Express R... | 5     |
| pci:8086-3e31 | Intel       | Coffee Lake Host Bridge/D... | 5     |
| pci:8086-4641 | Intel       | 12th Gen Core Processor H... | 5     |
| pci:8086-4dbf | Intel       | Jasper Lake PCIe Port #8     | 5     |
| pci:8086-4e12 | Intel       | Host bridge                  | 5     |
| pci:8086-5182 | Intel       | Alder Lake PCH eSPI Contr... | 5     |
| pci:8086-65c0 | Intel       | 5100 Chipset Memory Contr... | 5     |
| pci:8086-65f0 | Intel       | 5100 Chipset FSB Registers   | 5     |
| pci:8086-65f1 | Intel       | 5100 Chipset Reserved Reg... | 5     |
| pci:8086-65f3 | Intel       | 5100 Chipset Reserved Reg... | 5     |
| pci:8086-65f5 | Intel       | 5100 Chipset DDR Channel ... | 5     |
| pci:8086-65f6 | Intel       | 5100 Chipset DDR Channel ... | 5     |
| pci:0086-0000 | Unknown     | PCI bridge                   | 4     |
| pci:1002-5831 | AMD         | RS300 Host Bridge            | 4     |
| pci:1002-cbb2 | AMD         | RS200 Host Bridge            | 4     |
| pci:1022-1650 | AMD         | Milan Data Fabric; Functi... | 4     |
| pci:1022-1651 | AMD         | Milan Data Fabric; Functi... | 4     |
| pci:1022-1652 | AMD         | Milan Data Fabric; Functi... | 4     |
| pci:1022-1653 | AMD         | Milan Data Fabric; Functi... | 4     |
| pci:1022-1654 | AMD         | Milan Data Fabric; Functi... | 4     |
| pci:1022-1655 | AMD         | Milan Data Fabric; Functi... | 4     |
| pci:1022-1656 | AMD         | Milan Data Fabric; Functi... | 4     |
| pci:1022-1657 | AMD         | Milan Data Fabric; Functi... | 4     |
| pci:1039-0655 | Silicon ... | 655 Host                     | 4     |
| pci:104c-8232 | Texas In... | XIO3130 PCI Express Switc... | 4     |
| pci:104c-8233 | Texas In... | XIO3130 PCI Express Switc... | 4     |
| pci:104c-ac42 | Texas In... | PCI4451 PC card Cardbus C... | 4     |
| pci:104c-ac51 | Texas In... | PCI1420 PC card Cardbus C... | 4     |
| pci:10b5-8518 | PLX Tech... | PEX 8518 16-lane, 5-port ... | 4     |
| pci:10b5-8547 | PLX Tech... | PEX 8547 48-lane, 3-port ... | 4     |
| pci:10b5-8724 | PLX Tech... | PEX 8724 24-Lane, 6-Port ... | 4     |
| pci:10b9-1533 | ULi Elec... | M1533/M1535/M1543 PCI to ... | 4     |
| pci:10b9-524b | ULi Elec... | PCI Express Root Port        | 4     |
| pci:10b9-524c | ULi Elec... | PCI Express Root Port        | 4     |
| pci:10b9-524d | ULi Elec... | PCI Express Root Port        | 4     |
| pci:111d-8060 | Microsem... | PES16T4G2 PCI Express Gen... | 4     |
| pci:111d-806c | Microsem... | PES16T4A/4T4G2 PCI Expres... | 4     |
| pci:12d8-8140 | Pericom ... | PI7C8140A PCI-to-PCI Bridge  | 4     |
| pci:12d8-b608 | Pericom ... | Pericom PCI bridge           | 4     |
| pci:17cd-dc01 | Cadence ... | Cadence Design PCI bridge    | 4     |
| pci:17cd-dc16 | Cadence ... | Cadence Design PCI bridge    | 4     |
| pci:1b21-1806 | ASMedia ... | PCI bridge                   | 4     |
| pci:1b21-2812 | ASMedia ... | PCI bridge                   | 4     |
| pci:1d39-8060 | Unknown     | PCI bridge                   | 4     |
| pci:8086-06ae | Intel       | 400 Series Chipset Family... | 4     |
| pci:8086-0998 | Intel       | Host bridge                  | 4     |
| pci:8086-1460 | Intel       | 82870P2 P64H2 Hub PCI Bridge | 4     |
| pci:8086-1569 | Intel       | DSL4510 Thunderbolt Bridg... | 4     |
| pci:8086-1900 | Intel       | Xeon E3-1200 v5/E3-1500 v... | 4     |
| pci:8086-19a8 | Intel       | Atom Processor C3000 Seri... | 4     |
| pci:8086-1f01 | Intel       | Atom processor C2000 SoC ... | 4     |
| pci:8086-277a | Intel       | 82975X/3010 PCI Express R... | 4     |
| pci:8086-2e41 | Intel       | 4 Series Chipset PCI Expr... | 4     |
| pci:8086-3575 | Intel       | 82830M/MG/MP Host Bridge     | 4     |
| pci:8086-3576 | Intel       | 82830M/MP AGP Bridge         | 4     |
| pci:8086-37c2 | Intel       | PCI bridge                   | 4     |
| pci:8086-37c4 | Intel       | PCI bridge                   | 4     |
| pci:8086-4384 | Intel       | 500 Series Chipset Family... | 4     |
| pci:8086-43b7 | Intel       | 500 Series Chipset Family... | 4     |
| pci:8086-4e28 | Intel       | Host bridge                  | 4     |
| pci:8086-65e5 | Intel       | 5100 Chipset PCI Express ... | 4     |
| pci:8086-65e7 | Intel       | 5100 Chipset PCI Express ... | 4     |
| pci:8086-7abd | Intel       | Alder Lake-S PCH PCI Expr... | 4     |
| pci:8086-a1c8 | Intel       | ISA bridge                   | 4     |
| pci:8086-a1e7 | Intel       | C620 Series Chipset Famil... | 4     |
| pci:8086-a1e9 | Intel       | C620 Series Chipset Famil... | 4     |
| pci:8086-a29f | Intel       | 200 Series PCH PCI Expres... | 4     |
| pci:8086-a30c | Intel       | QM370 Chipset LPC/eSPI Co... | 4     |
| pci:8086-a315 | Intel       | 300 Series Chipset Family... | 4     |
| pci:1002-5a35 | AMD         | PCI bridge                   | 3     |
| pci:1022-149a | AMD         | Starship PCIe GPP Bridge ... | 3     |
| pci:1039-0961 | Silicon ... | SiS961 [MuTIOL Media IO]     | 3     |
| pci:104c-ac47 | Texas In... | PCI7510 PC card Cardbus C... | 3     |
| pci:104c-ac4a | Texas In... | PCI7510/7610 CardBus Bridge  | 3     |
| pci:10b5-8609 | PLX Tech... | PEX 8609 8-lane, 8-Port P... | 3     |
| pci:10b5-8732 | PLX Tech... | PEX 8732 32-lane, 8-Port ... | 3     |
| pci:10b5-8796 | PLX Tech... | PCI bridge                   | 3     |
| pci:10de-05b9 | Nvidia      | PCIe Gen 2 (5.0 GT/s) Bri... | 3     |
| pci:10de-0802 | Nvidia      | nForce 790i Host Bridge      | 3     |
| pci:10de-0ac8 | Nvidia      | MCP79 PCI Express Bridge     | 3     |
| pci:1106-0686 | VIA Tech... | VT82C686 [Apollo Super So... | 3     |
| pci:1106-0691 | VIA Tech... | VT82C693A/694x [Apollo PR... | 3     |
| pci:1106-3168 | VIA Tech... | P4X333/P4X400/PT800 AGP B... | 3     |
| pci:1106-8598 | VIA Tech... | VT82C598/694x [Apollo MVP... | 3     |
| pci:1106-b168 | VIA Tech... | VT8235 PCI Bridge            | 3     |
| pci:1106-c353 | VIA Tech... | VX800/820-Series PCI-Expr... | 3     |
| pci:111d-801c | Integrat... | PES24N3A PCI Express Switch  | 3     |
| pci:111d-8063 | Microsem... | PCI bridge                   | 3     |
| pci:111d-806e | Microsem... | PES24T6G2 PCI Express Gen... | 3     |
| pci:111d-806f | Integrat... | HIO524G2 PCI Express Gen2... | 3     |
| pci:1166-0130 | Broadcom    | BCM5780 [HT2000] PCI-X br... | 3     |
| pci:1166-0132 | Broadcom    | BCM5780 [HT2000] PCI-Expr... | 3     |
| pci:1166-0140 | Broadcom    | HT2100 PCI-Express Bridge    | 3     |
| pci:1166-0142 | Broadcom    | HT2100 PCI-Express Bridge    | 3     |
| pci:1166-0144 | Broadcom    | HT2100 PCI-Express Bridge    | 3     |
| pci:1217-6933 | O2 Micro    | OZ6933/711E1 CardBus/Smar... | 3     |
| pci:1217-7223 | O2 Micro    | OZ711M3/MC3 4-in-1 Memory... | 3     |
| pci:12d8-e110 | Pericom ... | PI7C9X110 PCI Express to ... | 3     |
| pci:1668-0100 | Actionte... | Mini-PCI bridge              | 3     |
| pci:17cb-0300 | Qualcomm    | MDM9x35 LTE Modem [Snapdr... | 3     |
| pci:19e5-371e | Huawei T... | Hi1822 Family Virtual Bridge | 3     |
| pci:1b0a-9602 | Pegatron    | PCI bridge                   | 3     |
| pci:1b21-1812 | ASMedia ... | PCI bridge                   | 3     |
| pci:1d17-0717 | Zhaoxin     | ZX-D/ZX-E PCI Express Roo... | 3     |
| pci:1d17-071b | Zhaoxin     | ZX-D/ZX-E PCI Express Roo... | 3     |
| pci:1d17-071c | Zhaoxin     | ZX-D/ZX-E PCI Express Roo... | 3     |
| pci:1d17-071d | Zhaoxin     | ZX-D/ZX-E PCI Express Roo... | 3     |
| pci:1d17-071e | Zhaoxin     | ZX-D/ZX-E PCI Express Roo... | 3     |
| pci:1d17-1001 | Zhaoxin     | ZX-D/ZX-E Miscellaneous Bus  | 3     |
| pci:1d17-1003 | Zhaoxin     | ZX-E Standard Host Bridge    | 3     |
| pci:1d17-31b0 | Zhaoxin     | ZX-100/ZX-D Standard Host... | 3     |
| pci:1d17-31b1 | Zhaoxin     | ZX-100/ZX-D Standard Host... | 3     |
| pci:1d17-31b2 | Zhaoxin     | ZX-100/ZX-D DRAM Controller  | 3     |
| pci:1d17-31b3 | Zhaoxin     | ZX-100/ZX-D Power Managem... | 3     |
| pci:1d17-31b4 | Zhaoxin     | ZX-100/ZX-D I/O APIC         | 3     |
| pci:1d17-31b5 | Zhaoxin     | ZX-100/ZX-D Scratch Device   | 3     |
| pci:1d17-31b7 | Zhaoxin     | ZX-100/ZX-D/ZX-E Standard... | 3     |
| pci:8086-0048 | Intel       | Core Processor DRAM Contr... | 3     |
| pci:8086-0330 | Intel       | 80332 [Dobson] I/O proces... | 3     |
| pci:8086-0332 | Intel       | 80332 [Dobson] I/O proces... | 3     |
| pci:8086-0817 | Intel       | Medfield Serial IO I2C Co... | 3     |
| pci:8086-1f02 | Intel       | Atom processor C2000 SoC ... | 3     |
| pci:8086-1f08 | Intel       | Atom processor C2000 SoC ... | 3     |
| pci:8086-29f9 | Intel       | 3210 Chipset Host-Seconda... | 3     |
| pci:8086-3581 | Intel       | 82852/82855 GM/GME/PM/GMV... | 3     |
| pci:8086-37c3 | Intel       | PCI bridge                   | 3     |
| pci:8086-4110 | Intel       | SM35 Chipset PCI Host Bridge | 3     |
| pci:8086-4650 | Intel       | Host bridge                  | 3     |
| pci:8086-466e | Intel       | Alder Lake-P Thunderbolt ... | 3     |
| pci:8086-4dbd | Intel       | Jasper Lake PCIe Port #6     | 3     |
| pci:8086-4e24 | Intel       | Host bridge                  | 3     |
| pci:8086-51bf | Intel       | Alder Lake PCH-P PCI Expr... | 3     |
| pci:8086-65e3 | Intel       | 5100 Chipset PCI Express ... | 3     |
| pci:8086-65f9 | Intel       | 5100 Chipset PCI Express ... | 3     |
| pci:8086-7ab1 | Intel       | 600 Series Chipset Family... | 3     |
| pci:8086-9dbd | Intel       | 300 Series Chipset PCIe P... | 3     |
| pci:0014-7a00 | Loongson... | Hyper Transport Bridge Co... | 2     |
| pci:0014-7a09 | Loongson... | PCI-to-PCI Bridge            | 2     |
| pci:0014-7a0c | Loongson... | LPC Controller               | 2     |
| pci:1014-04c1 | IBM         | POWER9 Host Bridge (PHB4)    | 2     |
| pci:1022-142e | AMD         | Liverpool Processor HT co... | 2     |
| pci:1022-142f | AMD         | Liverpool Processor Addre... | 2     |
| pci:1022-1430 | AMD         | Liverpool Processor DRAM ... | 2     |
| pci:1022-1431 | AMD         | Liverpool Processor Misc ... | 2     |
| pci:1022-1432 | AMD         | Liverpool Processor PM co... | 2     |
| pci:1022-1433 | AMD         | Liverpool Processor NB Pe... | 2     |
| pci:1022-1434 | AMD         | Liverpool Processor SPLL ... | 2     |
| pci:1022-1436 | AMD         | Liverpool Processor Root ... | 2     |
| pci:1022-1438 | AMD         | Liverpool UMI PCIe Dummy ... | 2     |
| pci:1022-1516 | AMD         | Family 14h Processor Root... | 2     |
| pci:1022-7460 | AMD         | AMD-8111 PCI                 | 2     |
| pci:1022-7468 | AMD         | AMD-8111 LPC                 | 2     |
| pci:1022-746b | AMD         | AMD-8111 ACPI                | 2     |
| pci:1039-0662 | Silicon ... | 662 Host                     | 2     |
| pci:1039-0746 | Silicon ... | 746 Host                     | 2     |
| pci:104c-ac16 | Texas In... | PCI1250                      | 2     |
| pci:104c-ac23 | Texas In... | PCI2250 PCI-to-PCI Bridge    | 2     |
| pci:10b5-3381 | PLX Tech... | PCI bridge                   | 2     |
| pci:10b5-8508 | PLX Tech... | PEX 8508 8-lane, 5-port P... | 2     |
| pci:10b5-8632 | PLX Tech... | PEX 8632 32-lane, 12-Port... | 2     |
| pci:10b5-9030 | PLX Tech... | PCI9030 32-bit 33MHz PCI ... | 2     |
| pci:10b5-9765 | PLX Tech... | PCI bridge                   | 2     |
| pci:10b5-9797 | PLX Tech... | PCI bridge                   | 2     |
| pci:10b9-1695 | ULi Elec... | M1695 Host Bridge            | 2     |
| pci:10b9-1697 | ULi Elec... | M1697 HTT Host Bridge        | 2     |
| pci:10b9-524e | ULi Elec... | PCI Express Root Port        | 2     |
| pci:10de-0030 | Nvidia      | nForce4 Intel Edition LPC... | 2     |
| pci:10de-003d | Nvidia      | MCP04 PCI Bridge             | 2     |
| pci:10de-0080 | Nvidia      | MCP2A ISA bridge             | 2     |
| pci:10de-008b | Nvidia      | MCP2A PCI Bridge             | 2     |
| pci:10de-07c2 | Nvidia      | MCP73 Host Bridge            | 2     |
| pci:10de-1ad2 | Nvidia      | Tegra PCIe x1 Root Complex   | 2     |
| pci:1106-3074 | VIA Tech... | VT8233 PCI to ISA Bridge     | 2     |
| pci:1106-3147 | VIA Tech... | VT8233A ISA Bridge           | 2     |
| pci:1106-3156 | VIA Tech... | P/KN266 Host Bridge          | 2     |
| pci:111d-802d | Integrat... | PES16T7 PCI Express Switch   | 2     |
| pci:111d-802e | Microsem... | PES24T6 PCI Express Switch   | 2     |
| pci:1166-0009 | Broadcom    | CNB20LE Host Bridge          | 2     |
| pci:1166-0101 | Broadcom    | CIOB-X2 PCI-X I/O Bridge     | 2     |
| pci:1166-0200 | Broadcom    | OSB4 South Bridge            | 2     |
| pci:1166-0201 | Broadcom    | CSB5 South Bridge            | 2     |
| pci:1166-0225 | Broadcom    | CSB5 LPC bridge              | 2     |
| pci:11f8-8533 | PMC-Sierra  | PM8533 PFX 48xG3 PCIe Fan... | 2     |
| pci:1217-7114 | O2 Micro    | OZ711M1/MC1 4-in-1 Memory... | 2     |
| pci:1283-8888 | Integrat... | IT8888F/G PCI to ISA Brid... | 2     |
| pci:1297-9602 | Holco En... | Holco Enterprise Co, Ltd/... | 2     |
| pci:12d8-8150 | Pericom ... | PCI to PCI Bridge            | 2     |
| pci:12d8-b304 | Pericom ... | Pericom PCI bridge           | 2     |
| pci:144d-a544 | Samsung ... | Exynos 8890 PCIe Root Com... | 2     |
| pci:144d-ecec | Samsung ... | Exynos 8895 PCIe Root Com... | 2     |
| pci:17cb-0104 | Qualcomm    | PCI bridge                   | 2     |
| pci:17cd-dc08 | Cadence ... | Cadence Design PCI bridge    | 2     |
| pci:1b72-9602 | Unknown     | PCI bridge                   | 2     |
| pci:3388-0022 | Hint        | HB4 PCI-PCI Bridge (PCI6150) | 2     |
| pci:8086-0049 | Intel       | Core Processor PCI Expres... | 2     |
| pci:8086-006a | Intel       | Host bridge                  | 2     |
| pci:8086-0335 | Intel       | 80331 [Lindsay] I/O proce... | 2     |
| pci:8086-0681 | Intel       | 400 Series Chipset Family... | 2     |
| pci:8086-06ad | Intel       | 400 Series Chipset Family... | 2     |
| pci:8086-151b | Intel       | CVL2510 Thunderbolt Contr... | 2     |
| pci:8086-1567 | Intel       | DSL4410 Thunderbolt Bridg... | 2     |
| pci:8086-1618 | Intel       | Broadwell-U Host Bridge -... | 2     |
| pci:8086-19a5 | Intel       | Atom Processor C3000 Seri... | 2     |
| pci:8086-19a6 | Intel       | Atom Processor C3000 Seri... | 2     |
| pci:8086-19a9 | Intel       | Atom Processor C3000 Seri... | 2     |
| pci:8086-1b81 | Intel       | ISA bridge                   | 2     |
| pci:8086-1bbd | Intel       | PCI bridge                   | 2     |
| pci:8086-1bbf | Intel       | PCI bridge                   | 2     |
| pci:8086-1bfe | Intel       | Host bridge                  | 2     |
| pci:8086-203f | Intel       | PCI bridge                   | 2     |
| pci:8086-2480 | Intel       | 82801CA LPC Interface Con... | 2     |
| pci:8086-2532 | Intel       | 82850 850 (Tehama) Chipse... | 2     |
| pci:8086-2550 | Intel       | E7505 Memory Controller Hub  | 2     |
| pci:8086-2552 | Intel       | E7505/E7205 PCI-to-AGP Br... | 2     |
| pci:8086-2553 | Intel       | E7505 Hub Interface B PCI... | 2     |
| pci:8086-347a | Intel       | PCI bridge                   | 2     |
| pci:8086-352a | Intel       | PCI bridge                   | 2     |
| pci:8086-3592 | Intel       | E7320 Memory Controller Hub  | 2     |
| pci:8086-359a | Intel       | E7520 PCI Express Port C1    | 2     |
| pci:8086-3600 | Intel       | 7300 Chipset Memory Contr... | 2     |
| pci:8086-3604 | Intel       | 7300 Chipset PCI Express ... | 2     |
| pci:8086-3605 | Intel       | 7300 Chipset PCI Express ... | 2     |
| pci:8086-3606 | Intel       | 7300 Chipset PCI Express ... | 2     |
| pci:8086-3607 | Intel       | 7300 Chipset PCI Express ... | 2     |
| pci:8086-3609 | Intel       | 7300 Chipset PCI Express ... | 2     |
| pci:8086-360c | Intel       | 7300 Chipset FSB Registers   | 2     |
| pci:8086-360d | Intel       | 7300 Chipset Snoop Filter... | 2     |
| pci:8086-360e | Intel       | 7300 Chipset Debug and Mi... | 2     |
| pci:8086-360f | Intel       | 7300 Chipset FBD Branch 0... | 2     |
| pci:8086-3610 | Intel       | 7300 Chipset FBD Branch 1... | 2     |
| pci:8086-3887 | Intel       | LPC Controller               | 2     |
| pci:8086-3b12 | Intel       | 3400 Series Chipset LPC I... | 2     |
| pci:8086-4027 | Intel       | 5400 Chipset PCI Express ... | 2     |
| pci:8086-43c1 | Intel       | 500 Series Chipset Family... | 2     |
| pci:8086-4630 | Intel       | Host bridge                  | 2     |
| pci:8086-463d | Intel       | 12th Gen Core Processor P... | 2     |
| pci:8086-51bc | Intel       | PCI bridge                   | 2     |
| pci:8086-5a04 | Intel       | Host bridge                  | 2     |
| pci:8086-65e2 | Intel       | 5100 Chipset PCI Express ... | 2     |
| pci:8086-65f7 | Intel       | 5100 Chipset PCI Express ... | 2     |
| pci:8086-65f8 | Intel       | 5100 Chipset PCI Express ... | 2     |
| pci:8086-65fa | Intel       | 5100 Chipset PCI Express ... | 2     |
| pci:8086-7100 | Intel       | 430TX - 82439TX MTXC         | 2     |
| pci:8086-780a | Intel       | Xeon Phi x200 product fam... | 2     |
| pci:8086-7a85 | Intel       | 600 Series Chipset Family... | 2     |
| pci:8086-7abf | Intel       | 600 Series Chipset Family... | 2     |
| pci:8086-8a16 | Intel       | Host bridge                  | 2     |
| pci:8086-9800 | Intel       | Host bridge                  | 2     |
| pci:8086-9885 | Intel       | LPC Controller               | 2     |
| pci:8086-98bc | Intel       | PCIe Port #5                 | 2     |
| pci:8086-a0b9 | Intel       | PCI bridge                   | 2     |
| pci:8086-a168 | Intel       | 100 Series/C230 Series Ch... | 2     |
| pci:8086-a1cb | Intel       | ISA bridge                   | 2     |
| pci:8086-a1ea | Intel       | C620 Series Chipset Famil... | 2     |
| pci:8086-a2d4 | Intel       | 200 Series Chipset Family... | 2     |
| pci:8086-b152 | Intel       | 21152 PCI-to-PCI Bridge      | 2     |
| pci:8087-1136 |             | PCI bridge                   | 2     |
| pci:80bb-1045 | Unknown     | Bridge                       | 2     |
| pci:0014-7a19 | Loongson... | PCI-to-PCI Bridge            | 1     |
| pci:1002-1470 | AMD         | PCI bridge                   | 1     |
| pci:1002-1471 | AMD         | PCI bridge                   | 1     |
| pci:1002-4243 | AMD         | R200 PCI Bridge [All-in-W... | 1     |
| pci:1002-5981 | AMD         | RD790 PCI to PCI bridge (... | 1     |
| pci:1002-5a22 | AMD         | SR56X0 Host Bridge Clock ... | 1     |
| pci:1002-cab3 | AMD         | RS250 Host Bridge            | 1     |
| pci:1011-0001 | Digital ... | DECchip 21050                | 1     |
| pci:1011-0022 | Digital ... | DECchip 21150                | 1     |
| pci:1011-0024 | Digital ... | DECchip 21152                | 1     |
| pci:1014-0188 | IBM         | EADS-X PCI-X to PCI-X Bridge | 1     |
| pci:1022-13e0 | AMD         | Ariel Root Complex           | 1     |
| pci:1022-13e2 | AMD         | Ariel PCIe Dummy Host Bridge | 1     |
| pci:1022-13e5 | AMD         | Ariel Internal PCIe GPP B... | 1     |
| pci:1022-13f0 | AMD         | Ariel Device 24: Function 0  | 1     |
| pci:1022-13f1 | AMD         | Ariel Device 24: Function 1  | 1     |
| pci:1022-13f2 | AMD         | Ariel Device 24: Function 2  | 1     |
| pci:1022-13f3 | AMD         | Ariel Device 24: Function 3  | 1     |
| pci:1022-13f4 | AMD         | Ariel Device 24: Function 4  | 1     |
| pci:1022-13f5 | AMD         | Ariel Device 24: Function 5  | 1     |
| pci:1022-13f6 | AMD         | Ariel Device 24: Function 6  | 1     |
| pci:1022-13f7 | AMD         | Ariel Device 24: Function 7  | 1     |
| pci:1022-1540 | AMD         | Kryptos/Cato/Garfield/Gar... | 1     |
| pci:1022-1541 | AMD         | Kryptos/Cato/Garfield/Gar... | 1     |
| pci:1022-1542 | AMD         | Kryptos/Cato/Garfield/Gar... | 1     |
| pci:1022-1543 | AMD         | Kryptos/Cato/Garfield/Gar... | 1     |
| pci:1022-1544 | AMD         | Kryptos/Cato/Garfield/Gar... | 1     |
| pci:1022-1545 | AMD         | Kryptos/Cato/Garfield/Gar... | 1     |
| pci:1022-1546 | AMD         | Kryptos/Cato/Garfield/Gar... | 1     |
| pci:1022-1548 | AMD         | Kryptos/Cato/Garfield/Gar... | 1     |
| pci:1022-1a00 | AMD         | Host bridge                  | 1     |
| pci:1022-1a01 | AMD         | Host bridge                  | 1     |
| pci:1022-1a02 | AMD         | PCI bridge                   | 1     |
| pci:1022-2080 | AMD         | CS5536 [Geode companion] ... | 1     |
| pci:1022-2090 | AMD         | CS5536 [Geode companion] ISA | 1     |
| pci:1022-700c | AMD         | AMD-760 MP [IGD4-2P] Syst... | 1     |
| pci:1022-700d | AMD         | AMD-760 MP [IGD4-2P] AGP ... | 1     |
| pci:1022-7440 | AMD         | AMD-768 [Opus] ISA           | 1     |
| pci:1022-7443 | AMD         | AMD-768 [Opus] ACPI          | 1     |
| pci:1022-7448 | AMD         | AMD-768 [Opus] PCI           | 1     |
| pci:1022-7454 | AMD         | AMD-8151 System Controller   | 1     |
| pci:1022-7455 | AMD         | AMD-8151 AGP Bridge          | 1     |
| pci:1022-7458 | AMD         | AMD-8132 PCI-X Bridge        | 1     |
| pci:1022-opus | AMD         | AMD-768 PCI [7448]           | 1     |
| pci:1022-o... | AMD         | AMD-768 USB [7449]           | 1     |
| pci:1039-0649 | Silicon ... | SiS649 Host                  | 1     |
| pci:1039-0755 | Silicon ... | 755 Host                     | 1     |
| pci:104c-ac1b | Texas In... | PCI1450                      | 1     |
| pci:104c-ac28 | Texas In... | PCI2050 PCI-to-PCI Bridge    | 1     |
| pci:1050-0628 | Winbond ... | Electronics ISA bridge       | 1     |
| pci:1050-5868 | Winbond ... | Electronics PCI bridge       | 1     |
| pci:105b-9602 | Foxconn ... | PCI bridge                   | 1     |
| pci:106b-002d | Apple       | UniNorth 1.5 AGP             | 1     |
| pci:106b-002e | Apple       | UniNorth 1.5 PCI             | 1     |
| pci:106b-002f | Apple       | UniNorth 1.5 Internal PCI    | 1     |
| pci:106b-0045 | Apple       | K2 HT-PCI Bridge             | 1     |
| pci:106b-0046 | Apple       | K2 HT-PCI Bridge             | 1     |
| pci:106b-0047 | Apple       | K2 HT-PCI Bridge             | 1     |
| pci:106b-0048 | Apple       | K2 HT-PCI Bridge             | 1     |
| pci:106b-0049 | Apple       | K2 HT-PCI Bridge             | 1     |
| pci:106b-004a | Apple       | CPC945 HT Bridge             | 1     |
| pci:106b-004b | Apple       | U3 AGP                       | 1     |
| pci:106b-0053 | Apple       | Shasta PCI Bridge            | 1     |
| pci:106b-0054 | Apple       | Shasta PCI Bridge            | 1     |
| pci:106b-0055 | Apple       | Shasta PCI Bridge            | 1     |
| pci:106b-0056 | Apple       | U4 PCIe                      | 1     |
| pci:106b-0058 | Apple       | U3L AGP Bridge               | 1     |
| pci:10b5-8505 | PLX Tech... | PEX 8505 5-lane, 5-port P... | 1     |
| pci:10b5-8517 | PLX Tech... | PEX 8517 16-lane, 5-port ... | 1     |
| pci:10b5-8614 | PLX Tech... | PEX 8614 12-lane, 12-Port... | 1     |
| pci:10b5-8616 | PLX Tech... | PEX 8616 16-lane, 4-Port ... | 1     |
| pci:10b5-86e1 | PLX Tech... | Bridge                       | 1     |
| pci:10b5-8717 | PLX Tech... | PEX 8717 16-lane, 8-Port ... | 1     |
| pci:10b5-8725 | PLX Tech... | PEX 8725 24-Lane, 10-Port... | 1     |
| pci:10b5-8748 | PLX Tech... | PEX 8748 48-Lane, 12-Port... | 1     |
| pci:10b5-8749 | PLX Tech... | PEX 8749 48-Lane, 18-Port... | 1     |
| pci:10b5-87b0 | PLX Tech... | PEX PCI Express Switch NT... | 1     |
| pci:10c5-0018 | Xerox       | Bridge                       | 1     |
| pci:10de-0070 | Nvidia      | nForce4 Intel Edition CPU... | 1     |
| pci:10de-03a2 | Nvidia      | C55 Host Bridge              | 1     |
| pci:10de-07c0 | Nvidia      | MCP73 Host Bridge            | 1     |
| pci:10de-0816 | Nvidia      | nForce 790i PCIe Bridge 2    | 1     |
| pci:10de-0818 | Nvidia      | nForce 790i PCIe Bridge 4    | 1     |
| pci:10de-0819 | Nvidia      | PCI bridge                   | 1     |
| pci:10e8-e004 | Applied ... | X-Gene PCIe bridge           | 1     |
| pci:1106-0305 | VIA Tech... | VT8363/8365 [KT133/KM133]    | 1     |
| pci:1106-0409 | VIA Tech... | VX855/VX875 Host Bridge: ... | 1     |
| pci:1106-0596 | VIA Tech... | VT82C596 ISA [Mobile South]  | 1     |
| pci:1106-1409 | VIA Tech... | VX855/VX875 Error Reporting  | 1     |
| pci:1106-2409 | VIA Tech... | VX855/VX875 Host Bus Control | 1     |
| pci:1106-3050 | VIA Tech... | VT82C596 Power Management    | 1     |
| pci:1106-3116 | VIA Tech... | VT8375 [KM266/KL266] Host... | 1     |
| pci:1106-3128 | VIA Tech... | VT8753 [P4X266 AGP]          | 1     |
| pci:1106-3409 | VIA Tech... | VX855/VX875 DRAM Bus Control | 1     |
| pci:1106-4409 | VIA Tech... | VX855/VX875 Power Managem... | 1     |
| pci:1106-6409 | VIA Tech... | VX855/VX875 Scratch Regis... | 1     |
| pci:1106-7409 | VIA Tech... | VX855/VX875 North-South M... | 1     |
| pci:1106-8305 | VIA Tech... | VT8363/8365 [KT133/KM133 ... | 1     |
| pci:1106-8409 | VIA Tech... | VX855/VX875 Bus Control a... | 1     |
| pci:111d-802b | Microsem... | PES8T5A PCI Express Switch   | 1     |
| pci:111d-803a | Microsem... | PES4T4 PCI Express Switch    | 1     |
| pci:1137-0040 | Cisco Sy... | VIC PCIe Upstream Port       | 1     |
| pci:1137-0041 | Cisco Sy... | VIC PCIe Downstream Port     | 1     |
| pci:1137-007a | Cisco Sy... | VIC 1300 PCIe Upstream Port  | 1     |
| pci:1166-0000 | Broadcom    | CMIC-LE                      | 1     |
| pci:1166-0012 | Broadcom    | CMIC-WS Host Bridge (GC-L... | 1     |
| pci:1166-0017 | Broadcom    | GCNB-LE Host Bridge          | 1     |
| pci:11ab-0110 | Marvell ... | 88F60x0/88F70x0/88F80x0/C... | 1     |
| pci:11ab-2211 | Marvell ... | 88SB2211 PCI Express to P... | 1     |
| pci:11ab-6282 | Marvell ... | Marvell PCI bridge           | 1     |
| pci:1217-6130 | O2 Micro    | Bridge                       | 1     |
| pci:1217-6134 | O2 Micro    | CardBus bridge               | 1     |
| pci:12d8-0303 | Pericom ... | PCI Express Switch 3-3       | 1     |
| pci:12d8-8152 | Pericom ... | PI7C8152A/PI7C8152B/PI7C8... | 1     |
| pci:12d8-8608 | Pericom ... | Pericom PCI bridge           | 1     |
| pci:144d-a575 | Samsung ... | Electronics PCI bridge       | 1     |
| pci:14f1-2e00 | Conexant... | Conexant Bridge              | 1     |
| pci:1524-1420 | ENE Tech... | CB1420 Cardbus Controller    | 1     |
| pci:15b3-5a46 | Mellanox... | MT23108 PCI Bridge           | 1     |
| pci:15ec-3101 | Beckhoff    | FC3101 Profibus DP 1 Chan... | 1     |
| pci:17cb-0105 | Qualcomm    | MSM8998 PCIe Root Complex    | 1     |
| pci:17cb-010b | Qualcomm    | PCI bridge                   | 1     |
| pci:1957-0086 | Freescal... | MPC8343E                     | 1     |
| pci:19e5-1610 | Huawei T... | PCI bridge                   | 1     |
| pci:1aed-2100 | SanDisk     | PCI bridge                   | 1     |
| pci:1d17-0718 | Zhaoxin     | ZX-D/ZX-E PCI Express Roo... | 1     |
| pci:1d17-0719 | Zhaoxin     | ZX-D/ZX-E PCI Express Roo... | 1     |
| pci:1d17-071a | Zhaoxin     | ZX-D/ZX-E PCI Express Roo... | 1     |
| pci:1fc8-0820 | Lucid In... | LT22102 3-way 16-lane PCI... | 1     |
| pci:1fc8-08a0 | Lucid In... | LT22102 3-way 16-lane PCI... | 1     |
| pci:1fc8-0920 | Lucid In... | LT22102 3-way 16-lane PCI... | 1     |
| pci:1fc8-0960 | Lucid In... | LT22102 3-way 16-lane PCI... | 1     |
| pci:1fff-8000 | MCST        | PCI Bridge                   | 1     |
| pci:1fff-8010 | MCST        | PCI-Express x4               | 1     |
| pci:1fff-8011 | MCST        | PCI-Express x16              | 1     |
| pci:1fff-8017 | MCST        | Virtual-Bridge               | 1     |
| pci:3388-0026 | Hint        | HB2 PCI-PCI Bridge           | 1     |
| pci:8086-004b | Intel       | Core Processor Secondary ... | 1     |
| pci:8086-1170 | Intel       | Host bridge                  | 1     |
| pci:8086-1360 | Intel       | 82806AA PCI64 Hub PCI Bridge | 1     |
| pci:8086-19a7 | Intel       | Atom Processor C3000 Seri... | 1     |
| pci:8086-1ad6 | Intel       | PCI bridge                   | 1     |
| pci:8086-1af0 | Intel       | Host bridge                  | 1     |
| pci:8086-1bb1 | Intel       | PCI bridge                   | 1     |
| pci:8086-1c25 | Intel       | 6 Series/C200 Series Chip... | 1     |
| pci:8086-1c43 | Intel       | Mobile 6 Series Chipset F... | 1     |
| pci:8086-1d40 | Intel       | C600/X79 series chipset L... | 1     |
| pci:8086-1f0b | Intel       | Atom processor C2000 SoC ... | 1     |
| pci:8086-1f0c | Intel       | Atom processor C2000 SoC ... | 1     |
| pci:8086-1f0e | Intel       | Atom processor C2000 SoC ... | 1     |
| pci:8086-2410 | Intel       | 82801AA ISA Bridge (LPC)     | 1     |
| pci:8086-2418 | Intel       | 82801AA PCI Bridge           | 1     |
| pci:8086-244c | Intel       | 82801BAM ISA Bridge (LPC)    | 1     |
| pci:8086-2530 | Intel       | 82850 850 (Tehama) Chipse... | 1     |
| pci:8086-2531 | Intel       | 82860 860 (Wombat) Chipse... | 1     |
| pci:8086-2533 | Intel       | 82860 860 (Wombat) Chipse... | 1     |
| pci:8086-2540 | Intel       | E7500 Memory Controller Hub  | 1     |
| pci:8086-2543 | Intel       | E7500/E7501 Hub Interface... | 1     |
| pci:8086-2545 | Intel       | E7500/E7501 Hub Interface... | 1     |
| pci:8086-254c | Intel       | E7501 Memory Controller Hub  | 1     |
| pci:8086-2554 | Intel       | E7505 Hub Interface B PCI... | 1     |
| pci:8086-2588 | Intel       | E7220/E7221 Memory Contro... | 1     |
| pci:8086-2589 | Intel       | E7220/E7221 PCI Express R... | 1     |
| pci:8086-27ad | Intel       | Mobile 945GSE Express PCI... | 1     |
| pci:8086-27d1 | Intel       | PCI bridge                   | 1     |
| pci:8086-27d3 | Intel       | PCI bridge                   | 1     |
| pci:8086-2910 | Intel       | 82801IB/IR/IH (ICH9 Famil... | 1     |
| pci:8086-347b | Intel       | PCI bridge                   | 1     |
| pci:8086-347c | Intel       | PCI bridge                   | 1     |
| pci:8086-347d | Intel       | PCI bridge                   | 1     |
| pci:8086-35b0 | Intel       | 3100 Chipset Memory I/O C... | 1     |
| pci:8086-35b6 | Intel       | 3100 Chipset PCI Express ... | 1     |
| pci:8086-35b7 | Intel       | 3100 Chipset PCI Express ... | 1     |
| pci:8086-3701 | Intel       | Xeon C5500/C3500 DMI         | 1     |
| pci:8086-3720 | Intel       | Xeon C5500/C3500 PCI Expr... | 1     |
| pci:8086-3721 | Intel       | Xeon C5500/C3500 PCI Expr... | 1     |
| pci:8086-3a7a | Intel       | 82801JD/DO (ICH10 Family)... | 1     |
| pci:8086-4390 | Intel       | 500 Series Chipset Family... | 1     |
| pci:8086-43c6 | Intel       | 500 Series Chipset Family... | 1     |
| pci:8086-462d | Intel       | PCI bridge                   | 1     |
| pci:8086-4dbb | Intel       | Jasper Lake PCIe Port #4     | 1     |
| pci:8086-51b8 | Intel       | PCI bridge                   | 1     |
| pci:8086-51be | Intel       | PCI bridge                   | 1     |
| pci:8086-5900 | Intel       | Xeon E3-1200 v6/7th Gen C... | 1     |
| pci:8086-65e4 | Intel       | 5100 Chipset PCI Express ... | 1     |
| pci:8086-65e6 | Intel       | 5100 Chipset PCI Express ... | 1     |
| pci:8086-7808 | Intel       | Xeon Phi x200 product fam... | 1     |
| pci:8086-783c | Intel       | Xeon Phi x200 product fam... | 1     |
| pci:8086-783e | Intel       | Host bridge                  | 1     |
| pci:8086-7ab7 | Intel       | 600 Series Chipset Family... | 1     |
| pci:8086-9a16 | Intel       | Host bridge                  | 1     |
| pci:8086-a0af | Intel       | Host bridge                  | 1     |
| pci:8086-a191 | Intel       | C620 Series Chipset Famil... | 1     |
| pci:8086-a19b | Intel       | C620 Series Chipset Famil... | 1     |
| pci:8086-a19e | Intel       | C620 Series Chipset Famil... | 1     |
| pci:8086-a1c6 | Intel       | C627 Series Chipset LPC/e... | 1     |
| pci:8086-a2c7 | Intel       | 200 Series PCH LPC Contro... | 1     |
| pci:8086-a2e8 | Intel       | 200 Series PCH PCI Expres... | 1     |
| pci:8086-b154 | Intel       | 21154 PCI-to-PCI Bridge      | 1     |
| pci:9005-528f | Adaptec     | PCI bridge                   | 1     |
| pci:9710-8825 | MosChip ... | MosChip ISA bridge           | 1     |

### Card reader (PCI)

Total devices: 19657

| ID            | MFG         | Name                         | Count |
|---------------|-------------|------------------------------|-------|
| pci:10ec-522a | Realtek ... | RTS522A PCI Express Card ... | 3741  |
| pci:10ec-525a | Realtek ... | RTS525A PCI Express Card ... | 3289  |
| pci:10ec-5229 | Realtek ... | RTS5229 PCI Express Card ... | 3145  |
| pci:10ec-5287 | Realtek ... | RTL8411B PCI Express Card... | 2632  |
| pci:10ec-5209 | Realtek ... | RTS5209 PCI Express Card ... | 2203  |
| pci:10ec-5227 | Realtek ... | RTS5227 PCI Express Card ... | 2091  |
| pci:10ec-5289 | Realtek ... | RTL8411 PCI Express Card ... | 972   |
| pci:10ec-5286 | Realtek ... | RTL8402 Integrated 1-LUN ... | 486   |
| pci:10ec-5260 | Realtek ... | RTS5260 PCI Express Card ... | 481   |
| pci:10ec-5249 | Realtek ... | RTS5249 PCI Express Card ... | 338   |
| pci:1aea-6625 | Alcor Micro | AU6625 PCI-E Flash card r... | 169   |
| pci:10ec-524a | Realtek ... | RTS524A PCI Express Card ... | 44    |
| pci:1aea-6621 | Alcor Micro | AU6621 PCI-E Flash card r... | 42    |
| pci:1aea-6601 | Alcor Micro | AU6601 PCI-E Flash card r... | 20    |
| pci:10ec-5208 | Realtek ... | RTS5208 PCI Express Card ... | 4     |

### Co-processor (PCI)

Total devices: 1376

| ID            | MFG         | Name                         | Count |
|---------------|-------------|------------------------------|-------|
| pci:10de-0aa3 | Nvidia      | MCP79 Co-processor           | 564   |
| pci:10de-0753 | Nvidia      | MCP78S [GeForce 8200] Co-... | 319   |
| pci:10de-0d7a | Nvidia      | MCP89 Co-Processor           | 116   |
| pci:10de-03f4 | Nvidia      | MCP61 SMU                    | 108   |
| pci:10de-0543 | Nvidia      | MCP67 Co-processor           | 106   |
| pci:10de-0271 | Nvidia      | MCP51 PMU                    | 69    |
| pci:10de-07da | Nvidia      | MCP73 Co-processor           | 46    |
| pci:10de-0447 | Nvidia      | MCP65 SMU                    | 16    |
| pci:8086-19e2 | Intel       | Atom Processor C3000 Seri... | 8     |
| pci:8086-1f18 | Intel       | Atom processor C2000 QAT     | 5     |
| pci:8086-37c8 | Intel       | C62x Chipset QuickAssist ... | 4     |
| pci:8086-225c | Intel       | Xeon Phi coprocessor SE10... | 3     |
| pci:8086-2710 | Intel       | Co-processor                 | 2     |
| pci:8086-4940 | Intel       | Co-processor                 | 2     |
| pci:1bbf-0003 | Maxeler ... | MAX3                         | 1     |
| pci:8086-0434 | Intel       | DH89XXCC Series QAT          | 1     |
| pci:8086-0435 | Intel       | DH895XCC Series QAT          | 1     |
| pci:8086-11a0 | Intel       | Merrifield SCU IPC           | 1     |
| pci:8086-11a1 | Intel       | Merrifield Power Manageme... | 1     |
| pci:8086-11a3 | Intel       | Co-processor                 | 1     |
| pci:8086-11a4 | Intel       | Co-processor                 | 1     |
| pci:8086-2250 | Intel       | Xeon Phi coprocessor 5100... | 1     |

### Communication controller (PCI)

Total devices: 80720

| ID            | MFG         | Name                         | Count |
|---------------|-------------|------------------------------|-------|
| pci:8086-1e3a | Intel       | 7 Series/C216 Chipset Fam... | 10828 |
| pci:8086-1c3a | Intel       | 6 Series/C200 Series Chip... | 10615 |
| pci:8086-9d3a | Intel       | Sunrise Point-LP CSME HEC... | 9447  |
| pci:8086-8c3a | Intel       | 8 Series/C220 Series Chip... | 6585  |
| pci:8086-a13a | Intel       | 100 Series/C230 Series Ch... | 4862  |
| pci:8086-a360 | Intel       | Cannon Lake PCH HECI Cont... | 4724  |
| pci:8086-3b64 | Intel       | 5 Series/3400 Series Chip... | 4304  |
| pci:8086-9c3a | Intel       | 8 Series HECI #0             | 3403  |
| pci:8086-9de0 | Intel       | Cannon Point-LP MEI Contr... | 2670  |
| pci:8086-9cba | Intel       | Wildcat Point-LP MEI Cont... | 2668  |
| pci:8086-a2ba | Intel       | 200 Series PCH CSME HECI #1  | 2274  |
| pci:8086-a0e0 | Intel       | Tiger Lake-LP Management ... | 1815  |
| pci:8086-02e0 | Intel       | Comet Lake Management Eng... | 1777  |
| pci:8086-a328 | Intel       | Cannon Lake PCH Serial IO... | 1408  |
| pci:8086-319a | Intel       | Celeron/Pentium Silver Pr... | 1394  |
| pci:8086-06e0 | Intel       | Comet Lake HECI Controller   | 1304  |
| pci:8086-8cba | Intel       | 9 Series Chipset Family M... | 1037  |
| pci:8086-34e0 | Intel       | Ice Lake-LP Management En... | 1003  |
| pci:8086-5a9a | Intel       | Celeron N3350/Pentium N42... | 970   |
| pci:8086-2e14 | Intel       | 4 Series Chipset HECI Con... | 693   |
| pci:8086-1d3a | Intel       | C600/X79 series chipset M... | 639   |
| pci:8086-43e0 | Intel       | Tiger Lake-H Management E... | 567   |
| pci:8086-8d3a | Intel       | C610/X99 series chipset M... | 544   |
| pci:8086-9da8 | Intel       | Cannon Point-LP Serial IO... | 523   |
| pci:8086-2a44 | Intel       | Mobile 4 Series Chipset M... | 436   |
| pci:8086-34a8 | Intel       | Ice Lake-LP Serial IO UAR... | 341   |
| pci:8086-a3ba | Intel       | Comet Lake PCH-V HECI Con... | 330   |
| pci:8086-a0a8 | Intel       | Tiger Lake-LP Serial IO U... | 324   |
| pci:8086-29b4 | Intel       | 82Q35 Express MEI Controller | 293   |
| pci:8086-06a8 | Intel       | Comet Lake PCH Serial IO ... | 216   |
| pci:8086-02a8 | Intel       | Comet Lake PCH-LP LPSS: U... | 201   |
| pci:8086-9d3e | Intel       | iTouch Controller            | 171   |
| pci:8086-a1ba | Intel       | C620 Series Chipset Famil... | 165   |
| pci:8086-1d3b | Intel       | C600/X79 series chipset M... | 155   |
| pci:8086-8d3b | Intel       | C610/X99 series chipset M... | 128   |
| pci:8086-a1be | Intel       | C620 Series Chipset Famil... | 125   |
| pci:8086-a1bb | Intel       | C620 Series Chipset Famil... | 115   |
| pci:14f1-2f20 | Conexant... | HSF 56k Data/Fax Modem       | 105   |
| pci:8086-02c7 | Intel       | Comet Lake PCH-LP LPSS: U... | 102   |
| pci:8086-2a04 | Intel       | Mobile PM965/GM965 MEI Co... | 96    |
| pci:8086-2994 | Intel       | 82Q963/Q965 HECI Controller  | 92    |
| pci:8086-4de0 | Intel       | Management Engine Interface  | 70    |
| pci:8086-5a9c | Intel       | Communication controller     | 66    |
| pci:8086-5a9e | Intel       | Communication controller     | 66    |
| pci:8086-7ae8 | Intel       | Alder Lake-S PCH HECI Con... | 66    |
| pci:9710-9835 | MosChip ... | PCI 9835 Multi-I/O Contro... | 57    |
| pci:104c-803d | Texas In... | PCIxx12 GemCore based Sma... | 56    |
| pci:8086-29c4 | Intel       | 82G33/G31/P35/P31 Express... | 55    |
| pci:8086-4da8 | Intel       | Jasper Lake LPSS: UART Co... | 52    |
| pci:8086-29a4 | Intel       | 82P965/G965 HECI Controller  | 49    |
| pci:8086-29d4 | Intel       | 82Q33 Express MEI Controller | 48    |
| pci:14f1-2f30 | Conexant... | SoftV92 SpeakerPhone Soft... | 37    |
| pci:8086-a0c7 | Intel       | Tiger Lake-LP Serial IO U... | 34    |
| pci:11c1-0620 | LSI         | Lucent V.92 Data/Fax Modem   | 33    |
| pci:8086-a329 | Intel       | 300 Series Chipset Family    | 33    |
| pci:11c1-0630 | LSI         | PCI-SV92EX Soft Modem        | 32    |
| pci:8086-2e24 | Intel       | 4 Series Chipset HECI Con... | 31    |
| pci:8086-a364 | Intel       | Cannon Lake PCH HECI Cont... | 29    |
| pci:14f1-2f00 | Conexant... | HSF 56k HSFi Modem           | 28    |
| pci:8086-8c3b | Intel       | 8 Series/C220 Series Chip... | 28    |
| pci:8086-34e4 | Intel       | Communication controller     | 27    |
| pci:8086-a13b | Intel       | 100 Series/C230 Series Ch... | 25    |
| pci:11c1-048c | LSI         | V.92 56K WinModem            | 20    |
| pci:104c-8035 | Texas In... | PCIxx21/PCIxx11 Smart Car... | 19    |
| pci:104c-8038 | Texas In... | PCI6515 SmartCard Controller | 16    |
| pci:8086-02a9 | Intel       | Comet Lake PCH-LP LPSS: U... | 16    |
| pci:8086-228c | Intel       | Atom/Celeron/Pentium Proc... | 16    |
| pci:8086-38e0 | Intel       | Ice Lake Management Engin... | 16    |
| pci:9710-9805 | MosChip ... | PCI 1 port parallel adapter  | 15    |
| pci:8086-38a8 | Intel       | LPSS: UART #0                | 14    |
| pci:13f6-0211 | C-Media ... | CM8738                       | 13    |
| pci:14f1-10b6 | Conexant... | CX06834-11 HCF V.92 56k D... | 13    |
| pci:14f1-2f50 | Conexant... | Conexant SoftK56 Data/Fax... | 13    |
| pci:14f1-2f40 | Conexant... | PCI CX11261 Soft Modem       | 12    |
| pci:8086-43a7 | Intel       | 500 Series Chipset Family... | 10    |
| pci:8086-a361 | Intel       | 300 Series Chipset HECI #2   | 10    |
| pci:8086-19d3 | Intel       | Atom Processor C3000 Seri... | 8     |
| pci:8086-1c3b | Intel       | 6 Series/C200 Series Chip... | 8     |
| pci:9710-9815 | MosChip ... | PCI 9815 Multi-I/O Contro... | 7     |
| pci:14f1-2f81 | Conexant... | PCIe CX95610 Soft Modem      | 6     |
| pci:14f1-2702 | Conexant... | HSFi modem RD01-D270         | 5     |
| pci:8086-51e0 | Intel       | Alder Lake PCH HECI Contr... | 5     |
| pci:8086-43a8 | Intel       | 500 Series Chipset Family... | 4     |
| pci:8086-9da9 | Intel       | 8th Gen Intel Core Proces... | 4     |
| pci:11c1-0480 | LSI         | Venus Modem (V90, 56KFlex)   | 3     |
| pci:125d-2838 | ESS Tech... | ES2838/2839 SuperLink Modem  | 3     |
| pci:14f1-1033 | Conexant... | HCF 56k Data/Fax Modem       | 3     |
| pci:14f1-2013 | Conexant... | HSF 56k Data/Fax Modem       | 3     |
| pci:8086-0801 | Intel       | Moorestown SPI Ctrl 1        | 3     |
| pci:8086-0802 | Intel       | Moorestown I2C 0             | 3     |
| pci:8086-0803 | Intel       | Moorestown I2C 1             | 3     |
| pci:8086-0804 | Intel       | Moorestown I2C 2             | 3     |
| pci:8086-1e3b | Intel       | 7 Series/C210 Series Chip... | 3     |
| pci:8086-2e44 | Intel       | 4 Series Chipset HECI Con... | 3     |
| pci:1093-c801 | National... | PCI-GPIB                     | 2     |
| pci:11d4-1805 | Analog D... | SM56 PCI modem               | 2     |
| pci:14f1-1035 | Conexant... | HCF 56k Data/Fax/Voice/Sp... | 2     |
| pci:14f1-2014 | Conexant... | HSF 56k Data/Fax/Voice Modem | 2     |
| pci:14f1-2f12 | Conexant... | HSF Data/Fax/Voice (USA)     | 2     |
| pci:14f1-2f82 | Conexant... | PCIe CX95610 Soft Modem      | 2     |
| pci:1556-1111 | PLDA        | XpressRich-AXI Ref Design    | 2     |
| pci:5372-6870 | Unknown     | Communication controller     | 2     |
| pci:8086-0f0a | Intel       | Atom Processor Z36xxx/Z37... | 2     |
| pci:8086-0f0c | Intel       | Atom Processor Z36xxx/Z37... | 2     |
| pci:8086-1be0 | Intel       | Management Engine Interfa... | 2     |
| pci:8086-1be1 | Intel       | Communication controller     | 2     |
| pci:8086-1be4 | Intel       | Communication controller     | 2     |
| pci:8086-29e4 | Intel       | 82X38/X48 Express MEI Con... | 2     |
| pci:8086-7aa8 | Intel       | 600 Series Chipset Family... | 2     |
| pci:8086-98a8 | Intel       | LPSS: UART Controller #0     | 2     |
| pci:8086-98a9 | Intel       | LPSS: UART Controller #1     | 2     |
| pci:8086-98e0 | Intel       | ME OEM Extension             | 2     |
| pci:8086-9dc7 | Intel       | 8th Gen Intel Core Proces... | 2     |
| pci:9710-9900 | MosChip ... | MCS9900 Multi-I/O Controller | 2     |
| pci:00f1-2f30 |             | Communication controller     | 1     |
| pci:00f1-2f50 | Unknown     | Communication controller     | 1     |
| pci:04f1-2f20 | Unknown     | Communication controller     | 1     |
| pci:125d-1989 | ESS Tech... | ESS Modem                    | 1     |
| pci:127a-1005 | Rockwell... | HCF 56k Data/Fax/Voice/Sp... | 1     |
| pci:127a-2013 | Rockwell... | HSF 56k Data/Fax Modem       | 1     |
| pci:127a-2015 | Rockwell... | HSF 56k Data/Fax/Voice/Sp... | 1     |
| pci:127a-4311 | Rockwell... | Riptide HSF 56k PCI Modem    | 1     |
| pci:13b0-0200 | Maxspeed    | Communication controller     | 1     |
| pci:14f1-1056 | Conexant... | HCF 56k Data/Fax/Voice/Sp... | 1     |
| pci:14f1-10b4 | Conexant... | HCF Data/Fax/Remote TAM      | 1     |
| pci:14f1-2f02 | Conexant... | HSF 56k HSFi Data/Fax        | 1     |
| pci:1813-4000 | Ambient ... | HaM controllerless modem     | 1     |
| pci:1fff-8014 | MCST        | GPIO MPV                     | 1     |
| pci:1fff-8019 | MCST        | Parallel and Serial          | 1     |
| pci:5372-6872 | Unknown     | Communication controller     | 1     |
| pci:8086-06a9 | Intel       | Comet Lake PCH Serial IO ... | 1     |
| pci:8086-1195 | Intel       | Merrifield Serial IO I2C ... | 1     |
| pci:8086-1196 | Intel       | Merrifield Serial IO I2C ... | 1     |
| pci:8086-1197 | Intel       | Communication controller     | 1     |
| pci:8086-1a9a | Intel       | ME OEM Extension             | 1     |
| pci:8086-228a | Intel       | Atom/Celeron/Pentium Proc... | 1     |
| pci:8086-29b5 | Intel       | 82Q35 Express MEI Controller | 1     |
| pci:8086-2a14 | Intel       | Mobile GME965/GLE960 MEI ... | 1     |
| pci:8086-2a45 | Intel       | Mobile 4 Series Chipset M... | 1     |
| pci:8086-34e1 | Intel       | Communication controller     | 1     |
| pci:8086-4dc7 | Intel       | Jasper Lake LPSS: UART Co... | 1     |
| pci:8086-9de1 | Intel       | Communication controller     | 1     |
| pci:8086-a0e4 | Intel       | Tiger Lake-LP Management ... | 1     |

### Digitizer pen (PCI)

Total devices: 20

| ID            | MFG         | Name                         | Count |
|---------------|-------------|------------------------------|-------|
| pci:8086-a0d0 | Intel       | Digitizer Pen                | 20    |

### Dma controller (PCI)

Total devices: 427

| ID            | MFG         | Name                         | Count |
|---------------|-------------|------------------------------|-------|
| pci:8086-9ce0 | Intel       | Wildcat Point-LP Serial I... | 292   |
| pci:8086-9c60 | Intel       | 8 Series Low Power Sub-Sy... | 65    |
| pci:8086-22c0 | Intel       | Atom/Celeron/Pentium Proc... | 38    |
| pci:8086-2286 | Intel       | Atom/Celeron/Pentium Proc... | 16    |
| pci:8086-0f40 | Intel       | Atom Processor Z36xxx/Z37... | 10    |
| pci:8086-0f06 | Intel       | Atom Processor Z36xxx/Z37... | 4     |
| pci:10b5-2715 | PLX Tech... | DMA controller               | 1     |
| pci:1311-0801 | Videoserver | DMA controller               | 1     |

### Docking station (PCI)

Total devices: 1

| ID            | MFG         | Name                         | Count |
|---------------|-------------|------------------------------|-------|
| pci:168c-0829 | Qualcomm... | Docking Station              | 1     |

### Dpio module (PCI)

Total devices: 4

| ID            | MFG         | Name                         | Count |
|---------------|-------------|------------------------------|-------|
| pci:10b5-9050 | PLX Tech... | PCI <-> IOBus Bridge         | 3     |
| pci:012d-4d4c | Unknown     | DPIO module                  | 1     |

### Dvb card (PCI)

Total devices: 124

| ID            | MFG         | Name                         | Count |
|---------------|-------------|------------------------------|-------|
| pci:13d0-2103 | Techsan ... | B2C2 FlexCopII DVB chip /... | 69    |
| pci:1131-7146 | Philips ... | SAA7146                      | 53    |
| pci:195d-1105 | Unknown     | Ethernet controller          | 2     |

### Encryption controller (PCI)

Total devices: 20371

| ID            | MFG         | Name                         | Count |
|---------------|-------------|------------------------------|-------|
| pci:1022-15df | AMD         | Family 17h (Models 10h-1f... | 6799  |
| pci:1022-1486 | AMD         | Starship/Matisse Cryptogr... | 3329  |
| pci:1022-1456 | AMD         | Family 17h (Models 00h-0f... | 3026  |
| pci:8086-2298 | Intel       | Atom/Celeron/Pentium Proc... | 2365  |
| pci:8086-0f18 | Intel       | Atom Processor Z36xxx/Z37... | 2080  |
| pci:1022-1578 | AMD         | Carrizo Platform Security... | 1724  |
| pci:1022-1537 | AMD         | Kabini/Mullins PSP-Platfo... | 1005  |
| pci:1022-1498 | AMD         | Starship/Matisse PTDMA       | 30    |
| pci:1022-1468 | AMD         | Zeppelin Cryptographic Co... | 10    |
| pci:1022-13ec | AMD         | Ariel Cryptographic Copro... | 1     |
| pci:1172-8004 | Altera      | Encryption controller        | 1     |
| pci:8086-1198 | Intel       | Encryption controller        | 1     |

### Entertainment encryption device (PCI)

Total devices: 1

| ID            | MFG         | Name                         | Count |
|---------------|-------------|------------------------------|-------|
| pci:1022-2082 | AMD         | Geode LX AES Security Block  | 1     |

### Firewire controller (PCI)

Total devices: 13826

| ID            | MFG         | Name                         | Count |
|---------------|-------------|------------------------------|-------|
| pci:1180-0832 | Ricoh       | R5C832 IEEE 1394 Controller  | 2602  |
| pci:1106-3044 | VIA Tech... | VT6306/7/8 [Fire II(M)] I... | 1947  |
| pci:197b-2380 | JMicron ... | IEEE 1394 Host Controller    | 1163  |
| pci:11c1-5811 | LSI         | FW322/323 [TrueFire] 1394... | 1147  |
| pci:1180-e832 | Ricoh       | R5C832 PCIe IEEE 1394 Con... | 1048  |
| pci:104c-8024 | Texas In... | TSB43AB23 IEEE-1394a-2000... | 971   |
| pci:11c1-5901 | LSI         | FW643 [TrueFire] PCIe 139... | 915   |
| pci:1106-3403 | VIA Tech... | VT6315 Series Firewire Co... | 907   |
| pci:104c-803a | Texas In... | PCIxx12 OHCI Compliant IE... | 720   |
| pci:104c-8023 | Texas In... | TSB43AB22A IEEE-1394a-200... | 554   |
| pci:1217-00f7 | O2 Micro    | Firewire (IEEE 1394)         | 439   |
| pci:104c-823f | Texas In... | XIO2213A/B/XIO2221 IEEE-1... | 298   |
| pci:1217-13f7 | O2 Micro    | 1394 OHCI Compliant Host ... | 211   |
| pci:1102-4001 | Creative... | SB Audigy FireWire Port      | 188   |
| pci:1180-0552 | Ricoh       | R5C552 IEEE 1394 Controller  | 131   |
| pci:104c-8032 | Texas In... | OHCI Compliant IEEE 1394 ... | 115   |
| pci:104c-8025 | Texas In... | TSB82AA2 IEEE-1394b Link ... | 89    |
| pci:1217-11f7 | O2 Micro    | OZ600 1394a-2000 Controller  | 71    |
| pci:1217-10f7 | O2 Micro    | 1394 OHCI Compliant Host ... | 64    |
| pci:11bd-0015 | Pinnacle... | FireWire IEEE1394            | 28    |
| pci:11c1-5903 | LSI         | FW533 [TrueFire] PCIe 139... | 26    |
| pci:1033-00f2 | NEC Comp... | uPD72874 [Firewarden] IEE... | 23    |
| pci:104c-8026 | Texas In... | TSB43AB21 IEEE-1394a-2000... | 23    |
| pci:104c-8029 | Texas In... | PCI4510 IEEE-1394 Controller | 18    |
| pci:104c-8235 | Texas In... | XIO2200A IEEE-1394a-2000 ... | 16    |
| pci:104c-802e | Texas In... | PCI7x20 1394a-2000 OHCI T... | 15    |
| pci:104c-8020 | Texas In... | TSB12LV26 IEEE-1394 Contr... | 14    |
| pci:1033-00e7 | NEC Comp... | uPD72873 [Firewarden] IEE... | 12    |
| pci:1106-3401 | VIA Tech... | FireWire (IEEE 1394)         | 11    |
| pci:104c-8019 | Texas In... | TSB12LV23 IEEE-1394 Contr... | 10    |
| pci:1180-0551 | Ricoh       | R5C551 IEEE 1394 Controller  | 7     |
| pci:10b9-5253 | ULi Elec... | M5253 P1394 OHCI 1.1 Cont... | 6     |
| pci:106b-0031 | Apple       | UniNorth 2 FireWire          | 5     |
| pci:1039-7007 | Silicon ... | FireWire Controller          | 4     |
| pci:104c-8027 | Texas In... | PCI4451 IEEE-1394 Controller | 4     |
| pci:1006-3044 | Reply Group | Reply FireWire (IEEE 1394)   | 3     |
| pci:104c-802b | Texas In... | PCI7410,7510,7610 OHCI-Ly... | 3     |
| pci:10de-006e | Nvidia      | nForce2 FireWire (IEEE 13... | 3     |
| pci:01c1-5811 | Unknown     | FireWire (IEEE 1394)         | 2     |
| pci:1033-00ce | NEC Comp... | uPD72871 [Firewarden] IEE... | 2     |
| pci:104c-8037 | Texas In... | FireWire (IEEE 1394)         | 2     |
| pci:004c-8024 | Unknown     | FireWire (IEEE 1394)         | 1     |
| pci:0180-0832 | Unknown     | FireWire (IEEE 1394)         | 1     |
| pci:104c-8000 | Texas In... | PCILynx/PCILynx2 IEEE 139... | 1     |
| pci:104c-8009 | Texas In... | TSB12LV22 IEEE-1394 Contr... | 1     |
| pci:104c-8021 | Texas In... | TSB43AA22 IEEE-1394 Contr... | 1     |
| pci:106b-0042 | Apple       | K2 FireWire                  | 1     |
| pci:106b-0052 | Apple       | Shasta Firewire              | 1     |
| pci:11bd-0014 | Pinnacle... | Pinnacle FireWire (IEEE 1... | 1     |
| pci:19ff-2380 | Eclipse ... | Eclipse FireWire (IEEE 1394) | 1     |

### Flash memory (PCI)

Total devices: 620

| ID            | MFG         | Name                         | Count |
|---------------|-------------|------------------------------|-------|
| pci:1524-0551 | ENE Tech... | SD/MMC Card Reader Contro... | 160   |
| pci:1524-0530 | ENE Tech... | ENE PCI Memory Stick Card... | 159   |
| pci:1524-0520 | ENE Tech... | FLASH memory: ENE Technol... | 133   |
| pci:1524-0730 | ENE Tech... | ENE PCI Memory Stick Card... | 62    |
| pci:1524-0751 | ENE Tech... | ENE PCI Secure Digital / ... | 62    |
| pci:1524-0720 | ENE Tech... | Memory Stick Card Reader ... | 31    |
| pci:1106-9530 | VIA Tech... | VX800/820/900 Series Secu... | 6     |
| pci:1524-0510 | ENE Tech... | CB710 Memory Card Reader ... | 6     |
| pci:1524-0500 | ENE Tech... | FLASH memory                 | 1     |

### Generic system peripheral (PCI)

Total devices: 4249

| ID            | MFG         | Name                         | Count |
|---------------|-------------|------------------------------|-------|
| pci:1022-1451 | AMD         | Family 17h (Models 00h-0f... | 2769  |
| pci:1002-5a23 | AMD         | RD890S/RD990 I/O Memory M... | 753   |
| pci:1022-1419 | AMD         | Family 15h (Models 10h-1f... | 469   |
| pci:1022-1423 | AMD         | Family 15h (Models 30h-3f... | 248   |
| pci:8086-19a2 | Intel       | Atom Processor C3000 Seri... | 8     |
| pci:8086-0b23 | Intel       | Generic system peripheral    | 2     |

### Graphics card (PCI)

Total devices: 170802

| ID            | MFG         | Name                         | Count |
|---------------|-------------|------------------------------|-------|
| pci:8086-0166 | Intel       | 3rd Gen Core processor Gr... | 5451  |
| pci:8086-5917 | Intel       | UHD Graphics 620             | 3357  |
| pci:8086-0116 | Intel       | 2nd Generation Core Proce... | 3272  |
| pci:8086-0a16 | Intel       | Haswell-ULT Integrated Gr... | 3008  |
| pci:8086-2a42 | Intel       | Mobile 4 Series Chipset I... | 2702  |
| pci:8086-3e9b | Intel       | CoffeeLake-H GT2 [UHD Gra... | 2700  |
| pci:8086-0046 | Intel       | Core Processor Integrated... | 2657  |
| pci:8086-5916 | Intel       | HD Graphics 620              | 2652  |
| pci:8086-1916 | Intel       | Skylake GT2 [HD Graphics ... | 2614  |
| pci:8086-2a43 | Intel       | Mobile 4 Series Chipset I... | 2588  |
| pci:1002-15d8 | AMD         | Picasso/Raven 2 [Radeon V... | 2456  |
| pci:8086-3ea0 | Intel       | WhiskeyLake-U GT2 [UHD Gr... | 2425  |
| pci:1002-67df | AMD         | Ellesmere [Radeon RX 470/... | 2375  |
| pci:8086-1616 | Intel       | HD Graphics 5500             | 2179  |
| pci:8086-0f31 | Intel       | Atom Processor Z36xxx/Z37... | 2164  |
| pci:8086-0416 | Intel       | 4th Gen Core Processor In... | 2057  |
| pci:8086-0412 | Intel       | Xeon E3-1200 v3/4th Gen C... | 1991  |
| pci:8086-0102 | Intel       | 2nd Generation Core Proce... | 1976  |
| pci:8086-0126 | Intel       | 2nd Generation Core Proce... | 1975  |
| pci:1002-1636 | AMD         | Renoir                       | 1875  |
| pci:8086-9a49 | Intel       | TigerLake-LP GT2 [Iris Xe... | 1671  |
| pci:8086-9b41 | Intel       | CometLake-U GT2 [UHD Grap... | 1629  |
| pci:8086-0152 | Intel       | Xeon E3-1200 v2/3rd Gen C... | 1501  |
| pci:8086-22b1 | Intel       | Atom/Celeron/Pentium Proc... | 1436  |
| pci:8086-2a02 | Intel       | Mobile GM965/GL960 Integr... | 1412  |
| pci:8086-2a03 | Intel       | Mobile GM965/GL960 Integr... | 1412  |
| pci:10de-128b | Nvidia      | GK208B [GeForce GT 710]      | 1321  |
| pci:8086-0106 | Intel       | 2nd Generation Core Proce... | 1241  |
| pci:1002-15dd | AMD         | Raven Ridge [Radeon Vega ... | 1213  |
| pci:10de-1c82 | Nvidia      | GP107 [GeForce GTX 1050 Ti]  | 1176  |
| pci:10de-0a65 | Nvidia      | GT218 [GeForce 210]          | 1151  |
| pci:8086-27a6 | Intel       | Mobile 945GM/GMS/GME, 943... | 1093  |
| pci:8086-591b | Intel       | HD Graphics 630              | 1084  |
| pci:8086-3185 | Intel       | GeminiLake [UHD Graphics ... | 1072  |
| pci:10de-1140 | Nvidia      | GF117M [GeForce 610M/710M... | 1047  |
| pci:1002-98e4 | AMD         | Stoney [Radeon R2/R3/R4/R... | 1010  |
| pci:8086-22b0 | Intel       | Atom/Celeron/Pentium Proc... | 1002  |
| pci:10de-1c8d | Nvidia      | GP107M [GeForce GTX 1050 ... | 919   |
| pci:8086-1912 | Intel       | HD Graphics 530              | 915   |
| pci:8086-9bc4 | Intel       | CometLake-H GT2 [UHD Grap... | 858   |
| pci:10de-1f91 | Nvidia      | TU117M [GeForce GTX 1650 ... | 849   |
| pci:1002-6900 | AMD         | Topaz XT [Radeon R7 M260/... | 828   |
| pci:8086-29c2 | Intel       | 82G33/G31 Express Integra... | 804   |
| pci:10de-1c03 | Nvidia      | GP106 [GeForce GTX 1060 6GB] | 799   |
| pci:8086-a011 | Intel       | Atom Processor D4xx/D5xx/... | 796   |
| pci:8086-a012 | Intel       | Atom Processor D4xx/D5xx/... | 795   |
| pci:8086-0156 | Intel       | 3rd Gen Core processor Gr... | 780   |
| pci:1002-68f9 | AMD         | Cedar [Radeon HD 5000/600... | 774   |
| pci:1002-6660 | AMD         | Sun XT [Radeon HD 8670A/8... | 766   |
| pci:8086-191b | Intel       | HD Graphics 530              | 762   |
| pci:8086-5a85 | Intel       | HD Graphics 500              | 756   |
| pci:1002-6760 | AMD         | Seymour [Radeon HD 6400M/... | 754   |
| pci:1002-731f | AMD         | Navi 10 [Radeon RX 5600 O... | 724   |
| pci:8086-2e32 | Intel       | 4 Series Chipset Integrat... | 722   |
| pci:8086-27a2 | Intel       | Mobile 945GM/GMS, 943/940... | 691   |
| pci:8086-5912 | Intel       | HD Graphics 630              | 689   |
| pci:10de-1c8c | Nvidia      | GP107M [GeForce GTX 1050 ... | 674   |
| pci:1002-9874 | AMD         | Wani [Radeon R5/R6/R7 Gra... | 639   |
| pci:8086-3e92 | Intel       | CoffeeLake-S GT2 [UHD Gra... | 629   |
| pci:1002-9851 | AMD         | Mullins [Radeon R4/R5 Gra... | 628   |
| pci:10de-1380 | Nvidia      | GM107 [GeForce GTX 750 Ti]   | 624   |
| pci:10de-1d01 | Nvidia      | GP108 [GeForce GT 1030]      | 607   |
| pci:8086-041e | Intel       | 4th Generation Core Proce... | 603   |
| pci:8086-8a56 | Intel       | Iris Plus Graphics G1 (Ic... | 596   |
| pci:10de-104a | Nvidia      | GF119 [GeForce GT 610]       | 577   |
| pci:1002-1638 | AMD         | Cezanne                      | 549   |
| pci:8086-2e12 | Intel       | 4 Series Chipset Integrat... | 546   |
| pci:10de-1b81 | Nvidia      | GP104 [GeForce GTX 1070]     | 545   |
| pci:1002-6840 | AMD         | Thames [Radeon HD 7500M/7... | 541   |
| pci:8086-2772 | Intel       | 82945G/GZ Integrated Grap... | 539   |
| pci:1002-6779 | AMD         | Caicos [Radeon HD 6450/74... | 535   |
| pci:8086-2e13 | Intel       | 4 Series Chipset Integrat... | 532   |
| pci:10de-13c2 | Nvidia      | GM204 [GeForce GTX 970]      | 527   |
| pci:1002-68e0 | AMD         | Park [Mobility Radeon HD ... | 526   |
| pci:10de-1287 | Nvidia      | GK208B [GeForce GT 730]      | 525   |
| pci:8086-0162 | Intel       | IvyBridge GT2 [HD Graphic... | 524   |
| pci:8086-0402 | Intel       | Xeon E3-1200 v3/4th Gen C... | 521   |
| pci:10de-1d10 | Nvidia      | GP108M [GeForce MX150]       | 520   |
| pci:1002-9616 | AMD         | RS780L [Radeon 3000]         | 504   |
| pci:10de-1401 | Nvidia      | GM206 [GeForce GTX 960]      | 471   |
| pci:1002-699f | AMD         | Lexa PRO [Radeon 540/540X... | 469   |
| pci:1002-67ef | AMD         | Baffin [Radeon RX 460/560... | 466   |
| pci:1002-9712 | AMD         | RS880M [Mobility Radeon H... | 461   |
| pci:10de-134d | Nvidia      | GM108M [GeForce 940MX]       | 452   |
| pci:10de-1b80 | Nvidia      | GP104 [GeForce GTX 1080]     | 442   |
| pci:10de-0df4 | Nvidia      | GF108M [GeForce GT 540M]     | 440   |
| pci:10de-1341 | Nvidia      | GM108M [GeForce 840M]        | 439   |
| pci:10de-0fc6 | Nvidia      | GK107 [GeForce GTX 650]      | 430   |
| pci:10de-0f00 | Nvidia      | GF108 [GeForce GT 630]       | 420   |
| pci:8086-27ae | Intel       | Mobile 945GSE Express Int... | 417   |
| pci:10de-1c20 | Nvidia      | GP106M [GeForce GTX 1060 ... | 413   |
| pci:10de-1c81 | Nvidia      | GP107 [GeForce GTX 1050]     | 398   |
| pci:10de-0640 | Nvidia      | G96C [GeForce 9500 GT]       | 397   |
| pci:10de-1244 | Nvidia      | GF116 [GeForce GTX 550 Ti]   | 386   |
| pci:10de-1c02 | Nvidia      | GP106 [GeForce GTX 1060 3GB] | 385   |
| pci:1002-9802 | AMD         | Wrestler [Radeon HD 6310]    | 383   |
| pci:10de-2191 | Nvidia      | TU116M [GeForce GTX 1660 ... | 381   |
| pci:1a03-2000 | ASPEED T... | ASPEED Graphics Family       | 380   |
| pci:10de-1b06 | Nvidia      | GP102 [GeForce GTX 1080 Ti]  | 375   |
| pci:10de-139b | Nvidia      | GM107M [GeForce GTX 960M]    | 368   |
| pci:10de-0de9 | Nvidia      | GF108M [GeForce GT 620M/6... | 365   |
| pci:10de-1d13 | Nvidia      | GP108M [GeForce MX250]       | 365   |
| pci:1002-6741 | AMD         | Whistler [Radeon HD 6630M... | 363   |
| pci:10de-1292 | Nvidia      | GK208M [GeForce GT 740M]     | 363   |
| pci:10de-0622 | Nvidia      | G94 [GeForce 9600 GT]        | 359   |
| pci:8086-8a52 | Intel       | Iris Plus Graphics G7        | 358   |
| pci:8086-0042 | Intel       | Core Processor Integrated... | 355   |
| pci:1002-164c | AMD         | Lucienne                     | 352   |
| pci:1002-9553 | AMD         | RV710/M92 [Mobility Radeo... | 346   |
| pci:10de-11c0 | Nvidia      | GK106 [GeForce GTX 660]      | 335   |
| pci:1002-67ff | AMD         | Baffin [Radeon RX 550 640... | 330   |
| pci:10de-1f95 | Nvidia      | TU117M [GeForce GTX 1650 ... | 327   |
| pci:8086-3184 | Intel       | GeminiLake [UHD Graphics ... | 324   |
| pci:10de-139a | Nvidia      | GM107M [GeForce GTX 950M]    | 318   |
| pci:10de-1299 | Nvidia      | GK208BM [GeForce 920M]       | 311   |
| pci:1002-9806 | AMD         | Wrestler [Radeon HD 6320]    | 305   |
| pci:10de-174d | Nvidia      | GM108M [GeForce MX130]       | 305   |
| pci:10de-0de1 | Nvidia      | GF108 [GeForce GT 430]       | 300   |
| pci:10de-0f02 | Nvidia      | GF108 [GeForce GT 730]       | 291   |
| pci:8086-3e98 | Intel       | CoffeeLake-S GT2 [UHD Gra... | 287   |
| pci:1002-683d | AMD         | Cape Verde XT [Radeon HD ... | 285   |
| pci:10de-1187 | Nvidia      | GK104 [GeForce GTX 760]      | 285   |
| pci:10de-1f82 | Nvidia      | TU117 [GeForce GTX 1650]     | 283   |
| pci:10de-1f99 | Nvidia      | TU117M                       | 280   |
| pci:1002-687f | AMD         | Vega 10 XL/XT [Radeon RX ... | 277   |
| pci:1002-68c1 | AMD         | Madison [Mobility Radeon ... | 277   |
| pci:1039-6351 | Silicon ... | 771/671 PCIE VGA Display ... | 270   |
| pci:1002-68b8 | AMD         | Juniper XT [Radeon HD 5770]  | 269   |
| pci:1002-6613 | AMD         | Oland PRO [Radeon R7 240/... | 264   |
| pci:1002-6665 | AMD         | Jet PRO [Radeon R5 M230 /... | 259   |
| pci:10de-03d0 | Nvidia      | C61 [GeForce 6150SE nForc... | 259   |
| pci:8086-1626 | Intel       | HD Graphics 6000             | 256   |
| pci:10de-21c4 | Nvidia      | TU116 [GeForce GTX 1660 S... | 255   |
| pci:1002-95c4 | AMD         | RV620/M82 [Mobility Radeo... | 254   |
| pci:1002-683f | AMD         | Cape Verde PRO [Radeon HD... | 253   |
| pci:8086-0be1 | Intel       | Atom Processor D2xxx/N2xx... | 249   |
| pci:8086-9bc5 | Intel       | CometLake-S GT2 [UHD Grap... | 246   |
| pci:10de-174e | Nvidia      | GM108M [GeForce MX110]       | 245   |
| pci:1002-6758 | AMD         | Turks XT [Radeon HD 6670/... | 243   |
| pci:1002-7340 | AMD         | Navi 14 [Radeon RX 5500/5... | 243   |
| pci:10de-03d6 | Nvidia      | C61 [GeForce 7025 / nForc... | 242   |
| pci:10de-0de0 | Nvidia      | GF108 [GeForce GT 440]       | 242   |
| pci:10de-0402 | Nvidia      | G84 [GeForce 8600 GT]        | 237   |
| pci:10de-0615 | Nvidia      | G92 [GeForce GTS 250]        | 232   |
| pci:10de-0fc1 | Nvidia      | GK107 [GeForce GT 640]       | 231   |
| pci:102b-0532 | Matrox E... | MGA G200eW WPCM450           | 230   |
| pci:1002-6841 | AMD         | Thames [Radeon HD 7550M/7... | 227   |
| pci:8086-3e91 | Intel       | CoffeeLake-S GT2 [UHD Gra... | 227   |
| pci:10de-1f08 | Nvidia      | TU106 [GeForce RTX 2060 R... | 225   |
| pci:10de-1381 | Nvidia      | GM107 [GeForce GTX 750]      | 223   |
| pci:10de-1e84 | Nvidia      | TU104 [GeForce RTX 2070 S... | 222   |
| pci:10de-1040 | Nvidia      | GF119 [GeForce GT 520]       | 221   |
| pci:1002-954f | AMD         | RV710 [Radeon HD 4350/4550]  | 219   |
| pci:8086-9bc8 | Intel       | CometLake-S GT2 [UHD Grap... | 219   |
| pci:10de-0614 | Nvidia      | G92 [GeForce 9800 GT]        | 216   |
| pci:8086-5a84 | Intel       | Celeron N3350/Pentium N42... | 215   |
| pci:1002-6759 | AMD         | Turks PRO [Radeon HD 6570... | 214   |
| pci:1002-6819 | AMD         | Pitcairn PRO [Radeon HD 7... | 214   |
| pci:10de-0ca3 | Nvidia      | GT215 [GeForce GT 240]       | 209   |
| pci:1002-9710 | AMD         | RS880 [Radeon HD 4200]       | 208   |
| pci:1002-9612 | AMD         | RS780M [Mobility Radeon H... | 206   |
| pci:10de-0fe4 | Nvidia      | GK107M [GeForce GT 750M]     | 205   |
| pci:1002-6811 | AMD         | Curacao PRO [Radeon R7 37... | 204   |
| pci:1002-9647 | AMD         | Sumo [Radeon HD 6520G]       | 204   |
| pci:8086-29b2 | Intel       | 82Q35 Express Integrated ... | 203   |
| pci:10de-10c3 | Nvidia      | GT218 [GeForce 8400 GS Re... | 202   |
| pci:10de-0a20 | Nvidia      | GT216 [GeForce GT 220]       | 196   |
| pci:10de-11c6 | Nvidia      | GK106 [GeForce GTX 650 Ti]   | 195   |
| pci:10de-1347 | Nvidia      | GM108M [GeForce 940M]        | 195   |
| pci:1002-6740 | AMD         | Whistler [Radeon HD 6730M... | 193   |
| pci:8086-9a60 | Intel       | TigerLake-H GT1 [UHD Grap... | 192   |
| pci:10de-0421 | Nvidia      | G86 [GeForce 8500 GT]        | 191   |
| pci:10de-2184 | Nvidia      | TU116 [GeForce GTX 1660]     | 190   |
| pci:10de-06e4 | Nvidia      | G98 [GeForce 8400 GS Rev. 2] | 186   |
| pci:10de-1f15 | Nvidia      | TU106M [GeForce RTX 2060 ... | 186   |
| pci:8086-0a06 | Intel       | Haswell-ULT Integrated Gr... | 186   |
| pci:1002-9809 | AMD         | Wrestler [Radeon HD 7310]    | 185   |
| pci:10de-0fd1 | Nvidia      | GK107M [GeForce GT 650M]     | 182   |
| pci:8086-2592 | Intel       | Mobile 915GM/GMS/910GML E... | 180   |
| pci:8086-2792 | Intel       | Mobile 915GM/GMS/910GML E... | 180   |
| pci:8086-9bca | Intel       | Comet Lake UHD Graphics      | 180   |
| pci:10de-0dc4 | Nvidia      | GF106 [GeForce GTS 450]      | 179   |
| pci:8086-1902 | Intel       | HD Graphics 510              | 178   |
| pci:10de-1058 | Nvidia      | GF119M [GeForce 610M]        | 176   |
| pci:8086-3ea5 | Intel       | CoffeeLake-U GT3e [Iris P... | 175   |
| pci:1002-666f | AMD         | Sun LE [Radeon HD 8550M /... | 172   |
| pci:8086-2992 | Intel       | 82Q963/Q965 Integrated Gr... | 171   |
| pci:10de-0863 | Nvidia      | C79 [GeForce 9400M]          | 170   |
| pci:1002-9498 | AMD         | RV730 PRO [Radeon HD 4650]   | 169   |
| pci:10de-134f | NVIDIA      | GM108M [GeForce 920MX]       | 169   |
| pci:1002-6810 | AMD         | Curacao XT / Trinidad XT ... | 168   |
| pci:10de-0a6c | Nvidia      | GT218M [NVS 3100M]           | 168   |
| pci:1002-6610 | AMD         | Oland XT [Radeon HD 8670 ... | 167   |
| pci:10de-2187 | Nvidia      | TU116 [GeForce GTX 1650 S... | 166   |
| pci:10de-1d11 | Nvidia      | GP108M [GeForce MX230]       | 165   |
| pci:1002-68e4 | AMD         | Robson CE [Radeon HD 6370... | 164   |
| pci:1002-68d8 | AMD         | Redwood XT [Radeon HD 567... | 163   |
| pci:1002-9830 | AMD         | Kabini [Radeon HD 8400 / ... | 162   |
| pci:8086-2e22 | Intel       | 4 Series Chipset Integrat... | 162   |
| pci:10de-1f11 | Nvidia      | TU106M [GeForce RTX 2060 ... | 161   |
| pci:1002-6798 | AMD         | Tahiti XT [Radeon HD 7970... | 160   |
| pci:10de-0df5 | Nvidia      | GF108M [GeForce GT 525M]     | 160   |
| pci:10de-2182 | Nvidia      | TU116 [GeForce GTX 1660 Ti]  | 160   |
| pci:10de-1402 | Nvidia      | GM206 [GeForce GTX 950]      | 159   |
| pci:8086-a001 | Intel       | Atom Processor D4xx/D5xx/... | 159   |
| pci:1002-9807 | AMD         | Wrestler [Radeon HD 6290]    | 157   |
| pci:10de-0de3 | Nvidia      | GF108M [GeForce GT 635M]     | 157   |
| pci:10de-1d12 | Nvidia      | GP108M [GeForce MX150]       | 157   |
| pci:1002-130f | AMD         | Kaveri [Radeon R7 Graphics]  | 156   |
| pci:1002-9715 | AMD         | RS880 [Radeon HD 4250]       | 156   |
| pci:1002-9850 | AMD         | Mullins [Radeon R3 Graphics] | 156   |
| pci:10de-2520 | Nvidia      | GA106M [GeForce RTX 3060 ... | 156   |
| pci:1002-1313 | AMD         | Kaveri [Radeon R7 Graphics]  | 153   |
| pci:8086-2e23 | Intel       | 4 Series Chipset Integrat... | 152   |
| pci:1002-6600 | AMD         | Mars [Radeon HD 8670A/867... | 151   |
| pci:1002-67b1 | AMD         | Hawaii PRO [Radeon R9 290... | 151   |
| pci:10de-0649 | Nvidia      | G96CM [GeForce 9600M GT]     | 151   |
| pci:10de-1050 | Nvidia      | GF119M [GeForce GT 520M]     | 150   |
| pci:1002-9832 | AMD         | Kabini [Radeon HD 8330]      | 149   |
| pci:10de-0a29 | Nvidia      | GT216M [GeForce GT 330M]     | 149   |
| pci:8086-5906 | Intel       | Kaby Lake-U GT1 Integrate... | 149   |
| pci:1002-95c5 | AMD         | RV620 LE [Radeon HD 3450]    | 148   |
| pci:1002-9853 | AMD         | Mullins [Radeon R2 Graphics] | 148   |
| pci:10de-1051 | Nvidia      | GF119M [GeForce GT 520MX]    | 146   |
| pci:10de-1c91 | Nvidia      | GP107M [GeForce GTX 1050 ... | 146   |
| pci:1002-6739 | AMD         | Barts PRO [Radeon HD 6850]   | 145   |
| pci:10de-1b82 | Nvidia      | GP104 [GeForce GTX 1070 Ti]  | 145   |
| pci:1002-9834 | AMD         | Kabini [Radeon HD 8210]      | 144   |
| pci:10de-134e | Nvidia      | GM108M [GeForce 930MX]       | 144   |
| pci:1002-791f | AMD         | RS690M [Radeon Xpress 120... | 142   |
| pci:10de-1f06 | Nvidia      | TU106 [GeForce RTX 2060 S... | 142   |
| pci:1002-9903 | AMD         | Trinity [Radeon HD 7640G]    | 141   |
| pci:1002-6611 | AMD         | Oland [Radeon HD 8570 / R... | 140   |
| pci:1002-9591 | AMD         | RV635/M86 [Mobility Radeo... | 139   |
| pci:10de-1184 | Nvidia      | GK104 [GeForce GTX 770]      | 139   |
| pci:8086-191e | Intel       | HD Graphics 515              | 139   |
| pci:1002-9808 | AMD         | Wrestler [Radeon HD 7340]    | 138   |
| pci:8086-2e33 | Intel       | 4 Series Chipset Integrat... | 138   |
| pci:10de-1200 | Nvidia      | GF114 [GeForce GTX 560 Ti]   | 137   |
| pci:1002-6778 | AMD         | Caicos XT [Radeon HD 7470... | 136   |
| pci:10de-1392 | Nvidia      | GM107M [GeForce GTX 860M]    | 136   |
| pci:10de-0641 | Nvidia      | G96C [GeForce 9400 GT]       | 134   |
| pci:8086-9a78 | Intel       | Tiger Lake UHD Graphics      | 134   |
| pci:10de-1201 | Nvidia      | GF114 [GeForce GTX 560]      | 133   |
| pci:1002-515e | AMD         | ES1000                       | 132   |
| pci:1002-9442 | AMD         | RV770 [Radeon HD 4850]       | 132   |
| pci:10de-1391 | Nvidia      | GM107M [GeForce GTX 850M]    | 131   |
| pci:8086-591e | Intel       | HD Graphics 615              | 131   |
| pci:1002-9993 | AMD         | Trinity 2 [Radeon HD 7480D]  | 130   |
| pci:8086-5921 | Intel       | Kaby Lake-U GT2f HD 620 G... | 129   |
| pci:1002-9900 | AMD         | Trinity [Radeon HD 7660G]    | 128   |
| pci:10de-0e22 | Nvidia      | GF104 [GeForce GTX 460]      | 128   |
| pci:10de-0fc8 | Nvidia      | GK107 [GeForce GT 740]       | 128   |
| pci:1002-9490 | AMD         | RV730 XT [Radeon HD 4670]    | 125   |
| pci:1002-73bf | AMD         | Navi 21 [Radeon RX 6800/6... | 124   |
| pci:10de-0a75 | Nvidia      | GT218M [GeForce 310M]        | 124   |
| pci:10de-0fd2 | Nvidia      | GK107M [GeForce GT 640M]     | 123   |
| pci:1002-679a | AMD         | Tahiti PRO [Radeon HD 795... | 122   |
| pci:1002-9480 | AMD         | RV730/M96 [Mobility Radeo... | 122   |
| pci:10de-1056 | Nvidia      | GF119M [NVS 4200M]           | 122   |
| pci:10de-0427 | Nvidia      | G86M [GeForce 8400M GS]      | 121   |
| pci:8086-0a26 | Intel       | Haswell-ULT Integrated Gr... | 121   |
| pci:1002-68e1 | AMD         | Park [Mobility Radeon HD ... | 120   |
| pci:1002-9990 | AMD         | Trinity 2 [Radeon HD 7520G]  | 120   |
| pci:10de-1f02 | Nvidia      | TU106 [GeForce RTX 2070]     | 120   |
| pci:1002-5a62 | AMD         | RC410M [Mobility Radeon X... | 118   |
| pci:1002-990e | AMD         | Richland [Radeon HD 8570D]   | 118   |
| pci:102b-0534 | Matrox E... | G200eR2                      | 118   |
| pci:10de-0dfc | Nvidia      | GF108GLM [NVS 5200M]         | 118   |
| pci:10de-17c8 | Nvidia      | GM200 [GeForce GTX 980 Ti]   | 118   |
| pci:10de-1e07 | Nvidia      | TU102 [GeForce RTX 2080 T... | 117   |
| pci:1002-68d9 | AMD         | Redwood PRO [Radeon HD 55... | 116   |
| pci:1002-6987 | AMD         | Lexa [Radeon 540X/550X/63... | 116   |
| pci:10de-1245 | Nvidia      | GF116 [GeForce GTS 450 Re... | 116   |
| pci:8086-0112 | Intel       | 2nd Generation Core Proce... | 116   |
| pci:8086-5902 | Intel       | HD Graphics 610              | 116   |
| pci:1002-5975 | AMD         | RS482M [Mobility Radeon X... | 113   |
| pci:10de-0a70 | Nvidia      | GT218M [GeForce 310M]        | 113   |
| pci:10de-13c0 | Nvidia      | GM204 [GeForce GTX 980]      | 113   |
| pci:1002-9838 | AMD         | Kabini [Radeon HD 8240 / ... | 112   |
| pci:10de-1fb8 | Nvidia      | TU117GLM [Quadro T2000 Mo... | 112   |
| pci:1002-6663 | AMD         | Sun PRO [Radeon HD 8570A/... | 110   |
| pci:1002-6658 | AMD         | Bonaire XTX [Radeon R7 26... | 109   |
| pci:1002-9552 | AMD         | RV710/M92 [Mobility Radeo... | 109   |
| pci:1002-9804 | AMD         | Wrestler [Radeon HD 6250]    | 109   |
| pci:102b-0522 | Matrox E... | MGA G200e [Pilot] ServerE... | 109   |
| pci:10de-0407 | Nvidia      | G84M [GeForce 8600M GT]      | 109   |
| pci:10de-179c | Nvidia      | GM107 [GeForce 940MX]        | 109   |
| pci:8086-29b3 | Intel       | 82Q35 Express Integrated ... | 108   |
| pci:8086-0be2 | Intel       | Atom Processor D2xxx/N2xx... | 107   |
| pci:10de-06e9 | Nvidia      | G98M [GeForce 9300M GS]      | 106   |
| pci:10de-1e81 | Nvidia      | TU104 [GeForce RTX 2080 S... | 106   |
| pci:8086-1921 | Intel       | HD Graphics 520              | 106   |
| pci:1002-6738 | AMD         | Barts XT [Radeon HD 6870]    | 105   |
| pci:10de-1d16 | Nvidia      | GP108M [GeForce MX330]       | 105   |
| pci:1002-6939 | AMD         | Tonga PRO [Radeon R9 285/... | 102   |
| pci:10de-1cbb | Nvidia      | GP107GLM [Quadro P1000 Mo... | 102   |
| pci:1002-665f | AMD         | Tobago PRO [Radeon R7 360... | 100   |
| pci:1002-9648 | AMD         | Sumo [Radeon HD 6480G]       | 100   |
| pci:1106-3371 | VIA Tech... | CN896/VN896/P4M900 [Chrom... | 100   |
| pci:8086-162b | Intel       | Iris Graphics 6100           | 100   |
| pci:10de-01d7 | Nvidia      | G72M [Quadro NVS 110M/GeF... | 99    |
| pci:10de-1be1 | Nvidia      | GP104BM [GeForce GTX 1070... | 98    |
| pci:1002-68be | AMD         | Juniper PRO [Radeon HD 5750] | 97    |
| pci:1002-9901 | AMD         | Trinity [Radeon HD 7660D]    | 97    |
| pci:1002-9641 | AMD         | Sumo [Radeon HD 6620G]       | 96    |
| pci:10de-2484 | Nvidia      | GA104 [GeForce RTX 3070]     | 96    |
| pci:8086-2776 | Intel       | 82945G/GZ Integrated Grap... | 96    |
| pci:8086-3e90 | Intel       | CoffeeLake-S GT1 [UHD Gra... | 96    |
| pci:8086-5926 | Intel       | Iris Plus Graphics 640       | 96    |
| pci:10de-0ff6 | Nvidia      | GK107GLM [Quadro K1100M]     | 94    |
| pci:10de-1183 | Nvidia      | GK104 [GeForce GTX 660 Ti]   | 93    |
| pci:10de-2204 | Nvidia      | GA102 [GeForce RTX 3090]     | 93    |
| pci:1002-6601 | AMD         | Mars [Radeon HD 8730M]       | 91    |
| pci:1002-677b | AMD         | Caicos PRO [Radeon HD 7450]  | 91    |
| pci:1002-6818 | AMD         | Pitcairn XT [Radeon HD 78... | 91    |
| pci:10de-13b1 | Nvidia      | GM107GLM [Quadro M1000M]     | 91    |
| pci:10de-1fb9 | Nvidia      | TU117GLM [Quadro T1000 Mo... | 91    |
| pci:1002-5b60 | AMD         | RV370 [Radeon X300]          | 90    |
| pci:1002-5b70 | AMD         | RV370 [Radeon X300 SE]       | 90    |
| pci:102b-0533 | Matrox E... | MGA G200EH                   | 90    |
| pci:8086-1606 | Intel       | HD Graphics                  | 89    |
| pci:1002-94c3 | AMD         | RV610 [Radeon HD 2400 PRO]   | 88    |
| pci:10de-1189 | Nvidia      | GK104 [GeForce GTX 670]      | 88    |
| pci:8086-2582 | Intel       | 82915G/GV/910GL Integrate... | 88    |
| pci:8086-0a2e | Intel       | Haswell-ULT Integrated Gr... | 87    |
| pci:10de-1f12 | Nvidia      | TU106M [GeForce RTX 2060 ... | 86    |
| pci:1002-73df | AMD         | Navi 22 [Radeon RX 6700/6... | 85    |
| pci:10de-1288 | Nvidia      | GK208B [GeForce GT 720]      | 84    |
| pci:1002-9610 | AMD         | RS780 [Radeon HD 3200]       | 83    |
| pci:1002-990b | AMD         | Richland [Radeon HD 8650G]   | 83    |
| pci:1002-9996 | AMD         | Richland [Radeon HD 8470D]   | 83    |
| pci:10de-0dd8 | Nvidia      | GF106GL [Quadro 2000]        | 83    |
| pci:1002-6719 | AMD         | Cayman PRO [Radeon HD 6950]  | 82    |
| pci:1002-9904 | AMD         | Trinity [Radeon HD 7560D]    | 82    |
| pci:10de-0a7a | Nvidia      | GT218M [GeForce 315M]        | 82    |
| pci:1002-6604 | AMD         | Opal XT [Radeon R7 M265/M... | 81    |
| pci:8086-161e | Intel       | HD Graphics 5300             | 81    |
| pci:8086-a002 | Intel       | Atom Processor D4xx/D5xx/... | 81    |
| pci:10de-0425 | Nvidia      | G86M [GeForce 8600M GS]      | 80    |
| pci:10de-11fc | Nvidia      | GK106GLM [Quadro K2100M]     | 80    |
| pci:10de-13d8 | Nvidia      | GM204M [GeForce GTX 970M]    | 80    |
| pci:10de-1f07 | Nvidia      | TU106 [GeForce RTX 2070 R... | 80    |
| pci:10de-1e89 | Nvidia      | TU104 [GeForce RTX 2060]     | 79    |
| pci:1002-9598 | AMD         | RV635 [Radeon HD 3650/375... | 78    |
| pci:8086-2572 | Intel       | 82865G Integrated Graphic... | 78    |
| pci:10de-25a0 | Nvidia      | GA107M [GeForce RTX 3050 ... | 77    |
| pci:10de-0392 | Nvidia      | G73 [GeForce 7600 GS]        | 76    |
| pci:10de-08a0 | Nvidia      | MCP89 [GeForce 320M]         | 76    |
| pci:8086-3ea1 | Intel       | Coffee Lake UHD 610 Graph... | 76    |
| pci:1002-6821 | AMD         | Venus XT [Radeon HD 8870M... | 75    |
| pci:1002-71c5 | AMD         | RV530/M56-P [Mobility Rad... | 75    |
| pci:10de-0df8 | Nvidia      | GF108GL [Quadro 600]         | 75    |
| pci:10de-1cb3 | Nvidia      | GP107GL [Quadro P400]        | 75    |
| pci:8086-2a12 | Intel       | Mobile GME965/GLE960 Inte... | 75    |
| pci:8086-2a13 | Intel       | Mobile GME965/GLE960 Inte... | 75    |
| pci:8086-1906 | Intel       | HD Graphics 510              | 74    |
| pci:1002-68ba | AMD         | Juniper XT [Radeon HD 6770]  | 73    |
| pci:1002-9583 | AMD         | RV630/M76 [Mobility Radeo... | 73    |
| pci:10de-06eb | Nvidia      | G98M [Quadro NVS 160M]       | 73    |
| pci:10de-0ffc | Nvidia      | GK107GLM [Quadro K1000M]     | 73    |
| pci:10de-1c94 | Nvidia      | GP107M [GeForce MX350]       | 73    |
| pci:10de-1f14 | Nvidia      | TU106M [GeForce RTX 2070 ... | 73    |
| pci:10de-249d | Nvidia      | GA104M [GeForce RTX 3070 ... | 73    |
| pci:1002-9640 | AMD         | Sumo [Radeon HD 6550D]       | 72    |
| pci:10de-1f10 | Nvidia      | TU106M [GeForce RTX 2070 ... | 72    |
| pci:8086-0122 | Intel       | 2nd Generation Core Proce... | 72    |
| pci:1002-6606 | AMD         | Mars XTX [Radeon HD 8790M]   | 71    |
| pci:10de-0fdf | Nvidia      | GK107M [GeForce GT 740M]     | 71    |
| pci:10de-1382 | Nvidia      | GM107 [GeForce GTX 745]      | 71    |
| pci:8086-2993 | Intel       | 82Q963/Q965 Integrated Gr... | 71    |
| pci:1002-9998 | AMD         | Richland [Radeon HD 8370D]   | 70    |
| pci:10de-0400 | Nvidia      | G84 [GeForce 8600 GTS]       | 70    |
| pci:10de-1346 | Nvidia      | GM108M [GeForce 930M]        | 70    |
| pci:10de-1f97 | Nvidia      | TU117M [GeForce MX450]       | 70    |
| pci:8086-4c8a | Intel       | RocketLake-S GT1 [UHD Gra... | 70    |
| pci:10de-0322 | Nvidia      | NV34 [GeForce FX 5200]       | 69    |
| pci:10de-0422 | Nvidia      | G86 [GeForce 8400 GS]        | 69    |
| pci:10de-1d52 | Nvidia      | GP108BM [GeForce MX250]      | 69    |
| pci:10de-1e87 | Nvidia      | TU104 [GeForce RTX 2080 R... | 69    |
| pci:10de-05e2 | Nvidia      | GT200 [GeForce GTX 260]      | 68    |
| pci:10de-0611 | Nvidia      | G92 [GeForce 8800 GT]        | 68    |
| pci:10de-1180 | Nvidia      | GK104 [GeForce GTX 680]      | 68    |
| pci:10de-2206 | Nvidia      | GA102 [GeForce RTX 3080]     | 68    |
| pci:8086-8108 | Intel       | US15W/US15X SCH [Poulsbo]... | 68    |
| pci:10de-1055 | Nvidia      | GF119M [GeForce 410M]        | 67    |
| pci:1002-9581 | AMD         | RV630/M76 [Mobility Radeo... | 66    |
| pci:10de-0dfa | Nvidia      | GF108GLM [Quadro 1000M]      | 66    |
| pci:10de-1057 | Nvidia      | GF119M [Quadro NVS 4200M]    | 66    |
| pci:10de-1ba1 | Nvidia      | GP104M [GeForce GTX 1070 ... | 66    |
| pci:8086-29c3 | Intel       | 82G33/G31 Express Integra... | 66    |
| pci:1002-791e | AMD         | RS690 [Radeon X1200]         | 65    |
| pci:8086-0d26 | Intel       | Crystal Well Integrated G... | 65    |
| pci:1002-682f | AMD         | Chelsea LP [Radeon HD 7730M] | 64    |
| pci:1002-990c | AMD         | Richland [Radeon HD 8670D]   | 64    |
| pci:10de-0393 | Nvidia      | G73 [GeForce 7300 GT]        | 64    |
| pci:1002-66af | AMD         | Vega 20 [Radeon VII]         | 63    |
| pci:10de-0845 | Nvidia      | C77 [GeForce 8200M G]        | 63    |
| pci:10de-0a34 | Nvidia      | GT216M [GeForce GT 240M]     | 63    |
| pci:10de-13b6 | Nvidia      | GM107GLM [Quadro M1200 Mo... | 63    |
| pci:8086-0a1e | Intel       | Haswell-ULT High Definiti... | 63    |
| pci:1002-6823 | AMD         | Venus PRO [Radeon HD 8850... | 62    |
| pci:1002-94c8 | AMD         | RV610/M74 [Mobility Radeo... | 62    |
| pci:1002-9589 | AMD         | RV630 PRO [Radeon HD 2600... | 62    |
| pci:1002-964a | AMD         | Sumo [Radeon HD 6530D]       | 62    |
| pci:10de-0f01 | Nvidia      | GF108 [GeForce GT 620]       | 62    |
| pci:10de-0fd4 | Nvidia      | GK107M [GeForce GTX 660M]    | 62    |
| pci:10de-13bb | Nvidia      | GM107GL [Quadro K620]        | 62    |
| pci:1002-6898 | AMD         | Cypress XT [Radeon HD 5870]  | 61    |
| pci:1002-9588 | AMD         | RV630 XT [Radeon HD 2600 XT] | 61    |
| pci:10de-0141 | Nvidia      | NV43 [GeForce 6600]          | 61    |
| pci:10de-0def | Nvidia      | GF108M [NVS 5400M]           | 61    |
| pci:10de-0fd5 | Nvidia      | GK107M [GeForce GT 650M M... | 61    |
| pci:10de-1284 | Nvidia      | GK208 [GeForce GT 630 Rev... | 61    |
| pci:10de-1290 | Nvidia      | GK208M [GeForce GT 730M]     | 61    |
| pci:10de-1049 | Nvidia      | GF119 [GeForce GT 620 OEM]   | 60    |
| pci:8086-2972 | Intel       | 82946GZ/GL Integrated Gra... | 60    |
| pci:1002-9505 | AMD         | RV670 [Radeon HD 3690/3850]  | 59    |
| pci:10de-0a3c | Nvidia      | GT216GLM [Quadro FX 880M]    | 59    |
| pci:1002-9649 | AMD         | SuperSumo [Radeon HD 6480G]  | 57    |
| pci:10de-0398 | Nvidia      | G73M [GeForce Go 7600]       | 57    |
| pci:10de-01d3 | Nvidia      | G72 [GeForce 7200 GS / 73... | 56    |
| pci:10de-0648 | Nvidia      | G96CM [GeForce 9600M GS]     | 56    |
| pci:8086-1926 | Intel       | Iris Graphics 540            | 56    |
| pci:8086-591c | Intel       | UHD Graphics 615             | 56    |
| pci:1002-71c2 | AMD         | RV530 [Radeon X1600 PRO]     | 55    |
| pci:1002-71e2 | AMD         | RV530 [Radeon X1600] (Sec... | 55    |
| pci:1002-67b0 | AMD         | Hawaii XT / Grenada XT [R... | 54    |
| pci:1002-9540 | AMD         | RV710 [Radeon HD 4550]       | 54    |
| pci:10de-06ec | Nvidia      | G98M [GeForce G 105M]        | 54    |
| pci:10de-1cba | Nvidia      | GP107GLM [Quadro P2000 Mo... | 54    |
| pci:1002-675d | AMD         | Turks PRO [Radeon HD 7570]   | 53    |
| pci:1002-718a | AMD         | RV516/M64 [Mobility Radeo... | 53    |
| pci:1002-990f | AMD         | Richland [Radeon HD 8610G]   | 53    |
| pci:10de-1c60 | Nvidia      | GP106BM [GeForce GTX 1060... | 53    |
| pci:1002-68c0 | AMD         | Madison [Mobility Radeon ... | 52    |
| pci:1002-9555 | AMD         | RV710/M92 [Mobility Radeo... | 52    |
| pci:10de-0df1 | Nvidia      | GF108M [GeForce GT 420M]     | 52    |
| pci:1002-9440 | AMD         | RV770 [Radeon HD 4870]       | 51    |
| pci:1002-9488 | AMD         | RV730/M96-XT [Mobility Ra... | 51    |
| pci:10de-06e8 | Nvidia      | G98M [GeForce 9200M GS]      | 51    |
| pci:10de-0a2d | Nvidia      | GT216M [GeForce GT 320M]     | 51    |
| pci:10de-11c2 | Nvidia      | GK106 [GeForce GTX 650 Ti... | 51    |
| pci:10de-13ba | Nvidia      | GM107GL [Quadro K2200]       | 51    |
| pci:1002-130a | AMD         | Kaveri [Radeon R6 Graphics]  | 50    |
| pci:1002-7145 | AMD         | RV515/M54 [Mobility Radeo... | 50    |
| pci:1002-980a | AMD         | Wrestler [Radeon HD 7290]    | 50    |
| pci:10de-01df | Nvidia      | G72 [GeForce 7300 GS]        | 50    |
| pci:10de-06dd | Nvidia      | GF100GL [Quadro 4000]        | 50    |
| pci:10de-25a2 | Nvidia      | GA107M [GeForce RTX 3050 ... | 50    |
| pci:8086-4e71 | Intel       | JasperLake [UHD Graphics]    | 50    |
| pci:8086-8a5a | Intel       | Iris Plus Graphics G4 (Ic... | 50    |
| pci:1002-5b63 | AMD         | RV370 [Radeon X300/X550/X... | 49    |
| pci:1002-5b73 | AMD         | RV370 [Radeon X300/X550/X... | 49    |
| pci:1002-6742 | AMD         | Whistler LE [Radeon HD 66... | 49    |
| pci:1002-94c9 | AMD         | RV610/M72-S [Mobility Rad... | 49    |
| pci:10de-0a28 | Nvidia      | GT216M [GeForce GT 230M]     | 49    |
| pci:10de-0a74 | Nvidia      | GT218M [GeForce G210M]       | 49    |
| pci:10de-0ffa | Nvidia      | GK107GL [Quadro K600]        | 49    |
| pci:10de-1004 | Nvidia      | GK110 [GeForce GTX 780]      | 49    |
| pci:1002-6771 | AMD         | Caicos XTX [Radeon HD 849... | 48    |
| pci:10de-01d1 | Nvidia      | G72 [GeForce 7300 LE]        | 48    |
| pci:10de-0ffe | Nvidia      | GK107GL [Quadro K2000]       | 48    |
| pci:8086-29d2 | Intel       | 82Q33 Express Integrated ... | 48    |
| pci:1002-6899 | AMD         | Cypress PRO [Radeon HD 5850] | 47    |
| pci:8086-191d | Intel       | HD Graphics P530             | 47    |
| pci:1002-5974 | AMD         | RS482/RS485 [Radeon Xpres... | 46    |
| pci:1002-9836 | AMD         | Kabini [Radeon HD 8280 / ... | 46    |
| pci:10de-13b0 | NVIDIA      | GM107GLM [Quadro M2000M]     | 46    |
| pci:1002-9991 | AMD         | Trinity 2 [Radeon HD 7540D]  | 45    |
| pci:10de-0391 | Nvidia      | G73 [GeForce 7600 GT]        | 45    |
| pci:8086-4680 | Intel       | AlderLake-S GT1              | 45    |
| pci:1002-73ff | AMD         | Navi 23 [Radeon RX 6600/6... | 44    |
| pci:10de-087d | Nvidia      | C79 [ION]                    | 44    |
| pci:10de-1080 | Nvidia      | GF110 [GeForce GTX 580]      | 44    |
| pci:10de-11e2 | NVIDIA      | GK106M [GeForce GTX 765M]    | 44    |
| pci:10de-249c | Nvidia      | GA104M [GeForce RTX 3080 ... | 44    |
| pci:10de-2560 | Nvidia      | GA106M [GeForce RTX 3060 ... | 44    |
| pci:1039-6330 | Silicon ... | 661/741/760 PCI/AGP or 66... | 43    |
| pci:10de-0638 | Nvidia      | G94GL [Quadro FX 1800]       | 43    |
| pci:10de-0de2 | Nvidia      | GF108 [GeForce GT 420]       | 43    |
| pci:10de-0fe1 | Nvidia      | GK107M [GeForce GT 730M]     | 43    |
| pci:10de-1340 | Nvidia      | GM108M [GeForce 830M]        | 43    |
| pci:10de-1cbd | Nvidia      | GP107GLM [Quadro P620]       | 43    |
| pci:8086-29a2 | Intel       | 82G965 Integrated Graphic... | 43    |
| pci:1002-68bf | AMD         | Juniper PRO [Radeon HD 6750] | 42    |
| pci:10de-01d8 | Nvidia      | G72M [GeForce Go 7400]       | 42    |
| pci:10de-0531 | Nvidia      | C67 [GeForce 7150M / nFor... | 42    |
| pci:10de-0647 | Nvidia      | G96CM [GeForce 9600M GT]     | 42    |
| pci:10de-0659 | Nvidia      | G96CGL [Quadro FX 580]       | 42    |
| pci:10de-0a64 | Nvidia      | GT218 [ION]                  | 42    |
| pci:10de-0dea | Nvidia      | GF108M [GeForce 610M]        | 42    |
| pci:10de-0df0 | Nvidia      | GF108M [GeForce GT 425M]     | 42    |
| pci:8086-041a | Intel       | Xeon E3-1200 v3 Processor... | 42    |
| pci:1002-5955 | AMD         | RS480M [Mobility Radeon X... | 41    |
| pci:1002-7149 | AMD         | RV515/M52 [Mobility Radeo... | 41    |
| pci:1002-7942 | AMD         | RS600M [Radeon Xpress 1250]  | 41    |
| pci:1002-94c1 | AMD         | RV610 [Radeon HD 2400 PRO... | 41    |
| pci:10de-07e1 | Nvidia      | C73 [GeForce 7100 / nForc... | 41    |
| pci:10de-0ff3 | Nvidia      | GK107GL [Quadro K420]        | 41    |
| pci:10de-1e04 | Nvidia      | TU102 [GeForce RTX 2080 Ti]  | 41    |
| pci:1002-682b | AMD         | Cape Verde PRO / Venus LE... | 40    |
| pci:10de-0221 | Nvidia      | NV44A [GeForce 6200]         | 40    |
| pci:10de-0dec | Nvidia      | GF108M [GeForce GT 525M]     | 40    |
| pci:10de-11fa | Nvidia      | GK106GL [Quadro K4000]       | 40    |
| pci:10de-1d34 | Nvidia      | GP108GLM [Quadro P520]       | 40    |
| pci:10de-1e82 | Nvidia      | TU104 [GeForce RTX 2080]     | 40    |
| pci:8086-4c8b | Intel       | RocketLake-S GT1 [UHD Gra... | 40    |
| pci:1002-1309 | AMD         | Kaveri [Radeon R6/R7 Grap... | 39    |
| pci:1002-1315 | AMD         | Kaveri [Radeon R5 Graphics]  | 39    |
| pci:1002-990d | AMD         | Richland [Radeon HD 8550G]   | 39    |
| pci:1002-9992 | AMD         | Trinity 2 [Radeon HD 7420G]  | 39    |
| pci:10de-03d1 | Nvidia      | C61 [GeForce 6100 nForce ... | 39    |
| pci:10de-0429 | Nvidia      | G86M [Quadro NVS 140M]       | 39    |
| pci:10de-0533 | Nvidia      | C67 [GeForce 7000M / nFor... | 39    |
| pci:1002-6720 | AMD         | Blackcomb [Radeon HD 6970... | 38    |
| pci:1002-796e | AMD         | RS740 [Radeon 2100]          | 38    |
| pci:10de-0dda | Nvidia      | GF106GLM [Quadro 2000M]      | 38    |
| pci:10de-1f9d | Nvidia      | TU117M [GeForce GTX 1650 ... | 38    |
| pci:1002-5960 | AMD         | RV280 [Radeon 9200 PRO / ... | 37    |
| pci:10de-0de5 | Nvidia      | GF108 [GeForce GT 530]       | 37    |
| pci:10de-100a | Nvidia      | GK110B [GeForce GTX 780 Ti]  | 36    |
| pci:1002-5940 | AMD         | RV280 [Radeon 9200 PRO] (... | 35    |
| pci:1002-7142 | AMD         | RV515 PRO [Radeon X1300/X... | 35    |
| pci:1002-7146 | AMD         | RV515 [Radeon X1300/X1550]   | 35    |
| pci:1002-7162 | AMD         | RV515 PRO [Radeon X1300/X... | 35    |
| pci:1002-7166 | AMD         | RV515 [Radeon X1300/X1550... | 35    |
| pci:1002-9611 | AMD         | RS780C [Radeon 3100]         | 35    |
| pci:1002-9714 | AMD         | RS880 [Radeon HD 4290]       | 35    |
| pci:1002-9852 | AMD         | Mullins [Radeon R2 Graphics] | 35    |
| pci:10de-0de8 | Nvidia      | GF108M [GeForce GT 620M]     | 35    |
| pci:10de-0fd3 | Nvidia      | GK107M [GeForce GT 640M LE]  | 35    |
| pci:10de-2486 | Nvidia      | GA104 [GeForce RTX 3060 Ti]  | 35    |
| pci:10de-2503 | Nvidia      | GA106 [GeForce RTX 3060]     | 35    |
| pci:1002-68a1 | AMD         | Broadway PRO [Mobility Ra... | 34    |
| pci:1002-6938 | AMD         | Tonga XT / Amethyst XT [R... | 34    |
| pci:1002-9839 | AMD         | Kabini [Radeon HD 8180]      | 34    |
| pci:10de-0161 | Nvidia      | NV44 [GeForce 6200 TurboC... | 34    |
| pci:10de-0193 | Nvidia      | G80 [GeForce 8800 GTS]       | 34    |
| pci:10de-0426 | Nvidia      | G86M [GeForce 8400M GT]      | 34    |
| pci:10de-0fe9 | Nvidia      | GK107M [GeForce GT 750M M... | 34    |
| pci:10de-0ffb | Nvidia      | GK107GLM [Quadro K2000M]     | 34    |
| pci:10de-11e0 | Nvidia      | GK106M [GeForce GTX 770M]    | 34    |
| pci:10de-1251 | Nvidia      | GF116M [GeForce GT 560M]     | 34    |
| pci:10de-1b83 | Nvidia      | GP104 [GeForce GTX 1060 6GB] | 34    |
| pci:8086-3582 | Intel       | 82852/855GM Integrated Gr... | 34    |
| pci:8086-5927 | Intel       | Iris Plus Graphics 650       | 34    |
| pci:1002-694c | AMD         | Polaris 22 XT [Radeon RX ... | 33    |
| pci:1002-6985 | AMD         | Lexa XT [Radeon PRO WX 3100] | 33    |
| pci:1002-9501 | AMD         | RV670 [Radeon HD 3870]       | 33    |
| pci:10de-042f | Nvidia      | G86 [Quadro NVS 290]         | 33    |
| pci:10de-0866 | Nvidia      | C79 [GeForce 9400M G]        | 33    |
| pci:10de-0867 | Nvidia      | C79 [GeForce 9400]           | 33    |
| pci:10de-11e3 | Nvidia      | GK106M [GeForce GTX 760M]    | 33    |
| pci:10de-1298 | Nvidia      | GK208M [GeForce GT 720M]     | 33    |
| pci:8086-0406 | Intel       | Haswell Integrated Graphi... | 33    |
| pci:1002-4150 | AMD         | RV350 [Radeon 9550/9600/X... | 32    |
| pci:1002-5460 | AMD         | RV370/M22 [Mobility Radeo... | 32    |
| pci:1002-5a61 | AMD         | RC410 [Radeon Xpress 200/... | 32    |
| pci:1002-6981 | AMD         | Lexa XT [Radeon PRO WX 3200] | 32    |
| pci:102b-0536 | Matrox E... | Integrated Matrox G200eW3... | 32    |
| pci:10de-0a23 | Nvidia      | GT216 [GeForce 210]          | 32    |
| pci:8086-3e93 | Intel       | CoffeeLake-S GT1 [UHD Gra... | 32    |
| pci:1002-4170 | AMD         | RV350 [Radeon 9550/9600/X... | 31    |
| pci:1002-665c | AMD         | Bonaire XT [Radeon HD 779... | 31    |
| pci:10de-0244 | Nvidia      | C51 [GeForce Go 6150]        | 31    |
| pci:10de-0247 | Nvidia      | C51 [GeForce Go 6100]        | 31    |
| pci:10de-0326 | Nvidia      | NV34 [GeForce FX 5500]       | 31    |
| pci:10de-0652 | Nvidia      | G96CM [GeForce GT 130M]      | 31    |
| pci:10de-2489 | Nvidia      | GA104 [GeForce RTX 3060 T... | 31    |
| pci:1002-68da | AMD         | Redwood LE [Radeon HD 555... | 30    |
| pci:10de-0140 | Nvidia      | NV43 [GeForce 6600 GT]       | 30    |
| pci:10de-0241 | Nvidia      | C51 [GeForce 6150 LE]        | 30    |
| pci:10de-084b | Nvidia      | C77 [GeForce 8200]           | 30    |
| pci:10de-0a60 | Nvidia      | GT218 [GeForce G210]         | 30    |
| pci:10de-107d | Nvidia      | GF119 [NVS 310]              | 30    |
| pci:10de-1be0 | Nvidia      | GP104BM [GeForce GTX 1080... | 30    |
| pci:10de-1f36 | Nvidia      | TU106GLM [Quadro RTX 3000... | 30    |
| pci:10de-2504 | Nvidia      | GA106 [GeForce RTX 3060 L... | 30    |
| pci:8086-193b | Intel       | Iris Pro Graphics 580        | 30    |
| pci:1002-68a0 | AMD         | Broadway XT [Mobility Rad... | 29    |
| pci:1002-9614 | AMD         | RS780D [Radeon HD 3300]      | 29    |
| pci:1033-0165 | NEC Comp... | NEC61253 Tuner               | 29    |
| pci:10de-0873 | Nvidia      | C79 [GeForce G102M]          | 29    |
| pci:10de-0fc2 | Nvidia      | GK107 [GeForce GT 630 OEM]   | 29    |
| pci:10de-0fe3 | Nvidia      | GK107M [GeForce GT 745M]     | 29    |
| pci:10de-107c | Nvidia      | GF119 [NVS 315]              | 29    |
| pci:10de-1247 | Nvidia      | GF116M [GeForce GT 555M/6... | 29    |
| pci:10de-1e91 | Nvidia      | TU104M [GeForce RTX 2070 ... | 29    |
| pci:8086-9b21 | Intel       | Comet Lake UHD Graphics      | 29    |
| pci:1002-4153 | AMD         | RV350 [Radeon 9550]          | 28    |
| pci:1002-4173 | AMD         | RV350 [Radeon 9550] (Seco... | 28    |
| pci:1002-6664 | AMD         | Jet XT [Radeon R5 M240]      | 28    |
| pci:1002-6901 | AMD         | Topaz PRO [Radeon R5 M255]   | 28    |
| pci:10de-0292 | Nvidia      | G71 [GeForce 7900 GS]        | 28    |
| pci:10de-0401 | Nvidia      | G84 [GeForce 8600 GT]        | 28    |
| pci:10de-0428 | Nvidia      | G86M [GeForce 8400M G]       | 28    |
| pci:10de-0caf | Nvidia      | GT215M [GeForce GT 335M]     | 28    |
| pci:10de-0e23 | Nvidia      | GF104 [GeForce GTX 460 SE]   | 28    |
| pci:10de-1086 | Nvidia      | GF110 [GeForce GTX 570 Re... | 28    |
| pci:10de-11b6 | Nvidia      | GK104GLM [Quadro K3100M]     | 28    |
| pci:10de-1c30 | Nvidia      | GP106GL [Quadro P2000]       | 28    |
| pci:8086-9ba8 | Intel       | CometLake-S GT1 [UHD Grap... | 28    |
| pci:1002-5b62 | AMD         | RV370 [Radeon X600/X600 SE]  | 27    |
| pci:1002-5b72 | AMD         | RV380 [Radeon X300/X550/X... | 27    |
| pci:1002-675b | AMD         | Turks [Radeon HD 7600 Ser... | 27    |
| pci:1002-9644 | AMD         | SuperSumo [Radeon HD 6410D]  | 27    |
| pci:10de-0181 | Nvidia      | NV18 [GeForce4 MX 440 AGP... | 27    |
| pci:10de-0405 | Nvidia      | G84M [GeForce 9500M GS]      | 27    |
| pci:10de-0849 | Nvidia      | C77 [GeForce 8200]           | 27    |
| pci:10de-1054 | Nvidia      | GF119M [GeForce 410M]        | 27    |
| pci:10de-13d7 | Nvidia      | GM204M [GeForce GTX 980M]    | 27    |
| pci:10de-17c2 | Nvidia      | GM200 [GeForce GTX TITAN X]  | 27    |
| pci:10de-1cb6 | Nvidia      | GP107GL [Quadro P620]        | 27    |
| pci:10de-2188 | Nvidia      | TU116 [GeForce GTX 1650]     | 27    |
| pci:18ca-0020 | XGI Tech... | Z7/Z9 (XG20 core)            | 27    |
| pci:1002-6820 | AMD         | Venus XTX [Radeon HD 8890... | 26    |
| pci:10de-0861 | Nvidia      | C79 [GeForce 9400]           | 26    |
| pci:10de-0a2c | Nvidia      | GT216M [NVS 5100M]           | 26    |
| pci:10de-1081 | Nvidia      | GF110 [GeForce GTX 570]      | 26    |
| pci:10de-10c5 | Nvidia      | GT218 [GeForce 405]          | 26    |
| pci:10de-10d8 | Nvidia      | GT218 [NVS 300]              | 26    |
| pci:1106-3343 | VIA Tech... | P4M890 [S3 UniChrome Pro]    | 26    |
| pci:1002-5653 | AMD         | RV410/M26 [Mobility Radeo... | 25    |
| pci:1002-95c2 | AMD         | RV620/M82 [Mobility Radeo... | 25    |
| pci:1002-9613 | AMD         | RS780MC [Mobility Radeon ... | 25    |
| pci:1002-983d | AMD         | Temash [Radeon HD 8250/82... | 25    |
| pci:10de-0242 | Nvidia      | C51G [GeForce 6100]          | 25    |
| pci:10de-040f | Nvidia      | G84GL [Quadro FX 1700]       | 25    |
| pci:10de-053b | Nvidia      | C68 [GeForce 7050 PV / nF... | 25    |
| pci:10de-06e0 | Nvidia      | G98 [GeForce 9300 GE]        | 25    |
| pci:10de-0869 | Nvidia      | MCP7A [GeForce 9400]         | 25    |
| pci:10de-0a66 | Nvidia      | GT218 [GeForce 310]          | 25    |
| pci:10de-0ca5 | Nvidia      | GT215 [GeForce GT 220]       | 25    |
| pci:10de-0dd1 | Nvidia      | GF106M [GeForce GTX 460M]    | 25    |
| pci:10de-0fcd | Nvidia      | GK107M [GeForce GT 755M]     | 25    |
| pci:10de-1c92 | Nvidia      | GP107M [GeForce GTX 1050 ... | 25    |
| pci:1002-6605 | AMD         | Opal PRO [Radeon R7 M260X]   | 24    |
| pci:10de-042b | Nvidia      | G86M [Quadro NVS 135M]       | 24    |
| pci:10de-06fd | Nvidia      | G98 [Quadro NVS 295]         | 24    |
| pci:10de-0a68 | Nvidia      | GT218M [GeForce G 105M]      | 24    |
| pci:10de-0ffd | Nvidia      | GK107 [NVS 510]              | 24    |
| pci:10de-1185 | Nvidia      | GK104 [GeForce GTX 660 OEM]  | 24    |
| pci:10de-134b | Nvidia      | GM108M [GeForce 940MX]       | 24    |
| pci:10de-1436 | Nvidia      | GM206GLM [Quadro M2200 Mo... | 24    |
| pci:10de-1cb1 | Nvidia      | GP107GL [Quadro P1000]       | 24    |
| pci:10de-2208 | Nvidia      | GA102 [GeForce RTX 3080 Ti]  | 24    |
| pci:1106-3344 | VIA Tech... | CN700/P4M800 Pro/P4M800 C... | 24    |
| pci:8086-3e96 | Intel       | CoffeeLake-S GT2 [UHD Gra... | 24    |
| pci:1002-5954 | AMD         | RS480 [Radeon Xpress 200 ... | 23    |
| pci:1002-68fa | AMD         | Cedar [Radeon HD 7350/835... | 23    |
| pci:1002-7188 | AMD         | RV516/M64-S [Mobility Rad... | 23    |
| pci:10de-06cd | Nvidia      | GF100 [GeForce GTX 470]      | 23    |
| pci:10de-06ef | Nvidia      | G98M [GeForce G 103M]        | 23    |
| pci:10de-0a35 | Nvidia      | GT216M [GeForce GT 325M]     | 23    |
| pci:10de-0a76 | Nvidia      | GT218M [ION 2]               | 23    |
| pci:10de-0ca2 | Nvidia      | GT215 [GeForce GT 320]       | 23    |
| pci:1002-673e | AMD         | Barts LE [Radeon HD 6790]    | 22    |
| pci:1002-689e | AMD         | Cypress LE [Radeon HD 5830]  | 22    |
| pci:1002-7300 | AMD         | Fiji [Radeon R9 FURY / NA... | 22    |
| pci:10de-0110 | Nvidia      | NV11 [GeForce2 MX/MX 400]    | 22    |
| pci:10de-0605 | Nvidia      | G92 [GeForce 9800 GT]        | 22    |
| pci:10de-0610 | Nvidia      | G92 [GeForce 9600 GSO]       | 22    |
| pci:10de-065b | Nvidia      | G96C [GeForce 9400 GT]       | 22    |
| pci:10de-065c | Nvidia      | G96GLM [Quadro FX 770M]      | 22    |
| pci:10de-0fc0 | Nvidia      | GK107 [GeForce GT 640 OEM]   | 22    |
| pci:10de-1213 | Nvidia      | GF114M [GeForce GTX 670M]    | 22    |
| pci:10de-1c8f | Nvidia      | GP107M [GeForce GTX 1050 ... | 22    |
| pci:10de-1f0a | Nvidia      | TU106 [GeForce GTX 1650]     | 22    |
| pci:10de-2216 | Nvidia      | GA102 [GeForce RTX 3080 L... | 22    |
| pci:10de-24dd | Nvidia      | GA104M [GeForce RTX 3070 ... | 22    |
| pci:1002-5874 | AMD         | RS480 [Radeon Xpress 1150... | 21    |
| pci:1002-7183 | AMD         | RV516 [Radeon X1300/X1550... | 21    |
| pci:1002-71a3 | AMD         | RV516 [Radeon X1300/X1550... | 21    |
| pci:1002-9460 | AMD         | RV790 [Radeon HD 4890]       | 21    |
| pci:1002-9645 | AMD         | SuperSumo [Radeon HD 6410D]  | 21    |
| pci:10de-05e3 | Nvidia      | GT200b [GeForce GTX 285]     | 21    |
| pci:10de-05e6 | Nvidia      | GT200b [GeForce GTX 275]     | 21    |
| pci:10de-0df6 | Nvidia      | GF108M [GeForce GT 550M]     | 21    |
| pci:10de-105a | Nvidia      | GF119M [GeForce 610M]        | 21    |
| pci:10de-13b4 | Nvidia      | GM107GLM [Quadro M620 Mob... | 21    |
| pci:1106-3108 | VIA Tech... | K8M800/K8N800/K8N800A [S3... | 21    |
| pci:8086-591d | Intel       | HD Graphics P630             | 21    |
| pci:1002-682d | AMD         | Chelsea XT GL [FirePro M4... | 20    |
| pci:1002-6995 | AMD         | Lexa XT [Radeon PRO WX 2100] | 20    |
| pci:1002-9495 | AMD         | RV730 [Radeon HD 4600 AGP... | 20    |
| pci:1002-9803 | AMD         | Wrestler [Radeon HD 6310]    | 20    |
| pci:1002-9999 | AMD         | Richland [Radeon HD 8510G]   | 20    |
| pci:10de-0654 | Nvidia      | G96CM [GeForce GT 220M]      | 20    |
| pci:10de-086e | Nvidia      | C79 [GeForce 9100M G]        | 20    |
| pci:10de-0dcd | Nvidia      | GF106M [GeForce GT 555M]     | 20    |
| pci:10de-0dce | Nvidia      | GF106M [GeForce GT 555M]     | 20    |
| pci:10de-0df7 | Nvidia      | GF108M [GeForce GT 520M]     | 20    |
| pci:10de-11c8 | Nvidia      | GK106 [GeForce GTX 650 OEM]  | 20    |
| pci:10de-13f1 | Nvidia      | GM204GL [Quadro M4000]       | 20    |
| pci:10de-1bb1 | Nvidia      | GP104GL [Quadro P4000]       | 20    |
| pci:10de-1c90 | Nvidia      | GP107M [GeForce MX150]       | 20    |
| pci:10de-1f50 | Nvidia      | TU106BM [GeForce RTX 2070... | 20    |
| pci:10de-1fbb | Nvidia      | TU117GLM [Quadro T500 Mob... | 20    |
| pci:8086-2782 | Intel       | 82915G Integrated Graphic... | 20    |
| pci:8086-3e94 | Intel       | Coffee Lake UHD Graphics ... | 20    |
| pci:1002-4152 | AMD         | RV360 [Radeon 9600/X1050 ... | 19    |
| pci:1002-4172 | AMD         | RV350 [Radeon 9600/X1050 ... | 19    |
| pci:1002-4c57 | AMD         | RV200/M7 [Mobility Radeon... | 19    |
| pci:1002-4e50 | AMD         | RV350/M10 / RV360/M11 [Mo... | 19    |
| pci:1002-9643 | AMD         | SuperSumo [Radeon HD 6380G]  | 19    |
| pci:10de-05fe | Nvidia      | GT200GL [Quadro FX 4800]     | 19    |
| pci:10de-086f | Nvidia      | MCP79 [GeForce 8200M G]      | 19    |
| pci:10de-0876 | Nvidia      | C79 [GeForce 9400M / ION]    | 19    |
| pci:10de-0a22 | Nvidia      | GT216 [GeForce 315]          | 19    |
| pci:10de-0fee | Nvidia      | GK107M [GeForce 810M]        | 19    |
| pci:10de-104c | Nvidia      | GF119 [GeForce GT 705]       | 19    |
| pci:10de-1198 | Nvidia      | GK104M [GeForce GTX 880M]    | 19    |
| pci:10de-1617 | Nvidia      | GM204M [GeForce GTX 980M]    | 19    |
| pci:10de-1e90 | Nvidia      | TU104M [GeForce RTX 2080 ... | 19    |
| pci:1a0a-6202 | Blackmagic  | Multimedia video controller  | 19    |
| pci:8086-0d22 | Intel       | Crystal Well Integrated I... | 19    |
| pci:1002-6640 | AMD         | Saturn XT [FirePro M6100]    | 18    |
| pci:1002-68a8 | AMD         | Granville [Radeon HD 6850... | 18    |
| pci:1002-7280 | AMD         | RV570 [Radeon X1950 PRO]     | 18    |
| pci:1002-72a0 | AMD         | RV570 [Radeon X1950 PRO] ... | 18    |
| pci:1002-944a | AMD         | RV770/M98L [Mobility Rade... | 18    |
| pci:1002-990a | AMD         | Trinity [Radeon HD 7500G]    | 18    |
| pci:1002-9995 | AMD         | Richland [Radeon HD 8450G]   | 18    |
| pci:10de-040c | Nvidia      | G84GLM [Quadro FX 570M]      | 18    |
| pci:10de-0612 | Nvidia      | G92 [GeForce 9800 GTX / 9... | 18    |
| pci:10de-0644 | Nvidia      | G96 [GeForce 9500 GS]        | 18    |
| pci:10de-0de4 | Nvidia      | GF108 [GeForce GT 520]       | 18    |
| pci:10de-0e3a | Nvidia      | GF104GLM [Quadro 3000M]      | 18    |
| pci:10de-11b4 | Nvidia      | GK104GL [Quadro K4200]       | 18    |
| pci:10de-11be | Nvidia      | GK104GLM [Quadro K3000M]     | 18    |
| pci:10de-1e93 | Nvidia      | TU104M [GeForce RTX 2080 ... | 18    |
| pci:1002-6718 | AMD         | Cayman XT [Radeon HD 6970]   | 17    |
| pci:102b-0530 | Matrox E... | MGA G200EV                   | 17    |
| pci:10de-0404 | Nvidia      | G84 [GeForce 8400 GS]        | 17    |
| pci:10de-040d | Nvidia      | G84GLM [Quadro FX 1600M]     | 17    |
| pci:10de-0fd8 | Nvidia      | GK107M [GeForce GT 640M M... | 17    |
| pci:10de-0fd9 | Nvidia      | GK107M [GeForce GT 645M]     | 17    |
| pci:10de-1199 | Nvidia      | GK104M [GeForce GTX 870M]    | 17    |
| pci:10de-1280 | Nvidia      | GK208 [GeForce GT 635]       | 17    |
| pci:10de-1c96 | Nvidia      | GP107M [GeForce MX350]       | 17    |
| pci:10de-1e02 | Nvidia      | TU102 [TITAN RTX]            | 17    |
| pci:10de-1eb1 | Nvidia      | TU104GL [Quadro RTX 4000]    | 17    |
| pci:1106-3230 | VIA Tech... | K8M890CE/K8N890CE [Chrome 9] | 17    |
| pci:8086-9a40 | Intel       | Tiger Lake Iris Xe Graphics  | 17    |
| pci:1002-4752 | AMD         | Rage 3 [Rage XL PCI]         | 16    |
| pci:1002-5964 | AMD         | RV280 [Radeon 9200 SE]       | 16    |
| pci:1002-6649 | AMD         | Bonaire [FirePro W5100]      | 16    |
| pci:1002-67c7 | AMD         | Ellesmere [Radeon Pro WX ... | 16    |
| pci:1002-6801 | AMD         | Neptune XT [Radeon HD 8970M] | 16    |
| pci:1002-6837 | AMD         | Cape Verde LE [Radeon HD ... | 16    |
| pci:1002-71c7 | AMD         | RV535 [Radeon X1650 PRO]     | 16    |
| pci:1002-71e7 | AMD         | RV535 [Radeon X1650 PRO] ... | 16    |
| pci:1002-9805 | AMD         | Wrestler [Radeon HD 6250]    | 16    |
| pci:1002-9833 | AMD         | Kabini [Radeon HD 8330E]     | 16    |
| pci:1002-9908 | AMD         | Trinity [Radeon HD 7600G]    | 16    |
| pci:10de-05ff | Nvidia      | GT200GL [Quadro FX 3800]     | 16    |
| pci:10de-0613 | Nvidia      | G92 [GeForce 9800 GTX+]      | 16    |
| pci:10de-061d | Nvidia      | G92GLM [Quadro FX 2800M]     | 16    |
| pci:10de-064c | Nvidia      | G96CM [GeForce 9650M GT]     | 16    |
| pci:10de-06e5 | Nvidia      | G98M [GeForce 9300M GS]      | 16    |
| pci:10de-0844 | Nvidia      | C77 [GeForce 9100M G]        | 16    |
| pci:10de-08a4 | Nvidia      | MCP89 [GeForce 320M]         | 16    |
| pci:10de-0a2b | Nvidia      | GT216M [GeForce GT 330M]     | 16    |
| pci:10de-0a6f | Nvidia      | GT218M [ION]                 | 16    |
| pci:10de-124d | Nvidia      | GF116M [GeForce GT 555M/6... | 16    |
| pci:10de-1407 | Nvidia      | GM206 [GeForce GTX 750 v2]   | 16    |
| pci:10de-1d33 | Nvidia      | GP108GLM [Quadro P500 Mob... | 16    |
| pci:8086-2562 | Intel       | 82845G/GL[Brookdale-G]/GE... | 16    |
| pci:8086-4e55 | Intel       | JasperLake [UHD Graphics]    | 16    |
| pci:8086-9a68 | Intel       | TigerLake-H GT1 [UHD Grap... | 16    |
| pci:1002-1318 | AMD         | Kaveri [Radeon R5 Graphics]  | 15    |
| pci:1002-3150 | AMD         | RV380/M24 [Mobility Radeo... | 15    |
| pci:1002-6608 | AMD         | Oland GL [FirePro W2100]     | 15    |
| pci:1002-6751 | AMD         | Turks [Radeon HD 7650A/76... | 15    |
| pci:1002-7187 | AMD         | RV516 [Radeon X1300/X1550... | 15    |
| pci:1002-71a7 | AMD         | RV516 [Radeon X1300/X1550... | 15    |
| pci:1002-71c6 | AMD         | RV530LE [Radeon X1600/X16... | 15    |
| pci:1002-71e6 | AMD         | RV530 [Radeon X1650] (Sec... | 15    |
| pci:1002-7210 | AMD         | RV550/M71 [Mobility Radeo... | 15    |
| pci:1002-7288 | AMD         | RV570 [Radeon X1950 GT]      | 15    |
| pci:1002-72a8 | AMD         | RV570 [Radeon X1950 GT] (... | 15    |
| pci:1002-94b3 | AMD         | RV740 PRO [Radeon HD 4770]   | 15    |
| pci:10de-016a | Nvidia      | NV44 [GeForce 7100 GS]       | 15    |
| pci:10de-0240 | Nvidia      | C51PV [GeForce 6150]         | 15    |
| pci:10de-040e | Nvidia      | G84GL [Quadro FX 570]        | 15    |
| pci:10de-042e | Nvidia      | G86M [GeForce 9300M G]       | 15    |
| pci:10de-063a | Nvidia      | G94GLM [Quadro FX 2700M]     | 15    |
| pci:10de-0646 | Nvidia      | G96C [GeForce GT 120]        | 15    |
| pci:10de-1048 | Nvidia      | GF119 [GeForce 605]          | 15    |
| pci:10de-1282 | Nvidia      | GK208 [GeForce GT 640 Rev... | 15    |
| pci:10de-1618 | Nvidia      | GM204M [GeForce GTX 970M]    | 15    |
| pci:10de-1b02 | Nvidia      | GP102 [TITAN Xp]             | 15    |
| pci:10de-1c31 | Nvidia      | GP106GL [Quadro P2200]       | 15    |
| pci:10de-1eba | Nvidia      | 3D controller                | 15    |
| pci:10de-1ed3 | Nvidia      | TU104BM [GeForce RTX 2080... | 15    |
| pci:10de-2192 | Nvidia      | TU116M [GeForce GTX 1650 ... | 15    |
| pci:8086-1927 | Intel       | Iris Graphics 550            | 15    |
| pci:8086-9bf6 | Intel       | Comet Lake-H WS GT2 Integ... | 15    |
| pci:1002-6770 | AMD         | Caicos [Radeon HD 6450A/7... | 14    |
| pci:1002-9907 | AMD         | Trinity [Radeon HD 7620G]    | 14    |
| pci:10de-06c0 | Nvidia      | GF100 [GeForce GTX 480]      | 14    |
| pci:10de-08a2 | Nvidia      | MCP89 [GeForce 320M]         | 14    |
| pci:10de-119f | NVIDIA      | GK104M [GeForce GTX 780M]    | 14    |
| pci:10de-1243 | Nvidia      | GF116 [GeForce GT 545]       | 14    |
| pci:10de-12b9 | Nvidia      | GK208GLM [Quadro K610M]      | 14    |
| pci:10de-137a | Nvidia      | GM108GLM [Quadro K620M / ... | 14    |
| pci:10de-1c83 | Nvidia      | GP107 [GeForce GTX 1050 3GB] | 14    |
| pci:10de-1cbc | Nvidia      | GP107GLM [Quadro P600 Mob... | 14    |
| pci:10de-1ed0 | Nvidia      | TU104BM [GeForce RTX 2080... | 14    |
| pci:1ade-3038 | Spin Master | PCIe Video Bridge            | 14    |
| pci:8086-016a | Intel       | Xeon E3-1200 v2/3rd Gen C... | 14    |
| pci:8086-1612 | Intel       | HD Graphics 5600             | 14    |
| pci:8086-8a53 | Intel       | Ice Lake Iris Plus Graphi... | 14    |
| pci:1002-5159 | AMD         | RV100 [Radeon 7000 / Rade... | 13    |
| pci:1002-5d44 | AMD         | RV280 [Radeon 9200 SE] (S... | 13    |
| pci:1002-6617 | AMD         | Radeon R7 240                | 13    |
| pci:1002-674a | AMD         | Turks GL [FirePro V3900]     | 13    |
| pci:1002-71c1 | AMD         | RV535 [Radeon X1650 PRO]     | 13    |
| pci:1002-71de | AMD         | RV530/M66 [Mobility Radeo... | 13    |
| pci:1002-71e1 | AMD         | RV535 [Radeon X1650 PRO] ... | 13    |
| pci:10de-0603 | Nvidia      | G92 [GeForce GT 230 OEM]     | 13    |
| pci:10de-0625 | Nvidia      | G94 [GeForce 9600 GSO 512]   | 13    |
| pci:10de-1eb6 | Nvidia      | TU104GLM [Quadro RTX 4000... | 13    |
| pci:10de-25a5 | Nvidia      | GA107M [GeForce RTX 3050 ... | 13    |
| pci:1106-7122 | VIA Tech... | VX900 Graphics [Chrome9 HD]  | 13    |
| pci:1002-3e50 | AMD         | RV380 [Radeon X550/X600]     | 12    |
| pci:1002-5e4b | AMD         | RV410 [Radeon X700 PRO]      | 12    |
| pci:1002-5e6b | AMD         | RV410 [Radeon X700 PRO] (... | 12    |
| pci:1002-679e | AMD         | Tahiti LE [Radeon HD 7870... | 12    |
| pci:1002-6800 | AMD         | Wimbledon XT [Radeon HD 7... | 12    |
| pci:1002-682c | AMD         | Cape Verde GL [FirePro W4... | 12    |
| pci:1002-95c0 | AMD         | RV620 PRO [Radeon HD 3470]   | 12    |
| pci:102b-0538 | Matrox E... | MGA G200eH3                  | 12    |
| pci:10de-0163 | Nvidia      | NV44 [GeForce 6200 LE]       | 12    |
| pci:10de-0403 | Nvidia      | G84 [GeForce 8600 GS]        | 12    |
| pci:10de-0cbc | Nvidia      | GT215GLM [Quadro FX 1800M]   | 12    |
| pci:10de-0deb | Nvidia      | GF108M [GeForce GT 555M]     | 12    |
| pci:10de-11c4 | Nvidia      | GK106 [GeForce GTX 645 OEM]  | 12    |
| pci:10de-1208 | Nvidia      | GF114 [GeForce GTX 560 SE]   | 12    |
| pci:10de-1427 | Nvidia      | GM206M [GeForce GTX 965M]    | 12    |
| pci:10de-1f51 | Nvidia      | TU106BM [GeForce RTX 2060... | 12    |
| pci:10de-1fbc | Nvidia      | TU117GLM [T1200 Laptop GPU]  | 12    |
| pci:8086-1622 | Intel       | Iris Pro Graphics 6200       | 12    |
| pci:8086-2e42 | Intel       | 4 Series Chipset Integrat... | 12    |
| pci:8086-2e43 | Intel       | 4 Series Chipset Integrat... | 12    |
| pci:1002-130d | AMD         | Kaveri [Radeon R6 Graphics]  | 11    |
| pci:1002-3e70 | AMD         | RV380 [Radeon X550/X600] ... | 11    |
| pci:1002-5961 | AMD         | RV280 [Radeon 9200]          | 11    |
| pci:1002-6607 | AMD         | Mars LE [Radeon HD 8530M ... | 11    |
| pci:1002-7196 | AMD         | RV516/M62-S [Mobility Rad... | 11    |
| pci:1002-7291 | AMD         | RV560 [Radeon X1650 XT]      | 11    |
| pci:1002-72b1 | AMD         | RV560 [Radeon X1650 XT] (... | 11    |
| pci:1002-95c6 | AMD         | RV620 LE [Radeon HD 3450 ... | 11    |
| pci:10de-01dd | Nvidia      | G72 [GeForce 7500 LE]        | 11    |
| pci:10de-0298 | Nvidia      | G71M [GeForce Go 7900 GS]    | 11    |
| pci:10de-0410 | Nvidia      | G92 [GeForce GT 330]         | 11    |
| pci:10de-0600 | Nvidia      | G92 [GeForce 8800 GTS 512]   | 11    |
| pci:10de-07e3 | Nvidia      | C73 [GeForce 7050 / nForc... | 11    |
| pci:10de-0848 | Nvidia      | C77 [GeForce 8300]           | 11    |
| pci:10de-0cb1 | Nvidia      | GT215M [GeForce GTS 360M]    | 11    |
| pci:10de-1188 | Nvidia      | GK104 [GeForce GTX 690]      | 11    |
| pci:10de-1286 | Nvidia      | GK208 [GeForce GT 720]       | 11    |
| pci:10de-1291 | Nvidia      | GK208M [GeForce GT 735M]     | 11    |
| pci:10de-13bc | Nvidia      | GM107GL [Quadro K1200]       | 11    |
| pci:10de-1e30 | Nvidia      | TU102GL [Quadro RTX 6000/... | 11    |
| pci:10de-1ed1 | Nvidia      | TU104BM [GeForce RTX 2070... | 11    |
| pci:10de-1f9c | Nvidia      | TU117M [GeForce MX450]       | 11    |
| pci:10de-2488 | Nvidia      | GA104 [GeForce RTX 3070 L... | 11    |
| pci:8086-2982 | Intel       | 82G35 Express Integrated ... | 11    |
| pci:8086-2983 | Intel       | 82G35 Express Integrated ... | 11    |
| pci:bdbd-a139 | Blackmag... | Intensity Pro 4K             | 11    |
| pci:1002-68c8 | AMD         | Redwood XT GL [FirePro V4... | 10    |
| pci:1002-9593 | AMD         | RV635/M86 [Mobility Radeo... | 10    |
| pci:1002-9837 | AMD         | Kabini [Radeon HD 8280E]     | 10    |
| pci:1002-9854 | AMD         | Mullins [Radeon R3E Graph... | 10    |
| pci:10de-0148 | Nvidia      | NV43M [GeForce Go 6600]      | 10    |
| pci:10de-0171 | Nvidia      | NV17 [GeForce4 MX 440]       | 10    |
| pci:10de-0191 | Nvidia      | G80 [GeForce 8800 GTX]       | 10    |
| pci:10de-0409 | Nvidia      | G84M [GeForce 8700M GT]      | 10    |
| pci:10de-0623 | Nvidia      | G94 [GeForce 9600 GS]        | 10    |
| pci:10de-06c4 | Nvidia      | GF100 [GeForce GTX 465]      | 10    |
| pci:10de-06e1 | Nvidia      | G98 [GeForce 9300 GS]        | 10    |
| pci:10de-06e6 | Nvidia      | G98 [GeForce G 100]          | 10    |
| pci:10de-08a3 | Nvidia      | MCP89 [GeForce 320M]         | 10    |
| pci:10de-0a63 | Nvidia      | GT218 [GeForce 310]          | 10    |
| pci:10de-0ded | Nvidia      | GF108M [GeForce GT 520M]     | 10    |
| pci:10de-11bd | Nvidia      | GK104GLM [Quadro K4000M]     | 10    |
| pci:10de-1281 | Nvidia      | GK208 [GeForce GT 710]       | 10    |
| pci:10de-1430 | Nvidia      | GM206GL [Quadro M2000]       | 10    |
| pci:10de-1b00 | Nvidia      | GP102 [TITAN X]              | 10    |
| pci:10de-1b84 | Nvidia      | GP104 [GeForce GTX 1060 3GB] | 10    |
| pci:10de-24dc | Nvidia      | GA104M [GeForce RTX 3080 ... | 10    |
| pci:10de-25b8 | Nvidia      | GA107GLM [RTX A2000 Mobile]  | 10    |
| pci:bdbd-a117 | Blackmag... | Intensity Pro                | 10    |
| pci:1002-4c66 | AMD         | RV250/M9 GL [Mobility Fir... | 9     |
| pci:1002-6749 | AMD         | Turks GL [FirePro V4900]     | 9     |
| pci:1002-67e3 | AMD         | Baffin [Radeon Pro WX 4100]  | 9     |
| pci:1002-67e8 | AMD         | Baffin [Radeon Pro WX 413... | 9     |
| pci:1002-68c9 | AMD         | Redwood PRO GL [FirePro V... | 9     |
| pci:1002-6907 | AMD         | Meso XT [Radeon R5 M315]     | 9     |
| pci:1002-6fdf | AMD         | Polaris 20 XL [Radeon RX ... | 9     |
| pci:1002-9596 | AMD         | RV635 PRO [Radeon HD 3650... | 9     |
| pci:1002-9831 | AMD         | Kabini [Radeon HD 8400E]     | 9     |
| pci:1002-9997 | AMD         | Richland [Radeon HD 8350G]   | 9     |
| pci:10de-0185 | Nvidia      | NV18 [GeForce4 MX 4000]      | 9     |
| pci:10de-0295 | Nvidia      | G71 [GeForce 7950 GT]        | 9     |
| pci:10de-0618 | Nvidia      | G92M [GeForce GTX 260M]      | 9     |
| pci:10de-0658 | Nvidia      | G96GL [Quadro FX 380]        | 9     |
| pci:10de-07e5 | Nvidia      | C73 [GeForce 7100 / nForc... | 9     |
| pci:10de-0a69 | Nvidia      | GT218M [GeForce G 105M]      | 9     |
| pci:10de-0dc0 | Nvidia      | GF106 [GeForce GT 440]       | 9     |
| pci:10de-0fea | Nvidia      | GK107M [GeForce GT 755M M... | 9     |
| pci:10de-1005 | Nvidia      | GK110 [GeForce GTX TITAN]    | 9     |
| pci:10de-1087 | Nvidia      | GF110 [GeForce GTX 560 Ti... | 9     |
| pci:10de-1210 | Nvidia      | GF114M [GeForce GTX 570M]    | 9     |
| pci:10de-13d9 | Nvidia      | GM204M [GeForce GTX 965M]    | 9     |
| pci:10de-1bbb | Nvidia      | GP104GLM [Quadro P3200 Mo... | 9     |
| pci:10de-1c06 | Nvidia      | GP106 [GeForce GTX 1060 6... | 9     |
| pci:10de-1cb2 | Nvidia      | GP107GL [Quadro P600]        | 9     |
| pci:10de-1eb5 | Nvidia      | TU104GLM [Quadro RTX 5000... | 9     |
| pci:1a0a-6200 | Blackmagic  | Intensity Pro                | 9     |
| pci:8086-29a3 | Intel       | 82G965 Integrated Graphic... | 9     |
| pci:1002-0000 | AMD         | VGA compatible controller    | 8     |
| pci:1002-5941 | AMD         | RV280 [Radeon 9200] (Seco... | 8     |
| pci:1002-5e4f | AMD         | RV410 [Radeon X700]          | 8     |
| pci:1002-5e6f | AMD         | RV410 [Radeon X700 SE Sec... | 8     |
| pci:1002-6646 | AMD         | Bonaire XT [Radeon R9 M280X] | 8     |
| pci:1002-6863 | AMD         | Vega 10 XTX [Radeon Vega ... | 8     |
| pci:1002-68f2 | AMD         | Cedar GL [FirePro 2270]      | 8     |
| pci:10de-0092 | Nvidia      | G70 [GeForce 7800 GT]        | 8     |
| pci:10de-00c0 | Nvidia      | NV41 [GeForce 6800 GS]       | 8     |
| pci:10de-0162 | Nvidia      | NV44 [GeForce 6200 SE Tur... | 8     |
| pci:10de-05e1 | Nvidia      | GT200 [GeForce GTX 280]      | 8     |
| pci:10de-0655 | Nvidia      | G96 [GeForce GT 120 Mac E... | 8     |
| pci:10de-06d9 | Nvidia      | GF100GL [Quadro 5000]        | 8     |
| pci:10de-06fa | Nvidia      | G98 [Quadro NVS 450]         | 8     |
| pci:10de-0dc6 | Nvidia      | GF106 [GeForce GTS 450 OEM]  | 8     |
| pci:10de-0dd6 | Nvidia      | GF106M [GeForce GT 550M]     | 8     |
| pci:10de-102d | Nvidia      | GK210GL [Tesla K80]          | 8     |
| pci:10de-104b | Nvidia      | GF119 [GeForce GT 625 OEM]   | 8     |
| pci:10de-1082 | Nvidia      | GF110 [GeForce GTX 560 Ti... | 8     |
| pci:10de-118e | Nvidia      | GK104 [GeForce GTX 760 OEM]  | 8     |
| pci:10de-11e1 | Nvidia      | GK106M [GeForce GTX 765M]    | 8     |
| pci:10de-1212 | Nvidia      | GF114M [GeForce GTX 675M]    | 8     |
| pci:10de-129a | Nvidia      | GK208BM [GeForce 910M]       | 8     |
| pci:10de-13fa | Nvidia      | GM204GLM [Quadro M3000M]     | 8     |
| pci:10de-1f96 | Nvidia      | TU117M [GeForce GTX 1650 ... | 8     |
| pci:10de-2482 | Nvidia      | GA104 [GeForce RTX 3070 Ti]  | 8     |
| pci:1106-1122 | VIA Tech... | VX800/VX820 Chrome 9 HC3 ... | 8     |
| pci:18c3-0720 | Micronas... | nGene PCI-Express Multime... | 8     |
| pci:19e5-1711 | Huawei T... | Hi171x Series [iBMC Intel... | 8     |
| pci:8086-010a | Intel       | Xeon E3-1200 Processor Fa... | 8     |
| pci:1002-130b | AMD         | Kaveri [Radeon R4 Graphics]  | 7     |
| pci:1002-4c59 | AMD         | RV100/M6 [Rage/Radeon Mob... | 7     |
| pci:1002-554b | AMD         | R423 [Radeon X800 GT/SE]     | 7     |
| pci:1002-554f | AMD         | R430 [Radeon X800]           | 7     |
| pci:1002-556b | AMD         | R423 [Radeon X800 GT] (Se... | 7     |
| pci:1002-556f | AMD         | R430 [Radeon X800] (Secon... | 7     |
| pci:1002-6808 | AMD         | Pitcairn XT GL [FirePro W... | 7     |
| pci:1002-6809 | AMD         | Pitcairn LE GL [FirePro W... | 7     |
| pci:1002-6825 | AMD         | Heathrow XT [Radeon HD 78... | 7     |
| pci:1002-7143 | AMD         | RV505 [Radeon X1300/X1550... | 7     |
| pci:1002-7163 | AMD         | RV505 [Radeon X1550 Serie... | 7     |
| pci:1002-71c3 | AMD         | RV535 PRO [Radeon X1300 S... | 7     |
| pci:1002-71d5 | AMD         | RV530/M66-P [Mobility Rad... | 7     |
| pci:1002-71e3 | AMD         | RV535 PRO [Radeon X1300 S... | 7     |
| pci:1002-944c | AMD         | RV770 LE [Radeon HD 4830]    | 7     |
| pci:1002-944e | AMD         | RV770 CE [Radeon HD 4710]    | 7     |
| pci:1002-9587 | AMD         | RV630 PRO [Radeon HD 2600... | 7     |
| pci:10de-0142 | Nvidia      | NV43 [GeForce 6600 LE]       | 7     |
| pci:10de-0291 | Nvidia      | G71 [GeForce 7900 GT/GTO]    | 7     |
| pci:10de-029d | Nvidia      | G71GL [Quadro FX 3500]       | 7     |
| pci:10de-029e | Nvidia      | G71GL [Quadro FX 1500]       | 7     |
| pci:10de-0423 | Nvidia      | G86 [GeForce 8300 GS]        | 7     |
| pci:10de-053e | Nvidia      | C68 [GeForce 7025 / nForc... | 7     |
| pci:10de-0606 | Nvidia      | G92 [GeForce 8800 GS]        | 7     |
| pci:10de-061a | Nvidia      | G92GL [Quadro FX 3700]       | 7     |
| pci:10de-061e | Nvidia      | G92GLM [Quadro FX 3700M]     | 7     |
| pci:10de-064a | Nvidia      | G96M [GeForce 9700M GT]      | 7     |
| pci:10de-0653 | Nvidia      | G96CM [GeForce GT 120M]      | 7     |
| pci:10de-0870 | Nvidia      | C79 [GeForce 9400M]          | 7     |
| pci:10de-087f | Nvidia      | C79 [ION LE]                 | 7     |
| pci:10de-0a67 | Nvidia      | GT218 [GeForce 315]          | 7     |
| pci:10de-0e3b | Nvidia      | GF104GLM [Quadro 4000M]      | 7     |
| pci:10de-100c | Nvidia      | GK110B [GeForce GTX TITAN... | 7     |
| pci:10de-103c | Nvidia      | GK110GL [Quadro K5200]       | 7     |
| pci:10de-11a0 | Nvidia      | GK104M [GeForce GTX 680M]    | 7     |
| pci:10de-137b | Nvidia      | GM108GLM [Quadro M520 Mob... | 7     |
| pci:10de-1bb7 | Nvidia      | GP104GLM [Quadro P4000 Mo... | 7     |
| pci:10de-1eb0 | Nvidia      | TU104GL [Quadro RTX 5000]    | 7     |
| pci:10de-1f54 | Nvidia      | TU106BM [GeForce RTX 2070... | 7     |
| pci:10de-1fba | Nvidia      | TU117GLM [T600 Mobile]       | 7     |
| pci:1106-3118 | VIA Tech... | CN400/PM800/PM880/PN800/P... | 7     |
| pci:8086-4905 | Intel       | DG1 [Iris Xe MAX Graphics]   | 7     |
| pci:bdbd-a130 | Blackmag... | DeckLink Mini Recorder       | 7     |
| pci:1002-5854 | AMD         | RS480 [Radeon Xpress 200 ... | 6     |
| pci:1002-5d4f | AMD         | R480 [Radeon X800 GTO]       | 6     |
| pci:1002-5d6f | AMD         | R480 [Radeon X800 GTO] (S... | 6     |
| pci:1002-6707 | AMD         | Cayman LE GL [FirePro V5900] | 6     |
| pci:1002-67c4 | AMD         | Ellesmere [Radeon Pro WX ... | 6     |
| pci:1002-689c | AMD         | Hemlock [Radeon HD 5970]     | 6     |
| pci:1002-68e5 | AMD         | Robson LE [Radeon HD 6330M]  | 6     |
| pci:1002-715f | AMD         | RV505 CE [Radeon X1550 64... | 6     |
| pci:1002-717f | AMD         | Radeon X1300 Secondary       | 6     |
| pci:1002-7181 | AMD         | RV516 [Radeon X1600/X1650... | 6     |
| pci:1002-71a1 | AMD         | RV516 [Radeon X1600/X1650... | 6     |
| pci:1002-71c0 | AMD         | RV530 [Radeon X1600 XT/X1... | 6     |
| pci:1002-71e0 | AMD         | RV530 [Radeon X1600] (Sec... | 6     |
| pci:1002-73af | AMD         | Navi 21 [Radeon RX 6900 XT]  | 6     |
| pci:1039-6325 | Silicon ... | 65x/M650/740 PCI/AGP VGA ... | 6     |
| pci:10de-00cd | Nvidia      | NV42GL [Quadro FX 3450/40... | 6     |
| pci:10de-00ce | Nvidia      | NV41GL [Quadro FX 1400]      | 6     |
| pci:10de-00f5 | Nvidia      | G70/G71 [GeForce 7800 GS ... | 6     |
| pci:10de-0167 | Nvidia      | NV44M [GeForce Go 6200]      | 6     |
| pci:10de-02e2 | Nvidia      | G73 [GeForce 7300 GT AGP]    | 6     |
| pci:10de-0312 | Nvidia      | NV31 [GeForce FX 5600]       | 6     |
| pci:10de-040a | Nvidia      | G84GL [Quadro FX 370]        | 6     |
| pci:10de-0609 | Nvidia      | G92M [GeForce 8800M GTS]     | 6     |
| pci:10de-06f1 | Nvidia      | G98M [GeForce G 105M]        | 6     |
| pci:10de-119a | Nvidia      | GK104M [GeForce GTX 860M]    | 6     |
| pci:10de-119d | Nvidia      | GK104M [GeForce GTX 775M ... | 6     |
| pci:10de-119e | Nvidia      | GK104M [GeForce GTX 780M ... | 6     |
| pci:10de-11ba | Nvidia      | GK104GL [Quadro K5000]       | 6     |
| pci:10de-13f0 | Nvidia      | GM204GL [Quadro M5000]       | 6     |
| pci:8086-193d | Intel       | Iris Pro Graphics P580       | 6     |
| pci:8086-87ca | Intel       | UHD Graphics 615             | 6     |
| pci:8086-9ba4 | Intel       | Comet Lake UHD Graphics      | 6     |
| pci:1002-4e48 | AMD         | R350 [Radeon 9800 Series]    | 5     |
| pci:1002-4e68 | AMD         | R350 [Radeon 9800 PRO] (S... | 5     |
| pci:1002-554d | AMD         | R480 [Radeon X800 GTO2/XL]   | 5     |
| pci:1002-556d | AMD         | R480 [Radeon X800 GTO2/XL... | 5     |
| pci:1002-5b64 | AMD         | RV370 GL [FireGL V3100]      | 5     |
| pci:1002-665d | AMD         | Bonaire [Radeon R7 200 Se... | 5     |
| pci:1002-6704 | AMD         | Cayman PRO GL [FirePro V7... | 5     |
| pci:1002-675f | AMD         | Turks LE [Radeon HD 5570/... | 5     |
| pci:1002-6843 | AMD         | Thames [Radeon HD 7670M]     | 5     |
| pci:1002-68a9 | AMD         | Juniper XT [FirePro V5800]   | 5     |
| pci:1002-68c7 | AMD         | Pinewood [Mobility Radeon... | 5     |
| pci:1002-68f1 | AMD         | Cedar GL [FirePro 2460]      | 5     |
| pci:1002-692b | AMD         | Tonga PRO GL [FirePro W7100] | 5     |
| pci:1002-71ce | AMD         | RV530 [Radeon X1300 XT/X1... | 5     |
| pci:1002-71ee | AMD         | RV530 [Radeon X1600 Secon... | 5     |
| pci:1002-9642 | AMD         | SuperSumo [Radeon HD 6370D]  | 5     |
| pci:1002-9713 | AMD         | RS880M [Mobility Radeon H... | 5     |
| pci:1002-9856 | AMD         | Mullins [Radeon R1E/R2E G... | 5     |
| pci:1002-9994 | AMD         | Trinity 2 [Radeon HD 7400G]  | 5     |
| pci:102b-0540 | Matrox E... | M91XX                        | 5     |
| pci:10de-002d | Nvidia      | NV5 [Riva TNT2 Model 64 /... | 5     |
| pci:10de-019e | Nvidia      | G80GL [Quadro FX 4600]       | 5     |
| pci:10de-0342 | Nvidia      | NV36 [GeForce FX 5700]       | 5     |
| pci:10de-040b | Nvidia      | G84GLM [Quadro NVS 320M]     | 5     |
| pci:10de-042c | Nvidia      | G86 [GeForce 9400 GT]        | 5     |
| pci:10de-05ea | Nvidia      | GT200 [GeForce GTX 260]      | 5     |
| pci:10de-05fd | Nvidia      | GT200GL [Quadro FX 5800]     | 5     |
| pci:10de-061f | Nvidia      | G92GLM [Quadro FX 3800M]     | 5     |
| pci:10de-062c | Nvidia      | G94M [GeForce 9800M GTS]     | 5     |
| pci:10de-06f8 | Nvidia      | G98 [Quadro NVS 420]         | 5     |
| pci:10de-0847 | Nvidia      | C78 [GeForce 9100]           | 5     |
| pci:10de-084d | Nvidia      | C77 [nForce 750a SLI]        | 5     |
| pci:10de-084f | Nvidia      | C77 [GeForce 8100 / nForc... | 5     |
| pci:10de-0860 | Nvidia      | C79 [GeForce 9300]           | 5     |
| pci:10de-086c | Nvidia      | C79 [GeForce 9300 / nForc... | 5     |
| pci:10de-0874 | Nvidia      | C79 [ION]                    | 5     |
| pci:10de-0a2a | Nvidia      | GT216M [GeForce GT 230M]     | 5     |
| pci:10de-0a72 | Nvidia      | GT218M [GeForce 310M]        | 5     |
| pci:10de-0dee | Nvidia      | GF108M [GeForce GT 415M]     | 5     |
| pci:10de-0df2 | Nvidia      | GF108M [GeForce GT 435M]     | 5     |
| pci:10de-0ff2 | Nvidia      | GK107GL [GRID K1]            | 5     |
| pci:10de-1023 | Nvidia      | GK110BGL [Tesla K40m]        | 5     |
| pci:10de-103a | Nvidia      | GK110GL [Quadro K6000]       | 5     |
| pci:10de-1042 | Nvidia      | GF119 [GeForce 510]          | 5     |
| pci:10de-1084 | Nvidia      | GF110 [GeForce GTX 560 OEM]  | 5     |
| pci:10de-11a1 | Nvidia      | GK104M [GeForce GTX 670MX]   | 5     |
| pci:10de-11a3 | Nvidia      | GK104M [GeForce GTX 680MX]   | 5     |
| pci:10de-11b7 | Nvidia      | GK104GLM [Quadro K4100M]     | 5     |
| pci:10de-1248 | Nvidia      | GF116M [GeForce GT 555M/6... | 5     |
| pci:10de-139c | Nvidia      | GM107M [GeForce 940M]        | 5     |
| pci:10de-1bb0 | Nvidia      | GP104GL [Quadro P5000]       | 5     |
| pci:10de-1c21 | Nvidia      | GP106M [GeForce GTX 1050 ... | 5     |
| pci:10de-1ec7 | Nvidia      | TU104 [GeForce RTX 2070 S... | 5     |
| pci:10de-1f47 | Nvidia      | TU106 [GeForce RTX 2060 S... | 5     |
| pci:1106-7205 | VIA Tech... | KM400/KN400/P4M800 [S3 Un... | 5     |
| pci:5333-8811 | S3 Graphics | 86c764/765 [Trio32/64/64V+]  | 5     |
| pci:5333-8d04 | S3 Graphics | VT8375 [ProSavage8 KM266/... | 5     |
| pci:8086-29d3 | Intel       | 82Q33 Express Integrated ... | 5     |
| pci:8086-46a6 | Intel       | Alder Lake-P Integrated G... | 5     |
| pci:8086-4e61 | Intel       | JasperLake [UHD Graphics]    | 5     |
| pci:8086-9a70 | Intel       | VGA compatible controller    | 5     |
| pci:1002-4151 | AMD         | RV350 [Radeon 9600 Series]   | 4     |
| pci:1002-4171 | AMD         | RV350 [Radeon 9600] (Seco... | 4     |
| pci:1002-4337 | AMD         | RS200M [Radeon IGP 330M/3... | 4     |
| pci:1002-5462 | AMD         | RV380/M24C [Mobility Rade... | 4     |
| pci:1002-5834 | AMD         | RS300 [Radeon 9100 IGP]      | 4     |
| pci:1002-5835 | AMD         | RS300M [Mobility Radeon 9... | 4     |
| pci:1002-5b74 | AMD         | RV370 GL [FireGL V3100] (... | 4     |
| pci:1002-671f | AMD         | Cayman CE [Radeon HD 6930]   | 4     |
| pci:1002-67a1 | AMD         | Hawaii PRO GL [FirePro W8... | 4     |
| pci:1002-714a | AMD         | RV515/M52 [Mobility Radeo... | 4     |
| pci:1002-7152 | AMD         | RV515 GL [FireGL V3300]      | 4     |
| pci:1002-7172 | AMD         | RV515 GL [FireGL V3300] (... | 4     |
| pci:1002-7240 | AMD         | R580+ [Radeon X1950 XTX]     | 4     |
| pci:1002-7244 | AMD         | R580+ [Radeon X1950 XT]      | 4     |
| pci:1002-7260 | AMD         | R580+ [Radeon X1950 XTX S... | 4     |
| pci:1002-7264 | AMD         | R580 [Radeon X1950 XT Sec... | 4     |
| pci:1002-7312 | AMD         | Navi 10 [Radeon Pro W5700]   | 4     |
| pci:1002-7941 | AMD         | RS600 [Radeon Xpress 1250]   | 4     |
| pci:1002-94c7 | AMD         | RV610 [Radeon HD 2350]       | 4     |
| pci:1002-950f | AMD         | R680 [Radeon HD 3870 X2]     | 4     |
| pci:1002-95cf | AMD         | RV620 GL [FirePro 2260]      | 4     |
| pci:1033-013a | NEC Comp... | Dual Tuner/MPEG Encoder      | 4     |
| pci:10de-00c3 | Nvidia      | NV41 [GeForce 6800 XT]       | 4     |
| pci:10de-00f8 | Nvidia      | NV45GL [Quadro FX 3400/4400] | 4     |
| pci:10de-014e | Nvidia      | NV43GL [Quadro FX 540]       | 4     |
| pci:10de-0297 | Nvidia      | G71M [GeForce Go 7950 GTX]   | 4     |
| pci:10de-02e1 | Nvidia      | G73 [GeForce 7600 GS AGP]    | 4     |
| pci:10de-0324 | Nvidia      | NV34M [GeForce FX Go5200 ... | 4     |
| pci:10de-0343 | Nvidia      | NV36 [GeForce FX 5700LE]     | 4     |
| pci:10de-042a | Nvidia      | G86M [Quadro NVS 130M]       | 4     |
| pci:10de-05eb | Nvidia      | GT200 [GeForce GTX 295]      | 4     |
| pci:10de-0602 | Nvidia      | G92 [GeForce 8800 GT]        | 4     |
| pci:10de-0627 | Nvidia      | G94 [GeForce GT 140]         | 4     |
| pci:10de-062a | Nvidia      | G94M [GeForce 9700M GTS]     | 4     |
| pci:10de-06d1 | Nvidia      | GF100GL [Tesla C2050 / C2... | 4     |
| pci:10de-06d8 | Nvidia      | GF100GL [Quadro 6000]        | 4     |
| pci:10de-06e2 | Nvidia      | G98 [GeForce 8400]           | 4     |
| pci:10de-086a | Nvidia      | C79 [GeForce 9400]           | 4     |
| pci:10de-0a27 | Nvidia      | GT216 [GeForce 405]          | 4     |
| pci:10de-0dd2 | Nvidia      | GF106M [GeForce GT 445M]     | 4     |
| pci:10de-1091 | Nvidia      | GF110GL [Tesla M2090]        | 4     |
| pci:10de-118f | Nvidia      | GK104GL [Tesla K10]          | 4     |
| pci:10de-1211 | Nvidia      | GF114M [GeForce GTX 580M]    | 4     |
| pci:10de-1246 | Nvidia      | GF116M [GeForce GT 550M]     | 4     |
| pci:10de-1344 | Nvidia      | GM108M [GeForce 845M]        | 4     |
| pci:10de-1ba0 | Nvidia      | GP104M [GeForce GTX 1080 ... | 4     |
| pci:10de-24b8 | Nvidia      | GA104GLM [RTX A3000 Mobile]  | 4     |
| pci:10de-25e0 | Nvidia      | GA107BM [GeForce RTX 3050... | 4     |
| pci:126f-0750 | Silicon ... | SM750                        | 4     |
| pci:8086-9bcc | Intel       | Comet Lake UHD Graphics      | 4     |
| pci:1002-130c | AMD         | Kaveri [Radeon R7 Graphics]  | 3     |
| pci:1002-130e | AMD         | Kaveri [Radeon R5 Graphics]  | 3     |
| pci:1002-4e54 | AMD         | RV350/M10 GL [Mobility Fi... | 3     |
| pci:1002-5c61 | AMD         | RV280/M9+ [Mobility Radeo... | 3     |
| pci:1002-5d52 | AMD         | R480 [Radeon X850 XT]        | 3     |
| pci:1002-5d72 | AMD         | R480 [Radeon X850 XT] (Se... | 3     |
| pci:1002-6750 | AMD         | Onega [Radeon HD 6650A/76... | 3     |
| pci:1002-68b9 | AMD         | Juniper LE [Radeon HD 567... | 3     |
| pci:1002-7102 | AMD         | R520/M58 [Mobility Radeon... | 3     |
| pci:1002-724b | AMD         | R580 [Radeon X1900 GT]       | 3     |
| pci:1002-726b | AMD         | R580 [Radeon X1900 GT] (S... | 3     |
| pci:1002-7341 | AMD         | Navi 14 [Radeon Pro W5500]   | 3     |
| pci:1002-743f | AMD         | Navi 24 [Radeon RX 6400 /... | 3     |
| pci:1002-9400 | AMD         | R600 [Radeon HD 2900 PRO/XT] | 3     |
| pci:1002-94a3 | AMD         | RV740/M97 GL [FirePro M7740] | 3     |
| pci:1002-958c | AMD         | RV630 GL [FireGL V5600]      | 3     |
| pci:102b-2527 | Matrox E... | Millennium G550              | 3     |
| pci:10de-0028 | Nvidia      | NV5 [Riva TNT2 / TNT2 Pro]   | 3     |
| pci:10de-0045 | Nvidia      | NV40 [GeForce 6800 GT]       | 3     |
| pci:10de-009d | Nvidia      | G70GL [Quadro FX 4500]       | 3     |
| pci:10de-0111 | Nvidia      | NV11 [GeForce2 MX200]        | 3     |
| pci:10de-014d | Nvidia      | NV43GL [Quadro FX 550]       | 3     |
| pci:10de-0160 | Nvidia      | NV44 [GeForce 6500]          | 3     |
| pci:10de-0172 | Nvidia      | NV17 [GeForce4 MX 420]       | 3     |
| pci:10de-0175 | Nvidia      | NV17M [GeForce4 420 Go]      | 3     |
| pci:10de-019d | Nvidia      | G80GL [Quadro FX 5600]       | 3     |
| pci:10de-0222 | Nvidia      | NV44 [GeForce 6200 A-LE]     | 3     |
| pci:10de-0290 | Nvidia      | G71 [GeForce 7900 GTX]       | 3     |
| pci:10de-029a | Nvidia      | G71GLM [Quadro FX 2500M]     | 3     |
| pci:10de-029b | Nvidia      | G71GLM [Quadro FX 1500M]     | 3     |
| pci:10de-031a | Nvidia      | NV31M [GeForce FX Go5600]    | 3     |
| pci:10de-0332 | Nvidia      | NV35 [GeForce FX 5900XT]     | 3     |
| pci:10de-0344 | Nvidia      | NV36 [GeForce FX 5700VE]     | 3     |
| pci:10de-042d | Nvidia      | G86GLM [Quadro FX 360M]      | 3     |
| pci:10de-0607 | Nvidia      | G92 [GeForce GTS 240]        | 3     |
| pci:10de-062b | Nvidia      | G94M [GeForce 9800M GS]      | 3     |
| pci:10de-062e | Nvidia      | G94 [GeForce 9600 GT]        | 3     |
| pci:10de-06ea | Nvidia      | G98M [Quadro NVS 150M]       | 3     |
| pci:10de-084c | Nvidia      | C77 [nForce 780a/980a SLI]   | 3     |
| pci:10de-087e | Nvidia      | C79 [ION LE]                 | 3     |
| pci:10de-0ca4 | Nvidia      | GT215 [GeForce GT 340]       | 3     |
| pci:10de-0ca9 | Nvidia      | GT215M [GeForce GTS 250M]    | 3     |
| pci:10de-0fe0 | Nvidia      | GK107M [GeForce GTX 660M ... | 3     |
| pci:10de-0ff9 | Nvidia      | GK107GL [Quadro K2000D]      | 3     |
| pci:10de-105b | Nvidia      | GF119M [GeForce 705M]        | 3     |
| pci:10de-1088 | Nvidia      | GF110 [GeForce GTX 590]      | 3     |
| pci:10de-1206 | Nvidia      | GF114 [GeForce GTX 555]      | 3     |
| pci:10de-1293 | Nvidia      | GK208M [GeForce GT 730M]     | 3     |
| pci:10de-13b3 | Nvidia      | GM107GLM [Quadro K2200M]     | 3     |
| pci:10de-13f9 | Nvidia      | GM204GLM [Quadro M4000M]     | 3     |
| pci:10de-1406 | Nvidia      | GM206 [GeForce GTX 960 OEM]  | 3     |
| pci:10de-1619 | Nvidia      | GM204M [GeForce GTX 965M]    | 3     |
| pci:10de-17fd | Nvidia      | GM200GL [Tesla M40]          | 3     |
| pci:10de-1bb5 | Nvidia      | GP104GLM [Quadro P5200 Mo... | 3     |
| pci:10de-1bb8 | Nvidia      | GP104GLM [Quadro P3000 Mo... | 3     |
| pci:10de-1d81 | Nvidia      | GV100 [TITAN V]              | 3     |
| pci:10de-1dba | Nvidia      | GV100GL [Quadro GV100]       | 3     |
| pci:10de-1eb8 | Nvidia      | TU104GL [Tesla T4]           | 3     |
| pci:10de-21d1 | Nvidia      | TU116BM [GeForce GTX 1660... | 3     |
| pci:10de-2487 | Nvidia      | GA104 [GeForce RTX 3060]     | 3     |
| pci:10de-24b6 | Nvidia      | GA104GLM [RTX A5000 Mobile]  | 3     |
| pci:10de-24b7 | Nvidia      | GA104GLM [RTX A4000 Mobile]  | 3     |
| pci:10de-25e2 | Nvidia      | GA107BM [GeForce RTX 3050... | 3     |
| pci:121a-0001 | 3Dfx Int... | Voodoo                       | 3     |
| pci:126f-0501 | Silicon ... | SM501 VoyagerGX Rev. AA      | 3     |
| pci:1797-6804 | Intersil... | HV4000 DVR card              | 3     |
| pci:1cd7-0004 | Nanjing ... | Electronics Multimedia vi... | 3     |
| pci:1d17-3a04 | Zhaoxin     | ZX-E C-960 GPU               | 3     |
| pci:5333-8c2e | S3 Graphics | SuperSavage IX/C SDR         | 3     |
| pci:8086-080d | Intel       | Moorestown External Displays | 3     |
| pci:8086-3ea6 | Intel       | Coffee Lake Iris Plus 645... | 3     |
| pci:8086-4102 | Intel       | Graphics Media Accelerato... | 3     |
| pci:8086-4692 | Intel       | VGA compatible controller    | 3     |
| pci:8086-9bc6 | Intel       | UHD P630 Graphics            | 3     |
| pci:bdbd-a12f | Blackmag... | DeckLink Mini Monitor        | 3     |
| pci:bdbd-a143 | Blackmag... | DeckLink Mini Recorder 4K    | 3     |
| pci:bdbd-a14e | Blackmag... | DeckLink Quad HDMI Recorder  | 3     |
| pci:0014-7a06 | Loongson... | DC (Display Controller)      | 2     |
| pci:0014-7a15 | Loongson... | Vivante GPU (Graphics Pro... | 2     |
| pci:1002-4756 | AMD         | Rage 2 [3D Rage IIC PCI]     | 2     |
| pci:1002-4966 | AMD         | RV250 [Radeon 9000 Series]   | 2     |
| pci:1002-4a49 | AMD         | R420 [Radeon X800 PRO/GTO... | 2     |
| pci:1002-4a69 | AMD         | R420 [Radeon X800 PRO/GTO... | 2     |
| pci:1002-4c4d | AMD         | Rage Mobility AGP 2x Series  | 2     |
| pci:1002-4e4a | AMD         | R360 [Radeon 9800 XXL/XT]    | 2     |
| pci:1002-4e6a | AMD         | RV350 [Radeon 9800 XT] (S... | 2     |
| pci:1002-5157 | AMD         | RV200 [Radeon 7500/7500 LE]  | 2     |
| pci:1002-5549 | AMD         | R423 [Radeon X800 GTO]       | 2     |
| pci:1002-5569 | AMD         | R423 [Radeon X800 PRO] (S... | 2     |
| pci:1002-5a41 | AMD         | RS400 [Radeon Xpress 200]    | 2     |
| pci:1002-5d4d | AMD         | R480 [Radeon X850 XT Plat... | 2     |
| pci:1002-5d6d | AMD         | R480 [Radeon X850 XT Plat... | 2     |
| pci:1002-679b | AMD         | Malta [Radeon HD 7990/899... | 2     |
| pci:1002-6827 | AMD         | Heathrow PRO [Radeon HD 7... | 2     |
| pci:1002-6828 | AMD         | Cape Verde PRO [FirePro W... | 2     |
| pci:1002-6835 | AMD         | Cape Verde PRX [Radeon R9... | 2     |
| pci:1002-6860 | AMD         | Vega 10 [Radeon Instinct ... | 2     |
| pci:1002-6861 | AMD         | Vega 10 XT [Radeon PRO WX... | 2     |
| pci:1002-6920 | AMD         | Amethyst [Radeon R9 M395/... | 2     |
| pci:1002-7153 | AMD         | RV515 GL [FireGL V3350]      | 2     |
| pci:1002-7173 | AMD         | RV515 GL [FireGL V3350] (... | 2     |
| pci:1002-7186 | AMD         | RV516/M64 [Mobility Radeo... | 2     |
| pci:1002-719f | AMD         | RV516 [Radeon X1550 Series]  | 2     |
| pci:1002-71c4 | AMD         | RV530/M56 GL [Mobility Fi... | 2     |
| pci:1002-71cd | AMD         | RV530 [Radeon X1600]         | 2     |
| pci:1002-71d2 | AMD         | RV530 GL [FireGL V3400]      | 2     |
| pci:1002-71d4 | AMD         | RV530/M66 GL [Mobility Fi... | 2     |
| pci:1002-71ed | AMD         | RV530 [Radeon X1600 Secon... | 2     |
| pci:1002-71f2 | AMD         | RV530 GL [FireGL V3400] (... | 2     |
| pci:1002-73a3 | AMD         | Navi 21 GL-XL [Radeon PRO... | 2     |
| pci:1002-73e3 | AMD         | Navi 23 WKS-XL [Radeon PR... | 2     |
| pci:1002-949c | AMD         | RV730 GL [FirePro V7750]     | 2     |
| pci:1002-949f | AMD         | RV730 GL [FirePro V3750]     | 2     |
| pci:1002-94a0 | AMD         | RV740/M97 [Mobility Radeo... | 2     |
| pci:1002-94c4 | AMD         | RV610 LE [Radeon HD 2400 ... | 2     |
| pci:1002-9509 | AMD         | RV670/M88 [Mobility Radeo... | 2     |
| pci:1002-9615 | AMD         | RS780E [Radeon HD 3200]      | 2     |
| pci:1002-9924 | AMD         | Gladius                      | 2     |
| pci:1002-999c | AMD         | Richland [Radeon HD 8650D]   | 2     |
| pci:102b-0519 | Matrox E... | MGA 2064W [Millennium]       | 2     |
| pci:102b-051a | Matrox E... | MGA 1064SG [Mystique]        | 2     |
| pci:102b-2538 | Matrox E... | Millennium P650 PCIe         | 2     |
| pci:103c-1008 | Hewlett-... | Visualize FX                 | 2     |
| pci:10c8-0004 | Neomagic    | NM2160 [MagicGraph 128XD]    | 2     |
| pci:10de-0041 | Nvidia      | NV40 [GeForce 6800]          | 2     |
| pci:10de-0091 | Nvidia      | G70 [GeForce 7800 GTX]       | 2     |
| pci:10de-00c1 | Nvidia      | NV41 [GeForce 6800]          | 2     |
| pci:10de-00c2 | Nvidia      | NV41 [GeForce 6800 LE]       | 2     |
| pci:10de-00c8 | Nvidia      | NV41M [GeForce Go 6800]      | 2     |
| pci:10de-00f1 | Nvidia      | NV43 [GeForce 6600 GT]       | 2     |
| pci:10de-00f2 | Nvidia      | NV43 [GeForce 6600]          | 2     |
| pci:10de-0112 | Nvidia      | NV11M [GeForce2 Go]          | 2     |
| pci:10de-0145 | Nvidia      | NV43 [GeForce 6610 XL]       | 2     |
| pci:10de-014a | Nvidia      | NV43 [Quadro NVS 440]        | 2     |
| pci:10de-014f | Nvidia      | NV43 [GeForce 6200]          | 2     |
| pci:10de-0165 | Nvidia      | NV44 [Quadro NVS 285]        | 2     |
| pci:10de-0168 | Nvidia      | NV44M [GeForce Go 6400]      | 2     |
| pci:10de-0174 | Nvidia      | NV17M [GeForce4 440 Go]      | 2     |
| pci:10de-0176 | Nvidia      | NV17M [GeForce4 420 Go 32M]  | 2     |
| pci:10de-0179 | Nvidia      | NV17M [GeForce4 440 Go 64M]  | 2     |
| pci:10de-01da | Nvidia      | G72M [Quadro NVS 110M]       | 2     |
| pci:10de-0299 | Nvidia      | G71M [GeForce Go 7900 GTX]   | 2     |
| pci:10de-02e0 | Nvidia      | G73 [GeForce 7600 GT AGP]    | 2     |
| pci:10de-0314 | Nvidia      | NV31 [GeForce FX 5600XT]     | 2     |
| pci:10de-0347 | Nvidia      | NV36M [GeForce FX Go5700]    | 2     |
| pci:10de-0394 | Nvidia      | G73 [GeForce 7600 LE]        | 2     |
| pci:10de-0399 | Nvidia      | G73M [GeForce Go 7600 GT]    | 2     |
| pci:10de-0408 | Nvidia      | G84M [GeForce 9650M GS]      | 2     |
| pci:10de-05e7 | Nvidia      | GT200GL [Tesla C1060 / M1... | 2     |
| pci:10de-060c | Nvidia      | G92M [GeForce 8800M GTX]     | 2     |
| pci:10de-061c | Nvidia      | G92GLM [Quadro FX 3600M]     | 2     |
| pci:10de-0626 | Nvidia      | G94 [GeForce GT 130]         | 2     |
| pci:10de-0645 | Nvidia      | G96C [GeForce 9500 GS]       | 2     |
| pci:10de-07e2 | Nvidia      | C73 [GeForce 7050 / nForc... | 2     |
| pci:10de-0862 | Nvidia      | C79 [GeForce 9400M G]        | 2     |
| pci:10de-086d | Nvidia      | C79 [GeForce 9200]           | 2     |
| pci:10de-0a38 | Nvidia      | GT216GL [Quadro 400]         | 2     |
| pci:10de-0a6a | Nvidia      | GT218M [NVS 2100M]           | 2     |
| pci:10de-0a78 | Nvidia      | GT218GL [Quadro FX 380 LP]   | 2     |
| pci:10de-0dc5 | Nvidia      | GF106 [GeForce GTS 450 OEM]  | 2     |
| pci:10de-1001 | Nvidia      | GK110B [GeForce GTX TITAN Z] | 2     |
| pci:10de-1007 | Nvidia      | GK110 [GeForce GTX 780 Re... | 2     |
| pci:10de-1021 | Nvidia      | GK110GL [Tesla K20Xm]        | 2     |
| pci:10de-1096 | Nvidia      | GF110GL [Tesla C2050 / C2... | 2     |
| pci:10de-109a | Nvidia      | GF100GLM [Quadro 5010M]      | 2     |
| pci:10de-11a2 | Nvidia      | GK104M [GeForce GTX 675MX... | 2     |
| pci:10de-11bf | Nvidia      | GK104GL [GRID K2]            | 2     |
| pci:10de-1205 | Nvidia      | GF114 [GeForce GTX 460 v2]   | 2     |
| pci:10de-1241 | Nvidia      | GF116 [GeForce GT 545 OEM]   | 2     |
| pci:10de-1398 | Nvidia      | GM107M [GeForce 845M]        | 2     |
| pci:10de-13b9 | Nvidia      | GM107GL [NVS 810]            | 2     |
| pci:10de-13f8 | Nvidia      | GM204GLM [Quadro M5000M /... | 2     |
| pci:10de-15f0 | Nvidia      | GP100GL [Quadro GP100]       | 2     |
| pci:10de-1bb9 | Nvidia      | GP104GLM [Quadro P4200 Mo... | 2     |
| pci:10de-1c07 | Nvidia      | GP106 [P106-100]             | 2     |
| pci:10de-1c09 | Nvidia      | GP106 [P106-090]             | 2     |
| pci:10de-1f98 | Nvidia      | TU117M [GeForce MX450]       | 2     |
| pci:10de-1fb1 | Nvidia      | TU117GL [T600]               | 2     |
| pci:10de-1fdd | Nvidia      | TU117BM [GeForce GTX 1650... | 2     |
| pci:10de-20f1 | Nvidia      | GA100 [A100 PCIe 40GB]       | 2     |
| pci:10de-24a0 | Nvidia      | GA104 [Geforce RTX 3070 T... | 2     |
| pci:10de-24b0 | Nvidia      | GA104GL [RTX A4000]          | 2     |
| pci:10ee-0007 | Xilinx      | Default PCIe endpoint ID     | 2     |
| pci:126f-0712 | Silicon ... | SM712 LynxEM+                | 2     |
| pci:13f6-0110 | C-Media ... | Electronics Multimedia vi... | 2     |
| pci:1797-6810 | Intersil... | TW6816 multimedia video c... | 2     |
| pci:1797-6811 | Intersil... | TW6816 multimedia video c... | 2     |
| pci:1797-6812 | Intersil... | TW6816 multimedia video c... | 2     |
| pci:1797-6813 | Intersil... | TW6816 multimedia video c... | 2     |
| pci:5333-8a22 | S3 Graphics | Savage 4                     | 2     |
| pci:8086-162a | Intel       | Iris Pro Graphics P6300      | 2     |
| pci:8086-8a51 | Intel       | Iris Plus Graphics G7 (Ic... | 2     |
| pci:8086-9840 | Intel       | UHD Graphics, LKF            | 2     |
| pci:8086-9baa | Intel       | Comet Lake UHD Graphics      | 2     |
| pci:bdbd-a11b | Blackmag... | DeckLink SDI/Duo/Quad        | 2     |
| pci:bdbd-a140 | Blackmag... | DeckLink Duo 2               | 2     |
| pci:bdbd-a144 | Blackmag... | DeckLink Mini Monitor 4K     | 2     |
| pci:1002-131c | AMD         | Kaveri [Radeon R7 Graphics]  | 1     |
| pci:1002-154c | AMD         | Kryptos [Radeon RX 350]      | 1     |
| pci:1002-3151 | AMD         | RV380 GL [FireMV 2400]       | 1     |
| pci:1002-3154 | AMD         | RV380/M24 GL [Mobility Fi... | 1     |
| pci:1002-3171 | AMD         | RV380 GL [FireMV 2400] (S... | 1     |
| pci:1002-4155 | AMD         | RV350 [Radeon 9600]          | 1     |
| pci:1002-4175 | AMD         | Radeon 9600 Secondary        | 1     |
| pci:1002-4242 | AMD         | R200 [All-In-Wonder Radeo... | 1     |
| pci:1002-4354 | AMD         | 215CT [Mach64 CT PCI]        | 1     |
| pci:1002-4437 | AMD         | RS250 [Mobility Radeon 70... | 1     |
| pci:1002-4742 | AMD         | Rage 3 [3D Rage PRO AGP 2X]  | 1     |
| pci:1002-496e | AMD         | RV250 [Radeon 9000] (Seco... | 1     |
| pci:1002-4b49 | AMD         | R481 [Radeon X850 XT AGP]    | 1     |
| pci:1002-4b69 | AMD         | R481 [Radeon X850 XT AGP]... | 1     |
| pci:1002-4e51 | AMD         | RV350 [Radeon 9550/9600/X... | 1     |
| pci:1002-4e71 | AMD         | RV350/M10 [Mobility Radeo... | 1     |
| pci:1002-5046 | AMD         | Rage 4 [Rage 128 PRO AGP 4X] | 1     |
| pci:1002-5050 | AMD         | Rage 4 [Rage 128 PRO PCI ... | 1     |
| pci:1002-5144 | AMD         | R100 [Radeon 7200 / All-I... | 1     |
| pci:1002-514c | AMD         | R200 [Radeon 8500/8500 LE]   | 1     |
| pci:1002-5245 | AMD         | Rage 128 GL PCI              | 1     |
| pci:1002-5446 | AMD         | Rage 128 PRO Ultra AGP 4x    | 1     |
| pci:1002-554e | AMD         | R430 [All-In-Wonder X800 GT] | 1     |
| pci:1002-556e | AMD         | Radeon X800 GT Secondary     | 1     |
| pci:1002-564f | AMD         | RV410/M26 [Mobility Radeo... | 1     |
| pci:1002-5652 | AMD         | RV410/M26 [Mobility Radeo... | 1     |
| pci:1002-5656 | AMD         | Mach64 VT4 [Video Xpressi... | 1     |
| pci:1002-5657 | AMD         | RV410 [Radeon X550 XTX / ... | 1     |
| pci:1002-5677 | AMD         | Radeon X550/X700 Secondary   | 1     |
| pci:1002-5962 | AMD         | RV280 [Radeon 9200]          | 1     |
| pci:1002-5d57 | AMD         | R423 [Radeon X800 XT]        | 1     |
| pci:1002-5d77 | AMD         | R423 [Radeon X800 XT] (Se... | 1     |
| pci:1002-5e4d | AMD         | RV410 [Radeon X700]          | 1     |
| pci:1002-5e6d | AMD         | RV410 [Radeon X700] (Seco... | 1     |
| pci:1002-664d | AMD         | Bonaire [FirePro W5100 / ... | 1     |
| pci:1002-66a3 | AMD         | Vega 20 [Radeon Pro Vega ... | 1     |
| pci:1002-6743 | AMD         | Whistler [Radeon E6760]      | 1     |
| pci:1002-6761 | AMD         | Seymour LP [Radeon HD 6430M] | 1     |
| pci:1002-6763 | AMD         | Seymour [Radeon E6460]       | 1     |
| pci:1002-6772 | AMD         | Caicos [Radeon HD 7450A]     | 1     |
| pci:1002-6780 | AMD         | Tahiti XT GL [FirePro W9000] | 1     |
| pci:1002-678a | AMD         | Tahiti PRO GL [FirePro Se... | 1     |
| pci:1002-67b9 | AMD         | Vesuvius [Radeon R9 295X2]   | 1     |
| pci:1002-67c0 | AMD         | Ellesmere [Radeon Pro WX ... | 1     |
| pci:1002-6867 | AMD         | Vega 10 XL [Radeon Pro Ve... | 1     |
| pci:1002-6868 | AMD         | Vega 10 [Radeon PRO WX 81... | 1     |
| pci:1002-6869 | AMD         | Vega 10 XGA [Radeon Pro V... | 1     |
| pci:1002-6888 | AMD         | Cypress XT [FirePro V8800]   | 1     |
| pci:1002-68f0 | AMD         | EG PARK PRO/XT               | 1     |
| pci:1002-6921 | AMD         | Amethyst XT [Radeon R9 M2... | 1     |
| pci:1002-6929 | AMD         | Tonga XT GL [FirePro S7150]  | 1     |
| pci:1002-69af | AMD         | Vega 12 [Radeon Pro Vega 20] | 1     |
| pci:1002-7100 | AMD         | R520 [Radeon X1800 XT]       | 1     |
| pci:1002-7109 | AMD         | R520 [Radeon X1800 XL]       | 1     |
| pci:1002-710a | AMD         | R520 [Radeon X1800 GTO]      | 1     |
| pci:1002-7120 | AMD         | R520 [Radeon X1800] (Seco... | 1     |
| pci:1002-7129 | AMD         | R520 [Radeon X1800] (Seco... | 1     |
| pci:1002-712a | AMD         | Radeon X1800 GTO Secondary   | 1     |
| pci:1002-7140 | AMD         | RV515 [Radeon X1300/X1550... | 1     |
| pci:1002-7147 | AMD         | RV505 [Radeon X1550 64-bit]  | 1     |
| pci:1002-7160 | AMD         | Radeon X1300 Secondary       | 1     |
| pci:1002-7167 | AMD         | RV515 [Radeon X1550 64-bi... | 1     |
| pci:1002-719b | AMD         | RV516 GL [FireMV 2250]       | 1     |
| pci:1002-71bb | AMD         | RV516 GL [FireMV 2250] (S... | 1     |
| pci:1002-7211 | AMD         | RV550/M71 [Mobility Radeo... | 1     |
| pci:1002-7249 | AMD         | R580 [Radeon X1900 XT]       | 1     |
| pci:1002-7319 | AMD         | VGA compatible controller    | 1     |
| pci:1002-735f | AMD         | VGA compatible controller    | 1     |
| pci:1002-73e1 | AMD         | Navi 23 WKS-XM [Radeon PR... | 1     |
| pci:1002-9441 | AMD         | R700 [Radeon HD 4870 X2]     | 1     |
| pci:1002-9443 | AMD         | R700 [Radeon HD 4850 X2]     | 1     |
| pci:1002-9450 | AMD         | RV770 GL [FireStream 9270]   | 1     |
| pci:1002-949e | AMD         | RV730 GL [FirePro V5700]     | 1     |
| pci:1002-9515 | AMD         | RV670 PRO [Radeon HD 3850... | 1     |
| pci:1002-955f | AMD         | RV710/M92 [Mobility Radeo... | 1     |
| pci:1002-9586 | AMD         | RV630 XT [Radeon HD 2600 ... | 1     |
| pci:1002-95cc | AMD         | RV620 GL [FirePro V3700]     | 1     |
| pci:1002-9910 | AMD         | Trinity [Radeon HD 7660G]    | 1     |
| pci:1002-e000 | AMD         | VGA compatible controller    | 1     |
| pci:1022-2081 | AMD         | Geode LX Video               | 1     |
| pci:1022-6840 | AMD         | Thames [Radeon HD 7500M/7... | 1     |
| pci:1022-68e4 | AMD         | Robson CE [Radeon HD 6370... | 1     |
| pci:1023-2100 | Trident ... | CyberBlade XP4m32            | 1     |
| pci:1023-2200 | Trident ... | XGI Volari XP5               | 1     |
| pci:102b-0520 | Matrox E... | MGA G200                     | 1     |
| pci:102b-0525 | Matrox E... | MGA G400/G450                | 1     |
| pci:1039-6326 | Silicon ... | 86C326 5598/6326             | 1     |
| pci:104d-8087 | Sony        | Multimedia video controller  | 1     |
| pci:109e-034e | Brooktree   | Multimedia video controller  | 1     |
| pci:109e-036c | Brooktree   | Bt879(??) Video Capture      | 1     |
| pci:10c8-0005 | Neomagic    | NM2200 [MagicGraph 256AV]    | 1     |
| pci:10de-0047 | Nvidia      | NV40 [GeForce 6800 GS]       | 1     |
| pci:10de-00cc | Nvidia      | NV41GLM [Quadro FX Go1400]   | 1     |
| pci:10de-00fa | Nvidia      | NV39 [GeForce PCX 5750]      | 1     |
| pci:10de-0101 | Nvidia      | NV10 [GeForce 256 DDR]       | 1     |
| pci:10de-0144 | Nvidia      | NV43M [GeForce Go 6600]      | 1     |
| pci:10de-0146 | Nvidia      | NV43M [GeForce Go6200 TE ... | 1     |
| pci:10de-0147 | Nvidia      | NV43 [GeForce 6700 XL]       | 1     |
| pci:10de-0150 | Nvidia      | NV15 [GeForce2 GTS/Pro]      | 1     |
| pci:10de-0152 | Nvidia      | NV15 [GeForce2 Ultra]        | 1     |
| pci:10de-0170 | Nvidia      | NV17 [GeForce4 MX 460]       | 1     |
| pci:10de-0177 | Nvidia      | NV17M [GeForce4 460 Go]      | 1     |
| pci:10de-0182 | Nvidia      | NV18 [GeForce4 MX 440SE A... | 1     |
| pci:10de-0190 | Nvidia      | G80 [GeForce 8800 GTS / 8... | 1     |
| pci:10de-0194 | Nvidia      | G80 [GeForce 8800 Ultra]     | 1     |
| pci:10de-01d6 | Nvidia      | G72M [GeForce Go 7200]       | 1     |
| pci:10de-0245 | Nvidia      | C51 [Quadro NVS 210S/GeFo... | 1     |
| pci:10de-0250 | Nvidia      | NV25 [GeForce4 Ti 4600]      | 1     |
| pci:10de-0258 | Nvidia      | NV25GL [Quadro4 900 XGL]     | 1     |
| pci:10de-0281 | Nvidia      | NV28 [GeForce4 Ti 4200 AG... | 1     |
| pci:10de-0323 | Nvidia      | NV34 [GeForce FX 5200LE]     | 1     |
| pci:10de-0329 | Nvidia      | NV34M [GeForce FX Go5200]    | 1     |
| pci:10de-032a | Nvidia      | NV34GL [Quadro NVS 280 PCI]  | 1     |
| pci:10de-032b | Nvidia      | NV34GL [Quadro FX 500/600... | 1     |
| pci:10de-032c | Nvidia      | NV34M [GeForce FX Go5300 ... | 1     |
| pci:10de-0348 | Nvidia      | NV36M [GeForce FX Go5700]    | 1     |
| pci:10de-0390 | Nvidia      | G73 [GeForce 7650 GS]        | 1     |
| pci:10de-0395 | Nvidia      | G73 [GeForce 7300 GT]        | 1     |
| pci:10de-0397 | Nvidia      | G73M [GeForce Go 7700]       | 1     |
| pci:10de-0424 | Nvidia      | G86 [GeForce 8400 GS]        | 1     |
| pci:10de-05e0 | Nvidia      | GT200b [GeForce GTX 295]     | 1     |
| pci:10de-0601 | Nvidia      | G92 [GeForce 9800 GT]        | 1     |
| pci:10de-0621 | Nvidia      | G94 [GeForce GT 230]         | 1     |
| pci:10de-0624 | Nvidia      | G94 [GeForce 9600 GT Gree... | 1     |
| pci:10de-0628 | Nvidia      | G94M [GeForce 9800M GTS]     | 1     |
| pci:10de-062f | Nvidia      | G94 [GeForce 9800 S]         | 1     |
| pci:10de-0651 | Nvidia      | G96CM [GeForce G 110M]       | 1     |
| pci:10de-065a | Nvidia      | G96GLM [Quadro FX 1700M]     | 1     |
| pci:10de-06ca | Nvidia      | GF100M [GeForce GTX 480M]    | 1     |
| pci:10de-06de | Nvidia      | GF100GL [Tesla T20 Proces... | 1     |
| pci:10de-06ed | Nvidia      | G98 [GeForce 9600 GT / 98... | 1     |
| pci:10de-06f9 | Nvidia      | G98GL [Quadro FX 370 LP]     | 1     |
| pci:10de-06fb | Nvidia      | G98GLM [Quadro FX 370M]      | 1     |
| pci:10de-07e0 | Nvidia      | C73 [GeForce 7150 / nForc... | 1     |
| pci:10de-0864 | Nvidia      | C79 [GeForce 9300]           | 1     |
| pci:10de-0868 | Nvidia      | C79 [nForce 760i SLI]        | 1     |
| pci:10de-0871 | Nvidia      | C79 [GeForce 9200]           | 1     |
| pci:10de-0a62 | Nvidia      | GT218 [GeForce 205]          | 1     |
| pci:10de-0a73 | Nvidia      | GT218M [GeForce 305M]        | 1     |
| pci:10de-0a7c | Nvidia      | GT218GLM [Quadro FX 380M]    | 1     |
| pci:10de-0ca0 | Nvidia      | GT215 [GeForce GT 330]       | 1     |
| pci:10de-0cb0 | Nvidia      | GT215M [GeForce GTS 350M]    | 1     |
| pci:10de-0df9 | Nvidia      | GF108GLM [Quadro 500M]       | 1     |
| pci:10de-0fe2 | Nvidia      | GK107M [GeForce GT 745M]     | 1     |
| pci:10de-0fff | Nvidia      | GK107GL [Quadro 410]         | 1     |
| pci:10de-1022 | Nvidia      | GK110GL [Tesla K20c]         | 1     |
| pci:10de-1024 | Nvidia      | GK180GL [Tesla K40c]         | 1     |
| pci:10de-1052 | Nvidia      | GF119M [GeForce GT 520M]     | 1     |
| pci:10de-116f | Nvidia      | VGA compatible controller    | 1     |
| pci:10de-11a7 | Nvidia      | GK104M [GeForce GTX 675MX]   | 1     |
| pci:10de-11b8 | Nvidia      | GK104GLM [Quadro K5100M]     | 1     |
| pci:10de-11bc | Nvidia      | GK104GLM [Quadro K5000M]     | 1     |
| pci:10de-11c3 | Nvidia      | GK106 [GeForce GTX 650 Ti... | 1     |
| pci:10de-124b | Nvidia      | GF116 [GeForce GT 640 OEM]   | 1     |
| pci:10de-1289 | Nvidia      | GK208 [GeForce GT 710]       | 1     |
| pci:10de-1295 | Nvidia      | GK208M [GeForce 710M]        | 1     |
| pci:10de-1296 | Nvidia      | GK208M [GeForce 825M]        | 1     |
| pci:10de-131a | Nvidia      | 3D controller                | 1     |
| pci:10de-1349 | Nvidia      | GM108M [GeForce 930M]        | 1     |
| pci:10de-1399 | Nvidia      | GM107M [GeForce 945M]        | 1     |
| pci:10de-13b2 | Nvidia      | GM107GLM [Quadro M600M]      | 1     |
| pci:10de-15f7 | Nvidia      | GP100GL [Tesla P100 PCIe ... | 1     |
| pci:10de-1600 | Nvidia      | Graphics Device              | 1     |
| pci:10de-17f0 | Nvidia      | GM200GL [Quadro M6000]       | 1     |
| pci:10de-1b87 | Nvidia      | GP104 [P104-100]             | 1     |
| pci:10de-1db4 | Nvidia      | GV100GL [Tesla V100 PCIe ... | 1     |
| pci:10de-1f55 | Nvidia      | TU106BM [GeForce RTX 2060... | 1     |
| pci:10de-1f76 | Nvidia      | TU106GLM [Quadro RTX 3000... | 1     |
| pci:10de-1fb0 | Nvidia      | TU117GLM [Quadro T1000 Mo... | 1     |
| pci:10de-1fb2 | Nvidia      | TU117GLM [Quadro T400 Mob... | 1     |
| pci:10de-2231 | Nvidia      | GA102GL [RTX A5000]          | 1     |
| pci:10de-2420 | Nvidia      | GA103M [GeForce RTX 3080 ... | 1     |
| pci:10de-2507 | Nvidia      | GA106 [Geforce RTX 3050]     | 1     |
| pci:10de-8012 | Nvidia      | 3D controller                | 1     |
| pci:1106-5122 | VIA Tech... | VX855/VX875 Chrome 9 HCM ... | 1     |
| pci:1142-6424 | Alliance... | ProVideo 6424                | 1     |
| pci:11de-6120 | Zoran       | ZR36120                      | 1     |
| pci:11ee-4d78 | Dome Ima... | Dome Imaging Display cont... | 1     |
| pci:11ff-0002 | Scion       | Multimedia video controller  | 1     |
| pci:121a-0002 | 3Dfx Int... | Voodoo 2                     | 1     |
| pci:126f-0718 | Silicon ... | SM718 LynxSE+                | 1     |
| pci:12d2-0018 | NVidia /... | Riva128                      | 1     |
| pci:1461-0054 | Avermedi... | Multimedia video controller  | 1     |
| pci:14f1-2b30 | Conexant... | Conexant Display controller  | 1     |
| pci:14f1-5851 | Conexant... | Conexant Multimedia video... | 1     |
| pci:14f1-8000 | Conexant... | Conexant Multimedia video... | 1     |
| pci:1797-6800 | Intersil... | Multimedia video controller  | 1     |
| pci:18ca-0021 | XGI Tech... | Z9s/Z9m (XG21 core)          | 1     |
| pci:18ca-0027 | XGI Tech... | Z11/Z11M                     | 1     |
| pci:1aff-002b | Unknown     | Multimedia video controller  | 1     |
| pci:1cd7-0010 | Nanjing ... | Pro Capture Endpoint         | 1     |
| pci:1cd7-0012 | Nanjing ... | Electronics Multimedia vi... | 1     |
| pci:1cd7-0015 | Nanjing ... | Electronics Multimedia vi... | 1     |
| pci:1fcb-0001 | Unknown     | Multimedia video controller  | 1     |
| pci:5254-0820 | Unknown     | Multimedia video controller  | 1     |
| pci:5333-8901 | S3 Graphics | 86c775/86c785 [Trio 64V2/... | 1     |
| pci:5333-8a01 | S3 Graphics | 86c375 [ViRGE/DX] or 86c3... | 1     |
| pci:5333-8a13 | S3 Graphics | 86c360 [Trio 3D/1X], 86c3... | 1     |
| pci:5333-8c10 | S3 Graphics | 86C270-294 [SavageMX-MV]     | 1     |
| pci:5333-8c12 | S3 Graphics | 86C270-294 [SavageIX-MV]     | 1     |
| pci:5333-8e48 | S3 Graphics | Matrix [Chrome S25 / S27]    | 1     |
| pci:5333-9045 | S3 Graphics | Chrome 430 ULP / 435 ULP ... | 1     |
| pci:8086-1182 | Intel       | Display controller           | 1     |
| pci:8086-11a6 | Intel       | Display controller           | 1     |
| pci:8086-1a84 | Intel       | HD Graphics                  | 1     |
| pci:8086-258a | Intel       | E7221 Integrated Graphics... | 1     |
| pci:8086-3e9a | Intel       | Coffee Lake UHD Graphics     | 1     |
| pci:8086-4682 | Intel       | VGA compatible controller    | 1     |
| pci:8086-4690 | Intel       | VGA compatible controller    | 1     |
| pci:8086-4908 | Intel       | DG1 [Iris Xe Graphics]       | 1     |
| pci:8086-9be6 | Intel       | Comet Lake-S WS GT2 Integ... | 1     |
| pci:bdbd-a10b | Blackmag... | Blackmagic DeckLink          | 1     |
| pci:bdbd-a11a | Blackmag... | DeckLink HD Extreme 2        | 1     |
| pci:bdbd-a120 | Blackmag... | Decklink Studio 2            | 1     |
| pci:bdbd-a136 | Blackmag... | DeckLink 4K Extreme 12G      | 1     |
| pci:bdbd-a137 | Blackmag... | DeckLink Studio 4K           | 1     |
| pci:bdbd-a148 | Blackmag... | DeckLink SDI Micro           | 1     |
| pci:bdbd-a14b | Blackmag... | DeckLink 8K Pro              | 1     |
| pci:dada-0150 | Datapath... | VisionRGB-E2                 | 1     |
| pci:f1d0-c0fe | AJA Video   | Xena HS/HD-R                 | 1     |
| pci:f1d0-c0ff | AJA Video   | Kona/Xena 2                  | 1     |
| pci:f1d0-daff | AJA Video   | KONA LHi                     | 1     |
| pci:f1d0-eb0d | AJA Video   | Corvid 88                    | 1     |

### I/o card (PCI)

Total devices: 1

| ID            | MFG         | Name                         | Count |
|---------------|-------------|------------------------------|-------|
| pci:10e8-80d8 | Applied ... | PCI-7200 40MB/s 32-channe... | 1     |

### Input device controller (PCI)

Total devices: 389

| ID            | MFG         | Name                         | Count |
|---------------|-------------|------------------------------|-------|
| pci:1102-7002 | Creative... | SB Live! Game Port           | 195   |
| pci:1102-7003 | Creative... | SB Audigy Game Port          | 169   |
| pci:1102-7004 | Creative... | [SB Live! Value] Input de... | 10    |
| pci:1319-0802 | Fortemedia  | Xwave QS3000A [FM801 game... | 8     |
| pci:1102-7005 | Creative... | SB Audigy LS Game Port       | 6     |
| pci:127a-4312 | Rockwell... | Riptide PCI Game Controller  | 1     |

### Iommu (PCI)

Total devices: 11287

| ID            | MFG         | Name                         | Count |
|---------------|-------------|------------------------------|-------|
| pci:1022-15d1 | AMD         | Raven/Raven2 IOMMU           | 3733  |
| pci:1022-1481 | AMD         | Starship/Matisse IOMMU       | 3209  |
| pci:1022-1631 | AMD         | Renoir/Cezanne IOMMU         | 2798  |
| pci:1022-1577 | AMD         | Family 15h (Models 60h-6f... | 1521  |
| pci:8086-1f16 | Intel       | Atom processor C2000 RCEC    | 13    |
| pci:1022-1567 | AMD         | Mullins IOMMU                | 7     |
| pci:1022-164f | AMD         | Milan IOMMU                  | 4     |
| pci:1022-1437 | AMD         | Liverpool I/O Memory Mana... | 2     |

### Ipmi smic interface (PCI)

Total devices: 553

| ID            | MFG         | Name                         | Count |
|---------------|-------------|------------------------------|-------|
| pci:10ec-816c | Realtek ... | RTL8111xP IPMI interface     | 494   |
| pci:103c-3302 | Hewlett-... | Integrated Lights-Out Sta... | 52    |
| pci:8086-108e | Intel       | 82573E KCS (Active Manage... | 7     |

### Isdn adapter (PCI)

Total devices: 26

| ID            | MFG         | Name                         | Count |
|---------------|-------------|------------------------------|-------|
| pci:1244-0e00 | AVM         | Fritz!Card PCI v2.0 ISDN     | 11    |
| pci:1244-0a00 | AVM         | A1 ISDN [Fritz]              | 9     |
| pci:e159-0001 | Tiger Je... | Tiger3XX Modem/ISDN inter... | 3     |
| pci:1397-2bd0 | Cologne ... | ISDN network controller [... | 2     |
| pci:1133-e00b | Dialogic    | Diva ISDN PCI 2.02           | 1     |

### Memory controller (PCI)

Total devices: 45940

| ID            | MFG         | Name                         | Count |
|---------------|-------------|------------------------------|-------|
| pci:8086-9d21 | Intel       | Sunrise Point-LP PMC         | 9614  |
| pci:8086-a121 | Intel       | 100 Series/C230 Series Ch... | 4911  |
| pci:8086-a36f | Intel       | Cannon Lake PCH Shared SRAM  | 4746  |
| pci:8086-9def | Intel       | Cannon Point-LP Shared SRAM  | 2683  |
| pci:8086-a2a1 | Intel       | 200 Series/Z370 Chipset F... | 2288  |
| pci:8086-02ef | Intel       | Comet Lake PCH-LP Shared ... | 1844  |
| pci:8086-a0ef | Intel       | Tiger Lake-LP Shared SRAM    | 1822  |
| pci:10de-03f5 | Nvidia      | MCP61 Memory Controller      | 1550  |
| pci:8086-06ef | Intel       | Comet Lake PCH Shared SRAM   | 1334  |
| pci:8086-34ef | Intel       | Ice Lake-LP DRAM Controller  | 1003  |
| pci:10de-03ea | Nvidia      | MCP61 Memory Controller      | 821   |
| pci:10de-03e2 | Nvidia      | MCP61 Host Bridge            | 729   |
| pci:8086-43ef | Intel       | Tiger Lake-H Shared SRAM     | 569   |
| pci:10de-0a88 | Nvidia      | MCP79 Memory Controller      | 564   |
| pci:10de-0a89 | Nvidia      | MCP79 Memory Controller      | 564   |
| pci:10de-0aa4 | Nvidia      | MCP79 Memory Controller      | 564   |
| pci:10de-0a98 | Nvidia      | MCP79 Memory Controller      | 355   |
| pci:10de-0568 | Nvidia      | MCP78S [GeForce 8200] Mem... | 348   |
| pci:10de-0754 | Nvidia      | MCP78S [GeForce 8200] Mem... | 348   |
| pci:8086-a3a1 | Intel       | Cannon Lake PCH Power Man... | 331   |
| pci:10de-0270 | Nvidia      | MCP51 Host Bridge            | 292   |
| pci:10de-0751 | Nvidia      | MCP78S [GeForce 8200] Mem... | 276   |
| pci:10de-027e | Nvidia      | C51 Memory Controller 2      | 250   |
| pci:10de-027f | Nvidia      | C51 Memory Controller 3      | 250   |
| pci:10de-02f8 | Nvidia      | C51 Memory Controller 5      | 250   |
| pci:10de-02f9 | Nvidia      | C51 Memory Controller 4      | 250   |
| pci:10de-02fe | Nvidia      | C51 Memory Controller 1      | 250   |
| pci:10de-02ff | Nvidia      | C51 Host Bridge              | 250   |
| pci:10de-02fa | Nvidia      | C51 Memory Controller 0      | 232   |
| pci:10de-0369 | Nvidia      | MCP55 Memory Controller      | 225   |
| pci:10de-005e | Nvidia      | CK804 Memory Controller      | 195   |
| pci:10de-0272 | Nvidia      | MCP51 Memory Controller 0    | 183   |
| pci:10de-0547 | Nvidia      | MCP67 Memory Controller      | 170   |
| pci:8086-a1a1 | Intel       | C620 Series Chipset Famil... | 165   |
| pci:10de-07c8 | Nvidia      | MCP73 Memory Controller      | 148   |
| pci:10de-07cb | Nvidia      | nForce 610i/630i memory c... | 148   |
| pci:10de-07cd | Nvidia      | nForce 610i/630i memory c... | 148   |
| pci:10de-07ce | Nvidia      | nForce 610i/630i memory c... | 148   |
| pci:10de-07cf | Nvidia      | nForce 610i/630i memory c... | 148   |
| pci:10de-07d0 | Nvidia      | nForce 610i/630i memory c... | 148   |
| pci:10de-07d1 | Nvidia      | nForce 610i/630i memory c... | 148   |
| pci:10de-07d2 | Nvidia      | nForce 610i/630i memory c... | 148   |
| pci:10de-07d3 | Nvidia      | nForce 610i/630i memory c... | 148   |
| pci:10de-07d6 | Nvidia      | nForce 610i/630i memory c... | 148   |
| pci:10de-07d9 | Nvidia      | MCP73 Memory Controller      | 141   |
| pci:10de-02f0 | Nvidia      | C51 Host Bridge              | 121   |
| pci:10de-0444 | Nvidia      | MCP65 Memory Controller      | 118   |
| pci:10de-0d68 | Nvidia      | MCP89 Memory Controller      | 116   |
| pci:10de-0d69 | Nvidia      | MCP89 Memory Controller      | 116   |
| pci:10de-0d6d | Nvidia      | MCP89 Memory Controller      | 116   |
| pci:10de-0d6e | Nvidia      | MCP89 Memory Controller      | 116   |
| pci:10de-0d6f | Nvidia      | MCP89 Memory Controller      | 116   |
| pci:10de-0d70 | Nvidia      | MCP89 Memory Controller      | 116   |
| pci:10de-0d71 | Nvidia      | MCP89 Memory Controller      | 116   |
| pci:10de-0d72 | Nvidia      | MCP89 Memory Controller      | 116   |
| pci:10de-0d75 | Nvidia      | MCP89 Memory Controller      | 116   |
| pci:10de-0d7b | Nvidia      | MCP89 Memory Controller      | 116   |
| pci:10de-0541 | Nvidia      | MCP67 Memory Controller      | 113   |
| pci:10de-0445 | Nvidia      | MCP65 Memory Controller      | 102   |
| pci:10de-03a8 | Nvidia      | C55 Memory Controller        | 96    |
| pci:10de-03a9 | Nvidia      | C55 Memory Controller        | 96    |
| pci:10de-03aa | Nvidia      | C55 Memory Controller        | 96    |
| pci:10de-03ab | Nvidia      | C55 Memory Controller        | 96    |
| pci:10de-03ac | Nvidia      | C55 Memory Controller        | 96    |
| pci:10de-03ad | Nvidia      | C55 Memory Controller        | 96    |
| pci:10de-03ae | Nvidia      | C55 Memory Controller        | 96    |
| pci:10de-03af | Nvidia      | C55 Memory Controller        | 96    |
| pci:10de-03b0 | Nvidia      | C55 Memory Controller        | 96    |
| pci:10de-03b1 | Nvidia      | C55 Memory Controller        | 96    |
| pci:10de-03b2 | Nvidia      | C55 Memory Controller        | 96    |
| pci:10de-03b3 | Nvidia      | C55 Memory Controller        | 96    |
| pci:10de-03b4 | Nvidia      | C55 Memory Controller        | 96    |
| pci:10de-03b5 | Nvidia      | C55 Memory Controller        | 96    |
| pci:10de-03b6 | Nvidia      | C55 Memory Controller        | 96    |
| pci:10de-03ba | Nvidia      | C55 Memory Controller        | 96    |
| pci:10de-03bc | Nvidia      | C55 Memory Controller        | 96    |
| pci:8086-444e | Intel       | Turbo Memory Controller      | 83    |
| pci:8086-4def | Intel       | Jasper Lake Shared SRAM C... | 71    |
| pci:8086-7aa7 | Intel       | Alder Lake-S PCH Shared SRAM | 66    |
| pci:10de-036a | Nvidia      | MCP55 Memory Controller      | 40    |
| pci:10de-02f1 | Nvidia      | C51 Host Bridge              | 39    |
| pci:10de-02f3 | Nvidia      | C51 Host Bridge              | 34    |
| pci:10de-02f4 | Nvidia      | C51 Host Bridge              | 26    |
| pci:10de-01ec | Nvidia      | nForce2 Memory Controller 2  | 23    |
| pci:10de-01ed | Nvidia      | nForce2 Memory Controller 3  | 23    |
| pci:10de-01ee | Nvidia      | nForce2 Memory Controller 4  | 23    |
| pci:10de-01ef | Nvidia      | nForce2 Memory Controller 5  | 23    |
| pci:10de-01eb | Nvidia      | nForce2 Memory Controller 1  | 17    |
| pci:10de-02f7 | Nvidia      | C51 Host Bridge              | 16    |
| pci:8086-38ef | Intel       | RAM memory                   | 16    |
| pci:10de-02f5 | Nvidia      | C51 Host Bridge              | 14    |
| pci:10de-0808 | Nvidia      | nForce 790i Memory Contro... | 12    |
| pci:10de-0809 | Nvidia      | nForce 790i Memory Contro... | 12    |
| pci:10de-080a | Nvidia      | nForce 790i Memory Contro... | 12    |
| pci:10de-080b | Nvidia      | nForce 790i Memory Contro... | 12    |
| pci:10de-080c | Nvidia      | nForce 790i Memory Contro... | 12    |
| pci:10de-080d | Nvidia      | nForce 790i Memory Contro... | 12    |
| pci:10de-080e | Nvidia      | nForce 790i Memory Contro... | 12    |
| pci:10de-080f | Nvidia      | nForce 790i Memory Contro... | 12    |
| pci:10de-0810 | Nvidia      | nForce 790i Memory Contro... | 12    |
| pci:10de-0811 | Nvidia      | nForce 790i Memory Contro... | 12    |
| pci:10de-0812 | Nvidia      | nForce 790i Memory Contro... | 12    |
| pci:10de-0813 | Nvidia      | nForce 790i Memory Contro... | 12    |
| pci:10de-0814 | Nvidia      | nForce 790i Memory Contro... | 12    |
| pci:10de-081a | Nvidia      | nForce 790i Memory Contro... | 12    |
| pci:10de-006f | Nvidia      | nForce4 Intel Edition Mem... | 9     |
| pci:10de-0075 | Nvidia      | nForce4 Intel Edition Mem... | 9     |
| pci:10de-0076 | Nvidia      | nForce4 Intel Edition Mem... | 9     |
| pci:10de-0078 | Nvidia      | nForce4 Intel Edition Mem... | 9     |
| pci:10de-0079 | Nvidia      | nForce4 Intel Edition Mem... | 9     |
| pci:10de-007a | Nvidia      | nForce4 Intel Edition Mem... | 9     |
| pci:10de-007b | Nvidia      | nForce4 Intel Edition Mem... | 9     |
| pci:10de-007c | Nvidia      | nForce4 Intel Edition Mem... | 9     |
| pci:10de-007d | Nvidia      | nForce4 Intel Edition Mem... | 9     |
| pci:10de-00b4 | Nvidia      | nForce4 Intel Edition Mem... | 9     |
| pci:1590-005f | Hewlett-... | Memory controller            | 9     |
| pci:10de-007f | Nvidia      | nForce4 Intel Edition Mem... | 8     |
| pci:8086-19de | Intel       | Atom Processor C3000 Seri... | 8     |
| pci:8086-490e | Intel       | Mini CTA                     | 8     |
| pci:10de-01ea | Nvidia      | nForce2 Memory Controller 0  | 6     |
| pci:10de-0361 | Nvidia      | MCP55 LPC Bridge             | 6     |
| pci:10de-00d3 | Nvidia      | CK804 Memory Controller      | 5     |
| pci:8086-51ef | Intel       | Alder Lake PCH Shared SRAM   | 5     |
| pci:1912-0011 | Renesas ... | SH7757 PCIe End-Point [PBI]  | 3     |
| pci:10de-003f | Nvidia      | nForce4 Intel Edition Hyp... | 2     |
| pci:8086-1bce | Intel       | RAM memory                   | 2     |
| pci:8086-98ef | Intel       | Shared SRAM Controller       | 2     |
| pci:10de-0074 | Nvidia      | RAM memory                   | 1     |
| pci:10ee-1015 | Xilinx      | Memory controller            | 1     |
| pci:10ee-9023 | Xilinx      | Memory controller            | 1     |
| pci:10ee-9024 | Xilinx      | Memory controller            | 1     |
| pci:110a-4078 | Siemens     | RAM memory                   | 1     |
| pci:15b3-020d | Mellanox... | MT28800 Family [ConnectX-... | 1     |
| pci:1b94-1500 | Signatec... | Memory controller            | 1     |
| pci:1d92-008d | Abaco Sy... | Memory controller            | 1     |
| pci:1d9b-0400 | Facebook    | Memory controller            | 1     |
| pci:8086-0374 | Intel       | 80333 Address Translation... | 1     |
| pci:8086-5a92 | Intel       | Memory controller            | 1     |

### Modem (PCI)

Total devices: 490

| ID            | MFG         | Name                         | Count |
|---------------|-------------|------------------------------|-------|
| pci:8086-266d | Intel       | 82801FB/FBM/FR/FW/FRW (IC... | 158   |
| pci:8086-24c6 | Intel       | 82801DB/DBL/DBM (ICH4/ICH... | 67    |
| pci:1002-4378 | AMD         | IXP SB400 AC'97 Modem Con... | 52    |
| pci:1106-3068 | VIA Tech... | AC'97 Modem Controller       | 45    |
| pci:1039-7013 | Silicon ... | AC'97 Modem Controller       | 37    |
| pci:1057-3052 | Motorola    | SM56 Data Fax Modem          | 29    |
| pci:11c1-044c | LSI         | LT WinModem                  | 15    |
| pci:8086-2486 | Intel       | 82801CA/CAM AC'97 Modem C... | 11    |
| pci:10b9-5457 | ULi Elec... | M5457 AC'97 Modem Controller | 7     |
| pci:8086-1040 | Intel       | 536EP Data Fax Modem         | 7     |
| pci:8086-24d6 | Intel       | 82801EB/ER (ICH5/ICH5R) A... | 7     |
| pci:1002-434d | AMD         | SB200 AC97 Modem Controller  | 6     |
| pci:10de-00d9 | Nvidia      | nForce3 Audio                | 6     |
| pci:11c1-044e | LSI         | LT WinModem                  | 6     |
| pci:11c1-0440 | LSI         | 56k WinModem                 | 4     |
| pci:134d-7892 | PCTel       | HSP MicroModem 56            | 4     |
| pci:1543-3052 | SILICON ... | Intel 537 [Winmodem]         | 4     |
| pci:2003-8800 | Smart Link  | LM-I56N                      | 3     |
| pci:8086-1080 | Intel       | FA82537EP 56K V.92 Data/F... | 3     |
| pci:8086-2446 | Intel       | 82801BA/BAM AC'97 Modem C... | 3     |
| pci:11c1-0448 | LSI         | WinModem 56k                 | 2     |
| pci:11c1-0449 | LSI         | L56xM+S [Mars-2] WinModem... | 2     |
| pci:134d-7890 | PCTel       | HSP MicroModem 56            | 2     |
| pci:2000-2800 | Smart Link  | SmartPCI2800 V.92 PCI Sof... | 2     |
| pci:8086-27dd | Intel       | 82801G (ICH7 Family) AC'9... | 2     |
| pci:10b9-5459 | ULi Elec... | SmartLink SmartPCI561 56K... | 1     |
| pci:10b9-545a | ULi Elec... | SmartLink SmartPCI563 56K... | 1     |
| pci:11c1-0450 | LSI         | LT WinModem                  | 1     |
| pci:11c1-045c | LSI         | LT WinModem                  | 1     |
| pci:134d-2189 | PCTel       | HSP56 MicroModem             | 1     |
| pci:163c-3052 | Smart Link  | SmartLink SmartPCI562 56K... | 1     |

### Multimedia (PCI)

Total devices: 1

| ID            | MFG         | Name                         | Count |
|---------------|-------------|------------------------------|-------|
| pci:0002-8290 | Unknown     |                              | 1     |

### Multimedia controller (PCI)

Total devices: 7336

| ID            | MFG         | Name                         | Count |
|---------------|-------------|------------------------------|-------|
| pci:1022-15e2 | AMD         | ACP/ACP3X/ACP6x Audio Cop... | 4341  |
| pci:8086-22b8 | Intel       | Atom/Celeron/Pentium Proc... | 818   |
| pci:14e4-1570 | Broadcom    | 720p FaceTime HD Camera      | 537   |
| pci:8086-1919 | Intel       | Xeon E3-1200 v5/E3-1500 v... | 381   |
| pci:8086-9d32 | Intel       | CSI-2 Host Controller        | 376   |
| pci:109e-0878 | Brooktree   | Bt878 Audio Capture          | 125   |
| pci:8086-5a88 | Intel       | Celeron N3350/Pentium N42... | 108   |
| pci:1131-7231 | Philips ... | SAA7231                      | 93    |
| pci:1131-7160 | Philips ... | SAA7160                      | 83    |
| pci:8086-8a19 | Intel       | Image Signal Processor       | 50    |
| pci:1131-7164 | Philips ... | SAA7164                      | 41    |
| pci:8086-9a19 | Intel       | Multimedia controller        | 37    |
| pci:1822-4e35 | Twinhan ... | Mantis DTV PCI Bridge Con... | 36    |
| pci:14f1-8804 | Conexant... | CX23880/1/2/3 PCI Video a... | 31    |
| pci:11bd-bede | Pinnacle... | AV/DV Studio Capture Card    | 28    |
| pci:14e4-1615 | Broadcom    | BCM70015 Video Decoder [C... | 28    |
| pci:8086-0f38 | Intel       | Atom Processor Z36xxx/Z37... | 26    |
| pci:544d-6178 | TBS Tech... | DVB Tuner PCIe Card          | 17    |
| pci:1002-ac12 | AMD         | Theater HD T507 (DVB-T) T... | 14    |
| pci:12ab-0380 | YUAN Hig... | Game Capture 4K60 Pro        | 14    |
| pci:14e4-1612 | Broadcom    | BCM70012 Video Decoder [C... | 10    |
| pci:1131-7162 | Philips ... | SAA7162                      | 9     |
| pci:8086-4e19 | Intel       | JasperLake IPU               | 9     |
| pci:dd01-0003 | Digital ... | Octopus DVB Adapter          | 9     |
| pci:1745-3000 | ViXS Sys... | Colossus Encoder             | 7     |
| pci:dd01-0006 | Digital ... | Cine V7                      | 6     |
| pci:1057-3410 | Motorola    | DSP56361 Digital Signal P... | 5     |
| pci:10cf-2036 | Fujitsu ... | DT-XXX                       | 5     |
| pci:1002-4d51 | AMD         | Unified AVStream             | 4     |
| pci:1057-1801 | Motorola    | DSP56301 Digital Signal P... | 4     |
| pci:1002-ad18 | AMD         | Multimedia controller        | 3     |
| pci:10cf-202a | Fujitsu ... | Integrated MPEG Encoder      | 3     |
| pci:10cf-2030 | Fujitsu ... | Fujitsu Multimedia contro... | 3     |
| pci:10ee-222a | Xilinx      | Multimedia controller        | 3     |
| pci:1797-6805 | Intersil... | HV4000 DVR card              | 3     |
| pci:1797-6869 | Intersil... | C968 PCIe SD Capture         | 3     |
| pci:1a00-0001 | Unknown     | Multimedia controller        | 3     |
| pci:1002-4d53 | AMD         | Theater 550 PRO PCIe         | 2     |
| pci:10b5-9056 | PLX Tech... | PCI9056 32-bit 66MHz PCI ... | 2     |
| pci:116e-00d0 | Electron... | Multimedia controller        | 2     |
| pci:116e-0600 | Electron... | Multimedia controller        | 2     |
| pci:11bd-0040 | Pinnacle... | Royal TS Function 1          | 2     |
| pci:11bd-0041 | Pinnacle... | RoyalTS Function 2           | 2     |
| pci:11bd-0042 | Pinnacle... | Royal TS Function 3          | 2     |
| pci:123f-8120 | LSI Logic   | DVxplore Codec               | 2     |
| pci:12ab-0371 | YUAN Hig... | Game Capture 4K60 Pro        | 2     |
| pci:12ab-0710 | YUAN Hig... | Multimedia controller        | 2     |
| pci:14b5-0600 | Creamware   | Pulsar2                      | 2     |
| pci:14f1-8803 | Conexant... | CX2388x TV Capture Chip      | 2     |
| pci:1745-2100 | ViXS Sys... | XCode 2100 Series            | 2     |
| pci:1797-6814 | Intersil... | TW6816 multimedia video c... | 2     |
| pci:1797-6815 | Intersil... | TW6816 multimedia video c... | 2     |
| pci:1797-6816 | Intersil... | TW6816 multimedia video c... | 2     |
| pci:1797-6817 | Intersil... | TW6816 multimedia video c... | 2     |
| pci:8086-9830 | Intel       | Multimedia controller        | 2     |
| pci:1002-4d52 | AMD         | Theater 550 PRO PCI [ATI ... | 1     |
| pci:1002-ac02 | AMD         | TV Wonder HD 600 PCIe        | 1     |
| pci:1017-1801 | SPEA Sof... | Multimedia controller        | 1     |
| pci:102b-8350 | Matrox E... | Matrox Multimedia controller | 1     |
| pci:102f-01ba | Toshiba ... | Toshiba Multimedia contro... | 1     |
| pci:109e-037e | Brooktree   | Multimedia controller        | 1     |
| pci:109e-0858 | Brooktree   | Multimedia controller        | 1     |
| pci:109e-0868 | Brooktree   | Multimedia controller        | 1     |
| pci:10cf-2026 | Fujitsu ... | Fujitsu Multimedia contro... | 1     |
| pci:10cf-2049 | Fujitsu ... | Fujitsu Multimedia contro... | 1     |
| pci:1105-8300 | Sigma De... | REALmagic Hollywood Plus ... | 1     |
| pci:1105-8400 | Sigma De... | EM840x REALmagic DVD/MPEG... | 1     |
| pci:1131-5134 | Philips ... | Multimedia controller        | 1     |
| pci:1131-5402 | Philips ... | TriMedia TM1300              | 1     |
| pci:1172-4c15 | Altera      | Multimedia controller        | 1     |
| pci:11bd-bed6 | Pinnacle... | Pinnacle Multimedia contr... | 1     |
| pci:127e-0010 | Winnov, ... | Videum 1000 Plus             | 1     |
| pci:12ab-1e3c | YUAN Hig... | DIB7700 DTV tuner            | 1     |
| pci:13fe-0059 | Advantech   | Multimedia controller        | 1     |
| pci:14b5-0200 | Creamware   | Scope                        | 1     |
| pci:14b5-0300 | Creamware   | Pulsar                       | 1     |
| pci:14e4-1610 | Broadcom    | Multimedia controller        | 1     |
| pci:14e4-6865 | Broadcom    | Multimedia controller        | 1     |
| pci:14f1-8002 | Conexant... | Conexant Multimedia contr... | 1     |
| pci:1a00-0002 |             | Multimedia controller        | 1     |
| pci:50c1-000b | Unknown     | Multimedia controller        | 1     |
| pci:8086-1a88 | Intel       | Imaging Signal Processor ... | 1     |

### Multiport serial controller (PCI)

Total devices: 49

| ID            | MFG         | Name                         | Count |
|---------------|-------------|------------------------------|-------|
| pci:1fd4-1999 | SUNIX       | Multiport serial controller  | 46    |
| pci:135a-08c1 | Brain Boxes | Multiport serial controller  | 1     |
| pci:135c-0170 | Quatech     | QSCLP-100                    | 1     |
| pci:1fff-8018 | MCST        | I2C SPI                      | 1     |

### Net/ethernet (PCI)

Total devices: 106336

| ID            | MFG         | Name                         | Count |
|---------------|-------------|------------------------------|-------|
| pci:10ec-8168 | Realtek ... | RTL8111/8168/8411 PCI Exp... | 52486 |
| pci:10ec-8136 | Realtek ... | RTL810xE PCI Express Fast... | 11430 |
| pci:8086-15b8 | Intel       | Ethernet Connection (2) I... | 1893  |
| pci:10ec-8139 | Realtek ... | RTL-8100/8101L/8139 PCI F... | 1722  |
| pci:1969-1083 | Qualcomm... | AR8151 v2.0 Gigabit Ethernet | 1652  |
| pci:8086-153a | Intel       | Ethernet Connection I217-LM  | 1581  |
| pci:10ec-8125 | Realtek ... | RTL8125 2.5GbE Controller    | 1144  |
| pci:1969-2062 | Attansic... | AR8152 v2.0 Fast Ethernet    | 965   |
| pci:8086-15bc | Intel       | Ethernet Connection (7) I... | 955   |
| pci:1969-1091 | Qualcomm... | AR8161 Gigabit Ethernet      | 908   |
| pci:1969-1063 | Qualcomm... | AR8131 Gigabit Ethernet      | 849   |
| pci:14e4-1692 | Broadcom    | NetLink BCM57780 Gigabit ... | 848   |
| pci:14e4-16b5 | Broadcom    | NetLink BCM57785 Gigabit ... | 829   |
| pci:8086-155a | Intel       | Ethernet Connection I218-LM  | 757   |
| pci:1969-1026 | Qualcomm... | AR8121/AR8113/AR8114 Giga... | 748   |
| pci:8086-153b | Intel       | Ethernet Connection I217-V   | 736   |
| pci:8086-15b7 | Intel       | Ethernet Connection (2) I... | 701   |
| pci:1969-e091 | Qualcomm... | Killer E220x Gigabit Ethe... | 686   |
| pci:8086-156f | Intel       | Ethernet Connection I219-LM  | 681   |
| pci:8086-15d7 | Intel       | Ethernet Connection (4) I... | 674   |
| pci:11ab-4354 | Marvell ... | 88E8040 PCI-E Fast Ethern... | 659   |
| pci:1969-10a1 | Qualcomm... | QCA8171 Gigabit Ethernet     | 626   |
| pci:8086-15a1 | Intel       | Ethernet Connection (2) I... | 617   |
| pci:8086-15d8 | Intel       | Ethernet Connection (4) I... | 613   |
| pci:8086-15a2 | Intel       | Ethernet Connection (3) I... | 611   |
| pci:1969-1062 | Qualcomm... | AR8132 Fast Ethernet         | 600   |
| pci:8086-15be | Intel       | Ethernet Connection (6) I... | 578   |
| pci:14e4-16b4 | Broadcom    | NetXtreme BCM57765 Gigabi... | 504   |
| pci:14e4-1693 | Broadcom    | NetLink BCM5787M Gigabit ... | 496   |
| pci:8086-15bb | Intel       | Ethernet Connection (7) I... | 491   |
| pci:14e4-1681 | Broadcom... | NetXtreme BCM5761 Gigabit... | 465   |
| pci:11ab-4364 | Marvell ... | 88E8056 PCI-E Gigabit Eth... | 460   |
| pci:1969-10a0 | Qualcomm... | QCA8172 Fast Ethernet        | 456   |
| pci:1969-1090 | Qualcomm... | AR8162 Fast Ethernet         | 450   |
| pci:197b-0250 | JMicron ... | JMC250 PCI Express Gigabi... | 448   |
| pci:1969-1048 | Qualcomm... | Attansic L1 Gigabit Ethernet | 445   |
| pci:14e4-1684 | Broadcom... | NetXtreme BCM5764M Gigabi... | 442   |
| pci:8086-15f3 | Intel       | Ethernet Controller I225-V   | 438   |
| pci:1969-e0b1 | Qualcomm... | Killer E2500 Gigabit Ethe... | 436   |
| pci:1969-e0a1 | Qualcomm... | Killer E2400 Gigabit Ethe... | 426   |
| pci:10ec-8169 | Realtek ... | RTL8169 PCI Gigabit Ether... | 417   |
| pci:10de-0ab0 | Nvidia      | MCP79 Ethernet               | 409   |
| pci:11ab-4363 | Marvell ... | 88E8055 PCI-E Gigabit Eth... | 368   |
| pci:14e4-1698 | Broadcom    | NetLink BCM5784M Gigabit ... | 346   |
| pci:8086-1570 | Intel       | Ethernet Connection I219-V   | 323   |
| pci:8086-0d4f | Intel       | Ethernet Connection (10) ... | 318   |
| pci:1039-0191 | Silicon ... | 191 Gigabit Ethernet Adapter | 300   |
| pci:10de-0760 | Nvidia      | MCP77 Ethernet               | 285   |
| pci:14e4-1686 | Broadcom    | NetXtreme BCM57766 Gigabi... | 283   |
| pci:10ec-8167 | Realtek ... | RTL-8110SC/8169SC Gigabit... | 271   |
| pci:14e4-1713 | Broadcom    | NetLink BCM5906M Fast Eth... | 267   |
| pci:1106-3106 | VIA Tech... | VT6105/VT6106S [Rhine-III]   | 265   |
| pci:11ab-4381 | Marvell ... | Yukon Optima 88E8059 [PCI... | 262   |
| pci:8086-0000 | Intel       | PROSet/Wireless WiFi Soft... | 249   |
| pci:1969-2060 | Qualcomm... | AR8152 v1.1 Fast Ethernet    | 241   |
| pci:8086-15bd | Intel       | Ethernet Connection (6) I... | 232   |
| pci:14e4-167a | Broadcom... | NetXtreme BCM5754 Gigabit... | 231   |
| pci:1969-2048 | Qualcomm... | Attansic L2 Fast Ethernet    | 227   |
| pci:8086-15fc | Intel       | Ethernet Connection (13) ... | 225   |
| pci:11ab-436a | Marvell ... | 88E8058 PCI-E Gigabit Eth... | 224   |
| pci:11ab-4320 | Marvell ... | 88E8001 Gigabit Ethernet ... | 211   |
| pci:11ab-4362 | Marvell ... | 88E8053 PCI-E Gigabit Eth... | 209   |
| pci:8086-15e3 | Intel       | Ethernet Connection (5) I... | 205   |
| pci:14e4-1677 | Broadcom    | NetXtreme BCM5751 Gigabit... | 193   |
| pci:1969-1073 | Qualcomm... | AR8151 v1.0 Gigabit Ethernet | 192   |
| pci:11ab-4380 | Marvell ... | 88E8057 PCI-E Gigabit Eth... | 181   |
| pci:8086-109a | Intel       | 82573L Gigabit Ethernet C... | 181   |
| pci:10de-054c | Nvidia      | MCP67 Ethernet               | 165   |
| pci:14e4-16b1 | Broadcom    | NetLink BCM57781 Gigabit ... | 165   |
| pci:14e4-16b3 | Broadcom    | NetXtreme BCM57786 Gigabi... | 164   |
| pci:14e4-1673 | Broadcom    | NetXtreme BCM5755M Gigabi... | 163   |
| pci:10ec-2600 | Realtek ... | Killer E2600 Gigabit Ethe... | 162   |
| pci:14e4-1600 | Broadcom    | NetXtreme BCM5752 Gigabit... | 143   |
| pci:1186-4300 | D-Link S... | DGE-528T Gigabit Ethernet... | 141   |
| pci:14e4-167b | Broadcom... | NetXtreme BCM5755 Gigabit... | 140   |
| pci:1d6a-07b1 | Aquantia    | AQC107 NBase-T/IEEE 802.3... | 135   |
| pci:14e4-165f | Broadcom    | NetXtreme BCM5720 Gigabit... | 128   |
| pci:8086-15a3 | Intel       | Ethernet Connection (3) I... | 128   |
| pci:10de-07dc | Nvidia      | MCP73 Ethernet               | 126   |
| pci:8086-0d4c | Intel       | Ethernet Connection (11) ... | 124   |
| pci:14e4-1680 | Broadcom... | NetXtreme BCM5761e Gigabi... | 118   |
| pci:8086-0d4d | Intel       | Ethernet Connection (11) ... | 118   |
| pci:11ab-4353 | Marvell ... | 88E8039 PCI-E Fast Ethern... | 117   |
| pci:14e4-1639 | Broadcom... | NetXtreme II BCM5709 Giga... | 117   |
| pci:11ab-436b | Marvell ... | 88E8071 PCI-E Gigabit Eth... | 111   |
| pci:14e4-1691 | Broadcom... | NetLink BCM57788 Gigabit ... | 109   |
| pci:197b-0260 | JMicron ... | JMC260 PCI Express Fast E... | 108   |
| pci:11ab-436c | Marvell ... | 88E8072 PCI-E Gigabit Eth... | 97    |
| pci:8086-15fa | Intel       | Ethernet Connection (14) ... | 95    |
| pci:8086-0d4e | Intel       | Ethernet Connection (10) ... | 94    |
| pci:1039-0900 | Silicon ... | SiS900 PCI Fast Ethernet     | 93    |
| pci:8086-1559 | Intel       | Ethernet Connection I218-V   | 92    |
| pci:8086-1096 | Intel       | 80003ES2LAN Gigabit Ether... | 89    |
| pci:13f0-0200 | Sundance... | IC Plus IP100A Integrated... | 88    |
| pci:8086-0d55 | Intel       | Ethernet Connection (12) ... | 88    |
| pci:8086-15a0 | Intel       | Ethernet Connection (2) I... | 87    |
| pci:11ab-4351 | Marvell ... | 88E8036 PCI-E Fast Ethern... | 85    |
| pci:8086-10fb | Intel       | 82599ES 10-Gigabit SFI/SF... | 84    |
| pci:8086-105e | Intel       | 82571EB/82571GB Gigabit E... | 81    |
| pci:10ec-3000 | Realtek ... | Killer E3000 2.5GbE Contr... | 75    |
| pci:14e4-1682 | Broadcom    | NetXtreme BCM57762 Gigabi... | 72    |
| pci:10ec-2502 | Realtek ... | Killer E2500 Gigabit Ethe... | 68    |
| pci:8086-1229 | Intel       | 82557/8/9/0/1 Ethernet Pr... | 66    |
| pci:8086-107c | Intel       | 82541PI Gigabit Ethernet ... | 65    |
| pci:14e4-1687 | Broadcom    | NetXtreme BCM5762 Gigabit... | 64    |
| pci:11ab-4357 | Marvell ... | 88E8042 PCI-E Fast Ethern... | 60    |
| pci:1d6a-d107 | Aquantia    | AQC107 NBase-T/IEEE 802.3... | 58    |
| pci:14e4-169c | Broadcom    | NetXtreme BCM5788 Gigabit... | 57    |
| pci:8086-1068 | Intel       | 82562ET/EZ/GT/GZ - PRO/10... | 57    |
| pci:14e4-165a | Broadcom... | NetXtreme BCM5722 Gigabit... | 55    |
| pci:11ab-4355 | Marvell ... | 88E8040T PCI-E Fast Ether... | 54    |
| pci:14e4-1657 | Broadcom    | NetXtreme BCM5719 Gigabit... | 54    |
| pci:14e4-165b | Broadcom    | NetXtreme BCM5723 Gigabit... | 54    |
| pci:8086-1563 | Intel       | Ethernet Controller 10G X... | 54    |
| pci:8086-15fb | Intel       | Ethernet Connection (13) ... | 54    |
| pci:10de-0450 | Nvidia      | MCP65 Ethernet               | 52    |
| pci:14e4-167d | Broadcom    | NetXtreme BCM5751M Gigabi... | 52    |
| pci:8086-15b9 | Intel       | Ethernet Connection (3) I... | 51    |
| pci:8086-1528 | Intel       | Ethernet Controller 10-Gi... | 50    |
| pci:10ec-8161 | Realtek ... | RTL8111/8168/8411 PCI Exp... | 49    |
| pci:1186-1300 | D-Link S... | RTL8139 Ethernet             | 46    |
| pci:14e4-169b | Broadcom    | NetLink BCM5787 Gigabit E... | 46    |
| pci:8086-1050 | Intel       | 82562EZ 10/100 Ethernet C... | 46    |
| pci:14e4-16a3 | Broadcom    | NetXtreme BCM57786 Gigabi... | 45    |
| pci:14e4-164c | Broadcom... | NetXtreme II BCM5708 Giga... | 41    |
| pci:14e4-163b | Broadcom    | NetXtreme II BCM5716 Giga... | 40    |
| pci:1d6a-11b1 | Aquantia    | AQC111 NBase-T/IEEE 802.3... | 40    |
| pci:8086-100e | Intel       | 82540EM Gigabit Ethernet ... | 37    |
| pci:8086-10bc | Intel       | 82571EB/82571GB Gigabit E... | 35    |
| pci:8086-15f9 | Intel       | Ethernet Connection (14) ... | 35    |
| pci:1186-4b01 | D-Link S... | DGE-530T Gigabit Ethernet... | 34    |
| pci:8086-1064 | Intel       | 82562ET/EZ/GT/GZ - PRO/10... | 34    |
| pci:8086-37d2 | Intel       | Ethernet Connection X722 ... | 34    |
| pci:14e4-1659 | Broadcom... | NetXtreme BCM5721 Gigabit... | 33    |
| pci:14e4-16fd | Broadcom... | NetXtreme BCM5753M Gigabi... | 33    |
| pci:8086-1076 | Intel       | 82541GI Gigabit Ethernet ... | 32    |
| pci:8086-15d6 | Intel       | Ethernet Connection (5) I... | 32    |
| pci:8086-108c | Intel       | 82573E Gigabit Ethernet C... | 31    |
| pci:8086-3101 | Intel       | Ethernet controller          | 31    |
| pci:8086-37d1 | Intel       | Ethernet Connection X722 ... | 30    |
| pci:10de-0d7d | Nvidia      | MCP89 Ethernet               | 28    |
| pci:14e4-1690 | Broadcom... | NetXtreme BCM57760 Gigabi... | 28    |
| pci:14e4-168e | Broadcom    | NetXtreme II BCM57810 10 ... | 27    |
| pci:14e4-169a | Broadcom    | NetLink BCM5786 Gigabit E... | 27    |
| pci:14e4-169d | Broadcom... | NetLink BCM5789 Gigabit E... | 27    |
| pci:8086-1572 | Intel       | Ethernet Controller X710 ... | 27    |
| pci:11ab-4352 | Marvell ... | 88E8038 PCI-E Fast Ethern... | 24    |
| pci:1317-0985 | ADMtek      | NC100 Network Everywhere ... | 22    |
| pci:14e4-1678 | Broadcom    | NetXtreme BCM5715 Gigabit... | 22    |
| pci:14e4-1674 | Broadcom    | NetXtreme BCM5756ME Gigab... | 21    |
| pci:14e4-16d8 | Broadcom... | BCM57416 NetXtreme-E Dual... | 19    |
| pci:14e4-16b0 | Broadcom    | NetXtreme BCM57761 Gigabi... | 18    |
| pci:8086-15f2 | Intel       | Ethernet Controller I225-LM  | 18    |
| pci:8086-107d | Intel       | 82572EI Gigabit Ethernet ... | 17    |
| pci:10b9-5263 | ULi Elec... | ULi 1689,1573 integrated ... | 16    |
| pci:10de-0066 | Nvidia      | nForce2 Ethernet Controller  | 16    |
| pci:10ec-8162 | Realtek ... | Realtek Ethernet controller  | 16    |
| pci:8086-1019 | Intel       | 82547EI Gigabit Ethernet ... | 16    |
| pci:8086-101e | Intel       | 82540EP Gigabit Ethernet ... | 16    |
| pci:10b7-1700 | 3Com        | 3c940 10/100/1000Base-T [... | 15    |
| pci:14e4-1696 | Broadcom... | NetXtreme BCM5782 Gigabit... | 15    |
| pci:8086-150e | Intel       | 82580 Gigabit Network Con... | 15    |
| pci:1113-1211 | Accton T... | SMC2-1211TX                  | 14    |
| pci:8086-1010 | Intel       | 82546EB Gigabit Ethernet ... | 14    |
| pci:8086-37cc | Intel       | Ethernet Connection X722     | 13    |
| pci:8086-1079 | Intel       | 82546GB Gigabit Ethernet ... | 12    |
| pci:8086-3100 | Intel       | Ethernet controller          | 12    |
| pci:100b-0020 | National... | DP83815 (MacPhyter) Ether... | 11    |
| pci:1d6a-94c0 | Aquantia    | Ethernet controller          | 11    |
| pci:8086-10b9 | Intel       | 82572EI Gigabit Ethernet ... | 11    |
| pci:8086-1557 | Intel       | 82599 10 Gigabit Network ... | 11    |
| pci:11ab-4360 | Marvell ... | 88E8052 PCI-E ASF Gigabit... | 10    |
| pci:1106-3119 | VIA Tech... | VT6120/VT6121/VT6122 Giga... | 9     |
| pci:11c1-ed00 | LSI         | ET-131x PCI-E Ethernet Co... | 9     |
| pci:1282-9102 | Davicom ... | DM9102 Fast Ethernet Cont... | 9     |
| pci:14e4-165d | Broadcom    | NetXtreme BCM5705M Gigabi... | 9     |
| pci:8086-1031 | Intel       | 82801CAM (ICH3) PRO/100 V... | 9     |
| pci:8086-103d | Intel       | 82801DB PRO/100 VE (MOB) ... | 9     |
| pci:1039-0190 | Silicon ... | 190 Ethernet Adapter         | 8     |
| pci:1d6a-d108 | Aquantia    | AQC108 NBase-T/IEEE 802.3... | 8     |
| pci:1fc9-4027 | Tehuti N... | TN9710P 10GBase-T/NBASE-T... | 8     |
| pci:8086-108b | Intel       | 82573V Gigabit Ethernet C... | 8     |
| pci:8086-1f41 | Intel       | Ethernet Connection I354     | 8     |
| pci:1186-4c00 | D-Link S... | Gigabit Ethernet Adapter     | 7     |
| pci:11ab-4361 | Marvell ... | 88E8050 PCI-E ASF Gigabit... | 7     |
| pci:11ab-4365 | Marvell ... | 88E8070 based Ethernet Co... | 7     |
| pci:13f0-1023 | Sundance... | IP1000 Family Gigabit Eth... | 7     |
| pci:14e4-1672 | Broadcom    | NetXtreme BCM5754M Gigabi... | 7     |
| pci:14e4-168a | Broadcom... | NetXtreme II BCM57800 1/1... | 7     |
| pci:19e5-a222 | Huawei T... | HNS GE/10GE/25GE RDMA Net... | 7     |
| pci:8086-1039 | Intel       | 82801DB PRO/100 VE (LOM) ... | 7     |
| pci:8086-15ac | Intel       | Ethernet Connection X552 ... | 7     |
| pci:8086-15ad | Intel       | Ethernet Connection X552/... | 7     |
| pci:8086-37d0 | Intel       | Ethernet Connection X722 ... | 7     |
| pci:14e4-1654 | Broadcom    | NetXtreme BCM5705_2 Gigab... | 6     |
| pci:14e4-165e | Broadcom    | NetXtreme BCM5705M_2 Giga... | 6     |
| pci:1924-0803 | Solarfla... | SFC9020 10G Ethernet Cont... | 6     |
| pci:1d6a-00b1 | Aquantia    | AQC100 10G Ethernet MAC c... | 6     |
| pci:1022-2000 | AMD         | 79c970 [PCnet32 LANCE]       | 5     |
| pci:1113-1216 | Accton T... | EN-1216 Ethernet Adapter     | 5     |
| pci:168c-abcd | Qualcomm... | Osprey Emulation Wireless... | 5     |
| pci:1904-8139 | Hangzhou... | RTL8139D [Realtek] PCI 10... | 5     |
| pci:19e5-a221 | Huawei T... | HNS GE/10GE/25GE Network ... | 5     |
| pci:1d6a-80b1 | Aquantia    | Ethernet controller          | 5     |
| pci:8086-1026 | Intel       | 82545GM Gigabit Ethernet ... | 5     |
| pci:8086-103b | Intel       | 82801DB PRO/100 VM (LOM) ... | 5     |
| pci:8086-154d | Intel       | Ethernet 10G 2P X520 Adapter | 5     |
| pci:8086-158b | Intel       | Ethernet Controller XXV71... | 5     |
| pci:8086-15e4 | Intel       | Ethernet Connection X553 ... | 5     |
| pci:8086-15e5 | Intel       | Ethernet Connection X553 ... | 5     |
| pci:8086-1a1d | Intel       | Ethernet Connection (17) ... | 5     |
| pci:10b7-9202 | 3Com        | 3C920B-EMB-WNM Integrated... | 4     |
| pci:1106-3043 | VIA Tech... | VT86C100A [Rhine]            | 4     |
| pci:1148-4320 | SysKonnect  | SK-98xx V2.0 Gigabit Ethe... | 4     |
| pci:14e4-1601 | Broadcom... | NetXtreme BCM5752M Gigabi... | 4     |
| pci:14e4-164a | Broadcom    | NetXtreme II BCM5706 Giga... | 4     |
| pci:1d6a-0001 | Aquantia    | AQC107 NBase-T/IEEE 802.3... | 4     |
| pci:1d6a-87b1 | Aquantia    | AQC107 NBase-T/IEEE 802.3... | 4     |
| pci:8086-10f8 | Intel       | 82599 10 Gigabit Dual Por... | 4     |
| pci:8086-2449 | Intel       | 82801BA/BAM/CA/CAM Ethern... | 4     |
| pci:10de-0372 | Nvidia      | MCP55 Ethernet               | 3     |
| pci:10ec-8129 | Realtek ... | RTL-8129                     | 3     |
| pci:1186-1002 | D-Link S... | DL10050 Sundance Ethernet    | 3     |
| pci:1186-4200 | D-Link S... | DFE-520TX Fast Ethernet P... | 3     |
| pci:14e4-1653 | Broadcom... | NetXtreme BCM5705 Gigabit... | 3     |
| pci:14e4-1655 | Broadcom    | NetXtreme BCM5717 Gigabit... | 3     |
| pci:14e4-166a | Broadcom    | NetXtreme BCM5780 Gigabit... | 3     |
| pci:14e4-16a1 | Broadcom    | BCM57840 NetXtreme II 10 ... | 3     |
| pci:14e4-16a7 | Broadcom    | NetXtreme BCM5703X Gigabi... | 3     |
| pci:8086-1075 | Intel       | 82547GI Gigabit Ethernet ... | 3     |
| pci:8086-154c | Intel       | Ethernet Virtual Function... | 3     |
| pci:1011-0009 | Digital ... | DECchip 21140 [FasterNet]    | 2     |
| pci:10b8-0005 | Standard... | 83c170 EPIC/100 Fast Ethe... | 2     |
| pci:1186-4302 | D-Link S... | DGE-530T Gigabit Ethernet... | 2     |
| pci:11ab-4343 | Marvell ... | 88E8062 PCI-E IPMI Gigabi... | 2     |
| pci:14e4-1648 | Broadcom    | NetXtreme BCM5704 Gigabit... | 2     |
| pci:14e4-1694 | Broadcom    | NetLink BCM57790 Gigabit ... | 2     |
| pci:14e4-16d6 | Broadcom    | BCM57412 NetXtreme-E 10Gb... | 2     |
| pci:168c-ff1a | Qualcomm... | Ethernet controller          | 2     |
| pci:1924-0903 | Solarfla... | SFC9120 10G Ethernet Cont... | 2     |
| pci:19e5-1822 | Huawei T... | Hi1822 Family (4*25GE)       | 2     |
| pci:1a47-0003 | 3DSP        | WLAN and Bluetooth Card      | 2     |
| pci:8086-1013 | Intel       | 82541EI Gigabit Ethernet ... | 2     |
| pci:8086-1077 | Intel       | 82541GI Gigabit Ethernet ... | 2     |
| pci:8086-108a | Intel       | 82546GB Gigabit Ethernet ... | 2     |
| pci:8086-10a4 | Intel       | 82571EB Gigabit Ethernet ... | 2     |
| pci:8086-10ed | Intel       | 82599 Ethernet Controller... | 2     |
| pci:8086-1516 | Intel       | 82580 Gigabit Network Con... | 2     |
| pci:8086-151c | Intel       | 82599 10 Gigabit TN Netwo... | 2     |
| pci:8086-1583 | Intel       | Ethernet Controller XL710... | 2     |
| pci:000c-0000 | Unknown     | Ethernet controller          | 1     |
| pci:0014-7a03 | Loongson... | Gigabit Ethernet Controller  | 1     |
| pci:1077-3022 | QLogic      | ISP4022-based Ethernet NIC   | 1     |
| pci:1077-3032 | QLogic      | ISP4032-based Ethernet IP... | 1     |
| pci:1077-8070 | QLogic      | FastLinQ QL41000 Series 1... | 1     |
| pci:10b7-5257 | 3Com        | 3cCFE575CT CardBus [Cyclone] | 1     |
| pci:10b7-9005 | 3Com        | 3c900B-Combo Etherlink XL... | 1     |
| pci:10de-00d6 | Nvidia      | nForce3 Ethernet             | 1     |
| pci:10ec-0139 | Realtek ... | RTL-8139/8139C/8139C+ Eth... | 1     |
| pci:10ec-8119 | Realtek ... | Realtek Ethernet controller  | 1     |
| pci:10ec-8131 | Realtek ... | RTL8131 PCIe Fast Etherne... | 1     |
| pci:10ec-8138 | Realtek ... | RT8139 (B/C) Cardbus Fast... | 1     |
| pci:1137-0043 | Cisco Sy... | VIC Ethernet NIC             | 1     |
| pci:1137-0044 | Cisco Sy... | VIC Ethernet NIC Dynamic     | 1     |
| pci:1186-4000 | D-Link S... | DL2000-based Gigabit Ethe... | 1     |
| pci:1186-4b00 | D-Link S... | DGE-560T PCI Express Giga... | 1     |
| pci:11ab-4370 | Marvell ... | 88E8075 PCI-E Gigabit Eth... | 1     |
| pci:12ae-0003 | Alteon N... | Ethernet controller          | 1     |
| pci:1317-0185 | ADMtek      | Ethernet controller          | 1     |
| pci:1374-0038 | Silicom     | Quad port Copper Ethernet... | 1     |
| pci:1425-0036 | Chelsio ... | S320-LP-CR 10GbE Dual Por... | 1     |
| pci:14e4-163a | Broadcom    | NetXtreme II BCM5709S Gig... | 1     |
| pci:14e4-1650 | Broadcom    | NetXtreme II BCM57711E 10... | 1     |
| pci:14e4-1656 | Broadcom    | NetXtreme BCM5718 Gigabit... | 1     |
| pci:14e4-1665 | Broadcom    | NetXtreme BCM5717 Gigabit... | 1     |
| pci:14e4-167e | Broadcom    | NetXtreme BCM5751F Fast E... | 1     |
| pci:14e4-16a2 | Broadcom    | BCM57840 NetXtreme II 10/... | 1     |
| pci:14e4-16d7 | Broadcom    | BCM57414 NetXtreme-E 10Gb... | 1     |
| pci:14e4-16f7 | Broadcom    | NetXtreme BCM5753 Gigabit... | 1     |
| pci:14e4-52a3 | Broadcom... | Ethernet controller          | 1     |
| pci:14e4-73fd | Broadcom    | Ethernet controller          | 1     |
| pci:14e4-8470 | Broadcom    | Ethernet controller          | 1     |
| pci:14e4-b844 | Broadcom    | Ethernet controller          | 1     |
| pci:1516-0803 | MYSON Te... | SURECOM EP-320X-S 100/10M... | 1     |
| pci:15b3-1004 | Mellanox... | MT27500/MT27520 Family [C... | 1     |
| pci:15b3-1019 | Mellanox... | MT28800 Family [ConnectX-... | 1     |
| pci:15b3-101d | Mellanox... | MT2892 Family [ConnectX-6... | 1     |
| pci:16ec-0116 | U.S. Rob... | USR997902 10/100/1000 Mbp... | 1     |
| pci:1904-2031 | Hangzhou... | SC92031 PCI Fast Ethernet... | 1     |
| pci:1d6a-08b1 | Aquantia    | AQC108 NBase-T/IEEE 802.3... | 1     |
| pci:1fc9-4022 | Tehuti N... | TN9310 10GbE SFP+ Etherne... | 1     |
| pci:1fff-8016 | MCST        | Gigabit Ethernet Controller  | 1     |
| pci:8086-0d53 | Intel       | Ethernet Connection (12) ... | 1     |
| pci:8086-1008 | Intel       | 82544EI Gigabit Ethernet ... | 1     |
| pci:8086-100d | Intel       | 82544GC Gigabit Ethernet ... | 1     |
| pci:8086-100f | Intel       | 82545EM Gigabit Ethernet ... | 1     |
| pci:8086-1016 | Intel       | 82540EP Gigabit Ethernet ... | 1     |
| pci:8086-103a | Intel       | 82801DB PRO/100 VE (CNR) ... | 1     |
| pci:8086-103e | Intel       | 82801DB PRO/100 VM (MOB) ... | 1     |
| pci:8086-1065 | Intel       | 82562ET/EZ/GT/GZ - PRO/10... | 1     |
| pci:8086-1069 | Intel       | 82562EM/EX/GX - PRO/100 V... | 1     |
| pci:8086-10aa | Intel       | Ethernet controller          | 1     |
| pci:8086-10e6 | Intel       | 82576 Gigabit Network Con... | 1     |
| pci:8086-1520 | Intel       | I350 Ethernet Controller ... | 1     |
| pci:8086-1536 | Intel       | I210 Gigabit Fiber Networ... | 1     |
| pci:8086-154b | Intel       | Ethernet controller          | 1     |
| pci:8086-1560 | Intel       | Ethernet Controller X540     | 1     |
| pci:8086-1589 | Intel       | Ethernet Controller X710/... | 1     |
| pci:8086-159b | Intel       | Ethernet Controller E810-... | 1     |
| pci:8086-15c4 | Intel       | Ethernet Connection X553 ... | 1     |
| pci:8086-15ff | Intel       | Ethernet Controller X710 ... | 1     |
| pci:8086-1a1e | Intel       | Ethernet Connection (16) ... | 1     |
| pci:8086-1f45 | Intel       | Ethernet Connection I354 ... | 1     |
| pci:8086-37cd | Intel       | Ethernet Virtual Function... | 1     |
| pci:8086-37d3 | Intel       | Ethernet Connection X722 ... | 1     |
| pci:8086-43a2 | Intel       | Ethernet controller          | 1     |
| pci:8086-43ac | Intel       | 500 Series Chipset Family... | 1     |
| pci:8086-5502 | Intel       | Ethernet Controller (2) I... | 1     |

### Net/other (PCI)

Total devices: 18283

| ID            | MFG         | Name                         | Count |
|---------------|-------------|------------------------------|-------|
| pci:8086-1502 | Intel       | 82579LM Gigabit Network C... | 4751  |
| pci:8086-1539 | Intel       | I211 Gigabit Network Conn... | 2763  |
| pci:10de-03ef | Nvidia      | MCP61 Ethernet               | 1353  |
| pci:8086-1503 | Intel       | 82579V Gigabit Network Co... | 1326  |
| pci:8086-10ea | Intel       | 82577LM Gigabit Network C... | 971   |
| pci:8086-10de | Intel       | 82567LM-3 Gigabit Network... | 720   |
| pci:8086-10f5 | Intel       | 82567LM Gigabit Network C... | 681   |
| pci:8086-10d3 | Intel       | 82574L Gigabit Network Co... | 584   |
| pci:8086-1533 | Intel       | I210 Gigabit Network Conn... | 537   |
| pci:14e4-170c | Broadcom... | BCM4401-B0 100Base-TX        | 408   |
| pci:8086-10bd | Intel       | 82566DM-2 Gigabit Network... | 377   |
| pci:1106-3065 | VIA Tech... | VT6102/VT6103 [Rhine-II]     | 333   |
| pci:8086-1521 | Intel       | I350 Gigabit Network Conn... | 264   |
| pci:8086-1049 | Intel       | 82566MM Gigabit Network C... | 261   |
| pci:10de-0269 | Nvidia      | MCP51 Ethernet Controller    | 246   |
| pci:8086-10ef | Intel       | 82578DM Gigabit Network C... | 214   |
| pci:10de-0373 | Nvidia      | MCP55 Ethernet               | 199   |
| pci:10de-0057 | Nvidia      | CK804 Ethernet Controller    | 178   |
| pci:8086-10f0 | Intel       | 82578DC Gigabit Network C... | 177   |
| pci:8086-10c0 | Intel       | 82562V-2 10/100 Network C... | 138   |
| pci:8086-10ce | Intel       | 82567V-2 Gigabit Network ... | 116   |
| pci:8086-1092 | Intel       | PRO/100 VE Network Connec... | 115   |
| pci:8086-10eb | Intel       | 82577LC Gigabit Network C... | 110   |
| pci:8086-27dc | Intel       | NM10/ICH7 Family LAN Cont... | 109   |
| pci:8086-10c9 | Intel       | 82576 Gigabit Network Con... | 105   |
| pci:8086-294c | Intel       | 82566DC-2 Gigabit Network... | 105   |
| pci:8086-104a | Intel       | 82566DM Gigabit Network C... | 102   |
| pci:8086-150c | Intel       | 82583V Gigabit Network Co... | 76    |
| pci:8086-10c4 | Intel       | 82562GT 10/100 Network Co... | 75    |
| pci:8086-10bf | Intel       | 82567LF Gigabit Network C... | 65    |
| pci:8086-104b | Intel       | 82566DC Gigabit Network C... | 62    |
| pci:8086-10f6 | Intel       | 82574L Gigabit Network Co... | 49    |
| pci:8086-10df | Intel       | 82567LF-3 Gigabit Network... | 48    |
| pci:8086-157b | Intel       | I210 Gigabit Network Conn... | 47    |
| pci:10b7-9200 | 3Com        | 3c905C-TX/TX-M [Tornado]     | 45    |
| pci:8086-10cd | Intel       | 82567LF-2 Gigabit Network... | 42    |
| pci:10de-00df | Nvidia      | CK8S Ethernet Controller     | 34    |
| pci:8086-10a7 | Intel       | 82575EB Gigabit Network C... | 33    |
| pci:10b7-9055 | 3Com        | 3c905B 100BaseTX [Cyclone]   | 32    |
| pci:15b3-1003 | Mellanox... | MT27500 Family [ConnectX-3]  | 31    |
| pci:8086-104c | Intel       | 82562V 10/100 Network Con... | 28    |
| pci:8086-1094 | Intel       | PRO/100 VE Network Connec... | 26    |
| pci:14e4-4401 | Broadcom... | BCM4401 100Base-T            | 25    |
| pci:15b3-6750 | Mellanox... | MT26448 [ConnectX EN 10Gi... | 24    |
| pci:1077-8020 | QLogic      | cLOM8214 1/10GbE Controller  | 16    |
| pci:8086-104d | Intel       | 82566MC Gigabit Network C... | 16    |
| pci:8086-10cc | Intel       | 82567LM-2 Gigabit Network... | 15    |
| pci:4040-0100 | NetXen I... | NX3031 Multifunction 1/10... | 12    |
| pci:8086-10cb | Intel       | 82567V Gigabit Network Co... | 12    |
| pci:8086-1525 | Intel       | 82567V-4 Gigabit Network ... | 12    |
| pci:10ec-8029 | Realtek ... | RTL-8029(AS)                 | 11    |
| pci:15b3-673c | Mellanox... | MT25408A0-FCC-QI ConnectX... | 11    |
| pci:8086-10e8 | Intel       | 82576 Gigabit Network Con... | 11    |
| pci:10b7-9050 | 3Com        | 3c905 100BaseTX [Boomerang]  | 9     |
| pci:15b3-1013 | Mellanox... | MT27700 Family [ConnectX-4]  | 8     |
| pci:8086-1093 | Intel       | PRO/100 VM Network Connec... | 8     |
| pci:10ee-2014 | Xilinx      | Network controller           | 7     |
| pci:1260-3890 | Intersil    | ISL3890 [Prism GT/Prism D... | 7     |
| pci:19a2-0700 | Emulex      | OneConnect OCe10100/OCe10... | 7     |
| pci:19a2-0710 | Emulex      | OneConnect 10Gb NIC (be3)    | 7     |
| pci:8086-10fe | Intel       | 82552 10/100 Network Conn... | 7     |
| pci:15b3-1015 | Mellanox... | MT27710 Family [ConnectX-... | 6     |
| pci:106b-0032 | Apple       | UniNorth 2 GMAC (Sun GEM)    | 5     |
| pci:14e4-5fa0 | Broadcom    | Network controller           | 5     |
| pci:15b3-1007 | Mellanox... | MT27520 Family [ConnectX-... | 5     |
| pci:10df-0720 | Emulex      | OneConnect NIC (Skyhawk)     | 4     |
| pci:1106-3053 | VIA Tech... | VT6105M [Rhine-III]          | 4     |
| pci:14e4-164f | Broadcom    | NetXtreme II BCM57711 10-... | 4     |
| pci:8086-1531 | Intel       | I210 Gigabit Unprogrammed    | 4     |
| pci:1737-1032 | Linksys     | Gigabit Network Adapter      | 3     |
| pci:8086-10d6 | Intel       | 82575GB Gigabit Network C... | 3     |
| pci:001c-0008 | PEAK-Sys... | Network controller           | 2     |
| pci:1077-7322 | QLogic      | IBA7322 QDR InfiniBand HCA   | 2     |
| pci:10b7-7646 | 3Com        | 3cSOHO100-TX Hurricane       | 2     |
| pci:10b7-9300 | 3Com        | 3CSOHO100B-TX 910-A01 [tu... | 2     |
| pci:1106-1106 | VIA Tech... | VT82C570MV                   | 2     |
| pci:11ad-0002 | Lite-On ... | LNE100TX                     | 2     |
| pci:11ad-c115 | Lite-On ... | LNE100TX [Linksys EtherFa... | 2     |
| pci:11f6-1401 | Compex      | ReadyLink 2000               | 2     |
| pci:1260-3886 | Intersil    | ISL3886 [Prism Javelin/Pr... | 2     |
| pci:1425-0031 | Chelsio ... | T320 10GbE Dual Port Adapter | 2     |
| pci:15b3-1017 | Mellanox... | MT27800 Family [ConnectX-5]  | 2     |
| pci:17cb-1103 | Qualcomm    | Atheros QCNFA765             | 2     |
| pci:1db3-2355 |             | Network controller           | 2     |
| pci:8086-1051 | Intel       | 82801EB/ER (ICH5/ICH5R) i... | 2     |
| pci:8086-1091 | Intel       | PRO/100 VM Network Connec... | 2     |
| pci:001c-0001 | PEAK-Sys... | PCAN-PCI CAN-Bus controller  | 1     |
| pci:001c-0003 | PEAK-Sys... | Network controller           | 1     |
| pci:001c-0018 | PEAK-Sys... | Network controller           | 1     |
| pci:03d0-2103 | Unknown     | Network controller           | 1     |
| pci:068c-0023 | Unknown     | Network controller           | 1     |
| pci:0814-0701 | Unknown     | Network controller           | 1     |
| pci:1006-3106 | Reply Group | Reply Ethernet controller    | 1     |
| pci:1014      | IBM         | IBM                          | 1     |
| pci:1014-0201 | IBM         | Network controller           | 1     |
| pci:1014-0302 | IBM         | Winnipeg PCI-X Host Bridge   | 1     |
| pci:1022-2001 | AMD         | Am79C978 PCnet Home (Home... | 1     |
| pci:104a-0500 | STMicroe... | ST70137 [Unicorn] ADSL DM... | 1     |
| pci:106b-0021 | Apple       | UniNorth GMAC (Sun GEM)      | 1     |
| pci:106b-004c | Apple       | K2 GMAC (Sun GEM)            | 1     |
| pci:106b-0051 | Apple       | Shasta (Sun GEM)             | 1     |
| pci:1077-4022 | QLogic      | ISP4022-based iSCSI TOE HBA  | 1     |
| pci:1077-4032 | QLogic      | ISP4032-based iSCSI TOE I... | 1     |
| pci:10b5-9712 | PLX Tech... | Network controller           | 1     |
| pci:10b7-6056 | 3Com        | 3c556B CardBus [Tornado]     | 1     |
| pci:10b7-9000 | 3Com        | 3c900 10BaseT [Boomerang]    | 1     |
| pci:10b7-9004 | 3Com        | 3c900B-TPO Etherlink XL [... | 1     |
| pci:10b7-9805 | 3Com        | 3c980-C 10/100baseTX NIC ... | 1     |
| pci:10d9-0531 | Macronix... | MX987x5                      | 1     |
| pci:10de-008c | Nvidia      | MCP2A Ethernet Controller    | 1     |
| pci:10ee-1004 | Xilinx      | Network controller           | 1     |
| pci:1106-3102 | VIA Tech... | VT8662 Host Bridge           | 1     |
| pci:1106-a409 | VIA Tech... | VX855/VX875/VX900 Series ... | 1     |
| pci:110a-3141 | Siemens     | SIMATIC NET CP 5611 / 5621   | 1     |
| pci:12d0-2103 | GDE Systems | GDE Network controller       | 1     |
| pci:148c-002d | Tul Corp... | Network controller           | 1     |
| pci:14e4-b850 | Broadcom    | BCM56850 Switch ASIC         | 1     |
| pci:14f3-2030 | BroadLogic  | 2030 DVB-S Satellite Rece... | 1     |
| pci:15b3-5a44 | Mellanox... | MT23108 InfiniHost           | 1     |
| pci:15b3-6274 | Mellanox... | MT25204 [InfiniHost III L... | 1     |
| pci:15b3-6278 | Mellanox... | MT25208 InfiniHost III Ex... | 1     |
| pci:168c-0028 | Qualcomm... | 11n AR9160 Anwi Diagnosti... | 1     |
| pci:168c-004a | Qualcomm... | Network controller           | 1     |
| pci:168c-0063 | Qualcomm... | Network controller           | 1     |
| pci:1804-5360 | Ralink      | Network controller           | 1     |
| pci:1810-3060 | HCL Tech... | Network controller           | 1     |
| pci:1923-0040 | Sangoma ... | A200/Remora FXO/FXS Analo... | 1     |
| pci:1931-000c | Option N.V. | Qualcomm MSM6275 UMTS chip   | 1     |
| pci:19e5-0206 | Huawei T... | Hi1822 Family (2*25GE)       | 1     |
| pci:8086-0436 | Intel       | DH8900CC Null Device         | 1     |
| pci:8086-10c6 | Intel       | 82598EB 10-Gigabit AF Dua... | 1     |
| pci:8086-10ca | Intel       | 82576 Virtual Function       | 1     |
| pci:8086-1526 | Intel       | 82576 Gigabit Network Con... | 1     |
| pci:d161-8002 | Digium      | Wildcard AEX800 8-port an... | 1     |
| pci:d161-8005 | Digium      | Wildcard TDM410 4-port an... | 1     |

### Net/wireless (PCI)

Total devices: 88417

| ID            | MFG         | Name                         | Count |
|---------------|-------------|------------------------------|-------|
| pci:8086-2723 | Intel       | Wi-Fi 6 AX200                | 4456  |
| pci:168c-002b | Qualcomm... | AR9285 Wireless Network A... | 4421  |
| pci:168c-0032 | Qualcomm... | AR9485 Wireless Network A... | 3867  |
| pci:168c-0042 | Qualcomm... | QCA9377 802.11ac Wireless... | 3708  |
| pci:168c-0036 | Qualcomm... | QCA9565 / AR9565 Wireless... | 3474  |
| pci:8086-24fd | Intel       | Wireless 8265 / 8275         | 3141  |
| pci:14e4-4727 | Broadcom    | BCM4313 802.11bgn Wireles... | 2445  |
| pci:10ec-c821 | Realtek ... | RTL8821CE 802.11ac PCIe W... | 2124  |
| pci:8086-095a | Intel       | Wireless 7265                | 2030  |
| pci:168c-003e | Qualcomm... | QCA6174 802.11ac Wireless... | 1971  |
| pci:10ec-b723 | Realtek ... | RTL8723BE PCIe Wireless N... | 1860  |
| pci:8086-24f3 | Intel       | Wireless 8260                | 1837  |
| pci:8086-a370 | Intel       | Cannon Lake PCH CNVi WiFi    | 1800  |
| pci:8086-08b1 | Intel       | Wireless 7260                | 1749  |
| pci:8086-3165 | Intel       | Wireless 3165                | 1684  |
| pci:8086-9df0 | Intel       | Cannon Point-LP CNVi [Wir... | 1577  |
| pci:14e4-4365 | Broadcom    | BCM43142 802.11b/g/n         | 1475  |
| pci:8086-24fb | Intel       | Dual Band Wireless-AC 316... | 1437  |
| pci:8086-a0f0 | Intel       | Wi-Fi 6 AX201                | 1411  |
| pci:8086-02f0 | Intel       | Comet Lake PCH-LP CNVi WiFi  | 1381  |
| pci:168c-001c | Qualcomm... | AR242x / AR542x Wireless ... | 1373  |
| pci:8086-0085 | Intel       | Centrino Advanced-N 6205 ... | 1220  |
| pci:10ec-c822 | Realtek ... | RTL8822CE 802.11ac PCIe W... | 1186  |
| pci:8086-4222 | Intel       | PRO/Wireless 3945ABG [Gol... | 1173  |
| pci:8086-2526 | Intel       | Wireless-AC 9260             | 1164  |
| pci:10ec-8176 | Realtek ... | RTL8188CE 802.11b/g/n WiF... | 1135  |
| pci:14e4-4315 | Broadcom    | BCM4312 802.11b/g LP-PHY     | 1118  |
| pci:10ec-b822 | Realtek ... | RTL8822BE 802.11a/b/g/n/a... | 1075  |
| pci:168c-0034 | Qualcomm... | AR9462 Wireless Network A... | 987   |
| pci:8086-06f0 | Intel       | Comet Lake PCH CNVi WiFi     | 953   |
| pci:8086-4232 | Intel       | WiFi Link 5100               | 897   |
| pci:14e4-43a0 | Broadcom... | BCM4360 802.11ac Wireless... | 879   |
| pci:8086-3166 | Intel       | Dual Band Wireless-AC 316... | 842   |
| pci:8086-08b2 | Intel       | Wireless 7260                | 824   |
| pci:168c-002e | Qualcomm... | AR9287 Wireless Network A... | 820   |
| pci:1814-3290 | Ralink      | RT3290 Wireless 802.11n 1... | 817   |
| pci:8086-08b3 | Intel       | Wireless 3160                | 784   |
| pci:10ec-8179 | Realtek ... | RTL8188EE Wireless Networ... | 775   |
| pci:8086-0082 | Intel       | Centrino Advanced-N 6205 ... | 728   |
| pci:168c-002a | Qualcomm... | AR928X Wireless Network A... | 720   |
| pci:10ec-d723 | Realtek ... | RTL8723DE Wireless Networ... | 688   |
| pci:8086-34f0 | Intel       | Ice Lake-LP PCH CNVi WiFi    | 627   |
| pci:8086-088e | Intel       | Centrino Advanced-N 6235     | 614   |
| pci:14e4-4359 | Broadcom    | BCM43228 802.11a/b/g/n       | 572   |
| pci:1814-3090 | Ralink      | RT3090 Wireless 802.11n 1... | 547   |
| pci:8086-4229 | Intel       | PRO/Wireless 4965 AG or A... | 537   |
| pci:8086-0887 | Intel       | Centrino Wireless-N 2230     | 530   |
| pci:10ec-8821 | Realtek ... | RTL8821AE 802.11ac PCIe W... | 516   |
| pci:14e4-4331 | Broadcom    | BCM4331 802.11a/b/g/n        | 516   |
| pci:8086-4237 | Intel       | PRO/Wireless 5100 AGN [Sh... | 457   |
| pci:14e4-432b | Broadcom    | BCM4322 802.11a/b/g/n Wir... | 434   |
| pci:8086-422b | Intel       | Centrino Ultimate-N 6300     | 430   |
| pci:10ec-8723 | Realtek ... | RTL8723AE PCIe Wireless N... | 415   |
| pci:8086-4239 | Intel       | Centrino Advanced-N 6200     | 414   |
| pci:168c-0030 | Qualcomm... | AR93xx Wireless Network A... | 404   |
| pci:10ec-8172 | Realtek ... | RTL8191SEvB Wireless LAN ... | 397   |
| pci:14e4-4311 | Broadcom    | BCM4311 802.11b/g WLAN       | 392   |
| pci:14e4-4353 | Broadcom... | BCM43224 802.11a/b/g/n       | 390   |
| pci:14e4-43b1 | Broadcom    | BCM4352 802.11ac Wireless... | 385   |
| pci:1814-5390 | Ralink      | RT5390 Wireless 802.11n 1... | 364   |
| pci:8086-4238 | Intel       | Centrino Ultimate-N 6300     | 364   |
| pci:14e4-4328 | Broadcom... | BCM4321 802.11a/b/g/n        | 350   |
| pci:8086-095b | Intel       | Wireless 7265                | 350   |
| pci:8086-422c | Intel       | Centrino Advanced-N 6200     | 335   |
| pci:8086-2725 | Intel       | Wi-Fi 6 AX210/AX211/AX411... | 319   |
| pci:8086-008a | Intel       | Centrino Wireless-N 1030 ... | 292   |
| pci:168c-002d | Qualcomm... | AR9227 Wireless Network A... | 285   |
| pci:8086-31dc | Intel       | Gemini Lake PCH CNVi WiFi    | 281   |
| pci:8086-0084 | Intel       | Centrino Wireless-N 1000 ... | 278   |
| pci:8086-7360 | Intel       | XMM7360 LTE Advanced Modem   | 276   |
| pci:14e4-4357 | Broadcom    | BCM43225 802.11b/g/n         | 275   |
| pci:8086-0896 | Intel       | Centrino Wireless-N 130      | 267   |
| pci:14c3-7961 | MEDIATEK    | MT7921 802.11ax PCI Expre... | 261   |
| pci:10ec-818b | Realtek ... | RTL8192EE PCIe Wireless N... | 255   |
| pci:8086-08b4 | Intel       | Wireless 3160                | 247   |
| pci:14e4-43ba | Broadcom    | BCM43602 802.11ac Wireles... | 244   |
| pci:10ec-8852 | Realtek ... | RTL8852AE 802.11ax PCIe W... | 241   |
| pci:11ab-2b38 | Marvell ... | 88W8897 [AVASTAR] 802.11a... | 237   |
| pci:8086-0083 | Intel       | Centrino Wireless-N 1000 ... | 201   |
| pci:14e4-4318 | Broadcom    | BCM4318 [AirForce One 54g... | 194   |
| pci:8086-43f0 | Intel       | Tiger Lake PCH CNVi WiFi     | 193   |
| pci:168c-001a | Qualcomm... | AR2413/AR2414 Wireless Ne... | 191   |
| pci:10ec-8178 | Realtek ... | RTL8192CE PCIe Wireless N... | 186   |
| pci:1814-0781 | Ralink      | RT2790 Wireless 802.11n 1... | 184   |
| pci:8086-08ae | Intel       | Centrino Wireless-N 100      | 182   |
| pci:168c-0013 | Qualcomm... | AR5212/5213/2414 Wireless... | 181   |
| pci:8086-0888 | Intel       | Centrino Wireless-N 2230     | 173   |
| pci:8086-4220 | Intel       | PRO/Wireless 2200BG [Cale... | 171   |
| pci:10ec-8812 | Realtek ... | RTL8812AE 802.11ac PCIe W... | 161   |
| pci:14e4-4358 | Broadcom    | BCM43227 802.11b/g/n         | 159   |
| pci:8086-0091 | Intel       | Centrino Advanced-N 6230 ... | 157   |
| pci:8086-4236 | Intel       | Ultimate N WiFi Link 5300    | 154   |
| pci:10ec-8171 | Realtek ... | RTL8191SEvA Wireless LAN ... | 149   |
| pci:8086-4235 | Intel       | Ultimate N WiFi Link 5300    | 148   |
| pci:1814-0301 | Ralink      | RT2561/RT61 802.11g PCI      | 137   |
| pci:14e4-4312 | Broadcom... | BCM4311 802.11a/b/g          | 132   |
| pci:8086-4227 | Intel       | PRO/Wireless 3945ABG [Gol... | 123   |
| pci:14c3-7630 | MEDIATEK    | MT7630e 802.11bgn Wireles... | 117   |
| pci:8086-4230 | Intel       | PRO/Wireless 4965 AG or A... | 114   |
| pci:1814-0302 | Ralink      | RT2561/RT61 rev B 802.11g    | 112   |
| pci:10ec-8185 | Realtek ... | RTL-8185 IEEE 802.11a/b/g... | 110   |
| pci:1814-3060 | Ralink      | RT3060 Wireless 802.11n 1... | 110   |
| pci:14e4-4464 | Broadcom    | BCM4364 802.11ac Wireless... | 107   |
| pci:1814-539b | Ralink      | RT5390R 802.11bgn PCIe Wi... | 102   |
| pci:14e4-43a3 | Broadcom    | BCM4350 802.11ac Wireless... | 93    |
| pci:8086-0087 | Intel       | Centrino Advanced-N + WiM... | 82    |
| pci:10ec-8199 | Realtek ... | RTL8187SE Wireless LAN Co... | 79    |
| pci:168c-0024 | Qualcomm... | AR5418 Wireless Network A... | 74    |
| pci:8086-008b | Intel       | Centrino Wireless-N 1030 ... | 74    |
| pci:8086-0891 | Intel       | Centrino Wireless-N 2200     | 71    |
| pci:17cb-1101 | Qualcomm    | QCA6390 Wireless Network ... | 66    |
| pci:8086-423c | Intel       | WiMAX/WiFi Link 5150         | 65    |
| pci:168c-0037 | Qualcomm... | AR9485 Wireless Network A... | 62    |
| pci:1814-5392 | Ralink      | RT5392 PCIe Wireless Netw... | 62    |
| pci:14e4-4320 | Broadcom    | BCM4306 802.11b/g Wireles... | 60    |
| pci:10ec-c82f | Realtek ... | RTL8822CE 802.11ac PCIe W... | 57    |
| pci:168c-0029 | Qualcomm... | AR922X Wireless Network A... | 56    |
| pci:1814-5360 | Ralink      | RT5360 Wireless 802.11n 1... | 54    |
| pci:1814-539f | Ralink      | RT5390 [802.11 b/g/n 1T1R... | 54    |
| pci:168c-0023 | Qualcomm... | AR5416 Wireless Network A... | 50    |
| pci:168c-001d | Qualcomm... | AR2417 Wireless Network A... | 48    |
| pci:8086-4df0 | Intel       | Wi-Fi 6 AX201 160MHz         | 48    |
| pci:1814-0601 | Ralink      | RT2800 802.11n PCI           | 47    |
| pci:8086-0885 | Intel       | Centrino Wireless-N 6150     | 46    |
| pci:8086-423d | Intel       | WiMAX/WiFi Link 5150         | 44    |
| pci:8086-0892 | Intel       | Centrino Wireless-N 135      | 42    |
| pci:8086-0893 | Intel       | Centrino Wireless-N 135      | 42    |
| pci:168c-002c | Qualcomm... | AR2427 802.11bg Wireless ... | 39    |
| pci:1814-3062 | Ralink      | RT3062 Wireless 802.11n 2... | 39    |
| pci:8086-093c | Intel       | Wireless Gigabit 17265       | 39    |
| pci:168c-001b | Qualcomm... | AR5413/AR5414 Wireless Ne... | 38    |
| pci:8086-0890 | Intel       | Centrino Wireless-N 2200     | 37    |
| pci:14e4-43c3 | Broadcom    | Network controller           | 35    |
| pci:8086-7af0 | Intel       | Alder Lake-S PCH CNVi WiFi   | 34    |
| pci:1814-0201 | Ralink      | RT2500 Wireless 802.11bg     | 29    |
| pci:168c-1014 | Qualcomm... | AR5212 802.11abg NIC         | 28    |
| pci:8086-0894 | Intel       | Centrino Wireless-N 105      | 28    |
| pci:168c-0041 | Qualcomm... | QCA6164 802.11ac Wireless... | 27    |
| pci:8086-088f | Intel       | Centrino Advanced-N 6235     | 27    |
| pci:1814-5592 | Ralink      | RT5592 PCIe Wireless Netw... | 26    |
| pci:1814-3092 | Ralink      | RT3092 Wireless 802.11n 2... | 25    |
| pci:8086-4223 | Intel       | PRO/Wireless 2915ABG [Cal... | 25    |
| pci:14e4-43ae | Broadcom    | BCM43162 802.11ac Wireles... | 24    |
| pci:1ae9-0310 | Wilocity    | Wil6200 802.11ad Wireless... | 24    |
| pci:10ec-8174 | Realtek ... | RTL8192SE Wireless LAN Co... | 23    |
| pci:10ec-a85a | Realtek ... | Realtek Network controller   | 23    |
| pci:11ab-1faa | Marvell ... | 88w8335 [Libertas] 802.11... | 23    |
| pci:8086-7560 | Intel       | Wireless controller          | 22    |
| pci:10ec-8190 | Realtek ... | RTL8190 802.11n PCI Wirel... | 21    |
| pci:14e4-43ec | Broadcom    | BCM4356 802.11ac Wireless... | 21    |
| pci:8086-0886 | Intel       | Centrino Wireless-N + WiM... | 20    |
| pci:1814-539a | Ralink      | WLAN controller              | 18    |
| pci:8086-0089 | Intel       | Centrino Advanced-N + WiM... | 18    |
| pci:14c3-0608 | MEDIATEK    | Network controller           | 17    |
| pci:1814-0701 | Ralink      | RT2760 Wireless 802.11n 1... | 15    |
| pci:8086-1043 | Intel       | PRO/Wireless LAN 2100 3B ... | 15    |
| pci:8086-0895 | Intel       | Centrino Wireless-N 105      | 14    |
| pci:104c-9066 | Texas In... | ACX 111 54Mbps Wireless I... | 12    |
| pci:1814-3592 | Ralink      | RT3592 Wireless 802.11abg... | 12    |
| pci:8086-4224 | Intel       | PRO/Wireless 2915ABG [Cal... | 12    |
| pci:14e4-4329 | Broadcom    | BCM4321 802.11b/g/n          | 11    |
| pci:14e4-0576 | Broadcom    | BCM43224 802.11a/b/g/n       | 10    |
| pci:14e4-4319 | Broadcom    | BCM4318 [AirForce 54g] 80... | 10    |
| pci:1814-0401 | Ralink      | RT2600 802.11 MIMO           | 10    |
| pci:10ec-8192 | Realtek ... | RTL8192E/RTL8192SE Wirele... | 9     |
| pci:168c-003c | Qualcomm... | QCA986x/988x 802.11ac Wir... | 9     |
| pci:14e4-43a9 | Broadcom    | BCM43217 802.11b/g/n         | 8     |
| pci:8086-0090 | Intel       | Centrino Advanced-N 6230 ... | 8     |
| pci:104c-8400 | Texas In... | ACX 100 22Mbps Wireless I... | 7     |
| pci:10ec-8813 | Realtek ... | RTL8813AE 802.11ac PCIe W... | 6     |
| pci:10ec-8180 | Realtek ... | RTL8180L 802.11b MAC         | 5     |
| pci:11ab-1fa6 | Marvell ... | Marvell W8300 802.11 Adapter | 5     |
| pci:14e4-4488 | Broadcom    | BCM4377b Wireless Network... | 5     |
| pci:8086-51f0 | Intel       | Alder Lake-P PCH CNVi WiFi   | 5     |
| pci:10ec-8191 | Realtek ... | RTL8192CE PCIe Wireless N... | 4     |
| pci:14e4-4324 | Broadcom    | BCM4309 802.11abg Wireles... | 4     |
| pci:1814-5362 | Ralink      | RT5362 PCI 802.11n Wirele... | 4     |
| pci:105b-e0ab | Foxconn ... | Wireless controller          | 3     |
| pci:10ec-b821 | Realtek ... | 8821CE Wireless LAN 802.1... | 3     |
| pci:11ab-2a08 | Marvell ... | 88W8362e [TopDog] 802.11a... | 3     |
| pci:1260-3873 | Intersil    | ISL3874 [Prism 2.5]/ISL38... | 3     |
| pci:14e4-441f | Broadcom    | BCM4361 802.11ac Dual-Ban... | 3     |
| pci:1799-700f | Belkin      | F5D7000 v7000 Wireless G ... | 3     |
| pci:1814-0300 | Ralink      | Wireless Adapter Canyon C... | 3     |
| pci:1050-0033 | Winbond ... | W89C33D 802.11 a/b/g BB/MAC  | 2     |
| pci:14e4-4301 | Broadcom    | BCM4301 802.11b Wireless ... | 2     |
| pci:14e4-43e9 | Broadcom    | BCM4358 802.11ac Wireless... | 2     |
| pci:14e4-4415 | Broadcom    | BCM4359 802.11ac Dual-Ban... | 2     |
| pci:168c-0033 | Qualcomm... | AR958x 802.11abgn Wireles... | 2     |
| pci:17fe-2220 | InProComm   | IPN 2220 802.11g             | 2     |
| pci:1814-0681 | Ralink      | RT2890 Wireless 802.11n PCIe | 2     |
| pci:1b4b-2b42 | Marvell ... | Marvell WLAN controller      | 2     |
| pci:03f0-0a6c | Unknown     | Wireless controller          | 1     |
| pci:105b-e0b0 | Foxconn ... | Wireless controller          | 1     |
| pci:10b7-0013 | 3Com        | AR5212 802.11abg NIC (3CR... | 1     |
| pci:11ab-1fa7 | Marvell ... | 88W8310 and 88W8000G [Lib... | 1     |
| pci:11ab-2a02 | Marvell ... | 88W8361 [TopDog] 802.11n ... | 1     |
| pci:1317-8201 | ADMtek      | ADM8211 802.11b Wireless ... | 1     |
| pci:14a4-4318 | Lite-On ... | BCM4318 [AirForce One 54g... | 1     |
| pci:14b9-a504 | Cisco Ai... | Cisco Aironet Wireless 80... | 1     |
| pci:14e4-4351 | Broadcom    | BCM43222 802.11abgn Wirel... | 1     |
| pci:14e4-43a2 | Broadcom    | BCM4360 802.11ac Wireless... | 1     |
| pci:14e4-440d | Broadcom    | 802.11ac Network Adapter     | 1     |
| pci:167b-2116 | ZyDAS Te... | ZD1212B Wireless Adapter     | 1     |
| pci:168c-0011 | Qualcomm... | AR5211 Wireless Network A... | 1     |
| pci:168c-0027 | Qualcomm... | AR9160 Wireless Network A... | 1     |
| pci:168c-ff1b | Qualcomm... | AR2425 Wireless Network A... | 1     |
| pci:168c-ff1d | Qualcomm... | AR922x Wireless Network A... | 1     |
| pci:1799-701f | Belkin      | F5D7010 v7000 Wireless G ... | 1     |
| pci:17cb-0001 | Qualcomm    | AGN100 802.11 a/b/g True ... | 1     |
| pci:1814-0101 | Ralink      | Wireless PCI Adapter RT24... | 1     |
| pci:1814-0200 | Ralink      | RT2500 802.11g PCI [PC54G2]  | 1     |
| pci:1814-3091 | Ralink      | RT3091 Wireless 802.11n 1... | 1     |
| pci:1ae9-0301 | Wilocity    | Wil6200 802.11ad Wireless... | 1     |

### Network and computing encryption device (PCI)

Total devices: 2

| ID            | MFG         | Name                         | Count |
|---------------|-------------|------------------------------|-------|
| pci:19e5-a255 | Huawei T... | HiSilicon SEC Engine         | 2     |

### Non-essential instrumentation (PCI)

Total devices: 13957

| ID            | MFG         | Name                         | Count |
|---------------|-------------|------------------------------|-------|
| pci:1022-1485 | AMD         | Starship/Matisse Reserved... | 3772  |
| pci:1022-148a | AMD         | Starship/Matisse PCIe Dum... | 3647  |
| pci:1022-145a | AMD         | Zeppelin/Raven/Raven2 PCI... | 3438  |
| pci:1022-1455 | AMD         | Zeppelin/Renoir PCIe Dumm... | 3026  |
| pci:8086-9d26 | Intel       | Skylake-U/Y Northpeak        | 33    |
| pci:8086-5a8e | Intel       | Non-Essential Instrumenta... | 18    |
| pci:8086-a126 | Intel       | 100 Series/C230 Series Ch... | 10    |
| pci:8086-318e | Intel       | Celeron/Pentium Silver Pr... | 9     |
| pci:8086-3456 | Intel       | Non-Essential Instrumenta... | 4     |

### Non-vga unclassified device (PCI)

Total devices: 2301

| ID            | MFG         | Name                         | Count |
|---------------|-------------|------------------------------|-------|
| pci:8086-9d35 | Intel       | Sunrise Point-LP Integrat... | 931   |
| pci:1022-15e4 | AMD         | Sensor Fusion Hub            | 476   |
| pci:1022-15e6 | AMD         | Raven/Raven2/Renoir Non-S... | 404   |
| pci:8086-22d8 | Intel       | Integrated Sensor Solution   | 154   |
| pci:8086-9d24 | Intel       | Skylake-U/Y SPI Controller   | 83    |
| pci:106b-1801 | Apple       | T2 Bridge Controller         | 81    |
| pci:106b-1802 | Apple       | T2 Secure Enclave Processor  | 81    |
| pci:8086-a135 | Intel       | 100 Series/C230 Series Ch... | 45    |
| pci:8086-a2a4 | Intel       | 200 Series/Z370 Chipset F... | 8     |
| pci:104c-9065 | Texas In... | TMS320DM642                  | 4     |
| pci:1b4b-1475 | Marvell ... |                              | 3     |
| pci:8086-a3a4 | Intel       | Comet Lake PCH-V SPI (fla... | 3     |
| pci:0014-7a10 | Loongson... | Hyper Transport Bridge Co... | 2     |
| pci:8086-a124 | Intel       | 100 Series/C230 Series Ch... | 2     |
| pci:0040-0000 | Unknown     |                              | 1     |
| pci:004c-8400 | Unknown     |                              | 1     |
| pci:0090-0000 | Unknown     |                              | 1     |
| pci:0702-82b0 | Unknown     |                              | 1     |
| pci:1001-0013 | Kolter E... | PCI-OPTO-RELAIS Digital I... | 1     |
| pci:1001-0017 | Kolter E... | PROTO-3 PCI Prototyping b... | 1     |
| pci:100c-8023 | Tseng Labs  |                              | 1     |
| pci:10ec-0119 | Realtek ... |                              | 1     |
| pci:1180-8476 | Ricoh       |                              | 1     |
| pci:1274-5882 | Ensoniq     |                              | 1     |
| pci:12f4-5000 | Megatel     |                              | 1     |
| pci:1415-9510 | Oxford S... | OX16PCI954 (Quad 16950 UA... | 1     |
| pci:14e4-8100 | Broadcom    |                              | 1     |
| pci:1814-0203 | Ralink      |                              | 1     |
| pci:1a39-0004 | Unknown     |                              | 1     |
| pci:1b7c-0004 | Unknown     | Ceton InfiniTV Network       | 1     |
| pci:1b94-c156 | Signatec... |                              | 1     |
| pci:1cbc-0100 | Unknown     |                              | 1     |
| pci:1f30-130f | Unknown     |                              | 1     |
| pci:1fff-800e | MCST        | System Power Managment (S... | 1     |
| pci:5555-3b00 | Genroco     | Epiphan DVI2PCIe video ca... | 1     |
| pci:8005-0000 | Unknown     |                              | 1     |
| pci:a411-0000 | Unknown     |                              | 1     |
| pci:f810-ffff | Unknown     |                              | 1     |

### Parallel controller (PCI)

Total devices: 51

| ID            | MFG         | Name                         | Count |
|---------------|-------------|------------------------------|-------|
| pci:1415-c110 | Oxford S... | OXPCIe952 Parallel Port      | 15    |
| pci:125b-9100 | Asix Ele... | AX99100 PCIe to Multi I/O... | 7     |
| pci:1409-7268 | Timedia ... | SUN1888 (Dual IEEE1284 pa... | 7     |
| pci:ffff-9865 | Illegal ... | Parallel controller          | 7     |
| pci:1c00-2170 | Unknown     | WCH PCI                      | 6     |
| pci:1415-8403 | Oxford S... | OX9162 Mode 0 (parallel p... | 4     |
| pci:1415-9523 | Oxford S... | OX16PCI952 Integrated Par... | 2     |
| pci:1407-8000 | Lava Com... | Lava Parallel                | 1     |
| pci:1415-c11c | Oxford S... | OXPCIe952 Parallel Port      | 1     |
| pci:9710-8925 | MosChip ... | MosChip Parallel controller  | 1     |

### Performance counters (PCI)

Total devices: 8710

| ID            | MFG         | Name                         | Count |
|---------------|-------------|------------------------------|-------|
| pci:8086-3c46 | Intel       | Xeon E5/Core i7 Processor... | 537   |
| pci:8086-3c43 | Intel       | Xeon E5/Core i7 Ring to P... | 536   |
| pci:8086-3c44 | Intel       | Xeon E5/Core i7 Ring to Q... | 536   |
| pci:8086-3ce6 | Intel       | Xeon E5/Core i7 QuickPath... | 536   |
| pci:8086-2f30 | Intel       | Xeon E7 v3/Xeon E5 v3/Cor... | 511   |
| pci:8086-2f34 | Intel       | Xeon E7 v3/Xeon E5 v3/Cor... | 511   |
| pci:8086-2f36 | Intel       | Xeon E7 v3/Xeon E5 v3/Cor... | 511   |
| pci:8086-2f37 | Intel       | Xeon E7 v3/Xeon E5 v3/Cor... | 511   |
| pci:8086-2f7d | Intel       | Xeon E7 v3/Xeon E5 v3/Cor... | 511   |
| pci:8086-0e30 | Intel       | Xeon E7 v2/Xeon E5 v2/Cor... | 346   |
| pci:8086-0e34 | Intel       | Xeon E7 v2/Xeon E5 v2/Cor... | 346   |
| pci:8086-0e36 | Intel       | Xeon E7 v2/Xeon E5 v2/Cor... | 346   |
| pci:8086-2015 | Intel       | Sky Lake-E Ubox Registers    | 315   |
| pci:8086-204c | Intel       | Sky Lake-E M3KTI Registers   | 314   |
| pci:8086-204d | Intel       | Sky Lake-E M3KTI Registers   | 314   |
| pci:8086-6f30 | Intel       | Xeon E7 v4/Xeon E5 v4/Xeo... | 201   |
| pci:8086-6f34 | Intel       | Xeon E7 v4/Xeon E5 v4/Xeo... | 201   |
| pci:8086-6f36 | Intel       | Xeon E7 v4/Xeon E5 v4/Xeo... | 201   |
| pci:8086-6f37 | Intel       | Xeon E7 v4/Xeon E5 v4/Xeo... | 201   |
| pci:8086-6f7d | Intel       | Xeon E7 v4/Xeon E5 v4/Xeo... | 201   |
| pci:8086-2058 | Intel       | Sky Lake-E KTI 0             | 159   |
| pci:8086-2f38 | Intel       | Xeon E7 v3/Xeon E5 v3/Cor... | 143   |
| pci:8086-2088 | Intel       | Sky Lake-E DDRIO Registers   | 106   |
| pci:8086-27a3 | Intel       | 945GM/GU Chipset Hardware... | 90    |
| pci:8086-2f32 | Intel       | Xeon E7 v3/Xeon E5 v3/Cor... | 88    |
| pci:8086-2f33 | Intel       | Xeon E7 v3/Xeon E5 v3/Cor... | 84    |
| pci:8086-6f32 | Intel       | Xeon E7 v4/Xeon E5 v4/Xeo... | 65    |
| pci:8086-6f33 | Intel       | Xeon E7 v4/Xeon E5 v4/Xeo... | 65    |
| pci:8086-3424 | Intel       | 7500/5520/5500/X58 Perfor... | 51    |
| pci:8086-6f38 | Intel       | Xeon E7 v4/Xeon E5 v4/Xeo... | 38    |
| pci:8086-0e37 | Intel       | Xeon E7 v2/Xeon E5 v2/Cor... | 25    |
| pci:8086-0e38 | Intel       | Xeon E7 v2/Xeon E5 v2/Cor... | 22    |
| pci:8086-3c41 | Intel       | Sandy Bridge QPI Port 0 P... | 20    |
| pci:8086-3c42 | Intel       | Sandy Bridge QPI Port 1 P... | 20    |
| pci:8086-0e32 | Intel       | Xeon E7 v2/Xeon E5 v2/Cor... | 9     |
| pci:8086-0e33 | Intel       | Xeon E7 v2/Xeon E5 v2/Cor... | 9     |
| pci:8086-2880 | Intel       | Performance counters         | 4     |
| pci:8086-0107 | Intel       | Performance counters         | 3     |
| pci:8086-6f39 | Intel       | Xeon E7 v4/Xeon E5 v4/Xeo... | 3     |
| pci:8086-0c07 | Intel       | Performance counters         | 2     |
| pci:8086-1907 | Intel       | Performance counters         | 2     |
| pci:8086-324a | Intel       | Performance counters         | 2     |
| pci:8086-344a | Intel       | Performance counters         | 2     |
| pci:8086-7814 | Intel       | Xeon Phi x200 product fam... | 2     |
| pci:8086-7817 | Intel       | Xeon Phi x200 product fam... | 2     |
| pci:8086-781b | Intel       | Xeon Phi x200 product fam... | 2     |
| pci:8086-0e39 | Intel       | Performance counters         | 1     |
| pci:8086-1c23 | Intel       | Performance counters         | 1     |
| pci:8086-2027 | Intel       | Skylake-E DMI3 PMON Regis... | 1     |
| pci:8086-2037 | Intel       | Performance counters         | 1     |
| pci:8086-2f39 | Intel       | Xeon E7 v3/Xeon E5 v3/Cor... | 1     |
| pci:8086-3508 | Intel       | Performance counters         | 1     |

### Pic (PCI)

Total devices: 8289

| ID            | MFG         | Name                         | Count |
|---------------|-------------|------------------------------|-------|
| pci:8086-342e | Intel       | 7500/5520/5500/X58 I/O Hu... | 1088  |
| pci:8086-3422 | Intel       | 7500/5520/5500/X58 I/O Hu... | 1086  |
| pci:8086-3423 | Intel       | 7500/5520/5500/X58 I/O Hu... | 1086  |
| pci:8086-3438 | Intel       | 7500/5520/5500/X58 I/O Hu... | 545   |
| pci:8086-3c2c | Intel       | Xeon E5/Core i7 I/O APIC     | 498   |
| pci:8086-2f2c | Intel       | Xeon E7 v3/Xeon E5 v3/Cor... | 472   |
| pci:8086-3425 | Intel       | 7500/5520/5500/X58 Physic... | 380   |
| pci:8086-3426 | Intel       | 7500/5520/5500/X58 Routin... | 380   |
| pci:8086-3427 | Intel       | 7500/5520/5500 Physical a... | 343   |
| pci:8086-3428 | Intel       | 7500/5520/5500 Routing & ... | 343   |
| pci:8086-342f | Intel       | 7500/5520/5500/X58 Truste... | 328   |
| pci:8086-0e2c | Intel       | Xeon E7 v2/Xeon E5 v2/Cor... | 327   |
| pci:8086-2026 | Intel       | Sky Lake-E IOAPIC            | 315   |
| pci:8086-2036 | Intel       | Sky Lake-E IOxAPIC Config... | 315   |
| pci:8086-342d | Intel       | 7500/5520/5500/X58 I/O Hu... | 257   |
| pci:8086-6f2c | Intel       | Xeon E7 v4/Xeon E5 v4/Xeo... | 178   |
| pci:1106-5364 | VIA Tech... | CN896/VN896/P4M900 I/O AP... | 138   |
| pci:1106-5327 | VIA Tech... | P4M890 I/O APIC Interrupt... | 60    |
| pci:1106-5336 | VIA Tech... | K8M890CE I/O APIC Interru... | 31    |
| pci:8086-3504 | Intel       | 6311ESB/6321ESB I/OxAPIC ... | 27    |
| pci:1106-5308 | VIA Tech... | PT894 I/O APIC Interrupt ... | 25    |
| pci:8086-0326 | Intel       | 6700/6702PXH I/OxAPIC Int... | 16    |
| pci:8086-0327 | Intel       | 6700PXH I/OxAPIC Interrup... | 10    |
| pci:1106-5353 | VIA Tech... | VX800/VX820 APIC and Cent... | 8     |
| pci:1022-7451 | AMD         | AMD-8131 PCI-X IOAPIC        | 6     |
| pci:1106-5351 | VIA Tech... | VT3351 I/O APIC Interrupt... | 6     |
| pci:1106-5238 | VIA Tech... | K8T890 I/O APIC Interrupt... | 5     |
| pci:8086-25ac | Intel       | 6300ESB I/O Advanced Prog... | 5     |
| pci:8086-1461 | Intel       | 82870P2 P64H2 I/OxAPIC       | 4     |
| pci:8086-7813 | Intel       | Xeon Phi x200 product fam... | 2     |
| pci:1022-7459 | AMD         | AMD-8132 PCI-X IOAPIC        | 1     |
| pci:1104-0844 | RasterOps   | PIC                          | 1     |
| pci:1106-5409 | VIA Tech... | VX855/VX875 APIC and Cent... | 1     |
| pci:8086-1161 | Intel       | 82806AA PCI64 Hub Advance... | 1     |
| pci:8086-373f | Intel       | Xeon C5500/C3500 IOxAPIC     | 1     |

### Power pc (PCI)

Total devices: 14

| ID            | MFG         | Name                         | Count |
|---------------|-------------|------------------------------|-------|
| pci:1957-c006 | Freescal... | MPC8308                      | 9     |
| pci:1957-00b6 | Freescal... | MPC8314E                     | 4     |
| pci:1957-0085 | Freescal... | MPC8347 PBGA                 | 1     |

### Processing accelerators (PCI)

Total devices: 3

| ID            | MFG         | Name                         | Count |
|---------------|-------------|------------------------------|-------|
| pci:10ee-5000 | Xilinx      | Processing accelerators      | 1     |
| pci:10ee-5001 | Xilinx      | Processing accelerators      | 1     |
| pci:10ee-d020 | Xilinx      | Processing accelerators      | 1     |

### Rf controller (PCI)

Total devices: 1

| ID            | MFG         | Name                         | Count |
|---------------|-------------|------------------------------|-------|
| pci:10ec-7305 | Realtek ... | UWB Radio                    | 1     |

### Sd host controller (PCI)

Total devices: 20744

| ID            | MFG         | Name                         | Count |
|---------------|-------------|------------------------------|-------|
| pci:1180-0822 | Ricoh       | R5C822 SD/SDIO/MMC/MS/MSP... | 2778  |
| pci:14e4-16bc | Broadcom    | BCM57765/57785 SDXC/MMC C... | 1696  |
| pci:1180-e822 | Ricoh       | MMC/SD Host Controller       | 1648  |
| pci:197b-2391 | JMicron ... | Standard SD Host Controller  | 1307  |
| pci:197b-2381 | JMicron ... | Standard SD Host Controller  | 1127  |
| pci:1217-8621 | O2 Micro    | SD/MMC Card Reader Contro... | 1077  |
| pci:1180-e823 | Ricoh       | PCIe SDXC/MMC Host Contro... | 1068  |
| pci:1022-7813 | AMD         | FCH SD Flash Controller      | 843   |
| pci:1217-8520 | O2 Micro    | SD/MMC Card Reader Contro... | 843   |
| pci:8086-31cc | Intel       | Celeron/Pentium Silver Pr... | 783   |
| pci:1217-8221 | O2 Micro    | OZ600FJ0/OZ900FJ0/OZ600FJ... | 697   |
| pci:8086-5acc | Intel       | Celeron N3350/Pentium N42... | 592   |
| pci:104c-803c | Texas In... | PCIxx12 SDA Standard Comp... | 526   |
| pci:8086-9d2d | Intel       | Sunrise Point-LP Secure D... | 443   |
| pci:1022-7806 | AMD         | FCH SD Flash Controller      | 418   |
| pci:8086-31d0 | Intel       | SD Host Controller           | 394   |
| pci:8086-5aca | Intel       | Celeron N3350/Pentium N42... | 375   |
| pci:8086-5ad0 | Intel       | Celeron N3350/Pentium N42... | 332   |
| pci:1217-7120 | O2 Micro    | Integrated MMC/SD Controller | 314   |
| pci:17a0-9750 | Genesys ... | GL9750 SD Host Controller    | 282   |
| pci:8086-9d2b | Intel       | Skylake-U/Y SCC: eMMC        | 280   |
| pci:8086-9df5 | Intel       | BayHubTech Integrated SD ... | 249   |
| pci:1217-8321 | O2 Micro    | OZ600RJ0/OZ900RJ0/OZ600RJ... | 225   |
| pci:8086-02f5 | Intel       | Comet Lake PCH-LP SCS3       | 206   |
| pci:1022-7906 | AMD         | FCH SD Flash Controller      | 201   |
| pci:1180-0843 | Ricoh       | R5C843 MMC Host Controller   | 198   |
| pci:17a0-9755 | Genesys ... | GL9755 SD Host Controller    | 196   |
| pci:10ec-5250 | Realtek ... | RTS5250 PCI Express Card ... | 166   |
| pci:1524-0550 | ENE Tech... | ENE PCI Secure Digital Ca... | 160   |
| pci:8086-2294 | Intel       | Atom/Celeron/Pentium Proc... | 147   |
| pci:104c-8034 | Texas In... | PCIxx21/PCIxx11 SD Host C... | 105   |
| pci:8086-2296 | Intel       | Atom/Celeron/Pentium Proc... | 103   |
| pci:8086-a375 | Intel       | 300 Series Chipset Family... | 84    |
| pci:1217-8620 | O2 Micro    | BayHubTech/O2Micro Integr... | 82    |
| pci:8086-34f8 | Intel       | Ice Lake-LP SD Controller    | 81    |
| pci:1217-8320 | O2 Micro    | OZ600RJ1/OZ900RJ1 SD/MMC ... | 73    |
| pci:1969-3010 | Qualcomm... | Secure Digital Card Reader   | 68    |
| pci:8086-34c4 | Intel       | Ice Lake-LP SD Host Contr... | 68    |
| pci:1217-8120 | O2 Micro    | Integrated MMC/SD Controller | 64    |
| pci:8086-0f50 | Intel       | Atom Processor E3800 Seri... | 63    |
| pci:1524-0750 | ENE Tech... | ENE PCI SmartMedia / xD C... | 62    |
| pci:8086-4dc4 | Intel       | Jasper Lake SCS1: eMMC Co... | 56    |
| pci:8086-9dc4 | Intel       | Cannon Point-LP SD Host C... | 53    |
| pci:8086-0f16 | Intel       | Atom Processor Z36xxx/Z37... | 44    |
| pci:8086-02c4 | Intel       | Comet Lake PCH-LP SCS1: eMMC | 31    |
| pci:10ec-5288 | Realtek ... | RTS5288 PCI Express Card ... | 29    |
| pci:8086-06f5 | Intel       | 400 Series Chipset Family... | 29    |
| pci:197b-2386 | JMicron ... | Standard SD Host Controller  | 15    |
| pci:1106-401b | VIA Tech... | VIA Secure Digital host c... | 12    |
| pci:8086-2295 | Intel       | Atom/Celeron/Pentium Proc... | 9     |
| pci:8086-4df8 | Intel       | SD Host Controller           | 8     |
| pci:8086-811c | Intel       | US15W/US15X/US15L/UL11L S... | 6     |
| pci:8086-811d | Intel       | US15W/US15X/US15L/UL11L S... | 4     |
| pci:8086-0807 | Intel       | Moorestown SD Host Ctrl 0    | 3     |
| pci:8086-0808 | Intel       | Moorestown SD Host Ctrl 1    | 3     |
| pci:8086-0812 | Intel       | Moorestown SPI Ctrl 2        | 3     |
| pci:8086-19db | Intel       | Atom Processor C3000 Seri... | 3     |
| pci:8086-811e | Intel       | US15W/US15X/US15L/UL11L S... | 2     |
| pci:8086-98f8 | Intel       | SD Host Controller           | 2     |
| pci:8086-9cb5 | Intel       | Wildcat Point-LP Secure D... | 2     |
| pci:0180-0822 | Unknown     | SD Host controller           | 1     |
| pci:14e4-b7fa | Broadcom    | SD Host controller           | 1     |
| pci:8086-0f15 | Intel       | Atom Processor Z36xxx/Z37... | 1     |
| pci:8086-1190 | Intel       | Merrifield SD/SDIO/eMMC C... | 1     |
| pci:8086-1aca | Intel       | SD Host Controller           | 1     |
| pci:8086-1acc | Intel       | SD Host Controller           | 1     |

### Serial bus controller (PCI)

Total devices: 40815

| ID            | MFG         | Name                         | Count |
|---------------|-------------|------------------------------|-------|
| pci:8086-a324 | Intel       | Cannon Lake PCH SPI Contr... | 4746  |
| pci:8086-a368 | Intel       | Cannon Lake PCH Serial IO... | 2784  |
| pci:8086-9da4 | Intel       | Cannon Point-LP SPI Contr... | 2683  |
| pci:8086-9de8 | Intel       | Cannon Point-LP Serial IO... | 2207  |
| pci:8086-a369 | Intel       | Cannon Lake PCH Serial IO... | 2123  |
| pci:8086-02a4 | Intel       | Comet Lake SPI (flash) Co... | 1844  |
| pci:8086-a0a4 | Intel       | Tiger Lake-LP SPI Controller | 1822  |
| pci:8086-9de9 | Intel       | Cannon Point-LP Serial IO... | 1686  |
| pci:8086-a0e8 | Intel       | Tiger Lake-LP Serial IO I... | 1657  |
| pci:8086-02e8 | Intel       | Serial IO I2C Host Contro... | 1499  |
| pci:8086-06a4 | Intel       | Comet Lake PCH SPI Contro... | 1334  |
| pci:8086-a0e9 | Intel       | Tiger Lake-LP Serial IO I... | 1173  |
| pci:10de-1aed | Nvidia      | TU116 USB Type-C UCSI Con... | 1167  |
| pci:10de-1adb | Nvidia      | TU106 USB Type-C UCSI Con... | 1163  |
| pci:8086-06e8 | Intel       | Comet Lake PCH Serial IO ... | 1044  |
| pci:8086-34a4 | Intel       | Ice Lake-LP SPI Controller   | 1003  |
| pci:8086-34e8 | Intel       | Ice Lake-LP Serial IO I2C... | 972   |
| pci:8086-02e9 | Intel       | Comet Lake Serial IO I2C ... | 820   |
| pci:8086-34e9 | Intel       | Ice Lake-LP Serial IO I2C... | 811   |
| pci:8086-06e9 | Intel       | Comet Lake PCH Serial IO ... | 738   |
| pci:10de-1ad9 | Nvidia      | TU104 USB Type-C UCSI Con... | 663   |
| pci:8086-9dc5 | Intel       | Cannon Point-LP Serial IO... | 594   |
| pci:8086-43a4 | Intel       | Tiger Lake-H SPI Controller  | 569   |
| pci:8086-43e8 | Intel       | Tiger Lake-H Serial IO I2... | 356   |
| pci:8086-02c5 | Intel       | Comet Lake Serial IO I2C ... | 322   |
| pci:8086-9ce6 | Intel       | Wildcat Point-LP Serial I... | 292   |
| pci:8086-a0eb | Intel       | Tiger Lake-LP Serial IO I... | 283   |
| pci:8086-9daa | Intel       | Cannon Point-LP Serial IO... | 280   |
| pci:8086-a0c5 | Intel       | Tiger Lake-LP Serial IO I... | 255   |
| pci:8086-a0ea | Intel       | Tiger Lake-LP Serial IO I... | 234   |
| pci:8086-a0ab | Intel       | Tiger Lake-LP Serial IO S... | 202   |
| pci:8086-a0c6 | Intel       | Tiger Lake-LP Serial IO I... | 202   |
| pci:8086-43e9 | Intel       | 500 Series Chipset Family... | 199   |
| pci:8086-02ea | Intel       | Comet Lake PCH-LP LPSS: I... | 197   |
| pci:10de-1ad7 | Nvidia      | TU102 USB Type-C UCSI Con... | 185   |
| pci:8086-34c5 | Intel       | Ice Lake-LP Serial IO I2c... | 176   |
| pci:8086-9dea | Intel       | 8th Gen Intel Core Proces... | 176   |
| pci:8086-34aa | Intel       | Ice Lake-LP Serial IO SPI... | 161   |
| pci:8086-a1a4 | Intel       | C620 Series Chipset Famil... | 158   |
| pci:8086-a36a | Intel       | Cannon Lake PCH Serial IO... | 131   |
| pci:8086-06ea | Intel       | Comet Lake PCH Serial IO ... | 124   |
| pci:8086-34ea | Intel       | Ice Lake-LP Serial IO I2C... | 112   |
| pci:8086-9deb | Intel       | 8th Gen Intel Core Proces... | 103   |
| pci:8086-9dab | Intel       | Cannon Point-LP Serial IO... | 101   |
| pci:8086-5ac8 | Intel       | Celeron N3350/Pentium N42... | 88    |
| pci:8086-02aa | Intel       | Comet Lake PCH-LP LPSS: S... | 71    |
| pci:8086-4da4 | Intel       | Jasper Lake SPI Controller   | 71    |
| pci:8086-4de8 | Intel       | Serial IO I2C Host Contro... | 66    |
| pci:8086-7aa4 | Intel       | Alder Lake-S PCH SPI Cont... | 66    |
| pci:8086-a0aa | Intel       | Tiger Lake-LP Serial IO S... | 65    |
| pci:8086-02ab | Intel       | Comet Lake PCH-LP LPSS: S... | 62    |
| pci:8086-34eb | Intel       | Ice Lake-LP Serial IO I2C... | 61    |
| pci:8086-9c66 | Intel       | 8 Series SPI Controller #1   | 52    |
| pci:8086-4dab | Intel       | Jasper Lake LPSS: SPI Con... | 51    |
| pci:1002-73a4 | AMD         | Navi 21 USB                  | 47    |
| pci:8086-7acc | Intel       | Alder Lake-S PCH I2C Cont... | 46    |
| pci:8086-7acd | Intel       | 600 Series Chipset Family... | 41    |
| pci:8086-7ace | Intel       | 600 Series Chipset Family... | 41    |
| pci:8086-a32a | Intel       | 300 Series Chipset Family    | 40    |
| pci:8086-02eb | Intel       | Comet Lake PCH-LP LPSS: I... | 34    |
| pci:8086-34ab | Intel       | Ice Lake-LP Serial IO SPI... | 33    |
| pci:8086-4dc5 | Intel       | Jasper Lake LPSS: I2C Con... | 28    |
| pci:8086-a32b | Intel       | Cannon Lake PCH SPI Host ... | 25    |
| pci:8086-22c6 | Intel       | Atom/Celeron/Pentium Proc... | 24    |
| pci:8086-4dea | Intel       | Jasper Lake LPSS: I2C Con... | 24    |
| pci:8086-22c7 | Intel       | Atom/Celeron/Pentium Proc... | 23    |
| pci:8086-43ad | Intel       | 500 Series Chipset Family... | 23    |
| pci:8086-4dc6 | Intel       | Jasper Lake LPSS: I2C Con... | 22    |
| pci:8086-a0d8 | Intel       | Tiger Lake-LP Serial IO I... | 21    |
| pci:8086-43ea | Intel       | 500 Series Chipset Family... | 20    |
| pci:8086-4de9 | Intel       | Serial IO I2C Host Contro... | 20    |
| pci:8086-9dc6 | Intel       | 8th Gen Intel Core Proces... | 18    |
| pci:8086-38a4 | Intel       | Ice Lake SPI Controller      | 16    |
| pci:8086-4deb | Intel       | Jasper Lake LPSS: I2C Con... | 15    |
| pci:8086-7acf | Intel       | 600 Series Chipset Family... | 15    |
| pci:8086-7afc | Intel       | 600 Series Chipset Family... | 15    |
| pci:8086-7afd | Intel       | 600 Series Chipset Family... | 15    |
| pci:8086-22c1 | Intel       | Atom/Celeron/Pentium Proc... | 14    |
| pci:8086-9c61 | Intel       | 8 Series I2C Controller #0   | 13    |
| pci:8086-9c62 | Intel       | 8 Series I2C Controller #1   | 13    |
| pci:8086-06ab | Intel       | Comet Lake PCH Serial IO ... | 12    |
| pci:8086-06eb | Intel       | Comet Lake PCH Serial IO ... | 11    |
| pci:8086-34c6 | Intel       | Ice Lake-LP Serial IO I2c... | 10    |
| pci:8086-43eb | Intel       | 500 Series Chipset Family... | 10    |
| pci:8086-0f41 | Intel       | Atom Processor Z36xxx/Z37... | 8     |
| pci:8086-19e0 | Intel       | Atom Processor C3000 Seri... | 8     |
| pci:8086-a36b | Intel       | Cannon Lake PCH Serial IO... | 8     |
| pci:8086-02c6 | Intel       | Comet Lake PCH-LP LPSS: I... | 7     |
| pci:8086-31c8 | Intel       | Serial bus controller        | 5     |
| pci:8086-51a4 | Intel       | Alder Lake-P PCH SPI Cont... | 5     |
| pci:8086-51e8 | Intel       | Alder Lake PCH Serial IO ... | 5     |
| pci:8086-9ce2 | Intel       | Wildcat Point-LP Serial I... | 5     |
| pci:1002-7314 | AMD         | Navi 10 USB                  | 4     |
| pci:8086-06aa | Intel       | Comet Lake PCH Serial IO ... | 4     |
| pci:8086-06fb | Intel       | Comet Lake PCH Serial IO ... | 4     |
| pci:8086-0f42 | Intel       | Atom Processor Z36xxx/Z37... | 4     |
| pci:8086-43ae | Intel       | 500 Series Chipset Family... | 4     |
| pci:8086-0f43 | Intel       | Atom Processor Z36xxx/Z37... | 3     |
| pci:8086-43ab | Intel       | 500 Series Chipset Family... | 3     |
| pci:8086-0f08 | Intel       | Atom Processor Z36xxx/Z37... | 2     |
| pci:8086-0f09 | Intel       | Atom Processor Z36xxx/Z37... | 2     |
| pci:8086-0f0e | Intel       | Atom Processor Z36xxx/Z37... | 2     |
| pci:8086-0f44 | Intel       | Atom Processor Z36xxx/Z37... | 2     |
| pci:8086-0f46 | Intel       | Atom Processor Z36xxx/Z37... | 2     |
| pci:8086-1bca | Intel       | Serial bus controller        | 2     |
| pci:8086-43fd | Intel       | Serial IO SPI Host Contro... | 2     |
| pci:8086-98a4 | Intel       | SPI Flash Controller         | 2     |
| pci:8086-98aa | Intel       | LPSS: SPI Controller #0      | 2     |
| pci:8086-98c5 | Intel       | LPSS: I2C Controller #4      | 2     |
| pci:8086-98c6 | Intel       | LPSS: I2C Controller #5      | 2     |
| pci:8086-98e8 | Intel       | LPSS: I2C Controller #0      | 2     |
| pci:8086-98e9 | Intel       | LPSS: I2C Controller #1      | 2     |
| pci:8086-98ea | Intel       | LPSS: I2C Controller #2      | 2     |
| pci:8086-98eb | Intel       | LPSS: I2C Controller #3      | 2     |
| pci:8086-9dfb | Intel       | 300 Series Chipset LPSS: ... | 2     |
| pci:8086-a37b | Intel       | 300 Series Chipset Family... | 2     |
| pci:8086-0f45 | Intel       | Atom Processor Z36xxx/Z37... | 1     |
| pci:8086-0f47 | Intel       | Atom Processor Z36xxx/Z37... | 1     |
| pci:8086-1ac8 | Intel       | Serial bus controller        | 1     |
| pci:8086-22c2 | Intel       | Atom/Celeron/Pentium Proc... | 1     |
| pci:8086-22c3 | Intel       | Atom/Celeron/Pentium Proc... | 1     |
| pci:8086-22c4 | Intel       | Atom/Celeron/Pentium Proc... | 1     |
| pci:8086-4daa | Intel       | Jasper Lake LPSS: SPI Con... | 1     |
| pci:8086-51e9 | Intel       | Alder Lake PCH Serial IO ... | 1     |
| pci:8086-51ea | Intel       | Alder Lake PCH Serial IO ... | 1     |
| pci:8086-5a96 | Intel       | Serial bus controller        | 1     |
| pci:8086-7aab | Intel       | 600 Series Chipset Family... | 1     |

### Serial controller (PCI)

Total devices: 12546

| ID            | MFG         | Name                         | Count |
|---------------|-------------|------------------------------|-------|
| pci:8086-1e3d | Intel       | 7 Series/C210 Series Chip... | 1494  |
| pci:8086-1c3d | Intel       | 6 Series/C200 Series Chip... | 1334  |
| pci:8086-8c3d | Intel       | 8 Series/C220 Series Chip... | 1161  |
| pci:8086-9d3d | Intel       | Sunrise Point-LP Active M... | 915   |
| pci:8086-3b67 | Intel       | 5 Series/3400 Series Chip... | 763   |
| pci:8086-a0fc | Intel       | Tiger Lake-LP Integrated ... | 759   |
| pci:8086-2e17 | Intel       | 4 Series Chipset Serial K... | 677   |
| pci:10ec-816a | Realtek ... | RTL8111xP UART #1            | 490   |
| pci:8086-9c3d | Intel       | 8 Series HECI KT             | 475   |
| pci:10ec-816b | Realtek ... | RTL8111xP UART #2            | 460   |
| pci:8086-a13d | Intel       | 100 Series/C230 Series Ch... | 448   |
| pci:8086-02fc | Intel       | Comet Lake Integrated Sen... | 379   |
| pci:8086-9dfc | Intel       | Cannon Point-LP Integrate... | 357   |
| pci:8086-a363 | Intel       | Cannon Lake PCH Active Ma... | 316   |
| pci:8086-2a47 | Intel       | Mobile 4 Series Chipset A... | 285   |
| pci:8086-29b7 | Intel       | 82Q35 Express Serial KT C... | 281   |
| pci:8086-06fc | Intel       | 400 Series Chipset Family... | 267   |
| pci:8086-34fc | Intel       | Ice Lake-LP Integrated Se... | 222   |
| pci:8086-9de3 | Intel       | Cannon Point-LP Keyboard ... | 212   |
| pci:8086-a37c | Intel       | VROC Virtual Controller      | 140   |
| pci:8086-1d3d | Intel       | C600/X79 series chipset K... | 137   |
| pci:8086-06e3 | Intel       | Comet Lake Keyboard and T... | 111   |
| pci:8086-a2bd | Intel       | 200 Series Chipset Family... | 102   |
| pci:8086-43fc | Intel       | 500 Series Chipset Family... | 100   |
| pci:8086-2a07 | Intel       | Mobile PM965/GM965 KT Con... | 88    |
| pci:8086-a0e3 | Intel       | Tiger Lake-LP Active Mana... | 79    |
| pci:8086-8d3d | Intel       | C610/X99 series chipset K... | 75    |
| pci:8086-02e3 | Intel       | Comet Lake PCH-LP Keyboar... | 74    |
| pci:9710-9865 | MosChip ... | PCI 9865 Multi-I/O Contro... | 46    |
| pci:8086-2997 | Intel       | 82Q963/Q965 KT Controller    | 42    |
| pci:8086-43e3 | Intel       | 500 Series Chipset Family... | 36    |
| pci:8086-a1bd | Intel       | C620 Series Chipset Famil... | 21    |
| pci:9710-9912 | MosChip ... | PCIe 9912 Multi-I/O Contr... | 21    |
| pci:1c00-3250 | Unknown     | WCH PCI Express              | 20    |
| pci:9710-9922 | MosChip ... | MCS9922 PCIe Multi-I/O Co... | 13    |
| pci:1c00-2273 | Unknown     | WCH PCI                      | 11    |
| pci:1c00-3253 | Unknown     | WCH PCI Express              | 10    |
| pci:1415-c158 | Oxford S... | OXPCIe952 Dual Native 950... | 9     |
| pci:4348-3253 | WCH.CN      | CH352 PCI Dual Serial Por... | 9     |
| pci:4348-7053 | WCH.CN      | CH353 PCI Dual Serial and... | 8     |
| pci:8086-108f | Intel       | Active Management Technol... | 7     |
| pci:12b9-1008 | 3Com Cor... | 56K FaxModem Model 5610      | 5     |
| pci:1415-9501 | Oxford S... | OX16PCI954 (Quad 16950 UA... | 5     |
| pci:1c00-3050 | Unknown     | WCH PCI Express              | 5     |
| pci:8086-9cbd | Intel       | Wildcat Point-LP KT Contr... | 5     |
| pci:8086-9ce3 | Intel       | Wildcat Point-LP Serial I... | 5     |
| pci:9710-9845 | MosChip ... | PCI 9845 Multi-I/O Contro... | 4     |
| pci:9710-9904 | MosChip ... | 4-Port PCIe Serial Adapter   | 4     |
| pci:ffff-816a | Illegal ... | Serial controller            | 4     |
| pci:125b-9105 | Asix Ele... | Electronics Serial contro... | 3     |
| pci:1409-7168 | Timedia ... | PCI2S550 (Dual 16550 UART)   | 3     |
| pci:4651-7073 | TXIC        | Serial controller            | 3     |
| pci:8086-2e27 | Intel       | 4 Series Chipset Serial K... | 3     |
| pci:9710-9901 | MosChip ... | PCIe 9901 Multi-I/O Contr... | 3     |
| pci:1283-8872 | Integrat... | IT887xF PCI to ISA I/O ch... | 2     |
| pci:1393-1041 | Moxa Tec... | CP104U (4-port RS-232 Uni... | 2     |
| pci:1393-1141 | Moxa Tec... | Industrio CP-114             | 2     |
| pci:1415-c208 | Oxford S... | OXPCIe954 Quad Native 950... | 2     |
| pci:14a1-4d02 | Systembase  | Multi-2/PCI For Win98        | 2     |
| pci:4348-5053 | WCH.CN      | CH352 PCI Serial and Para... | 2     |
| pci:8086-98fc | Intel       | Serial controller            | 2     |
| pci:9710-9905 | MosChip ... | MosChip Serial controller    | 2     |
| pci:1014-0297 | IBM         | Serial controller            | 1     |
| pci:10ee-4b87 | Xilinx      | Serial controller            | 1     |
| pci:10ee-4b88 | Xilinx      | Serial controller            | 1     |
| pci:12d8-7952 | Pericom ... | Pericom PI7C9X7952 PCIe U... | 1     |
| pci:1393-1024 | Moxa Tec... | CP-102E (2-port RS-232 Sm... | 1     |
| pci:1393-1045 | Moxa Tec... | CP-104EL-A (4-port RS-232... | 1     |
| pci:1393-1680 | Moxa Tec... | Smartio C168H/PCI            | 1     |
| pci:1393-1683 | Moxa Tec... | CP-168EL-A (8-port RS-232... | 1     |
| pci:13a8-0352 | Exar        | XR17V3521 Dual PCIe UART     | 1     |
| pci:13a8-0354 | Exar        | Exar's 4-Port UART PCIe Card | 1     |
| pci:1407-0500 | Lava Com... | Lava Single Serial           | 1     |
| pci:1415-9500 | Oxford S... | OX16PCI954 (Quad 16950 UA... | 1     |
| pci:1415-9504 | Oxford S... | AAEON OX16PCI954 PCI UART... | 1     |
| pci:1415-9521 | Oxford S... | OX16PCI952 (Dual 16950 UART) | 1     |
| pci:1415-c138 | Oxford S... | OXPCIe952 Native 950 UART    | 1     |
| pci:1415-c308 | Oxford S... | OXPCIe958 Quad Native 950... | 1     |
| pci:14a1-4303 | Systembase  | Serial controller            | 1     |
| pci:14a1-4d01 | Systembase  | Multi-1/PCI For Win98        | 1     |
| pci:4348-3453 | WCH.CN      | CH353 PCI Quad Serial Por... | 1     |
| pci:4348-7173 | WCH.CN      | CH355 PCI Quad Serial Por... | 1     |
| pci:55a5-a006 | Unknown     | Serial controller            | 1     |
| pci:8086-1191 | Intel       | Merrifield Serial IO HSUA... | 1     |
| pci:8086-1192 | Intel       | Merrifield Serial IO HSUA... | 1     |
| pci:8086-19d8 | Intel       | Atom Processor C3000 Seri... | 1     |

### Signal processing controller (PCI)

Total devices: 87504

| ID            | MFG         | Name                         | Count |
|---------------|-------------|------------------------------|-------|
| pci:8086-1903 | Intel       | Xeon E3-1200 v5/E3-1500 v... | 13083 |
| pci:8086-9d31 | Intel       | Sunrise Point-LP Thermal ... | 8971  |
| pci:8086-9d60 | Intel       | Sunrise Point-LP Serial I... | 6586  |
| pci:8086-9d61 | Intel       | Sunrise Point-LP Serial I... | 4421  |
| pci:8086-a379 | Intel       | Cannon Lake PCH Thermal C... | 4245  |
| pci:8086-a131 | Intel       | 100 Series/C230 Series Ch... | 3388  |
| pci:8086-3b32 | Intel       | 5 Series/3400 Series Chip... | 3325  |
| pci:8086-9df9 | Intel       | Cannon Point-LP Thermal C... | 2683  |
| pci:8086-9a03 | Intel       | TigerLake-LP Dynamic Tuni... | 1886  |
| pci:8086-02f9 | Intel       | Comet Lake Thermal Subsytem  | 1844  |
| pci:8086-22dc | Intel       | Atom/Celeron/Pentium Proc... | 1832  |
| pci:8086-a160 | Intel       | 100 Series/C230 Series Ch... | 1402  |
| pci:8086-9d27 | Intel       | Sunrise Point-LP Serial I... | 1338  |
| pci:8086-9a0d | Intel       | Tigerlake Telemetry Aggre... | 1291  |
| pci:8086-06f9 | Intel       | Comet Lake PCH Thermal Co... | 1235  |
| pci:8086-9ca4 | Intel       | Wildcat Point-LP Thermal ... | 1217  |
| pci:8086-318c | Intel       | Celeron/Pentium Silver Pr... | 1156  |
| pci:8086-31b4 | Intel       | Celeron/Pentium Silver Pr... | 1087  |
| pci:8086-a161 | Intel       | 100 Series/C230 Series Ch... | 1047  |
| pci:8086-a2b1 | Intel       | 200 Series PCH Thermal Su... | 993   |
| pci:8086-9d62 | Intel       | Sunrise Point-LP Serial I... | 958   |
| pci:8086-8a03 | Intel       | Ice Lake Dynamic Platform... | 941   |
| pci:8086-31bc | Intel       | Celeron/Pentium Silver Pr... | 791   |
| pci:8086-31b6 | Intel       | Celeron/Pentium Silver Pr... | 785   |
| pci:8086-31be | Intel       | Celeron/Pentium Silver Pr... | 779   |
| pci:8086-1603 | Intel       | Broadwell-U Processor The... | 777   |
| pci:8086-31ee | Intel       | Celeron/Pentium Silver Pr... | 777   |
| pci:8086-5ab4 | Intel       | Celeron N3350/Pentium N42... | 731   |
| pci:8086-2932 | Intel       | 82801I (ICH9 Family) Ther... | 681   |
| pci:8086-5a8c | Intel       | Atom/Celeron/Pentium Dyna... | 675   |
| pci:8086-31c0 | Intel       | Celeron/Pentium Silver Pr... | 663   |
| pci:8086-5aac | Intel       | Celeron N3350/Pentium N42... | 633   |
| pci:8086-31ba | Intel       | Celeron/Pentium Silver Pr... | 584   |
| pci:8086-31b8 | Intel       | Celeron/Pentium Silver Pr... | 564   |
| pci:8086-31c2 | Intel       | Celeron/Pentium Silver Pr... | 537   |
| pci:8086-9c24 | Intel       | 8 Series Thermal             | 515   |
| pci:8086-31ac | Intel       | Celeron/Pentium Silver Pr... | 508   |
| pci:8086-31b2 | Intel       | Celeron/Pentium Silver Pr... | 501   |
| pci:8086-9d29 | Intel       | Sunrise Point-LP Serial I... | 494   |
| pci:8086-9d63 | Intel       | Sunrise Point-LP Serial I... | 491   |
| pci:8086-31c4 | Intel       | Celeron/Pentium Silver Pr... | 486   |
| pci:8086-0a03 | Intel       | Haswell-ULT Thermal Subsy... | 463   |
| pci:8086-5ac2 | Intel       | Celeron N3350/Pentium N42... | 458   |
| pci:8086-31b0 | Intel       | Celeron/Pentium Silver Pr... | 448   |
| pci:8086-5ab2 | Intel       | Celeron N3350/Pentium N42... | 447   |
| pci:8086-5abc | Intel       | Celeron N3350/Pentium N42... | 447   |
| pci:8086-5ab0 | Intel       | Celeron N3350/Pentium N42... | 446   |
| pci:8086-31ae | Intel       | Celeron/Pentium Silver Pr... | 442   |
| pci:8086-5ab6 | Intel       | Celeron N3350/Pentium N42... | 438   |
| pci:8086-5aae | Intel       | Celeron N3350/Pentium N42... | 431   |
| pci:8086-5ac6 | Intel       | Celeron N3350/Pentium N42... | 431   |
| pci:8086-5ac4 | Intel       | Celeron N3350/Pentium N42... | 430   |
| pci:8086-31c6 | Intel       | Celeron/Pentium Silver Pr... | 407   |
| pci:8086-5abe | Intel       | Celeron N3350/Pentium N42... | 407   |
| pci:8086-5ac0 | Intel       | Celeron N3350/Pentium N42... | 402   |
| pci:8086-5ab8 | Intel       | Celeron N3350/Pentium N42... | 400   |
| pci:8086-5aba | Intel       | Celeron N3350/Pentium N42... | 400   |
| pci:8086-5aee | Intel       | Celeron N3350/Pentium N42... | 385   |
| pci:8086-a127 | Intel       | 100 Series/C230 Series Ch... | 354   |
| pci:8086-1e24 | Intel       | 7 Series/C210 Series Chip... | 348   |
| pci:8086-8c24 | Intel       | 8 Series Chipset Family T... | 290   |
| pci:8086-0153 | Intel       | 3rd Gen Core Processor Th... | 271   |
| pci:8086-a3b1 | Intel       | Comet Lake PCH-V Thermal ... | 230   |
| pci:8086-9d2a | Intel       | Sunrise Point-LP Serial I... | 223   |
| pci:8086-9d66 | Intel       | Sunrise Point-LP Serial I... | 166   |
| pci:8086-a1b1 | Intel       | C620 Series Chipset Famil... | 165   |
| pci:8086-a2e0 | Intel       | 200 Series PCH Serial IO ... | 163   |
| pci:8086-a2a7 | Intel       | 200 Series/Z370 Chipset F... | 142   |
| pci:8086-a2e1 | Intel       | 200 Series PCH Serial IO ... | 126   |
| pci:8086-1d24 | Intel       | C600/X79 series chipset T... | 105   |
| pci:8086-1c24 | Intel       | 6 Series/C200 Series Chip... | 84    |
| pci:8086-a162 | Intel       | 100 Series/C230 Series Ch... | 74    |
| pci:8086-9d64 | Intel       | Sunrise Point-LP Serial I... | 73    |
| pci:8086-467d | Intel       | Platform Monitoring Techn... | 61    |
| pci:8086-4e03 | Intel       | Dynamic Tuning service       | 60    |
| pci:8086-8d24 | Intel       | C610/X99 series chipset T... | 55    |
| pci:8086-a129 | Intel       | 100 Series/C230 Series Ch... | 46    |
| pci:8086-0c03 | Intel       | Dynamic Platform and Ther... | 42    |
| pci:8086-a3e0 | Intel       | Comet Lake PCH-V LPSS: I2... | 27    |
| pci:8086-0103 | Intel       | Core i7/i5/i3 Thermal Man... | 26    |
| pci:8086-9d65 | Intel       | Sunrise Point-LP Serial I... | 19    |
| pci:8086-a3e1 | Intel       | Comet Lake PCH-V LPSS: I2... | 19    |
| pci:8086-284f | Intel       | 82801H (ICH8 Family) Ther... | 16    |
| pci:8086-3a32 | Intel       | 82801JI (ICH10 Family) Th... | 15    |
| pci:8086-4c03 | Intel       | Signal processing controller | 13    |
| pci:8086-9d28 | Intel       | Sunrise Point-LP Serial I... | 11    |
| pci:8086-0050 | Intel       | Core Processor Thermal Ma... | 10    |
| pci:8086-a128 | Intel       | 100 Series/C230 Series Ch... | 8     |
| pci:8086-a12a | Intel       | 100 Series/C230 Series Ch... | 8     |
| pci:8086-a166 | Intel       | 100 Series/C230 Series Ch... | 8     |
| pci:8086-a3a7 | Intel       | Comet Lake PCH-V LPSS: UA... | 8     |
| pci:8086-2a08 | Intel       | Signal processing controller | 7     |
| pci:8086-461d | Intel       | Alder Lake Innovation Pla... | 7     |
| pci:8086-8ca4 | Intel       | 9 Series Chipset Family T... | 7     |
| pci:19e5-1710 | Huawei T... | iBMA Virtual Network Adapter | 5     |
| pci:8086-3a62 | Intel       | 82801JD/DO (ICH10 Family)... | 2     |
| pci:8086-9820 | Intel       | Dynamic Platform and Ther... | 2     |
| pci:8086-a2a8 | Intel       | 200 Series/Z370 Chipset F... | 2     |
| pci:144a-8554 | Adlink T... | PCI-8554                     | 1     |
| pci:1805-0812 | Euresys     | S.A Signal processing con... | 1     |
| pci:19aa-2280 | Unknown     | Signal processing controller | 1     |
| pci:1a4a-2030 | SLAC Nat... | AXI Stream DAQ PCIe card     | 1     |
| pci:8086-0d03 | Intel       | Dynamic Platform and Ther... | 1     |
| pci:8086-119f | Intel       | Signal processing controller | 1     |
| pci:8086-1a8c | Intel       | Dynamic Platform and Ther... | 1     |
| pci:8086-1aac | Intel       | Signal processing controller | 1     |
| pci:8086-1aae | Intel       | Signal processing controller | 1     |
| pci:8086-1ab0 | Intel       | Signal processing controller | 1     |
| pci:8086-1ab2 | Intel       | Signal processing controller | 1     |
| pci:8086-1ab4 | Intel       | Signal processing controller | 1     |
| pci:8086-1ab6 | Intel       | Signal processing controller | 1     |
| pci:8086-1ab8 | Intel       | Signal processing controller | 1     |
| pci:8086-1aba | Intel       | Signal processing controller | 1     |
| pci:8086-1abc | Intel       | Signal processing controller | 1     |
| pci:8086-1abe | Intel       | Signal processing controller | 1     |
| pci:8086-1ac0 | Intel       | Signal processing controller | 1     |
| pci:8086-1ac2 | Intel       | Signal processing controller | 1     |
| pci:8086-1ac4 | Intel       | Signal processing controller | 1     |
| pci:8086-1ac6 | Intel       | Signal processing controller | 1     |
| pci:8086-1aee | Intel       | Signal processing controller | 1     |
| pci:8086-1d77 | Intel       | C600/X79 series chipset P... | 1     |

### Signal processing management (PCI)

Total devices: 1

| ID            | MFG         | Name                         | Count |
|---------------|-------------|------------------------------|-------|
| pci:19a2-0800 | Emulex      | ServerView iRMC HTI          | 1     |

### Smbus (PCI)

Total devices: 127632

| ID            | MFG         | Name                         | Count |
|---------------|-------------|------------------------------|-------|
| pci:1022-790b | AMD         | FCH SMBus Controller         | 15116 |
| pci:8086-1e22 | Intel       | 7 Series/C216 Chipset Fam... | 10664 |
| pci:8086-1c22 | Intel       | 6 Series/C200 Series Chip... | 10386 |
| pci:8086-9d23 | Intel       | Sunrise Point-LP SMBus       | 9434  |
| pci:1002-4385 | AMD         | SBx00 SMBus Controller       | 8071  |
| pci:8086-8c22 | Intel       | 8 Series/C220 Series Chip... | 6655  |
| pci:8086-27da | Intel       | NM10/ICH7 Family SMBus Co... | 6496  |
| pci:1022-780b | AMD         | FCH SMBus Controller         | 5475  |
| pci:8086-3b30 | Intel       | 5 Series/3400 Series Chip... | 5062  |
| pci:8086-a123 | Intel       | 100 Series/C230 Series Ch... | 4911  |
| pci:8086-a323 | Intel       | Cannon Lake PCH SMBus Con... | 4741  |
| pci:8086-2930 | Intel       | 82801I (ICH9 Family) SMBu... | 4698  |
| pci:8086-9c22 | Intel       | 8 Series SMBus Controller    | 3369  |
| pci:8086-9da3 | Intel       | Cannon Point-LP SMBus Con... | 2662  |
| pci:8086-9ca2 | Intel       | Wildcat Point-LP SMBus Co... | 2643  |
| pci:8086-283e | Intel       | 82801H (ICH8 Family) SMBu... | 2436  |
| pci:8086-a2a3 | Intel       | 200 Series/Z370 Chipset F... | 2288  |
| pci:8086-3a30 | Intel       | 82801JI (ICH10 Family) SM... | 1912  |
| pci:8086-02a3 | Intel       | Comet Lake PCH-LP SMBus H... | 1834  |
| pci:8086-a0a3 | Intel       | Tiger Lake-LP SMBus Contr... | 1809  |
| pci:8086-0f12 | Intel       | Atom Processor E3800/CE27... | 1688  |
| pci:10de-03eb | Nvidia      | MCP61 SMBus                  | 1550  |
| pci:8086-31d4 | Intel       | Celeron/Pentium Silver Pr... | 1396  |
| pci:8086-2292 | Intel       | Atom/Celeron/Pentium Proc... | 1363  |
| pci:8086-06a3 | Intel       | Comet Lake PCH SMBus Cont... | 1334  |
| pci:8086-8ca2 | Intel       | 9 Series Chipset Family S... | 1041  |
| pci:8086-5ad4 | Intel       | Celeron N3350/Pentium N42... | 971   |
| pci:8086-34a3 | Intel       | Ice Lake-LP SMBus Controller | 954   |
| pci:8086-1d22 | Intel       | C600/X79 series chipset S... | 713   |
| pci:8086-8d22 | Intel       | C610/X99 series chipset S... | 639   |
| pci:8086-43a3 | Intel       | Tiger Lake-H SMBus Contro... | 569   |
| pci:10de-0aa2 | Nvidia      | MCP79 SMBus                  | 564   |
| pci:8086-3a60 | Intel       | 82801JD/DO (ICH10 Family)... | 523   |
| pci:8086-266a | Intel       | 82801FB/FBM/FR/FW/FRW (IC... | 401   |
| pci:10de-0752 | Nvidia      | MCP78S [GeForce 8200] SMBus  | 348   |
| pci:8086-a3a3 | Intel       | Comet Lake PCH-V SMBus Ho... | 331   |
| pci:10de-0264 | Nvidia      | MCP51 SMBus                  | 292   |
| pci:8086-24d3 | Intel       | 82801EB/ER (ICH5/ICH5R) S... | 268   |
| pci:1002-4372 | AMD         | IXP SB4x0 SMBus Controller   | 259   |
| pci:10de-0368 | Nvidia      | MCP55 SMBus Controller       | 225   |
| pci:10de-0052 | Nvidia      | CK804 SMBus                  | 195   |
| pci:10de-0542 | Nvidia      | MCP67 SMBus                  | 170   |
| pci:8086-a1a3 | Intel       | C620 Series Chipset Famil... | 158   |
| pci:8086-269b | Intel       | 631xESB/632xESB/3100 Chip... | 152   |
| pci:10de-07d8 | Nvidia      | MCP73 SMBus                  | 148   |
| pci:10de-0446 | Nvidia      | MCP65 SMBus                  | 118   |
| pci:10de-0d79 | Nvidia      | MCP89 SMBus                  | 116   |
| pci:8086-24c3 | Intel       | 82801DB/DBL/DBM (ICH4/ICH... | 94    |
| pci:8086-4da3 | Intel       | Jasper Lake SMBus            | 70    |
| pci:1039-0016 | Silicon ... | SiS961/2/3 SMBus controller  | 69    |
| pci:8086-7aa3 | Intel       | Alder Lake-S PCH SMBus Co... | 66    |
| pci:10de-00e4 | Nvidia      | nForce 250Gb PCI System M... | 44    |
| pci:10de-0064 | Nvidia      | nForce2 SMBus (MCP)          | 21    |
| pci:8086-38a3 | Intel       | SMBus Controller             | 16    |
| pci:8086-2443 | Intel       | 82801BA/BAM SMBus Controller | 14    |
| pci:8086-1d70 | Intel       | C600/X79 series chipset S... | 13    |
| pci:8086-1f3c | Intel       | Atom processor C2000 PCU ... | 13    |
| pci:1002-4353 | AMD         | SB200 SMBus Controller       | 12    |
| pci:8086-2483 | Intel       | 82801CA/CAM SMBus Controller | 11    |
| pci:10de-00d4 | Nvidia      | nForce3 SMBus                | 8     |
| pci:8086-19df | Intel       | Atom Processor C3000 Seri... | 8     |
| pci:8086-25a4 | Intel       | 6300ESB SMBus Controller     | 5     |
| pci:8086-51a3 | Intel       | Alder Lake PCH-P SMBus Ho... | 5     |
| pci:1106-3057 | VIA Tech... | VT82C686 [Apollo Super ACPI] | 3     |
| pci:10de-0034 | Nvidia      | MCP04 SMBus                  | 2     |
| pci:10de-0084 | Nvidia      | MCP2A SMBus                  | 2     |
| pci:8086-1bc9 | Intel       | SMBus                        | 2     |
| pci:8086-1d71 | Intel       | C608/C606/X79 series chip... | 2     |
| pci:8086-8d7f | Intel       | C610/X99 series chipset M... | 2     |
| pci:8086-2413 | Intel       | 82801AA SMBus Controller     | 1     |
| pci:8086-8d7d | Intel       | C610/X99 series chipset M... | 1     |

### Sound (PCI)

Total devices: 202774

| ID            | MFG         | Name                         | Count |
|---------------|-------------|------------------------------|-------|
| pci:8086-1e20 | Intel       | 7 Series/C216 Chipset Fam... | 11046 |
| pci:8086-1c20 | Intel       | 6 Series/C200 Series Chip... | 10799 |
| pci:1002-4383 | AMD         | SBx00 Azalia (Intel HDA)     | 7735  |
| pci:8086-27d8 | Intel       | NM10/ICH7 Family High Def... | 7041  |
| pci:1022-15e3 | AMD         | Family 17h/19h HD Audio C... | 6725  |
| pci:8086-9d71 | Intel       | Sunrise Point-LP HD Audio    | 6601  |
| pci:8086-8c20 | Intel       | 8 Series/C220 Series Chip... | 6543  |
| pci:8086-3b56 | Intel       | 5 Series/3400 Series Chip... | 5500  |
| pci:1022-780d | AMD         | FCH Azalia Controller        | 5407  |
| pci:8086-293e | Intel       | 82801I (ICH9 Family) HD A... | 5381  |
| pci:8086-0c0c | Intel       | Xeon E3-1200 v3/4th Gen C... | 4738  |
| pci:8086-a348 | Intel       | Cannon Lake PCH cAVS         | 4629  |
| pci:8086-a170 | Intel       | 100 Series/C230 Series Ch... | 3544  |
| pci:1002-15de | AMD         | Raven/Raven2/Fenghuang HD... | 3511  |
| pci:1022-1487 | AMD         | Starship/Matisse HD Audio... | 3499  |
| pci:8086-9c20 | Intel       | 8 Series HD Audio Controller | 3458  |
| pci:8086-0a0c | Intel       | Haswell-ULT HD Audio Cont... | 3437  |
| pci:8086-9d70 | Intel       | Sunrise Point-LP HD Audio    | 2992  |
| pci:8086-284b | Intel       | 82801H (ICH8 Family) HD A... | 2918  |
| pci:1022-1457 | AMD         | Family 17h (Models 00h-0f... | 2912  |
| pci:8086-160c | Intel       | Broadwell-U Audio Controller | 2732  |
| pci:8086-9dc8 | Intel       | Cannon Point-LP High Defi... | 2675  |
| pci:8086-9ca0 | Intel       | Wildcat Point-LP High Def... | 2671  |
| pci:10de-0bea | Nvidia      | GF108 High Definition Aud... | 2564  |
| pci:10de-0fb9 | Nvidia      | GP107GL High Definition A... | 2554  |
| pci:1002-1637 | AMD         | Renoir Radeon High Defini... | 2410  |
| pci:1002-aaf0 | AMD         | Ellesmere HDMI Audio [Rad... | 2395  |
| pci:10de-0e0f | Nvidia      | GK208 HDMI/DP Audio Contr... | 2295  |
| pci:1002-9840 | AMD         | Kabini HDMI/DP Audio         | 2288  |
| pci:8086-a2f0 | Intel       | 200 Series PCH HD Audio      | 2198  |
| pci:1002-aab0 | AMD         | Oland/Hainan/Cape Verde/P... | 2023  |
| pci:10de-0be3 | Nvidia      | High Definition Audio Con... | 2018  |
| pci:8086-3a3e | Intel       | 82801JI (ICH10 Family) HD... | 1861  |
| pci:8086-02c8 | Intel       | Comet Lake PCH-LP cAVS       | 1843  |
| pci:8086-a0c8 | Intel       | Tiger Lake-LP Smart Sound... | 1821  |
| pci:8086-0f04 | Intel       | Atom Processor Z36xxx/Z37... | 1785  |
| pci:1022-157a | AMD         | Family 15h (Models 60h-6f... | 1657  |
| pci:10de-10f1 | Nvidia      | GP106 High Definition Aud... | 1588  |
| pci:10de-03f0 | Nvidia      | MCP61 High Definition Audio  | 1503  |
| pci:10de-0e1b | Nvidia      | GK107 HDMI Audio Controller  | 1468  |
| pci:1002-aa68 | AMD         | Cedar HDMI Audio [Radeon ... | 1439  |
| pci:8086-2284 | Intel       | Atom/Celeron/Pentium Proc... | 1430  |
| pci:8086-3198 | Intel       | Celeron/Pentium Silver Pr... | 1388  |
| pci:10de-10f0 | Nvidia      | GP104 High Definition Aud... | 1381  |
| pci:10de-10fa | Nvidia      | TU107 GeForce GTX 1650 Hi... | 1350  |
| pci:10de-0fbc | Nvidia      | GM107 High Definition Aud... | 1331  |
| pci:8086-06c8 | Intel       | Comet Lake PCH cAVS          | 1297  |
| pci:1002-9902 | AMD         | Trinity HDMI Audio Contro... | 1266  |
| pci:10de-0e08 | Nvidia      | GF119 HDMI Audio Controller  | 1258  |
| pci:8086-a171 | Intel       | CM238 HD Audio Controller    | 1231  |
| pci:10de-10f9 | Nvidia      | TU106 High Definition Aud... | 1191  |
| pci:10de-1aeb | Nvidia      | TU116 High Definition Aud... | 1169  |
| pci:1002-aa38 | AMD         | RV710/730 HDMI Audio [Rad... | 1167  |
| pci:1002-1314 | AMD         | Wrestler HDMI Audio          | 1105  |
| pci:1002-aae0 | AMD         | Baffin HDMI/DP Audio [Rad... | 1087  |
| pci:1002-aa98 | AMD         | Caicos HDMI Audio [Radeon... | 1034  |
| pci:1002-15b3 | AMD         | High Definition Audio Con... | 1010  |
| pci:8086-8ca0 | Intel       | 9 Series Chipset Family H... | 1006  |
| pci:8086-34c8 | Intel       | Ice Lake-LP Smart Sound T... | 1003  |
| pci:1002-ab38 | AMD         | Navi 10 HDMI Audio           | 972   |
| pci:1002-aa90 | AMD         | Turks HDMI Audio [Radeon ... | 968   |
| pci:8086-5a98 | Intel       | Celeron N3350/Pentium N42... | 965   |
| pci:10de-0e0a | Nvidia      | GK104 HDMI Audio Controller  | 859   |
| pci:8086-3a6e | Intel       | 82801JD/DO (ICH10 Family)... | 779   |
| pci:10de-0e0b | Nvidia      | GK106 HDMI Audio Controller  | 773   |
| pci:10de-0fbb | Nvidia      | GM204 High Definition Aud... | 766   |
| pci:10de-0be2 | Nvidia      | GT216 HDMI Audio Controller  | 680   |
| pci:10de-0fba | Nvidia      | GM206 High Definition Aud... | 668   |
| pci:10de-10f8 | Nvidia      | TU104 HD Audio Controller    | 664   |
| pci:1002-aa60 | AMD         | Redwood HDMI Audio [Radeo... | 657   |
| pci:10de-0bee | Nvidia      | GF116 High Definition Aud... | 632   |
| pci:10de-0fb8 | Nvidia      | GP108 High Definition Aud... | 607   |
| pci:8086-1d20 | Intel       | C600/X79 series chipset H... | 600   |
| pci:1002-1714 | AMD         | BeaverCreek HDMI Audio [R... | 591   |
| pci:1002-970f | AMD         | RS880 HDMI Audio [Radeon ... | 582   |
| pci:1002-aa58 | AMD         | Juniper HDMI Audio [Radeo... | 566   |
| pci:10de-0ac0 | Nvidia      | MCP79 High Definition Audio  | 564   |
| pci:8086-8d20 | Intel       | C610/X99 series chipset H... | 522   |
| pci:1002-1308 | AMD         | Kaveri HDMI/DP Audio Cont... | 448   |
| pci:13f6-8788 | C-Media ... | CMI8788 [Oxygen HD Audio]    | 437   |
| pci:13f6-0111 | C-Media ... | CMI8738/CMI8768 PCI Audio    | 430   |
| pci:10de-0be9 | Nvidia      | GF106 High Definition Aud... | 401   |
| pci:10de-10ef | Nvidia      | GP102 HDMI Audio Controller  | 398   |
| pci:1002-960f | AMD         | RS780 HDMI Audio [Radeon ... | 395   |
| pci:8086-43c8 | Intel       | Tiger Lake-H HD Audio Con... | 390   |
| pci:1039-7502 | Silicon ... | Azalia Audio Controller      | 375   |
| pci:10de-0774 | Nvidia      | MCP72XE/MCP72P/MCP78U/MCP... | 344   |
| pci:10de-228b | Nvidia      | GA104 High Definition Aud... | 342   |
| pci:1102-0012 | Creative... | Sound Core3D [Sound Blast... | 341   |
| pci:10de-0e0c | Nvidia      | GF114 HDMI Audio Controller  | 327   |
| pci:8086-a3f0 | Intel       | Comet Lake PCH-V cAVS        | 327   |
| pci:10de-0be4 | Nvidia      | High Definition Audio Con... | 310   |
| pci:1002-aa88 | AMD         | Barts HDMI Audio [Radeon ... | 309   |
| pci:1002-aaa0 | AMD         | Tahiti HDMI Audio [Radeon... | 295   |
| pci:1002-aaf8 | AMD         | Vega 10 HDMI Audio [Radeo... | 291   |
| pci:8086-266e | Intel       | 82801FB/FBM/FR/FW/FRW (IC... | 274   |
| pci:8086-24d5 | Intel       | 82801EB/ER (ICH5/ICH5R) A... | 268   |
| pci:1002-ab28 | AMD         | Navi 21 HDMI Audio [Radeo... | 266   |
| pci:1002-aac0 | AMD         | Tobago HDMI Audio [Radeon... | 261   |
| pci:1102-0007 | Creative... | CA0106/CA0111 [SB Live!/A... | 258   |
| pci:1002-aa28 | AMD         | RV620 HDMI Audio [Radeon ... | 257   |
| pci:10de-228e | Nvidia      | Audio device                 | 257   |
| pci:1106-3288 | VIA Tech... | VX900/VT8xxx High Definit... | 245   |
| pci:10de-026c | Nvidia      | MCP51 High Definition Audio  | 243   |
| pci:1002-aa30 | AMD         | RV770 HDMI Audio [Radeon ... | 235   |
| pci:8086-2668 | Intel       | 82801FB/FBM/FR/FW/FRW (IC... | 225   |
| pci:1002-aac8 | AMD         | Hawaii HDMI Audio [Radeon... | 210   |
| pci:10de-1aef | Nvidia      | GA102 High Definition Aud... | 206   |
| pci:1102-0004 | Creative... | EMU10k2/CA0100/CA0102/CA1... | 204   |
| pci:1102-0002 | Creative... | EMU10k1 [Sound Blaster Li... | 198   |
| pci:10de-0371 | Nvidia      | MCP55 High Definition Audio  | 188   |
| pci:10de-10f7 | Nvidia      | TU102 High Definition Aud... | 185   |
| pci:1002-aa20 | AMD         | RV635 HDMI Audio [Radeon ... | 181   |
| pci:10de-0beb | Nvidia      | GF104 High Definition Aud... | 181   |
| pci:1106-3059 | VIA Tech... | VT8233/A/8235/8237 AC97 A... | 173   |
| pci:1002-aa08 | AMD         | RV630 HDMI Audio [Radeon ... | 168   |
| pci:8086-f0c8 | Intel       | Audio device                 | 166   |
| pci:1002-437b | AMD         | IXP SB4x0 High Definition... | 162   |
| pci:10de-055c | Nvidia      | MCP67 High Definition Audio  | 158   |
| pci:10de-0e09 | Nvidia      | GF110 High Definition Aud... | 145   |
| pci:10de-0fb0 | Nvidia      | GM200 High Definition Audio  | 145   |
| pci:10de-07fc | Nvidia      | MCP73 High Definition Audio  | 143   |
| pci:1102-0005 | Creative... | EMU20k1 [Sound Blaster X-... | 143   |
| pci:1002-aad8 | AMD         | Tonga HDMI Audio [Radeon ... | 142   |
| pci:10de-0059 | Nvidia      | CK804 AC'97 Audio Controller | 139   |
| pci:1002-aa50 | AMD         | Cypress HDMI Audio [Radeo... | 137   |
| pci:1039-7012 | Silicon ... | SiS7012 AC'97 Sound Contr... | 133   |
| pci:8086-269a | Intel       | 631xESB/632xESB High Defi... | 124   |
| pci:1102-000b | Creative... | EMU20k2 [Sound Blaster X-... | 122   |
| pci:1412-1724 | VIA Tech... | VT1720/24 [Envy24PT/HT] P... | 119   |
| pci:10de-0e1a | Nvidia      | GK110 High Definition Aud... | 117   |
| pci:1102-0008 | Creative... | CA0108/CA10300 [Sound Bla... | 117   |
| pci:10de-0d94 | Nvidia      | MCP89 High Definition Audio  | 116   |
| pci:8086-24c5 | Intel       | 82801DB/DBL/DBM (ICH4/ICH... | 115   |
| pci:10de-044a | Nvidia      | MCP65 High Definition Audio  | 114   |
| pci:1002-aa80 | AMD         | Cayman/Antilles HDMI Audi... | 113   |
| pci:8086-27de | Intel       | 82801G (ICH7 Family) AC'9... | 111   |
| pci:1002-aa10 | AMD         | RV610 HDMI Audio [Radeon ... | 100   |
| pci:10de-0be5 | Nvidia      | GF100 High Definition Aud... | 100   |
| pci:1002-4370 | AMD         | IXP SB400 AC'97 Audio Con... | 95    |
| pci:1002-aa18 | AMD         | RV670/680 HDMI Audio [Rad... | 93    |
| pci:8086-0d0c | Intel       | Crystal Well HD Audio Con... | 84    |
| pci:106b-1803 | Apple       | Audio Device                 | 81    |
| pci:10de-2291 | Nvidia      | Audio device                 | 75    |
| pci:8086-3b57 | Intel       | 5 Series/3400 Series Chip... | 73    |
| pci:1102-0009 | Creative... | CA0110 [Sound Blaster X-F... | 71    |
| pci:8086-4dc8 | Intel       | Jasper Lake HD Audio         | 70    |
| pci:8086-811b | Intel       | US15W/US15X/US15L/UL11L S... | 68    |
| pci:1002-ab20 | AMD         | Vega 20 HDMI Audio [Radeo... | 64    |
| pci:8086-7ad0 | Intel       | Alder Lake-S HD Audio Con... | 63    |
| pci:1412-1712 | VIA Tech... | ICE1712 [Envy24] PCI Mult... | 61    |
| pci:1002-7919 | AMD         | RS690 HDMI Audio [Radeon ... | 55    |
| pci:8086-a1f0 | Intel       | Lewisburg MROM 0             | 54    |
| pci:1274-5880 | Ensoniq     | 5880B / Creative Labs CT5880 | 41    |
| pci:1002-ab08 | AMD         | Polaris 22 HDMI Audio        | 40    |
| pci:10de-026b | Nvidia      | MCP51 AC97 Audio Controller  | 37    |
| pci:10de-00ea | Nvidia      | nForce3 250Gb AC'97 Audio... | 36    |
| pci:1274-1371 | Ensoniq     | ES1371/ES1373 / Creative ... | 28    |
| pci:10b9-5461 | ULi Elec... | HD Audio Controller          | 26    |
| pci:13f6-5011 | C-Media ... | CM8888 [Oxygen Express]      | 25    |
| pci:1002-aae8 | AMD         | Fiji HDMI/DP Audio [Radeo... | 22    |
| pci:8086-f1c8 | Intel       | Audio device                 | 22    |
| pci:10de-006a | Nvidia      | nForce2 AC97 Audio Contro... | 21    |
| pci:8086-22a8 | Intel       | Atom/Celeron/Pentium Proc... | 20    |
| pci:1002-0002 | AMD         | Bonaire HDMI Audio           | 18    |
| pci:8086-38c8 | Intel       | Audio device                 | 16    |
| pci:8086-2485 | Intel       | 82801CA/CAM AC'97 Audio C... | 14    |
| pci:1013-6003 | Cirrus L... | CS 4614/22/24/30 [Crystal... | 13    |
| pci:1102-0006 | Creative... | EMU10k1X / CA0103 [SB Liv... | 12    |
| pci:1002-4341 | AMD         | SB200 AC97 Audio Controller  | 11    |
| pci:8086-0f28 | Intel       | Atom Processor Z36xxx/Z37... | 11    |
| pci:8086-2445 | Intel       | 82801BA/BAM AC'97 Audio C... | 11    |
| pci:125d-1969 | ESS Tech... | ES1938/ES1946/ES1969 Solo... | 10    |
| pci:1002-aa00 | AMD         | R600 HDMI Audio [Radeon H... | 9     |
| pci:10b9-5455 | ULi Elec... | M5455 PCI AC-Link Control... | 9     |
| pci:12eb-0002 | Aureal S... | Vortex 2                     | 9     |
| pci:10de-00da | Nvidia      | nForce3 Audio                | 8     |
| pci:1102-0010 | Creative... | Creative Audio device        | 8     |
| pci:1319-0801 | Fortemedia  | Xwave QS3000A [FM801]        | 8     |
| pci:10de-10f2 | Nvidia      | GV100 TITAN V High Defini... | 6     |
| pci:10ee-3fc5 | Xilinx      | RME Hammerfall DSP           | 6     |
| pci:1106-9170 | VIA Tech... | High Definition Audio Con... | 6     |
| pci:1013-6005 | Cirrus L... | Crystal CS4281 PCI Audio     | 5     |
| pci:8086-51c8 | Intel       | Alder Lake PCH-P High Def... | 5     |
| pci:1073-0010 | Yamaha      | YMF-744B [DS-1S Audio Con... | 4     |
| pci:10b9-5451 | ULi Elec... | M5451 PCI AC-Link Control... | 4     |
| pci:10ee-3fc6 | Xilinx      | RME Hammerfall DSP MADI      | 4     |
| pci:19fe-7000 | ESI         | MAYA44e Controller           | 4     |
| pci:1002-793b | AMD         | RS600 HDMI Audio [Radeon ... | 3     |
| pci:104c-a106 | Texas In... | TMS320C6414 TMS320C6415 T... | 3     |
| pci:1073-000d | Yamaha      | YMF-724F [DS-1 Audio Cont... | 3     |
| pci:10de-006b | Nvidia      | nForce Audio Processing Unit | 3     |
| pci:125d-1988 | ESS Tech... | ES1988 Allegro-1             | 3     |
| pci:1274-5000 | Ensoniq     | ES1370 [AudioPCI]            | 3     |
| pci:12eb-0003 | Aureal S... | AU8810 Vortex Digital Aud... | 3     |
| pci:1d17-3288 | Zhaoxin     | ZX-100/ZX-D/ZX-E High Def... | 3     |
| pci:1d17-9144 | Zhaoxin     | ZX-E High Definition Audi... | 3     |
| pci:4005-4000 | Avance L... | ALS4000 Audio Chipset        | 3     |
| pci:8086-080a | Intel       | Moorestown Audio Ctrl        | 3     |
| pci:0014-7a07 | Loongson... | HDA (High Definition Audi... | 2     |
| pci:1002-9921 | AMD         | Liverpool HDMI/DP Audio C... | 2     |
| pci:1073-0004 | Yamaha      | YMF-724                      | 2     |
| pci:1073-0012 | Yamaha      | YMF-754 [DS-1E Audio Cont... | 2     |
| pci:10de-003a | Nvidia      | MCP04 AC'97 Audio Controller | 2     |
| pci:10de-008a | Nvidia      | MCP2S AC'97 Audio Controller | 2     |
| pci:10de-0fb1 | Nvidia      | Audio device                 | 2     |
| pci:10ee-3fc4 | Xilinx      | RME Digi9652 (Hammerfall)    | 2     |
| pci:1106-3058 | VIA Tech... | VT82C686 AC97 Audio Contr... | 2     |
| pci:125d-1978 | ESS Tech... | ES1978 Maestro 2E            | 2     |
| pci:12eb-0001 | Aureal S... | Vortex 1                     | 2     |
| pci:8086-1bc8 | Intel       | Audio device                 | 2     |
| pci:8086-98c8 | Intel       | HD Graphics SGPC             | 2     |
| pci:0045-c061 | Unknown     | Audio device                 | 1     |
| pci:1002-154d | AMD         | Audio device                 | 1     |
| pci:1002-abf8 | AMD         | Audio device                 | 1     |
| pci:1022-2093 | AMD         | CS5536 [Geode companion] ... | 1     |
| pci:1023-2000 | Trident ... | 4DWave DX                    | 1     |
| pci:104c-b801 | Texas In... | Multimedia audio controller  | 1     |
| pci:1073-1000 | Yamaha      | SW1000XG [XG Factory]        | 1     |
| pci:10de-2288 | Nvidia      | Audio device                 | 1     |
| pci:10ee-3fc1 | Xilinx      | RME Digi96/8                 | 1     |
| pci:10ee-3fc3 | Xilinx      | RME Digi96/8 Pad             | 1     |
| pci:11af-ee40 | Avid Tec... | Digidesign Audiomedia III    | 1     |
| pci:125d-1968 | ESS Tech... | ES1968 Maestro 2             | 1     |
| pci:125d-1998 | ESS Tech... | ES1983S Maestro-3i PCI Au... | 1     |
| pci:127a-4310 | Rockwell... | Riptide Bus / Firmware Do... | 1     |
| pci:137a-0001 | Mark of ... | PCI-324 Audiowire Interface  | 1     |
| pci:137a-0005 | Mark of ... | Multimedia audio controller  | 1     |
| pci:13e6-0111 | Argosy r... | Argosy Multimedia audio c... | 1     |
| pci:13f2-0111 | Ford Mic... |                              | 1     |
| pci:1412-1624 | VIA Tech... | Multimedia audio controller  | 1     |
| pci:1c67-0101 | Unknown     | Multimedia audio controller  | 1     |
| pci:1fff-800a | MCST        | HD Audio                     | 1     |
| pci:3388-1018 | Hint        | Audiotrak INCA88             | 1     |
| pci:3388-1019 | Hint        | Miditrak 2120                | 1     |
| pci:6549-2200 | Teradici    | Audio device                 | 1     |
| pci:8086-119a | Intel       | Multimedia audio controller  | 1     |
| pci:8086-1a98 | Intel       | Smart Sound Technology (I... | 1     |
| pci:8086-2415 | Intel       | 82801AA AC'97 Audio Contr... | 1     |
| pci:8086-25a6 | Intel       | 6300ESB AC'97 Audio Contr... | 1     |
| pci:8086-2698 | Intel       | 631xESB/632xESB AC '97 Au... | 1     |
| pci:8086-490d | Intel       | HD Graphics D3COLD           | 1     |
| pci:8086-9d72 | Intel       | 300 Series Chipset Smart ... | 1     |
| pci:8086-9d74 | Intel       | 300 Series Chipset Smart ... | 1     |

### Storage/ata (PCI)

Total devices: 108623

| ID            | MFG         | Name                         | Count |
|---------------|-------------|------------------------------|-------|
| pci:1022-7901 | AMD         | FCH SATA Controller [AHCI... | 11145 |
| pci:8086-1e03 | Intel       | 7 Series Chipset Family 6... | 7052  |
| pci:8086-9d03 | Intel       | Sunrise Point-LP SATA Con... | 6748  |
| pci:8086-1c03 | Intel       | 6 Series/C200 Series Chip... | 5162  |
| pci:1002-4391 | AMD         | SB7x0/SB8x0/SB9x0 SATA Co... | 4355  |
| pci:8086-8c02 | Intel       | 8 Series/C220 Series Chip... | 3973  |
| pci:1022-7801 | AMD         | FCH SATA Controller [AHCI... | 3486  |
| pci:8086-2929 | Intel       | 82801IBM/IEM (ICH9M/ICH9M... | 3344  |
| pci:8086-1c02 | Intel       | 6 Series/C200 Series Chip... | 3282  |
| pci:1022-43c8 | AMD         | 400 Series Chipset SATA C... | 3197  |
| pci:8086-9c03 | Intel       | 8 Series SATA Controller ... | 3155  |
| pci:1002-4390 | AMD         | SB7x0/SB8x0/SB9x0 SATA Co... | 2980  |
| pci:8086-a102 | Intel       | Q170/Q150/B150/H170/H110/... | 2972  |
| pci:8086-1e02 | Intel       | 7 Series/C210 Series Chip... | 2512  |
| pci:8086-3b29 | Intel       | 5 Series/3400 Series Chip... | 2426  |
| pci:1b21-0612 | ASMedia ... | ASM1062 Serial ATA Contro... | 2335  |
| pci:8086-9c83 | Intel       | Wildcat Point-LP SATA Con... | 2258  |
| pci:8086-a282 | Intel       | 200 Series PCH SATA contr... | 2034  |
| pci:8086-8c03 | Intel       | 8 Series/C220 Series Chip... | 2023  |
| pci:8086-a353 | Intel       | Cannon Lake Mobile PCH SA... | 2017  |
| pci:8086-2829 | Intel       | 82801HM/HEM (ICH8M/ICH8M-... | 1807  |
| pci:8086-a352 | Intel       | Cannon Lake PCH SATA AHCI... | 1568  |
| pci:8086-0f23 | Intel       | Atom Processor E3800 Seri... | 1563  |
| pci:1022-7804 | AMD         | FCH SATA Controller [AHCI... | 1422  |
| pci:8086-a103 | Intel       | HM170/QM170 Chipset SATA ... | 1415  |
| pci:8086-31e3 | Intel       | Celeron/Pentium Silver Pr... | 1312  |
| pci:8086-3b2f | Intel       | 5 Series/3400 Series Chip... | 1237  |
| pci:8086-27c1 | Intel       | NM10/ICH7 Family SATA Con... | 1224  |
| pci:8086-22a3 | Intel       | Atom/Celeron/Pentium Proc... | 1151  |
| pci:8086-9dd3 | Intel       | Cannon Point-LP SATA Cont... | 1139  |
| pci:1022-43eb | AMD         | 500 Series Chipset SATA C... | 973   |
| pci:8086-8c82 | Intel       | 9 Series Chipset Family S... | 964   |
| pci:8086-5ae3 | Intel       | Celeron N3350/Pentium N42... | 948   |
| pci:8086-02d3 | Intel       | Comet Lake SATA AHCI Cont... | 924   |
| pci:1022-43b7 | AMD         | 300 Series Chipset SATA C... | 903   |
| pci:1022-43b8 | AMD         | FCH SATA Controller D        | 869   |
| pci:8086-3a22 | Intel       | 82801JI (ICH10 Family) SA... | 843   |
| pci:8086-3b22 | Intel       | 5 Series/3400 Series Chip... | 670   |
| pci:1002-4380 | AMD         | SB600 Non-Raid-5 SATA        | 650   |
| pci:8086-1d02 | Intel       | C600/X79 series chipset 6... | 617   |
| pci:1022-7800 | AMD         | FCH SATA Controller [IDE ... | 601   |
| pci:8086-27c5 | Intel       | 82801GBM/GHM (ICH7-M Fami... | 525   |
| pci:8086-8d02 | Intel       | C610/X99 series chipset 6... | 494   |
| pci:1022-43b5 | AMD         | X370 Series Chipset SATA ... | 473   |
| pci:1b4b-9172 | Marvell ... | 88SE9172 SATA 6Gb/s Contr... | 457   |
| pci:8086-3a02 | Intel       | 82801JD/DO (ICH10 Family)... | 454   |
| pci:1022-7904 | AMD         | FCH SATA Controller [AHCI... | 453   |
| pci:10de-0ab9 | Nvidia      | MCP79 AHCI Controller        | 435   |
| pci:8086-8d62 | Intel       | C610/X99 series chipset s... | 423   |
| pci:8086-a0d3 | Intel       | Tiger Lake-LP SATA Contro... | 396   |
| pci:8086-34d3 | Intel       | Ice Lake-LP SATA Controll... | 394   |
| pci:8086-06d3 | Intel       | 400 Series Chipset Family... | 384   |
| pci:8086-43d2 | Intel       | 500 Series Chipset Family... | 338   |
| pci:8086-06d2 | Intel       | Comet Lake SATA AHCI Cont... | 333   |
| pci:8086-2922 | Intel       | 82801IR/IO/IH (ICH9R/DO/D... | 329   |
| pci:197b-2362 | JMicron ... | JMB362 SATA Controller       | 300   |
| pci:144d-a801 | Samsung ... | Electronics SATA controller  | 299   |
| pci:8086-a382 | Intel       | 400 Series Chipset Family... | 293   |
| pci:1b4b-9215 | Marvell ... | 88SE9215 PCIe 2.0 x1 4-po... | 186   |
| pci:1022-43b6 | AMD         | X399 Series Chipset SATA ... | 184   |
| pci:1b4b-9230 | Marvell ... | 88SE9230 PCIe 2.0 x2 4-po... | 146   |
| pci:1b4b-9130 | Marvell ... | 88SE9128 PCIe SATA 6 Gb/s... | 145   |
| pci:197b-2360 | JMicron ... | JMB360 AHCI Controller       | 130   |
| pci:10de-0ad4 | Nvidia      | MCP78S [GeForce 8200] AHC... | 114   |
| pci:8086-a1d2 | Intel       | C620 Series Chipset Famil... | 110   |
| pci:10de-0d88 | Nvidia      | MCP89 SATA Controller (AH... | 108   |
| pci:8086-a182 | Intel       | C620 Series Chipset Famil... | 106   |
| pci:144d-1600 | Samsung ... | Apple PCIe SSD               | 105   |
| pci:8086-2681 | Intel       | 631xESB/632xESB SATA AHCI... | 95    |
| pci:1b4b-9123 | Marvell ... | 88SE9123 PCIe SATA 6.0 Gb... | 93    |
| pci:1b4b-9120 | Marvell ... | 88SE9120 SATA 6Gb/s Contr... | 85    |
| pci:1b4b-9183 | Marvell ... | 88SS9183 PCIe SSD Controller | 71    |
| pci:8086-7ae2 | Intel       | Alder Lake-S PCH SATA Con... | 66    |
| pci:1002-4394 | AMD         | SB7x0/SB8x0/SB9x0 SATA Co... | 65    |
| pci:1b4b-9128 | Marvell ... | 88SE9128 PCIe SATA 6 Gb/s... | 65    |
| pci:10de-07f4 | Nvidia      | GeForce 7100/nForce 630i ... | 63    |
| pci:8086-43d3 | Intel       | 500 Series Chipset Family... | 62    |
| pci:8086-2923 | Intel       | 82801IB (ICH9) 4 port SAT... | 55    |
| pci:1b21-0625 | ASMedia ... | 106x SATA/RAID Controller    | 52    |
| pci:10de-0ab8 | Nvidia      | MCP79 AHCI Controller        | 39    |
| pci:8086-2821 | Intel       | 82801HR/HO/HH (ICH8R/DO/D... | 37    |
| pci:1039-1185 | Silicon ... | AHCI IDE Controller (0106)   | 30    |
| pci:8086-4dd3 | Intel       | Jasper Lake SATA AHCI Con... | 29    |
| pci:2646-0010 | Kingston... | HyperX Predator PCIe AHCI... | 28    |
| pci:8086-2824 | Intel       | 82801HB (ICH8) 4 port SAT... | 25    |
| pci:1022-7900 | AMD         | FCH SATA Controller [IDE ... | 24    |
| pci:1b4b-9235 | Marvell ... | 88SE9235 PCIe 2.0 x2 4-po... | 21    |
| pci:1b4b-9182 | Marvell ... | 88SE9182 PCIe 2.0 x2 2-po... | 19    |
| pci:1c28-0122 | Lite-On ... | M6e PCI Express SSD [Marv... | 18    |
| pci:144d-a800 | Samsung ... | XP941 PCIe SSD               | 17    |
| pci:1b21-1064 | ASMedia ... | SATA controller              | 17    |
| pci:1095-3112 | Silicon ... | SiI 3112 [SATALink/SATARa... | 16    |
| pci:10de-0ad5 | Nvidia      | nForce SATA Controller       | 13    |
| pci:8086-1f32 | Intel       | Atom processor C2000 AHCI... | 13    |
| pci:10de-044d | Nvidia      | MCP65 AHCI Controller        | 10    |
| pci:1b21-1166 | ASMedia ... | SATA controller              | 10    |
| pci:8086-1f22 | Intel       | Atom processor C2000 AHCI... | 10    |
| pci:1b4b-9125 | Marvell ... | 88SE9125 PCIe SATA 6.0 Gb... | 9     |
| pci:10de-0554 | Nvidia      | MCP67 AHCI Controller        | 8     |
| pci:10de-0584 | Nvidia      | SATA controller              | 7     |
| pci:19e5-a235 | Huawei T... | HiSilicon AHCI HBA           | 7     |
| pci:1b21-0622 | ASMedia ... | 106x SATA/RAID Controller    | 7     |
| pci:197b-0585 | JMicron ... | JMB58x AHCI SATA controller  | 6     |
| pci:8086-19c2 | Intel       | Atom Processor C3000 Seri... | 6     |
| pci:8086-8c83 | Intel       | 9 Series Chipset Family S... | 6     |
| pci:11ab-6141 | Marvell ... | 88SE614x SATA II PCI-E co... | 5     |
| pci:1b4b-9170 | Marvell ... | 88SE9170 PCIe 2.0 x1 2-po... | 5     |
| pci:1b4b-9220 | Marvell ... | 88SE9220 PCIe 2.0 x2 2-po... | 5     |
| pci:8086-19b2 | Intel       | Atom Processor C3000 Seri... | 5     |
| pci:10de-0585 | Nvidia      | SATA controller              | 4     |
| pci:1179-010b | Toshiba ... | Toshiba America Info SATA... | 4     |
| pci:1d17-9083 | Zhaoxin     | ZX-100/ZX-200/ZX-E StorX ... | 3     |
| pci:8086-0816 | Intel       | SM35 Chipset SATA AHCI Co... | 3     |
| pci:0014-7a08 | Loongson... | SATA AHCI Controller         | 2     |
| pci:10de-0555 | Nvidia      | MCP67 SATA Controller        | 2     |
| pci:14a4-0224 | Lite-On ... | SATA controller              | 2     |
| pci:1b4b-9171 | Marvell ... | 88SE9171 SATA 6G Controller  | 2     |
| pci:8086-1ba2 | Intel       | SATA controller              | 2     |
| pci:8086-3b23 | Intel       | 5 Series/3400 Series Chip... | 2     |
| pci:1101-1622 | Initio      | INI-1623 PCI SATA-II Cont... | 1     |
| pci:1b4b-9186 | Marvell ... | 91xx SATA 6G Controller      | 1     |
| pci:1fff-801a | MCST        | SATA                         | 1     |

### Storage/ide (PCI)

Total devices: 49102

| ID            | MFG         | Name                         | Count |
|---------------|-------------|------------------------------|-------|
| pci:8086-27c0 | Intel       | NM10/ICH7 Family SATA Con... | 4580  |
| pci:1002-439c | AMD         | SB7x0/SB8x0/SB9x0 IDE Con... | 4371  |
| pci:8086-27df | Intel       | 82801G (ICH7 Family) IDE ... | 4091  |
| pci:8086-2850 | Intel       | 82801HM/HEM (ICH8M/ICH8M-... | 2183  |
| pci:8086-1c08 | Intel       | 6 Series/C200 Series Chip... | 1874  |
| pci:8086-1c00 | Intel       | 6 Series/C200 Series Chip... | 1871  |
| pci:10de-03f6 | Nvidia      | MCP61 SATA Controller        | 1549  |
| pci:197b-2363 | JMicron ... | JMB363 SATA/IDE Controller   | 1418  |
| pci:10de-03ec | Nvidia      | MCP61 IDE                    | 1334  |
| pci:8086-3a20 | Intel       | 82801JI (ICH10 Family) 4 ... | 1079  |
| pci:8086-2926 | Intel       | 82801I (ICH9 Family) 2 po... | 1065  |
| pci:8086-3a26 | Intel       | 82801JI (ICH10 Family) 2 ... | 1021  |
| pci:1022-780c | AMD         | FCH IDE Controller           | 873   |
| pci:8086-27c4 | Intel       | 82801GBM/GHM (ICH7-M Fami... | 866   |
| pci:197b-2368 | JMicron ... | JMB368 IDE controller        | 749   |
| pci:8086-3b20 | Intel       | 5 Series/3400 Series Chip... | 742   |
| pci:8086-3b26 | Intel       | 5 Series/3400 Series Chip... | 705   |
| pci:8086-2920 | Intel       | 82801IR/IO/IH (ICH9R/DO/D... | 651   |
| pci:1002-438c | AMD         | SB600 IDE                    | 648   |
| pci:8086-2e16 | Intel       | 4 Series Chipset PT IDER ... | 630   |
| pci:8086-2828 | Intel       | 82801HM/HEM (ICH8M/ICH8M-... | 570   |
| pci:8086-1e00 | Intel       | 7 Series/C210 Series Chip... | 568   |
| pci:8086-1e08 | Intel       | 7 Series/C210 Series Chip... | 568   |
| pci:1039-5513 | Silicon ... | 5513 IDE Controller          | 484   |
| pci:8086-2820 | Intel       | 82801H (ICH8 Family) 4 po... | 465   |
| pci:8086-2921 | Intel       | 82801IB (ICH9) 2 port SAT... | 446   |
| pci:1106-0571 | VIA Tech... | VT82C586A/B/VT82C686/A/B/... | 421   |
| pci:8086-1e01 | Intel       | 7 Series Chipset Family 4... | 419   |
| pci:8086-1e09 | Intel       | 7 Series Chipset Family 2... | 417   |
| pci:8086-2928 | Intel       | 82801IBM/IEM (ICH9M/ICH9M... | 412   |
| pci:8086-2825 | Intel       | 82801HR/HO/HH (ICH8R/DO/D... | 399   |
| pci:11ab-6121 | Marvell ... | 88SE6111/6121 SATA II / P... | 397   |
| pci:8086-266f | Intel       | 82801FB/FBM/FR/FW/FRW (IC... | 369   |
| pci:1039-1183 | Silicon ... | SATA Controller / IDE mode   | 351   |
| pci:8086-292d | Intel       | 82801IBM/IEM (ICH9M/ICH9M... | 330   |
| pci:8086-1c01 | Intel       | 6 Series/C200 Series Chip... | 315   |
| pci:8086-3b2d | Intel       | 5 Series/3400 Series Chip... | 302   |
| pci:1106-0415 | VIA Tech... | VT6415 PATA IDE Host Cont... | 300   |
| pci:10de-0759 | Nvidia      | MCP78S [GeForce 8200] IDE    | 297   |
| pci:8086-1c09 | Intel       | 6 Series/C200 Series Chip... | 287   |
| pci:10de-0266 | Nvidia      | MCP51 Serial ATA Controller  | 286   |
| pci:11ab-6101 | Marvell ... | 88SE6101/6102 single-port... | 284   |
| pci:8086-29b6 | Intel       | 82Q35 Express PT IDER Con... | 281   |
| pci:8086-24db | Intel       | 82801EB/ER (ICH5/ICH5R) I... | 263   |
| pci:1002-4376 | AMD         | IXP SB4x0 IDE Controller     | 259   |
| pci:10de-0265 | Nvidia      | MCP51 IDE                    | 255   |
| pci:8086-3a06 | Intel       | 82801JD/DO (ICH10 Family)... | 239   |
| pci:8086-3a00 | Intel       | 82801JD/DO (ICH10 Family)... | 230   |
| pci:10de-037f | Nvidia      | MCP55 SATA Controller        | 224   |
| pci:10de-036e | Nvidia      | MCP55 IDE                    | 219   |
| pci:10de-0ad0 | Nvidia      | MCP78S [GeForce 8200] SAT... | 213   |
| pci:8086-3b66 | Intel       | 5 Series/3400 Series Chip... | 213   |
| pci:8086-269e | Intel       | 631xESB/632xESB IDE Contr... | 199   |
| pci:8086-24d1 | Intel       | 82801EB (ICH5) SATA Contr... | 195   |
| pci:10de-0055 | Nvidia      | CK804 Serial ATA Controller  | 194   |
| pci:10de-0054 | Nvidia      | CK804 Serial ATA Controller  | 193   |
| pci:10de-0053 | Nvidia      | CK804 IDE                    | 190   |
| pci:8086-3b28 | Intel       | 5 Series/3400 Series Chip... | 185   |
| pci:8086-2651 | Intel       | 82801FB/FW (ICH6/ICH6W) S... | 184   |
| pci:8086-2a46 | Intel       | Mobile 4 Series Chipset P... | 182   |
| pci:10de-0267 | Nvidia      | MCP51 Serial ATA Controller  | 176   |
| pci:1002-4379 | AMD         | IXP SB4x0 Serial ATA Cont... | 171   |
| pci:10de-0550 | Nvidia      | MCP67 AHCI Controller        | 159   |
| pci:197b-2361 | JMicron ... | JMB361 AHCI/IDE              | 159   |
| pci:10de-0560 | Nvidia      | MCP67 IDE Controller         | 153   |
| pci:8086-8c00 | Intel       | 8 Series/C220 Series Chip... | 143   |
| pci:1b4b-91a3 | Marvell ... | 88SE91A3 SATA-600 Controller | 140   |
| pci:8086-3b2e | Intel       | 5 Series/3400 Series Chip... | 134   |
| pci:10de-056c | Nvidia      | MCP73 IDE Controller         | 131   |
| pci:1106-0591 | VIA Tech... | VT8237A SATA 2-Port Contr... | 130   |
| pci:8086-1d3c | Intel       | C600/X79 series chipset I... | 129   |
| pci:8086-2653 | Intel       | 82801FBM (ICH6M) SATA Con... | 127   |
| pci:10de-0448 | Nvidia      | MCP65 IDE                    | 115   |
| pci:10de-045d | Nvidia      | MCP65 SATA Controller        | 109   |
| pci:1b4b-917a | Marvell ... | 88SE9172 SATA III 6Gb/s R... | 104   |
| pci:1b4b-91a4 | Marvell ... | 88SE912x IDE Controller      | 95    |
| pci:8086-1c3c | Intel       | 6 Series/C200 Series Chip... | 94    |
| pci:8086-2a06 | Intel       | Mobile PM965/GM965 PT IDE... | 88    |
| pci:8086-8c08 | Intel       | 8 Series/C220 Series Chip... | 78    |
| pci:1b4b-91a0 | Marvell ... | 88SE912x SATA 6Gb/s Contr... | 75    |
| pci:1b21-0611 | ASMedia ... | ASM1061 SATA IDE Controller  | 72    |
| pci:8086-2680 | Intel       | 631xESB/632xESB/3100 Chip... | 71    |
| pci:1283-8213 | Integrat... | IT8213 IDE Controller        | 70    |
| pci:8086-24ca | Intel       | 82801DBM (ICH4-M) IDE Con... | 70    |
| pci:10de-07f0 | Nvidia      | MCP73 SATA Controller (ID... | 69    |
| pci:8086-0f21 | Intel       | Atom Processor E3800 Seri... | 68    |
| pci:8086-811a | Intel       | US15W/US15X/US15L/UL11L S... | 68    |
| pci:10de-0ab5 | Nvidia      | MCP79 SATA Controller        | 67    |
| pci:197b-0368 | JMicron ... | JMB368 IDE controller        | 65    |
| pci:8086-1d00 | Intel       | C600/X79 series chipset 4... | 60    |
| pci:8086-8c01 | Intel       | 8 Series Chipset Family 4... | 60    |
| pci:8086-8c09 | Intel       | 8 Series/C220 Series Chip... | 60    |
| pci:1106-5337 | VIA Tech... | Serial ATA Controller        | 57    |
| pci:8086-24cb | Intel       | 82801DB (ICH4) IDE Contro... | 51    |
| pci:8086-2652 | Intel       | 82801FR/FRW (ICH6R/ICH6RW... | 51    |
| pci:1106-5372 | VIA Tech... | VT8237/8251 Serial ATA Co... | 48    |
| pci:10de-00e5 | Nvidia      | CK8S Parallel ATA Control... | 44    |
| pci:10de-00e3 | Nvidia      | nForce3 Serial ATA Contro... | 42    |
| pci:8086-2996 | Intel       | 82Q963/Q965 PT IDER Contr... | 42    |
| pci:1002-437a | AMD         | IXP SB400 Serial ATA Cont... | 39    |
| pci:1039-0180 | Silicon ... | RAID bus controller 180 S... | 38    |
| pci:10b9-5229 | ULi Elec... | M5229 IDE                    | 38    |
| pci:8086-1d08 | Intel       | C600/X79 series chipset 2... | 38    |
| pci:1b4b-914d | Marvell ... | 88SE914D SATA-600 Controller | 31    |
| pci:8086-8d3c | Intel       | C610/X99 series chipset I... | 30    |
| pci:8086-a1bc | Intel       | C620 Series Chipset Famil... | 25    |
| pci:10de-0065 | Nvidia      | nForce2 IDE                  | 21    |
| pci:10de-0ab4 | Nvidia      | MCP79 SATA Controller        | 18    |
| pci:8086-244b | Intel       | 82801BA IDE U100 Controller  | 15    |
| pci:1106-3349 | VIA Tech... | VT8251 AHCI/SATA 4-Port C... | 14    |
| pci:8086-248a | Intel       | 82801CAM IDE U100 Controller | 14    |
| pci:1106-9001 | VIA Tech... | VX900 Series Serial-ATA C... | 13    |
| pci:8086-8c80 | Intel       | 9 Series Chipset Family S... | 13    |
| pci:1002-4349 | AMD         | SB200 IDE Controller         | 12    |
| pci:8086-1e3c | Intel       | 7 Series/C210 Series Chip... | 12    |
| pci:8086-8c88 | Intel       | 9 Series Chipset Family S... | 12    |
| pci:10b9-5288 | ULi Elec... | ULi M5288 SATA               | 11    |
| pci:1b21-0624 | ASMedia ... | 106x SATA/RAID Controller    | 11    |
| pci:10de-0d85 | Nvidia      | MCP89 SATA Controller        | 10    |
| pci:8086-7111 | Intel       | 82371AB/EB/MB PIIX4 IDE      | 9     |
| pci:1039-0181 | Silicon ... | SATA                         | 8     |
| pci:10de-00d5 | Nvidia      | nForce3 IDE                  | 8     |
| pci:1106-5324 | VIA Tech... | CX700M2/VX700/VX800/820-S... | 8     |
| pci:11ab-6145 | Marvell ... | 88SE6145 SATA II PCI-E co... | 8     |
| pci:1166-0214 | Broadcom    | BCM5785 [HT1000] IDE         | 7     |
| pci:8086-8c3c | Intel       | 8 Series/C220 Series Chip... | 7     |
| pci:10de-00ee | Nvidia      | nForce3 Serial ATA Contro... | 6     |
| pci:8086-8d00 | Intel       | C610/X99 series chipset 4... | 6     |
| pci:1039-0183 | Silicon ... | Silicon Integrated IDE in... | 5     |
| pci:8086-25a2 | Intel       | 6300ESB PATA Storage Cont... | 5     |
| pci:1b4b-918a | Marvell ... | 91xx SATA 6G Controller      | 4     |
| pci:1b4b-91b0 | Marvell ... | 88SE91B0 SATA 6G Controller  | 4     |
| pci:8086-25a3 | Intel       | 6300ESB SATA Storage Cont... | 4     |
| pci:1166-024b | Broadcom    | BCM5785 [HT1000] SATA (PA... | 3     |
| pci:8086-2e26 | Intel       | 4 Series Chipset PT IDER ... | 3     |
| pci:8086-8d08 | Intel       | C610/X99 series chipset 2... | 3     |
| pci:8086-8d60 | Intel       | C610/X99 series chipset s... | 3     |
| pci:8086-9c3c | Intel       | 8 Series HECI IDER           | 3     |
| pci:1022-7469 | AMD         | AMD-8111 IDE                 | 2     |
| pci:1039-0182 | Silicon ... | 182 SATA/RAID Controller     | 2     |
| pci:10de-0035 | Nvidia      | MCP04 IDE                    | 2     |
| pci:10de-0036 | Nvidia      | MCP04 Serial ATA Controller  | 2     |
| pci:10de-003e | Nvidia      | MCP04 Serial ATA Controller  | 2     |
| pci:10de-0085 | Nvidia      | MCP2A IDE                    | 2     |
| pci:10de-008e | Nvidia      | nForce2 Serial ATA Contro... | 2     |
| pci:1166-0211 | Broadcom    | OSB4 IDE Controller          | 2     |
| pci:1166-0212 | Broadcom    | CSB5 IDE Controller          | 2     |
| pci:1166-0240 | Broadcom    | K2 SATA                      | 2     |
| pci:8086-108d | Intel       | Active Management Technol... | 2     |
| pci:8086-248b | Intel       | 82801CA Ultra ATA Storage... | 2     |
| pci:1022-209a | AMD         | CS5536 [Geode companion] IDE | 1     |
| pci:1022-7441 | AMD         | AMD-768 [Opus] IDE           | 1     |
| pci:1095-0646 | Silicon ... | PCI0646                      | 1     |
| pci:1106-5287 | VIA Tech... | VT8251 Serial ATA Controller | 1     |
| pci:1106-c409 | VIA Tech... | VX855/VX875 EIDE Controller  | 1     |
| pci:197b-2366 | JMicron ... | JMB366 AHCI/IDE              | 1     |
| pci:1fff-800b | MCST        | IDE controller               | 1     |
| pci:8086-2411 | Intel       | 82801AA IDE Controller       | 1     |
| pci:8086-244a | Intel       | 82801BAM IDE U100 Controller | 1     |

### Storage/nvme (PCI)

Total devices: 28926

| ID            | MFG         | Name                         | Count |
|---------------|-------------|------------------------------|-------|
| pci:144d-a808 | Samsung ... | NVMe SSD Controller SM981... | 6096  |
| pci:144d-a804 | Samsung ... | NVMe SSD Controller SM961... | 1606  |
| pci:144d-a809 | Samsung ... | NVMe SSD Controller 980      | 1254  |
| pci:8086-f1a8 | Intel       | SSD 660P Series              | 1150  |
| pci:15b7-5006 | Sandisk     | WD Black SN750 / PC SN730... | 1109  |
| pci:1987-5012 | Phison E... | E12 NVMe Controller          | 948   |
| pci:15b7-5009 | Sandisk     | WD Blue SN550 NVMe SSD       | 934   |
| pci:1e0f-0001 | KIOXIA      | Non-Volatile memory contr... | 677   |
| pci:1c5c-1327 | SK Hynix    | BC501 NVMe Solid State Drive | 666   |
| pci:15b7-5003 | Sandisk     | WD Blue SN500 / PC SN520 ... | 652   |
| pci:15b7-5002 | Sandisk     | WD Black 2018/SN750 / PC ... | 613   |
| pci:126f-2263 | Silicon ... | SM2263EN/SM2263XT SSD Con... | 611   |
| pci:1179-011a | Toshiba ... | XG6 NVMe SSD Controller      | 572   |
| pci:144d-a80a | Samsung ... | NVMe SSD Controller PM9A1... | 539   |
| pci:1cc1-8201 | ADATA Te... | XPG SX8200 Pro PCIe Gen3x... | 536   |
| pci:2646-2263 | Kingston... | A2000 NVMe SSD               | 482   |
| pci:1c5c-1339 | SK Hynix    | BC511                        | 463   |
| pci:1179-0116 | Toshiba ... | Toshiba America Info Non-... | 437   |
| pci:1c5c-174a | SK Hynix    | Gold P31 SSD                 | 434   |
| pci:1179-0113 | Toshiba ... | BG3 NVMe SSD Controller      | 426   |
| pci:144d-a802 | Samsung ... | NVMe SSD Controller SM951... | 422   |
| pci:1987-5016 | Phison E... | E16 PCIe4 NVMe Controller    | 419   |
| pci:8086-f1a6 | Intel       | SSD Pro 7600p/760p/E 6100... | 416   |
| pci:2646-5008 | Kingston... | U-SNS8154P3 NVMe SSD         | 380   |
| pci:c0a9-2263 | Micron/C... | P1 NVMe PCIe SSD             | 360   |
| pci:8086-f1a5 | Intel       | SSD 600P Series              | 289   |
| pci:1344-5410 | Micron T... | Non-Volatile memory contr... | 268   |
| pci:1c5c-1527 | SK Hynix    | PC401 NVMe Solid State Dr... | 244   |
| pci:1c5c-1627 | SK Hynix    | Non-Volatile memory contr... | 240   |
| pci:126f-2262 | Silicon ... | SM2262/SM2262EN SSD Contr... | 229   |
| pci:1344-5405 | Micron T... | Non-Volatile memory contr... | 222   |
| pci:15b7-5005 | Sandisk     | PC SN520 NVMe SSD            | 220   |
| pci:c0a9-540a | Micron/C... | P2 NVMe PCIe SSD             | 217   |
| pci:1c5c-1639 | SK Hynix    | Non-Volatile memory contr... | 213   |
| pci:1987-5013 | Phison E... | PS5013 E13 NVMe Controller   | 212   |
| pci:8086-0975 | Intel       | Non-Volatile memory contr... | 196   |
| pci:1179-0115 | Toshiba ... | XG4 NVMe SSD Controller      | 194   |
| pci:15b7-5008 | Sandisk     | Non-Volatile memory contr... | 189   |
| pci:2646-500c | Kingston... | Technology Company Non-Vo... | 184   |
| pci:10ec-5762 | Realtek ... | RTS5763DL NVMe SSD Contro... | 169   |
| pci:1344-5404 | Micron T... | Non-Volatile memory contr... | 155   |
| pci:10ec-5763 | Realtek ... | Realtek Non-Volatile memo... | 142   |
| pci:1e95-9100 | Solid St... | Non-Volatile memory contr... | 128   |
| pci:15b7-5011 | Sandisk     | WD PC SN810 / Black SN850... | 118   |
| pci:c0a9-5403 | Micron/C... | NVMe Controller              | 109   |
| pci:15b7-5004 | Sandisk     | PC SN520 NVMe SSD            | 108   |
| pci:1cc1-33f3 | ADATA Te... | Non-Volatile memory contr... | 100   |
| pci:1987-5008 | Phison E... | NVMe Storage Controller      | 98    |
| pci:15b7-5007 | Sandisk     | Non-Volatile memory contr... | 97    |
| pci:106b-2001 | Apple       | S1X NVMe Controller          | 96    |
| pci:1cc4-5008 | Union Me... | Non-Volatile memory contr... | 94    |
| pci:1179-010f | Toshiba ... | NVMe Controller              | 89    |
| pci:106b-2005 | Apple       | ANS2 NVMe Controller         | 81    |
| pci:8086-2522 | Intel       | NVMe Optane Memory Series    | 76    |
| pci:1987-5007 | Phison E... | E7 NVMe Controller           | 73    |
| pci:2646-500d | Kingston... | OM3PDP3 NVMe SSD             | 72    |
| pci:1cc1-33f8 | ADATA Te... | Non-Volatile memory contr... | 70    |
| pci:8086-f1aa | Intel       | Non-Volatile memory contr... | 59    |
| pci:15b7-5001 | Sandisk     | WD Black NVMe SSD            | 55    |
| pci:144d-a806 | Samsung ... | Electronics Non-Volatile ... | 54    |
| pci:1cc4-6202 | Union Me... | Non-Volatile memory contr... | 54    |
| pci:2646-500e | Kingston... | SNVS2000G [NV1 NVMe PCIe ... | 53    |
| pci:1bb1-5016 | Seagate ... | FireCuda 520 SSD             | 52    |
| pci:c0a9-5412 | Micron/C... | Non-Volatile memory contr... | 52    |
| pci:14a4-2300 | Lite-On ... | Non-Volatile memory contr... | 51    |
| pci:2646-2262 | Kingston... | KC2000 NVMe SSD              | 51    |
| pci:1bb1-5012 | Seagate ... | FireCuda 510 SSD             | 49    |
| pci:106b-2003 | Apple       | S3X NVMe Controller          | 45    |
| pci:15b7-5019 | Sandisk     | Non-Volatile memory contr... | 43    |
| pci:8086-faf0 | Intel       | Non-Volatile memory contr... | 40    |
| pci:2646-500f | Kingston... | Technology Company Non-Vo... | 38    |
| pci:1cc4-6203 | Union Me... | Non-Volatile memory contr... | 37    |
| pci:14a4-23f1 | Lite-On ... | Non-Volatile memory contr... | 36    |
| pci:14a4-9100 | Lite-On ... | NVMe Controller              | 36    |
| pci:14a4-22f1 | Lite-On ... | M8Pe Series NVMe SSD         | 35    |
| pci:17aa-0003 | Lenovo      | Non-Volatile memory contr... | 35    |
| pci:17aa-0006 | Lenovo      | Non-Volatile memory contr... | 30    |
| pci:1987-5018 | Phison E... | E18 PCIe4 NVMe Controller    | 30    |
| pci:17aa-0005 | Lenovo      | Non-Volatile memory contr... | 28    |
| pci:10ec-5765 | Realtek ... | Realtek Non-Volatile memo... | 27    |
| pci:8086-0953 | Intel       | PCIe Data Center SSD         | 27    |
| pci:126f-2260 | Silicon ... | Non-Volatile memory contr... | 25    |
| pci:1d97-1160 | Shenzhen... | Non-Volatile memory contr... | 25    |
| pci:1b85-6018 | OCZ Tech... | RD400/400A SSD               | 24    |
| pci:10ec-5760 | Realtek ... | Realtek Non-Volatile memo... | 23    |
| pci:14a4-2100 | Lite-On ... | Non-Volatile memory contr... | 23    |
| pci:17aa-0004 | Lenovo      | Non-Volatile memory contr... | 23    |
| pci:8086-2700 | Intel       | Optane SSD 900P Series       | 23    |
| pci:1c5c-1284 | SK Hynix    | PC300 NVMe Solid State Dr... | 21    |
| pci:1cc1-5350 | ADATA Te... | Non-Volatile memory contr... | 20    |
| pci:1e0f-0009 | KIOXIA      | NVMe SSD                     | 20    |
| pci:1e49-1001 | Yangtze ... | Non-Volatile memory contr... | 20    |
| pci:8086-0a54 | Intel       | NVMe Datacenter SSD [3DNA... | 20    |
| pci:15b7-501e | Sandisk     | Non-Volatile memory contr... | 19    |
| pci:1cc4-2263 | Union Me... | Non-Volatile memory contr... | 19    |
| pci:1d97-2263 | Shenzhen... | SM2263EN/SM2263XT-based O... | 19    |
| pci:14a4-2200 | Lite-On ... | Lite-On Non-Volatile memo... | 18    |
| pci:1c5c-1283 | SK Hynix    | PC300 NVMe Solid State Dr... | 18    |
| pci:1022-b000 | AMD         | RAID Bottom Device           | 17    |
| pci:14a4-3500 | Lite-On ... | Non-Volatile memory contr... | 16    |
| pci:15b7-501a | Sandisk     | WD Blue SN570 NVMe SSD       | 14    |
| pci:15b7-501d | Sandisk     | Non-Volatile memory contr... | 14    |
| pci:1c5c-1285 | SK Hynix    | PC300 NVMe Solid State Dr... | 13    |
| pci:1e0f-000d | KIOXIA      | Non-Volatile memory contr... | 12    |
| pci:1344-5407 | Micron T... | Non-Volatile memory contr... | 11    |
| pci:1bb1-5018 | Seagate ... | FireCuda 530 SSD             | 11    |
| pci:1cc4-17aa | Union Me... | Non-Volatile memory contr... | 11    |
| pci:1bb1-5013 | Seagate ... | Non-Volatile memory contr... | 10    |
| pci:1dbe-5236 | Unknown     | Non-Volatile memory contr... | 9     |
| pci:1dee-2263 | Biwin St... | Non-Volatile memory contr... | 9     |
| pci:1e95-3500 | Solid St... | Non-Volatile memory contr... | 9     |
| pci:2646-5010 | Kingston... | Technology Company Non-Vo... | 9     |
| pci:c0a9-5407 | Micron/C... | Non-Volatile memory contr... | 9     |
| pci:1c5c-1504 | SK Hynix    | SC300 512GB M.2 2280 SATA... | 8     |
| pci:1cc4-5012 | Union Me... | Non-Volatile memory contr... | 8     |
| pci:1e0f-0008 | KIOXIA      | Non-Volatile memory contr... | 8     |
| pci:1e49-0001 | Yangtze ... | Non-Volatile memory contr... | 7     |
| pci:144d-a822 | Samsung ... | NVMe SSD Controller 172Xa... | 6     |
| pci:14a4-21f1 | Lite-On ... | Non-Volatile memory contr... | 6     |
| pci:1cc4-17ab | Union Me... | NVMe 256G SSD device         | 6     |
| pci:1d79-2263 | Unknown     | Non-Volatile memory contr... | 6     |
| pci:1dee-2262 | Biwin St... | Non-Volatile memory contr... | 6     |
| pci:1344-51b2 | Micron T... | Non-Volatile memory contr... | 5     |
| pci:1b4b-2241 | Marvell ... | 88NR2241 Non-Volatile mem... | 5     |
| pci:1cc4-6201 | Union Me... | Non-Volatile memory contr... | 5     |
| pci:1e4b-1202 | MAXIO Te... | NVMe SSD Controller MAP1202  | 5     |
| pci:2646-5013 | Kingston... | Technology Company Non-Vo... | 5     |
| pci:1344-51a2 | Micron T... | Non-Volatile memory contr... | 4     |
| pci:144d-a824 | Samsung ... | NVMe SSD Controller PM173X   | 4     |
| pci:1b4b-1092 | Marvell ... | Marvell Non-Volatile memo... | 4     |
| pci:1e4b-1001 | MAXIO Te... | NVMe SSD Controller MAP1001  | 4     |
| pci:1e95-35f1 | Solid St... | Non-Volatile memory contr... | 4     |
| pci:8086-2701 | Intel       | NVMe Datacenter SSD [Optane] | 4     |
| pci:126f-1001 | Silicon ... | Non-Volatile memory contr... | 3     |
| pci:1b4b-1160 | Marvell ... | Marvell Non-Volatile memo... | 3     |
| pci:1bb1-0100 | Seagate ... | Nytro Flash Storage          | 3     |
| pci:1d97-1d97 | Shenzhen... | Electronics Non-Volatile ... | 3     |
| pci:1dbe-5216 | Unknown     | Non-Volatile memory contr... | 3     |
| pci:1179-0119 | Toshiba     | Toshiba America Info Non-... | 2     |
| pci:14a4-5100 | Lite-On ... | Non-Volatile memory contr... | 2     |
| pci:15b7-5014 | Sandisk     | Non-Volatile memory contr... | 2     |
| pci:19e5-3714 | Huawei T... | ES3000 V5 NVMe PCIe SSD      | 2     |
| pci:1bc0-1002 | Innodisk    | PCIe 3TE6 Controller         | 2     |
| pci:1c44-1100 | Enmotus     | Non-Volatile memory contr... | 2     |
| pci:1cc1-2263 | ADATA Te... | Non-Volatile memory contr... | 2     |
| pci:1cc4-17a9 | Union Me... | Non-Volatile memory contr... | 2     |
| pci:1e95-1005 | Solid St... | Non-Volatile memory contr... | 2     |
| pci:9d32-1000 | Beijing ... | Non-Volatile memory contr... | 2     |
| pci:1344-5180 | Micron T... | 9100 PRO NVMe SSD            | 1     |
| pci:1344-5181 | Micron T... | 9100 MAX NVMe SSD            | 1     |
| pci:1344-5192 | Micron T... | 9200 MAX NVMe SSD            | 1     |
| pci:1344-5411 | Micron T... | Non-Volatile memory contr... | 1     |
| pci:144d-a821 | Samsung ... | NVMe SSD Controller 172X     | 1     |
| pci:14a4-22a0 | Lite-On ... | Non-Volatile memory contr... | 1     |
| pci:14a4-2f00 | Lite-On ... | Non-Volatile memory contr... | 1     |
| pci:14a4-35f1 | Lite-On ... | Non-Volatile memory contr... | 1     |
| pci:16c3-2262 | Synopsys    | Non-Volatile memory contr... | 1     |
| pci:1987-5015 | Phison E... | Electronics Non-Volatile ... | 1     |
| pci:1b96-2200 | Western ... | Ultrastar DC SN630 NVMe SSD  | 1     |
| pci:1b96-2400 | Western ... | Ultrastar DC SN640 NVMe SSD  | 1     |
| pci:1bb1-005d | Seagate ... | Nytro PCIe Flash Storage     | 1     |
| pci:1c5c-1282 | SK Hynix    | Non-Volatile memory contr... | 1     |
| pci:1c5c-2839 | SK Hynix    | PE8000 Series NVMe Solid ... | 1     |
| pci:1cc1-5763 | ADATA Te... | A Non-Volatile memory con... | 1     |
| pci:1cc1-5766 | ADATA Te... | ADATA XPG GAMMIXS1 1L Media  | 1     |
| pci:1cc4-0005 | Union Me... | Non-Volatile memory contr... | 1     |
| pci:1cc4-2260 | Union Me... | Non-Volatile memory contr... | 1     |
| pci:1cc4-6204 | Union Me... | Non-Volatile memory contr... | 1     |
| pci:1dd4-0010 | Unknown     | Non-Volatile memory contr... | 1     |
| pci:1e0f-0007 | KIOXIA      | NVMe SSD Controller Cx6      | 1     |
| pci:1e49-0041 | Yangtze ... | ZHITAI TiPro7000             | 1     |
| pci:1e4b-1002 | MAXIO Te... | NVMe SSD Controller MAP1002  | 1     |
| pci:1e95-1001 | Solid St... | Non-Volatile memory contr... | 1     |
| pci:1e95-1002 | Solid St... | NVMe Datacenter LJ1 SSD [... | 1     |
| pci:1e95-1003 | Solid St... | Non-Volatile memory contr... | 1     |
| pci:1eab-300b | Hefei DA... | NVMe SSD Controller 300B     | 1     |
| pci:2646-500a | Kingston... | Technology Company Non-Vo... | 1     |
| pci:2646-500b | Kingston... | Technology Company Non-Vo... | 1     |
| pci:8086-0a53 | Intel       | DC P3520 SSD                 | 1     |
| pci:8086-f1a7 | Intel       | Non-Volatile memory contr... | 1     |
| pci:9d32-1201 | Beijing ... | STAR1200C NVMe SSD           | 1     |
| pci:9d32-fc22 | Beijing ... | Non-Volatile memory contr... | 1     |
| pci:cc53-0001 | ScaleFlux   | Non-Volatile memory contr... | 1     |
| pci:efff-641a |             | Non-Volatile memory contr... | 1     |

### Storage/other (PCI)

Total devices: 1857

| ID            | MFG         | Name                         | Count |
|---------------|-------------|------------------------------|-------|
| pci:104c-803b | Texas In... | PCIxx12 Flash Media Contr... | 746   |
| pci:1217-7130 | O2 Micro    | Integrated MS/xD Controller  | 312   |
| pci:1217-8231 | O2 Micro    | O2Micro Integrated MS/MSP... | 205   |
| pci:1217-8331 | O2 Micro    | O2 Flash Memory Card         | 171   |
| pci:104c-8033 | Texas In... | PCIxx21/PCIxx11 Flash Med... | 116   |
| pci:1217-8330 | O2 Micro    | OZ600 MS/xD Controller       | 73    |
| pci:1217-8130 | O2 Micro    | Integrated MS/MSPRO/xD Co... | 64    |
| pci:1283-8211 | Integrat... | ITE 8211F Single Channel ... | 48    |
| pci:104c-ac8f | Texas In... | PCI7420/7620 SD/MS-Pro Co... | 14    |
| pci:1077-2432 | QLogic      | ISP2432-based 4Gb Fibre C... | 13    |
| pci:1077-2532 | QLogic      | ISP2532-based 8Gb Fibre C... | 13    |
| pci:1106-401a | VIA Tech... | VIA Card Reader Host Cont... | 12    |
| pci:1aed-2001 | SanDisk     | ioDrive2                     | 6     |
| pci:105a-4d69 | Promise ... | 20269                        | 5     |
| pci:10b9-5289 | ULi Elec... | ULi 5289 SATA                | 5     |
| pci:11f8-8032 | PMC-Sierra  | PM8032 Tachyon QE8           | 5     |
| pci:105a-4d68 | Promise ... | PDC20268 [Ultra100 TX2]      | 4     |
| pci:10df-fe00 | Emulex      | Zephyr-X LightPulse Fibre... | 4     |
| pci:105a-3d17 | Promise ... | PDC40718 (SATA 300 TX4)      | 3     |
| pci:105a-3d73 | Promise ... | PDC40775 (SATA 300 TX2plus)  | 3     |
| pci:1077-2031 | QLogic      | ISP8324-based 16Gb Fibre ... | 3     |
| pci:10df-f0e5 | Emulex      | Zephyr LightPulse Fibre C... | 3     |
| pci:10df-f100 | Emulex      | LPe12000 Series 8Gb Fibre... | 3     |
| pci:1000-0646 | Broadcom... | FC949ES Fibre Channel Ada... | 2     |
| pci:105a-3375 | Promise ... | PDC20375 (SATA150 TX2plus)   | 2     |
| pci:1077-2312 | QLogic      | ISP2312-based 2Gb Fibre C... | 2     |
| pci:19a2-0704 | Emulex      | OneConnect OCe10100/OCe10... | 2     |
| pci:1aed-3002 | SanDisk     | ioMemory HHHL                | 2     |
| pci:8086-98fa | Intel       | Universal Flash Storage (... | 2     |
| pci:105a-1275 | Promise ... | 20275                        | 1     |
| pci:105a-3d75 | Promise ... | PDC20575 (SATAII150 TX2plus) | 1     |
| pci:105a-4d30 | Promise ... | PDC20267 (FastTrak100/Ult... | 1     |
| pci:1077-2261 | QLogic      | ISP2722-based 16/32Gb Fib... | 1     |
| pci:10df-0724 | Emulex      | OneConnect FCoE Initiator... | 1     |
| pci:10df-f400 | Emulex      | LPe35000/LPe36000 Series ... | 1     |
| pci:10df-fa00 | Emulex      | Thor-X LightPulse Fibre C... | 1     |
| pci:117c-0064 | ATTO Tec... | Celerity FC 16Gb/s Gen 5 ... | 1     |
| pci:1261-3001 | Matsushi... | Storage controller           | 1     |
| pci:19a2-0702 | Emulex      | OneConnect 10Gb iSCSI Ini... | 1     |
| pci:19a2-0712 | Emulex      | OneConnect 10Gb iSCSI Ini... | 1     |
| pci:19e5-0203 | Huawei T... | Hi1822 Family (2*16G FC)     | 1     |
| pci:ace1-0005 | Unknown     | Storage controller           | 1     |
| pci:ace1-0006 | Unknown     | Storage controller           | 1     |

### Storage/raid (PCI)

Total devices: 9670

| ID            | MFG         | Name                         | Count |
|---------------|-------------|------------------------------|-------|
| pci:8086-282a | Intel       | 82801 Mobile SATA Control... | 4667  |
| pci:8086-2822 | Intel       | SATA Controller [RAID mode]  | 1941  |
| pci:8086-9a0b | Intel       | Volume Management Device ... | 922   |
| pci:8086-2826 | Intel       | C600/X79 series chipset S... | 230   |
| pci:1106-3149 | VIA Tech... | VIA VT6420 SATA RAID Cont... | 129   |
| pci:1095-3132 | Silicon ... | SiI 3132 Serial ATA Raid ... | 91    |
| pci:1106-3249 | VIA Tech... | VT6421 IDE/SATA Controller   | 85    |
| pci:1000-005d | LSI Logi... | MegaRAID SAS-3 3108 [Inva... | 81    |
| pci:1000-0079 | LSI Logi... | MegaRAID SAS 2108 [Libera... | 78    |
| pci:1095-3114 | Silicon ... | SiI 3114 [SATALink/SATARa... | 68    |
| pci:103c-323a | Hewlett-... | Smart Array G6 controllers   | 65    |
| pci:1002-4392 | AMD         | SB7x0/SB8x0/SB9x0 SATA Co... | 58    |
| pci:8086-2827 | Intel       | C610/X99 series chipset s... | 56    |
| pci:1000-005b | LSI Logi... | MegaRAID SAS 2208 [Thunde... | 55    |
| pci:8086-02d7 | Intel       | Comet Lake PCH-LP SATA RA... | 54    |
| pci:103c-323b | Hewlett-... | Smart Array Gen8 Controllers | 46    |
| pci:1022-7916 | AMD         | RS690 PCI to PCI Bridge (... | 45    |
| pci:1000-0060 | LSI Logi... | MegaRAID SAS 1078            | 43    |
| pci:8086-27c3 | Intel       | 82801GR/GDH (ICH7R/ICH7DH... | 43    |
| pci:1000-0073 | LSI Logi... | MegaRAID SAS 2008 [Falcon]   | 41    |
| pci:1022-43bd | AMD         | FCH RAID Controller          | 41    |
| pci:1002-4393 | AMD         | SB7x0/SB8x0/SB9x0 SATA Co... | 36    |
| pci:8086-201d | Intel       | Volume Management Device ... | 36    |
| pci:1095-3531 | Silicon ... | SiI 3531 [SATALink/SATARa... | 35    |
| pci:1095-3512 | Silicon ... | SiI 3512 [SATALink/SATARa... | 33    |
| pci:1000-005f | LSI Logi... | MegaRAID SAS-3 3008 [Fury]   | 32    |
| pci:1283-8212 | Integrat... | IT8212 Dual channel ATA R... | 31    |
| pci:8086-06d6 | Intel       | Comet Lake PCH-H RAID        | 31    |
| pci:8086-06d7 | Intel       | Comet Lake PCH-H RAID        | 31    |
| pci:8086-2682 | Intel       | 631xESB/632xESB SATA RAID... | 27    |
| pci:8086-a386 | Intel       | 300 Series Chipset Family... | 26    |
| pci:8086-467f | Intel       | Volume Management Device ... | 24    |
| pci:1095-0680 | Silicon ... | PCI0680 Ultra ATA-133 Hos... | 22    |
| pci:9005-0285 | Adaptec     | AAC-RAID                     | 21    |
| pci:1106-3164 | VIA Tech... | VT6410 ATA133 RAID contro... | 18    |
| pci:11ab-6485 | Marvell ... | MV64460/64461/64462 Syste... | 17    |
| pci:9005-028b | Adaptec     | Series 6 - 6G SAS/PCIe 2     | 17    |
| pci:1000-0016 | LSI Logi... | MegaRAID Tri-Mode SAS3508    | 16    |
| pci:11ab-6440 | Marvell ... | 88SE6440 SAS/SATA PCIe co... | 16    |
| pci:103c-3230 | Hewlett-... | Smart Array Controller       | 15    |
| pci:103c-3239 | Hewlett-... | Smart Array Gen9 Controllers | 15    |
| pci:10b9-5287 | ULi Elec... | ULi 5287 SATA                | 15    |
| pci:10de-07f8 | Nvidia      | MCP73 SATA RAID Controller   | 13    |
| pci:13c1-1004 | 3ware       | 9650SE SATA-II RAID PCIe     | 13    |
| pci:17d3-1880 | Areca Te... | ARC-188x series PCIe 2.0/... | 13    |
| pci:105a-3373 | Promise ... | PDC20378 (FastTrak 378/SA... | 11    |
| pci:10de-0abc | Nvidia      | MCP79 RAID Controller        | 11    |
| pci:1000-0014 | Broadcom... | MegaRAID Tri-Mode SAS3516    | 10    |
| pci:1095-3124 | Silicon ... | SiI 3124 PCI-X Serial ATA... | 10    |
| pci:8086-43d6 | Intel       | 500 Series Chipset Family... | 10    |
| pci:1022-7917 | AMD         | RS690 PCI to PCI Bridge (... | 9     |
| pci:1b4b-9485 | Marvell ... | 88SE9485 SAS/SATA 6Gb/s c... | 9     |
| pci:1022-7802 | AMD         | FCH SATA Controller [RAID... | 8     |
| pci:103c-3238 | Hewlett-... | Smart Array E200i (SAS Co... | 8     |
| pci:9005-028c | Adaptec     | Series 7 6G SAS/PCIe 3       | 8     |
| pci:1028-0015 | Dell        | PowerEdge Expandable RAID... | 7     |
| pci:8086-27c6 | Intel       | 82801GHM (ICH7-M DH) SATA... | 7     |
| pci:10de-0ad8 | Nvidia      | MCP78S [GeForce 8200] SAT... | 6     |
| pci:1b4b-9192 | Marvell ... | 88SE9172 SATA III 6Gb/s R... | 6     |
| pci:8086-1c04 | Intel       | 6 Series/C200 Series Desk... | 6     |
| pci:8086-3a25 | Intel       | 82801JIR (ICH10R) SATA RA... | 6     |
| pci:8086-8d06 | Intel       | C610/X99 series chipset S... | 6     |
| pci:9005-0241 | Adaptec     | Serial ATA II RAID 1420SA    | 6     |
| pci:1022-7805 | AMD         | FCH SATA Controller [RAID... | 5     |
| pci:8086-24df | Intel       | 82801ER (ICH5R) SATA Cont... | 5     |
| pci:8086-3b25 | Intel       | 5 Series/3400 Series Chip... | 5     |
| pci:105a-3515 | Promise ... | PDC40719 [FastTrak TX4300... | 4     |
| pci:105a-3f20 | Promise ... | PDC42819 [FastTrak TX2650... | 4     |
| pci:1103-0622 | HighPoin... | RocketRAID 622 2 Port SAT... | 4     |
| pci:13c1-1003 | 3ware       | 9550SX SATA-II RAID PCI-X    | 4     |
| pci:8086-1d04 | Intel       | C600/X79 series chipset S... | 4     |
| pci:1000-0411 | Broadcom... | MegaRAID SAS 1068            | 3     |
| pci:105a-4d38 | Promise ... | PDC20262 (FastTrak66/Ultr... | 3     |
| pci:1166-024a | Broadcom    | BCM5785 [HT1000] SATA (Na... | 3     |
| pci:19e5-a25a | Huawei T... | HiSilicon RDE Engine         | 3     |
| pci:8086-a356 | Intel       | 300 Series Chipset Family... | 3     |
| pci:9005-0286 | Adaptec     | AAC-RAID (Rocket)            | 3     |
| pci:1000-0017 | Broadcom... | MegaRAID Tri-Mode SAS3408    | 2     |
| pci:1000-10e2 | Broadcom... | MegaRAID 12GSAS/PCIe Secu... | 2     |
| pci:1000-1960 | LSI Logi... | MegaRAID                     | 2     |
| pci:1022-7905 | AMD         | RAID Bottom                  | 2     |
| pci:1028-0013 | Dell        | PowerEdge Expandable RAID... | 2     |
| pci:1028-0016 | Dell        | PowerEdge Expandable RAID... | 2     |
| pci:103c-193f | Hewlett-... | Dynamic Smart Array B140i    | 2     |
| pci:1095-0242 | Silicon ... | AAR-1220SA Serial ATA Hos... | 2     |
| pci:1103-0004 | HighPoin... | HPT366/368/370/370A/372/372N | 2     |
| pci:1103-0620 | HighPoin... | RocketRAID 620 2 Port SAT... | 2     |
| pci:1103-2720 | HighPoin... | RocketRAID 2720 SAS Contr... | 2     |
| pci:1103-4320 | HighPoin... | RocketRAID 4320 SAS Contr... | 2     |
| pci:13c1-1001 | 3ware       | 7xxx/8xxx-series PATA/SAT... | 2     |
| pci:13c1-1010 | 3ware       | 9750 SAS2/SATA-II RAID PCIe  | 2     |
| pci:1590-0045 | Hewlett-... | RAID bus controller          | 2     |
| pci:17d3-1210 | Areca Te... | ARC-1210 4-Port PCI-Expre... | 2     |
| pci:8086-43de | Intel       | 500 Series Chipset Family... | 2     |
| pci:8086-8c04 | Intel       | 8 Series/C220 Series Chip... | 2     |
| pci:8086-8d66 | Intel       | C610/X99 series chipset s... | 2     |
| pci:8086-a106 | Intel       | Q170/H170/Z170/CM236 Chip... | 2     |
| pci:9005-8092 | Adaptec     | ASC-29320 U320 w/HostRAID    | 2     |
| pci:1000-0010 | Broadcom... | 53C1510                      | 1     |
| pci:1000-0409 | Broadcom... | MegaRAID                     | 1     |
| pci:1014-02bd | IBM         | Obsidian chipset SCSI con... | 1     |
| pci:1039-1182 | Silicon ... | SATA Controller / RAID mode  | 1     |
| pci:103c-3220 | Hewlett-... | Smart Array P600             | 1     |
| pci:103c-323c | Hewlett-... | Smart Array Gen8+ Control... | 1     |
| pci:105a-3319 | Promise ... | PDC20319 (FastTrak S150 TX4) | 1     |
| pci:105a-3371 | Promise ... | PDC20371 (FastTrak S150 T... | 1     |
| pci:105a-3570 | Promise ... | PDC20771 [FastTrak TX2300]   | 1     |
| pci:105a-3571 | Promise ... | PDC20571 (FastTrak TX2200)   | 1     |
| pci:105a-4302 | Promise ... | 80333 [SuperTrak EX4350]     | 1     |
| pci:105a-6269 | Promise ... | PDC20271 (FastTrak TX2000)   | 1     |
| pci:105a-8350 | Promise ... | 80333 [SuperTrak EX8350/E... | 1     |
| pci:1095-0244 | Silicon ... | AAR-1225SA Serial ATA Hos... | 1     |
| pci:1095-0649 | Silicon ... | SiI 0649 Ultra ATA/100 PC... | 1     |
| pci:1095-1114 | Silicon ... | RAID bus controller          | 1     |
| pci:1103-0611 | HighPoin... | RAID bus controller          | 1     |
| pci:1103-0640 | HighPoin... | RocketRAID 640 4 Port SAT... | 1     |
| pci:1103-0647 | HighPoin... | RAID bus controller          | 1     |
| pci:1103-0840 | HighPoin... | RAID bus controller          | 1     |
| pci:1103-2840 | HighPoin... | RAID bus controller          | 1     |
| pci:1103-3520 | HighPoin... | RocketRAID 3520 SATA Cont... | 1     |
| pci:1103-3530 | HighPoin... | RocketRAID 3530 SATA Cont... | 1     |
| pci:1103-3740 | HighPoin... | RAID bus controller          | 1     |
| pci:1103-7103 | HighPoin... | RAID bus controller          | 1     |
| pci:1103-7110 | HighPoin... | RAID bus controller          | 1     |
| pci:1106-1241 | VIA Tech... | RAID bus controller          | 1     |
| pci:117c-002c | ATTO Tec... | ExpressSAS R380              | 1     |
| pci:17d3-1160 | Areca Te... | ARC-1160 16-Port PCI-X to... | 1     |
| pci:17d3-1220 | Areca Te... | ARC-1220 8-Port PCI-Expre... | 1     |
| pci:17d3-1680 | Areca Te... | ARC-1680 series PCIe to S... | 1     |
| pci:1b4b-91a2 | Marvell ... | 88SE91A2 SATA 6G Controller  | 1     |
| pci:1b4b-9480 | Marvell ... | 88SE9480 SAS/SATA 6Gb/s R... | 1     |
| pci:6883-0dd4 | Unknown     | RAID bus controller          | 1     |
| pci:8086-a186 | Intel       | C620 Series Chipset Famil... | 1     |
| pci:9005-0243 | Adaptec     | Serial ATA II RAID 1430SA    | 1     |
| pci:9005-0250 | Adaptec     | ServeRAID Controller         | 1     |
| pci:9005-8095 | Adaptec     | ASC-39320(B) U320 w/HostRAID | 1     |
| pci:9005-809d | Adaptec     | AIC-7902(B) U320 w/HostRAID  | 1     |

### Storage/sas (PCI)

Total devices: 575

| ID            | MFG         | Name                         | Count |
|---------------|-------------|------------------------------|-------|
| pci:8086-1d6b | Intel       | C602 chipset 4-Port SATA ... | 227   |
| pci:1000-0072 | Broadcom... | SAS2008 PCI-Express Fusio... | 120   |
| pci:1000-0086 | Broadcom... | SAS2308 PCI-Express Fusio... | 47    |
| pci:1000-0087 | LSI Logi... | SAS2308 PCI-Express Fusio... | 44    |
| pci:1000-0097 | LSI Logi... | SAS3008 PCI-Express Fusio... | 43    |
| pci:1000-0064 | LSI Logi... | SAS2116 PCI-Express Fusio... | 13    |
| pci:9005-028f | Adaptec     | Smart Storage PQI SAS        | 10    |
| pci:1000-0070 | LSI Logi... | SAS2004 PCI-Express Fusio... | 9     |
| pci:8086-1d68 | Intel       | C606 chipset Dual 4-Port ... | 9     |
| pci:8086-1d69 | Intel       | C604/X79 series chipset 4... | 9     |
| pci:9005-028d | Adaptec     | Series 8 12G SAS/PCIe 3      | 9     |
| pci:19e5-a230 | Huawei T... | HiSilicon SAS 3.0 HBA        | 7     |
| pci:1000-007e | Broadcom... | SSS6200 PCI-Express Flash... | 4     |
| pci:1000-00c4 | Broadcom... | SAS3224 PCI-Express Fusio... | 4     |
| pci:8086-1d60 | Intel       | C608 chipset Dual 4-Port ... | 4     |
| pci:1000-00ac | Broadcom... | SAS3416 Fusion-MPT Tri-Mo... | 3     |
| pci:1000-00af | Broadcom... | SAS3408 Fusion-MPT Tri-Mo... | 3     |
| pci:8086-1d6a | Intel       | C600/X79 series chipset D... | 3     |
| pci:117c-0042 | ATTO Tec... | ExpressSAS 6Gb/s SAS/SATA... | 2     |
| pci:11f8-8001 | PMC-Sierra  | SPC 8x6G SAS/SATA (storport) | 1     |
| pci:8086-1d6c | Intel       | C600/X79 series chipset D... | 1     |
| pci:8086-1d6d | Intel       | C600/X79 series chipset 4... | 1     |
| pci:8086-1d6f | Intel       | C600/X79 series chipset 4... | 1     |
| pci:9005-0450 | Adaptec     | ASC-1405 Unified Serial HBA  | 1     |

### Storage/scsi (PCI)

Total devices: 327

| ID            | MFG         | Name                         | Count |
|---------------|-------------|------------------------------|-------|
| pci:1000-0058 | LSI Logi... | SAS1068E PCI-Express Fusi... | 124   |
| pci:1000-0056 | LSI Logi... | SAS1064ET PCI-Express Fus... | 33    |
| pci:1000-0054 | LSI Logi... | SAS1068 PCI-X Fusion-MPT SAS | 23    |
| pci:1000-0030 | LSI Logi... | 53c1030 PCI-X Fusion-MPT ... | 20    |
| pci:9004-5078 | Adaptec     | AIC-7850T/7856T [AVA-2902... | 15    |
| pci:9004-8178 | Adaptec     | AIC-7870P/7881U [AHA-2940... | 14    |
| pci:9005-8017 | Adaptec     | ASC-29320ALP U320            | 9     |
| pci:9004-6178 | Adaptec     | AIC-7861                     | 8     |
| pci:9004-7178 | Adaptec     | AIC-7870P/7871 [AHA-2940/... | 8     |
| pci:9005-0010 | Adaptec     | AHA-2940U2/U2W               | 6     |
| pci:9005-0080 | Adaptec     | AIC-7892A U160/m             | 6     |
| pci:1b85-1021 | OCZ Tech... | OCZ SCSI storage controller  | 5     |
| pci:1000-0001 | LSI Logi... | 53c810                       | 4     |
| pci:1000-0050 | Broadcom... | SAS1064 PCI-X Fusion-MPT SAS | 4     |
| pci:10cd-1300 | Advanced... | ASC1300 / ASC3030 [ABP940... | 4     |
| pci:1de1-0391 | Tekram T... | TRM-S1040 [DC-315 / DC-39... | 4     |
| pci:1000-000f | Broadcom... | 53c875                       | 3     |
| pci:11ab-7042 | Marvell ... | 88SX7042 PCI-e 4-port SAT... | 3     |
| pci:1000-0059 | LSI Logi... | MegaRAID SAS 8208ELP/8208ELP | 2     |
| pci:1b85-1041 | OCZ Tech... | RevoDrive 3 X2 PCI-Expres... | 2     |
| pci:9004-3860 | Adaptec     | AHA-2930CU                   | 2     |
| pci:9005-00c0 | Adaptec     | AHA-3960D / AIC-7899A U160/m | 2     |
| pci:9005-8012 | Adaptec     | ASC-29320 U320               | 2     |
| pci:9005-8016 | Adaptec     | ASC-39320A U320              | 2     |
| pci:9005-801d | Adaptec     | AIC-7902B U320               | 2     |
| pci:1022-2020 | AMD         | 53c974 [PCscsi]              | 1     |
| pci:1069-b166 | Mylex       | AcceleRAID 600/500/400/Sa... | 1     |
| pci:1095-3110 | Silicon ... | SCSI storage controller      | 1     |
| pci:1101-9400 | Initio      | INI-940 Fast Wide SCSI Ad... | 1     |
| pci:1101-9500 | Initio      | INI-950 SCSI Adapter         | 1     |
| pci:1103-2310 | HighPoin... | RocketRAID 2310 4 Port SA... | 1     |
| pci:117c-0030 | ATTO Tec... | Ultra320 SCSI Host Adapter   | 1     |
| pci:1191-8020 | Artop El... | AEC6712U SCSI                | 1     |
| pci:1191-8040 | Artop El... | AEC6712D SCSI                | 1     |
| pci:11ab-6041 | Marvell ... | MV88SX6041 4-port SATA II... | 1     |
| pci:11ab-6081 | Marvell ... | MV88SX6081 8-port SATA II... | 1     |
| pci:1b85-1221 | OCZ Tech... | OCZ 12xx SCSI Controller     | 1     |
| pci:9004-8078 | Adaptec     | AIC-7880U                    | 1     |
| pci:9004-8278 | Adaptec     | AHA-3940U/UW/UWD / AIC-7882U | 1     |
| pci:9004-8778 | Adaptec     | AHA-2940UW Pro / AIC-788x    | 1     |
| pci:9004-8c78 | Adaptec     | SCSI storage controller      | 1     |
| pci:9005-0011 | Adaptec     | AHA-2930U2                   | 1     |
| pci:9005-0081 | Adaptec     | AIC-7892B U160/m             | 1     |
| pci:9005-00cf | Adaptec     | AIC-7899P U160/m             | 1     |
| pci:9005-801f | Adaptec     | AIC-7902 U320                | 1     |

### System peripheral (PCI)

Total devices: 126535

| ID            | MFG         | Name                         | Count |
|---------------|-------------|------------------------------|-------|
| pci:8086-1911 | Intel       | Xeon E3-1200 v5/v6 / E3-1... | 11063 |
| pci:1180-0592 | Ricoh       | R5C592 Memory Stick Bus H... | 1938  |
| pci:1180-0852 | Ricoh       | xD-Picture Card Controller   | 1579  |
| pci:197b-2392 | JMicron ... | SD/MMC Host Controller       | 1312  |
| pci:197b-2382 | JMicron ... | SD/MMC Host Controller       | 1138  |
| pci:197b-2383 | JMicron ... | MS Host Controller           | 1095  |
| pci:8086-9a11 | Intel       | GNA Scoring Accelerator m... | 1064  |
| pci:8086-d155 | Intel       | Core Processor System Man... | 1008  |
| pci:8086-d156 | Intel       | Core Processor Semaphore ... | 1008  |
| pci:8086-d157 | Intel       | Core Processor System Con... | 1008  |
| pci:8086-d150 | Intel       | Core Processor QPI Link      | 999   |
| pci:8086-d151 | Intel       | Core Processor QPI Routin... | 999   |
| pci:8086-d158 | Intel       | Core Processor Miscellane... | 997   |
| pci:8086-15eb | Intel       | JHL7540 Thunderbolt 3 NHI... | 868   |
| pci:8086-09ab | Intel       | System peripheral            | 845   |
| pci:8086-3190 | Intel       | Celeron/Pentium Silver Pr... | 810   |
| pci:14e4-16be | Broadcom    | BCM57765/57785 MS Card Re... | 767   |
| pci:14e4-16bf | Broadcom    | BCM57765/57785 xD-Picture... | 767   |
| pci:197b-2384 | JMicron ... | xD Host Controller           | 755   |
| pci:8086-15e8 | Intel       | JHL7540 Thunderbolt 3 NHI... | 718   |
| pci:1180-e230 | Ricoh       | R5U2xx (R5U230 / R5U231 /... | 683   |
| pci:8086-15d2 | Intel       | JHL6540 Thunderbolt 3 NHI... | 647   |
| pci:8086-15d9 | Intel       | JHL6340 Thunderbolt 3 NHI... | 574   |
| pci:8086-3c28 | Intel       | Xeon E5/Core i7 Address M... | 542   |
| pci:8086-3c2a | Intel       | Xeon E5/Core i7 Control S... | 542   |
| pci:8086-3c71 | Intel       | Xeon E5/Core i7 Integrate... | 537   |
| pci:8086-3ca0 | Intel       | Xeon E5/Core i7 Processor... | 537   |
| pci:8086-3ca8 | Intel       | Xeon E5/Core i7 Integrate... | 537   |
| pci:8086-3caa | Intel       | Xeon E5/Core i7 Integrate... | 537   |
| pci:8086-3cab | Intel       | Xeon E5/Core i7 Integrate... | 537   |
| pci:8086-3cac | Intel       | Xeon E5/Core i7 Integrate... | 537   |
| pci:8086-3cad | Intel       | Xeon E5/Core i7 Integrate... | 537   |
| pci:8086-3cae | Intel       | Xeon E5/Core i7 Integrate... | 537   |
| pci:8086-3cb0 | Intel       | Xeon E5/Core i7 Integrate... | 537   |
| pci:8086-3cb2 | Intel       | Xeon E5/Core i7 Integrate... | 537   |
| pci:8086-3cb3 | Intel       | Xeon E5/Core i7 Integrate... | 537   |
| pci:8086-3cb6 | Intel       | Xeon E5/Core i7 Integrate... | 537   |
| pci:8086-3cb7 | Intel       | Xeon E5/Core i7 Integrate... | 537   |
| pci:8086-3cc0 | Intel       | Xeon E5/Core i7 Power Con... | 537   |
| pci:8086-3cd0 | Intel       | Xeon E5/Core i7 Power Con... | 537   |
| pci:8086-3ce0 | Intel       | Xeon E5/Core i7 Interrupt... | 537   |
| pci:8086-3ce3 | Intel       | Xeon E5/Core i7 Semaphore... | 537   |
| pci:8086-3ce8 | Intel       | Xeon E5/Core i7 Unicast R... | 537   |
| pci:8086-3cf4 | Intel       | Xeon E5/Core i7 Integrate... | 537   |
| pci:8086-3cf5 | Intel       | Xeon E5/Core i7 Integrate... | 537   |
| pci:8086-3cf6 | Intel       | Xeon E5/Core i7 System Ad... | 537   |
| pci:8086-3c45 | Intel       | Xeon E5/Core i7 Ring to Q... | 536   |
| pci:8086-3c80 | Intel       | Xeon E5/Core i7 QPI Link 0   | 536   |
| pci:8086-3c90 | Intel       | Xeon E5/Core i7 QPI Link 1   | 536   |
| pci:8086-3cb1 | Intel       | Xeon E5/Core i7 Integrate... | 536   |
| pci:8086-3cb5 | Intel       | Xeon E5/Core i7 Integrate... | 536   |
| pci:8086-3cb8 | Intel       | Xeon E5/Core i7 DDRIO        | 536   |
| pci:8086-3cc1 | Intel       | Xeon E5/Core i7 Power Con... | 536   |
| pci:8086-3cc2 | Intel       | Xeon E5/Core i7 Power Con... | 536   |
| pci:8086-3ce4 | Intel       | Xeon E5/Core i7 R2PCIe       | 536   |
| pci:8086-2f1d | Intel       | Xeon E7 v3/Xeon E5 v3/Cor... | 511   |
| pci:8086-2f1e | Intel       | Xeon E7 v3/Xeon E5 v3/Cor... | 511   |
| pci:8086-2f1f | Intel       | Xeon E7 v3/Xeon E5 v3/Cor... | 511   |
| pci:8086-2f28 | Intel       | Xeon E7 v3/Xeon E5 v3/Cor... | 511   |
| pci:8086-2f29 | Intel       | Xeon E7 v3/Xeon E5 v3/Cor... | 511   |
| pci:8086-2f2a | Intel       | Xeon E7 v3/Xeon E5 v3/Cor... | 511   |
| pci:8086-2f68 | Intel       | Xeon E7 v3/Xeon E5 v3/Cor... | 511   |
| pci:8086-2f6e | Intel       | Xeon E7 v3/Xeon E5 v3/Cor... | 511   |
| pci:8086-2f6f | Intel       | Xeon E7 v3/Xeon E5 v3/Cor... | 511   |
| pci:8086-2f71 | Intel       | Xeon E7 v3/Xeon E5 v3/Cor... | 511   |
| pci:8086-2f81 | Intel       | Xeon E7 v3/Xeon E5 v3/Cor... | 511   |
| pci:8086-2f88 | Intel       | Xeon E7 v3/Xeon E5 v3/Cor... | 511   |
| pci:8086-2f8a | Intel       | Xeon E7 v3/Xeon E5 v3/Cor... | 511   |
| pci:8086-2f98 | Intel       | Xeon E7 v3/Xeon E5 v3/Cor... | 511   |
| pci:8086-2f99 | Intel       | Xeon E7 v3/Xeon E5 v3/Cor... | 511   |
| pci:8086-2f9a | Intel       | Xeon E7 v3/Xeon E5 v3/Cor... | 511   |
| pci:8086-2f9c | Intel       | Xeon E7 v3/Xeon E5 v3/Cor... | 511   |
| pci:8086-2fa0 | Intel       | Xeon E7 v3/Xeon E5 v3/Cor... | 511   |
| pci:8086-2fa8 | Intel       | Xeon E7 v3/Xeon E5 v3/Cor... | 511   |
| pci:8086-2faa | Intel       | Xeon E7 v3/Xeon E5 v3/Cor... | 511   |
| pci:8086-2fab | Intel       | Xeon E7 v3/Xeon E5 v3/Cor... | 511   |
| pci:8086-2fae | Intel       | Xeon E7 v3/Xeon E5 v3/Cor... | 511   |
| pci:8086-2faf | Intel       | Xeon E7 v3/Xeon E5 v3/Cor... | 511   |
| pci:8086-2fb0 | Intel       | Xeon E7 v3/Xeon E5 v3/Cor... | 511   |
| pci:8086-2fb1 | Intel       | Xeon E7 v3/Xeon E5 v3/Cor... | 511   |
| pci:8086-2fb2 | Intel       | Xeon E7 v3/Xeon E5 v3/Cor... | 511   |
| pci:8086-2fb3 | Intel       | Xeon E7 v3/Xeon E5 v3/Cor... | 511   |
| pci:8086-2fb8 | Intel       | Xeon E7 v3/Xeon E5 v3/Cor... | 511   |
| pci:8086-2fb9 | Intel       | Xeon E7 v3/Xeon E5 v3/Cor... | 511   |
| pci:8086-2fba | Intel       | Xeon E7 v3/Xeon E5 v3/Cor... | 511   |
| pci:8086-2fbb | Intel       | Xeon E7 v3/Xeon E5 v3/Cor... | 511   |
| pci:8086-2fbe | Intel       | Xeon E7 v3/Xeon E5 v3/Cor... | 511   |
| pci:8086-2fbf | Intel       | Xeon E7 v3/Xeon E5 v3/Cor... | 511   |
| pci:8086-2fc0 | Intel       | Xeon E7 v3/Xeon E5 v3/Cor... | 511   |
| pci:8086-2fd0 | Intel       | Xeon E7 v3/Xeon E5 v3/Cor... | 511   |
| pci:8086-2fe0 | Intel       | Xeon E7 v3/Xeon E5 v3/Cor... | 511   |
| pci:8086-2fe1 | Intel       | Xeon E7 v3/Xeon E5 v3/Cor... | 511   |
| pci:8086-2fe2 | Intel       | Xeon E7 v3/Xeon E5 v3/Cor... | 511   |
| pci:8086-2fe3 | Intel       | Xeon E7 v3/Xeon E5 v3/Cor... | 511   |
| pci:8086-2ff8 | Intel       | Xeon E7 v3/Xeon E5 v3/Cor... | 511   |
| pci:8086-2ff9 | Intel       | Xeon E7 v3/Xeon E5 v3/Cor... | 511   |
| pci:8086-2ffc | Intel       | Xeon E7 v3/Xeon E5 v3/Cor... | 511   |
| pci:8086-2ffd | Intel       | Xeon E7 v3/Xeon E5 v3/Cor... | 511   |
| pci:8086-2ffe | Intel       | Xeon E7 v3/Xeon E5 v3/Cor... | 511   |
| pci:8086-15bf | Intel       | JHL6240 Thunderbolt 3 NHI... | 508   |
| pci:8086-3cb4 | Intel       | Xeon E5/Core i7 Integrate... | 503   |
| pci:8086-3c83 | Intel       | Xeon E5/Core i7 QPI Link ... | 485   |
| pci:8086-3c84 | Intel       | Xeon E5/Core i7 QPI Link ... | 485   |
| pci:8086-3c93 | Intel       | Xeon E5/Core i7 QPI Link ... | 485   |
| pci:8086-3c94 | Intel       | Xeon E5/Core i7 QPI Link ... | 485   |
| pci:197b-2393 | JMicron ... | MS Host Controller           | 482   |
| pci:8086-2fe4 | Intel       | Xeon E7 v3/Xeon E5 v3/Cor... | 456   |
| pci:8086-2fe5 | Intel       | Xeon E7 v3/Xeon E5 v3/Cor... | 456   |
| pci:8086-2fbc | Intel       | Xeon E7 v3/Xeon E5 v3/Cor... | 403   |
| pci:8086-2fbd | Intel       | Xeon E7 v3/Xeon E5 v3/Cor... | 403   |
| pci:8086-2fac | Intel       | Xeon E7 v3/Xeon E5 v3/Cor... | 368   |
| pci:8086-2fad | Intel       | Xeon E7 v3/Xeon E5 v3/Cor... | 368   |
| pci:8086-2fb4 | Intel       | Xeon E7 v3/Xeon E5 v3/Cor... | 368   |
| pci:8086-2fb5 | Intel       | Xeon E7 v3/Xeon E5 v3/Cor... | 368   |
| pci:8086-2fb6 | Intel       | Xeon E7 v3/Xeon E5 v3/Cor... | 368   |
| pci:8086-2fb7 | Intel       | Xeon E7 v3/Xeon E5 v3/Cor... | 368   |
| pci:8086-0e28 | Intel       | Xeon E7 v2/Xeon E5 v2/Cor... | 347   |
| pci:8086-0e2a | Intel       | Xeon E7 v2/Xeon E5 v2/Cor... | 347   |
| pci:8086-0e1d | Intel       | Xeon E7 v2/Xeon E5 v2/Cor... | 346   |
| pci:8086-0e1e | Intel       | Xeon E7 v2/Xeon E5 v2/Cor... | 346   |
| pci:8086-0e1f | Intel       | Xeon E7 v2/Xeon E5 v2/Cor... | 346   |
| pci:8086-0e71 | Intel       | Xeon E7 v2/Xeon E5 v2/Cor... | 346   |
| pci:8086-0e80 | Intel       | Xeon E7 v2/Xeon E5 v2/Cor... | 346   |
| pci:8086-0e81 | Intel       | Xeon E7 v2/Xeon E5 v2/Cor... | 346   |
| pci:8086-0e90 | Intel       | Xeon E7 v2/Xeon E5 v2/Cor... | 346   |
| pci:8086-0ea0 | Intel       | Xeon E7 v2/Xeon E5 v2/Cor... | 346   |
| pci:8086-0ea8 | Intel       | Xeon E7 v2/Xeon E5 v2/Cor... | 346   |
| pci:8086-0eaa | Intel       | Xeon E7 v2/Xeon E5 v2/Cor... | 346   |
| pci:8086-0eab | Intel       | Xeon E7 v2/Xeon E5 v2/Cor... | 346   |
| pci:8086-0eac | Intel       | Xeon E7 v2/Xeon E5 v2/Cor... | 346   |
| pci:8086-0ead | Intel       | Xeon E7 v2/Xeon E5 v2/Cor... | 346   |
| pci:8086-0eb0 | Intel       | Xeon E7 v2/Xeon E5 v2/Cor... | 346   |
| pci:8086-0eb1 | Intel       | Xeon E7 v2/Xeon E5 v2/Cor... | 346   |
| pci:8086-0eb2 | Intel       | Xeon E7 v2/Xeon E5 v2/Cor... | 346   |
| pci:8086-0eb3 | Intel       | Xeon E7 v2/Xeon E5 v2/Cor... | 346   |
| pci:8086-0eb4 | Intel       | Xeon E7 v2/Xeon E5 v2/Cor... | 346   |
| pci:8086-0eb5 | Intel       | Xeon E7 v2/Xeon E5 v2/Cor... | 346   |
| pci:8086-0eb7 | Intel       | Xeon E7 v2/Xeon E5 v2/Cor... | 346   |
| pci:8086-0ec0 | Intel       | Xeon E7 v2/Xeon E5 v2/Cor... | 346   |
| pci:8086-0ec1 | Intel       | Xeon E7 v2/Xeon E5 v2/Cor... | 346   |
| pci:8086-0ec2 | Intel       | Xeon E7 v2/Xeon E5 v2/Cor... | 346   |
| pci:8086-0ec3 | Intel       | Xeon E7 v2/Xeon E5 v2/Cor... | 346   |
| pci:8086-0ec8 | Intel       | Xeon E7 v2/Xeon E5 v2/Cor... | 346   |
| pci:8086-0ec9 | Intel       | Xeon E7 v2/Xeon E5 v2/Cor... | 346   |
| pci:8086-0eca | Intel       | Xeon E7 v2/Xeon E5 v2/Cor... | 346   |
| pci:8086-0ee0 | Intel       | Xeon E7 v2/Xeon E5 v2/Cor... | 346   |
| pci:8086-0ee1 | Intel       | Xeon E7 v2/Xeon E5 v2/Cor... | 346   |
| pci:8086-0ee2 | Intel       | Xeon E7 v2/Xeon E5 v2/Cor... | 346   |
| pci:8086-0ee3 | Intel       | Xeon E7 v2/Xeon E5 v2/Cor... | 346   |
| pci:8086-2014 | Intel       | Sky Lake-E Ubox Registers    | 315   |
| pci:8086-2016 | Intel       | Sky Lake-E Ubox Registers    | 315   |
| pci:8086-2024 | Intel       | Sky Lake-E MM/Vt-d Config... | 315   |
| pci:8086-2025 | Intel       | Sky Lake-E RAS               | 315   |
| pci:8086-2034 | Intel       | Sky Lake-E VT-d              | 315   |
| pci:8086-2035 | Intel       | Sky Lake-E RAS Configurat... | 315   |
| pci:8086-2040 | Intel       | Sky Lake-E Integrated Mem... | 315   |
| pci:8086-2041 | Intel       | Sky Lake-E Integrated Mem... | 315   |
| pci:8086-2042 | Intel       | Sky Lake-E Integrated Mem... | 315   |
| pci:8086-2043 | Intel       | Sky Lake-E Integrated Mem... | 315   |
| pci:8086-2044 | Intel       | Sky Lake-E Integrated Mem... | 315   |
| pci:8086-2045 | Intel       | Sky Lake-E LM Channel 1      | 315   |
| pci:8086-2046 | Intel       | Sky Lake-E LMS Channel 1     | 315   |
| pci:8086-2047 | Intel       | Sky Lake-E LMDP Channel 1    | 315   |
| pci:8086-2048 | Intel       | Sky Lake-E DECS Channel 2    | 315   |
| pci:8086-2049 | Intel       | Sky Lake-E LM Channel 2      | 315   |
| pci:8086-204a | Intel       | Sky Lake-E LMS Channel 2     | 315   |
| pci:8086-204b | Intel       | Sky Lake-E LMDP Channel 2    | 315   |
| pci:8086-2066 | Intel       | Sky Lake-E Integrated Mem... | 315   |
| pci:8086-2018 | Intel       | Sky Lake-E M2PCI Registers   | 314   |
| pci:8086-204e | Intel       | Sky Lake-E M3KTI Registers   | 314   |
| pci:8086-2054 | Intel       | Sky Lake-E CHA Registers     | 314   |
| pci:8086-2055 | Intel       | Sky Lake-E CHA Registers     | 314   |
| pci:8086-2056 | Intel       | Sky Lake-E CHA Registers     | 314   |
| pci:8086-2057 | Intel       | Sky Lake-E CHA Registers     | 314   |
| pci:8086-2080 | Intel       | Sky Lake-E PCU Registers     | 314   |
| pci:8086-2081 | Intel       | Sky Lake-E PCU Registers     | 314   |
| pci:8086-2082 | Intel       | Sky Lake-E PCU Registers     | 314   |
| pci:8086-2083 | Intel       | Sky Lake-E PCU Registers     | 314   |
| pci:8086-2084 | Intel       | Sky Lake-E PCU Registers     | 314   |
| pci:8086-2085 | Intel       | Sky Lake-E PCU Registers     | 314   |
| pci:8086-2086 | Intel       | Sky Lake-E PCU Registers     | 314   |
| pci:8086-208d | Intel       | Sky Lake-E CHA Registers     | 314   |
| pci:8086-208e | Intel       | Sky Lake-E CHA Registers     | 314   |
| pci:8086-0eb6 | Intel       | Xeon E7 v2/Xeon E5 v2/Cor... | 312   |
| pci:8086-156c | Intel       | DSL5520 Thunderbolt 2 NHI... | 301   |
| pci:8086-2021 | Intel       | Sky Lake-E CBDMA Registers   | 295   |
| pci:8086-0ee4 | Intel       | Xeon E7 v2/Xeon E5 v2/Cor... | 286   |
| pci:8086-0ee5 | Intel       | Xeon E7 v2/Xeon E5 v2/Cor... | 286   |
| pci:8086-2576 | Intel       | 82865G/PE/P Processor to ... | 268   |
| pci:8086-8a17 | Intel       | Ice Lake Thunderbolt 3 NH... | 262   |
| pci:8086-3429 | Intel       | 5520/5500/X58 Chipset Qui... | 238   |
| pci:8086-342a | Intel       | 5520/5500/X58 Chipset Qui... | 238   |
| pci:8086-342b | Intel       | 5520/5500/X58 Chipset Qui... | 238   |
| pci:8086-342c | Intel       | 5520/5500/X58 Chipset Qui... | 238   |
| pci:8086-3430 | Intel       | 5520/5500/X58 Chipset Qui... | 238   |
| pci:8086-3431 | Intel       | 5520/5500/X58 Chipset Qui... | 238   |
| pci:8086-3432 | Intel       | 5520/5500/X58 Chipset Qui... | 238   |
| pci:8086-3433 | Intel       | 5520/5500/X58 Chipset Qui... | 238   |
| pci:8086-156a | Intel       | DSL5320 Thunderbolt 2 NHI... | 223   |
| pci:8086-2fe6 | Intel       | Xeon E7 v3/Xeon E5 v3/Cor... | 217   |
| pci:8086-2fe7 | Intel       | Xeon E7 v3/Xeon E5 v3/Cor... | 217   |
| pci:8086-6f28 | Intel       | Xeon E7 v4/Xeon E5 v4/Xeo... | 202   |
| pci:8086-6f29 | Intel       | Xeon E7 v4/Xeon E5 v4/Xeo... | 202   |
| pci:8086-6f2a | Intel       | Xeon E7 v4/Xeon E5 v4/Xeo... | 202   |
| pci:8086-6f1d | Intel       | Xeon E7 v4/Xeon E5 v4/Xeo... | 201   |
| pci:8086-6f1e | Intel       | Xeon E7 v4/Xeon E5 v4/Xeo... | 201   |
| pci:8086-6f1f | Intel       | Xeon E7 v4/Xeon E5 v4/Xeo... | 201   |
| pci:8086-6f71 | Intel       | Xeon E7 v4/Xeon E5 v4/Xeo... | 201   |
| pci:8086-6f76 | Intel       | Xeon E7 v4/Xeon E5 v4/Xeo... | 201   |
| pci:8086-6f81 | Intel       | Xeon E7 v4/Xeon E5 v4/Xeo... | 201   |
| pci:8086-6f88 | Intel       | Xeon E7 v4/Xeon E5 v4/Xeo... | 201   |
| pci:8086-6f8a | Intel       | Xeon E7 v4/Xeon E5 v4/Xeo... | 201   |
| pci:8086-6f98 | Intel       | Xeon E7 v4/Xeon E5 v4/Xeo... | 201   |
| pci:8086-6f99 | Intel       | Xeon E7 v4/Xeon E5 v4/Xeo... | 201   |
| pci:8086-6f9a | Intel       | Xeon E7 v4/Xeon E5 v4/Xeo... | 201   |
| pci:8086-6f9c | Intel       | Xeon E7 v4/Xeon E5 v4/Xeo... | 201   |
| pci:8086-6fa0 | Intel       | Xeon E7 v4/Xeon E5 v4/Xeo... | 201   |
| pci:8086-6fa8 | Intel       | Xeon E7 v4/Xeon E5 v4/Xeo... | 201   |
| pci:8086-6faa | Intel       | Xeon E7 v4/Xeon E5 v4/Xeo... | 201   |
| pci:8086-6fab | Intel       | Xeon E7 v4/Xeon E5 v4/Xeo... | 201   |
| pci:8086-6fae | Intel       | Xeon E7 v4/Xeon E5 v4/Xeo... | 201   |
| pci:8086-6faf | Intel       | Xeon E7 v4/Xeon E5 v4/Xeo... | 201   |
| pci:8086-6fb0 | Intel       | Xeon E7 v4/Xeon E5 v4/Xeo... | 201   |
| pci:8086-6fb1 | Intel       | Xeon E7 v4/Xeon E5 v4/Xeo... | 201   |
| pci:8086-6fb2 | Intel       | Xeon E7 v4/Xeon E5 v4/Xeo... | 201   |
| pci:8086-6fb3 | Intel       | Xeon E7 v4/Xeon E5 v4/Xeo... | 201   |
| pci:8086-6fbe | Intel       | Xeon E7 v4/Xeon E5 v4/Xeo... | 201   |
| pci:8086-6fbf | Intel       | Xeon E7 v4/Xeon E5 v4/Xeo... | 201   |
| pci:8086-6fc0 | Intel       | Xeon E7 v4/Xeon E5 v4/Xeo... | 201   |
| pci:8086-6fe0 | Intel       | Xeon E7 v4/Xeon E5 v4/Xeo... | 201   |
| pci:8086-6fe1 | Intel       | Xeon E7 v4/Xeon E5 v4/Xeo... | 201   |
| pci:8086-6ff8 | Intel       | Xeon E7 v4/Xeon E5 v4/Xeo... | 201   |
| pci:8086-6ffc | Intel       | Xeon E7 v4/Xeon E5 v4/Xeo... | 201   |
| pci:8086-6ffd | Intel       | Xeon E7 v4/Xeon E5 v4/Xeo... | 201   |
| pci:8086-6ffe | Intel       | Xeon E7 v4/Xeon E5 v4/Xeo... | 201   |
| pci:8086-6fbc | Intel       | Xeon E7 v4/Xeon E5 v4/Xeo... | 200   |
| pci:8086-6fbd | Intel       | Xeon E7 v4/Xeon E5 v4/Xeo... | 200   |
| pci:8086-6fe2 | Intel       | Xeon E7 v4/Xeon E5 v4/Xeo... | 197   |
| pci:8086-6fe3 | Intel       | Xeon E7 v4/Xeon E5 v4/Xeo... | 197   |
| pci:8086-6f68 | Intel       | Xeon E7 v4/Xeon E5 v4/Xeo... | 181   |
| pci:8086-6f6e | Intel       | Xeon E7 v4/Xeon E5 v4/Xeo... | 181   |
| pci:8086-6f6f | Intel       | Xeon E7 v4/Xeon E5 v4/Xeo... | 181   |
| pci:8086-6fb8 | Intel       | Xeon E7 v4/Xeon E5 v4/Xeo... | 181   |
| pci:8086-6fb9 | Intel       | Xeon E7 v4/Xeon E5 v4/Xeo... | 181   |
| pci:8086-6fba | Intel       | Xeon E7 v4/Xeon E5 v4/Xeo... | 181   |
| pci:8086-6fbb | Intel       | Xeon E7 v4/Xeon E5 v4/Xeo... | 181   |
| pci:8086-6fd0 | Intel       | Xeon E7 v4/Xeon E5 v4/Xeo... | 181   |
| pci:8086-6ff9 | Intel       | Xeon E7 v4/Xeon E5 v4/Xeo... | 181   |
| pci:8086-6fe4 | Intel       | Xeon E7 v4/Xeon E5 v4/Xeo... | 179   |
| pci:8086-6fe5 | Intel       | Xeon E7 v4/Xeon E5 v4/Xeo... | 179   |
| pci:8086-6fac | Intel       | Xeon E7 v4/Xeon E5 v4/Xeo... | 165   |
| pci:8086-6fad | Intel       | Xeon E7 v4/Xeon E5 v4/Xeo... | 165   |
| pci:8086-6fb4 | Intel       | Xeon E7 v4/Xeon E5 v4/Xeo... | 165   |
| pci:8086-6fb5 | Intel       | Xeon E7 v4/Xeon E5 v4/Xeo... | 165   |
| pci:8086-6fb6 | Intel       | Xeon E7 v4/Xeon E5 v4/Xeo... | 165   |
| pci:8086-6fb7 | Intel       | Xeon E7 v4/Xeon E5 v4/Xeo... | 165   |
| pci:8086-3c20 | Intel       | Xeon E5/Core i7 DMA Chann... | 162   |
| pci:8086-3c21 | Intel       | Xeon E5/Core i7 DMA Chann... | 162   |
| pci:8086-3c22 | Intel       | Xeon E5/Core i7 DMA Chann... | 162   |
| pci:8086-3c23 | Intel       | Xeon E5/Core i7 DMA Chann... | 162   |
| pci:8086-3c24 | Intel       | Xeon E5/Core i7 DMA Chann... | 162   |
| pci:8086-3c25 | Intel       | Xeon E5/Core i7 DMA Chann... | 162   |
| pci:8086-3c26 | Intel       | Xeon E5/Core i7 DMA Chann... | 162   |
| pci:8086-3c27 | Intel       | Xeon E5/Core i7 DMA Chann... | 162   |
| pci:8086-2059 | Intel       | Sky Lake-E UPI Registers     | 159   |
| pci:103c-3306 | Hewlett-... | Integrated Lights-Out Sta... | 144   |
| pci:103c-3307 | Hewlett-... | Integrated Lights-Out Sta... | 144   |
| pci:8086-2f60 | Intel       | Xeon E7 v3/Xeon E5 v3/Cor... | 143   |
| pci:8086-2f6a | Intel       | Xeon E7 v3/Xeon E5 v3/Cor... | 143   |
| pci:8086-2f6b | Intel       | Xeon E7 v3/Xeon E5 v3/Cor... | 143   |
| pci:8086-2f79 | Intel       | Xeon E7 v3/Xeon E5 v3/Cor... | 143   |
| pci:8086-2fd1 | Intel       | Xeon E7 v3/Xeon E5 v3/Cor... | 143   |
| pci:8086-2fd2 | Intel       | Xeon E7 v3/Xeon E5 v3/Cor... | 143   |
| pci:8086-2fd3 | Intel       | Xeon E7 v3/Xeon E5 v3/Cor... | 143   |
| pci:8086-2ffa | Intel       | Xeon E7 v3/Xeon E5 v3/Cor... | 143   |
| pci:8086-2ffb | Intel       | Xeon E7 v3/Xeon E5 v3/Cor... | 143   |
| pci:8086-2fe8 | Intel       | Xeon E7 v3/Xeon E5 v3/Cor... | 141   |
| pci:8086-2fe9 | Intel       | Xeon E7 v3/Xeon E5 v3/Cor... | 141   |
| pci:1180-e232 | Ricoh       | PCIe Memory Stick Host Co... | 139   |
| pci:8086-0ee6 | Intel       | Xeon E7 v2/Xeon E5 v2/Cor... | 135   |
| pci:8086-0ee7 | Intel       | Xeon E7 v2/Xeon E5 v2/Cor... | 135   |
| pci:8086-0e20 | Intel       | Xeon E7 v2/Xeon E5 v2/Cor... | 129   |
| pci:8086-0e21 | Intel       | Xeon E7 v2/Xeon E5 v2/Cor... | 129   |
| pci:8086-0e22 | Intel       | Xeon E7 v2/Xeon E5 v2/Cor... | 129   |
| pci:8086-0e23 | Intel       | Xeon E7 v2/Xeon E5 v2/Cor... | 129   |
| pci:8086-0e24 | Intel       | Xeon E7 v2/Xeon E5 v2/Cor... | 129   |
| pci:8086-0e25 | Intel       | Xeon E7 v2/Xeon E5 v2/Cor... | 129   |
| pci:8086-0e26 | Intel       | Xeon E7 v2/Xeon E5 v2/Cor... | 129   |
| pci:8086-0e27 | Intel       | Xeon E7 v2/Xeon E5 v2/Cor... | 129   |
| pci:197b-2394 | JMicron ... | xD Host Controller           | 127   |
| pci:8086-2fea | Intel       | Xeon E7 v3/Xeon E5 v3/Cor... | 112   |
| pci:8086-2feb | Intel       | Xeon E7 v3/Xeon E5 v3/Cor... | 112   |
| pci:8086-6fe6 | Intel       | Xeon E7 v4/Xeon E5 v4/Xeo... | 111   |
| pci:8086-6fe7 | Intel       | Xeon E7 v4/Xeon E5 v4/Xeo... | 111   |
| pci:8086-8a0d | Intel       | Ice Lake Thunderbolt 3 NH... | 101   |
| pci:8086-2f80 | Intel       | Xeon E7 v3/Xeon E5 v3/Cor... | 95    |
| pci:8086-2f83 | Intel       | Xeon E7 v3/Xeon E5 v3/Cor... | 95    |
| pci:8086-2f90 | Intel       | Xeon E7 v3/Xeon E5 v3/Cor... | 89    |
| pci:8086-2f93 | Intel       | Xeon E7 v3/Xeon E5 v3/Cor... | 89    |
| pci:8086-0ee8 | Intel       | Xeon E7 v2/Xeon E5 v2/Cor... | 84    |
| pci:8086-0ee9 | Intel       | Xeon E7 v2/Xeon E5 v2/Cor... | 84    |
| pci:8086-6fe8 | Intel       | Xeon E7 v4/Xeon E5 v4/Xeo... | 79    |
| pci:8086-6fe9 | Intel       | Xeon E7 v4/Xeon E5 v4/Xeo... | 79    |
| pci:8086-4c11 | Intel       | System peripheral            | 76    |
| pci:8086-8a11 | Intel       | System peripheral            | 73    |
| pci:8086-6f80 | Intel       | Xeon E7 v4/Xeon E5 v4/Xeo... | 70    |
| pci:8086-6f83 | Intel       | Xeon E7 v4/Xeon E5 v4/Xeo... | 70    |
| pci:8086-6f90 | Intel       | Xeon E7 v4/Xeon E5 v4/Xeo... | 70    |
| pci:8086-6f93 | Intel       | Xeon E7 v4/Xeon E5 v4/Xeo... | 70    |
| pci:8086-1575 | Intel       | DSL6340 Thunderbolt 3 NHI... | 60    |
| pci:8086-1a38 | Intel       | 5000 Series Chipset DMA E... | 54    |
| pci:0e11-b203 | Compaq C... | Integrated Lights Out Con... | 53    |
| pci:0e11-b204 | Compaq C... | Integrated Lights Out  Pr... | 53    |
| pci:8086-6f20 | Intel       | Xeon E7 v4/Xeon E5 v4/Xeo... | 52    |
| pci:8086-6f21 | Intel       | Xeon E7 v4/Xeon E5 v4/Xeo... | 52    |
| pci:8086-6f22 | Intel       | Xeon E7 v4/Xeon E5 v4/Xeo... | 52    |
| pci:8086-6f23 | Intel       | Xeon E7 v4/Xeon E5 v4/Xeo... | 52    |
| pci:8086-6f24 | Intel       | Xeon E7 v4/Xeon E5 v4/Xeo... | 52    |
| pci:8086-6f25 | Intel       | Xeon E7 v4/Xeon E5 v4/Xeo... | 52    |
| pci:8086-6f26 | Intel       | Xeon E7 v4/Xeon E5 v4/Xeo... | 52    |
| pci:8086-6f27 | Intel       | Xeon E7 v4/Xeon E5 v4/Xeo... | 52    |
| pci:8086-4e11 | Intel       | System peripheral            | 42    |
| pci:8086-2f20 | Intel       | Xeon E7 v3/Xeon E5 v3/Cor... | 41    |
| pci:8086-2f21 | Intel       | Xeon E7 v3/Xeon E5 v3/Cor... | 41    |
| pci:8086-2f22 | Intel       | Xeon E7 v3/Xeon E5 v3/Cor... | 41    |
| pci:8086-2f23 | Intel       | Xeon E7 v3/Xeon E5 v3/Cor... | 41    |
| pci:8086-2f24 | Intel       | Xeon E7 v3/Xeon E5 v3/Cor... | 41    |
| pci:8086-2f25 | Intel       | Xeon E7 v3/Xeon E5 v3/Cor... | 41    |
| pci:8086-2f26 | Intel       | Xeon E7 v3/Xeon E5 v3/Cor... | 41    |
| pci:8086-2f27 | Intel       | Xeon E7 v3/Xeon E5 v3/Cor... | 41    |
| pci:8086-6fea | Intel       | Xeon E7 v4/Xeon E5 v4/Xeo... | 40    |
| pci:8086-6feb | Intel       | Xeon E7 v4/Xeon E5 v4/Xeo... | 40    |
| pci:8086-402f | Intel       | 5400 Chipset QuickData Te... | 39    |
| pci:8086-6f60 | Intel       | Xeon E7 v4/Xeon E5 v4/Xeo... | 38    |
| pci:8086-6f6a | Intel       | Xeon E7 v4/Xeon E5 v4/Xeo... | 38    |
| pci:8086-6f6b | Intel       | Xeon E7 v4/Xeon E5 v4/Xeo... | 38    |
| pci:8086-6f79 | Intel       | Xeon E7 v4/Xeon E5 v4/Xeo... | 38    |
| pci:8086-6fd1 | Intel       | Xeon E7 v4/Xeon E5 v4/Xeo... | 38    |
| pci:8086-6fd2 | Intel       | Xeon E7 v4/Xeon E5 v4/Xeo... | 38    |
| pci:8086-6fd3 | Intel       | Xeon E7 v4/Xeon E5 v4/Xeo... | 38    |
| pci:8086-6ffa | Intel       | Xeon E7 v4/Xeon E5 v4/Xeo... | 38    |
| pci:8086-6ffb | Intel       | Xeon E7 v4/Xeon E5 v4/Xeo... | 38    |
| pci:8086-3584 | Intel       | 82852/82855 GM/GME/PM/GMV... | 36    |
| pci:8086-3585 | Intel       | 82852/82855 GM/GME/PM/GMV... | 36    |
| pci:8086-464f | Intel       | 12th Gen Core Processor G... | 35    |
| pci:8086-2f70 | Intel       | Xeon E7 v3/Xeon E5 v3/Cor... | 33    |
| pci:8086-6fec | Intel       | Xeon E7 v4/Xeon E5 v4/Xeo... | 33    |
| pci:8086-6fed | Intel       | Xeon E7 v4/Xeon E5 v4/Xeo... | 33    |
| pci:8086-0e29 | Intel       | Xeon E7 v2/Xeon E5 v2/Cor... | 22    |
| pci:8086-0e60 | Intel       | Xeon E7 v2/Xeon E5 v2/Cor... | 22    |
| pci:8086-0e68 | Intel       | Xeon E7 v2/Xeon E5 v2/Cor... | 22    |
| pci:8086-0e6a | Intel       | Xeon E7 v2/Xeon E5 v2/Cor... | 22    |
| pci:8086-0e6b | Intel       | Xeon E7 v2/Xeon E5 v2/Cor... | 22    |
| pci:8086-0e6c | Intel       | Xeon E7 v2/Xeon E5 v2/Cor... | 22    |
| pci:8086-0e6d | Intel       | Xeon E7 v2/Xeon E5 v2/Cor... | 22    |
| pci:8086-0e79 | Intel       | Xeon E7 v2/Xeon E5 v2/Cor... | 22    |
| pci:8086-0e83 | Intel       | Xeon E7 v2/Xeon E5 v2/Cor... | 22    |
| pci:8086-0e84 | Intel       | Xeon E7 v2/Xeon E5 v2/Cor... | 22    |
| pci:8086-0e93 | Intel       | Xeon E7 v2/Xeon E5 v2/Cor... | 22    |
| pci:8086-0e94 | Intel       | Xeon E7 v2/Xeon E5 v2/Cor... | 22    |
| pci:8086-0eea | Intel       | Xeon E7 v2/Xeon E5 v2/Cor... | 22    |
| pci:8086-0eeb | Intel       | Xeon E7 v2/Xeon E5 v2/Cor... | 22    |
| pci:8086-0ef0 | Intel       | Xeon E7 v2/Xeon E5 v2/Cor... | 22    |
| pci:8086-0ef1 | Intel       | Xeon E7 v2/Xeon E5 v2/Cor... | 22    |
| pci:8086-0ef2 | Intel       | Xeon E7 v2/Xeon E5 v2/Cor... | 22    |
| pci:8086-0ef3 | Intel       | Xeon E7 v2/Xeon E5 v2/Cor... | 22    |
| pci:8086-0ef4 | Intel       | Xeon E7 v2/Xeon E5 v2/Cor... | 22    |
| pci:8086-0ef5 | Intel       | Xeon E7 v2/Xeon E5 v2/Cor... | 22    |
| pci:8086-0ef7 | Intel       | Xeon E7 v2/Xeon E5 v2/Cor... | 22    |
| pci:8086-1577 | Intel       | DSL6540 Thunderbolt 3 NHI... | 21    |
| pci:8086-6f50 | Intel       | Xeon Processor D Family Q... | 20    |
| pci:8086-6f51 | Intel       | Xeon Processor D Family Q... | 20    |
| pci:8086-6f52 | Intel       | Xeon Processor D Family Q... | 20    |
| pci:8086-6f53 | Intel       | Xeon Processor D Family Q... | 20    |
| pci:8086-6fee | Intel       | Xeon E7 v4/Xeon E5 v4/Xeo... | 20    |
| pci:8086-6fef | Intel       | Xeon E7 v4/Xeon E5 v4/Xeo... | 20    |
| pci:8086-0ef6 | Intel       | Xeon E7 v2/Xeon E5 v2/Cor... | 19    |
| pci:8086-0eb8 | Intel       | System peripheral            | 17    |
| pci:8086-6f70 | Intel       | Xeon E7 v4/Xeon E5 v4/Xeo... | 17    |
| pci:197b-2387 | JMicron ... | SD/MMC Host Controller       | 15    |
| pci:197b-2388 | JMicron ... | MS Host Controller           | 15    |
| pci:197b-2389 | JMicron ... | xD Host Controller           | 15    |
| pci:8086-2fec | Intel       | Xeon E7 v3/Xeon E5 v3/Cor... | 15    |
| pci:8086-2fed | Intel       | Xeon E7 v3/Xeon E5 v3/Cor... | 15    |
| pci:8086-257e | Intel       | 82875P/E7210 Processor to... | 14    |
| pci:8086-0eae | Intel       | Xeon E7 v2/Xeon E5 v2/Cor... | 13    |
| pci:8086-1f15 | Intel       | Atom processor C2000 SMBu... | 13    |
| pci:8086-6ff0 | Intel       | Xeon E7 v4/Xeon E5 v4/Xeo... | 13    |
| pci:8086-6ff1 | Intel       | Xeon E7 v4/Xeon E5 v4/Xeo... | 13    |
| pci:8086-2f78 | Intel       | Xeon E7 v3/Xeon E5 v3/Cor... | 12    |
| pci:8086-3c86 | Intel       | Sandy Bridge QPI Port 0 D... | 10    |
| pci:8086-3c96 | Intel       | Sandy Bridge QPI Port 1 D... | 10    |
| pci:8086-15de | Intel       | JHL6340 Thunderbolt 3 Con... | 8     |
| pci:8086-19ac | Intel       | Atom Processor C3000 Seri... | 8     |
| pci:19e5-a122 | Huawei T... | HiSilicon Embedded DMA En... | 7     |
| pci:8086-0e86 | Intel       | System peripheral            | 7     |
| pci:8086-0e96 | Intel       | System peripheral            | 7     |
| pci:1179-0805 | Toshiba ... | SD TypA Controller           | 6     |
| pci:8086-6f78 | Intel       | Xeon E7 v4/Xeon E5 v4/Xeo... | 6     |
| pci:104c-8201 | Texas In... | PCI1620 Firmware Loading ... | 5     |
| pci:1217-7110 | O2 Micro    | OZ711Mx 4-in-1 MemoryCard... | 5     |
| pci:1ac1-089a | Global U... | Coral Edge TPU               | 5     |
| pci:8086-0e10 | Intel       | Xeon E7 v2/Xeon E5 v2/Cor... | 5     |
| pci:8086-0e11 | Intel       | System peripheral            | 5     |
| pci:8086-0e12 | Intel       | System peripheral            | 5     |
| pci:8086-0e13 | Intel       | Xeon E7 v2/Xeon E5 v2/Cor... | 5     |
| pci:8086-0e14 | Intel       | System peripheral            | 5     |
| pci:8086-0e15 | Intel       | System peripheral            | 5     |
| pci:8086-0e16 | Intel       | System peripheral            | 5     |
| pci:8086-0e17 | Intel       | Xeon E7 v2/Xeon E5 v2/Cor... | 5     |
| pci:8086-0e18 | Intel       | Xeon E7 v2/Xeon E5 v2/Cor... | 5     |
| pci:8086-0e19 | Intel       | System peripheral            | 5     |
| pci:8086-0e1a | Intel       | System peripheral            | 5     |
| pci:8086-0e1b | Intel       | System peripheral            | 5     |
| pci:8086-0e1c | Intel       | Xeon E7 v2/Xeon E5 v2/Cor... | 5     |
| pci:8086-0e85 | Intel       | Xeon E7 v2/Xeon E5 v2/Cor... | 5     |
| pci:8086-0e87 | Intel       | Xeon E7 v2/Xeon E5 v2/Cor... | 5     |
| pci:8086-0e95 | Intel       | Xeon E7 v2/Xeon E5 v2/Cor... | 5     |
| pci:8086-157d | Intel       | DSL5110 Thunderbolt 2 NHI... | 5     |
| pci:8086-25ab | Intel       | 6300ESB Watchdog Timer       | 5     |
| pci:8086-2fee | Intel       | Xeon E7 v3/Xeon E5 v3/Cor... | 5     |
| pci:8086-2fef | Intel       | Xeon E7 v3/Xeon E5 v3/Cor... | 5     |
| pci:8086-09a2 | Intel       | System peripheral            | 4     |
| pci:8086-09a3 | Intel       | System peripheral            | 4     |
| pci:8086-09a4 | Intel       | System peripheral            | 4     |
| pci:8086-09a6 | Intel       | System peripheral            | 4     |
| pci:8086-09a7 | Intel       | Mini CTA                     | 4     |
| pci:8086-0e78 | Intel       | System peripheral            | 4     |
| pci:8086-0e98 | Intel       | System peripheral            | 4     |
| pci:8086-0e99 | Intel       | System peripheral            | 4     |
| pci:8086-0e9a | Intel       | System peripheral            | 4     |
| pci:8086-0e9b | Intel       | System peripheral            | 4     |
| pci:8086-1568 | Intel       | DSL4510 Thunderbolt NHI [... | 4     |
| pci:8086-2ff0 | Intel       | Xeon E7 v3/Xeon E5 v3/Cor... | 4     |
| pci:8086-2ff1 | Intel       | Xeon E7 v3/Xeon E5 v3/Cor... | 4     |
| pci:8086-344f | Intel       | System peripheral            | 4     |
| pci:8086-3457 | Intel       | System peripheral            | 4     |
| pci:104c-8204 | Texas In... | PCI7410/7510/7610 PCI Fir... | 3     |
| pci:8086-0813 | Intel       | Moorestown SC DMA            | 3     |
| pci:8086-09a8 | Intel       | System peripheral            | 3     |
| pci:8086-3594 | Intel       | E7520 DMA Controller         | 3     |
| pci:0014-7a0b | Loongson... | SPI Controller               | 2     |
| pci:1180-0576 | Ricoh       | R5C576 SD Bus Host Adapter   | 2     |
| pci:8086-0b00 | Intel       | System peripheral            | 2     |
| pci:8086-0b25 | Intel       | System peripheral            | 2     |
| pci:8086-0cfe | Intel       | System peripheral            | 2     |
| pci:8086-1566 | Intel       | DSL4410 Thunderbolt NHI [... | 2     |
| pci:8086-1bff | Intel       | System peripheral            | 2     |
| pci:8086-3240 | Intel       | System peripheral            | 2     |
| pci:8086-3241 | Intel       | System peripheral            | 2     |
| pci:8086-3242 | Intel       | System peripheral            | 2     |
| pci:8086-3245 | Intel       | System peripheral            | 2     |
| pci:8086-3246 | Intel       | System peripheral            | 2     |
| pci:8086-3247 | Intel       | System peripheral            | 2     |
| pci:8086-324c | Intel       | System peripheral            | 2     |
| pci:8086-324d | Intel       | System peripheral            | 2     |
| pci:8086-3250 | Intel       | System peripheral            | 2     |
| pci:8086-3251 | Intel       | System peripheral            | 2     |
| pci:8086-3252 | Intel       | System peripheral            | 2     |
| pci:8086-3255 | Intel       | System peripheral            | 2     |
| pci:8086-3258 | Intel       | System peripheral            | 2     |
| pci:8086-3259 | Intel       | System peripheral            | 2     |
| pci:8086-325a | Intel       | System peripheral            | 2     |
| pci:8086-325b | Intel       | System peripheral            | 2     |
| pci:8086-325c | Intel       | System peripheral            | 2     |
| pci:8086-325d | Intel       | System peripheral            | 2     |
| pci:8086-325e | Intel       | System peripheral            | 2     |
| pci:8086-325f | Intel       | System peripheral            | 2     |
| pci:8086-3440 | Intel       | System peripheral            | 2     |
| pci:8086-3441 | Intel       | System peripheral            | 2     |
| pci:8086-3442 | Intel       | System peripheral            | 2     |
| pci:8086-3443 | Intel       | System peripheral            | 2     |
| pci:8086-3445 | Intel       | System peripheral            | 2     |
| pci:8086-3446 | Intel       | System peripheral            | 2     |
| pci:8086-3447 | Intel       | System peripheral            | 2     |
| pci:8086-3448 | Intel       | System peripheral            | 2     |
| pci:8086-344b | Intel       | System peripheral            | 2     |
| pci:8086-344c | Intel       | System peripheral            | 2     |
| pci:8086-344d | Intel       | System peripheral            | 2     |
| pci:8086-3450 | Intel       | System peripheral            | 2     |
| pci:8086-3451 | Intel       | System peripheral            | 2     |
| pci:8086-3452 | Intel       | System peripheral            | 2     |
| pci:8086-3455 | Intel       | System peripheral            | 2     |
| pci:8086-3458 | Intel       | System peripheral            | 2     |
| pci:8086-3459 | Intel       | System peripheral            | 2     |
| pci:8086-345a | Intel       | System peripheral            | 2     |
| pci:8086-345b | Intel       | System peripheral            | 2     |
| pci:8086-345c | Intel       | System peripheral            | 2     |
| pci:8086-345d | Intel       | System peripheral            | 2     |
| pci:8086-345e | Intel       | System peripheral            | 2     |
| pci:8086-345f | Intel       | System peripheral            | 2     |
| pci:8086-5a11 | Intel       | System peripheral            | 2     |
| pci:8086-65ff | Intel       | 5100 Chipset DMA Engine      | 2     |
| pci:8086-6f10 | Intel       | Xeon E7 v4/Xeon E5 v4/Xeo... | 2     |
| pci:8086-6f11 | Intel       | Xeon E7 v4/Xeon E5 v4/Xeo... | 2     |
| pci:8086-6f12 | Intel       | Xeon E7 v4/Xeon E5 v4/Xeo... | 2     |
| pci:8086-6f13 | Intel       | Xeon E7 v4/Xeon E5 v4/Xeo... | 2     |
| pci:8086-6f14 | Intel       | Xeon E7 v4/Xeon E5 v4/Xeo... | 2     |
| pci:8086-6f15 | Intel       | Xeon E7 v4/Xeon E5 v4/Xeo... | 2     |
| pci:8086-6f16 | Intel       | Xeon E7 v4/Xeon E5 v4/Xeo... | 2     |
| pci:8086-6f17 | Intel       | Xeon E7 v4/Xeon E5 v4/Xeo... | 2     |
| pci:8086-6f18 | Intel       | Xeon E7 v4/Xeon E5 v4/Xeo... | 2     |
| pci:8086-6f19 | Intel       | Xeon E7 v4/Xeon E5 v4/Xeo... | 2     |
| pci:8086-6f1a | Intel       | Xeon E7 v4/Xeon E5 v4/Xeo... | 2     |
| pci:8086-6f1b | Intel       | Xeon E7 v4/Xeon E5 v4/Xeo... | 2     |
| pci:8086-6f1c | Intel       | Xeon E7 v4/Xeon E5 v4/Xeo... | 2     |
| pci:8086-6f6c | Intel       | Xeon E7 v4/Xeon E5 v4/Xeo... | 2     |
| pci:8086-6f6d | Intel       | Xeon E7 v4/Xeon E5 v4/Xeo... | 2     |
| pci:8086-6f85 | Intel       | Xeon E7 v4/Xeon E5 v4/Xeo... | 2     |
| pci:8086-6f86 | Intel       | Xeon E7 v4/Xeon E5 v4/Xeo... | 2     |
| pci:8086-6f87 | Intel       | Xeon E7 v4/Xeon E5 v4/Xeo... | 2     |
| pci:8086-6f95 | Intel       | Xeon E7 v4/Xeon E5 v4/Xeo... | 2     |
| pci:8086-6f96 | Intel       | Xeon E7 v4/Xeon E5 v4/Xeo... | 2     |
| pci:8086-6fd4 | Intel       | Xeon E7 v4/Xeon E5 v4/Xeo... | 2     |
| pci:8086-6fd5 | Intel       | Xeon E7 v4/Xeon E5 v4/Xeo... | 2     |
| pci:8086-6fd6 | Intel       | Xeon E7 v4/Xeon E5 v4/Xeo... | 2     |
| pci:8086-6fd7 | Intel       | Xeon E7 v4/Xeon E5 v4/Xeo... | 2     |
| pci:8086-7810 | Intel       | Xeon Phi x200 product fam... | 2     |
| pci:8086-7812 | Intel       | Xeon Phi x200 product fam... | 2     |
| pci:8086-7816 | Intel       | Xeon Phi x200 product fam... | 2     |
| pci:8086-781a | Intel       | Xeon Phi x200 product fam... | 2     |
| pci:8086-781c | Intel       | Xeon Phi x200 product fam... | 2     |
| pci:8086-781f | Intel       | Xeon Phi x200 product fam... | 2     |
| pci:8086-7820 | Intel       | Xeon Phi x200 product fam... | 2     |
| pci:8086-7821 | Intel       | Xeon Phi x200 product fam... | 2     |
| pci:8086-7822 | Intel       | Xeon Phi x200 product fam... | 2     |
| pci:8086-7823 | Intel       | Xeon Phi x200 product fam... | 2     |
| pci:8086-7824 | Intel       | Xeon Phi x200 product fam... | 2     |
| pci:8086-7825 | Intel       | Xeon Phi x200 product fam... | 2     |
| pci:8086-7826 | Intel       | Xeon Phi x200 product fam... | 2     |
| pci:8086-782a | Intel       | Xeon Phi x200 product fam... | 2     |
| pci:8086-782b | Intel       | Xeon Phi x200 product fam... | 2     |
| pci:8086-782c | Intel       | Xeon Phi x200 product fam... | 2     |
| pci:8086-782d | Intel       | Xeon Phi x200 product fam... | 2     |
| pci:8086-782e | Intel       | Xeon Phi x200 product fam... | 2     |
| pci:8086-782f | Intel       | Xeon Phi x200 product fam... | 2     |
| pci:8086-7831 | Intel       | Xeon Phi x200 product fam... | 2     |
| pci:8086-7833 | Intel       | Xeon Phi x200 product fam... | 2     |
| pci:8086-7835 | Intel       | Xeon Phi x200 product fam... | 2     |
| pci:8086-7837 | Intel       | Xeon Phi x200 product fam... | 2     |
| pci:8086-7839 | Intel       | Xeon Phi x200 product fam... | 2     |
| pci:8086-7840 | Intel       | Xeon Phi x200 product fam... | 2     |
| pci:8086-7841 | Intel       | Xeon Phi x200 product fam... | 2     |
| pci:8086-7842 | Intel       | Xeon Phi x200 product fam... | 2     |
| pci:8086-7843 | Intel       | Xeon Phi x200 product fam... | 2     |
| pci:8086-7844 | Intel       | Xeon Phi x200 product fam... | 2     |
| pci:8086-7845 | Intel       | Xeon Phi x200 product fam... | 2     |
| pci:8086-7846 | Intel       | Xeon Phi x200 product fam... | 2     |
| pci:8086-7847 | Intel       | Xeon Phi x200 product fam... | 2     |
| pci:8086-7848 | Intel       | Xeon Phi x200 product fam... | 2     |
| pci:8086-7849 | Intel       | Xeon Phi x200 product fam... | 2     |
| pci:0180-0592 | Unknown     | System peripheral            | 1     |
| pci:0180-0843 | Unknown     | System peripheral            | 1     |
| pci:0180-0852 | Unknown     | System peripheral            | 1     |
| pci:0e11-a0f0 | Compaq C... | Advanced System Managemen... | 1     |
| pci:1014-0295 | IBM         | System peripheral            | 1     |
| pci:104d-90c8 | Sony        | Belize ACPI                  | 1     |
| pci:104d-90c9 | Sony        | Belize Ethernet Controller   | 1     |
| pci:104d-90ca | Sony        | Belize SATA AHCI Controller  | 1     |
| pci:104d-90cb | Sony        | Belize SD/MMC Host Contro... | 1     |
| pci:104d-90cc | Sony        | Belize PCI Express Glue a... | 1     |
| pci:104d-90cd | Sony        | Belize DMA Controller        | 1     |
| pci:104d-90ce | Sony        | Belize Memory (DDR3/SPM)     | 1     |
| pci:104d-90cf | Sony        | Belize USB 3.0 xHCI Host ... | 1     |
| pci:104d-90d7 | Sony        | Baikal ACPI                  | 1     |
| pci:104d-90d8 | Sony        | Baikal Ethernet Controller   | 1     |
| pci:104d-90d9 | Sony        | Baikal SATA AHCI Controller  | 1     |
| pci:104d-90da | Sony        | Baikal SD/MMC Host Contro... | 1     |
| pci:104d-90db | Sony        | Baikal PCI Express Glue a... | 1     |
| pci:104d-90dc | Sony        | Baikal DMA Controller        | 1     |
| pci:104d-90dd | Sony        | Baikal Memory (DDR3/SPM)     | 1     |
| pci:104d-90de | Sony        | Baikal USB 3.0 xHCI Host ... | 1     |
| pci:10b5-2065 | PLX Tech... | System peripheral            | 1     |
| pci:10b5-87d0 | PLX Tech... | PEX PCI Express Switch DM... | 1     |
| pci:14e4-114a | Broadcom    | System peripheral            | 1     |
| pci:19e5-a124 | Huawei T... | HiSilicon Internal SDI Fu... | 1     |
| pci:19e5-a12b | Huawei T... | System peripheral            | 1     |
| pci:8086-1193 | Intel       | System peripheral            | 1     |
| pci:8086-1194 | Intel       | Merrifield Serial IO SPI ... | 1     |
| pci:8086-1199 | Intel       | Merrifield GPIO Controller   | 1     |
| pci:8086-119b | Intel       | System peripheral            | 1     |
| pci:8086-11a2 | Intel       | Merrifield Serial IO DMA ... | 1     |
| pci:8086-11a5 | Intel       | Merrifield Serial IO PWM ... | 1     |
| pci:8086-15dd | Intel       | JHL6340 Thunderbolt 3 Con... | 1     |
| pci:8086-2f10 | Intel       | Xeon E7 v3/Xeon E5 v3/Cor... | 1     |
| pci:8086-2f11 | Intel       | Xeon E7 v3/Xeon E5 v3/Cor... | 1     |
| pci:8086-2f12 | Intel       | Xeon E7 v3/Xeon E5 v3/Cor... | 1     |
| pci:8086-2f13 | Intel       | Xeon E7 v3/Xeon E5 v3/Cor... | 1     |
| pci:8086-2f14 | Intel       | Xeon E7 v3/Xeon E5 v3/Cor... | 1     |
| pci:8086-2f15 | Intel       | Xeon E7 v3/Xeon E5 v3/Cor... | 1     |
| pci:8086-2f16 | Intel       | Xeon E7 v3/Xeon E5 v3/Cor... | 1     |
| pci:8086-2f17 | Intel       | Xeon E7 v3/Xeon E5 v3/Cor... | 1     |
| pci:8086-2f18 | Intel       | Xeon E7 v3/Xeon E5 v3/Cor... | 1     |
| pci:8086-2f19 | Intel       | Xeon E7 v3/Xeon E5 v3/Cor... | 1     |
| pci:8086-2f1a | Intel       | Xeon E7 v3/Xeon E5 v3/Cor... | 1     |
| pci:8086-2f1b | Intel       | Xeon E7 v3/Xeon E5 v3/Cor... | 1     |
| pci:8086-2f1c | Intel       | Xeon E7 v3/Xeon E5 v3/Cor... | 1     |
| pci:8086-35b5 | Intel       | 3100 Chipset Enhanced DMA... | 1     |
| pci:8086-3712 | Intel       | Xeon C5500/C3500 CB3 DMA     | 1     |
| pci:8086-3713 | Intel       | Xeon C5500/C3500 CB3 DMA     | 1     |
| pci:8086-3714 | Intel       | Xeon C5500/C3500 CB3 DMA     | 1     |
| pci:8086-3715 | Intel       | Xeon C5500/C3500 CB3 DMA     | 1     |
| pci:8086-3716 | Intel       | Xeon C5500/C3500 CB3 DMA     | 1     |
| pci:8086-3717 | Intel       | Xeon C5500/C3500 CB3 DMA     | 1     |
| pci:8086-3718 | Intel       | Xeon C5500/C3500 CB3 DMA     | 1     |
| pci:8086-3719 | Intel       | Xeon C5500/C3500 CB3 DMA     | 1     |
| pci:8086-371a | Intel       | Xeon C5500/C3500 QPI Link    | 1     |
| pci:8086-371b | Intel       | Xeon C5500/C3500 QPI Rout... | 1     |
| pci:8086-371d | Intel       | Xeon C5500/C3500 QPI Rout... | 1     |
| pci:8086-3728 | Intel       | Xeon C5500/C3500 Core        | 1     |
| pci:8086-3729 | Intel       | Xeon C5500/C3500 Core        | 1     |
| pci:8086-372a | Intel       | Xeon C5500/C3500 Core        | 1     |
| pci:8086-372b | Intel       | Xeon C5500/C3500 Core        | 1     |
| pci:8086-372c | Intel       | Xeon C5500/C3500 Reserved    | 1     |

### Tv card (PCI)

Total devices: 1263

| ID            | MFG         | Name                         | Count |
|---------------|-------------|------------------------------|-------|
| pci:1131-7133 | Philips ... | SAA7131/SAA7133/SAA7135 V... | 340   |
| pci:1131-7134 | Philips ... | SAA7134/SAA7135HL Video B... | 135   |
| pci:14f1-8800 | Conexant... | CX23880/1/2/3 PCI Video a... | 125   |
| pci:109e-036e | Brooktree   | Bt878 Video Capture          | 124   |
| pci:1131-7130 | Philips ... | SAA7130 Video Broadcast D... | 109   |
| pci:14f1-8880 | Conexant... | CX23887/8 PCIe Broadcast ... | 108   |
| pci:14f1-8802 | Conexant... | CX23880/1/2/3 PCI Video a... | 94    |
| pci:14f1-8852 | Conexant... | CX23885 PCI Video and Aud... | 72    |
| pci:4444-0016 | Internex... | iTVC16 (CX23416) Video De... | 46    |
| pci:14f1-8801 | Conexant... | CX23880/1/2/3 PCI Video a... | 35    |
| pci:14f1-5b7a | Conexant... | CX23418 Single-Chip MPEG-... | 27    |
| pci:14f1-8811 | Conexant... | CX23880/1/2/3 PCI Video a... | 25    |
| pci:11de-6057 | Zoran       | ZR36057PQC Video cutting ... | 12    |
| pci:4444-0803 | Internex... | iTVC15 (CX23415) Video De... | 7     |
| pci:109e-0350 | Brooktree   | Bt848 Video Capture          | 3     |
| pci:109e-0351 | Brooktree   | Bt849A Video capture         | 1     |

### Unknown (PCI)

Total devices: 1270

| ID            | MFG         | Name                         | Count |
|---------------|-------------|------------------------------|-------|
| pci:8086-8d7c | Intel       | C610/X99 series chipset SPSR | 669   |
| pci:8086-a1ec | Intel       | C620 Series Chipset Famil... | 165   |
| pci:8086-a1ed | Intel       | C620 Series Chipset Famil... | 105   |
| pci:10ec-816e | Realtek ... | RealManage BMC               | 43    |
| pci:1002-694e | AMD         | Polaris 22 XL [Radeon RX ... | 38    |
| pci:8086-31a2 | Intel       | Celeron/Pentium Silver Pr... | 32    |
| pci:8086-5aa2 | Intel       | Celeron N3350/Pentium N42... | 32    |
| pci:10ec-5228 | Realtek ... |                              | 31    |
| pci:1af2-a001 | AVerMedia   | Live Gamer HD                | 17    |
| pci:1eac-1001 | Quectel ... | EM120R-GL LTE Modem          | 17    |
| pci:10ec-5261 | Realtek ... | PCIe Card Reader             | 13    |
| pci:8086-6ff2 | Intel       | Broadwell-E CBo Unicast R... | 10    |
| pci:8086-6ff3 | Intel       | Broadwell-E CBo Unicast R... | 10    |
| pci:8086-3591 | Intel       | E7525/E7520 Error Reporti... | 7     |
| pci:8086-6ff4 | Intel       | Broadwell-E CBo Unicast R... | 7     |
| pci:8086-6ff5 | Intel       | Broadwell-E CBo Unicast R... | 7     |
| pci:1000-fury | LSI Logi... | MegaRAID SAS-3 3008 [005f]   | 6     |
| pci:106b-003b | Apple       | UniNorth/Intrepid ATA/100    | 4     |
| pci:106b-003e | Apple       | KeyLargo/Intrepid Mac I/O    | 4     |
| pci:1912-001b | Renesas ... | SH7758 PCIe End-Point [PBI]  | 4     |
| pci:1971-0000 | AGEIA Te... | AGEIA PhysX 100 PCIe Card    | 3     |
| pci:106b-0022 | Apple       | KeyLargo Mac I/O             | 2     |
| pci:8086-10a6 | Intel       | 82599EB 10-Gigabit Dummy ... | 2     |
| pci:8086-2541 | Intel       | E7500/E7501 Host RASUM Co... | 2     |
| pci:0018-fd00 | Unknown     |                              | 1     |
| pci:0274-0371 | Unknown     |                              | 1     |
| pci:102f-0181 | Toshiba ... | TX4925 MIPS RISC PCI Cont... | 1     |
| pci:106b-0033 | Apple       | UniNorth 2 ATA/100           | 1     |
| pci:106b-0041 | Apple       | K2 KeyLargo Mac/IO           | 1     |
| pci:106b-0043 | Apple       | K2 ATA/100                   | 1     |
| pci:106b-004f | Apple       | Shasta Mac I/O               | 1     |
| pci:106b-0050 | Apple       | Shasta IDE                   | 1     |
| pci:1093-2a70 | National... | PCI-6024E                    | 1     |
| pci:10b5-2091 | PLX Tech... |                              | 1     |
| pci:10ec      | Realtek ... | RTL8822BE 802.11a/b/g/n/a... | 1     |
| pci:1172-0005 | Altera      |                              | 1     |
| pci:1172-646c | Altera      | KT-500/KT-521 board          | 1     |
| pci:1217-6120 | O2 Micro    |                              | 1     |
| pci:127a-2014 | Rockwell... | HSF 56k Data/Fax/Voice Modem | 1     |
| pci:1306-3038 | Duet Tec... |                              | 1     |
| pci:13fe-1716 | Advantech   |                              | 1     |
| pci:13fe-1751 | Advantech   |                              | 1     |
| pci:144a-5101 | Adlink T... |                              | 1     |
| pci:149d-0102 | NEWTEK      |                              | 1     |
| pci:14f1-2520 | Conexant... |                              | 1     |
| pci:1684-0029 | Unknown     |                              | 1     |
| pci:17b6-0229 | GE Medic... |                              | 1     |
| pci:17b6-2000 | GE Medic... |                              | 1     |
| pci:17cb-0306 | Qualcomm    |                              | 1     |
| pci:17fe-a220 | InProComm   |                              | 1     |
| pci:1931-1011 | Option N.V. |                              | 1     |
| pci:1a41-0200 | Tilera      | TILE-Gx processor            | 1     |
| pci:1a41-0201 | Tilera      | TILE-Gx Processor Virtual... | 1     |
| pci:1bb0-0010 | SimpliVity  | OmniCube Accelerator OA-3... | 1     |
| pci:1fc8-0be0 | Lucid In... | HYDRA 200                    | 1     |
| pci:494f-0100 | ACCES I/... |                              | 1     |
| pci:8037-cf10 |             |                              | 1     |
| pci:8086-1aa2 | Intel       | Integrated Sensor Solution   | 1     |
| pci:8086-2546 | Intel       | E7500/E7501 Hub Interface... | 1     |
| pci:8086-2551 | Intel       | E7505/E7205 Series RAS Co... | 1     |
| pci:8086-3593 | Intel       | E7320 Error Reporting Reg... | 1     |
| pci:8086-35b1 | Intel       | 3100 DRAM Controller Erro... | 1     |
| pci:80bb-0000 | Unknown     |                              | 1     |
| pci:9710-9825 | MosChip ... | Nm9825 Single PCI UART       | 1     |

### Usb controller (PCI)

Total devices: 387885

| ID            | MFG         | Name                         | Count |
|---------------|-------------|------------------------------|-------|
| pci:8086-1e26 | Intel       | 7 Series/C216 Chipset Fam... | 11167 |
| pci:8086-1e2d | Intel       | 7 Series/C216 Chipset Fam... | 11131 |
| pci:8086-1c26 | Intel       | 6 Series/C200 Series Chip... | 10974 |
| pci:8086-1c2d | Intel       | 6 Series/C200 Series Chip... | 10879 |
| pci:8086-1e31 | Intel       | 7 Series/C210 Series Chip... | 10024 |
| pci:8086-9d2f | Intel       | Sunrise Point-LP USB 3.0 ... | 9614  |
| pci:1002-4397 | AMD         | SB7x0/SB8x0/SB9x0 USB OHC... | 7415  |
| pci:1002-4396 | AMD         | SB7x0/SB8x0/SB9x0 USB EHC... | 7413  |
| pci:8086-27c8 | Intel       | NM10/ICH7 Family USB UHCI... | 7324  |
| pci:8086-27c9 | Intel       | NM10/ICH7 Family USB UHCI... | 7281  |
| pci:8086-27cc | Intel       | NM10/ICH7 Family USB2 EHC... | 7272  |
| pci:8086-27ca | Intel       | NM10/ICH7 Family USB UHCI... | 7216  |
| pci:8086-27cb | Intel       | NM10/ICH7 Family USB UHCI... | 7198  |
| pci:8086-8c31 | Intel       | 8 Series/C220 Series Chip... | 6647  |
| pci:8086-8c26 | Intel       | 8 Series/C220 Series Chip... | 6475  |
| pci:8086-8c2d | Intel       | 8 Series/C220 Series Chip... | 6351  |
| pci:1002-4399 | AMD         | SB7x0/SB8x0/SB9x0 USB OHC... | 6231  |
| pci:8086-3b34 | Intel       | 5 Series/3400 Series Chip... | 5681  |
| pci:8086-3b3c | Intel       | 5 Series/3400 Series Chip... | 5676  |
| pci:8086-2934 | Intel       | 82801I (ICH9 Family) USB ... | 5515  |
| pci:8086-2935 | Intel       | 82801I (ICH9 Family) USB ... | 5515  |
| pci:8086-293a | Intel       | 82801I (ICH9 Family) USB2... | 5515  |
| pci:8086-2937 | Intel       | 82801I (ICH9 Family) USB ... | 5510  |
| pci:8086-293c | Intel       | 82801I (ICH9 Family) USB2... | 5510  |
| pci:1022-7808 | AMD         | FCH USB EHCI Controller      | 5475  |
| pci:8086-2936 | Intel       | 82801I (ICH9 Family) USB ... | 5420  |
| pci:8086-2938 | Intel       | 82801I (ICH9 Family) USB ... | 5338  |
| pci:8086-2939 | Intel       | 82801I (ICH9 Family) USB ... | 5207  |
| pci:8086-a12f | Intel       | 100 Series/C230 Series Ch... | 4911  |
| pci:8086-a36d | Intel       | Cannon Lake PCH USB 3.1 x... | 4746  |
| pci:1022-7807 | AMD         | FCH USB OHCI Controller      | 4470  |
| pci:1022-149c | AMD         | Matisse USB 3.0 Host Cont... | 3742  |
| pci:1033-0194 | NEC Comp... | uPD720200 USB 3.0 Host Co... | 3585  |
| pci:1022-15e0 | AMD         | Raven USB 3.1                | 3535  |
| pci:1022-15e1 | AMD         | Raven USB 3.1                | 3535  |
| pci:1002-4398 | AMD         | SB7x0 USB OHCI1 Controller   | 3490  |
| pci:8086-9c31 | Intel       | 8 Series USB xHCI HC         | 3381  |
| pci:1022-7814 | AMD         | FCH USB XHCI Controller      | 3124  |
| pci:8086-9c26 | Intel       | 8 Series USB EHCI #1         | 3036  |
| pci:8086-2830 | Intel       | 82801H (ICH8 Family) USB ... | 2942  |
| pci:8086-2831 | Intel       | 82801H (ICH8 Family) USB ... | 2942  |
| pci:8086-2836 | Intel       | 82801H (ICH8 Family) USB2... | 2942  |
| pci:8086-2834 | Intel       | 82801H (ICH8 Family) USB ... | 2884  |
| pci:8086-283a | Intel       | 82801H (ICH8 Family) USB2... | 2884  |
| pci:1022-1639 | AMD         | Renoir/Cezanne USB 3.1       | 2866  |
| pci:8086-2832 | Intel       | 82801H (ICH8 Family) USB ... | 2827  |
| pci:8086-2835 | Intel       | 82801H (ICH8 Family) USB ... | 2784  |
| pci:8086-9ded | Intel       | Cannon Point-LP USB 3.1 x... | 2683  |
| pci:8086-9cb1 | Intel       | Wildcat Point-LP USB xHCI... | 2679  |
| pci:1022-43d5 | AMD         | 400 Series Chipset USB 3.... | 2596  |
| pci:8086-22b5 | Intel       | Atom/Celeron/Pentium Proc... | 2438  |
| pci:1b21-1042 | ASMedia ... | ASM1042 SuperSpeed USB Ho... | 2298  |
| pci:8086-a2af | Intel       | 200 Series/Z370 Chipset F... | 2288  |
| pci:1106-3483 | VIA Tech... | VL805/806 xHCI USB 3.0 Co... | 2139  |
| pci:8086-3a34 | Intel       | 82801JI (ICH10 Family) US... | 2139  |
| pci:8086-3a35 | Intel       | 82801JI (ICH10 Family) US... | 2139  |
| pci:8086-3a36 | Intel       | 82801JI (ICH10 Family) US... | 2139  |
| pci:8086-3a3a | Intel       | 82801JI (ICH10 Family) US... | 2138  |
| pci:1022-7809 | AMD         | FCH USB OHCI Controller      | 2131  |
| pci:8086-3a39 | Intel       | 82801JI (ICH10 Family) US... | 2081  |
| pci:8086-3a37 | Intel       | 82801JI (ICH10 Family) US... | 2080  |
| pci:8086-3a3c | Intel       | 82801JI (ICH10 Family) US... | 2080  |
| pci:8086-3a38 | Intel       | 82801JI (ICH10 Family) US... | 2067  |
| pci:8086-0f35 | Intel       | Atom Processor Z36xxx/Z37... | 1982  |
| pci:8086-02ed | Intel       | Comet Lake PCH-LP USB 3.1... | 1844  |
| pci:8086-a0ed | Intel       | Tiger Lake-LP USB 3.2 Gen... | 1822  |
| pci:8086-9ca6 | Intel       | Wildcat Point-LP USB EHCI... | 1809  |
| pci:1022-145f | AMD         | Zeppelin USB 3.0 Host con... | 1691  |
| pci:1022-7914 | AMD         | FCH USB XHCI Controller      | 1683  |
| pci:1022-7908 | AMD         | FCH USB EHCI Controller      | 1622  |
| pci:8086-9a13 | Intel       | Tiger Lake-LP Thunderbolt... | 1579  |
| pci:10de-03f1 | Nvidia      | MCP61 USB 1.1 Controller     | 1550  |
| pci:10de-03f2 | Nvidia      | MCP61 USB 2.0 Controller     | 1550  |
| pci:1b21-1142 | ASMedia ... | ASM1042A USB 3.0 Host Con... | 1433  |
| pci:1b21-1242 | ASMedia ... | ASM1142 USB 3.1 Host Cont... | 1428  |
| pci:1022-7812 | AMD         | FCH USB XHCI Controller      | 1403  |
| pci:8086-31a8 | Intel       | Celeron/Pentium Silver Pr... | 1396  |
| pci:1022-145c | AMD         | Family 17h (Models 00h-0f... | 1338  |
| pci:8086-06ed | Intel       | Comet Lake USB 3.1 xHCI H... | 1334  |
| pci:8086-9a1b | Intel       | Tiger Lake-LP Thunderbolt... | 1194  |
| pci:10de-1aec | Nvidia      | TU116 USB 3.1 Host Contro... | 1167  |
| pci:10de-1ada | Nvidia      | TU106 USB 3.1 Host Contro... | 1162  |
| pci:1b21-2142 | ASMedia ... | ASM2142 USB 3.1 Host Cont... | 1111  |
| pci:8086-8cb1 | Intel       | 9 Series Chipset Family U... | 1034  |
| pci:8086-8ca6 | Intel       | 9 Series Chipset Family U... | 1031  |
| pci:8086-8cad | Intel       | 9 Series Chipset Family U... | 1021  |
| pci:8086-34ed | Intel       | Ice Lake-LP USB 3.1 xHCI ... | 1003  |
| pci:8086-5aa8 | Intel       | Celeron N3350/Pentium N42... | 971   |
| pci:1b6f-7023 | Etron Te... | EJ168 USB 3.0 Host Contro... | 921   |
| pci:1022-43ee | AMD         | 500 Series Chipset USB 3.... | 914   |
| pci:1022-43bb | AMD         | 300 Series Chipset USB 3.... | 905   |
| pci:1106-3038 | VIA Tech... | VT82xx/62xx/VX700/8x0/900... | 885   |
| pci:8086-15ec | Intel       | JHL7540 Thunderbolt 3 USB... | 885   |
| pci:1106-3104 | VIA Tech... | USB 2.0 EHCI-Compliant Ho... | 875   |
| pci:1022-43bc | AMD         | FCH USB 3.1 XHCI Host Con... | 870   |
| pci:8086-1d26 | Intel       | C600/X79 series chipset U... | 815   |
| pci:8086-1d2d | Intel       | C600/X79 series chipset U... | 798   |
| pci:8086-3a64 | Intel       | 82801JD/DO (ICH10 Family)... | 794   |
| pci:8086-3a65 | Intel       | 82801JD/DO (ICH10 Family)... | 794   |
| pci:8086-3a66 | Intel       | 82801JD/DO (ICH10 Family)... | 794   |
| pci:8086-3a67 | Intel       | 82801JD/DO (ICH10 Family)... | 794   |
| pci:8086-3a68 | Intel       | 82801JD/DO (ICH10 Family)... | 794   |
| pci:8086-3a69 | Intel       | 82801JD/DO (ICH10 Family)... | 794   |
| pci:8086-15d4 | Intel       | JHL6540 Thunderbolt 3 USB... | 793   |
| pci:8086-3a6a | Intel       | 82801JD/DO (ICH10 Family)... | 793   |
| pci:8086-3a6c | Intel       | 82801JD/DO (ICH10 Family)... | 793   |
| pci:1912-0015 | Renesas ... | uPD720202 USB 3.0 Host Co... | 766   |
| pci:8086-15db | Intel       | JHL6340 Thunderbolt 3 USB... | 741   |
| pci:8086-15e9 | Intel       | JHL7540 Thunderbolt 3 USB... | 717   |
| pci:10de-1ad8 | Nvidia      | TU104 USB 3.1 Host Contro... | 664   |
| pci:1002-4387 | AMD         | SB600 USB (OHCI0)            | 654   |
| pci:1002-4388 | AMD         | SB600 USB (OHCI1)            | 654   |
| pci:8086-8d26 | Intel       | C610/X99 series chipset U... | 654   |
| pci:1002-4386 | AMD         | SB600 USB Controller (EHCI)  | 653   |
| pci:1002-438b | AMD         | SB600 USB (OHCI4)            | 653   |
| pci:8086-8d2d | Intel       | C610/X99 series chipset U... | 653   |
| pci:1002-438a | AMD         | SB600 USB (OHCI3)            | 637   |
| pci:8086-8d31 | Intel       | C610/X99 series chipset U... | 636   |
| pci:1002-4389 | AMD         | SB600 USB (OHCI2)            | 634   |
| pci:1912-0014 | Renesas ... | uPD720201 USB 3.0 Host Co... | 592   |
| pci:8086-43ed | Intel       | Tiger Lake-H USB 3.2 Gen ... | 569   |
| pci:1022-43d0 | AMD         | FCH USB 3.1 XHCI Host Con... | 565   |
| pci:10de-0aa5 | Nvidia      | MCP79 OHCI USB 1.1 Contro... | 564   |
| pci:10de-0aa6 | Nvidia      | MCP79 EHCI USB 2.0 Contro... | 564   |
| pci:8086-15c1 | Intel       | JHL6240 Thunderbolt 3 USB... | 555   |
| pci:1b21-1343 | ASMedia ... | ASM1143 USB 3.1 Host Cont... | 531   |
| pci:8086-9a1d | Intel       | Tiger Lake-LP Thunderbolt... | 530   |
| pci:1039-7001 | Silicon ... | USB 1.1 Controller           | 515   |
| pci:1039-7002 | Silicon ... | USB 2.0 Controller           | 511   |
| pci:8086-2658 | Intel       | 82801FB/FBM/FR/FW/FRW (IC... | 510   |
| pci:8086-2659 | Intel       | 82801FB/FBM/FR/FW/FRW (IC... | 504   |
| pci:8086-265a | Intel       | 82801FB/FBM/FR/FW/FRW (IC... | 502   |
| pci:8086-265c | Intel       | 82801FB/FBM/FR/FW/FRW (IC... | 498   |
| pci:10de-0aa7 | Nvidia      | MCP79 OHCI USB 1.1 Contro... | 478   |
| pci:10de-0aa9 | Nvidia      | MCP79 EHCI USB 2.0 Contro... | 478   |
| pci:8086-265b | Intel       | 82801FB/FBM/FR/FW/FRW (IC... | 477   |
| pci:1022-43b9 | AMD         | X370 Series Chipset USB 3... | 475   |
| pci:8086-8a13 | Intel       | Ice Lake Thunderbolt 3 US... | 460   |
| pci:10ec-816d | Realtek ... | RTL811x EHCI host controller | 441   |
| pci:1022-15e5 | AMD         | Raven2 USB 3.1               | 401   |
| pci:8086-0f34 | Intel       | Atom Processor Z36xxx/Z37... | 395   |
| pci:104c-8241 | Texas In... | TUSB73x0 SuperSpeed USB 3... | 388   |
| pci:8086-3b36 | Intel       | 5 Series/3400 Series Chip... | 371   |
| pci:8086-3b3b | Intel       | 5 Series/3400 Series Chip... | 371   |
| pci:8086-1c27 | Intel       | 6 Series/C200 Series Chip... | 369   |
| pci:8086-1c2c | Intel       | 6 Series/C200 Series Chip... | 369   |
| pci:1b73-1100 | Fresco L... | FL1100 USB 3.0 Host Contr... | 358   |
| pci:10de-077b | Nvidia      | MCP78S [GeForce 8200] OHC... | 348   |
| pci:10de-077c | Nvidia      | MCP78S [GeForce 8200] EHC... | 348   |
| pci:10de-077d | Nvidia      | MCP78S [GeForce 8200] OHC... | 348   |
| pci:10de-077e | Nvidia      | MCP78S [GeForce 8200] EHC... | 348   |
| pci:8086-a3af | Intel       | Comet Lake PCH-V USB Cont... | 331   |
| pci:8086-24d2 | Intel       | 82801EB/ER (ICH5/ICH5R) U... | 297   |
| pci:8086-24d4 | Intel       | 82801EB/ER (ICH5/ICH5R) U... | 297   |
| pci:8086-24dd | Intel       | 82801EB/ER (ICH5/ICH5R) U... | 296   |
| pci:10de-026d | Nvidia      | MCP51 USB Controller         | 292   |
| pci:10de-026e | Nvidia      | MCP51 USB Controller         | 292   |
| pci:8086-24d7 | Intel       | 82801EB/ER (ICH5/ICH5R) U... | 290   |
| pci:8086-24de | Intel       | 82801EB/ER (ICH5/ICH5R) U... | 268   |
| pci:8086-3b37 | Intel       | 5 Series/3400 Series Chip... | 265   |
| pci:8086-3b38 | Intel       | 5 Series/3400 Series Chip... | 265   |
| pci:8086-3b3e | Intel       | 5 Series/3400 Series Chip... | 265   |
| pci:8086-3b3f | Intel       | 5 Series/3400 Series Chip... | 265   |
| pci:1b6f-7052 | Etron Te... | EJ188/EJ198 USB 3.0 Host ... | 264   |
| pci:1002-4374 | AMD         | IXP SB4x0 USB Host Contro... | 258   |
| pci:1002-4375 | AMD         | IXP SB4x0 USB Host Contro... | 258   |
| pci:1002-4373 | AMD         | IXP SB4x0 USB2 Host Contr... | 257   |
| pci:1033-0035 | NEC Comp... | OHCI USB Controller          | 245   |
| pci:1033-00e0 | NEC Comp... | uPD72010x USB 2.0 Controller | 242   |
| pci:10de-036c | Nvidia      | MCP55 USB Controller         | 225   |
| pci:10de-036d | Nvidia      | MCP55 USB Controller         | 225   |
| pci:8086-2688 | Intel       | 631xESB/632xESB/3100 Chip... | 217   |
| pci:8086-2689 | Intel       | 631xESB/632xESB/3100 Chip... | 217   |
| pci:8086-268a | Intel       | 631xESB/632xESB/3100 Chip... | 216   |
| pci:8086-268c | Intel       | 631xESB/632xESB/3100 Chip... | 216   |
| pci:8086-9a17 | Intel       | Tiger Lake-H Thunderbolt ... | 208   |
| pci:1106-3432 | VIA Tech... | VL800/801 xHCI USB 3.0 Co... | 207   |
| pci:8086-268b | Intel       | 631xESB/632xESB/3100 Chip... | 207   |
| pci:10de-005a | Nvidia      | CK804 USB Controller         | 195   |
| pci:10de-005b | Nvidia      | CK804 USB Controller         | 194   |
| pci:1b73-1000 | Fresco L... | FL1000G USB 3.0 Host Cont... | 190   |
| pci:1022-43ba | AMD         | X399 Series Chipset USB 3... | 185   |
| pci:10de-1ad6 | Nvidia      | TU102 USB 3.1 Host Contro... | 185   |
| pci:103c-3300 | Hewlett-... | Integrated Lights-Out Sta... | 184   |
| pci:1b73-1009 | Fresco L... | FL1009 USB 3.0 Host Contr... | 184   |
| pci:10de-055e | Nvidia      | MCP67 OHCI USB 1.1 Contro... | 170   |
| pci:10de-055f | Nvidia      | MCP67 EHCI USB 2.0 Contro... | 170   |
| pci:8086-a1af | Intel       | C620 Series Chipset Famil... | 165   |
| pci:8086-15f0 | Intel       | JHL7540 Thunderbolt 3 USB... | 162   |
| pci:8086-15b6 | Intel       | DSL6540 USB 3.1 Controlle... | 154   |
| pci:10de-056a | Nvidia      | MCP73 [nForce 630i] USB 2... | 148   |
| pci:10de-07fe | Nvidia      | MCP73 OHCI USB 1.1 Contro... | 148   |
| pci:1022-148c | AMD         | Starship USB 3.0 Host Con... | 145   |
| pci:8086-9a1f | Intel       | Tiger Lake-H Thunderbolt ... | 138   |
| pci:8086-15b5 | Intel       | DSL6340 USB 3.1 Controlle... | 137   |
| pci:8086-3b39 | Intel       | 5 Series/3400 Series Chip... | 128   |
| pci:8086-24c2 | Intel       | 82801DB/DBL/DBM (ICH4/ICH... | 121   |
| pci:8086-24c4 | Intel       | 82801DB/DBL/DBM (ICH4/ICH... | 121   |
| pci:8086-24cd | Intel       | 82801DB/DBM (ICH4/ICH4-M)... | 120   |
| pci:10de-0454 | Nvidia      | MCP65 USB 1.1 OHCI Contro... | 118   |
| pci:10de-0455 | Nvidia      | MCP65 USB 2.0 EHCI Contro... | 118   |
| pci:10de-0d9c | Nvidia      | MCP89 OHCI USB 1.1 Contro... | 116   |
| pci:10de-0d9d | Nvidia      | MCP89 EHCI USB 2.0 Contro... | 116   |
| pci:8086-22b7 | Intel       | USB Synopsys Controller      | 108   |
| pci:8086-24c7 | Intel       | 82801DB/DBL/DBM (ICH4/ICH... | 106   |
| pci:1b21-3242 | ASMedia ... | ASM3242 USB 3.2 Host Cont... | 98    |
| pci:8086-9a21 | Intel       | Tiger Lake-H Thunderbolt ... | 75    |
| pci:8086-4ded | Intel       | Jasper Lake USB 3.1 XHCI ... | 71    |
| pci:10b9-5237 | ULi Elec... | USB 1.1 Controller           | 68    |
| pci:10b9-5239 | ULi Elec... | USB 2.0 Controller           | 68    |
| pci:8086-8114 | Intel       | US15W/US15X/US15L/UL11L S... | 68    |
| pci:8086-8115 | Intel       | US15W/US15X/US15L/UL11L S... | 68    |
| pci:8086-8116 | Intel       | US15W/US15X/US15L/UL11L S... | 68    |
| pci:8086-8117 | Intel       | US15W/US15X/US15L/UL11L S... | 68    |
| pci:8086-7ae0 | Intel       | Alder Lake-S PCH USB 3.2 ... | 66    |
| pci:1022-43ec | AMD         | USB Controller               | 54    |
| pci:1022-43d1 | AMD         | FCH USB 3.1 XHCI Host Con... | 53    |
| pci:1b21-3241 | ASMedia ... | ASM3241 USB 3.0 XHCI Cont... | 50    |
| pci:8086-0f37 | Intel       | Atom Processor Z36xxx/Z37... | 49    |
| pci:1002-73a6 | AMD         | Navi 21 [Radeon RX 6000 X... | 47    |
| pci:10de-00e7 | Nvidia      | CK8S USB Controller          | 44    |
| pci:10de-00e8 | Nvidia      | nForce3 EHCI USB 2.0 Cont... | 44    |
| pci:8086-1137 | Intel       | Thunderbolt 4 NHI [Maple ... | 35    |
| pci:8086-1138 | Intel       | Thunderbolt 4 USB Control... | 35    |
| pci:8086-9d30 | Intel       | Skylake-U/Y USB Device Co... | 31    |
| pci:1b21-1040 | ASMedia ... | ASM1040 XHCI Controller      | 22    |
| pci:1022-43ef | AMD         | USB Controller               | 21    |
| pci:10de-0067 | Nvidia      | nForce2 USB Controller       | 21    |
| pci:10de-0068 | Nvidia      | nForce2 USB Controller       | 21    |
| pci:1045-c861 | OPTi        | 82C861 OHCI USB Host         | 20    |
| pci:8086-2482 | Intel       | 82801CA/CAM USB Controlle... | 16    |
| pci:8086-38ed | Intel       | USB Controller               | 16    |
| pci:8086-5aaa | Intel       | USB Controller               | 16    |
| pci:1b73-1400 | Fresco L... | FL1400 USB 3.0 Host Contr... | 14    |
| pci:8086-2442 | Intel       | 82801BA/BAM UHCI USB 1.1 ... | 14    |
| pci:8086-2444 | Intel       | 82801BA/BAM UHCI USB 1.1 ... | 14    |
| pci:8086-1f2c | Intel       | Atom processor C2000 USB ... | 13    |
| pci:103c-22f6 | Hewlett-... | iLO5 Virtual USB Controller  | 12    |
| pci:8086-2484 | Intel       | 82801CA/CAM USB Controlle... | 12    |
| pci:8086-2487 | Intel       | 82801CA/CAM USB Controlle... | 12    |
| pci:8086-7112 | Intel       | 82371AB/EB/MB PIIX4 USB      | 9     |
| pci:1002-4347 | AMD         | SB200 OHCI USB Controller #1 | 8     |
| pci:1002-4348 | AMD         | SB200 OHCI USB Controller #2 | 8     |
| pci:12d8-400e | Pericom ... | PI7C9X442SL USB OHCI Cont... | 8     |
| pci:12d8-400f | Pericom ... | PI7C9X442SL USB EHCI Cont... | 8     |
| pci:8086-19d0 | Intel       | Atom Processor C3000 Seri... | 8     |
| pci:1002-4345 | AMD         | SB200 EHCI USB Controller    | 7     |
| pci:10de-00d7 | Nvidia      | nForce3 USB 1.1              | 7     |
| pci:10de-00d8 | Nvidia      | nForce3 USB 2.0              | 7     |
| pci:1166-0223 | Broadcom    | BCM5785 [HT1000] USB         | 7     |
| pci:19e5-a238 | Huawei T... | HiSilicon USB 3.0 Host Co... | 7     |
| pci:19e5-a239 | Huawei T... | HiSilicon USB 2.0 2-port ... | 7     |
| pci:19e5-a23b | Huawei T... | HiSilicon USB 1.1 Host Co... | 7     |
| pci:9710-9990 | MosChip ... | MCS9990 PCIe to 4-Port US... | 7     |
| pci:8086-25a9 | Intel       | 6300ESB USB Universal Hos... | 5     |
| pci:8086-25aa | Intel       | 6300ESB USB Universal Hos... | 5     |
| pci:8086-25ad | Intel       | 6300ESB USB2 Enhanced Hos... | 5     |
| pci:8086-51ed | Intel       | Alder Lake PCH USB 3.2 xH... | 5     |
| pci:1002-7316 | AMD         | USB Controller               | 4     |
| pci:1022-43d2 | AMD         | FCH USB 3.1 XHCI Host Con... | 4     |
| pci:106b-003f | Apple       | KeyLargo/Intrepid USB        | 4     |
| pci:1b21-1041 | ASMedia ... | ASM1041 USB 3.0 XHCI Cont... | 4     |
| pci:8086-2833 | Intel       | 82801H (ICH8 Family) USB ... | 4     |
| pci:8086-461e | Intel       | Alder Lake-P Thunderbolt ... | 4     |
| pci:8086-a130 | Intel       | 100 Series/C230 Series Ch... | 4     |
| pci:1095-0673 | Silicon ... | USB0673                      | 3     |
| pci:1166-0220 | Broadcom    | OSB4/CSB5 OHCI USB Contro... | 3     |
| pci:1b21-3142 | ASMedia ... | USB 3.1 XHCI Controller      | 3     |
| pci:1d17-3038 | Zhaoxin     | ZX-100/ZX-200/ZX-E Standa... | 3     |
| pci:1d17-3104 | Zhaoxin     | ZX-100/ZX-200/ZX-E Standa... | 3     |
| pci:1d17-9204 | Zhaoxin     | ZX-E USB eXtensible Host ... | 3     |
| pci:8086-0806 | Intel       | Moorestown USB Ctrl          | 3     |
| pci:8086-0811 | Intel       | Moorestown OTG Ctrl          | 3     |
| pci:8086-31aa | Intel       | USB Synopsys Controller      | 3     |
| pci:8086-463e | Intel       | Alder Lake-P Thunderbolt ... | 3     |
| pci:0014-7a14 | Loongson... | EHCI USB Controller          | 2     |
| pci:0014-7a24 | Loongson... | OHCI USB Controller          | 2     |
| pci:1022-7464 | AMD         | AMD-8111 USB OHCI            | 2     |
| pci:106b-0019 | Apple       | KeyLargo USB                 | 2     |
| pci:10de-003b | Nvidia      | MCP04 USB Controller         | 2     |
| pci:10de-003c | Nvidia      | MCP04 USB Controller         | 2     |
| pci:10de-0087 | Nvidia      | MCP2A USB Controller         | 2     |
| pci:10de-0088 | Nvidia      | MCP2A USB Controller         | 2     |
| pci:8086-1bcd | Intel       | USB Controller               | 2     |
| pci:8086-98ed | Intel       | USB Controller               | 2     |
| pci:1000-0003 | Broadcom... | 53c825                       | 1     |
| pci:1022-13ed | AMD         | Ariel USB 3.1 Type C: Gen... | 1     |
| pci:1022-13ee | AMD         | Ariel USB 3.1 Type A: Gen... | 1     |
| pci:1022-2094 | AMD         | CS5536 [Geode companion] OHC | 1     |
| pci:1022-2095 | AMD         | CS5536 [Geode companion] EHC | 1     |
| pci:1022-2096 | AMD         | CS5536 [Geode companion] UDC | 1     |
| pci:1022-7449 | AMD         | AMD-768 [Opus] USB           | 1     |
| pci:1033-0031 | NEC Comp... | USB Controller               | 1     |
| pci:106b-0040 | Apple       | K2 KeyLargo USB              | 1     |
| pci:1106-1038 | VIA Tech... | USB Controller               | 1     |
| pci:1106-1104 | VIA Tech... | USB Controller               | 1     |
| pci:1106-3004 | VIA Tech... | USB Controller               | 1     |
| pci:1106-3018 | VIA Tech... | PCI Device Universal PCI ... | 1     |
| pci:1233-00e0 | Bus-Tech    | USB Controller               | 1     |
| pci:1306-3104 | Duet Tec... | USB Controller               | 1     |
| pci:196f-7022 | Unknown     | USB Controller               | 1     |
| pci:1fff-8008 | MCST        | USB 2.0 OHCI                 | 1     |
| pci:1fff-801e | MCST        | USB 2.0 EHCI                 | 1     |
| pci:8086-0b27 | Intel       | Thunderbolt 4 USB Control... | 1     |
| pci:8086-119e | Intel       | Merrifield USB Device Con... | 1     |
| pci:8086-1aa8 | Intel       | USB Controller               | 1     |
| pci:8086-1aaa | Intel       | USB Synopsys Controller      | 1     |
| pci:8086-1c28 | Intel       | 6 Series Chipset Family U... | 1     |
| pci:8086-1c29 | Intel       | 6 Series Chipset Family U... | 1     |
| pci:8086-1c2e | Intel       | 6 Series Chipset Family U... | 1     |
| pci:8086-2412 | Intel       | 82801AA USB Controller       | 1     |
| pci:8086-27cd | Intel       | USB Controller               | 1     |
| pci:8086-34ee | Intel       | USB Controller               | 1     |
| pci:8086-43ee | Intel       | 500 Series Chipset Family... | 1     |
| pci:8086-8a15 | Intel       | USB xDCI                     | 1     |
| pci:8086-9a15 | Intel       | USB Controller               | 1     |
| pci:8086-9dee | Intel       | 300 Series Chipset USB Sy... | 1     |
| pci:8086-a0ee | Intel       | Tiger Lake-LP USB Synopsy... | 1     |
| pci:8086-a36e | Intel       | 300 Series Chipset Family    | 1     |

