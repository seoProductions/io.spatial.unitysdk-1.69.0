# SDK CHANGES:

- `SpatialSys.UnitySDK.Editor.UpgradeUtility.CheckForUpgrade` Due to the nature of the local spatialSDK, I removed support for automatic SDK upgrades.
- `SpatialSys.UnitySDK.Editor.SpatialFeatureFlags` Set member variable to a permanent enabled. A nessesary evil 🫢
- `SpatialSys.UnitySDK.Editor.SpatialSDKConfigWindow` Cloned and modified the Token Login function to enable CLI support

# WHY ?
- to run via comand line invoking `SpatialSys.UnitySDK.Editor.BuildUtility.BuildAndPublishPackage`
