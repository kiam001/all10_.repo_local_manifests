# Offical_Xtended_.repo_local_manifests


```bash
repo init -u https://github.com/Project-Xtended/manifest.git -b xq
```
```bash
git clone https://github.com/kiam001/all10_.repo_local_manifests -b xtended-offical .repo/local_manifests
```
```bash
repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags
```
```bash
. build/envsetup.sh
lunch xtended_cedric-userdebug
make xtended
```
