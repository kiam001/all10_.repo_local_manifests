# aex_.repo_local_manifests

```bash
repo init --depth=1 -u git://github.com/AospExtended/manifest.git -b 10.x
```
```bash
git clone https://github.com/kiam001/all10_.repo_local_manifests -b aicp .repo/local_manifests
```
```bash
repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags
```

```bash
# Set up environment
. build/envsetup.sh

# Choose a target
lunch aosp_cedric-userdebug

# Build the code
mka bacon -j$(nproc --all)
```
