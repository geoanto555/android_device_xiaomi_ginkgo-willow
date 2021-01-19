# android_device_xiaomi_ginkgo-willow
Source to compile twrp for ginkgo-willow

![Xiaomi Redmi Note 8](https://fdn2.gsmarena.com/vv/pics/xiaomi/xiaomi-redmi-note-8-1.jpg "Xiaomi Redmi Note 8")

=====================================================
Basic   | Specs
-------:|:-------------------------
CPU     | Qualcomm SDM665 Snapdragon 665 (11 nm)
GPU     | Adreno 610
Memory  |  3GB 4GB 6GB
Storage | 32GB 64GB 128GB
Os      | Android 9, MIUI 11
Battery | Li-Po 4000 mAh, non-removable
Dimensions | 158.3 x 75.3 x 8.4 mm (6.23 x 2.96 x 0.33 in)
Display |  6.3 inches, 1080 x 2340 pixels
Rear Camera  | 48 MP, f/1.8, 26mm (wide), 1/2.0", 0.8µm, PDAF 8 MP, f/2.2, 13mm (ultrawide), 1/4.0", 1.12µm 2 MP, f/2.4, (macro) 2 MP, f/2.4, (depth)
Front Camera | 8 MP, f/2.1, (wide), 1/4.0", 1.12µm
Release Date |  2019, August 29

------------------------------------
Working :                           
                                    
ADB                                           

Decryption userdata android 10 - 11            

Screen brightness settings

Correct screenshot color

Backup

MTP.

Lock Screen


-------------------------------------
To compile:

build/envsetup.sh

export ALLOW_MISSING_DEPENDENCIES=true

lunch omni_ginkgo-eng

make recoveryimage
