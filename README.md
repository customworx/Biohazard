# Biohazard Theme

Biohazard Layers & CMTE theme

## How to Build
_Option 1_
* Gradle via Android Studio
    Open Gradle tab on the right side the select 
```
Biohazard > :Theme > build > assembleDebug
```
_Option 2_
* Gradle via Terminal/CommandPrompt 
    Navigate to root project folder (Biohazard directory) open terminal/cmd then type
    (Linux)
```
./gradlew assembleDebug
```
   (Windows)
```
gradlew.bat assembleDebug
```
*It will download the required Gradle plugin first, so make sure you have internet connection.

## Tip
To switch between overlays package, use the Build Variants tab and select which overlay package you would like to work on. This also preview the files e.g vector.xml

## APK output

Individual Overlays apk's will be available at Overlays/build/outputs/apk

Theme apk's will be available at Theme/build/outputs/apk
