---
layout: default
lang: en
title: Privacy Policy (English)
description: Privacy policy of Soujidoki (English version)
permalink: /privacy-en/
nav: privacy-en
root: "../"
# source: docs/legal/privacy-policy-en.md  ← 原典。本文を直すときは原典と両方を更新すること（この行はページには出力されません）
---

Effective date: August 21, 2026

This is the English version of the privacy policy of Soujidoki, provided for reference. **In case of any discrepancy, the [Japanese version](../privacy/) prevails.** The App is distributed on the Japanese App Store only, and this Policy is written against Japanese law (APPI).

## 0. Summary

| Question | Soujidoki's answer |
|---|---|
| Rooms, tasks, completion history, settings | **Never leaves your device.** |
| Name, email, phone number, or any personal identifier | **Never collected.** There is no account and no sign-up. |
| Advertising and tracking | **None.** No ad SDK and no analytics SDK is embedded. |
| What does leave the device | **Nothing.** The app runs entirely on-device; there is no server. |
| Data export (JSON) | A local, user-initiated action. The exported file is **never sent to the developer.** |
| Sharing with third parties | **None** — there is nothing to share. |

---

## 1. Scope

This Privacy Policy ("Policy") describes how information is handled in the iOS application **Soujidoki** (Bundle ID `jp.soujidoki.app`) ("the App"). It does not apply to any other service.

The App is distributed on the **Japanese App Store only**, and this Policy is written against Japanese law (the Act on the Protection of Personal Information, APPI).

## 2. Provider

| Item | Detail |
|---|---|
| Provider | **m8a** (trade name) |
| Type | Individual developer (Apple Developer Program, individual account) |
| Contact | **m8a.dev@gmail.com** |
| Legal name / postal address / phone | Not published here. See the Japanese ["Act on Specified Commercial Transactions" disclosure page](../tokushoho/) — **disclosed without undue delay upon request** sent to the contact address above. |

## 3. Information we do NOT collect

The App does **not** collect any of the following:

- Name, email address, phone number, postal address, or date of birth
- Account or login credentials (the App has no account system)
- Location, contacts, calendar, microphone, camera, or photo library contents
- Advertising identifiers (IDFA) or any other advertising/measurement identifier
- Any information used to track you across apps or websites

The App **does not present the App Tracking Transparency prompt**, because it performs no tracking. **No third-party advertising or analytics SDK is embedded, and the App has no server of any kind.**

## 4. What the App stores — on your device only

The App stores the following, created by your own use of the App, in an on-device database (SwiftData):

| Data | What it is |
|---|---|
| Rooms | The rooms you register, with their names and types |
| Tasks | Cleaning tasks per room (frequency, importance, notes, last-done date) |
| Completion history | A log of when you marked tasks done (used for stats and streaks) |
| Settings | In-app settings such as notification time |

**All of this stays on your iPhone.** Nothing is transmitted to the developer or to any third party, because **the App has no server to send it to.** The developer cannot see which rooms or tasks you created, or when you cleaned.

If you delete the App, this on-device data is erased by iOS. The App has no cloud backup, so if you want to keep a copy first, use the export feature described below.

## 5. Data export (JSON)

The App lets you export your rooms, tasks, completion history, and settings as a single JSON file from the Settings screen.

- This is a **local, on-device operation.** What you do with the exported file (save it, share it, delete it) is entirely up to you.
- **The developer never receives or sees this file.** It is handed to whatever destination you choose via iOS's standard share sheet.
- Export is optional and not required to use the App.

## 6. Payments

- All purchases of "Soujidoki Pro" (subscription) are processed **entirely by Apple (the App Store).** The developer never receives your card number, name, or billing address.
- Through Apple's StoreKit, the App checks only whether an entitlement is active, and stores that state on-device. It is not transmitted anywhere.
- Subscription management, cancellation, and refunds are handled by Apple. See the [Terms of Service](../terms/) (Japanese) for details.

## 7. Statistics provided by Apple (for reference)

The developer views the **aggregated, anonymous statistics** that App Store Connect provides by default (downloads, retention, crash counts) to any developer on the platform. These are Apple's own aggregates and cannot identify an individual user; they are not something the App itself collects. No additional analytics tooling has been added.

## 8. Notifications

With your permission, the App sends **local notifications only** (generated entirely on your device):

- A daily morning reminder suggesting today's cleaning tasks (time is configurable)
- A reminder the day before your annual-plan free trial ends, so billing never surprises you

No push notification server is involved. You can turn notifications off at any time in iOS Settings.

## 9. Purpose, sharing, retention

- **Purpose**: on-device data (Section 4) is used solely to provide the App's own features (today's suggestions, statistics, notifications), on your device.
- **Sharing**: the developer does **not** sell, rent, or otherwise share data with third parties — there is no data to share.
- **Retention**: on-device data is erased when you delete the App.
- **International transfer**: none — nothing is transmitted off the device.
- **Distribution territory**: Japan-only at launch. If distribution expands, this Policy will be revised accordingly and notice given per Section 13.

## 10. Children

- The App is not directed primarily at children and is not distributed in the Kids Category.
- Because the App collects no personal information whatsoever, it does not knowingly collect personal information from children.
- If a child uses the App on a device managed by a parent or guardian, we ask that the guardian review any purchase (via Family Sharing / Ask to Buy).
- Contact us (Section 12) with any concerns.

## 11. Security and your rights

- On-device data is protected by the iOS sandbox and device encryption. **The developer cannot access data on your device.**
- **Access, correction, deletion**: because the developer holds none of your data, there is nothing on our side to disclose, correct, or delete. You can view, change, or delete your own data at any time directly in the App, or by deleting the App.
- For anything else, including a request to disclose the provider's legal identity under Japanese law, contact us (Section 12).

## 12. Contact

**m8a.dev@gmail.com**

Replies may take a few days (the App is run by one person). For billing, refunds, and cancellations, Apple (App Store Support) is the point of contact — see the [Terms of Service](../terms/).

## 13. Changes to this Policy

We may update this Policy as the law or the App changes. For significant changes we will give notice in the App or in the App Store description. The updated Policy takes effect when posted on this page.

## 14. Revision history

| Version | Date | Change |
|---|---|---|
| 1.0 | 2026-08-21 | First published version |

## Related documents

- [プライバシーポリシー（日本語・正文）](../privacy/)
- [利用規約 / Terms of Service (Japanese)](../terms/)
- [特定商取引法に基づく表記 (Japanese)](../tokushoho/)
