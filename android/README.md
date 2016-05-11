#Android

#Learning Resources
* **Developing Android Apps** on Udacity - https://www.udacity.com/course/developing-android-apps--ud853


#Android Studio
* When building projects with NDK on OS X, it's possible that `ndk.dir` is `null`.

  * Go to `Preferences > Appearances & Behavior > System Settings > Android SDK > SDK Tools` and 
  check the box next to Android NDK.

  * Once downloaded, the NDK will be located at `/Users/{username}/Library/Android/sdk/ndk-bundle`
  * If Android Studio doesn't automatically configure ndk.dir, you can directly edit local.properties
    to add `ndk.dir=/Users/{username}/Library/Android/sdk/ndk-bundle`.
