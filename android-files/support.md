---
title: Help & support (Android files for Mac)
lang: en
permalink: /android-files/support/
---

# {{ site.android_files_name }} help & support

## Contact

Write to [{{ site.contact_email }}](mailto:{{ site.contact_email }}), and please include the app version ({{ site.android_files_name }} → About {{ site.android_files_name }}), your Mac's macOS version, your phone model and what happened. I read every message.

## Questions

### How do I connect my phone?
Connect the phone to your Mac with a USB cable and unlock the phone. Then tap the USB notification on the phone and choose File transfer (on some phones it's called "File transfer / Android Auto"). The phone's files appear in the app a moment later.

Some phones go back to charging only each time you plug them in, so you may need to choose File transfer again after reconnecting. If the app says the phone shows no storage, unlock the phone and choose File transfer.

### The app doesn't find my phone
- Use a cable that carries data. Some USB cables can only charge.
- Unlock the phone and choose File transfer in the USB notification, not photo transfer (PTP), MIDI or another mode.
- Quit Photos, Image Capture, Android File Transfer and OpenMTP. They can take over the phone so that no other app can use it. Then unplug the phone and connect it again.

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

### How do I change the language?
Choose {{ site.android_files_name }} → Settings (⌘,) → Language. The app is available in English, Chinese (Simplified and Traditional), Czech, Dutch, French, German, Greek, Hungarian, Italian, Japanese, Korean, Polish, Portuguese, Romanian, Russian, Spanish, Swedish, Turkish and Ukrainian, or it can follow your Mac's language (System Default). The new language is used after the app relaunches: click Relaunch Now, or quit and open the app again.

### Does the app need the internet or Wi-Fi?
No. The app works over the USB cable only. It doesn't transfer files over Wi-Fi. Only the Help and Privacy Policy pages, which open in your browser, need the internet.

### What data does the app collect?
None. The app makes no internet connections of its own, has no account, no ads, no analytics and no tracking, and your files go only between your Mac and your phone. Details are in the [privacy policy](/android-files/privacy/).
