---
layout: default
title: Postcard Archive — Privacy Policy
---

# Privacy Policy — Postcard Archive

**Effective date:** 2026-06-15

<!-- policy-translations-start -->
## Translations

Translations are provided for convenience. The English policy controls if there is any difference.

[Español](es/) | [Français](fr/) | [Deutsch](de/) | [Italiano](it/) | [日本語](ja/) | [한국어](ko/) | [Português (Brasil)](pt-BR/) | [简体中文](zh-Hans/) | [繁體中文](zh-Hant/) | [العربية](ar/) | [עברית](he/) | [Nederlands](nl/) | [Русский](ru/)
<!-- policy-translations-end -->
**Applies to:** Postcard Archive for iOS / iPadOS / macOS (Mac Catalyst) and Postcard Archive for Android.

Postcard Archive is an offline, private archival app for postcard collectors. This policy explains, plainly, what we do and do not collect.

## What we collect

**Nothing.** Postcard Archive has no user accounts, no cloud sync, no analytics, no advertising, no crash reporters that transmit data, and no tracking of any kind.

The app has no server of our own, and it sends nothing about you to us. Its core archival features work fully offline. The one optional exception is the Pro map described under *Maps and geocoding* below.

## What stays on your device

Every postcard you add to Postcard Archive — including the front and back images, captions, dates, locations, stamp and postmark notes, condition, themes, transcriptions, and any other field you fill in — is stored only in this app's local storage on your device.

- On iOS, iPadOS, and macOS (Mac Catalyst), data is stored in a local SwiftData store inside the app's sandbox.
- On Android, data is stored in a local Room (SQLite) database inside the app's private internal storage.

The app does not transmit this data anywhere.

## Maps and geocoding

Postcard Archive Pro includes an optional map ("Places") that plots your postcards across the world. While that map is open — and only then — the app uses your device's network in two narrow ways:

- **Map tiles.** The background map imagery is fetched over the network while the map is open. On iOS, iPadOS, and macOS the tiles come from Apple Maps (MapKit); on Android they come from the OpenStreetMap tile servers. These requests carry only what any map request needs — the area being viewed — plus the ordinary network metadata every internet request includes (such as your device's IP address and a standard app/user-agent string, which the provider needs in order to deliver the imagery). They include no postcard data and no account.
- **Place lookup (geocoding).** To drop a pin, the app asks your device's built-in geocoder to turn a place *name* you typed (for example, "Paris, France") into coordinates. On iOS, iPadOS, and macOS this is Apple's geocoder; on Android it is the operating system's geocoding service. Only that short place-name text is sent, only for cards you gave a location, and the resulting coordinates are cached on your device so the map then works offline.

We run none of these services and receive none of this traffic. No postcard images, notes, or personal details are transmitted. On Android the Places tab opens to an offline list by default, so the map — and any network use — happens only if you choose to open it; if you never open the map, the app makes no network requests at all. Map tiles and geocoding are handled by Apple, the OpenStreetMap Foundation, or your Android system geocoder under their own terms.

## Photos and camera permission

If you grant the app access to your photo library, the app reads images you select. The selected image is copied into your local archive. The app does not upload your photos.

If you grant camera access (where applicable), the app captures images directly into your local archive. Camera frames are not transmitted.

You can deny or revoke these permissions at any time in your operating system's Settings; the app will still run but image-capture features will be unavailable.

## Exports

You can export your archive as a CSV or JSON file from the app's Settings screen. The exported file is written to a local temporary location on your device and offered to you through the system share sheet, where you choose the destination (Files, AirDrop, Mail, another app, etc.).

Postcard Archive Pro can also create a full archive backup file for your own safekeeping. On Android, this backup is a passphrase-protected encrypted `.pcabak` file. The passphrase is chosen by you and is not sent to us. If you share or store that backup elsewhere, that destination's privacy and security practices apply.

The contents and destination of an exported file are entirely under your control. We do not see what you export or where you send it.

## Backups

On iOS and iPadOS, the app's data is included in iCloud Backup or Mac/iTunes encrypted backups according to Apple's standard rules for app sandbox data. On macOS (Mac Catalyst), the app's data lives inside its Mac App Sandbox container and is included in your Mac's Time Machine backups if you have Time Machine enabled. The data is not synchronised separately by us.

On Android, the app opts out of Google Auto Backup for Apps. The postcard database is not copied to Google's servers by the app, and Android cloud backup is disabled for Postcard Archive. To move or preserve your archive, use the in-app export and passphrase-protected encrypted backup tools that you control.

## Children's privacy

The app does not knowingly collect any personal information from anyone, including children under 13. The app contains no advertising and no behaviour tracking.

## Data sharing

We do not sell, share, rent, or otherwise disclose your data because we never have it. The app stays local.

## Changes to this policy

If we change this policy, the new version will appear in a future release of the app and at this URL. The version of this document that ships with your installed app is the version that applies to you.

## Contact

Questions about this policy can be sent to **[rizkcorsight@rizkcorsight.com](mailto:rizkcorsight@rizkcorsight.com)**.
