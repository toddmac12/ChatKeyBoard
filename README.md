To run your project, navigate to the directory and run one of the following npm commands.

- cd ChatKeyBoard
- npm run android (Android Emulator must be running otherwise use npm run web)
- npm run ios # you need to use macOS to build the iOS project - use managed workflow if you need to do iOS development without a Mac
- npm run web

💡 You can also open up the projects in the ios and android directories with their respective IDEs.
🚀 expo-updates (​<https://github.com/expo/expo/blob/master/packages/expo-updates/README.md>​) has been installed in your project. Before you do a release build, you'll need to configure a few values in Expo.plist and AndroidManifest.xml in order for updates to work.

## Android (to run on emulator)

Go to your react-native Project then go to android directory Create a file with following name:
local.properties

Open the file and paste your Android SDK path like below:
For windows users:

sdk.dir=C:\\Users\\UserName\\AppData\\Local\\Android\\sdk
Replace UserName with your pc user name . Also make sure the folder is sdk or Sdk. In my case my computer user name is Zahid so the path look like:

sdk.dir=C:\\Users\\Zahid\\AppData\\Local\\Android\\sdk
For Mac users:

sdk.dir = /Users/USERNAME/Library/Android/sdk
Where USERNAME is your OSX username.

For Linux (Ubuntu) users:

sdk.dir = /home/USERNAME/Android/Sdk
Where USERNAME is your linux username(Linux paths are case-sensitive: make sure the case of S in Sdk matches)

In case if this doesn't work, add ANDROID_HOME variable in "Environment Variables" as C:\Users\USER\AppData\Local\Android\Sdk
