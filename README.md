# Resurrection Remix 17.0 Local Manifest for Xiaomi Mi 11X Pro / Redmi K40 Pro (haydn)

Place `haydn.xml` in your `.repo/local_manifests/` directory before syncing.

```bash
mkdir -p .repo/local_manifests
curl -o .repo/local_manifests/haydn.xml https://raw.githubusercontent.com/kichukic/rr_haydn_local_manifest/main/haydn.xml
repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags
```
