# vidyo.io-helloworld-android
Simple video chat application using Vidyo.io on Android

> For an instructional video detailing how to build this app, take a look at this [Blog Post](https://vidyo.io/how-to/build-mobile-video-chat-app-android-minutes). Take note that there have been some minor changes to the API since the video was recorded, most of which are related to the case of the methods, enums, etc.

## Clone Repository
git clone https://github.com/Vidyo/vidyo.io-helloworld-android.git

## Acquire .jar and .so Files
1. Download the latest Vidyo.io Android SDK package: https://static.vidyo.io/latest/package/VidyoClient-AndroidSDK.zip
2. Copy all files located at VidyoClient-AndroidSDK/lib/android to the VidyoIODemo/app/libs directory.

> Note: VidyoClient SDK version 4.1.18.8 or greater is required.
> The version of the SDK that you are acquiring is highlighted in the blue box here: https://developer.vidyo.io/documentation/latest

## Build and Run Application
1. In Android Studio, use Import project to open and import the Android project for the app: VidyoIODemo
2. Open the source file VidyoIODemo/app/src/main/java/com/example/pfuternik/vidyoiodemo/MainActivity.java and update the token value "InsertValidTokenHere" with a valid generated token. See the Token section of the Documentation at https://developer.vidyo.io for more info on generating tokens or watch an instructional video [here](https://support.vidyo.io/hc/en-us/articles/115004915647-Generate-Vidyo-io-Tokens).
3. Connect an Android device to your computer via USB.
4. In Android Studio, run the app. Android Studio builds, loads, and runs the app on an Android device.

