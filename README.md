# REACT NATIVE SAMPLE DEMO PROJECT
This is a simple demo project of React Native to start a project.

## Installation
You need to install the following things before start.
```
1. Node module
2. JDK
3. react-native-cli
```
There is no need to install Android Studio, you can run your react native project from VS code as well.

## Environment Variable setting change
```
1. Set Your SDK path as ANDROID_HOME, in my case this is C:\Users\Sunil\AppData\Local\Android\Sdk
2. Set platform tool path as platform-tools, in my case C:\Users\Sunil\AppData\Local\Android\Sdk\platform-tools
3. set ANDROID_HOME and platform-tools in your path variable.
4. Create a local.properies file in your Main project and set your sdk path here
    sdk.dir=C\:\\Users\\Sunil\\AppData\\Local\\Android\\Sdk
```

## Project Start Process
Run the following command to start the Project
```
1. npm install -g react-native-cli
2. react-native init AwesomeProject
3. cd AwesomeProject
4. npm start
5. react-native run-android
```
```
Do not forget to connect your Device and to start developer mode.
```

## May need to change some more file
You may need to change your android tool build version in file build.gradle inside your Android folder.
```
dependencies {
    classpath("com.android.tools.build:gradle:3.3.2")
}
```


