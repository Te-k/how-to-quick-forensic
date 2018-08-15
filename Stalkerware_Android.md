# Check for Stalkerware on Android

**/!\ Warning : this guide is a draft guide to look for Stalkerware applications on Android. It is not a 100% process, and does not cover other malware. Use it cautiously.**

Stalkerware are malicious applications installed in abusive relationships to spy on people's partner or ex partner. There is a large market of companies selling this kind of abusive products. This guide provides hints to see if your Android phone has such an app installed. It follow the following steps :
* Check for insecure settings
* Check if SuperSU is installed
* Check if the phone is rooted

## Look for insecure settings

In the process of installing Stalkerware, the user needs to change two settings :
* Allow to install applications from APK files (called "Install apps from Unknown Sources" by Google, disabled by default), only before Android 8
* Disable "Scan Devices for Security Threats" on modern devices (this features would allow Google to detect and remove the application).

The first settings is in **Settings > Security > Unknown Sources** (only before Android 8 "Oreo") :

![Unknown Sources](img/unknown_sources.png)

The second settings is either in **Settings > Security > Scan Devices for Security Threats** or in **Settings > Security > Google Play Protect**, you should check that it is enabled, it would be suspicious to have this feature disabled.

![Google Play Protect](img/androidscan.png)

## Check if SuperSU is installed

[SuperSU](http://www.supersu.com/) is an Android application installed automatically most of the time during rooting. It is not a malicious application in itself, but indicate that the phone has been rooted. It is used by Stalkerware to hide the stalkerware application, but most of the time SuperSU is not hidden.

To check if SuperSU is installed on your computer :
* Look for the SuperSU icon in the main application menu
* Look for SuperSU in Settings > Apps and Notifications

![Super SU Icon](img/supersu.png)

## Detect if the phone is rooted

The last step is to check if the phone is rooted. To do this, you can find the open source application Root Verifier available on [Google Play](https://play.google.com/store/apps/details?id=com.abcdjdj.rootverifier&hl=en) or [F-Droid](https://f-droid.org/en/packages/com.abcdjdj.rootverifier/)

![Root Verifier](img/rootverifier1.png)

Once the application is installed, you just have to click on "Check" and see the results.

![Root Verifier](img/rootverifier2.png)

If you have not done any extensive modificaton of the device since you bought it, and bought the phone new, it is highly suspicious to have your phone rooted. It may indicated that your phone
