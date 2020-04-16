# PixelExperience_.repo_local_manifests

# Pixel Experience

```bash
repo init -u https://github.com/PixelExperience/manifest -b ten
```
```bash
git clone https://github.com/kiam001/all10_.repo_local_manifests -b pe .repo/local_manifests
```
```bash
repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags
```

```bash
# Set up environment
$ . build/envsetup.sh

# Choose a target
$ lunch aosp_cedric-userdebug

# Build the code
$ mka bacon -j$(nproc --all)
```

# Pixel Experience Plus

```bash
repo init -u repo init -u https://github.com/PixelExperience/manifest -b ten-plus
```
```bash
git clone https://github.com/kiam001/all10_.repo_local_manifests -b pe .repo/local_manifests
```
```bash
repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags
```

```bash
# Set up environment
$ . build/envsetup.sh

# Choose a target
$ lunch aosp_cedric-userdebug

# Build the code
$ mka bacon -j$(nproc --all)
```
