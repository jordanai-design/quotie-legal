---
title: Privacy Policy
---

# Quotie — Privacy Policy

**Effective date: 2 May 2026**

This Privacy Policy explains how Quotie ("the app", "we", "our") handles your information.

## TL;DR

- All your activity in the app (favorites, quiz history, streaks, settings) is stored **only on your device**. Nothing is sent to our servers.
- We don't track you. There are no analytics, no advertising, no third-party tracking SDKs.
- The app downloads public quote content from a hosted manifest. No personal information is sent in those requests.
- If you sign in to Apple's Game Center, leaderboards and achievements sync via Apple's infrastructure under Apple's privacy terms — we never see that data.

## Who we are

Quotie is developed by Yarden Akaby as an independent personal project. Contact: jordan.akaby@gmail.com.

## What the app stores on your device

All of the following live in your device's local SwiftData store and never leave your device through us:

- **App activity** — quote favorites, quote history (which quotes you've seen), quiz attempts and results, current streak, XP total, earned badges, like/dislike preferences for individual quotes
- **Settings** — selected theme, notification preferences, sound effects toggle, content categories

## What we do *not* collect

- No analytics (no Mixpanel, Firebase Analytics, Amplitude, or similar)
- No advertising or ad-tracking identifiers (no IDFA, IDFV, or other tracker)
- No location data
- No contact list, photo library, microphone, or camera access
- No personal identifiers — the app has no account system; we don't ask for your name, email, or login
- No usage telemetry sent to us

The app's [Privacy Manifest](https://github.com/jordanai-design/quotes-app/blob/main/QuotesApp/PrivacyInfo.xcprivacy) declares `NSPrivacyTracking: false` to formalize this.

## Network requests the app makes

Two outbound request types, both anonymous:

1. **Quote content updates** — the app may periodically fetch updated quote and category data from a public manifest URL. These requests contain no personal information and are not associated with any account.
2. **Game Center (optional)** — if you sign in to Game Center, Apple handles all data flow. See [Apple's Game Center privacy terms](https://www.apple.com/legal/internet-services/itunes/dev/stdeula/).

## Third-party services

- **Apple Game Center** — optional. If you sign in, Apple syncs your achievements and leaderboard scores. Governed by Apple's privacy policy.
- **RevenueCat** — used for in-app purchase processing. Currently dormant (in-app purchases are not yet active in the app). When the paywall ships in a future update, RevenueCat will receive only the App Store transaction information needed to verify your purchase. See [RevenueCat's privacy policy](https://www.revenuecat.com/privacy/).

## iCloud sync (not yet enabled)

Currently, the app does **not** sync your data to iCloud. A future update may introduce optional iCloud sync, in which case your data would sync only to your own iCloud account via Apple's CloudKit infrastructure — we would never see that data. This Privacy Policy will be updated to reflect that change before the feature ships.

## Sharing quotes

When you tap the share button, you choose where to send a quote (Messages, social apps, etc.) using the iOS system share sheet. The shared content is the quote text, its author, and a Quotie watermark — no personal information of yours is included.

## Push notifications

If you enable notifications, the app schedules them locally on your device using Apple's UNUserNotificationCenter. We don't send notifications from a server, so no notification content passes through us.

## Your rights and choices

- **Delete all data** — delete the app from your device. All app activity is removed at the same time.
- **Disable notifications** — iOS Settings → Quotie → Notifications.
- **Disable sound effects** — In-app Settings → Sound effects toggle.
- **GDPR / CCPA** — because we don't store data on our servers, there's nothing for us to access, export, or delete on your behalf. Your data remains in your control on your own device.

## Children's privacy

Quotie is not directed at children under 13 (or 16 in the EU/UK). The app does not knowingly collect personal information from children. Since the app has no account system and stores no data on our servers, the practical risk is minimal. If you believe a child has provided information through the app, please contact us.

## Changes to this policy

If we make material changes, we'll update the **Effective date** above and, where appropriate, surface the change in the app on the next launch.

## Contact

Questions or concerns: **jordan.akaby@gmail.com**.
