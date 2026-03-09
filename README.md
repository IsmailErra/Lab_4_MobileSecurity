# Lab_4_MobileSecurity

# Android APK Static Analysis Lab

## Informations générales

* **APK analysé:** UnCrackable-Level1.apk
* **Outils utilisés:** JADX GUI, dex2jar
* **Date:** 2026

## Objectif

The goal of this lab was to perform a static analysis of an Android APK in order to understand its structure and identify potential security issues.

## Analyse du Manifest

The AndroidManifest.xml file was analyzed to identify application configuration and components.

* Package name: `owasp.mstg.uncrackable1`
* Main activity: `sg.vantagepoint.uncrackable1.MainActivity`
* Minimum SDK: 19
* Target SDK: 28

## Analyse du code

The APK was decompiled using JADX GUI.
The source code of the application was explored, particularly the `MainActivity` class.

The code includes checks for:

* Root detection
* Debuggable mode
* Secret validation

## Recherche de chaînes sensibles

A search was performed for sensitive strings such as:

* debug
* secret
* password
* api

One interesting string found:

```
"This is the correct secret."
```

## Conclusion

The static analysis allowed inspection of the APK structure, AndroidManifest
