# Corvus_.repo_local_manifests

```bash
repo init -u https://github.com/Corvus-ROM/android_manifest.git -b 10
```
```bash
git clone https://github.com/kiam001/all10_.repo_local_manifests -b corvus .repo/local_manifests
```
```bash
repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags
```

```bash
# Set up environment
. build/envsetup.sh

# Choose a target
lunch du_cedric-userdebug

# Build the code
make corvus
```
