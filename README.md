# Expo Camera Preview Freeze on Android

This repository demonstrates a bug encountered when using the Expo Camera API on certain Android devices. The camera preview intermittently freezes or displays a black screen, particularly during continuous camera use (e.g., video recording). This issue is specific to Expo's managed workflow and is not consistently reproducible.

## Bug Reproduction

1. Clone this repository.
2. Run `npm install` or `yarn install`.
3. Start the app using `expo start`.
4. Use the app's camera functionality for an extended period. You might need to try multiple times on different devices to reproduce the issue.

## Potential Causes

The root cause of this bug is currently unknown. However, potential contributors might include:

* **Expo's Camera API implementation:** A possible issue with how Expo handles the camera on Android.
* **Device-specific hardware/software issues:** Incompatibilities with certain Android devices or their respective camera drivers.
* **Resource management:** The app might be encountering resource limitations, leading to the preview freeze.

## Note

This bug is not consistently reproducible and is specific to the Expo managed workflow. It does not occur in bare workflow projects.