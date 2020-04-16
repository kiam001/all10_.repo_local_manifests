# Ancient_.repo_local_manifests

```bash
repo init -u https://github.com/Ancient-Lab/manifest -b ten
``````
```bash
git clone https://github.com/kiam001/all10_.repo_local_manifests -b ancient .repo/local_manifests
```
```bash
repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags
```


```bash
. build/envsetup.sh
lunch ancient_<devicecodename>-userdebug
mka bacon -j$(nproc --all)
```
