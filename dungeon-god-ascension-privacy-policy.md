# Privacy Policy for Dungeon God: Ascension

**Last updated: November 19, 2026**

This Privacy Policy explains how **Dungeon God: Ascension** ("the Game", "we", "our") collects, uses, stores, and shares information when you play the game.

Dungeon God: Ascension is a pixel-art roguelite action game for Android. The game works offline; online features such as cloud saves, Google sign-in, leaderboards, in-app purchases, analytics, and crash reporting use third-party services provided by Google, and usage analytics are also sent to PostHog.

## Data Controller

- **Developer:** Marco Della Rosa
- **Privacy contact:** hoenngames@gmail.com
- **Country:** Italy

## Information We Process

### 1. Game progress

The Game stores your progress on your device, such as souls, gems, unlocked characters, weapons and relics, achievements, bestiary, statistics, run history, challenges, and settings.

When online, this progress is also saved in **Google Firebase Cloud Firestore**, linked to an **anonymous Firebase account identifier** (UID) that is created automatically on first launch. We do not ask for a password.

### 2. Google sign-in (optional)

You can choose to link your progress to your Google account, so it can be restored on another device. If you do, **Firebase Authentication** receives from Google your **Google account identifier**, **e-mail address**, **display name**, and **profile picture URL**. This information is used only to sign you in and keep your progress linked to your account. It is never shown to other players.

If you sign out, the Game continues with a new anonymous account on the device.

### 3. Leaderboard data

When you finish a run, an entry is added to the online leaderboard. Other players can see:

- an automatically generated anonymous name (for example `PLAYER-1A2B`);
- the score and floor reached in the run.

Your real name and e-mail address are never shown on the leaderboard.

### 4. Purchase data

The Game offers in-app purchases (gems) through **Google Play Billing**. To validate purchases and prevent fraud, we process:

- product identifier;
- purchase token and order status;
- the anonymous account identifier that made the purchase.

Purchase tokens are verified server-side through a **Firebase Cloud Function** and recorded so that a purchase cannot be claimed twice. Payment details such as card numbers are handled by Google and are never received by us.

### 5. Analytics and diagnostics

The Android version of the Game sends **usage statistics and crash reports** automatically while you play. The Game does **not** ask for consent for this, and there is currently **no in-app setting** to turn it off; see "How to Stop Analytics" below for your options.

We use **Firebase Analytics** and **Firebase Crashlytics** to understand how the Game is played, balance difficulty, and fix crashes. These services may process:

- in-game events (for example runs started and ended, rooms cleared, upgrades chosen, performance summaries);
- device model, operating system version, language, and country;
- crash logs and diagnostic information;
- an app-instance identifier.

We also use **Firebase Remote Config** to adjust game-balance values and seasonal events without an app update. Remote Config uses an app-instance identifier to deliver the configuration.

#### Usage analytics (PostHog)

We also use **PostHog** (PostHog, Inc., USA) for product analytics. PostHog processes:

- a **random device identifier** created by the PostHog software when the Game is first started; it is not the advertising ID and is not linked to your name or e-mail address;
- **usage events**: the Game being installed, updated, opened, and sent to the background; screens opened; runs started, floors reached, and runs won, lost, or abandoned (dungeon, hero, difficulty, mode, floor, duration, kills, souls earned, and what defeated the hero); first-launch and tutorial steps; features used (for example opening chests, buying skins or blessings, Google sign-in); souls and gems spent; achievements; daily rewards; store views and gem-pack purchases (product identifier, price, and currency); rating prompts; and run seeds copied to share;
- a few **game properties** used to group players: total runs, best floor, and whether you have made a purchase;
- **device and app information** added automatically: device manufacturer and model, operating system and version, app version and build, language, screen size, time zone, and network type;
- your **IP address**, which PostHog uses to derive an **approximate location** (country, region, and city).

PostHog does **not** record your screen (no session replay) and does not receive your name, e-mail address, Google account details, player name, or the advertising ID. PostHog events are linked only to the random device identifier; no PostHog user profile is created.

### 6. No advertising

The Game does **not** show ads and does **not** use the advertising ID.

## Why We Process Data

We use information to:

1. provide the Game and save and restore your progress;
2. let you sign in with Google and restore progress on another device;
3. show leaderboards;
4. validate purchases, deliver gems, and prevent fraud;
5. fix crashes and improve the Game: understand how it is played, measure how many players come back, find where players get stuck or stop playing, and fix problems (Firebase Analytics, Crashlytics, and PostHog). Analytics data is not used for advertising and is never sold;
6. tune game balance and run A/B experiments through Remote Config;
7. comply with legal obligations.

## Legal Bases Under the GDPR

Where the GDPR applies, processing may rely on:

- **performance of a contract (Art. 6(1)(b))** to provide the Game, cloud saves, Google sign-in, leaderboards, and purchases;
- **legitimate interests (Art. 6(1)(f))** for analytics and crash reporting (Firebase Analytics, Crashlytics, and PostHog), namely our interest in keeping the Game stable and improving it; you have the right to object at any time (see "How to Stop Analytics");
- **legitimate interests (Art. 6(1)(f))** for security, fraud prevention, and game-balance configuration;
- **legal obligations (Art. 6(1)(c))** where processing is required by law.

## Service Providers and Data Sharing

We share information only as needed to operate the Game with:

- **Google Firebase** — Authentication (anonymous and Google sign-in), Cloud Firestore, Cloud Functions, Analytics, Crashlytics, Remote Config — [firebase.google.com/support/privacy](https://firebase.google.com/support/privacy)
- **PostHog, Inc.** (USA) — product analytics — [posthog.com/privacy](https://posthog.com/privacy)
- **Google Play** — distribution, billing, and purchase validation — [policies.google.com/privacy](https://policies.google.com/privacy)

We do **not** sell personal data.

Information may also be disclosed if required by law or when reasonably necessary to protect users, the service, or legal rights.

## International Data Transfers

Google may process data outside your country. Where required, transfers are handled using the safeguards provided by applicable law and by Google.

PostHog, Inc. is based in the United States, and PostHog analytics data is stored in PostHog's US cloud. These transfers are protected by the European Commission's Standard Contractual Clauses (included in PostHog's Data Processing Agreement) and, where applicable, the EU-U.S. Data Privacy Framework.

## Data Retention

- **Local data** stays on your device until you clear the app's storage or uninstall the Game.
- **Cloud save and account data** is kept while your account is in use or until you request deletion.
- **Leaderboard entries** are kept until you request deletion.
- **Purchase records** may be kept as needed to validate or restore purchases and to meet accounting and legal obligations.
- **Analytics and crash data** are kept according to Firebase retention settings.
- **PostHog analytics events** are kept for up to 12 months and then deleted automatically (or anonymised and aggregated).

## How to Stop Analytics

The Game currently has no in-app setting to turn off analytics or crash reports. You can:

- **uninstall the Game**, which stops all collection;
- **clear the Game's data or reinstall it**, which resets the random PostHog identifier and the Firebase app-instance identifier (clearing data also deletes progress that is not saved in the cloud);
- **e-mail hoenngames@gmail.com** to object to analytics or to request deletion of your data.

## Data Deletion

You can request deletion of your account and data by e-mailing **hoenngames@gmail.com** with the subject "Dungeon God: Ascension – delete my data". To help us find your data, include the Google account e-mail you signed in with, or the anonymous player name shown in the Game. We delete your account, cloud save, and leaderboard entries within 30 days.

Purchase records may be kept where required by law (for example accounting obligations).

## Your Rights

Depending on your jurisdiction, including under the GDPR, you may have the right to access, correct, delete, restrict, or object to processing of your personal data, to data portability, to withdraw consent, and to lodge a complaint with a data protection authority (in Italy, the Garante per la protezione dei dati personali).

To exercise these rights, contact **hoenngames@gmail.com**.

## Security

We use reasonable technical measures such as HTTPS/TLS, Firebase Authentication, Firestore security rules (each player can only read and write their own profile), and server-side purchase verification. No electronic system can be guaranteed to be completely secure.

## Children's Privacy

Dungeon God: Ascension is not directed to children under 13, and we do not knowingly collect personal data from children. If we learn that such data was collected, we will delete it. Analytics data is pseudonymous and is not used for advertising or profiling.

## Changes to This Policy

We may update this Privacy Policy as the Game changes. The "Last updated" date above will be revised when material changes are made.

## Contact

**Marco Della Rosa**
**Email:** hoenngames@gmail.com
**Country:** Italy
