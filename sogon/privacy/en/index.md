---
title: "Sogon Privacy Policy"
permalink: /sogon/privacy/en/
lang: en
---

[한국어](/unveil-privacy/sogon/privacy/)

# Sogon Privacy Policy

Effective date: 2026-11-14  
Operator: un-veil ("we")  
Contact: support@un-veil.co.kr

> **Notice of this update (effective 2026-11-14)**  
> This policy takes effect on 2026-11-14. What changed from the policy effective 2026-11-13 is listed below.
>
> - **Billing library diagnostics** (applies to all versions from 0.5.0): we now state in sections 3-2 and 5 that the Google Play Billing Library, which checks whether you purchased, may send technical diagnostic information to Google. This is not new behavior; it has been there since 0.5.0, and this update only completes the description.
> - This update only completes the description in this policy; it does not change what information the app handles or how. What the policy effective 2026-11-13 added (ads with Google AdMob, a one-time in-app purchase to remove ads with Google Play, and "text in photos" search, in version 0.5.0 or later) still applies, and the full list of changes is in the change history at the bottom.

We provide the Android app "Sogon" (the "app"). This policy explains what information the app handles, where, and what rights you have.

## 1. At a glance

- The app has no sign-up or login and **we do not operate any server for it.**
- Your photos, videos, search queries, the analysis results of your photos, the capture locations recorded in your photos and, if you turn it on, **the text in your photos** are **processed and stored on your device and are not sent to any server of ours.**
- "Search by text in photos" is **off by default** and works only after you turn it on in Settings. Turning it off deletes all the text the app has read.
- To show ads, **the Google ad SDK included in the app processes information such as the advertising ID and IP address and sends it to Google** (section 3-1). This information does not pass through any server of ours, and we do not receive it per user. Ads are requested only in a non-personalized way (not based on your interests).
- Removing ads is a one-time purchase through Google Play. The app does not receive your payment method or card details; it only checks with Google Play whether you have purchased. When it does, the Google Play Billing Library included in the app may send technical diagnostic information to Google (section 3-2).

## 2. What the app handles and how

| Information | Purpose | Where it is processed and stored | Sent to our servers |
|---|---|---|---|
| Photos and videos (files and details your device provides, such as capture time, file name, album name) | Show the library, search, analysis | On your device. The app only reads them, and deletes only when you choose to, through the system | No |
| Analysis results (numeric search values, "sea/food"-type content suggestions, analysis progress) | Search by sentence or content, similar photos | App-private storage on your device | No |
| Text in your photos (only if you turn on "Search by text in photos" in Settings; search text) | Find photos that contain a lot of text, such as receipts, menus, screenshots and signs, by that text | The app reads your photos on the device and stores the resulting text in the app-private database on your device. It mainly reads photos that look like they contain a lot of text. Text in photos may include personal information such as names, phone numbers and addresses, and may be stored as it is. However, **digits that look like a Korean resident registration number or a payment card number are deleted before saving** (this also applies when such a number is read split across several lines, if the format matches; other numbers, such as bank account numbers, are not filtered out). The app does not sort or analyze the text by type and does not use it for anything other than search | No |
| Capture location stored in your photos (only if you allow the "photo location" permission) | Search by place name such as "Incheon" | Converted on the device into a neighborhood-level ID using an offline place-name dictionary bundled in the app; **the coordinates are discarded** (not stored, logged or sent). The app does not read your device's current location | No |
| Search queries and recent searches | Search, show recent searches | On your device; you can clear them in Settings | No |
| Favorites and display settings | App features | On your device | No |
| Notifications | Show analysis progress (if you allow notifications) | On your device | No |
| Numbers that decide how often to show ads and purchase prompts (number of app launches, days of use, number of successful searches, analysis progress ratio, number and time of prompts shown) | Show ads and purchase prompts in moderation | App-private storage on your device. Only numbers are stored; they do not contain the content of photos or searches | No |
| Whether you have purchased "remove ads" | Do not show ads to those who purchased | Google Play handles purchase verification, and the app stores only the result (purchased or not) on your device. The app does not receive your payment method or card details | No |
| Billing library diagnostics (technical information such as the results of billing operations and connection problems; the exact items are decided by Google) | Performance improvement and error handling of the Google Play Billing Library (the purpose Google states) | The Google Play Billing Library included in the app **sends it directly from your device to Google** for processing (sections 3-2 and 5). It can happen while you use the app, whether or not you purchased "remove ads". We do not receive or keep this information and cannot see its contents | No (sent to Google) |
| Ad-related information (identifiers such as the advertising ID, approximate location estimated from the IP address, app interactions such as ad impressions and taps, app and ad SDK performance diagnostics) | Show ads, analytics, fraud prevention | The Google ad SDK included in the app **sends it directly from your device to Google** for processing (sections 3-1 and 5). We do not receive or keep this information per user | No (sent to Google) |
| Ad consent choice (only in regions such as the European Economic Area where a consent message is shown by law) | Request ads according to your choice | On your device. While showing the consent message, the Google consent management SDK may communicate with Google (section 3-1) | No |

App data (including text read from photos) is excluded from Android automatic (cloud) backup (`allowBackup=false`). If you reinstall the app, whether you purchased "remove ads" is checked again with Google Play.

## 3. When the app uses the internet

The app uses the internet permission and the network-state permission. It uses the internet in four ways.

- **Showing ads**: before you purchase "remove ads", when ads are requested and shown, the Google ad SDK communicates with Google over the internet. The information processed is described in section 3-1.
- **Purchase and verification**: Google Play billing is used to buy "remove ads" and to check whether you purchased. Google Play handles the payment, and we do not receive your payment method or card details. The billing library used for this may send diagnostic information to Google (section 3-2).
- **Model download**: in versions that provide features needing the search model and the text-reading model (about 650 MB in total), the models are **downloaded separately by Google Play** after install and delivered to the app (over Wi-Fi by default). This is a Google Play service; we do not receive your information, and your photos and text are not used in this process. After the models are downloaded, you can search without an internet connection.
- **Ad consent message**: in regions where a consent message is required by law, the Google consent management SDK may communicate with Google to check your consent status.

We do not operate any server, and the app code written by us has no function that sends your photos, videos, search queries, analysis results, text read from photos or capture locations. The four uses above are all communications made by Google SDKs or services.

### 3-1. Ads and the ad SDK

- Sogon shows ads until you purchase "remove ads". The ads are native ads (ads shaped to fit the app screen) provided by Google AdMob. When ads are requested and shown, the Google ad SDK included in the app sends the information below directly from your device to Google and processes it. We do not receive or keep this information per user; we can see only aggregated statistics, such as impressions and revenue, that AdMob provides.

| Item | Purpose | Recipient and country |
|---|---|---|
| IP address (may be used to estimate approximate location) | Ads, analytics, fraud prevention | Google LLC · United States and other countries |
| Ad and app interactions (app launches, ad impressions, taps, etc.) | Same | Same |
| Diagnostics (app and SDK performance, run time, etc.) | Same | Same |
| Device and account identifiers (advertising ID, app set ID, etc.) | Same | Same |

- Ads are requested **only in a non-personalized way (not based on your interests)**. Even non-personalized ads may use the advertising ID for frequency capping and aggregated reporting.
- When the app code written by us requests an ad, it includes only the ad unit identifier and the ad format (native). There is no code that puts your photos, videos, search queries, text read from photos, album names or capture locations into an ad request, or that adds extra information such as keywords or content URLs. However, the information the ad SDK collects by itself is as listed in the table above, and how the SDK behaves internally is decided by Google.
- You can reset or delete the advertising ID in your device settings (menu names differ by device; it is usually under "Ads" in the Google or Privacy section of Settings). Even if you delete the advertising ID, other information such as the IP address may still be sent.
- In the European Economic Area and some other regions, a consent message (Google consent management SDK) may be shown as required by law, and your choice is stored on your device. In regions where the message is shown, you can change your choice again in the app settings.
- For how Google uses this information, see Google's explanation (https://policies.google.com/technologies/partner-sites) and the Google Privacy Policy (https://policies.google.com/privacy).

### 3-2. Billing library (Google Play Billing)

- The app uses the Google Play Billing Library, provided by Google, to buy "remove ads" and to check whether you purchased. In versions that include this feature, the library runs together with the app whether or not you purchased "remove ads".
- Google states that the library records information such as the results of billing operations (success or failure) and connection problems, and uses it to improve the library's performance and handle errors. While you use the app, the library may send technical diagnostic information directly from your device to Google over the internet. Which items it contains is decided by Google, and we cannot receive or see the contents.
- The app code written by us uses this library only to look up the remove-ads product, open the purchase screen and check whether you purchased; it is built not to pass your photos, videos, search queries, text read from photos or capture locations to it.
- There is no setting in the app that turns off only this transmission. If you do not use the app or you uninstall it, nothing is sent. For how Google uses this information, see the Google Privacy Policy (https://policies.google.com/privacy).

## 4. Retention and deletion

- Information the app stores on your device (analysis results, search history, favorites, settings, the numbers used for ad and purchase prompts, whether you purchased, your ad consent choice, etc.) is deleted when you uninstall the app or clear its data. "Clear history" in Settings removes only your search history.
- **Text read from your photos** is deleted all at once when you turn off "Search by text in photos" in Settings (turning it on again starts reading from scratch). The text of a photo is also deleted when that photo is deleted, removed from the app's list, or edited. It is deleted too when you uninstall the app or clear its data.
- Information stored on your device is deleted by you using the methods above; there is no information that we must retain by law.
- How long Google keeps the information the ad SDK and the billing library process at Google follows Google's policies. Purchase records are kept by Google Play.
- We do not keep personal information on any server, so we have no separate retention or deletion procedure.
- Photos you ask the app to delete are handled under Android's system trash rules.

## 5. Sharing, processors and international transfers

- We do not keep your personal information on any server of ours, and we do not directly provide it to third parties or hand its processing over to others.
- However, to show ads, the Google ad SDK included in the app sends the information in section 3-1 to Google as described below (an international transfer). The information is sent directly from your device to Google; we do not receive it and pass it on. The diagnostic information from the billing library is described in the second table below.

| Item | Details |
|---|---|
| Recipient | Google LLC (see the Google Privacy Policy at https://policies.google.com/privacy for how to contact Google) |
| Country | United States and other countries where Google operates its services |
| Information transferred | IP address, ad and app interactions, diagnostics, identifiers such as the advertising ID (table in section 3-1) |
| When and how | Each time an ad is requested and shown, sent directly from your device over the internet. Google states that the ad SDK's transmissions are encrypted with TLS |
| Purpose | Showing ads, analytics, fraud prevention |
| Retention | Follows Google's policies |
| How to refuse and effect | You can reset or delete the advertising ID in your device settings, but the IP address and other information may still be sent. If you purchase "remove ads", the app does not show ads. If you do not purchase it and do not want the transfer above, there is no way other than not using the app |

**Billing library diagnostics (section 3-2)**

| Item | Details |
|---|---|
| Recipient | Google LLC (https://policies.google.com/privacy) |
| Country | United States and other countries where Google operates its services |
| Information transferred | Technical diagnostic information such as the results of billing operations and connection problems (the exact items are decided by Google and we cannot see them) |
| When and how | While you use the app, sent directly from your device over the internet. It can happen whether or not you purchased "remove ads" |
| Purpose | The purpose Google states: performance improvement and error handling of the billing library |
| Retention | Follows Google's policies |
| How to refuse and effect | There is no setting in the app that turns off only this transmission. Purchasing "remove ads" may not stop it. If you do not want this transmission, there is no way other than not using the app or uninstalling it |

- Google Play (model delivery and purchase verification) is a direct relationship between you and Google, and we do not receive your information through it. However, the diagnostic information that the billing library included in the app sends to Google is described in the second table above.

## 6. Your rights

- Information stored only on your device can be removed by you in the app (clear history; turn off "Search by text in photos" to delete the text the app has read), by clearing app data, or by uninstalling.
- You can change or withdraw photo and location permissions at any time in your device settings. Withdrawing location permission does not remove place identifiers already stored; clearing app data does.
- Information that Google processes through the ad SDK can be managed in your device's ad settings (reset or delete the advertising ID) and in the ad settings of your Google Account. Billing library diagnostics cannot be turned off or deleted in the app; you can direct questions and requests about information Google processes to Google as described in the Google Privacy Policy (https://policies.google.com/privacy).
- Requests to access, correct, delete or restrict processing are received at the contact in section 10 (support@un-veil.co.kr), handled by us directly, and answered within the period required by law. Because we keep no personal information on any server, we will tell you if we hold no information about you.
- The legal guardian of a child under 14 can make the same requests in the same way.

## 7. Children

The app is not directed to children under 14 and we do not knowingly collect personal information from children under 14. If we learn that a child under 14 is using the app, we accept a legal guardian's request at the contact in section 10; we hold no information about the child.

## 8. Security

- Information is processed and stored on your device by design, and we operate no server.
- Requested permissions are limited to what is needed: reading photos/videos, reading photo locations, notifications, the analysis task, network access for ads, purchase verification and model download, the advertising ID (for advertising), and Google Play billing.
- App data is excluded from cloud backup.
- Digits that look like a resident registration number or a payment card number are deleted before saving, and text read from photos is kept only in the app-private storage on your device. That storage is not separately encrypted and relies on your device's lock screen, encryption and app isolation.
- The ads and billing features are separated into their own module so that the code handling photos, search queries and text read from photos does not use that module and the module does not reference that code (checked automatically at build time). However, the ad SDK and the billing library run in the same process as the app, so the information they collect follows sections 3-1 and 3-2 and Google's explanations.

## 9. Cookies and similar technologies

- The app does not use cookies.
- However, when requesting an ad, the ad SDK automatically reads and uses your device's advertising ID (section 3-1). This happens while ads are shown, before you purchase "remove ads".
- You can refuse this by resetting or deleting the advertising ID in your device settings. If you purchase "remove ads", the app does not show ads.

## 10. Privacy officer

- Name: un-veil (the operator; an individual developer who handles this personally)
- Contact: support@un-veil.co.kr
- Requests to access, correct, delete or restrict processing, and other privacy inquiries, are received at the contact above.

## 11. Remedies for privacy infringement

You can report or seek advice about privacy infringement from the following organizations (numbers and addresses are standard information as of the effective date and may change). These organizations are in Korea and provide their services in Korean.
- Personal Information Infringement Report Center: privacy.kisa.or.kr / 118 (no area code)
- Personal Information Dispute Mediation Committee: www.kopico.go.kr / 1833-6972
- Supreme Prosecutors' Office, Cyber Investigation Division: www.spo.go.kr / 1301 (no area code)
- Korean National Police Agency, Cyber Bureau: ecrm.police.go.kr / 182 (no area code)

## 12. Changes

We will announce changes on this page before they take effect. The history is kept at the bottom of this page, and we provide the previous effective version on request.

Change history:
- 2026-11-01 First version
- 2026-11-13 Added ads (Google AdMob), a one-time purchase to remove ads (Google Play) and text-in-photos search (from version 0.5.0). Added to the information table: ad-related information, purchase status, text read from photos, numbers used for ad prompts and the ad consent choice. Added internet use (section 3) and the ad SDK (section 3-1); rewrote the third-party sharing and processor section as international transfers (section 5); expanded retention and deletion (section 4), rights (section 6), security (section 8), automatic collection technologies including the advertising ID (section 9) and the privacy officer (section 10); added the remedies section (section 11, previously only in the Korean version); corrected the model size to about 650 MB
- 2026-11-14 Now describe the diagnostic information that the Google Play Billing Library, present since 0.5.0, may send to Google (the app's behavior did not change). Updated sections 1, 2 (new row), 3, 3-2 (new), 4, 5 (billing table added), 6 and 8, and the notice
