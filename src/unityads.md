# UnityAds - Mediation

<Button href="https://www.fab.com/listings/57466477-d393-4aa5-b5bc-de80cf71f808" class="fab-button">
Download the plugin on Fab
</Button>

This section contains information on how to use UnityAds as a mediation partner.

## Enabling UnityAds Mediation
First, we need to enable UnityAds Mediation. 
1. Open `<Project>/Config/DefaultEngine.ini`.
2. Add the following configuration:
```ini
[AdsPro.Mediation]
EnableUnityAdsMediation=true
```
3. Save and close the file.

!> On iOS, you will have to rebuild the plugin for the change to take effect.

> Make sure to follow [this guide](https://developers.google.com/admob/ios/mediation/unity#step_1_set_up_unity_ads) to create and configure an UnityAds account.

## GDPR
You can update the consent status with the C++ method `UUnityAdsLibrary::SetUserConsent()` or the equivalent Blueprint node `Set User Consent`.