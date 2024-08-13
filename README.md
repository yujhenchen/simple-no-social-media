# simple_no_social_media

A new Flutter project.

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.


## Issues and solutions

### Error
```
FAILURE: Build failed with an exception.

* What went wrong:
A problem was found with the configuration of task ':app:processDebugResources' (type 'LinkApplicationAndroidResourcesTask').
  - In plugin 'com.android.internal.version-check' type 'com.android.build.gradle.internal.res.LinkApplicationAndroidResourcesTask' property 'androidJarInput.androidJar' specifies file 'C:\Users\user\AppData\Local\Android\sdk\platforms\android-34\android.jar' which doesn't exist.

    Reason: An input file was expected to be present but it doesn't exist.
```

#### Solution
android\app\build.gradle

Update `targetSdk` to the correct version this is installed on the computer under the path `C:\Users\user\AppData\Local\Android\sdk\platforms\`. For example, the one that exists in my local directory is `C:\Users\user\AppData\Local\Android\sdk\platforms\android-35\android.jar`, change the value `targetSdk` to be 35: `targetSdk =  35`



## Learning resources
- https://www.youtube.com/playlist?list=PLjxrf2q8roU3wk7CDw4RfV3mEwOJbjx1k
