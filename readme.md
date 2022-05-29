# SwiftOS Local Manifest
to build SwiftOS with the provided device tree, use a command like this:

```bash
git clone https://github.com/SwiftOS-DEVICES/local_manifest.git -b lava .repo/local_manifests
```
then run repo sync

tree Sheet
----------

Path       | -                         | -
--------   |:------------------------- |:-------
device     | mediatek                  | mt6768-common
device     | mediatek                  | sepolicy_vndr
device     | xiaomi                    | lava
kernel     | xiaomi                    | mt6768
vendor     | xiaomi                    | lava
vendor     | xiaomi                    | mt6768-ims

device/mediatek/sepolicy_vndr
