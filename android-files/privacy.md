---
title: Privacy policy (Android files for Mac)
lang: en
permalink: /android-files/privacy/
---

# {{ site.android_files_name }} privacy policy

Last updated: {{ site.android_files_privacy_effective }}

{{ site.android_files_name }} is a Mac app for browsing the files on an Android phone connected with a USB cable, and for copying files between the Mac and the phone.

- Developer, responsible for your data ("I", "me" below): {{ site.developer }}
- Published on the Mac App Store by: {{ site.publisher_app_store }}
- Contact: [{{ site.contact_email }}](mailto:{{ site.contact_email }})

## In short

- The app makes no internet connections of its own. Your files go only between your Mac and your phone, over the USB cable.
- No account, no ads, no tracking, no analytics and no crash reports.
- I don't receive, sell or share any of your data.
- When you write to me, I receive your message.

## What stays on your Mac and your phone

- **Your phone's files**: the app lists the folders you open and copies the files you choose, over USB. File names, thumbnails and file contents are shown in the app and aren't sent anywhere else.
- **Files on your Mac**: the app reads a file or folder on your Mac only when you choose it for upload, in the file picker or by dropping it on the window. It writes files only to the download folder you choose, or to where you drop files you drag out of the window.
- **USB connection**: to show the USB link speed and its likely limit, the app reads the details of the USB connection from macOS. They are shown on screen and not stored.

### What the app saves on your Mac

- **Settings**, in the app's preferences: the view you last chose (such as list or icons), the last download folder and the language you chose.
- **Copies of phone files**: a file you preview with Quick Look, open in another app or drag out of the window is first copied from the phone into the app's cache folder (`~/Library/Caches/DroidBrowse/Files`). The cache is emptied each time the app starts, and older copies are removed once it passes about 1 GB. <!-- TODO: check this path when the app is renamed or sandboxed (a sandboxed app's cache is inside ~/Library/Containers). -->
- **Thumbnails** are kept in memory only, and forgotten when you disconnect the phone or quit the app.

All of this stays on your Mac. If you back up your Mac (for example with Time Machine), the backup may include the app's settings, like any other file on your Mac. I have no access to it.

## What leaves your Mac

### Files you copy to your phone

They go to your phone over USB, and nowhere else. If your phone backs up its files to the cloud (for example Google Photos), the files you copy to the phone may be backed up too, under that service's privacy policy and your phone's settings.

### Help and privacy pages

{{ site.android_files_name }} Help and Privacy Policy, in the app's Help menu and in Settings, open this website in your browser. It is hosted on GitHub Pages, which sees your IP address, as any website does. See [GitHub's privacy statement](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement).

### The Mac App Store

You get the app and its updates from the Mac App Store, under [Apple's privacy policy](https://www.apple.com/legal/privacy/). If you turned on sharing with app developers in macOS (System Settings → Privacy & Security → Analytics & Improvements), Apple may share crash reports and usage statistics with me. They don't identify you.

### Messages you send me

- **Email**: if you write to the address above, I receive your email address and message.
- Legal basis: my legitimate interest in answering and improving the app (Art. 6(1)(f) GDPR).
- Kept until the matter is dealt with, and no longer than two years.

<!-- TODO: In-app purchases are planned (a free allowance of transfers, then a one-time Lifetime Unlock, possibly through RevenueCat; see MONETIZATION.md in the app's repo) but not implemented. When they ship, add a "Purchases" section modeled on Multitool's "Pro purchases: RevenueCat": payment is handled entirely by Apple; what RevenueCat receives (purchase history for this app / the store receipt, a random app user ID, country and currency, technical data such as the Mac model, macOS and app version, and the IP address); legal basis Art. 6(1)(b) GDPR; how long it is kept; a link to https://www.revenuecat.com/privacy. Also: say the app then connects to the internet for purchases (update "In short" and "What the app doesn't do"), add the free-transfer counter to "What the app saves on your Mac", add a "Transfers outside your country" section (RevenueCat in the US, Standard Contractual Clauses), and in "Your rights" explain deleting the RevenueCat record with the order number from the App Store receipt. Update the support page's FAQ and android_files_privacy_effective too. -->

## What the app doesn't do

- No internet connections of its own: no analytics, crash reporting, advertising IDs, fingerprinting or tracking.
- No account, and no collection of your name, contacts or location.
- No selling or sharing of data with anyone.
- No automated decisions about you.

## Children

The app is not directed at children and doesn't collect personal data from anyone, including children.

## Your rights

Under the GDPR and similar laws, you have the right to access, correct and delete your personal data, to restrict its processing, to object to it, and to receive it in a portable form. You also have the right to complain to your data protection authority.

The app sends me nothing, so the only data about you I can hold is email you send me. To have it deleted, or to ask anything else about it, write to me and tell me roughly when you wrote.

## Changes

If this policy changes, the new version is published on this page with a new date.

## Contact

Questions and requests: [{{ site.contact_email }}](mailto:{{ site.contact_email }})
