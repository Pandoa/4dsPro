# Updates

This section contains the patch notes of the latest updates.

### 1.0.25 - 1.0.26
- Fixed a crash when loading an AppOpen ad on Android.
- Fixed API 31+ dependency.

### 1.0.24
- Added the following nodes to replace their usual equivalent:
    - `Read In-App Purchases (Android Updated API)`
    - `Man an In-App Purchase (Android Updated API)`

### 1.0.23
- Added the following methods to comply with Google Play’s Families Policies.
    - `SetTagForChildDirectedTreatment(EAdMobTagForChildDirectedTreatment Tag)`
    - `SetTagForUnderAgeOfConsent(EAdMobTagForUnderAgeOfConsent Tag)`
    - `SetMaxAdContentRating(EAdMobMaxAdContentRating Rating)`

### 1.0.21 - 1.0.22
- Minor bug fixes.

### 1.0.20
- Fix crash on updated Android methods when using Unreal Engine 5.

### 1.0.19 
- Improved the Fake API used to test the code in Editor.

### 1.0.18
- Updated the Android UMP library to version `2.0.0`.
- Fixed a crash when calling the `SetPersonalizedAdsEnabled()` method on Android.

### 1.0.17
- Added `UAdMobLibrary::ShowAdInspector` C++ method and `Show Ad Inspector` Blueprint node.
- Fixed IronSource SDK initialization error.

### 1.0.16
- Added `UIRonSourceLibrary::ValidateIntegration` C++ method and `Validate Integration` Blueprint node.
- Changed the implementation of `Read Leaderboard Integer (Android Updated API)` to use the API limit of 500 reads instead of 3 per instance.

### 1.0.15
- Added `UIronSourceLibrary::Initialize` C++ method and `Initialize` Blueprint node to initialize the IronSource SDK manually.


