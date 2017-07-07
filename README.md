# NoobBuilds Manifest

I'm just an old retired guy who enjoys playing with aosp as a hobby.

So use at your own risk!!

## Latest AOSP builds

```
Android 7.1.2_r19
```

## Create noobbuilds working directory and pull in build scripts.

```
git clone https://github.com/noobbuilds/build-scripts.git -b noob noobbuilds \
&& cd ~/noobbuilds && chmod a+x N6CLEAN N6DIRTY N6PCLEAN N6PDIRTY N9CLEAN N9DIRTY
```

## Get noobbuilds source

```
repo init -u https://github.com/noobbuilds/noobbuilds_manifest -b 2r4
repo sync --force-sync
```

## Build Instructions

```
cd ~/noobbuilds
./<yourchoice> see README_BUILD_SCRIPTS for options
```

Look in out/target/product/device_name/xxxx.....zip for your finished build.

Enjoy and good luck!!!

## Credits and thanks

Later
