## Sync the manifest:

```
git clone https://github.com/MSM89xRevival/local_manifests -b 11.0 .repo/local_manifests
```

After that do 
```repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags```
to get both the rom and device sources.
