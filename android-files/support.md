---
title: Help & support (Android files for Mac)
lang: en
permalink: /android-files/support/
---

# {{ site.android_files_name }} help & support

## Contact

Write to [{{ site.contact_email }}](mailto:{{ site.contact_email }}), and please include the app version ({{ site.android_files_name }} → About {{ site.android_files_name }}), your Mac's macOS version, your phone model and what happened. I read every message.

## Questions

### What do I need?
A Mac with Apple silicon (M1 or later) and macOS 14 or later, an Android phone or tablet that offers File transfer over USB, and a USB cable that carries data.

### How do I connect my phone?
Connect the phone to your Mac with a USB cable and unlock the phone. Then tap the USB notification on the phone and choose File transfer (on some phones it's called "File transfer / Android Auto"). The phone's files appear in the app a moment later.

Some phones go back to charging only each time you plug them in, so you may need to choose File transfer again after reconnecting. If the app says the phone shows no storage, unlock the phone and choose File transfer.

### The app doesn't find my phone
- Use a cable that carries data. Some USB cables can only charge.
- Unlock the phone and choose File transfer in the USB notification, not photo transfer (PTP), MIDI or another mode.
- Quit Photos, Image Capture, Android File Transfer and OpenMTP. They can take over the phone so that no other app can use it. Then unplug the phone and connect it again.

More tips are on [Android phone not showing up on your Mac?](/android-files/android-file-transfer-not-working/)

### Transfers are slow
The bar above the file list shows the speed of the USB connection, and each running transfer shows its current speed. If the connection speed is shown in orange, the connection is slower than it could be: click it to see which part is the likely limit (the phone, the cable, a USB hub or the Mac's port) and what to do about it.

A common cause is a USB 2 cable: it limits transfers to about 30 MB/s even when the phone and the Mac support USB 3. Plugging the phone straight into the Mac, without a hub, can also help. Speed also depends on the phone.

### Why does a transfer say "Waiting"?
Over USB, the phone handles one operation at a time, so transfers run one after another and the next one waits in line. You can keep browsing while a transfer runs: the app lists folders between the parts of a file. Opening or previewing a file goes ahead of the transfers in line.

### Does copying overwrite files with the same name?
No. If a file or folder with the same name is already there, the copy gets a new name, such as "photo (1).jpg".

### Can I undo a delete?
No. Deleting removes the items from the phone at once, folders with everything inside, and there is no trash for files deleted over USB. The app asks you to confirm first.

### Can I edit a file on the phone?
Not directly. Opening a file opens a read-only copy on your Mac. To change it, save your edited version under a new name (for example with Save As or Duplicate) and upload it to the phone.

### How do I see thumbnails of photos and videos?
Choose View → as Icons (⌘2), or the view switch in the toolbar. Photos and videos in the current folder show thumbnails. To look at a file in full size, select it and press Space for Quick Look.

### Is there a gallery for photos and videos?
Yes. Choose View → as Gallery (⌘3), or the gallery button in the toolbar. The current folder's photos and videos show as tiles, with its folders so you can move around; the slider at the bottom changes the tile size. Double-click a photo or video to see it large in the window, use ← and → to move to the previous or next one, and press Esc to go back to the tiles. A photo or video is copied from the phone before it shows, so a long video takes a moment.

<!-- TODO: files over 4 GB haven't been tested on a real phone yet. Add a question about them only after they are. -->

### Is the app free?
Browsing, previews, the gallery, and creating, renaming and deleting files are free. Copying is free for up to 10 files a day, in either direction: downloads, uploads and files dragged out to Finder all count, and a folder counts the files inside it. Quick Look, the gallery's large view and opening a file in another app don't count. The count starts again at midnight.

For unlimited copying, buy Unlimited Transfers once (no subscription). It stays unlocked in every update. If a copy needs more files than are left today, the app asks before it starts and never stops a copy that is running.

### I bought Unlimited Transfers. How do I get it on another Mac?
Sign in with the same Apple Account in the App Store, open the app and choose {{ site.android_files_name }} → Restore Purchases. The same works after reinstalling the app.

### How do I change the language?
Choose {{ site.android_files_name }} → Settings (⌘,) → Language. The app is available in English, Chinese (Simplified and Traditional), Czech, Dutch, French, German, Greek, Hungarian, Italian, Japanese, Korean, Polish, Portuguese, Romanian, Russian, Spanish, Swedish, Turkish and Ukrainian, or it can follow your Mac's language (System Default). The new language is used after the app relaunches: click Relaunch Now, or quit and open the app again.

### Does the app need the internet or Wi-Fi?
Not for browsing or copying: the app works over the USB cable only and doesn't transfer files over Wi-Fi. It uses the internet only for the Unlimited Transfers purchase. Once bought, it stays unlocked when your Mac is offline. The Help and Privacy Policy pages open in your browser.

### What data does the app collect?
Your files go only between your Mac and your phone, and the app has no account, no ads, no analytics and no tracking. For the purchase, RevenueCat receives a random app user ID, your purchase history for this app and technical data such as the macOS version. Details are in the [privacy policy](/android-files/privacy/).

## Open-source components

{{ site.android_files_name }} uses these libraries, unmodified. Their license texts are inside the app (Contents/Resources/Licenses).

- [libmtp](https://github.com/libmtp/libmtp) 1.1.23, GNU Lesser General Public License 2.1 or later. Source: [libmtp-1.1.23.tar.gz](https://downloads.sourceforge.net/project/libmtp/libmtp/1.1.23/libmtp-1.1.23.tar.gz)
- [libusb](https://github.com/libusb/libusb) 1.0.30, GNU Lesser General Public License 2.1 or later. Source: [libusb-1.0.30.tar.bz2](https://github.com/libusb/libusb/releases/download/v1.0.30/libusb-1.0.30.tar.bz2)
- [RevenueCat purchases-ios](https://github.com/RevenueCat/purchases-ios), MIT License

libmtp and libusb are linked dynamically, as separate libraries in Contents/Frameworks. Write to me if you'd like their source sent to you.

Android is a trademark of Google LLC.
