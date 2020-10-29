# bugs

```sh
# $ npx react-native-macos-init

➜  ReactNativeMacOSApp git:(main) ✗ npx react-native-macos-init
npx: installed 113 in 27.479s
Reading application name from package.json…
Reading react-native version from node_modules…
Reading react-native-macos version from node_modules…
Latest matching version of react-native-macos for react-native@0.62.0 is react-native-macos@0.62.16.
Installing react-native-macos@^0.62.0-0…
warning "react-native > use-subscription@1.5.0" has incorrect peer dependency "react@^17.0.0".
warning "@react-native-community/eslint-config > @typescript-eslint/eslint-plugin@1.13.0" has incorrect peer dependency "eslint@^5.0.0".
warning "@react-native-community/eslint-config > @typescript-eslint/parser@1.13.0" has incorrect peer dependency "eslint@^5.0.0".
warning "@react-native-community/eslint-config > eslint-plugin-react@7.12.4" has incorrect peer dependency "eslint@^3.0.0 || ^4.0.0 || ^5.0.0".
warning "@react-native-community/eslint-config > eslint-plugin-react-native@3.6.0" has incorrect peer dependency "eslint@^3.17.0 || ^4 || ^5".
warning "@react-native-community/eslint-config > @typescript-eslint/eslint-plugin > tsutils@3.17.1" has unmet peer dependency "typescript@>=2.8.0 || >= 3.2.0-dev || >= 3.3.0-dev || >= 3.4.0-dev || >= 3.5.0-dev || >= 3.6.0-dev || >= 3.6.0-beta || >= 3.7.0-dev || >= 3.7.0-beta".
react-native-macos@^0.62.0-0 successfully installed!
new macos/Podfile
new macos/.gitignore
new macos/ReactNativeMacOSApp-iOS/AppDelegate.h
new macos/ReactNativeMacOSApp-iOS/AppDelegate.m
new macos/ReactNativeMacOSApp-iOS/Base.lproj/LaunchScreen.xib
new macos/ReactNativeMacOSApp-iOS/Images.xcassets/AppIcon.appiconset/Contents.json
new macos/ReactNativeMacOSApp-iOS/Images.xcassets/Contents.json
new macos/ReactNativeMacOSApp-iOS/Info.plist
new macos/ReactNativeMacOSApp-iOS/main.m
new macos/ReactNativeMacOSApp-macOS/AppDelegate.h
new macos/ReactNativeMacOSApp-macOS/AppDelegate.m
new macos/ReactNativeMacOSApp-macOS/Assets.xcassets/AppIcon.appiconset/Contents.json
new macos/ReactNativeMacOSApp-macOS/Assets.xcassets/Contents.json
new macos/ReactNativeMacOSApp-macOS/Base.lproj/Main.storyboard
new macos/ReactNativeMacOSApp-macOS/ReactNativeMacOSApp.entitlements
new macos/ReactNativeMacOSApp-macOS/Info.plist
new macos/ReactNativeMacOSApp-macOS/ViewController.h
new macos/ReactNativeMacOSApp-macOS/ViewController.m
new macos/ReactNativeMacOSApp-macOS/main.m
new macos/ReactNativeMacOSApp.xcodeproj/project.pbxproj
new macos/ReactNativeMacOSApp.xcodeproj/xcshareddata/xcschemes/ReactNativeMacOSApp-iOS.xcscheme
new macos/ReactNativeMacOSApp.xcodeproj/xcshareddata/xcschemes/ReactNativeMacOSApp-macOS.xcscheme
new metro.config.macos.js
1.9.3
> pod install
Analyzing dependencies
Fetching podspec for `DoubleConversion` from `../node_modules/react-native-macos/third-party-podspecs/DoubleConversion.podspec`
Fetching podspec for `RCT-Folly` from `../node_modules/react-native-macos/third-party-podspecs/RCT-Folly.podspec`
Fetching podspec for `boost-for-react-native` from `../node_modules/react-native-macos/third-party-podspecs/boost-for-react-native.podspec`
Fetching podspec for `glog` from `../node_modules/react-native-macos/third-party-podspecs/glog.podspec`
Downloading dependencies
Installing CocoaAsyncSocket (7.6.4)
Installing CocoaLibEvent (1.0.0)
Installing DoubleConversion (1.1.6)

[!] Error installing DoubleConversion
[!] /usr/bin/git clone https://github.com/google/double-conversion.git /var/folders/qm/csrtpvpn62x82v4zykvsrnw80000gn/T/d20201029-17346-1wtga9u --template= --single-branch --depth 1 --branch v1.1.6

Cloning into '/var/folders/qm/csrtpvpn62x82v4zykvsrnw80000gn/T/d20201029-17346-1wtga9u'...
error: RPC failed; curl 56 LibreSSL SSL_read: SSL_ERROR_SYSCALL, errno 54
fatal: the remote end hung up unexpectedly
fatal: early EOF
fatal: unpack-objects failed


Aborting run
An unexpected error was encountered. Please report it as a bug:
Error
    at CocoaPodsPackageManager._installAsync (/Users/xgqfrms-mbp/.npm/_npx/17210/lib/node_modules/pod-install/build/index.js:2:85721)
    at processTicksAndRejections (internal/process/task_queues.js:97:5)

Command failed: npx --quiet pod-install --non-interactive --quiet Error: Command failed: npx --quiet pod-install --non-interactive --quiet
    at checkExecSyncError (child_process.js:630:11)
    at Object.execSync (child_process.js:666:15)
    at installPods (/Users/xgqfrms-mbp/Documents/GitHub/React-Native-for-macOS/src/ReactNativeMacOSApp/node_modules/react-native-macos/local-cli/generator-macos/index.js:153:16)
    at generateMacOS (/Users/xgqfrms-mbp/Documents/GitHub/React-Native-for-macOS/src/ReactNativeMacOSApp/node_modules/react-native-macos/local-cli/generate-macos.js:33:3)
    at Object.<anonymous> (/Users/xgqfrms-mbp/.npm/_npx/15316/lib/node_modules/react-native-macos-init/lib-commonjs/cli.js:254:9)
    at Generator.next (<anonymous>)
    at fulfilled (/Users/xgqfrms-mbp/.npm/_npx/15316/lib/node_modules/react-native-macos-init/lib-commonjs/cli.js:10:58) {
  status: 1,
  signal: null,
  output: [ null, null, null ],
  pid: 17210,
  stdout: null,
  stderr: null
}
➜  ReactNativeMacOSApp git:(main) ✗ 

```

## build bug

```sh
➜  ReactNativeMacOSApp git:(main) ✗ npx react-native run-macos
info Found Xcode project "ReactNativeMacOSApp.xcodeproj"
info Building (using "xcodebuild -project ReactNativeMacOSApp.xcodeproj -configuration Debug -scheme ReactNativeMacOSApp-macOS")
..........
error Failed to build macOS project. We ran "xcodebuild" command but it exited with error code 65. To debug build logs further, consider building your app with Xcode.app, by opening ReactNativeMacOSApp.xcodeproj. Run CLI with --verbose flag for more details.
Command line invocation:
    /Applications/Xcode.app/Contents/Developer/usr/bin/xcodebuild -project ReactNativeMacOSApp.xcodeproj -configuration Debug -scheme ReactNativeMacOSApp-macOS

note: Using new build system
note: Building targets in parallel
note: Planning build
note: Constructing build description
error: /Users/xgqfrms-mbp/Documents/GitHub/React-Native-for-macOS/src/ReactNativeMacOSApp/macos/Pods/Target Support Files/Pods-Shared-ReactNativeMacOSApp-macOS/Pods-Shared-ReactNativeMacOSApp-macOS.debug.xcconfig: unable to open file (in target "ReactNativeMacOSApp-macOS" in project "ReactNativeMacOSApp") (in target 'ReactNativeMacOSApp-macOS' from project 'ReactNativeMacOSApp')
error: /Users/xgqfrms-mbp/Documents/GitHub/React-Native-for-macOS/src/ReactNativeMacOSApp/macos/Pods/Target Support Files/Pods-Shared-ReactNativeMacOSApp-macOS/Pods-Shared-ReactNativeMacOSApp-macOS.debug.xcconfig: unable to open file (in target "ReactNativeMacOSApp-macOS" in project "ReactNativeMacOSApp") (in target 'ReactNativeMacOSApp-macOS' from project 'ReactNativeMacOSApp')
error: /Users/xgqfrms-mbp/Documents/GitHub/React-Native-for-macOS/src/ReactNativeMacOSApp/macos/Pods/Target Support Files/Pods-Shared-ReactNativeMacOSApp-macOS/Pods-Shared-ReactNativeMacOSApp-macOS.debug.xcconfig: unable to open file (in target "ReactNativeMacOSApp-macOS" in project "ReactNativeMacOSApp") (in target 'ReactNativeMacOSApp-macOS' from project 'ReactNativeMacOSApp')


** BUILD FAILED **


➜  ReactNativeMacOSApp git:(main) ✗ 
```
