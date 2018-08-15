
# Device tree for OnePlus6
This device tree is used to build Android-8.1 on OnePlus6

Requirements to build: 4 cores, 8GB ram.

You will spend time: it depends on the hardware, it can vary from 2 to 15 hours, on my PC with Intel core i5 Mobile, 16GB ram takes 5 hours, on my VPS with Intel Xeon E6 and 20 GB of ram with SSD it takes 2 hours


#### **Instructions:**
##### After syncing the rom you want to build, you need to download the necessary to build on OnePlus6:

 **`git clone https://github.com/teo12valpo/android_device_oneplus_enchilada.git`
`git clone https://github.com/teo12valpo/android_device_oneplus_sdm845-common.git`
`git clone https://github.com/teo12valpo/android_kernel_oneplus_sdm845.git`
`git clone https://github.com/teo12valpo/android_vendor_oneplus_sdm845-common.git `**


##### This tree is for the rom that I build, for example ArrowOS, you can choose the tree according to the rom you want to do, scrolling through the branches, if there is not you will have to adapt it to the rom you have to do yourself, editing the files .mk

##### Perfect, after downloading the right tree or editing it, you can finally start to build. To do this, run these 2 commands
** `. build/envsetup.sh`
`brunch enchilada `**
