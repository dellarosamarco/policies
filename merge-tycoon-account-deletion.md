# Merge Tycoon – Account and Data Deletion

**App:** Merge Tycoon (Android package `com.MaarcoDev.mergetycoon`)
**Developer contact:** [hoenngames@gmail.com](mailto:hoenngames@gmail.com)

Merge Tycoon does not require registration. When cloud save is available, the app creates an **anonymous account** (a random Player ID, with no name, e‑mail or phone number) to store a backup of your game progress. You can delete this account and all associated data at any time, in one of two ways.

---

## Option 1 – Delete in the app (immediate)

1. Open **Merge Tycoon**.
2. Tap the **⚙️ Settings** icon (top right).
3. Scroll to the bottom and tap **Delete all my data**.
4. Confirm.

This immediately and permanently deletes:

- your game progress saved on the device (coins, items, upgrades, statistics, collection);
- your cloud save stored in Google Firebase (Cloud Firestore);
- your anonymous account (Firebase Authentication);
- the analytics identifier associated with the app on your device (it is reset).

The game then starts again from the beginning.

## Option 2 – Request deletion by e‑mail

If you no longer have the app installed or cannot access it:

1. Send an e‑mail to **[hoenngames@gmail.com](mailto:hoenngames@gmail.com)**.
2. Subject: **Delete my data – Merge Tycoon**.
3. Include your **Player ID** if you can (shown in the app under *Settings → Cloud save*). Without it we will ask for details (approximate install date, device model, progress) to locate your data.

We confirm and complete the deletion **within 30 days**.

## What is deleted and what is kept

| Data | Deleted | Notes |
|---|---|---|
| Game progress on the device | ✅ Immediately | Also removed when you uninstall the app. |
| Cloud save (Cloud Firestore) | ✅ Immediately (in‑app) / within 30 days (e‑mail) | |
| Anonymous account (Firebase Authentication) | ✅ Immediately (in‑app) / within 30 days (e‑mail) | |
| Transfer codes | ✅ | Automatically deleted after 24 hours anyway. |
| Analytics data (Firebase Analytics) | ✅ Identifier reset; historical aggregated, pseudonymous events expire within 14 months | Not linked to your identity. |
| Crash reports (Firebase Crashlytics) | Expire automatically within 90 days | Contain no personal data. |
| Purchase records | ❌ Kept by Google Play | Required by Google Play for billing, refunds and tax purposes; managed by Google. |

> Note: deleting your data does not cancel an active **Tycoon Club** subscription. Cancel it in the Google Play Store app: *Profile → Payments & subscriptions → Subscriptions*.

See also the [Merge Tycoon Privacy Policy](https://github.com/dellarosamarco/policies/blob/main/merge-tycoon-privacy-policy.md).
