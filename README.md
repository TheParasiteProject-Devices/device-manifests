# Device Manifests

Repository to storing Device Specific manifests.

## Usage

1. Download common.xml and place it under .repo/local_manifests
2. Download desired device's manifests xml and place it under .repo/local_manifests
3. Sync it by typing below command in the Terminal.

```
# Sync
$ repo sync -c --force-sync --optimized-fetch --no-tags --no-clone-bundle --prune -j$(nproc --all)
```

4. Build :)
