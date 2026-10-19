# Onlyward

**Only you get in.**

Onlyward is an independent macOS project focused on keeping selected apps private, with optional face-based Mac unlocking.

[Explore the interactive preview](https://onlyward.app/) · [Project progress](https://onlyward.app/progress)

## Current status

Onlyward is in early development. The website is an interactive concept, and the native Mac app is not available to download. No release date has been announced.

The preview simulates app selection, protection controls, unlocking, relocking, and recognition outcomes. It does not access your camera, recognize faces, save passwords, or protect installed apps.

This public repository contains the project overview. The native app source and a runnable application are not included here.

## What we’re building

- **App Lock:** choose which apps should require authentication before revealing their content.
- **Familiar authentication:** planned support for macOS Touch ID or account-password verification.
- **Relock rules:** control when protected apps should request authentication again.
- **Optional Mac Unlock:** a separate setup for face-based Mac unlocking, which can remain disabled.
- **Local verification:** face processing designed to run on your Mac, with camera activity limited to verification attempts.

App Lock is the first planned native feature. Reliability, compatibility, spoof resistance, and battery use still need testing in the native implementation.

## Privacy and security

App Lock is being designed as a visual privacy layer; it does not encrypt another app’s files. Its planned macOS authentication flow does not require saving your login password.

Automatic Mac unlocking would require a separate, explicitly enabled setup that stores and enters your Mac login password. Face verification on a standard Mac camera should not be treated as equivalent to Apple Face ID: Macs lack its dedicated depth-sensing hardware, and the proposed liveness checks still need validation.

Read the website’s [Privacy notice](https://onlyward.app/privacy) and [Terms](https://onlyward.app/terms) for the current preview’s scope.

## Feedback

Tell us which apps you would protect, when you share your Mac, and what you would want from an early native prototype.

- [Open an issue](https://github.com/abhigyan6/Onlyward/issues)
- Email [work@abhigyandwivedi.me](mailto:work@abhigyandwivedi.me)

Please do not include passwords, face images, or other sensitive information in public issues.

## Credits

The website’s result animations are adapted from [Glance](https://github.com/jonnyoo/glance) under its MIT license. The macOS app artwork shown in the preview belongs to Apple Inc. See the website’s [Credits](https://onlyward.app/credits) for details and the animation license.

Onlyward is an independent project and is not affiliated with or endorsed by Apple.

---

Created by Abhigyan Dwivedi. © 2026 Abhigyan Dwivedi. All rights reserved, except third-party materials governed by their respective licenses.
