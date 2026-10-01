---
title: Multitool privacy policy
lang: en
permalink: /multitool/privacy/
---

# Multitool privacy policy

Last updated: {{ site.privacy_effective }}

Multitool is a toolbox app for Android and iOS.

- Developer, responsible for your data ("I", "me" below): {{ site.developer }}
- Published on Google Play by: {{ site.publisher_google_play }}
- Published on the App Store by: {{ site.publisher_app_store }}
- Contact: [{{ site.contact_email }}](mailto:{{ site.contact_email }})

## In short

- No account, no ads, no tracking, and I don't collect usage analytics.
- What you measure, scan, type and photograph is processed on your phone and isn't sent to me, unless you send it to me yourself as feedback.
- A few service providers receive technical data: for crash reports (you can turn them off), for Pro purchases, and on Android for reading barcodes.
- When you send me feedback, I receive your message.
- I don't sell or share your data.

## What stays on your phone

The tools work on the device. What they read isn't sent to me or anyone else:

- **Camera** (QR scanner, magnifier): the picture is analysed live. It is saved only when you save a frozen picture in the magnifier, and then only to your own photo library.
- **Photos and files** (QR scanner): when you pick a photo, PDF or Word file to scan, only that file is read, to find codes in it. The app may keep a temporary copy in its own cache, which the system clears. It is never uploaded.
- **Microphone** (sound meter): the loudness is measured live. Nothing is recorded or stored.
- **Location** (GPS info; the Wi-Fi name in Network info, which Android and iOS only give to apps with location access): used only while the tool is open, shown on screen, never stored or sent.
- **Motion and other sensors** (level, compass, sensor dashboard): read live, never stored or sent.
- **Local network** (ping in Network info, iOS asks for this separately): used only to reach the address you enter, such as your router.
- **Notifications and alarms** (timer): used only to ring when a timer ends, on time, even if the app is closed.
- **Clipboard**: the app reads or writes it only when you tap Paste or Copy.
- **Text you type or paste and codes you scan** (dev utilities, QR generator, converters, QR scanner): processed on the device. When you tap Share, the system share sheet opens and you choose where it goes.

### What the app saves on your phone

The app keeps its settings, pinned tools and tool preferences (for example the ruler calibration) in its own storage. So that you don't have to start over, it also keeps what you last entered in some tools: the text of the QR codes and barcodes you create, the last ping address, converter and percentage inputs, and the stopwatch and timer state.

This storage is deleted when you uninstall the app. If device backup is turned on in your phone's settings, Android or iOS may include it in your backup (in your Google or iCloud account, or on your computer) and restore it on a new phone. That backup belongs to your account; I have no access to it.

### Permissions

The app asks for a permission only when you use a feature that needs it, and everything that doesn't need a permission works without it. You can withdraw a permission at any time in the system settings.

## What leaves your phone

### Service providers

Some features rely on service providers. They receive **technical data** only, such as the device model and operating system, the app version and settings, random IDs for this installation, your IP address, and performance and error information. They are not given what you scan, type, measure or photograph, and none of it is used for advertising.

**Crash and error reports: Google (Firebase Crashlytics)**
- When the app crashes or hits an error, it sends a report so that I can find and fix the problem: the error and where in the code it happened, technical data as above, the tool or screen that was open, and a short technical log of app events (for example "torch turned on"). Each time the app starts, it also sends a small session event, so that I can see how often the app runs without crashing.
- Reports are designed not to contain your content. Error messages come from the system, though, and in rare cases one may include a detail such as a file name.
- Legal basis: my legitimate interest in keeping the app working (Art. 6(1)(f) GDPR).
- Reports are on by default. Turn them off at any time in Settings → Send crash reports.
- Kept for 90 days. See [Firebase's privacy information](https://firebase.google.com/support/privacy).

**Pro purchases: RevenueCat**
- Multitool Pro is a one-time purchase made through Google Play or the App Store. Payment is handled entirely by Google or Apple under their own privacy policies. I never see your name, email address or payment details.
- RevenueCat checks the purchase, unlocks Pro and restores it on a new phone. It receives your purchase history for this app (the store receipt), a random app user ID, your country and currency, and technical data as above.
- Legal basis: performing the purchase contract (Art. 6(1)(b) GDPR).
- Kept until you ask me to delete it (see Your rights). See [RevenueCat's privacy policy](https://www.revenuecat.com/privacy).

**Reading barcodes on Android: Google (ML Kit)**
- On Android, the QR scanner reads codes with Google's ML Kit on the device. The picture and the codes stay on your phone. ML Kit sends Google technical data as above, plus which ML Kit features ran and how well, which Google uses to maintain and improve ML Kit.
- Legal basis: my legitimate interest in offering a reliable scanner (Art. 6(1)(f) GDPR).
- This happens only when you use the scanner, and it can't be turned off in the app. See [ML Kit's data disclosure](https://developers.google.com/ml-kit/android-data-disclosure).
- On iOS the scanner uses Apple's Vision framework, which works entirely on the device.

Each provider processes this data under its data processing terms, which protect it at least as well as this policy.

### Messages you send me

- **Send feedback and Suggest a tool** send me your message together with where you wrote it, the star rating if you came from the rating prompt, and the app version and platform. Please don't include personal details you don't want me to have. <!-- TODO: name the feedback service and where messages are stored once the feedback package is integrated. -->
- **Email**: if you write to the address above, I receive your email address and message.
- Legal basis: my legitimate interest in answering and improving the app (Art. 6(1)(f) GDPR), or performing the purchase contract for purchase questions (Art. 6(1)(b)).
- Kept until the matter is dealt with, and no longer than two years.

### Rating the app

When you rate the app with 4 or 5 stars, the app opens Google Play's or the App Store's own rating dialog. What you write there goes to the store under its privacy policy; the app doesn't see it. With 1 to 3 stars, the app opens the feedback page instead, and nothing is sent until you tap Send.

### Network tools, only when you use them

- **Ping** (Network info) sends network requests to the address you enter. That server sees your IP address, as with any connection.
- **Public IP address** (Network info) asks the ipify service (api64.ipify.org) which address the internet sees. ipify learns your IP address. This happens only when you tap Look up.
- **Links** in scanned codes open in your browser only when you tap Open. The same goes for Help & FAQ and Privacy policy in Settings (pages on GitHub Pages), and Rate the app opens the store. The website's or store's own privacy policy then applies.

## What the app doesn't do

- No analytics of my own, no advertising IDs, fingerprinting or cross-app tracking.
- No selling or sharing of data with advertisers or data brokers.
- No account, and no collection of your name, contacts or location history.
- No automated decisions about you.

## Transfers outside your country

Google and RevenueCat may process data in the United States and other countries, under data processing terms that include the EU Standard Contractual Clauses. Data is encrypted in transit.

## Children

The app is not directed at children and doesn't knowingly collect personal data from them.

## Your rights

Under the GDPR and similar laws, you have the right to access, correct and delete your personal data, to restrict its processing, and to receive it in a portable form. You also have the right to complain to your data protection authority.

**You can object at any time** to processing based on legitimate interest. For crash reports, turn them off in Settings → Send crash reports; for anything else, write to me.

The app holds no data that identifies you directly, so for most requests there is nothing to find. For purchases, write to me with the order number from your Google Play or App Store receipt, and I will have the RevenueCat record deleted. This doesn't take Pro away: your store still knows you bought it, and Restore purchases brings it back. For feedback, tell me roughly when you sent it and what it said.

## Changes

If this policy changes, the new version is published on this page with a new date.

## Contact

Questions and requests: [{{ site.contact_email }}](mailto:{{ site.contact_email }})
