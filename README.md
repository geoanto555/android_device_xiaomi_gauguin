
![MI10T LITE](https://fdn.gsmarena.com/imgroot/news/20/11/xiaomi-mi-10t-lite-in-for-review/-1200w5/gsmarena_001.jpg "MI10T LITE")
MI10T LITE - twrp
=====================================================
Basic   | Specs
-------:|:-------------------------
CPU     | Qualcomm SM7225 Snapdragon 750G 5G (8 nm)
GPU     | Adreno 619
Memory  | 6 GB
Storage | 64GB / 128GB
Os      | Android 10, MIUI 12
Battery | Li-Po 4820 mAh, non-removable
Dimensions | 165.4 x 76.8 x 9 mm (6.51 x 3.02 x 0.35 in)
Display |  6.67 inches 1080 x 2400 pixels
Rear Camera  | 64 MP, f/1.9, 26mm (wide), 1/1.73", 0.8µm, PDAF
Front Camera | 16 MP, f/2.5, 25mm (wide), 1/3.06" 1.0µm
Release Date |  2020, September 30

Thanks to mauronofrio for the script..

To compile:

extract kernel tar.gz 

build/envsetup.sh

export ALLOW_MISSING_DEPENDENCIES=true

lunch 

make  recoveryimage
