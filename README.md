# cygnus_.repo_local_manifests

```bash
repo init -u https://github.com/cygnus-rom/manifest.git -b caf-ten
```
```bash
git clone https://github.com/kiam001/all10_.repo_local_manifests -b cygnus .repo/local_manifests
```
```bash
sudo apt install git-lfs
repo sync -j$(nproc --all) --force-sync --no-tags --no-clone-bundle --prune --optimized-fetch
repo forall -c git lfs pull
```

```bash
source build/envsetup.sh
lunch cygnus_cedric-userdebug
mka cygnus
```
