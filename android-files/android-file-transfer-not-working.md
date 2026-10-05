---
title: Android phone not showing up on your Mac? What to check
description: Android File Transfer or another app doesn't see your Android phone on a Mac? Check these causes, from the USB mode to apps that hold on to the phone.
lang: en
permalink: /android-files/android-file-transfer-not-working/
---

# Android phone not showing up on your Mac?

Android File Transfer, or another app for copying files from an Android phone, doesn't see the phone? Most of the time it's one of these. Try them in order.

## 1. Unlock the phone and choose File transfer

When you plug it in, an Android phone usually only charges. Unlock it, tap the USB notification ("Charging this device via USB") and choose **File transfer** (on some phones "File transfer / Android Auto"). Photo transfer (PTP) shows only photos, and MIDI shows nothing.

Many phones go back to charging only every time they are plugged in, so choose File transfer again after each reconnect. If the phone asks whether to allow access to its data, tap Allow.

## 2. Use a cable that carries data

Some USB cables can only charge. Try the cable that came with the phone, or another cable you know copies data.

## 3. Plug straight into the Mac

Hubs, docks and adapters can get in the way. Connect the phone directly to a port on the Mac, and try another port.

## 4. Quit apps that hold on to the phone

Over USB, only one app at a time can use the phone. Photos, Image Capture, Android File Transfer, OpenMTP and similar apps can take it over, even in the background. Quit them, then unplug the phone and connect it again.

## 5. Restart the phone

If nothing above helps, restart the phone, plug it in again and choose File transfer.

## Transfers are slow?

A USB 2 cable or port limits copies to about 30 MB/s, even when the phone and the Mac support USB 3. A shorter, USB 3 cable plugged straight into the Mac is usually fastest.

## A Mac app for this

[{{ site.android_files_name }}](/android-files/support/) is a Mac app I make for exactly this: browse an Android phone's files over USB, with photo and video thumbnails and a gallery, drag files both ways between the phone and Finder, and see what's slowing a copy down (the cable, a hub or a port). It's coming soon to the Mac App Store. <!-- TODO: link the App Store page at launch. -->

---

This page is from the developer of {{ site.android_files_name }}, an independent app. It isn't affiliated with or endorsed by Google. Android is a trademark of Google LLC.
