# Privacy and Store Launch Checklist

Do not submit the game until every item below matches the production build.

## Current assumptions used in the website text
- No standalone Staggie Games account system.
- No AppLovin SDK.
- Firebase Analytics is included.
- Firebase Crashlytics is included.
- Adjust is included.
- Unity Ads / Unity LevelPlay is included.
- Google Play Games Services and Apple Game Center may be enabled by platform.
- The game is not designed or directed primarily to children under 13.

## Developer checks
- [ ] Confirm the final list of SDKs and every LevelPlay mediation adapter in the production build.
- [ ] If AppLovin or another ad network is added, update `privacy.html` before release.
- [ ] Confirm whether personalized ads are used in each region.
- [ ] Implement the required consent flow for the EEA/UK and other applicable regions.
- [ ] Implement Apple App Tracking Transparency before tracking on iOS where required.
- [ ] Confirm Firebase Analytics retention settings.
- [ ] Confirm Adjust retention and privacy settings.
- [ ] Confirm crash, analytics, and advertising collection can be disabled or limited where required.
- [ ] Add a visible Privacy Policy link inside the game, such as Settings → Privacy Policy.
- [ ] Add a visible Privacy Choices link inside the game if privacy controls are offered.
- [ ] Complete Google Play Data Safety based on the actual production build.
- [ ] Complete Apple App Privacy based on the actual production build.
- [ ] Ensure the store forms, consent screens, SDK configuration, and `privacy.html` all say the same thing.
- [ ] In Google Play Target Audience, do not select child age groups unless the game was actually designed for them and all Families requirements are implemented.
- [ ] If a standalone Staggie account is added later, implement in-app account deletion and an external deletion webpage before release.
- [ ] Test every website link publicly over HTTPS before store submission.
