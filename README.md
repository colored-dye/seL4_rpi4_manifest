# seL4_rpi4_manifest

```sh
mkdir seL4_rpi4_manifest
cd seL4_rpi4_manifest
repo init -u https://github.com/colored-dye/seL4_rpi4_manifest
repo sync
git clone https://github.com/colored-dye/seL4_rpi4 -b core
ln -s seL4_rpi4/apps apps
ln -s seL4_rpi4/GEC-block GEC-block
ln -s seL4_rpi4/mavlink mavlink
ln -s seL4_rpi4/scripts scripts

```
