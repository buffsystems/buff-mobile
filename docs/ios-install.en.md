# Buff on iPhone with Sideloadly

The Buff app is not in the App Store yet. Until it is, install it on an iPhone from the `buff-v<version>.ipa` file of the [latest release](https://github.com/buffsystems/buff-mobile/releases/latest) with [Sideloadly](https://sideloadly.io): it signs the app with your Apple ID and installs it over the cable.

## You need

- An iPhone on iOS 16 or later, and a cable to the computer.
- A computer with Windows 10/11 or macOS.
- An Apple ID. A free one works; a separate one, not your main, is better.
- The `buff-v<version>.ipa` file from the [latest release](https://github.com/buffsystems/buff-mobile/releases/latest).

## Install

1. Download Sideloadly from [sideloadly.io](https://sideloadly.io) and install it.
   - **Windows:** you need iTunes and iCloud **from Apple's website**, not from the Microsoft Store. The links are on Sideloadly's download page.
2. Connect the iPhone with the cable, unlock it, and tap "Trust This Computer".
3. Open Sideloadly. Check that **iDevice** shows your iPhone.
4. Drag the `.ipa` file onto the IPA icon in the Sideloadly window.
5. Enter your Apple ID in **Apple account** and press **Start**. Enter the Apple ID password and the two-factor code if asked. The password goes only to Apple.
6. Wait for **Done**.

## First launch on the iPhone

1. **Turn on Developer Mode:** Settings → Privacy & Security → Developer Mode → on. The iPhone restarts; confirm afterwards.
2. **Trust the developer:** Settings → General → VPN & Device Management → your Apple ID → Trust.
3. Open Buff and connect an installation: the QR code or the link with a code from the cabinet, the admin panel or Buff Code (Settings → Phone).

## Good to know

- **A free Apple ID signs for 7 days.** After that the app stops opening. To renew the signature, open Sideloadly again and press Start with the same file; the app's data stays. Sideloadly can renew it automatically: tick **Automatic refresh** in Advanced options, with the computer and the iPhone on the same Wi-Fi. With a paid Apple Developer account the signature lasts a year.
- **No notifications.** Apple push notifications reach only App Store and TestFlight apps. Everything else works; data refreshes while the app is open.
- **Free Apple ID limits:** at most 3 such apps on a device, and at most 10 new App IDs in 7 days.
- **An error about app extensions or App IDs.** If Sideloadly reports an app extension or App ID limit error, open **Advanced options** and tick **Remove app extensions**. The extension serves only notifications; the app works without it.
- **An "App ID … is not available" error.** Another Apple ID already holds the app's identifier. In **Advanced options**, turn on **Change bundle ID** and enter your own, for example `systems.buff.app.smith`.
- **A "Guru Meditation" or "lockdownd" error.** Unplug and reconnect the iPhone, unlock it, and trust the computer again. On Windows, update iTunes from Apple's website.

When Buff is out in the App Store, delete this copy and install the store app: connect your installations again, since the phone keeps only a cache.

[Русский](ios-install.md) · [About the app](../README.en.md)
