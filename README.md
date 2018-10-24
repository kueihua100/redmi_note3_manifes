# Getting start:
To initialize your local repository, use command:

repo init -u https://gitlab.com/kueihua/redmi_note3_manifest.git

Then sync up:

repo sync  -f --force-sync --no-clone-bundle -jx

# Building the system:
a) source ./build/envsetup.sh

b) lunch arrow_kenzo-userdebug

c) brunch arrow_kenzo-userdebug

