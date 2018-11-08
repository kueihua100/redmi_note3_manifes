# Getting start:
To initialize your local repository, use command:

repo init -u https://github.com/kueihua100/redmi_note3_manifest.git -b pie

Then sync up:

repo sync  -f --force-sync --no-clone-bundle -jx

# Building the system:
a) source ./build/envsetup.sh

b) lunch arrow_kenzo-userdebug

c) brunch arrow_kenzo-userdebug

