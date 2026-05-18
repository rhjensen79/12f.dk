---
title: "Dog Stories App Privacy Policy - 12F ApS"
description: "Privacy policy for Dog Stories iOS app by 12F ApS. Your dog's records stay on your device — no servers, no analytics, no tracking."
date: 2026-05-18T12:00:00+02:00
draft: false
keywords:
  - "dog stories privacy policy"
  - "dog stories app privacy"
  - "iOS dog tracking app privacy"
  - "privacy-focused pet app"
  - "12F ApS privacy"
---
Effective Date: 2026-05-18

Summary
-------

Dog Stories stores your dog's records on your device. We don't run a server. We don't collect analytics, track you, or share anything with third parties.

About This App
--------------

Dog Stories is an iOS app for dog owners. It helps you keep track of your dog's health (weight, vaccinations, medications, vet visits), expenses, schedule and reminders, photos, and walks. Version 1 supports a single dog; the data model is built to handle multiple pets in future updates.

What's Stored on Your Device
----------------------------

Everything you enter in Dog Stories is saved locally using Apple's SwiftData framework. That includes:

- **Your dog's profile and content** you create — names, notes, memories, and similar entries
- **Photos and videos** you attach to your dog's profile or memories
- **Purchase history** for in-app purchases, linked to your Apple ID — Apple handles this; see "In-App Purchases" below

We have no servers and no databases. None of this data is sent to us.

What We Don't Do
----------------

- **No analytics.** No third-party SDKs collect usage data.
- **No advertising.** No ad networks, no ad identifiers.
- **No tracking.** The app does not track you across other apps or websites. The app's privacy manifest declares tracking as disabled and lists no tracking domains.
- **No remote crash reporting.** The app uses Apple's MetricKit for local crash diagnostics; that data stays on your device.

iCloud Sync
-----------

An iCloud container is provisioned for Dog Stories, but **no sync feature ships in version 1**. The app's data layer is built to be sync-ready, but no active sync code paths run in this release. If sync is enabled in a future version, this policy will be updated and the change will be disclosed before sync begins.

Permissions the App Requests
----------------------------

Dog Stories only asks for a permission when you use a feature that needs it. You can change any of these later in iOS Settings.

- **Camera** — to take photos of your dog directly from add forms.
- **Photo Library** — to attach existing photos to your dog's profile and memories.
- **Apple Health (read)** — to import walking workouts you've already recorded, which you can mark as a dog walk. Read-only.
- **Apple Health (write)** — the HealthKit framework is linked in the app, which is why iOS may show this string, but **Dog Stories never writes anything to Apple Health**.
- **Notifications** — to deliver local reminders for medications, vaccinations, and appointments. Reminders are scheduled on your device; nothing is sent through a remote push server.
- **Calendar** — opt-in, to write your dog's appointments to your iOS Calendar so they appear alongside the rest of your schedule.
- **Face ID** — optional, to lock the app behind biometric authentication if you choose to enable it.

What the App's Privacy Manifest Declares
----------------------------------------

To match what's filed with Apple in the app's `PrivacyInfo.xcprivacy`:

- **Tracking:** Disabled. No tracking domains.
- **Data types collected**, all used solely for app functionality and none used for tracking:
    - **User Content** (the notes, names, and similar text you create) — not linked to your identity
    - **Photos or Videos** — not linked to your identity
    - **Purchase History** — linked to your Apple ID, because in-app purchases run through Apple
- **Required Reasons APIs:** UserDefaults (to access app settings within the app's own container) and File Timestamp (to display dates to you).

In-App Purchases
----------------

Dog Stories offers one in-app purchase: **Dog Stories Premium** (`12f.dog_stories.premium.lifetime`), a one-time lifetime unlock. Apple handles the transaction through the App Store. The app never sees your card details. Your purchase is associated with your Apple ID so you can restore it on your other devices.

Apple's Role
------------

Apple processes your in-app purchase and, if iCloud sync is enabled in a future version, would handle that sync. Apple's handling of that data is governed by their privacy policy: <https://www.apple.com/legal/privacy/>.

Children's Privacy
------------------

Dog Stories is not directed at children under 13. The App Store age rating is 4+. Because everything stays on your device and we collect nothing, we have no way to identify or contact users of any age.

Data Retention and Deletion
---------------------------

All your data lives on your device. To delete it, delete the app — iOS removes the app's data with it. You can also delete individual entries from within the app at any time.

Contact
-------

For any privacy questions:

- Email: [robert@12f.dk](mailto:robert@12f.dk)
- Website: [www.12f.dk](https://www.12f.dk)

Changes to This Policy
----------------------

If this policy changes, the effective date at the top of this page will be updated, and a revised policy will be posted here and on the App Store. Material changes — such as enabling iCloud sync — will be called out clearly.
