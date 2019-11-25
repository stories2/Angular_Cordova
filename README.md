# Angular_Cordova
Convert Angular Project to Mobile App using Cordova

[Reference](https://medium.com/@nacojohn/convert-your-angular-project-to-mobile-app-using-cordova-f0384a7711a6).

ios undefined platform

[Reference](https://github.com/phonegap/phonegap-cli/issues/753).

```
I had the same issue.
I just updated node to the latest version.

cordova platform rm ios cordova platform add ios

This solved the issue for me.
```