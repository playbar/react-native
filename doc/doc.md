1、 git clone https://github.com/facebook/react-native.git
2、 //  以运行  Android app 为例：
   ## Running this app
   
   Before running the app, make sure you ran:
   
       git clone https://github.com/facebook/react-native.git
       cd react-native
       npm install
       
3、 ### Running on Android
   
   You'll need to have all the [prerequisites](https://github.com/facebook/react-native/tree/master/ReactAndroid#prerequisites) (SDK, NDK) for Building React Native installed.
   
   Start an Android emulator ([Genymotion](https://www.genymotion.com) is recommended).
   
       cd react-native
       ./gradlew :RNTester:android:app:installDebug
       ./scripts/packager.sh
   
   _Note: Building for the first time can take a while._
   
   Open the RNTester app in your emulator.
   
   See [Running on Device](https://facebook.github.io/react-native/docs/running-on-device.html) in case you want to use a physical device.      



运行adb reverse tcp:8081 tcp:8081
不需要更多配置，你就可以使用Reload JS和其它的开发选项了。
