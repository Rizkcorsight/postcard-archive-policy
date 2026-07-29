---
layout: default
title: Postcard Archive — Privacy Policy
---

<!-- privacy-localizations-2026-07-29-start -->
<aside style="margin:16px auto;padding:13px 15px;max-width:920px;border:1px solid #9cb2a9;border-radius:12px">
<strong>Privacy policy translations:</strong> <a href="privacy/languages.html">Read this policy in every language offered by the Apple App Store or Google Play listing.</a>
</aside>
<!-- privacy-localizations-2026-07-29-end -->


<!-- store-access-2026-07-15-start -->
> **Store access and purchases — updated July 15, 2026:** Postcard Archive is free to download and includes a local 3-day full-access trial. After the trial, continued access requires one one-time unlock at the price displayed by Apple App Store or Google Play. There is no subscription, automatic renewal, or recurring charge. [Read this disclosure in every supported language](store-access.html).
<!-- store-access-2026-07-15-end -->


# Privacy Policy — Postcard Archive

**Effective date:** 2026-07-21

<!-- policy-translations-start -->
## Translations

Translations are provided for convenience. The English policy controls if there is any difference.

[Español](es/) | [Français](fr/) | [Deutsch](de/) | [Italiano](it/) | [日本語](ja/) | [한국어](ko/) | [Português (Brasil)](pt-BR/) | [简体中文](zh-Hans/) | [繁體中文](zh-Hant/) | [العربية](ar/) | [עברית](he/) | [Nederlands](nl/) | [Русский](ru/)
<!-- policy-translations-end -->
<!-- store-audit-2026-06-29-start -->
## Store Listing Alignment

**Checked 2026-07-21.** This page was compared with the public App Store and Google Play listings. The Google Play Data Safety declaration is being corrected to disclose the limited technical metrics processed by the bundled Google ML Kit SDK on Android.

**Accurate app behavior:** Archive entries, photos, OCR/transcriptions, captions, dates, locations, stamp notes, and exports stay local. The optional Places map may contact Apple Maps, OpenStreetMap, or the OS geocoder for map tiles or place lookup; store systems handle purchase, restore, refund, receipt, or price display. On Android, Google ML Kit processes OCR on-device and receives limited technical diagnostics and usage metrics. No accounts, ads, tracking, developer-operated analytics, or developer backend are used.
<!-- store-audit-2026-06-29-end -->

**Applies to:** Postcard Archive for iOS / iPadOS / macOS (Mac Catalyst) and Postcard Archive for Android.

Postcard Archive is an offline-first, private archival app for postcard collectors. This policy explains, plainly, what we do and do not collect.

## What we collect

**We collect nothing.** Postcard Archive has no user accounts, no cloud sync, no advertising, no tracking, and no analytics or crash-reporting service operated by us.

The app has no server of our own, and it sends nothing about you to us. Its core archival features work fully offline. Network access is limited to the optional Full Access map, the platform purchase service, and Google ML Kit's technical diagnostics on Android, as described below.

## What stays on your device

Every postcard you add to Postcard Archive — including the front and back images, captions, dates, locations, stamp and postmark notes, condition, themes, transcriptions, and any other field you fill in — is stored only in this app's local storage on your device.

- On iOS, iPadOS, and macOS (Mac Catalyst), data is stored in a local SwiftData store inside the app's sandbox.
- On Android, data is stored in a local Room (SQLite) database inside the app's private internal storage.

The app does not transmit this data anywhere.

## Maps and geocoding

Postcard Archive Pro includes an optional map ("Places") that plots your postcards across the world. While that map is open — and only then — the app uses your device's network in two narrow ways:

- **Map tiles.** The background map imagery is fetched over the network while the map is open. On iOS, iPadOS, and macOS the tiles come from Apple Maps (MapKit); on Android they come from the OpenStreetMap tile servers. These requests carry only what any map request needs — the area being viewed — plus the ordinary network metadata every internet request includes (such as your device's IP address and a standard app/user-agent string, which the provider needs in order to deliver the imagery). They include no postcard data and no account.
- **Place lookup (geocoding).** To drop a pin, the app asks your device's built-in geocoder to turn a place *name* you typed (for example, "Paris, France") into coordinates. On iOS, iPadOS, and macOS this is Apple's geocoder; on Android it is the operating system's geocoding service. Only that short place-name text is sent, only for cards you gave a location, and the resulting coordinates are cached on your device so the map then works offline.

We run none of these services and receive none of this traffic. No postcard images, notes, or personal details are transmitted. On Android the Places tab opens to an offline list by default, so map-related network use happens only if you choose to open the map. Map tiles and geocoding are handled by Apple, the OpenStreetMap Foundation, or your Android system geocoder under their own terms.

## Purchases

Postcard Archive offers one optional Full Access in-app purchase. The app contacts Apple's App Store or Google Play Billing to load the local price, complete or restore a purchase, and verify the resulting entitlement. Apple or Google may process the account, payment, device, and transaction information needed to provide their store service under their own privacy policies.

We do not operate a purchase server and do not receive your payment details or postcard archive. The app receives only the product, transaction, and entitlement status supplied by the platform so it can unlock Full Access on your device.

## On-device text recognition on Android

The Android app uses the bundled Google ML Kit Text Recognition SDK to read postcard text. Postcard images, recognized text, and recognition results are processed on-device and are not sent to Google.

Google states that ML Kit may occasionally contact its servers for bug fixes, model updates, and hardware-compatibility information, and sends technical metrics for diagnostics and usage analytics. For the bundled SDK these metrics can include device and app information, a per-installation identifier not intended to identify a person or physical device, performance and latency, API configuration, input/output size, feature version, event type, and error codes. Google states that this data is encrypted in transit and is not shared with third parties. We do not receive these metrics. Google's ML Kit terms and privacy documentation govern this processing.

## Photos and camera permission

If you grant the app access to your photo library, the app reads images you select. The selected image is copied into your local archive. The app does not upload your photos.

If you grant camera access (where applicable), the app captures images directly into your local archive. Camera frames are not transmitted.

You can deny or revoke these permissions at any time in your operating system's Settings; the app will still run but image-capture features will be unavailable.

## Exports

You can export your archive as a CSV or JSON file from the app's Settings screen. The exported file is written to a local temporary location on your device and offered to you through the system share sheet, where you choose the destination (Files, AirDrop, Mail, another app, etc.).

The contents and destination of an exported file are entirely under your control. We do not see what you export or where you send it.

## Device storage

On iOS, device-level copies follow Apple's standard rules for app sandbox data. The data is not synchronised separately by us.

On Android, the app sets `android:allowBackup="false"`: the postcard database is not copied to Google's servers and is excluded from device-transfer. Your collection stays on the device. To move or preserve a copy of it, use the in-app Postcard Archive Full Access CSV/JSON export tool, which you control entirely.

## Children's privacy

The app does not knowingly collect any personal information from anyone, including children under 13. The app contains no advertising and no behaviour tracking.

## Data sharing

We do not sell, share, rent, or otherwise disclose your postcard data because we never have it. The platform stores, map providers, system geocoder, and Google ML Kit process only the limited information described above under their own terms.

## Changes to this policy

If we change this policy, the new version will appear in a future release of the app and at this URL. The version of this document that ships with your installed app is the version that applies to you.

## Contact

Questions about this policy can be sent to **[rizkcorsight@rizkcorsight.com](mailto:rizkcorsight@rizkcorsight.com)**.
