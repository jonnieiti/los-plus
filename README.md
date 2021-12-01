# los-plus
Los Plus

To get started with Android/LineageOS, you'll need to get familiar with Source Control Tools.

To initialize your local repository using the LineageOS trees, use a command like this:

repo init -u git://github.com/los-plus/android.git -b lineage-18.1


Then to sync up:

repo sync -c --force-sync --no-tags --no-clone-bundle -j$(nproc --all) --optimized-fetch --prune


Please see the LineageOS Wiki for building instructions, by device.
Submitting patches

Patches are always welcome! Please submit your patches via LineageOS Gerrit!

Simply follow our guide on how to submit patches.

To view the status of your and others' patches, visit LineageOS Gerrit Code Review.
Buildbot

All supported devices are built weekly and periodically as changes are committed to ensure the source trees remain buildable.

You can view the current build statuses at LineageOS Buildkite.

Builds produced weekly by the buildbot can be downloaded from LineageOS downloads.
