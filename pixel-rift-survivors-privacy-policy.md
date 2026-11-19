# Privacy Policy for Pixel Rift: Survivors

**Last updated: November 19, 2026**

This Privacy Policy explains how **Pixel Rift: Survivors** ("Pixel Rift", "the Game", "we", "our") collects, uses, stores, and shares information when you play the game.

Pixel Rift: Survivors is a pixel-art roguelite action game for Android. The game works offline; online features such as cloud saves, leaderboards, purchases, advertising, analytics, and crash reporting use third-party services.

## Data Controller

- **Developer:** Marco Della Rosa
- **Privacy contact:** hoenngames@gmail.com
- **Country:** Italy

## Information We Process

### 1. Game progress

The Game stores progress on your device, such as coins, gems, permanent upgrades, unlocked heroes and maps, records, daily rewards, missions, nickname, and settings.

When online, this progress is also saved in **Google Firebase Cloud Firestore**, linked to an **anonymous Firebase account identifier** (UID). We do not ask for your name, e-mail address, or password.

### 2. Leaderboard data

If you take part in leaderboards, the following information is visible to other players:

- your chosen nickname;
- survival time, kills, hero, map, and difficulty tier of your runs.

Choose a nickname that does not reveal personal information.

### 3. Purchase data

The Game offers in-app purchases and subscriptions through **Google Play Billing**. To validate purchases and prevent fraud, we process:

- product identifier;
- purchase token, order status, and subscription expiry.

Purchase tokens are verified server-side through a Firebase Cloud Function. Payment details such as card numbers are handled by Google and are never received by us.

### 4. Analytics and diagnostics

We use **Firebase Analytics**, **Firebase Crashlytics**, and **Firebase Remote Config** to understand how the Game is played, fix crashes, and tune game balance. These services may process:

- in-game events and interactions;
- device model, operating system version, language, and country;
- crash logs and diagnostic information;
- an app-instance identifier.

### 5. Usage analytics (PostHog)

We also use **PostHog** (PostHog, Inc., USA) for product analytics, only while **usage statistics** are allowed (see "Consent and usage statistics" below). PostHog processes:

- a **random device identifier** created by the PostHog SDK for this installation (it is not the advertising ID and is not linked to your name, e-mail, or Firebase account);
- **usage events**: app installed, opened, updated, and sent to the background; screens you view; first-run and tutorial steps; runs started and finished (stage, mode, hero, difficulty tier, duration, kills, player level, how the run ended, top weapon, evolutions, revives); achievements; daily rewards; features used (for example upgrades, hero unlocks, chests, rerolls, revives, endless mode, skins, season and quest rewards); shop, season pass, and starter pack views; purchases and subscriptions (product, price, currency); rating prompts; notifications opened; short error reports (where the error happened and a short error message); and a few player properties (payer, premium status, supporter level, play days, total runs, and stages unlocked);
- **device and app information**: device manufacturer and model, operating system and version, app version and build, language/locale, screen size, time zone, and network type;
- your **IP address**, which PostHog uses to derive an **approximate location** (country, region, city).

PostHog is used **without session replay or any recording of your screen**, and **no person profile** is created: events are linked only to the random device identifier. Events contain no name, e-mail address, advertising ID, nickname, or text you type. We use one PostHog project for all our apps; each event is tagged with the app it comes from.

### 6. Advertising

The Game shows ads through **Google AdMob** (optional rewarded ads and limited interstitial ads). AdMob may process the **advertising ID**, IP address, and device information to show and measure ads and, if you consent, to personalise them.

Players with an active Rift Pass subscription or the Remove Ads purchase do not see interstitial ads.

## Consent and usage statistics

- **EEA, UK, and Switzerland** (based on your device's region setting; if it cannot be determined, you are asked too): usage statistics stay **off** until you answer a one-time in-game question ("Help us improve?"), shown after your first run. If you choose **No thanks**, nothing is sent to PostHog and Firebase Analytics is told (through Google Consent Mode) not to store analytics data.
- **Other countries**: usage statistics are **on by default**.
- **Everywhere**: you can switch **Settings → Privacy → Usage statistics** on or off at any time. The same switch controls both Firebase Analytics and PostHog, and a new choice applies straight away.

Uninstalling the Game stops all collection. Clearing the app's storage or reinstalling the Game creates a new random PostHog identifier. You can also e-mail **hoenngames@gmail.com** to object to analytics or to ask us to delete your analytics data.

You can also reset or delete your advertising ID from your Android device settings.

## Why We Process Data

We use information to:

1. provide the Game and save and restore your progress;
2. show leaderboards;
3. validate purchases, restore entitlements, and prevent fraud;
4. fix crashes and improve the Game, including understanding how the Game is used, measuring how many players come back, and finding where players get stuck or stop playing (usage analytics are never used for advertising and never sold);
5. run game-balance experiments through Remote Config;
6. show advertising that keeps the Game free to play;
7. comply with legal obligations.

## Legal Bases Under the GDPR

Where the GDPR applies, processing may rely on:

- **performance of a contract (Art. 6(1)(b))** to provide the Game, cloud saves, leaderboards, and purchases;
- **consent (Art. 6(1)(a))** for usage analytics (PostHog and Firebase Analytics) in the EEA, UK, and Switzerland, for personalised advertising, and where otherwise required; you can withdraw consent at any time in **Settings → Privacy → Usage statistics**;
- **legitimate interests (Art. 6(1)(f))** for security, fraud prevention, and crash reporting;
- **legal obligations (Art. 6(1)(c))** where processing is required by law.

## Service Providers and Data Sharing

We share information only as needed to operate the Game with:

- **Google Firebase** — Authentication (anonymous), Cloud Firestore, Cloud Functions, Analytics, Crashlytics, Remote Config — [firebase.google.com/support/privacy](https://firebase.google.com/support/privacy)
- **Google AdMob** — advertising — [policies.google.com/technologies/ads](https://policies.google.com/technologies/ads)
- **Google Play** — distribution, billing, and purchase validation — [policies.google.com/privacy](https://policies.google.com/privacy)
- **PostHog, Inc. (USA)** — product analytics — [posthog.com/privacy](https://posthog.com/privacy)

We do **not** sell personal data.

Information may also be disclosed if required by law or when reasonably necessary to protect users, the service, or legal rights.

## International Data Transfers

Google may process data outside your country. Where required, transfers are handled using the safeguards provided by applicable law and by Google.

**PostHog, Inc.** is based in the USA, and usage analytics are stored in PostHog's US cloud. These transfers are protected by the European Commission's Standard Contractual Clauses (included in PostHog's Data Processing Agreement) and, where applicable, the EU-U.S. Data Privacy Framework.

## Data Retention

- **Local data** stays on your device until you clear the app's storage or uninstall the Game.
- **Cloud save and leaderboard data** is kept while your anonymous account is active or until you request deletion.
- **Purchase data** may be kept as needed to validate or restore purchases and to meet accounting and legal obligations.
- **Analytics and crash data** are kept according to Firebase retention settings.
- **PostHog analytics events** are kept for up to 12 months and then deleted automatically (or anonymised/aggregated).

## Data Deletion

You can delete your data from in-game **Settings → Delete my data**, or by e-mailing **hoenngames@gmail.com**. We delete your cloud save and leaderboard entries within 30 days.

A public deletion guide is available in this repository: `pixel-rift-survivors-account-deletion.md`.

Deleting your data does **not** cancel a Google Play subscription. Manage subscriptions from the Google Play Store.

## Your Rights

Depending on your jurisdiction, including under the GDPR, you may have the right to access, correct, delete, restrict, or object to processing of your personal data, to data portability, to withdraw consent, and to lodge a complaint with a data protection authority.

To exercise these rights, contact **hoenngames@gmail.com**.

## Security

We use reasonable technical measures such as HTTPS/TLS, Firebase Authentication, Firestore security rules, and server-side purchase verification. No electronic system can be guaranteed to be completely secure.

## Children's Privacy

Pixel Rift: Survivors is not directed to children under 13, and we do not knowingly collect personal data from children. If we learn that such data was collected, we will delete it. Usage analytics are pseudonymous (linked only to a random device identifier) and are not used for advertising or profiling.

## Changes to This Policy

We may update this Privacy Policy as the Game changes. The "Last updated" date above will be revised when material changes are made.

## Contact

**Marco Della Rosa**  
**Email:** hoenngames@gmail.com  
**Country:** Italy
