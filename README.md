# Hashcat-benchmark

GPUs hashcat benchmark

## NVIDIA GTX
| Nvidia GTX 9xx | MCU | C-CLK | M-CLK | MEM Size |  0-HCM |
| --- | --- | --- | --- | --- | --- |
| [GTX 970] | 13 MCU |  |  | 4 GB | 10 113.1 MH/s |

| Nvidia GTX 10xx | MCU | C-CLK | M-CLK | MEM Size |  0-HCM | HC-V & O | Driver & CUDA |
| --- | --- | --- | --- | --- | --- | --- | --- |
| [GTX 1050 Ti](https://github.com/AndryhaMSK/Hashcat-benchmark/blob/main/Nvidia%20GTX%201050%20Ti%204%20GB%2C%206MCU) | 6 MCU | 1304 | 1752 | 4 GB | 5 554.2 MH/s | 6.2.3 & -O -w 4 | 546.33 & CUDA 12.3 |
| [GTX 1060] | 9 MCU |  |  | 3 GB | 10 702.5 MH/s | 6.2.6-813 & -O -w 4 | 560.35.03 & CUDA 12.6 |
| [GTX 1060] | 10 MCU |  |  | 6 GB | 13 097.4 MH/s | 6.2.6-813 & -O -w 4 | 560.35.03 & CUDA 12.6 |
| [GTX 1070] | 15 MCU |  |  | 8 GB | 19 587.4 MH/s | 6.2.6-813 & -O -w 4 | 550.127.08 & CUDA 12.4 |
| [GTX 1070 Ti] | 19 MCU |  |  | 8 GB | 24 255.9 MH/s | 6.2.6-813 & -O -w 4 | 550.120 & CUDA 12.4 |
| [GTX 1080](https://github.com/AndryhaMSK/Hashcat-benchmark/blob/main/Nvidia%20GTX%201080%208%20GB%2C%2020MCU) | 20 MCU | 1696 | 1251 | 8 GB | 28 122.2 MH/s | 6.2.3 & -O -w 4 | 555.85 & CUDA 12.5 |
| [GTX 1080 Ti] | 28 MCU |  |  | 11 GB | 34 320.2 MH/s | | |

| Nvidia GTX 16xx | MCU | C-CLK | M-CLK | MEM Size |  0-HCM |
| --- | --- | --- | --- | --- | --- |
| [GTX 1650](https://github.com/AndryhaMSK/Hashcat-benchmark/blob/main/Nvidia%20GTX%201650%204%20GB%2C%2014MCU) | 14 MCU | 1485 | 2001 | 4 GB | 11 622.2 MH/s |
| [GTX 1650 Ti - mobile] | 16 MCU | 1350 | 1500 | 4 GB | 6 371.4 MH/s |

## NVIDIA RTX
| Nvidia RTX 20xx | MCU | C-CLK | M-CLK | MEM Size |  0-HCM |
| --- | --- | --- | --- | --- | --- |
| [RTX 2060](https://github.com/AndryhaMSK/Hashcat-benchmark/blob/main/Nvidia%20RTX%202060%206%20GB%2C%2030MCU) | 30 MCU | 1365 | 1750 | 6 GB | 27 504.1 MH/s |
| [RTX 2060](https://github.com/AndryhaMSK/Hashcat-benchmark/blob/main/Nvidia%20RTX%202060%2012%20GB%2C%2034MCU) | 34 MCU | 1470 | 1750 | 12 GB | 29 685.1 MH/s |
| [RTX 2070] | 36 MCU |  |  | 8 GB | 26 928.4 MH/s |
| [RTX 2070 SUPER] | 40 MCU |  |  | 8 GB | 34 762.3 MH/s |
| [RTX 2080] | 46 MCU |  |  | 8 GB | 40 682.9 MH/s |
| [RTX 2080 Ti] | 68 MCU |  |  | 11 GB | 57 908.1 MH/s |

| Nvidia RTX 30xx | MCU | C-CLK | M-CLK | MEM Size |  0-HCM |
| --- | --- | --- | --- | --- | --- |
| [RTX 3070 Laptop](https://github.com/AndryhaMSK/Hashcat-benchmark/blob/main/Nvidia%20RTX%203070%20Laptop%208%20GB%2C%2040MCU) | 40 MCU | 1110 | 1750 | 8 GB | 31 878.6 MH/s |
| [RTX 3070 Ti](https://github.com/AndryhaMSK/Hashcat-benchmark/blob/main/Nvidia%20RTX%203070%20Ti%208%20GB%2C%2048MCU) | 48 MCU | 1575 | 1188 | 8 GB | 44 432.0 MH/s |
| [RTX RTX 3080] | 68 MCU |  |  | 10 GB | 58 120.9 MH/s |
| [RTX 3080 Ti] | 80 MCU |  |  | 12 GB | 71 301.6 MH/s |
| [RTX 3090] | 82 MCU |  |  | 24 GB | 70 862.6 MH/s |
| [RTX 3090 Ti] | 84 MCU |  |  | 24 GB | 79 460.7 MH/s |

| Nvidia RTX 40xx | MCU | C-CLK | M-CLK | MEM Size |  0-HCM |
| --- | --- | --- | --- | --- | --- |
| [RTX 4060] | 24 MCU |  |  | 8 GB | 28 582.1 MH/s |
| [RTX 4060 Ti] | 34 MCU |  |  | 8 GB | 41 451.3 MH/s |
| [RTX 4070 Ti] | 60 MCU |  |  | 12 GB | 67 809.5 MH/s |
| [RTX 4070 SUPER] | 56 MCU |  |  | 12 GB | 65 023.9 MH/s |
| [RTX 4070 Ti SUPER] | 66 MCU |  |  | 16 GB | 78 787.6 MH/s |
| [RTX 4080] | 76 MCU |  |  | 16 GB | 98 262.8 MH/s |
| [RTX 4080 SUPER] | 80 MCU |  |  | 16 GB | 97 613.2 MH/s |
| [RTX 4090](https://github.com/AndryhaMSK/Hashcat-benchmark/blob/main/Nvidia%20RTX%204090%2024%20GB%2C%20128MCU) | 128 MCU | 2235 | 1313 | 24 GB | 148.0 GH/s |

| Nvidia RTX 50xx | MCU | C-CLK | M-CLK | MEM Size |  0-HCM |
| --- | --- | --- | --- | --- | --- |
| [RTX 5080] | 84 MCU | | | 16 GB | 104.8 GH/s |
| [RTX 5090] | 170 MCU | | | 32 GB | 215.8 GH/s |

## NVIDIA MINING

| Nvidia P  | MCU | C-CLK | M-CLK | MEM Size |  0-HCM |
| --- | --- | --- | --- | --- | --- |
| [P106-90] | 5 MCU | 1531 | 2002 | 3 GB |  |
| [P106-100] | 10 MCU | 1506 | 2002 | 6 GB | 9 552.0 MH/s |
| [P104-100] | 15 MCU | 1607 | 1251 | 4 GB | 16 240.2 MH/s |

| Nvidia CMP  | MCU | C-CLK | M-CLK | MEM Size |  0-HCM | Cores / TMUS / ROPS / BUS-W |
| --- | --- | --- | --- | --- | --- | --- |
| [CMP 50HX](https://github.com/AndryhaMSK/Hashcat-benchmark/blob/main/Nvidia%20CMP%2050HX%2010%20GB%2C%2056MCU) | 56 MCU | 1350 | 1750 | 10 GB | 44 156.8 MH/s | 3584 / 192 / 80 / 320 bit |
| [CMP 70HX] | 30 MCU | 1365 | 1188 | 8 GB | 22 112.8 MH/s | 3840 / 120 / 64 / 256 bit |
| [CMP 90HX](https://github.com/AndryhaMSK/Hashcat-benchmark/blob/main/Nvidia%20CMP%2050HX%2010%20GB%2C%2056MCU) | 50 MCU | 1500 | 1188 | 10 GB | 39 746.3 MH/s | 6400 / 200 / 80 / 320 bit |
| [CMP 170HX](https://github.com/AndryhaMSK/Hashcat-benchmark/blob/main/Nvidia%20CMP%20170HX%208%20GB%2C%2070MCU.txt) | 70 MCU | 1140 | 1458 | 8 GB | 43 380.6 MH/s | 4480 / 280 / 128 / 4096 bit |

## NVIDIA PRO

| Nvidia A  | MCU | C-CLK | M-CLK | MEM Size |  0-HCM | Cores / TMUS / ROPS / BUS-W |
| --- | --- | --- | --- | --- | --- | --- |
| [A5000] | 64 MCU |  |  | 24 GB | 49 137.5 MH/s | 8192 / 256 / 96 / 384 bit |
| [A10G] | 80 MCU |  |  | 24 GB | 60 537.7 MH/s | 9216 / 288 / 96 / 384 bit |
| [A100-SXM4-40GB] | 108 MCU |  |  | 40 GB | 69 600.2 MH/s | 6912 / 432 / 160 / 5120 bit |

| Nvidia Titan  | MCU | C-CLK | M-CLK | MEM Size |  0-HCM | Cores / TMUS / ROPS / BUS-W |
| --- | --- | --- | --- | --- | --- | --- |
| [TITAN X] | 24 MCU |  |  | 12 GB | 18 639.7 MH/s | 3072 / 192 / 96 / 384 bit |
| [TITAN V] | 80 MCU | 1200 | 850 | 12 GB | 45 493.6 MH/s | 5120 / 320 / 96 / 3072 bit |
| [TITAN RTX] | 72 MCU |  |  | 24 GB | 64 019.6 MH/s | 4608 / 288 / 96 / 384 bit |

| Nvidia Tesla  | MCU | C-CLK | M-CLK | MEM Size |  0-HCM |
| --- | --- | --- | --- | --- | --- |
| [Tesla K80] | 13 MCU |  |  | 12 GB | 4 504.4 MH/s |
| [Tesla M60] | 16 MCU |  |  | 8 GB | 11 959.8 MH/s |
| [Tesla T4] | 40 MCU |  |  | 16 GB | 22 224.3 MH/s |
| [Tesla P100-PCIE-16GB] | 56 MCU |  |  | 16 GB | 27 159.5 MH/s |
| [Tesla V100-SXM2-16G] | 80 MCU |  |  | 16 GB | 55 020.1 MH/s |
| [Tesla H100 80GB HBM3] | 132 MCU |  |  | 80 GB | 111.3 GH/s |

## AMD RX
| AMD RX  | MCU | C-CLK | M-CLK | MEM Size |  0-HCM |
| --- | --- | --- | --- | --- | --- |
| [RX 470] | 32 MCU ||| 4GB | 10 679.3 MH/s |
| [RX 560 XT] | 28 MCU ||| 8GB | 8 219.9 MH/s |
| [RX 580 2048SP](https://github.com/AndryhaMSK/Hashcat-benchmark/blob/main/AMD/AMD%20RX%20580%202048SP%2C%2032MCU) | 32 MCU | 1150 | 2000 | 8GB | 10 105.8 MH/s |
| [RX 6600](https://github.com/AndryhaMSK/Hashcat-benchmark/blob/main/AMD/AMD%20RX%206600%208%20GB%2C%2014MCU) | 14 MCU | 2044 | 1750 | 8GB | 20 580.4 MH/s |
