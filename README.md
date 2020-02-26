TWRP Device Tree for JIAYU S3 
===========
Unoffical Build for MT6752 TWRP 
------------------

the way to do:
```
- repo init -u git://github.com/minimal-manifest-twrp/platform_manifest_twrp_omni.git -b twrp-6.0

- repo sync

- git clone https://github.com/h0sch180/android_twrp_device_jiayu_s3 device/JIAYU/S3

- . build/envsetup.sh

- lunch omni_S3-eng

- make -j# recoveryimage [# : no. of cpu core]
```

