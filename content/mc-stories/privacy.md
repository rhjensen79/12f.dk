---
title: "MC Stories App Privacy Policy - 12F ApS"
description: "Privacy policy for MC Stories iOS app by 12F ApS. Your motorcycle records stay on your device and in your private iCloud — no 12F servers."
date: 2026-07-25T00:00:00+02:00
draft: false
keywords:
  - "mc stories privacy policy"
  - "mc stories app privacy"
  - "motorcycle maintenance app privacy"
  - "iOS motorcycle tracking app privacy"
  - "12F ApS privacy"
---
Effective Date: 2026-07-25

Summary
-------

MC Stories stores your motorcycle records on your device and syncs them through your own private iCloud account. We don't run a server and never see your data. The app includes optional, anonymous usage analytics that you can turn off in Settings — it never includes your motorcycle data.

About This App
--------------

MC Stories is an iOS app for motorcyclists. It helps you track each bike's maintenance and parts, purchase and running costs, mileage, rides (recorded in the app with GPS or imported from a GPX file), track days and lap times, fuel, tyres, photos, and documents such as manuals, receipts, and warranties.

What's Stored on Your Device and in Your iCloud
-----------------------------------------------

Everything you enter in MC Stories is saved locally using Apple's SwiftData framework and synced through **your private iCloud (CloudKit)** so it's available on your other devices signed in to the same Apple ID. That includes:

- **Your motorcycles and their content** you create — names, notes, parts, maintenance records, costs, mileage, fuel, tyres, track days and lap times
- **Rides and their GPS routes**, whether recorded in the app or imported from a GPX file
- **Photos** you attach to motorcycles, parts, rides, or damage records
- **Documents** you add, such as manuals, receipts, and warranties, stored inside the app
- **Local backups** the app makes of your data, kept on your device
- **Purchase history** for the in-app purchase, linked to your Apple ID — Apple handles this; see "In-App Purchases" below

This data lives on your device and in your private iCloud. 12F has no servers and no access to it.

Location and Ride Recording
---------------------------

When you record a ride, MC Stories uses your device's location to trace the route and measure the distance. This happens **only while a ride is recording**, and recording continues in the background so the route isn't lost when your screen locks or you switch apps — which is why iOS shows the location indicator during a ride.

- Your route is stored **on your device and in your private iCloud**, alongside the ride. It is never sent to 12F.
- Location is not collected when you are not recording a ride.
- You can stop a recording at any time, and you can revoke the permission in **iOS Settings → Privacy & Security → Location Services**.

VIN Lookup
----------

If you enter a VIN and tap **Decode**, MC Stories sends that VIN over HTTPS to the **NHTSA vPIC** service — a free public vehicle database run by the U.S. National Highway Traffic Safety Administration — to prefill the brand, model, year, engine size, and fuel type. This is the only feature that sends anything you typed off your device.

- It sends the **VIN only**. No name, no account, no other content from the app, and nothing that identifies you or your device.
- It happens **only when you tap Decode**. Nothing is sent while you type, and the feature is entirely optional — every field it fills can be entered by hand.
- The lookup is best-effort: if it fails, you simply fill the fields yourself.
- NHTSA's handling of requests to that service is governed by their own privacy policy: <https://www.nhtsa.gov/privacy-policy>.

Analytics
---------

MC Stories includes **anonymous, non-identifying usage analytics** (via PostHog, hosted in the EU) to help us understand which features are used and improve the app. This data is **opt-out**: it's on by default and you can turn it off at any time in **Settings → Share anonymous analytics**.

- It records anonymous app-usage events (for example, that a feature was opened) and basic device/app information.
- It **never** includes your motorcycle data — names, notes, photos, documents, costs, rides, routes, VINs, or any content you create.
- It is not used to track you across other apps or websites, and it is not sold or shared for advertising.

When you turn the toggle off, the analytics SDK stops collecting and opts out.

iCloud Sync
-----------

MC Stories syncs your data through Apple's CloudKit using **your private iCloud database**. Only you, on your own Apple ID, can access it. 12F cannot read it. Apple's handling of iCloud data is governed by their privacy policy: <https://www.apple.com/legal/privacy/>.

What We Don't Do
----------------

- **No 12F servers.** We don't run a backend or database. Your content never reaches us.
- **No advertising.** No ad networks, no ad identifiers.
- **No selling your data.** We never sell or share your content with third parties.
- **No tracking across apps.** The app does not track you across other apps or websites.

Permissions the App Requests
----------------------------

MC Stories only asks for a permission when you use a feature that needs it. You can change any of these later in iOS Settings.

- **Location (while using the app)** — to record a ride's route and distance. Recording continues in the background for the duration of the ride; see "Location and Ride Recording" above.
- **Camera** — to take photos of your motorcycles, parts, and rides directly from add forms.
- **Photo Library** — to attach existing photos to your motorcycles, parts, and rides, and to save motorcycle photos back to your library.
- **Notifications** — to deliver local reminders for maintenance, service, warranty expiry, and document renewals. Reminders are scheduled on your device.

In-App Purchases
----------------

MC Stories offers one in-app purchase: **MC Stories Pro** (`12f.mc_stories.pro`), a one-time, non-consumable unlock. Apple handles the transaction through the App Store. The app never sees your card details. Your purchase is associated with your Apple ID so you can restore it on your other devices.

Apple's Role
------------

Apple processes your in-app purchase and handles the iCloud sync of your data. Apple's handling of that data is governed by their privacy policy: <https://www.apple.com/legal/privacy/>.

Children's Privacy
------------------

MC Stories is not directed at children under 13. The App Store age rating is 4+. We collect no personal data on our own servers, so we have no way to identify or contact users of any age.

Data Retention and Deletion
---------------------------

Your data lives on your device and in your private iCloud. You can delete individual entries from within the app at any time. To remove everything, delete the app and remove its iCloud data in **iOS Settings → your name → iCloud**.

Contact
-------

For any privacy questions:

- Email: [mc-stories@12f.dk](mailto:mc-stories@12f.dk)
- Website: [www.12f.dk](https://www.12f.dk)

Changes to This Policy
----------------------

If this policy changes, the effective date at the top of this page will be updated, and a revised policy will be posted here and on the App Store. Material changes will be called out clearly.
