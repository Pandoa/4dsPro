# Updates

This section contains the patch notes of the latest updates.

### 1.0.27
- Upadted Google Ads SDK to version 22.2.0.
- Updated AdColony adapter to 4.8.0.2.
- Updated AppLovin adapter to 11.11.1.0.
- Updated Charboost adapter to 9.4.0.0.
- Updated i-mobile adapter to 2.3.1.1.
- Updated InMobi adapter to 10.5.7.1.
- Updated IronSource adapter to 7.4.0.0.
- Updated TapJoy adapter to 13.1.2.0.
- Updated UnityAds SDK to 4.8.0.
- Updated UnityAds adapter to 4.8.0.0.
- Updated maio adapter to 1.1.16.2.

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


