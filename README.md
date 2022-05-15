# All-About-NVIDIA-Drivers-On-Linux-Kernel


> Nvidia is specifically releasing an open source kernel driver under a dual MIT/GPL license and is not currently open-sourcing parts of the driver that run in user space. This includes drivers for OpenGL, Vulkan, OpenCL, and CUDA, which are still closed source, in addition to the firmware for the GPU System Processor (GSP). Nvidia says these drivers "will remain closed source and published with pre-built binaries," so it doesn't sound like there are immediate plans to release open source versions.

Source: https://arstechnica.com/gadgets/2022/05/nvidia-takes-first-step-toward-open-source-linux-gpu-drivers/

### Official Blog Post
<https://developer.nvidia.com/blog/nvidia-releases-open-source-gpu-kernel-modules/>

### GitHub Repository
Published the source code to a variant of the NVIDIA Linux kernel modules **dual-licensed as MIT/GPLv2**.  
<https://github.com/NVIDIA/open-gpu-kernel-modules>

### Compiled Download
<https://www.nvidia.com/download/driverResults.aspx/187826/en-us>

### External News
<https://www.omgubuntu.co.uk/2022/05/nvidia-unexpectedly-announces-open-source-gpu-kernel-modules>  
<https://www.gamingonlinux.com/2022/05/nvidia-releases-open-source-linux-gpu-kernel-modules-beta-driver-5154304-out>  
<https://www.phoronix.com/scan.php?page=article&item=nvidia-open-kernel&num=1>  
<https://www.zdnet.com/article/nvidia-finally-releases-open-source-gpu-kernel-modules-for-linux/>  
<https://blogs.gnome.org/uraeus/2022/05/11/why-is-the-open-source-driver-release-from-nvidia-so-important-for-linux/>  
<https://www.tomshardware.com/news/nvidia-open-sources-linux-drivers>  
<https://www.pcgamer.com/the-unthinkable-has-happened-nvidia-has-finally-embraced-open-source-gpu-drivers/>  
<https://news.itsfoss.com/nvidia-open-source-linux/>  

### Educational Content
[NVIDIA Open Sources Their Drivers - Mental Outlaw - Youtube.com](https://www.youtube.com/watch?v=7MjtsiATEGQ)

### Supported Products
```
NVIDIA TITAN Series:
NVIDIA TITAN RTX, NVIDIA TITAN V, NVIDIA TITAN Xp, NVIDIA TITAN X (Pascal), GeForce GTX TITAN X

GeForce RTX 30 Series (Notebooks):
GeForce RTX 3080 Ti Laptop GPU, GeForce RTX 3080 Laptop GPU, GeForce RTX 3070 Ti Laptop GPU, GeForce RTX 3070 Laptop GPU, GeForce RTX 3060 Laptop GPU, GeForce RTX 3050 Ti Laptop GPU, GeForce RTX 3050 Laptop GPU

GeForce RTX 30 Series:
GeForce RTX 3090 Ti, GeForce RTX 3090, GeForce RTX 3080 Ti, GeForce RTX 3080, GeForce RTX 3070 Ti, GeForce RTX 3070, GeForce RTX 3060 Ti, GeForce RTX 3060, GeForce RTX 3050

GeForce RTX 20 Series (Notebooks):
GeForce RTX 2080 SUPER, GeForce RTX 2080, GeForce RTX 2070 SUPER, GeForce RTX 2070, GeForce RTX 2060, GeForce RTX 2050

GeForce RTX 20 Series:
GeForce RTX 2080 Ti, GeForce RTX 2080 SUPER, GeForce RTX 2080, GeForce RTX 2070 SUPER, GeForce RTX 2070, GeForce RTX 2060 SUPER, GeForce RTX 2060

GeForce MX500 Series (Notebooks):
GeForce MX570, GeForce MX550

GeForce MX400 Series (Notebooks):
GeForce MX450

GeForce MX300 Series (Notebooks):
GeForce MX350, GeForce MX330

GeForce MX200 Series (Notebooks):
GeForce MX250, GeForce MX230

GeForce MX100 Series (Notebook):
GeForce MX150, GeForce MX130, GeForce MX110

GeForce GTX 16 Series (Notebooks):
GeForce GTX 1660 Ti, GeForce GTX 1650 Ti, GeForce GTX 1650

GeForce 16 Series:
GeForce GTX 1660 SUPER, GeForce GTX 1650 SUPER, GeForce GTX 1660 Ti, GeForce GTX 1660, GeForce GTX 1650

GeForce 10 Series:
GeForce GTX 1080 Ti, GeForce GTX 1080, GeForce GTX 1070 Ti, GeForce GTX 1070, GeForce GTX 1060, GeForce GTX 1050 Ti, GeForce GTX 1050, GeForce GT 1030, GeForce GT 1010

GeForce 10 Series (Notebooks):
GeForce GTX 1080, GeForce GTX 1070, GeForce GTX 1060, GeForce GTX 1050 Ti, GeForce GTX 1050

GeForce 900 Series:
GeForce GTX 980 Ti, GeForce GTX 980, GeForce GTX 970, GeForce GTX 960, GeForce GTX 950

GeForce 900M Series (Notebooks):
GeForce GTX 980, GeForce GTX 980M, GeForce GTX 970M, GeForce GTX 965M, GeForce GTX 960M, GeForce GTX 950M, GeForce 945M, GeForce 940MX, GeForce 930MX, GeForce 920MX, GeForce 940M, GeForce 930M

GeForce 800M Series (Notebooks):
GeForce GTX 860M, GeForce GTX 850M, GeForce 845M, GeForce 840M, GeForce 830M

GeForce 700 Series:
GeForce GTX 750 Ti, GeForce GTX 750, GeForce GTX 745

NVIDIA RTX Series:
NVIDIA RTX A6000, NVIDIA RTX A5500, NVIDIA RTX A5000, NVIDIA RTX A4500, NVIDIA RTX A4000H, NVIDIA RTX A4000, NVIDIA RTX A2000 12GB, NVIDIA RTX A2000, NVIDIA T1000 8GB, NVIDIA T1000, NVIDIA T600, NVIDIA T400 4GB, NVIDIA T400

NVIDIA RTX Series (Notebooks):
NVIDIA RTX A5500 Laptop GPU, NVIDIA RTX A5000 Laptop GPU, NVIDIA RTX A4500 Laptop GPU, NVIDIA RTX A4000 Laptop GPU, NVIDIA RTX A3000 12GB Laptop GPU, NVIDIA RTX A3000 Laptop GPU, NVIDIA RTX A2000 8GB Laptop GPU, NVIDIA RTX A2000 Laptop GPU, NVIDIA RTX A1000 Laptop GPU, NVIDIA RTX A500 Laptop GPU, NVIDIA T1200 Laptop GPU , NVIDIA T600 Laptop GPU, NVIDIA T550 Laptop GPU, NVIDIA T500

Quadro RTX Series:
Quadro RTX 8000, Quadro RTX 6000, Quadro RTX 5000, Quadro RTX 4000, Quadro RTX 3000

Quadro RTX Series (Notebooks):
Quadro RTX 6000, Quadro RTX 5000, Quadro RTX 4000, Quadro RTX 3000

Quadro Series:
Quadro GV100, Quadro GP100, Quadro P6000, Quadro P5200, Quadro P5000, Quadro P4000, Quadro P2200, Quadro P2000, Quadro P1000, Quadro P620, Quadro P600, Quadro P400, Quadro M6000 24GB, Quadro M6000, Quadro M5000, Quadro M4000, Quadro M2000, Quadro K2200, Quadro K1200, Quadro K620

Quadro Series (Notebooks):
Quadro T2000, Quadro T1000, Quadro P5200, Quadro P5000, Quadro P4200, Quadro P3200, Quadro P4000, Quadro P3000, Quadro P2000, Quadro P1000, Quadro P600, Quadro P520, Quadro P500, Quadro M2200, Quadro M1200, Quadro M620, Quadro M520, Quadro M5500, Quadro M5000M, Quadro M4000M, Quadro M3000M, Quadro M2000M, Quadro M1000M, Quadro M600M, Quadro M500M, Quadro K2200M, Quadro K620M

Quadro Blade/Embedded Series :
Quadro P5000, Quadro P3000, Quadro M5000 SE, Quadro M3000 SE

Quadro NVS Series:
NVS 810

NVS Series:
NVS 810
```
