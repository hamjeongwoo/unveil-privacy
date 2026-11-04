---
title: "Sonbaram Privacy Policy"
permalink: /sonbaram/privacy/en/
lang: en
---

[한국어](/unveil-privacy/sonbaram/privacy/)

# Sonbaram Privacy Policy

Effective date: 2026-11-04  
Operator: un-veil ("we")  
Contact: support@un-veil.co.kr

We provide the Android app "Sonbaram" (the "app"). This policy explains what information the app handles, where it keeps it, who it may reach, and what rights you have.

## 1. At a glance

- The app reads the hand shape shown to the camera **on your phone** and runs the action you chose (open an app, open the dialer, open a message draft, control music or video).
- Camera images are used only to read the hand shape on your phone. **They are never saved and never leave your phone.**
- The app has no sign-up or login, and **we operate no server.** We do not collect or keep your information through the app.
- Information the app stores stays on your phone and is excluded from cloud backup and device-to-device transfer.
- The app has ads (Google AdMob) and a one-time purchase (Google Play Billing). Google may process some information for these two (sections 4 and 5).
- The app is intended for users aged 18 and over.

## 2. What the app handles and how

### 2.1 Camera images

| Item | Details |
|---|---|
| Purpose | To read the hand shape shown to the camera and decide whether it matches a shape you registered |
| When | After you allow the camera: (1) the screen where you show a hand shape to create a gesture, (2) the "Try it now" screen, (3) while the "Use gestures with the camera" switch on the home screen is on |
| How | Front-camera frames are processed only in your phone's memory and turned into the coordinates of 21 hand points; the image is then discarded at once. To tell you when it is too dark, the app computes one average-brightness number per frame, which is not stored either |
| Stored? | No photo or video is saved as a file. The app creates no pictures or videos in your gallery or app storage |
| Sent out? | Nothing leaves your phone. Hand reading works without the internet |
| Face and background | The app does not store faces or backgrounds and has no feature that reads faces, bodies or surroundings |
| On-screen indicator | While the camera is on, Android shows a small dot on screen, which the app cannot turn off. A status notification ("Reading your hand with the camera") is always shown while the camera is on, and its "Turn off" button stops it |

### 2.2 Information stored on your phone (app-private internal storage)

The information below is stored only in the app's private storage on your phone and is not sent to us or to third parties.

| Information | Description |
|---|---|
| Hand shape data | The three hand shapes you showed when creating a gesture, saved as the coordinates of 21 points relative to the wrist and divided by palm size. They are numbers, not pictures, but may reflect the proportions of your hand, such as finger lengths |
| Gesture information | Gesture name, on/off state, and the action linked to the gesture |
| Action settings | Open an app (target app name), call (phone number and display name), message (recipient number and text), music/video control (play/pause, next, previous) |
| Settings and state | The master switch, notification, vibration and edge-glow settings, whether you have seen the guides, whether you bought ad removal and when it was last checked, when an ad was last shown, and time records used to count the free-use period (3 days) |

- The data lives in the app's private internal storage, which other apps cannot read. It is excluded from cloud backup and device transfer (`allowBackup=false` and data extraction rules), so it is not restored when you reinstall the app or move to a new phone.
- Phone numbers and message text are either typed by you in the app, or, when you use the system contact picker, only the one number and name you pick are saved. The app does not read your whole contact list and does not request the contacts permission (READ_CONTACTS).
- The app has no feature that sends this information to a server.

### 2.3 What happens when an action runs

- When a hand shape is recognized, the app asks the matching app on your phone (Phone, Messages, KakaoTalk, YouTube, etc.) to open a screen. The phone number and message text go only to the phone or messaging app on your device. The app does not place calls or send messages itself; it only opens the screen.
- Music/video control sends your phone's media key signals (play/pause, next, previous). The app does not read what is playing.
- The app checks on your phone whether a target app is installed and does not send the result anywhere.

### 2.4 What the app does not use

The app does not use accessibility services, location, the microphone, storage (photos or files), your full contact list, call logs or the SMS inbox. It does not receive your name, email or account information. The app contains no analytics or crash-reporting tools.

## 3. Permissions the app requests

| Permission | How it is requested | Used for | If you do not allow it |
|---|---|---|---|
| Camera | A system prompt after an explanation, when you first enter the screen that shows hand shapes | Reading hand shapes (2.1) | You cannot create or read gestures; the rest of the app still works |
| Notifications | After an explanation, when you first turn the master switch on | The "camera is on" status notification, the free-use-period (3 days) notices, and opening actions from a notification while another app is in front | Some notifications may not appear |
| Display over other apps (optional) | A special permission that you turn on yourself in settings; the app never turns it on by itself | (1) Opening the chosen app, dialer or message screen directly while you use another app, without tapping a notification (2) Showing a light along the screen edge for less than 0.5 seconds when a hand shape is read. This display takes no touches, does not cover the middle of the screen, does not read other apps' screens, and contains no ads, text or images | You open actions by tapping the notification instead; everything else works. You can turn it off in settings any time |
| Vibration | A normal permission granted at install | A short vibration when a hand shape is read; can be turned off in the app settings | — |
| Foreground service (camera type) | Granted at install, no separate prompt | While you keep the master switch on, a service keeps the camera running so hands can be read over other apps, with a notification. It does not start by itself before you turn it on or after the phone restarts | — |
| Internet and network state, advertising ID, basic device state, background work, billing (Google Play) | Granted automatically at install; required by the ad and billing components | Ads and purchases (sections 4 and 5). Hand reading and storage do not use these | — |

## 4. Ads (Google AdMob)

- The app is free and shows ads (a banner and interstitial ads). Ads appear only inside the app's own screens. If you buy the ad-removal product, no ad requests are made.
- Ads are handled by Google LLC's Google Mobile Ads SDK (AdMob) and User Messaging Platform (UMP). To show ads, measure performance and prevent fraud, these components may send the following to Google. We do not receive or store this information ourselves.
  - Device and account identifiers: the Android advertising ID, app set ID and, where applicable, identifiers related to the account signed in on the device
  - IP address (which may be used for approximate location)
  - App usage: app launches, taps, video views and other interactions
  - Diagnostics: app and SDK performance (launch time, hang rate, energy use, etc.)
- The app does not pass gestures, contacts, phone numbers, message text or camera images to the ad components.
- You can reset or delete the advertising ID in your phone's settings. Transmission is encrypted with TLS (per Google's public documentation).
- Consent: where required by law, UMP shows a consent form for ad privacy. Where it applies, you can change your choice in the app's "Privacy options" setting, and the app follows the choice made in the form.
- How the advertising provider uses information is governed by Google's privacy policy (https://policies.google.com/privacy).

## 5. Purchases (Google Play Billing)

- The ad-removal product ("Keep it on without ads", a one-time purchase that removes ads and the 3-day limit) is processed by Google Play. Your payment method and Google account details are handled by Google Play and are not visible to the app or to us.
- The app stores on your phone only whether you bought it and when it was last checked. Reinstalling with the same Google account restores the purchase.
- The app communicates with Google Play through the Play Billing component to check the purchase status.

## 6. Third-party provision, outsourcing and transfer abroad

- We do not provide your information to third parties or outsource its processing (we receive none).
- Google's components in sections 4 and 5 may process information outside the Republic of Korea (for example, in the United States).
- Information that Google Play collects when you install and use the app from Google Play (install statistics, crash statistics from devices that opted in to sharing, etc.) is governed by Google Play's policies.

## 7. Retention and deletion

- Information stored on your phone is removed for a gesture when you delete that gesture in the app, and all of the app's stored information is removed when you uninstall the app or clear its data.
- We keep no information about you on any server, so there is nothing for us to retain or delete.
- Retention and deletion of information the ad components sent to Google follow Google's policies. You can reset or delete the advertising ID in your phone's settings (the menu location varies by manufacturer and Android version).

## 8. Your rights and how to use them

- You can review (gesture list and details), edit and delete your information directly in the app, and uninstalling the app removes everything.
- You can change or withdraw the camera, notification and display-over-other-apps permissions in your phone's settings at any time.
- For questions about this policy or about how information is handled, or to request access, correction, deletion or restriction, email support@un-veil.co.kr. We will respond within the period required by law. If we hold no information about you, we will tell you so.

## 9. Children

The app is intended for users aged 18 and over, and we do not knowingly collect personal information from children under 14.

## 10. Security measures

- Stored information is kept in the app's private internal storage and excluded from cloud backup and device transfer.
- Camera images are processed only in your phone's memory and are never saved or sent.
- The only external communication of the app is by the ad and billing components.
- The app's code has no feature that sends your information to our servers.

## 11. Cookies and similar technologies

The app does not use cookies.

## 12. Privacy officer

- Name: un-veil
- Contact: support@un-veil.co.kr

## 13. Remedies for infringement

For reports and consultations about privacy infringement, you can contact the following (numbers and addresses are standard information as of the effective date and may change).
- Personal Information Infringement Report Center: privacy.kisa.or.kr / 118
- Personal Information Dispute Mediation Committee: www.kopico.go.kr / 1833-6972
- Supreme Prosecutors' Office Cyber Investigation Division: www.spo.go.kr / 1301
- National Police Agency Cyber Bureau: ecrm.police.go.kr / 182

## 14. Changes to this policy

When we change this policy, we will announce it on this page from 7 days before it takes effect (30 days for material changes). The change history is kept at the bottom of this page.

Change history: 2026-11-04 First effective version
