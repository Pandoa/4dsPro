# Fyber - Mediation

<Button href="https://www.fab.com/listings/57466477-d393-4aa5-b5bc-de80cf71f808" class="fab-button">
Download the plugin on Fab
</Button>

This section contains information on how to use Fyber as a mediation partner.

## Enabling Fyber Mediation
First, we need to enable Fyber Mediation. 
1. Open `<Project>/Config/DefaultEngine.ini`.
2. Add the following configuration:
```ini
[AdsPro.Mediation]
EnableFyberMediation=true
```
3. Save and close the file.

!> On iOS, you will have to rebuild the plugin for the change to take effect.

> Make sure to follow [this guide](https://developers.google.com/admob/android/mediation/fyber#step_1_set_up_fyber_marketplace) to create and 
configure a Fyber account.


## Additional Fyber Settings
The following methods are available to customize Fyber settings:

|C++|Blueprints|Description|
|:----|:-----|:-----|
|`UFyberLibrary::InitializeInneractiveAdManager()`| `Initialize Inneractive Ad Manager`| Initializes Fyber's Ad Manager with an App ID.|

## GDPR
You can update the consent status with the C++ method `UFyberLibrary::SetGdprConsent()` or the equivalent Blueprint node `Set GDPR Consent`.