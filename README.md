Xcode libstdc++
===============

The missing libstdc++ headers and libraries for Xcode 10 or above.

please do the following command in your shell environment

```shell
sudo mkdir /Applications/Xcode.app/Contents/Developer/Platforms/MacOSX.platform/Developer/SDKs/MacOSX.sdk/usr/include/c++
sudo cp -R ./include/c++/* /Applications/Xcode.app/Contents/Developer/Platforms/MacOSX.platform/Developer/SDKs/MacOSX.sdk/usr/include/c++
sudo cp ./lib/*  /Applications/Xcode.app/Contents/Developer/Platforms/MacOSX.platform/Developer/SDKs/MacOSX.sdk/usr/lib/
```





