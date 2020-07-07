-----------------------------------------------------------------------------

Getting Started:
==============

To get started with the building process, you'll need to get familiar with [Git and Repo](http://source.android.com/source/using-repo.html).

To initialize your local repository, use a command like this:

```bash
repo init -u https://github.com/Octavi-Broken-Lab/android_manifest -b wip
```
Then to sync up:
================

```bash
repo sync -c -f --force-sync --no-tags --no-clone-bundle -j$(nproc --all) --optimized-fetch --prune
```

Finally to build:
====================

From root directory of Project, perform following commands in terminal


```bash
. build/envsetup.sh
lunch octavi_<devicecodename>-userdebug
brunch octavi_<devicecodename>-userdebug
```
-----------------------------------------------------------------------------

Credits:
=======
 * [**AOSP**](https://android.googlesource.com)
 * [**LineageOS**](https://github.com/LineageOS)
 * [**DirtyUnicorns**](https://github.com/dirtyunicorns)
 * [**AospExtended**](https://github.com/AospExtended)
 * [**PixelExperience**](https://github.com/PixelExperience)
 * [**RevengeOs**](https://github.com/RevengeOS)
 * [**POSP**](https://github.com/PotatoProject)
 * [**Havoc**](https://github.com/Havoc-OS)
 * [**Nitrogen**](https://github.com/nitrogen-project)
 * [**ProjectXtended**](https://github.com/Project-Xtended)
 * [**ColtOS**](https://github.com/https://github.com/Colt-Enigma)
 * [**LucidProject**](https://github.com/https://github.com/LucidProject)
-----------------------------------------------------------------------------

