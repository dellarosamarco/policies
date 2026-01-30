# Privacy Policy for PetDates

## Introduction

This **Privacy Policy** explains how the **PetDates** app (“PetDates”, “we”, “our”) collects, uses, and shares users’ information.  
This policy is designed to comply with **Google Play Store requirements** and applicable data protection laws, including the **General Data Protection Regulation (GDPR)**.

PetDates is a dating and messaging platform for pet owners.  
The app is **not intended for children**, and users must meet the minimum legal age required to create an account.

---

## Data Controller

- **Developer name:** Marco Della Rosa
- **Privacy contact email:** hoenngames@gmail.com
- **Country:** Italy

---

## Data We Collect

| Category | Details and Purpose |
|----------|---------------------|
| **Account data** | Email address and password used to create and authenticate the account through Firebase Authentication. Passwords are never stored in plain text. |
| **Pet profile data** | Pet name, type, breed, age, gender, biography, profile photo, and image gallery (up to 3 images). Stored in Firebase Firestore (`pets` collection) and displayed to other users for matchmaking. |
| **Location data** | GPS coordinates and city provided during onboarding. Stored as a `geo` object (geopoint + geohash) and used to show nearby pets and calculate distance. Optional but required for some features. |
| **Push notification token (FCM)** | Firebase Cloud Messaging token used to send notifications about new matches and messages. |
| **Interaction data** | Likes, passes, matches, chat messages, blocked users, and reports. Stored in Firestore. |
| **City search data** | Requests sent to OpenStreetMap Nominatim service when searching for cities. These requests may include IP address and search query. |
| **Technical logs** | Technical data such as IP address, device type, operating system, and timestamps collected by Firebase for security and diagnostics. |

---

## Purpose of Data Processing

PetDates uses the collected data to:

1. Create and manage user accounts  
2. Display pet profiles and enable matchmaking  
3. Enable chat and user interactions  
4. Send push notifications  
5. Ensure user safety (blocking and reporting)  
6. Comply with legal obligations  

---

## Legal Basis (GDPR)

PetDates processes personal data based on:

- **Contract performance (Art. 6(1)(b) GDPR)** – to provide the service  
- **User consent (Art. 6(1)(a) GDPR)** – for location data and push notifications  
- **Legitimate interest (Art. 6(1)(f) GDPR)** – for security and abuse prevention  

Users may withdraw consent at any time from device or app settings.

---

## Data Sharing with Third Parties

PetDates **does not sell personal data**.

Data may be shared with the following service providers:

- **Google Firebase** (Authentication, Firestore, Cloud Functions, Storage, Cloud Messaging)  
- **Google Maps / Geolocator / Geoflutterfire** (distance and location features)  
- **OpenStreetMap Nominatim** (city lookup)  
- **Hosting and infrastructure providers** when strictly necessary  

All data transfers occur over secure HTTPS connections.

---

## Data Retention and Deletion

Data is stored only as long as necessary:

- **Active accounts:** Data is stored while the account is active  
- **Account deletion:** Users can delete their account from the app. This permanently removes:
  - User profile
  - Likes and passes
  - Matches
  - Blocked users
  - Images from Firebase Storage
  - Firebase Authentication account  

- **Inactive accounts:** Data may be deleted after long periods of inactivity  
- **Anonymous data:** Aggregated and anonymized data may be kept for service improvement  

---

## User Rights

Users have the right to:

1. Access their personal data  
2. Rectify incorrect or incomplete data  
3. Request deletion of personal data  
4. Restrict processing  
5. Data portability  
6. Object to processing  
7. Withdraw consent at any time  

Requests can be sent to the email address listed in the **Data Controller** section.

Users also have the right to lodge a complaint with their national data protection authority.

---

## Security Measures

PetDates implements appropriate security measures, including:

- Encrypted communication (HTTPS/TLS)  
- Restricted access to data  
- Secure authentication via Firebase  
- Password hashing handled by Firebase Auth  
- Monitoring and abuse prevention  

However, no system is completely secure.

---

## Children’s Privacy

PetDates does not knowingly collect personal data from children under 13 years of age.  
If such data is discovered, it will be deleted immediately.

---

## Changes to This Privacy Policy

This Privacy Policy may be updated periodically.  
Users will be notified of significant changes through the app or other appropriate channels.

---

## Contact

For privacy-related questions or requests, please contact:

- **Email:** hoenngames@gmail.com

---

**Last updated: January 2026**
