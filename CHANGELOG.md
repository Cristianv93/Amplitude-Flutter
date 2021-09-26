## 3.4.0
* Add `useAppSetIdForDeviceId` API for Android.
* Upgrade kotlin gradle plugin to '1.5.30'.


## 3.3.0
* Add `setMinTimeBetweenSessionsMillis` API. Thanks @chillbrodev!

## 3.2.1
* Add `getUserId` API. Thanks @keke-dandois!
* Fix iOS initializeApiKey have a wrong flow When passe null as the userid. Thanks @keke-dandois!

## 3.1.1
* Fix `Identify` set and other methods cannot pass int as value on Android.

## 3.1.0
* Add `getSessionId` and `getDeviceId` API

## 3.0.0
* Migrate package to null-safety

## 2.3.1
* Add `setEventUploadThreshold` API

## 2.3.0
* Add `regenerateDeviceId` API to enable regenerate a new deviceId.

## 2.2.3
* Bump iOS (7.2.0) and Android (2.29.2) Amplitude SDK versions
* Add `setUseDynamicConfig` API to dynamically adjust server URL

## 2.2.2
* Fix - Fixing crash on iOS. Thanks @nishiths23!
* Misc - Migrated plugin to android v2 embedding. Thanks @sergey-triputsco!

## 2.2.1
* Fix addIdentity doesn't work correctly. Thanks @bradchien!

## 2.2.0
* Add `setServerUrl` API to customize server destination.

## 2.1.1
* Fix calling `setUserId` with null crashes on iOS.

## 2.1.0
* Fix the crash when calling `setUserProperties`
* Add API `uploadEvents` to force uploading unsent events. 

## 2.0.0
* A whole new Flutter SDK which is based on much more stable Amplitude native iOS, Android SDKs
