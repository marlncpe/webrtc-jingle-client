```
# mkdir webrtcjinleproject
# cd webrtcjingleproject
# gclient config https://github.com/lukeweber/webrtc-jingle-client.git --name trunk
# gclient sync

# cd trunk
# export CHROME_SRC=`pwd`
# source build/android/envsetup.sh
# gclient runhooks
# make
```