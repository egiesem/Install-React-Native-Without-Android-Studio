# Install-React-Native-Without-Android-Studio
Install React Native Without Android Studio


## Mac OS
### 1. Node & Watchman

```
brew install node
brew install watchman
```

### 2. Java Development Kit

```
brew cask install adoptopenjdk/openjdk/adoptopenjdk8
```

### 3. Installing the Android SDK (via Homebrew)

```
brew cask install android-sdk
```

### 4. For ADB devices
```
brew cask install android-platform-tools
```

### 5. Install React Native CLI
```
npm install -g react-native-cli
```
or with npx

```
npx react-native init AwesomeProject
```


## FIX Task 'installDebug' not found in project ':app'. Some candidates are: 'installDevDebug'.

```
Open your brand new React Native project

Go inside Android folder

Create a file:- local.properties

4)Once you create local.properties file open the file

5)Paste code inside your local.properties file

If you are using MacBook then paste this code:-

sdk.dir=/Users/USERNAME/Library/android/sdk

if you are using Windows then paste this code:-

sdk.dir=C:\\Users\\USERNAME\\AppData\\Local\\Android\\sdk

if you are using Linux then paste this code:-

sdk.dir = /home/USERNAME/Android/sdk

6)last thing just run command npx react-native run-android

```


https://guides.codepath.com/android/installing-android-sdk-tools#installing-the-android-sdk-via-homebrew

https://stackoverflow.com/questions/17901692/set-up-adb-on-mac-os-x

