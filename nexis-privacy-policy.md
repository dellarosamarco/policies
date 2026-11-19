# Privacy Policy for Nexis

**Last updated: November 19, 2026**

This Privacy Policy explains how **Nexis: Notes, Tasks & Planner** ("Nexis", "we", "our") collects, uses, stores, and shares information when you use the app.

Nexis is a productivity app for notes, to-do lists, spreadsheets, tasks, timeline, calendar, folders, and tags. Your content is stored in your personal cloud space so it can sync across your devices, and a local copy is kept on the device so the app also works offline.

## Data Controller

- **Developer:** Marco Della Rosa
- **Privacy contact:** hoenngames@gmail.com
- **Country:** Italy

## Information We Process

### 1. Account and authentication data

Nexis uses Firebase Authentication (Google). Depending on how you sign in, we may process:

- a Firebase user identifier (UID);
- e-mail address (e-mail/password or Google sign-in);
- display name and profile information returned by Google Sign-In, if you choose that option;
- authentication provider information.

You can also use Nexis as a guest: in that case an anonymous Firebase account is created, with no e-mail or name. A guest can later link a Google account without losing data.

Passwords are handled by Firebase Authentication and are never stored by Nexis in plain text.

### 2. Content you create

To provide the app's features, Nexis stores the content you create in Cloud Firestore, in a private area linked to your account:

- notes (title, text, tags, folder, pinned state);
- to-do lists and their items;
- spreadsheets (cells, values, and formulas);
- tasks (title, description, priority, start and due dates, status, tags);
- folders (name, icon, color);
- creation and update timestamps.

### 3. Attachments: photos and audio

If you add attachments to a note, Nexis uploads them to Firebase Storage in a private area linked to your account:

- images you pick from your gallery or take with the camera;
- voice memos you record with the microphone, or audio files you choose.

The microphone is used only while you are recording a voice memo. The camera and gallery are used only when you choose to attach a photo. Attachments must be images or audio and are limited to 20 MB each.

### 4. Data stored only on your device

Nexis stores some data only on your device, such as:

- app preferences (theme, accent color, text size, navigation bar layout, start page, library view);
- an offline cache of your content and of images you have already viewed, so the app can work without a connection.

### 5. Usage analytics and crash reports

Nexis sends **usage statistics and crash reports** automatically. Nexis does **not** ask for consent for this, and there is currently **no in-app setting** to turn it off (see "How to Stop Analytics" below).

**Google Analytics for Firebase and Firebase Crashlytics (Google).** To understand how the app is used and to fix crashes, these services process app usage events (the same kinds of events listed below for PostHog), an app-instance identifier, device model, operating system and app version, language, approximate country, and crash logs and diagnostic information.

**Usage analytics (PostHog).** We also use **PostHog** (PostHog, Inc., USA) for product analytics. PostHog processes:

- a **random device identifier** created by the PostHog software when the app is first started; it is not the advertising ID and is not linked to your account, name or e-mail address;
- **usage events**: the app being installed, updated, opened and sent to the background; screens opened; items created (notes, tasks, lists, spreadsheets, habits — only the type of item, never its content); tasks completed, habits checked and reminders set; the welcome pages viewed or skipped; account created or guest account linked (only the method: e-mail, Google, Apple or guest); features used (for example attachments by type, content shared into Nexis, chats created, import and export); Premium screen views and purchases or subscriptions (product ID, price and currency); rating prompts; reminders opened from a notification; and error codes (where the error happened and a short technical code);
- two **account properties** used to group users: whether you use a guest account and whether you have Premium;
- **device and app information** added automatically: device manufacturer and model, operating system and version, app version and build, language, screen size, time zone and network type;
- your **IP address**, which PostHog uses to derive an **approximate location** (country, region, city).

PostHog does **not** record your screen (no session replay) and never receives the content of your notes, tasks, lists, spreadsheets, chats or attachments, your name, your e-mail address or the advertising ID. PostHog events are linked only to the random device identifier; no PostHog user profile is created and events are not linked to your Nexis account.

## How We Use Information

We use the information only to:

- create and manage your account and let you sign in;
- store, sync, and show your notes, lists, spreadsheets, tasks, folders, and attachments across your devices;
- let you use the app offline and sync changes when you are back online;
- keep the service secure and prevent abuse;
- understand how the app is used and improve it, measure how many users come back, find where users get stuck or drop off, and fix crashes and other problems (usage analytics and crash reports).

We do **not** use your content for advertising, profiling, or selling, and Nexis does **not** show ads. Analytics data is not used for advertising and is never sold.

## Legal Basis (EEA/UK users)

We process your data because it is necessary to provide the service you request (performance of a contract) and, for security purposes, on the basis of our legitimate interest in keeping the service safe.

Usage analytics (Google Analytics for Firebase and PostHog) and crash reports are processed on the basis of our legitimate interest in understanding how the app is used, keeping it stable and improving it (Art. 6(1)(f) GDPR). You have the right to object at any time (see "How to Stop Analytics").

## Sharing of Information

We do not sell your personal data and we do not share it with third parties for their own purposes.

Your data is processed by our service provider **Google Firebase** (Google LLC / Google Ireland Ltd.) for authentication, database, file storage, analytics (Google Analytics for Firebase), and crash reporting (Crashlytics). Google acts as a data processor on our behalf. More information: https://firebase.google.com/support/privacy

Usage analytics are also processed by **PostHog, Inc.** (USA) — product analytics — https://posthog.com/privacy

Data may be processed on servers located outside your country, including in the United States, with the safeguards provided by Google's data processing terms.

PostHog, Inc. is based in the United States, and PostHog analytics data is stored in PostHog's US cloud. These transfers are protected by the European Commission's Standard Contractual Clauses (included in PostHog's Data Processing Agreement) and, where applicable, the EU-U.S. Data Privacy Framework.

We may disclose information if required by law.

## Security

- All data is transmitted over encrypted connections (HTTPS/TLS).
- Security rules on Firestore and Storage allow each user to access only their own data.
- Attachments are restricted to images and audio files of up to 20 MB.

No method of transmission or storage is 100% secure, but we take reasonable measures to protect your information.

## Data Retention

We keep your data for as long as your account exists. Content you delete in the app (notes, lists, spreadsheets, tasks, folders, attachments) is removed from our cloud storage. When your account is deleted, all your cloud data is deleted.

PostHog analytics events are kept for up to 12 months and then deleted automatically (or anonymised and aggregated).

## How to Stop Analytics

Nexis currently has no in-app setting to turn off usage analytics or crash reports. You can:

- uninstall the app, which stops all collection;
- clear the app's data or reinstall it, which resets the random analytics identifiers;
- write to **hoenngames@gmail.com** to object to analytics or to request deletion of your data.

## Your Rights and Account Deletion

You can view, edit, and delete your content at any time from the app.

You can request the deletion of your account and all associated data by following the instructions at:
https://github.com/dellarosamarco/policies/blob/main/nexis-account-deletion.md

Depending on where you live (for example under the GDPR), you may also have the right to access, correct, export, restrict, or object to the processing of your data, and to lodge a complaint with a supervisory authority (in Italy: Garante per la protezione dei dati personali). To exercise your rights, write to hoenngames@gmail.com.

## Children

Nexis is not directed to children under 13, and we do not knowingly collect personal data from children under 13. If you believe a child has provided us with personal data, contact us and we will delete it. Analytics data is pseudonymous and is not used for advertising or profiling.

## Changes to This Policy

We may update this Privacy Policy from time to time. The updated version will be published on this page with a new "Last updated" date.

## Contact

For any question about this Privacy Policy or your data, contact: **hoenngames@gmail.com**
