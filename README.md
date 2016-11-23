# Biohazard Theme
Biohazard Substratum | RRO | CMTE 
[![Build Status](https://travis-ci.org/pierx/Biohazard.svg?branch=master)](https://travis-ci.org/pierx/Biohazard)

## How to Build Debug version
- _Option 1_ - Gradle via Android Studio
    Open Gradle tab on the right side the select 
```
Biohazard > Biohazard(root) > build > assembleDebug
```
- _Option 2_ - Gradle via Terminal/CommandPrompt
Navigate to root project folder (Biohazard directory) open terminal/cmd then type.

(Linux)
```
./gradlew assembleDebug
```
(Windows)
```
gradlew.bat assembleDebug
```
*It will download the required Gradle plugin first, so make sure you have internet connection.

- The assets :
All required files will be generated automatically.
The overlays for OMS and CMTE are copied from the Overlays modules to the Theme modules, also the same with .zip files for Layers. 
See build.gradle file for more info. 

- Tips:
To switch between overlays package, use the Build Variants tab and select which overlay package you would like to work on. 
This also preview the files e.g vector.xml

## Info
For more info please use the Google+ community here https://goo.gl/BJHxg4 

## License:
<a rel="license" href="http://creativecommons.org/licenses/by-nc/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc/4.0/">Creative Commons Attribution-NonCommercial 4.0 International License</a>.


##Download
<a href='https://play.google.com/store/apps/details?id=com.pierx.biohazard&utm_source=global_co&utm_medium=prtnr&utm_content=Mar2515&utm_campaign=PartBadge&pcampaignid=MKT-Other-global-all-co-prtnr-py-PartBadge-Mar2515-1'><img alt='Get it on Google Play' src='https://play.google.com/intl/en_us/badges/images/generic/en_badge_web_generic.png'/></a>

