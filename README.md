Example project which exibits the react-native-camera cocoapods bug https://github.com/react-native-community/react-native-camera/pull/2045

To see the error, run `bundle exec pod install` inside `ios`.

Results:
```sh
❯❯❯ bundle exec pod install
Analyzing dependencies
Fetching podspec for `DoubleConversion` from `../node_modules/react-native/third-party-podspecs/DoubleConversion.podspec`
Fetching podspec for `Folly` from `../node_modules/react-native/third-party-podspecs/Folly.podspec`
Fetching podspec for `React` from `../node_modules/react-native`
Fetching podspec for `glog` from `../node_modules/react-native/third-party-podspecs/glog.podspec`
Fetching podspec for `react-native-camera` from `../node_modules/react-native-camera`
Fetching podspec for `yoga` from `../node_modules/react-native/ReactCommon/yoga`
Downloading dependencies
Installing DoubleConversion (1.1.6)
Installing Folly (2016.10.31.00)
Installing React (0.57.8)
Installing boost-for-react-native (1.63.0)
Installing glog (0.3.5)
Installing react-native-camera (1.8.0)

[!] Error installing react-native-camera
[!] /usr/local/bin/git clone https://github.com/react-native-community/react-native-camera /var/folders/rh/zjc3x5b91k3gsw1bsl91nw200000gn/T/d20190111-7250-vqejge --template= --single-branch --depth 1 --branch 1.8.0

Cloning into '/var/folders/rh/zjc3x5b91k3gsw1bsl91nw200000gn/T/d20190111-7250-vqejge'...
warning: Could not find remote branch 1.8.0 to clone.
fatal: Remote branch 1.8.0 not found in upstream origin
```
