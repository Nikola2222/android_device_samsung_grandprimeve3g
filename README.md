##Device configuration for DEXP Ixion MS650

=====================================

Basic   | Spec Sheet
-------:|:-------------------------
CPU     | Quad-core 1,3GHz Cortex-A7
CHIPSET | Spreadtrum SC7730SE sc8830
GPU     | Mali-400MP2
Memory  | 2 GB
Shipped Android Version | Android 7.0
Storage | 16 GB
MicroSD | Up to 64 GB
Battery | 2500 mAh Li-polymer (removable)
Dimensions | 143.8 x 71 x 9.3 mm
Display | 720 x 1280 pixels, 5.0"
Rear Camera  | 8.0 MP, LED flash
Front Camera | 8.0 MP, LED flash
Release Date | 2017

##Building instructions

### What do you need?
* 50GB left of your hard disk space
* Basic skills / knowledge of Linux

### Building steps
* 1. Sync Android source
* 2. Copy this file ([grandprimeve3g.xml](https://github.com/koquantam/android_local_manifests/blob/cm-14.1-grandprimeve3g/grandprimeve3g.xml)) to `.repo/local_manifests` (if that folder doesn't exist then "mkdir" it)
* 3. `repo sync` again
* 5. After sync, type `. build/envsetup.sh && brunch grandprimeve3g`
