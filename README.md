# Lab_4_MobileSecurity

## Tools Used
- JADX GUI
- dex2jar

## APK Information
APK Name: UnCrackable-Level1.apk

## Static Analysis

The APK was analyzed using JADX GUI to explore the source code and application structure.

### Code Analysis
The decompiled source code was inspected to understand the application's logic.

### Manifest Analysis
The AndroidManifest.xml file was examined to identify permissions and application components.

### Sensitive Data Search
Search was performed for potential sensitive strings such as:
- password
- token
- secret
- debug
- http

No critical hardcoded secrets were found during this analysis.

## Conclusion
Static analysis allowed inspection of the application structure, manifest configuration, and source code without executing the APK.
