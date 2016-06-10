# Biohazard Theme

Biohazard Layers & CMTE theme

## How to Build

* Gradle via Android Studio
    Open Gradle tab on the right side the select 
```
Biohazard > :Theme > build > assembleDebug
```
* Gradle via Terminal (Linux)
    From Biohazard directory, open terminal then type
```
./gradlew assembleDebug
```
* Gradle via CommandPrompt (Windows)
    From Biohazard folder, open up cmd then type
```
gradlew.bat assembleDebug
```
*It will download the required Gradle plugin first, so make sure you have internet connection.

## Tip
To switch between overlays package, use the Build Variants tab and select which overlay package you would like to work on. This also preview the files e.g vector .xml

## APK output

Individual Overlays apk's will be available at Overlays/build/outputs/apk
Theme apk's will be available at Theme/build/outputs/apk
