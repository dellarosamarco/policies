# Merge Tycoon – Privacy Policy

**Effective date:** November 19, 2026
**App:** Merge Tycoon (Android package `com.MaarcoDev.mergetycoon`)
**Contact:** [hoenngames@gmail.com](mailto:hoenngames@gmail.com)

This Privacy Policy explains what information Merge Tycoon ("the app", "we") processes, why, and the choices you have. Merge Tycoon **contains no advertising**, does not ask for your name, e‑mail, phone number or contacts, and **does not sell personal data**.

---

## 1. Information stored on your device

Your game progress (coins, items, upgrades, statistics), your settings (sound, music, vibration, notifications, language) and the identifiers of completed in‑app purchases (used to avoid delivering the same purchase twice) are saved locally on your device. You can delete them at any time with **Settings → Delete all my data** or by uninstalling the app.

## 2. Cloud save (Google Firebase)

To back up your progress and let you restore it, the app uses Google Firebase:

| Service | Data | Purpose |
|---|---|---|
| **Firebase Authentication (anonymous)** | A random user identifier ("Player ID"). No name, e‑mail or phone number. | Identify your cloud save. |
| **Cloud Firestore** | A copy of your game progress, the date of the last backup, total coins earned, number of ascensions, device platform (e.g. "android"). | Cloud backup / restore of your progress. |
| **Transfer codes** (optional) | A copy of your game progress linked to a random 10‑character code. | Move your progress to another device. Codes expire and are deleted after 24 hours. |

Automatic cloud backup can be turned off in **Settings → Cloud save**. Each player can only read and write their own save (enforced by server‑side security rules).

## 3. Analytics and crash reports

| Service | Data | Purpose |
|---|---|---|
| **Firebase Analytics** | App‑instance identifier, in‑game events (e.g. tutorial completed, new era reached, ascension, daily reward claimed, purchase completed), device model, OS version, language, app version, approximate location (country/region derived from the IP address). **The advertising ID is not collected.** | Understand how the game is played and improve it. |
| **Firebase Crashlytics** | Crash and error reports (stack traces), device model, OS version, app version, a Crashlytics installation identifier. | Find and fix bugs and crashes. |
| **PostHog** (usage analytics) | A random device identifier, game events, device and app information, IP address (see below). **No location is derived from the IP address.** | Understand how the game is played, measure retention, find where players get stuck or stop playing, and fix problems. |

**Usage analytics (PostHog).** The app sends pseudonymous usage events to PostHog (PostHog, Inc., USA):

- **Random device identifier** created by the PostHog SDK. It is not the advertising ID and is not linked to your name, e‑mail or Player ID.
- **Game events:** app installed, updated, opened and sent to the background; screens and sheets opened (shop, upgrades, missions, collection, ascension, settings); merges (counted in batches); tutorial steps; new eras reached and new items discovered; ascensions (stars earned, number of ascensions, highest item tier); features used; achievements; daily rewards; shop and offer views; completed purchases and subscriptions (product ID, price, currency); rating prompts shown; notifications opened; and a few game statistics (best era, number of ascensions, whether you are a premium/VIP player).
- **Device and app information:** device manufacturer and model, OS and version, app version and build, language/locale, screen size, time zone and network type.
- **IP address:** PostHog receives it as part of the connection, but the app asks PostHog **not to derive any location** from it.

PostHog is configured with **no session replay** and no recording of the screen. No name, e‑mail, advertising ID or free text is sent. Events are linked only to the random device identifier: **no user profile** is created and the Player ID is not sent to PostHog.

This data is not used for advertising, is not sold and is not linked to your real identity. See [Firebase privacy and security](https://firebase.google.com/support/privacy) and the [PostHog privacy policy](https://posthog.com/privacy).

## 4. In‑app purchases

Purchases are processed entirely by **Google Play**. We never receive your payment details. The app only receives a purchase confirmation (product and order/purchase identifier) to deliver the item.

## 5. Notifications

If you allow notifications, the app schedules **local reminders** on your device (for example "your vault is full" or "daily reward ready"). No push server is used. You can disable them in **Settings → Notifications** or in your device settings.

## 6. Legal bases (EEA/UK users)

We process data to provide the service you request (game progress, cloud save, purchases – *performance of a contract*), and for analytics (Firebase and PostHog) and crash reporting to keep the game working and improve it (*legitimate interests*, Art. 6(1)(f) GDPR). You have the right to object to this processing at any time by contacting us.

## 7. Sharing

We do not sell or rent your data. Data is processed on our behalf only by the following service providers, under their terms:

- **Google LLC** (USA) — Firebase and Google Play — [policies.google.com/privacy](https://policies.google.com/privacy)
- **PostHog, Inc.** (USA) — product analytics — [posthog.com/privacy](https://posthog.com/privacy)

Data may be processed on servers outside your country, including in the United States, with appropriate safeguards (e.g. Standard Contractual Clauses). In particular, PostHog stores analytics data in its US cloud; these transfers are protected by the European Commission's Standard Contractual Clauses (included in PostHog's Data Processing Agreement) and, where applicable, the EU‑U.S. Data Privacy Framework.

## 8. Security

All data sent between the app and Firebase or PostHog is **encrypted in transit (HTTPS/TLS)**. Data stored by Firebase is encrypted at rest by Google. Access to cloud saves is restricted to the owner of the anonymous account.

## 9. Retention

- **Local data:** until you delete it in the app or uninstall the app.
- **Cloud save and anonymous account:** until you delete them (see section 10).
- **Transfer codes:** automatically deleted after 24 hours.
- **Analytics:** user‑level data is kept for up to 14 months; **Crashlytics** reports for up to 90 days.
- **PostHog usage analytics:** events are kept for up to 12 months and then deleted automatically (or kept only in anonymised, aggregated form).

## 10. Your choices and data deletion

- **In the app:** *Settings → Delete all my data* immediately deletes your local progress, your cloud save, your anonymous account and resets the analytics identifier.
- **Usage analytics (PostHog):** the app currently has **no in‑app switch** to turn usage analytics off. *Settings → Delete all my data*, clearing the app data or reinstalling the app resets the random PostHog identifier, so new events are no longer linked to earlier ones; uninstalling the app stops all collection. To object to analytics or ask for deletion of your analytics data, write to [hoenngames@gmail.com](mailto:hoenngames@gmail.com).
- **By e‑mail:** write to [hoenngames@gmail.com](mailto:hoenngames@gmail.com) with the subject "Delete my data – Merge Tycoon", including the **Player ID** shown in *Settings → Cloud save*. We delete the data within 30 days.

Full instructions: [Merge Tycoon – Account and data deletion](https://github.com/dellarosamarco/policies/blob/main/merge-tycoon-account-deletion.md).

Depending on where you live (e.g. GDPR in the EU/UK, CCPA/CPRA in California), you may have the right to access, correct, delete or port your data and to object to or restrict processing. Contact us to exercise them; you may also lodge a complaint with your local data protection authority.

## 11. Children

Merge Tycoon is a general‑audience game and is **not directed to children under 13**. We do not knowingly collect personal information from children under 13. Analytics data is pseudonymous and is never used for advertising or profiling. If you believe a child has provided us with personal information, contact us and we will delete it.

## 12. Changes to this policy

We may update this policy from time to time. The new version will be published at this address with an updated effective date. Significant changes will be announced in the app.

## 13. Contact

For any question about this policy or your data: **[hoenngames@gmail.com](mailto:hoenngames@gmail.com)**
