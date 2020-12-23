# android_device_xiaomi_ginkgo-willow
Source to compile twrp for ginkgo-willow

------------------------------------
Working :                           
                                    
ADB                                           

Decryption userdata                 

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
