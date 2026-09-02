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
| Rooms, tasks, completion history, settings | Normally **never leaves your device** (see below for the "Family Sharing" case). |
| Name, email, phone number, or any personal identifier | **Never collected.** There is no account and no sign-up. |
| Advertising and tracking | **None.** No ad SDK and no analytics SDK is embedded. |
| What does leave the device | **Nothing goes to the developer** — there is no server. If you use the optional "Family Sharing" feature, the data you share syncs with your invitees through your own iCloud account (Section 4.3). |
| "Family Sharing" (optional) | If you use it, the data in the household you share syncs with your invitees through your own iCloud account. **The developer cannot access it** (Section 4.3). |
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

### 4.3 Using "Family Sharing" (かぞくで共有)

The App includes an optional feature called **"Family Sharing"** that lets you share the state of your rooms and tasks with family members or housemates. Nothing is shared unless you deliberately create or join a "household" — the feature does nothing on its own.

- **What syncs, and how**: When you turn on Family Sharing, the rooms, tasks, completion history, and cleaning-supply notes in the household you share — along with each member's nickname (a self-chosen in-app display name, not necessarily your real name) — sync to the devices of the people you invite, or the person who invited you, **through your own iCloud account, using Apple's CloudKit.**
- **The developer still cannot access it**: This sync happens entirely between your and your household members' iCloud accounts and never passes through a developer server — as described in Section 4.1, there isn't one. The App's "we don't collect it" policy does not change when you use this feature. What changes is simply that your data now also travels, through your own iCloud, to people you chose to invite.
- **If sharing ends**: If you leave a household, or the owner stops sharing it, syncing stops from that point. The device where sharing ended deletes its local copy of the shared data. Whatever data you had on your device before joining stays there and reappears once sharing ends. If you are the household owner, your own data in iCloud is unaffected by a member leaving or by you turning sharing off.
- **"Done for you" notifications**: When a household member completes a chore assigned to you, their device writes a short notification text (their nickname, the chore name, and the household name) into **a notification area inside your own iCloud**, and Apple's push notification system delivers it to your device. This text never passes through a developer server and the developer cannot read it. You can turn these notifications off at any time in Settings.
- **If you don't use it**: Unless you use Family Sharing, the App works exactly as described in Sections 4, 4.1, and 4.2 above — entirely on-device.
- **About iCloud**: Family Sharing runs on top of Apple's iCloud (CloudKit). How Apple itself handles data inside iCloud is governed by [Apple's own Privacy Policy](https://www.apple.com/legal/privacy/).

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
| 1.1 | 2026-08-25 | Added explanation of the "Family Sharing" feature (Section 4.3; adjusted Section 0 summary) |
| 1.2 | 2026-09-02 | Added explanation of "Done for you" notifications (Section 4.3) |

## Related documents

- [プライバシーポリシー（日本語・正文）](../privacy/)
- [利用規約 / Terms of Service (Japanese)](../terms/)
- [特定商取引法に基づく表記 (Japanese)](../tokushoho/)
