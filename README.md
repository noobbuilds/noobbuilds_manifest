# OREO WIP!!!!  NoobBuilds Manifest

I'm just an old retired guy who enjoys playing with aosp as a hobby.

So use at your own risk!!

## Latest AOSP builds

```
Android 8.1.0_r26
```

## Get noobbuilds source

```
mkdir noobbuilds
cd ~/noobbuilds
repo init -u https://github.com/noobbuilds/noobbuilds_manifest -b o81
repo sync
```
## Build noobbuilds taimen

```
source build/envsetup.sh
make clobber
breakfast taimen
export USE_CCACHE=1      not req'd if set in bashrc
mka bacon

or

source build/envsetup.sh
make clobber
export USE_CCACHE=1      not req'd if set in bashrc
brunch taimen
```



## More Later
