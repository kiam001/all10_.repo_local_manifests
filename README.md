# crdroid_.repo_local_manifests

```bash
repo init -u git://github.com/crdroidandroid/android.git -b 10.0
```
```bash
git clone https://github.com/kiam001/all10_.repo_local_manifests -b crdroid .repo/local_manifests
```
```bash
repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags
```

```bash
# Set up environment
. build/envsetup.sh

# Build the code
brunch cedric
```
