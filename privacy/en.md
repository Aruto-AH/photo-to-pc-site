---
title: Photo to PC Privacy Policy
lang: en
---

# Photo to PC Privacy Policy

[日本語](index.md)

- Effective date: October 6, 2026
- Provided by: Alto Software ("we")

Photo to PC ("the app") lets you send photos and files from a phone's web browser to the Windows PC where the app is installed, over the same Wi-Fi network. This page explains what information the app handles and where it is kept.

## Summary

- Photos and files go directly from a phone on the same Wi-Fi to the PC. Nothing is sent to us or to any outside server.
- The connection is not encrypted. Use the app only on a Wi-Fi network you trust, such as at home.
- Photo location (GPS) is kept as is by default. You can remove it from JPEG photos in Settings.
- No account, no ads, and no usage reporting.

## 1. We do not collect your information

- The app does not send personal information or usage data to us or to any third party.
- The app does not use any external server. It has no telemetry (usage reporting), no ads, and no automatic update checks.
- No account is needed.

App updates are delivered by the Microsoft Store. Information handled by the Store is covered by the [Microsoft Privacy Statement](https://privacy.microsoft.com/privacystatement).

## 2. How your files move

- Files go directly from a phone on the same Wi-Fi to the save folder on the PC. They do not pass through any server on the internet.
- The default save folder is "Pictures\Photo to PC". You can change it in Settings.
- No app is needed on the phone. Scan the QR code shown on the PC with the phone's camera, and send from the phone's web browser.

## 3. The connection is not encrypted

- To receive files from your phone, the app runs a small web server on the PC (HTTP, port 8765).
- The connection is **not encrypted** (it is not HTTPS). Other people on the same Wi-Fi may be able to see what you send. Use the app only on a Wi-Fi network you trust, such as at home.
- To keep other people from sending files, the QR code contains an "access key". The key is shown only on the app's screen and is never written to files or logs.
- The key in the QR code can be used only once. The phone's browser that reads it receives a separate key for that phone in a cookie, and the QR code changes. When you choose "Resume receiving" or "Refresh QR code" on the PC, both keys are renewed and the old ones stop working.
- The app does not accept connections from outside the same Wi-Fi (the same network). It stops receiving automatically when nothing is sent for a while (30 minutes by default; you can change this in Settings).

## 4. Location and date taken in photos

- By default, the location (GPS) and the date taken are kept in your photos.
- If you set "Location in photos" to "Remove from JPEG photos" in Settings, the app removes only the location from received JPEG photos. Image quality does not change.
- This setting does not remove location from HEIC photos or videos.
- Files that contain location are shown as "Included" in the "Location" column of the receive history (and in Windows notifications, when the app is set to show them). Check them before you share them.
- When a photo or video has a date taken, the app sets the saved file's modified date to that date, so that files sort in the order they were taken.
- If you don't want to send location from the phone, turn it off in the phone's photo picker (on iPhone, under "Options").

## 5. What the app stores on the PC

The app stores the following only in its own app data folder on the PC. It does not send them anywhere.

- **Settings**: save folder, whether to remove location, notifications, auto-stop time, port number, and other choices you make in Settings
- **Receive history (up to 500 entries)**: date and time received, file name, size, format, whether the file contains location, result (saved or canceled), and where the file was saved
- **Temporary files for unfinished transfers**: the part of a file received so far. It is deleted when the file is saved or canceled, or 24 hours after the last data was received.

The receive history does not include the access key, IP addresses, or information about the phone. You can clear it at any time with "Clear history" on the Receive history screen. Clearing the history does not delete the files you received.

Counts such as the number of connected phones are kept in memory only while the app is running. They are not written to files.

## 6. Network check

The "Can't connect?" check only reads the PC's network type (private or public) and firewall rules. It does not change any settings.

If you copy the check results, they include IP addresses and network adapter names. Keep this in mind if you share them. The app never sends them anywhere.

## 7. When you uninstall

- If you installed the app from the Microsoft Store, uninstalling it deletes the settings, receive history, and temporary files.
- Files in your save folder are not deleted.
- If you changed the port and added a firewall rule yourself, that rule is not removed when you uninstall. Remove it with the command shown in Settings.

## 8. Changes to this policy

If we change this policy, we will update this page and its effective date.

## 9. Contact

Email: alto-software@outlook.com
