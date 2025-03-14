# Benchmark of different GPUs in Hashcat
* Сomparison table with MD5 / 0 HCM (hashcat mode) benchmarks
* Full benchmark available by click on GPU name

## NVIDIA GTX
| Nvidia GTX 9xx | MEM Size | MCU | 0-HCM | HC-V & O | Driver & CUDA |
| --- | --- | --- | --- | --- | --- |
| [GTX 970] | 4 GB | 13 MCU | 10 113.1 MH/s |||

| Nvidia GTX 10xx | MEM Size | MCU | 0-HCM | HC-V & O | Driver & CUDA |
| --- | --- | --- | --- | --- | --- |
| [GTX 1050 Ti](https://github.com/PHCS-gh/Hashcat-benchmark/blob/main/NVIDIA/Nvidia%20GTX%201050%20Ti%204%20GB%2C%206MCU) | 4 GB | 6 MCU | 5 554.2 MH/s | 6.2.3 & -O -w 4 | 546.33 & CUDA 12.3 |
| [GTX 1060] | 3 GB | 9 MCU | 10 702.5 MH/s | 6.2.6-813 & -O -w 4 | 560.35.03 & CUDA 12.6 |
| [GTX 1060] | 6 GB | 10 MCU | 13 097.4 MH/s | 6.2.6-813 & -O -w 4 | 560.35.03 & CUDA 12.6 |
| [GTX 1070] | 8 GB | 15 MCU | 19 587.4 MH/s | 6.2.6-813 & -O -w 4 | 550.127.08 & CUDA 12.4 |
| [GTX 1070 Ti] | 8 GB | 19 MCU | 24 255.9 MH/s | 6.2.6-813 & -O -w 4 | 550.120 & CUDA 12.4 |
| [GTX 1080](https://github.com/PHCS-gh/Hashcat-benchmark/blob/main/NVIDIA/Nvidia%20GTX%201080%208%20GB%2C%2020MCU) | 8 GB | 20 MCU | 28 122.2 MH/s | 6.2.3 & -O -w 4 | 555.85 & CUDA 12.5 |
| [GTX 1080 Ti] | 11 GB | 28 MCU | 34 320.2 MH/s | | |

| Nvidia GTX 16xx | MEM Size | MCU | 0-HCM | HC-V & O | Driver & CUDA |
| --- | --- | --- | --- | --- | --- |
| [GTX 1650](https://github.com/PHCS-gh/Hashcat-benchmark/blob/main/NVIDIA/Nvidia%20GTX%201650%204%20GB%2C%2014MCU) | 4 GB | 14 MCU | 11 622.2 MH/s | 6.2.3 & -O -w 4 | 560.76 & CUDA 12.6 |
| [GTX 1660] | 6 GB | 22 MCU | 18 965.5 MH/s | 6.2.3 & -O -w 4 | 565.77 & CUDA 12.7 |
| [GTX 1660 SUPER] | 6 GB | 22 MCU | 19 584.2 MH/s | 6.2.3 & -O -w 4 | 550.120 & CUDA 12.4 |
| [GTX 1650 Ti - mobile] | 4 GB | 16 MCU | 6 371.4 MH/s | | |

## NVIDIA RTX
| Nvidia RTX 20xx | MEM Size | MCU | 0-HCM | HC-V & O | Driver & CUDA |
| --- | --- | --- | --- | --- | --- |
| [RTX 2060](https://github.com/PHCS-gh/Hashcat-benchmark/blob/main/NVIDIA/Nvidia%20RTX%202060%206%20GB%2C%2030MCU) | 6 GB | 30 MCU | 27 504.1 MH/s | 6.2.3 & -O -w 4 | 545.92 & CUDA 12.3|
| [RTX 2060](https://github.com/PHCS-gh/Hashcat-benchmark/blob/main/NVIDIA/Nvidia%20RTX%202060%2012%20GB%2C%2034MCU) | 12 GB | 34 MCU | 29 685.1 MH/s | 6.2.3 & -O -w 4 | 545.92 & CUDA 12.3|
| [RTX 2060 SUPER] | 8 GB | 34 MCU | 29 124.0 MH/s | 6.2.6-813 & -O -w 4 | 550.54.14 & CUDA 12.4 |
| [RTX 2070] | 8 GB | 36 MCU | 26 928.4 MH/s |||
| [RTX 2070 SUPER] | 8 GB | 40 MCU | 34 762.3 MH/s |||
| [RTX 2080] | 8 GB | 46 MCU | 40 682.9 MH/s |||
| [RTX 2080 SUPER] | 8 GB | 48 MCU | 41 368.1 MH/s |||
| [RTX 2080 Ti] | 11 GB | 68 MCU | 57 908.1 MH/s |||

| Nvidia RTX 30xx | MEM Size | MCU | 0-HCM | HC-V & O | Driver & CUDA |
| --- | --- | --- | --- | --- | --- |
| [RTX 3060] | 12 GB | 28 MCU | 25 183.3 MH/s | 6.2.6-813 & -O -w 4 | 550.127.05 & CUDA 12.4 |
| [RTX 3060 Ti] | 8 GB | 38 MCU | 34 806.9 MH/s | 6.2.6-813 & -O -w 4 | 550.127.05 & CUDA 12.4 |
| [RTX 3070] | 8 GB | 46 MCU | 35 457.2 MH/s | 6.2.6-813 & -O -w 4 | 565.77 & CUDA 12.7 |
| [RTX 3070 Laptop](https://github.com/PHCS-gh/Hashcat-benchmark/blob/main/NVIDIA/Nvidia%20RTX%203070%20Laptop%208%20GB%2C%2040MCU) | 8 GB | 40 MCU | 31 878.6 MH/s | 6.2.3 & -O -w 4 | 545.92 & CUDA 12.3|
| [RTX 3070 Ti](https://github.com/PHCS-gh/Hashcat-benchmark/blob/main/NVIDIA/Nvidia%20RTX%203070%20Ti%208%20GB%2C%2048MCU) | 8 GB | 48 MCU | 44 432.0 MH/s | 6.2.3 & -O -w 4 | 545.92 & CUDA 12.3|
| [RTX RTX 3080] | 10 GB | 68 MCU | 61 144.9 MH/s | 6.2.6-813 & -O -w 4 | 560.35.03 & CUDA 12.6 |
| [RTX 3080 Ti] | 12 GB | 80 MCU | 71 301.6 MH/s |||
| [RTX 3090] | 24 GB | 82 MCU | 71 714.1 MH/s | 6.2.6-813 & -O -w 4 | 565.57.01 & CUDA 12.7 |
| [RTX 3090 Ti] | 24 GB | 84 MCU | 79 738.8 MH/s | - & -O -w 4 | 525.60.11 & CUDA 12.0 |

| Nvidia RTX 40xx | MEM Size | MCU | 0-HCM | HC-V & O | Driver & CUDA |
| --- | --- | --- | --- | --- | --- |
| [RTX 4060] | 8 GB | 24 MCU | 28 582.1 MH/s |||
| [RTX 4060 Laptop] | 8 GB | 24 MCU | 25 319.9 MH/s | 6.2.5-397 & -O -w 4 | - & CUDA 12.4 |
| [RTX 4060 Ti] | 8 GB | 34 MCU | 41 451.3 MH/s |||
| [RTX 4060 Ti] | 16 GB | 34 MCU | 42 965.2 MH/s | 6.2.6-813 & -O -w 4 | 560.35.03 & CUDA 12.6 |
| [RTX 4070] | 12 GB | 46 MCU | 58 823.7 MH/s | 6.2.6-813 & -O -w 4 | 550.120 & CUDA 12.4 |
| [RTX 4070 Ti] | 12 GB | 60 MCU | 67 809.5 MH/s |||
| [RTX 4070 SUPER] | 12 GB | 56 MCU | 69 908.6 MH/s | 6.2.6-813 & -O -w 4 | 565.57.01 & CUDA 12.7 |
| [RTX 4070 Ti SUPER] | 16 GB | 66 MCU | 84 984.2 MH/s | 6.2.6-813 & -O -w 4 | 550.90.07 & CUDA 12.4 |
| [RTX 4080] | 16 GB | 76 MCU | 98 262.8 MH/s |||
| [RTX 4080 SUPER] | 16 GB | 80 MCU | 99 625.4 MH/s | 6.2.6-813 & -O -w 4 | 550.67 & CUDA 12.4 |
| [RTX 4090](https://github.com/PHCS-gh/Hashcat-benchmark/blob/main/NVIDIA/Nvidia%20RTX%204090%2024%20GB%2C%20128MCU) | 24 GB | 128 MCU | 148.0 GH/s | 6.2.3 & -O -w 4 | 545.92 & CUDA 12.3|

| Nvidia RTX 50xx | MEM Size | MCU | 0-HCM | HC-V & O | Driver & CUDA |
| --- | --- | --- | --- | --- | --- |
| [RTX 5080] | 16 GB | 84 MCU | 104.8 GH/s | 6.2.6 & -O | - & CUDA 12.8|
| [RTX 5090] | 32 GB | 170 MCU | 215.8 GH/s | 6.2.6 & -O | - & CUDA 12.8|

## NVIDIA MINING

| Nvidia P | MEM Size | MCU | 0-HCM | HC-V & O | Driver & CUDA |
| --- | --- | --- | --- | --- | --- |
| [P106-90] | 3 GB | 5 MCU | |||
| [P106-100] | 6 GB | 10 MCU | 9 552.0 MH/s |||
| [P104-100] | 4 GB | 15 MCU | 16 240.2 MH/s |||

| Nvidia CMP | MEM Size | MCU | 0-HCM | HC-V & O | Driver & CUDA |
| --- | --- | --- | --- | --- | --- |
| [CMP 50HX](https://github.com/PHCS-gh/Hashcat-benchmark/blob/main/NVIDIA/Nvidia%20CMP%2050HX%2010%20GB%2C%2056MCU) | 10 GB | 56 MCU | 44 156.8 MH/s | 6.2.3 & -O -w 4 | 555.85 & CUDA 12.5|
| [CMP 70HX] | 8 GB | 30 MCU | 22 112.8 MH/s |||
| [CMP 90HX](https://github.com/PHCS-gh/Hashcat-benchmark/blob/main/NVIDIA/Nvidia%20CMP%2090HX%2010%20GB%2C%2050MCU) | 10 GB | 50 MCU | 39 746.3 MH/s | 6.2.3 & -O -w 4 | 555.85 & CUDA 12.5|
| [CMP 170HX](https://github.com/PHCS-gh/Hashcat-benchmark/blob/main/NVIDIA/Nvidia%20CMP%20170HX%208%20GB%2C%2070MCU.txt) | 8 GB | 70 MCU | 43 380.6 MH/s | 6.2.6 & -O| 552.12 & CUDA 12.4|

## NVIDIA PRO

| Nvidia Quadro | MEM Size | MCU | 0-HCM | HC-V & O | Driver & CUDA |
| --- | --- | --- | --- | --- | --- |
| [RTX A4000] | 16 GB | 48 MCU | 33 288.7 MH/s | 6.2.6-813 & -O -w 4 | 555.58.02 & CUDA 12.5 |
| [RTX A5000] | 24 GB | 64 MCU | 49 137.5 MH/s |||

| Nvidia Titan | MEM Size | MCU | 0-HCM | HC-V & O | Driver & CUDA |
| --- | --- | --- | --- | --- | --- |
| [TITAN X] | 12 GB | 24 MCU | 18 639.7 MH/s |||
| [TITAN V] | 12 GB | 80 MCU | 45 493.6 MH/s |||
| [TITAN RTX] | 24 GB | 72 MCU | 64 019.6 MH/s |||

| Nvidia Tesla | MEM Size | MCU | 0-HCM | HC-V & O | Driver & CUDA |
| --- | --- | --- | --- | --- | --- |
| [Tesla K80] | 12 GB | 13 MCU | 4 504.4 MH/s |||
| [Tesla M60] | 8 GB | 16 MCU | 11 959.8 MH/s |||
| [Tesla T4] | 16 GB | 40 MCU | 22 224.3 MH/s |||
| [Tesla P100-PCIE-16GB] | 16 GB | 56 MCU | 27 159.5 MH/s |||
| [Tesla V100-SXM2-16G] | 16 GB | 80 MCU | 55 020.1 MH/s |||
| [A10G] | 24 GB | 80 MCU | 60 537.7 MH/s |||
| [A100-SXM4-40GB] | 40 GB | 108 MCU | 69 600.2 MH/s |||
| [H100 80GB HBM3] | 80 GB | 132 MCU | 111.3 GH/s |||
| [L40S] | 48 GB | 142 MCU | 148.0 GH/s | 6.2.6-851 & -O | - & CUDA 12.5 |

## AMD RX
| AMD RX | MEM Size | MCU | 0-HCM | HC-V & O | Driver |
| --- | --- | --- | --- | --- | --- |
| [RX 470] | 4 GB | 32 MCU | 10 679.3 MH/s |||
| [RX 560 XT] | 8 GB | 28 MCU | 8 219.9 MH/s |||
| [RX 580 2048SP](https://github.com/PHCS-gh/Hashcat-benchmark/blob/main/AMD/AMD%20RX%20580%202048SP%2C%2032MCU) | 8 GB | 32 MCU | 10 105.8 MH/s | 6.2.6 & -O -w 4| AMD 22.5.1|
| [RX 5600 XT] | 6 GB | 18 MCU | 20 646.9 MH/s | 6.2.6-851 & -O | -|
| [RX 6600](https://github.com/PHCS-gh/Hashcat-benchmark/blob/main/AMD/AMD%20RX%206600%208%20GB%2C%2014MCU) | 8 GB | 14 MCU | 20 580.4 MH/s | 6.2.3 & -O -w 4 | AMD 23.12.1|

## INTEL
| INTEL | MEM Size | MCU | 0-HCM | HC-V & O | Driver |
| --- | --- | --- | --- | --- | --- |
| [Arc B580] | 12 GB | 160 MCU | 24 154.6 MH/s | 6.2.6-813 & -O | - |

## CPU
| AMD | MEM Size | MCU | 0-HCM | HC-V & O | Driver |
| --- | --- | --- | --- | --- | --- |
| [EPYC 9754 128-Core] | 2.3 TB | 511 MCU | 28 029.6 MH/s | 6.2.6 & -O | - |
