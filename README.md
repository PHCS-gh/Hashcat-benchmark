# Benchmark of different GPUs in Hashcat

- Comparison table with MD5 / `-m 0` (0-HCM) benchmarks
- Full benchmark is available by clicking the GPU name where a source file exists
- Speeds above 10 000 MH/s are displayed in GH/s with one decimal place

## NVIDIA GTX

### GTX 7xx

| GPU | VRAM | MD5 speed | Hashcat | Options | Driver | Runtime |
|---|---:|---:|---|---|---|---|
| GTX 750 Ti | 2 GB | 3 911.5 MH/s | — | — | — | — |

### GTX 9xx

| GPU | VRAM | MD5 speed | Hashcat | Options | Driver | Runtime |
|---|---:|---:|---|---|---|---|
| GTX 970 | 4 GB | 10.1 GH/s | — | — | — | — |

### GTX 10xx

| GPU | VRAM | MD5 speed | Hashcat | Options | Driver | Runtime |
|---|---:|---:|---|---|---|---|
| [GTX 1050 Ti](https://github.com/PHCS-gh/Hashcat-benchmark/blob/main/NVIDIA/Nvidia%20GTX%201050%20Ti%204%20GB%2C%206MCU) | 4 GB | 5 554.2 MH/s | 6.2.3 | `-O -w 4` | 546.33 | CUDA 12.3 |
| GTX 1060 | 3 GB | 10.7 GH/s | 6.2.6-813 | `-O -w 4` | 560.35.03 | CUDA 12.6 |
| GTX 1060 | 6 GB | 13.1 GH/s | 6.2.6-813 | `-O -w 4` | 560.35.03 | CUDA 12.6 |
| GTX 1070 | 8 GB | 19.6 GH/s | 6.2.6-813 | `-O -w 4` | 550.127.08 | CUDA 12.4 |
| GTX 1070 Ti | 8 GB | 24.3 GH/s | 6.2.6-813 | `-O -w 4` | 550.120 | CUDA 12.4 |
| [GTX 1080](https://github.com/PHCS-gh/Hashcat-benchmark/blob/main/NVIDIA/Nvidia%20GTX%201080%208%20GB%2C%2020MCU) | 8 GB | 28.1 GH/s | 6.2.3 | `-O -w 4` | 555.85 | CUDA 12.5 |
| GTX 1080 Ti | 11 GB | 34.3 GH/s | — | — | — | — |

### GTX 16xx

| GPU | VRAM | MD5 speed | Hashcat | Options | Driver | Runtime |
|---|---:|---:|---|---|---|---|
| [GTX 1650](https://github.com/PHCS-gh/Hashcat-benchmark/blob/main/NVIDIA/Nvidia%20GTX%201650%204%20GB%2C%2014MCU) | 4 GB | 11.6 GH/s | 6.2.3 | `-O -w 4` | 560.76 | CUDA 12.6 |
| GTX 1660 | 6 GB | 19.0 GH/s | 6.2.3 | `-O -w 4` | 565.77 | CUDA 12.7 |
| GTX 1660 SUPER | 6 GB | 19.6 GH/s | 6.2.3 | `-O -w 4` | 550.120 | CUDA 12.4 |
| GTX 1650 Ti - Laptop | 4 GB | 6 371.4 MH/s | — | — | — | — |

## NVIDIA RTX

### RTX 20xx

| GPU | VRAM | MD5 speed | Hashcat | Options | Driver | Runtime |
|---|---:|---:|---|---|---|---|
| [RTX 2060](https://github.com/PHCS-gh/Hashcat-benchmark/blob/main/NVIDIA/Nvidia%20RTX%202060%206%20GB%2C%2030MCU) | 6 GB | 27.5 GH/s | 6.2.3 | `-O -w 4` | 545.92 | CUDA 12.3 |
| [RTX 2060](https://github.com/PHCS-gh/Hashcat-benchmark/blob/main/NVIDIA/Nvidia%20RTX%202060%2012%20GB%2C%2034MCU) | 12 GB | 29.7 GH/s | 6.2.3 | `-O -w 4` | 545.92 | CUDA 12.3 |
| RTX 2060 SUPER | 8 GB | 29.1 GH/s | 6.2.6-813 | `-O -w 4` | 550.54.14 | CUDA 12.4 |
| RTX 2070 | 8 GB | 26.9 GH/s | — | — | — | — |
| RTX 2070 SUPER | 8 GB | 34.8 GH/s | — | — | — | — |
| RTX 2070 SUPER Max-Q - Laptop | 8 GB | 25.0 GH/s | 6.2.5 | `-O` | 470.141.03 | CUDA 11.4 |
| RTX 2080 | 8 GB | 40.7 GH/s | — | — | — | — |
| RTX 2080 SUPER | 8 GB | 41.4 GH/s | — | — | — | — |
| RTX 2080 Ti | 11 GB | 57.9 GH/s | — | — | — | — |

### RTX 30xx

| GPU | VRAM | MD5 speed | Hashcat | Options | Driver | Runtime |
|---|---:|---:|---|---|---|---|
| RTX 3050 6 GB | 6 GB | 13.9 GH/s | — | `-O` | — | OpenCL CUDA 12.4.131 |
| RTX 3050 Ti - Laptop | 4 GB | 16.8 GH/s | 6.2.6 | `-O` | — | CUDA 12.0 |
| RTX 3060 | 12 GB | 25.2 GH/s | 6.2.6-813 | `-O -w 4` | 550.127.05 | CUDA 12.4 |
| RTX 3060 - Laptop | 6 GB | 25.0 GH/s | 6.2.5 | `-O` | — | CUDA 11.6 |
| RTX 3060 Ti | 8 GB | 34.8 GH/s | 6.2.6-813 | `-O -w 4` | 550.127.05 | CUDA 12.4 |
| RTX 3070 | 8 GB | 35.5 GH/s | 6.2.6-813 | `-O -w 4` | 565.77 | CUDA 12.7 |
| [RTX 3070 - Laptop, Desktop PCB](https://github.com/PHCS-gh/Hashcat-benchmark/blob/main/NVIDIA/Nvidia%20RTX%203070%20Laptop%208%20GB%2C%2040MCU) | 8 GB | 31.9 GH/s | 6.2.3 | `-O -w 4` | 545.92 | CUDA 12.3 |
| [RTX 3070 Ti](https://github.com/PHCS-gh/Hashcat-benchmark/blob/main/NVIDIA/Nvidia%20RTX%203070%20Ti%208%20GB%2C%2048MCU) | 8 GB | 44.4 GH/s | 6.2.3 | `-O -w 4` | 545.92 | CUDA 12.3 |
| RTX RTX 3080 | 10 GB | 61.1 GH/s | 6.2.6-813 | `-O -w 4` | 560.35.03 | CUDA 12.6 |
| RTX 3080 Ti | 12 GB | 71.3 GH/s | — | — | — | — |
| RTX 3090 | 24 GB | 71.7 GH/s | 6.2.6-813 | `-O -w 4` | 565.57.01 | CUDA 12.7 |
| RTX 3090 Ti | 24 GB | 79.7 GH/s | — | `-O -w 4` | 525.60.11 | CUDA 12.0 |

### RTX 40xx

| GPU | VRAM | MD5 speed | Hashcat | Options | Driver | Runtime |
|---|---:|---:|---|---|---|---|
| RTX 4050 - Laptop | 6 GB | 8 278.2 MH/s | 6.2.6 | `-w 1` | — | CUDA 12.9 |
| RTX 4060 | 8 GB | 28.6 GH/s | — | — | — | — |
| RTX 4060 - Laptop | 8 GB | 25.3 GH/s | 6.2.5-397 | `-O -w 4` | — | CUDA 12.4 |
| RTX 4060 Ti | 8 GB | 41.5 GH/s | — | — | — | — |
| RTX 4060 Ti | 16 GB | 43.0 GH/s | 6.2.6-813 | `-O -w 4` | 560.35.03 | CUDA 12.6 |
| RTX 4070 | 12 GB | 58.8 GH/s | 6.2.6-813 | `-O -w 4` | 550.120 | CUDA 12.4 |
| RTX 4070 Ti | 12 GB | 67.8 GH/s | — | — | — | — |
| RTX 4070 SUPER | 12 GB | 69.9 GH/s | 6.2.6-813 | `-O -w 4` | 565.57.01 | CUDA 12.7 |
| RTX 4070 Ti SUPER | 16 GB | 85.0 GH/s | 6.2.6-813 | `-O -w 4` | 550.90.07 | CUDA 12.4 |
| RTX 4080 | 16 GB | 98.3 GH/s | — | — | — | — |
| RTX 4080 SUPER | 16 GB | 99.6 GH/s | 6.2.6-813 | `-O -w 4` | 550.67 | CUDA 12.4 |
| [RTX 4090](https://github.com/PHCS-gh/Hashcat-benchmark/blob/main/NVIDIA/Nvidia%20RTX%204090%2024%20GB%2C%20128MCU) | 24 GB | 148.0 GH/s | 6.2.3 | `-O -w 4` | 545.92 | CUDA 12.3 |

### RTX 50xx

| GPU | VRAM | MD5 speed | Hashcat | Options | Driver | Runtime |
|---|---:|---:|---|---|---|---|
| RTX 5060 Ti | 16 GB | 47.0 GH/s | 7.1.2 | `-O` | — | CUDA 13.0 |
| RTX 5070 | 12 GB | 61.4 GH/s | 7.0.0 | `-O` | — | CUDA 13.0 |
| RTX 5070 Ti | 16 GB | 88.2 GH/s | 6.2.6 | `-O` | — | CUDA 12.8 |
| RTX 5080 | 16 GB | 104.8 GH/s | 6.2.6 | `-O` | — | CUDA 12.8 |
| RTX 5090 | 32 GB | 215.8 GH/s | 6.2.6 | `-O` | — | CUDA 12.8 |

## NVIDIA MINING

### NVIDIA P

| GPU | VRAM | MD5 speed | Hashcat | Options | Driver | Runtime |
|---|---:|---:|---|---|---|---|
| P106-90 | 3 GB | — | — | — | — | — |
| P106-100 | 6 GB | 9 552.0 MH/s | — | — | — | — |
| P104-100 | 4 GB | 16.2 GH/s | — | — | — | — |

### NVIDIA CMP

| GPU | VRAM | MD5 speed | Hashcat | Options | Driver | Runtime |
|---|---:|---:|---|---|---|---|
| [CMP 50HX](https://github.com/PHCS-gh/Hashcat-benchmark/blob/main/NVIDIA/Nvidia%20CMP%2050HX%2010%20GB%2C%2056MCU) | 10 GB | 44.2 GH/s | 6.2.3 | `-O -w 4` | 555.85 | CUDA 12.5 |
| CMP 70HX | 8 GB | 22.1 GH/s | — | — | — | — |
| [CMP 90HX](https://github.com/PHCS-gh/Hashcat-benchmark/blob/main/NVIDIA/Nvidia%20CMP%2090HX%2010%20GB%2C%2050MCU) | 10 GB | 39.7 GH/s | 6.2.3 | `-O -w 4` | 555.85 | CUDA 12.5 |
| CMP 100-200 | 6 GB | 37.2 GH/s | 6.2.6 | `-O` | — | CUDA 12.4 |
| [CMP 170HX](https://github.com/PHCS-gh/Hashcat-benchmark/blob/main/NVIDIA/Nvidia%20CMP%20170HX%208%20GB%2C%2070MCU.txt) | 8 GB | 43.4 GH/s | 6.2.6 | `-O` | 552.12 | CUDA 12.4 |

## NVIDIA PRO

### NVIDIA Quadro / RTX A

| GPU | VRAM | MD5 speed | Hashcat | Options | Driver | Runtime |
|---|---:|---:|---|---|---|---|
| RTX A4000 | 16 GB | 33.3 GH/s | 6.2.6-813 | `-O -w 4` | 555.58.02 | CUDA 12.5 |
| RTX A5000 | 24 GB | 49.1 GH/s | — | — | — | — |

### NVIDIA PRO — Ada Generation

| GPU | VRAM | MD5 speed | Hashcat | Options | Driver | Runtime |
|---|---:|---:|---|---|---|---|
| RTX 6000 Ada Generation | 48 GB | 131.9 GH/s | 6.2.6 | `-O` | — | CUDA 12.8 |

### NVIDIA PRO — Blackwell

| GPU | VRAM | MD5 speed | Hashcat | Options | Driver | Runtime |
|---|---:|---:|---|---|---|---|
| RTX PRO 6000 Blackwell Server Edition | 96 GB | 200.9 GH/s | 7.1.2 | `-O` | — | CUDA 13.0 |
| RTX PRO 6000 Blackwell Workstation Edition | 96 GB | 251.0 GH/s | 7.1.2 | `-O` | — | OpenCL CUDA 13.3.44 |

### NVIDIA Titan

| GPU | VRAM | MD5 speed | Hashcat | Options | Driver | Runtime |
|---|---:|---:|---|---|---|---|
| TITAN X | 12 GB | 18.6 GH/s | — | — | — | — |
| TITAN V | 12 GB | 45.5 GH/s | — | — | — | — |
| TITAN RTX | 24 GB | 64.0 GH/s | — | — | — | — |

### NVIDIA Tesla

| GPU | VRAM | MD5 speed | Hashcat | Options | Driver | Runtime |
|---|---:|---:|---|---|---|---|
| Tesla K80 | 12 GB | 4 504.4 MH/s | — | — | — | — |
| Tesla M60 | 8 GB | 12.0 GH/s | — | — | — | — |
| Tesla T4 | 16 GB | 22.2 GH/s | — | — | — | — |
| Tesla P100-PCIE-16GB | 16 GB | 27.2 GH/s | — | — | — | — |
| Tesla V100-SXM2-16G | 16 GB | 55.0 GH/s | — | — | — | — |
| A10G | 24 GB | 60.5 GH/s | — | — | — | — |
| A100-SXM4-40GB | 40 GB | 69.6 GH/s | — | — | — | — |
| H100 80GB HBM3 | 80 GB | 111.3 GH/s | — | — | — | — |
| L40S | 48 GB | 148.0 GH/s | 6.2.6-851 | `-O` | — | CUDA 12.5 |

### NVIDIA Server

| GPU | VRAM | MD5 speed | Hashcat | Options | Driver | Runtime |
|---|---:|---:|---|---|---|---|
| NVIDIA B200 | 180 GB | 140.4 GH/s | 7.1.2 | `O` | 570.172.08 | 12.8 |

## AMD

### AMD RX

| GPU | VRAM | MD5 speed | Hashcat | Options | Driver | Runtime |
|---|---:|---:|---|---|---|---|
| RX 470 | 4 GB | 10.7 GH/s | — | — | — | — |
| RX 560 XT | 8 GB | 8 219.9 MH/s | — | — | — | — |
| [RX 580 2048SP](https://github.com/PHCS-gh/Hashcat-benchmark/blob/main/AMD/AMD%20RX%20580%202048SP%2C%2032MCU) | 8 GB | 10.1 GH/s | 6.2.6 | `-O -w 4` | AMD 22.5.1 | — |
| RX 590 | 8 GB | 14.0 GH/s | 6.2.5 | `-O` | — | OpenCL AMD-APP 3380.4 |

### AMD RX 6000

| GPU | VRAM | MD5 speed | Hashcat | Options | Driver | Runtime |
|---|---:|---:|---|---|---|---|
| [RX 6600](https://github.com/PHCS-gh/Hashcat-benchmark/blob/main/AMD/AMD%20RX%206600%208%20GB%2C%2014MCU) | 8 GB | 20.6 GH/s | 6.2.3 | `-O -w 4` | AMD 23.12.1 | — |

### AMD RX 5000

| GPU | VRAM | MD5 speed | Hashcat | Options | Driver | Runtime |
|---|---:|---:|---|---|---|---|
| RX 5600 XT | 6 GB | 20.6 GH/s | 6.2.6-851 | `-O` | — | — |
| RX 5700 XT | 8 GB | 23.8 GH/s | 5.1.0-1397-g7f4df9eb | `-O` | AMDGPU Pro 19.30 | OpenCL AMD-APP 2906.7 |

### AMD R9

| GPU | VRAM | MD5 speed | Hashcat | Options | Driver | Runtime |
|---|---:|---:|---|---|---|---|
| R9 290 | 3 GB | 10.1 GH/s | — | — | — | — |

## INTEL

| GPU | VRAM | MD5 speed | Hashcat | Options | Driver | Runtime |
|---|---:|---:|---|---|---|---|
| Arc B580 | 12 GB | 24.2 GH/s | 6.2.6-813 | `-O` | — | — |

## CPU

### AMD

| CPU | Memory | MD5 speed | Hashcat | Options | Driver | Runtime |
|---|---:|---:|---|---|---|---|
| EPYC 9754 128-Core | 2.3 TB | 28.0 GH/s | 6.2.6 | `-O` | — | — |
