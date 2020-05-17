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



https://guides.codepath.com/android/installing-android-sdk-tools#installing-the-android-sdk-via-homebrew

https://stackoverflow.com/questions/17901692/set-up-adb-on-mac-os-x

