## Current desktop specifications

Build 1, V1.0

![](/images/workstationv11.jpg)

### Current Components and Specifications (Hardware)
-------------------------------------

| Component | Supplier | Model | Link | Notes |
| --- | ---- | ---- | ---- | --- |
| Motherboard | Asus | H110M-K | [Link](https://www.asus.com/Motherboards/H110M-K/) | 1 PCIe16 only. So, if I want to run a dual GPU setup, this is a bottleneck. |
| CPU | Intel | i3 7100 3.9Ghz 3MB Cache s11151 | [Link](https://ark.intel.com/content/www/us/en/ark/products/97455/intel-core-i3-7100-processor-3m-cache-3-90-ghz.html) | This might seem like a basic CPU, but I don't game and use the PC almost exclusively for office work. I edit images almost daily and video occasionally. My laptop has an i7 and, with my average workload, I can't say that I notice any difference in performance. |
| RAM | Kingston | ValueRAM 8GB 2400Mhz x 2 (16GB total) |  | My motherboard has two RAM slots so the only way to upgrade, at this point, is to swap out an 8GB stick with something of larger capacity. I actually hit the 16GB from time to time when I have a lot of Chrome tabs open and am running a VM. So 32GB would be better for my next build. |
| PSU | Antec | Antec 400W BP400PS | [Link](https://www.alon-computers.co.il/items/520364-%D7%A1%D7%A4%D7%A7-%D7%9B%D7%97-Antec-400W-BP400PS) | This is obviously only a 400W PSU. My GPU actually only requires 300W according to its spec sheet. But a recent "frog croaking" sound coming from somewhere in the PC indicates that something is up. I presume this PSU has an international product name. |
| GPU | Geforce | Nvidia Geforce GTX 1050 Ti Windforce OC, 4G | [Link](https://www.gigabyte.com/il/Graphics-Card/GV-N105TWF2OC-4GD#kf) | I went for this particular GPU because it seemed like the best NVIDIA option that could work with my current PSU and would take me towards my eventual aim of running a six monitor display. |
| Case | Sharkoon | VS4-S Black ATX Case | [Link](https://en.sharkoon.com/product/16020) |  |
| Storage | Kingston | SSDs x 4 | [Link](https://www.kingston.com/datasheets/SUV400S3_us.pdf) | See: My [Ubuntu backup strategy](https://www.danielrosehill.co.il/myblog/my-current-ubuntu-backup-strategy/) if you're curious why I run 4 SSDs, which is the the maximum amount that my motherboard can support. 1 is my "production" Ubuntu OS, 1 is Windows, and 2 are used exclusively for storing backups (Clonezilla images and Timeshift restore points). Yes, the latter could be HDDs but ..... noises. |
| Cooler | Noctau | NH l9x65 | [Link](https://noctua.at/en/nh-l9x65) |  |

### Current Components and Specifications (Software)

**OS:** Ubuntu 20.04 LTS (Focal Fossa)

Disk partition table:

**SDA (480GB SSD)**
-> Ubuntu 

**SDB (240GB SSD)**
-> [Clonezilla](https:/www.clonezilla.org) backups

**SDC (480GB SSD)**
-> Timeshift system restore points 


**SDD (120GB SSD)**
-> Windows 10 

![](/images/diskpartitioning.png)


### Additional Connected Equipment
------------------------------

| Component | Details | Details |
| --- | --- | --- |
| PSU | Eaton 650W PSU |  |
| Monitors | [AOC E2275SWJ](https://www.amazon.co.uk/AOC-E2275SWJ-Widescreen-Multimedia-1920x1080/dp/B01CO2SH9M) x 3, each connected over HDMI |

### UPS Connection Diagram

![](/images/upsconnnections.png | width=800)
