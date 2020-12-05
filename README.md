OrchidOS
===========

Getting started
---------------

To get started with Android/OrchidOS, you'll need to get
familiar with [Repo](https://source.android.com/source/using-repo.html) and [Version Control with Git](https://source.android.com/source/version-control.html).

To initialize your local repository using the LineageOS trees, use a command like this:
```
repo init -u https://github.com/teamorchidos/manifest.git -b ten
```
## Sync
```## Sync
repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags

[ IF YOU GOT INTO ANY PROBLMES JUST SIMPLY USE 'repo sync' ]
```
# Build Process
```## Set up environment
. build/envsetup.sh
        (or)
. b*/e*
```

## Choose a target
```## Choose a target
lunch lineage_$device-userdebug
```
## Build the code
```## Build the code
make bacon -jX
```
---
>Credits:-
* AOSP Team
* Lineage-OS Team
* All Other Friends Who Helped Me In This Process
