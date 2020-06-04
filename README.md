# PixysOS_.repo_local_manifests

```bash
repo init -u https://github.com/PixysOS/manifest -b ten
```
```bash
git clone https://github.com/kiam001/all10_.repo_local_manifests -b pixysos .repo/local_manifests
```
```bash
repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags
```

```bash
# Set up environment
. build/envsetup.sh

# Choose a target
lunch pixys_cedric-userdebug

# Build the code
make pixys j$(nproc --all)
```
