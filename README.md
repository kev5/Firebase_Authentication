# Firebase Authentication
User registration and login using firebase services.


* User Registration/Sign Up-

![](images/UserRegistration.PNG)


* User Login-

![](images/UserLogin.PNG)


* User Profile-

![](images/UserProfile.PNG)


* Registered Users List on Firebase-

![](images/Authentication.PNG)

## Manual Testing of the App

The tests with the description and the results are in the following excel sheet-

![Test Cases Sheet](https://github.com/kev5/Firebase_Authentication/blob/master/App%20Test%20Case%20Sheet.xlsx)

## AWS Automated Test

The Application was tested using AWS Device Farm and the results were as follows-

* AWS Unit Test Devices List-

![](https://github.com/kev5/Firebase_Authentication/blob/master/AWS%20Unit%20Test%20devices%20list.png)

* AWS Unit Test Suites and Results-

![](https://github.com/kev5/Firebase_Authentication/blob/master/AWS%20Unit%20Test%20Suites%20and%20Results.png)

Detailed Test Results for the Built-in Explorer Test Suite were as follows:

```
{"rootCause":"NO_FAILURE_DETECTED","isWifiConnected":true,"isLaunchScreenshotTaken":true,"isOpenGLApp":false,"unsuccessfulWatcherCount":0,"unvisitedComponentCount":0,"visitedComponentCount":1,"imageCount":0,"deviceFingerprint":"samsung\/matissewifiopenbnn\/matissewifiopenbnn:4.4.2\/KOT49H\/T530NUOVU1AOA2:user\/release-keys","ignoredComponentCount":0,"isLaunchSuccessful":true,"visitedScreenCount":1,"isExitDetected":false,"isCrashDetected":false,"totalTimeInMillis":31841,"isExitAfterSystemPopup":false,"visitedActivities":"[.MainActivity]","visitedActivityCount":1,"observation":"PASSED_BY_AVS","eventCount":2,"successfulWatcherCount":0,"securityThreat":"NO_ISSUE","sessionCount":1,"pid":11715,"securityStatus":{"totalOpenedSockets":0,"totalConnection":0,"totalOpenedPorts":0,"socketStats":[]},"isWebViewApp":false,"isExitAfterApplicationPopup":false,"isDropboxLogCollected":false,"isNonNativeViewApp":false,"isEntitlementPopup":false}
```

Hence, there were no failures detected and the application is free of bugs.
