# GeneratePIF

### Requirements :
+ **Rooted Device with v15.1 Play Integrity Fix by Chiteroman** [Download it HERE](https://github.com/chiteroman/PlayIntegrityFix/releases/download/v15.1/PlayIntegrityFix.zip)

+ **MT Manager** [Download it HERE](https://github.com/x1337cn/GeneratePIF/releases/download/v0.1/MT.Manager.apk)

+ **GeneratePIF.sh** [Download it HERE](https://github.com/x1337cn/GeneratePIF/releases/download/v0.1/GeneratePIF.sh)

+ **GeneratePIF.zip** (with working fingerprint GeneratePIF.sh, build.prop and vendor-build.prop) [Download it HERE](https://github.com/x1337cn/GeneratePIF/releases/download/v0.1/GeneratePIF.zip)

+ **GeneratePIF Fingerprint 2.zip** (with working fingerprint GeneratePIF.sh, build.prop and vendor-build.prop) [Download it HERE](https://github.com/x1337cn/GeneratePIF/releases/download/v0.1/GeneratePIF.Fingerprint.2.zip)

+ **For Magisk Users / Kitsune / Alpha you should enable zygisk on settings**

+ **For APatch users Download and Flash ZygiskNEXT Module** [Download it HERE](https://github.com/Yervant7/ZygiskNext/releases/download/v4-0.9.4-285/Zygisk-Next-v4-0.9.4-285-release.zip)

+ **For KernelSU users Download and Flash ZygiskNEXT Module** [Download it HERE](https://github.com/Dr-TSNG/ZygiskNext/releases/download/v4-0.9.1.1/Zygisk-Next-v4-0.9.1.1-189-release.zip)

### What is the purpose of this script? :
+ **This script automatically generate pif.json from target or build.prop and vendor-build.prop from  https://dumps.tadiphone.dev/dumps** 

### How to use this script? :
+ **Download build.prop and vendor-build.prop from Android Dumps Website on https://dumps.tadiphone.dev/dumps**
  
+ **build.prop is located on /system/build.prop**
  
+ **Sample working build.prop**
+ Doogee X90
https://dumps.tadiphone.dev/dumps/doogee/x90/-/raw/full_k80hd_bsp_fwv_512m-user-8.1.0-O11019-1558923087-release-keys/system/build.prop?ref_type=heads&inline=false

+ **Another sample working build.prop**
+ ZTE Z6530V
https://dumps.tadiphone.dev/dumps/zte/z6530/-/raw/full_k71v1_64_bsp-user-9-PPR1.180610.011-126-release-keys/system/system/build.prop?ref_type=heads&inline=false

+ **vendor-build.prop is located on /vendor/build.prop (rename to vendor-build.prop)**

+ **Sample working vendor-build.prop**
+ Doogee X90
https://dumps.tadiphone.dev/dumps/doogee/x90/-/raw/full_k80hd_bsp_fwv_512m-user-8.1.0-O11019-1558923087-release-keys/vendor/build.prop?ref_type=heads&inline=false

+ **Another sample working vendor-build.prop**
+ ZTE Z6530V
https://dumps.tadiphone.dev/dumps/zte/z6530/-/raw/full_k71v1_64_bsp-user-9-PPR1.180610.011-126-release-keys/vendor/build.prop?ref_type=heads&inline=false

+ **Create a new folder on your device and put the GeneratePIF.sh, build.prop and vendor-build.prop on a single folder. Once it's done tap execute script and will automatically replace your pif.json on /data/adb/modules/playintegrityfix/pif.json**

### Script usage and PlayIntegrityCheck
+ **GeneratePIF.zip** - Doogee X90 Custom PIF
```bash
{
  "MANUFACTURER": "DOOGEE",
  "MODEL": "X90",
  "FINGERPRINT": "DOOGEE/X90/X90:8.1.0/O11019/1558407864:user/release-keys",
  "BRAND": "DOOGEE",
  "PRODUCT": "X90",
  "DEVICE": "X90",
  "SECURITY_PATCH": "2019-05-05",
  "FIRST_API_LEVEL": "27"
}
```
![](https://github.com/x1337cn/GeneratePIF/blob/main/screen-20240119-093127-ezgif.com-video-to-gif-converter%20(1).gif)

+ **GeneratePIF Fingerprint 2.zip** - ZTE Z6530V Custom PIF
```bash
{
  "MANUFACTURER": "ZTE",
  "MODEL": "Z6530V",
  "FINGERPRINT": "ZTE/VSBL_Z6530V/Z6530:9/PPR1.180610.011/20190924.105452:user/release-keys",
  "BRAND": "ZTE",
  "PRODUCT": "VSBL_Z6530V",
  "DEVICE": "Z6530",
  "SECURITY_PATCH": "2019-09-05",
  "FIRST_API_LEVEL": "28"
}
```
![](https://github.com/x1337cn/GeneratePIF/blob/main/screen-20240119-155758-ezgif.com-video-to-gif-converter.gif)

### Tips and Tricks :
+ **Find Old Device and the security patch should be lower than 2019 and the Android Version is Below than 8.0**

+ **Also use Chinese ROM Like ZTE, VIVO and OPPO. Do not use Samsung, Xiaomi and any other famous ROM Manufacturers. Most of the fingerprints from this Manufacturers are already banned.**

+ **Credits and special thanks to chiteroman and osm0sis**
  
+ **Contact me on Telegram @x1337cn01** 
+ **Join on our Telegram Group For More Updates** https://t.me/AutoPIFNEXT
+ **Support and Donate me on this project** 
https://www.buymeacoffee.com/x1337cn
