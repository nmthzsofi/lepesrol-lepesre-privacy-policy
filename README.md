# Privacy Policy

**App name:** Lépésről Lépésre
**Last updated:** March 22, 2026
**Developer:** Zsófia Németh
**Contact:** nemethzsofia442@gmail.com

---

## 1. Introduction

Lépésről Lépésre ("the app", "we", "us") is a fitness tracking application that helps you set virtual journeys and track your progress through physical activity. This Privacy Policy explains what personal data we collect, why we collect it, how it is used, and what rights you have over your data.

By using the app, you agree to the collection and use of data as described in this policy.

---

## 2. Data We Collect

### 2.1 Account & Authentication Data

- **Email address** — used to create and authenticate your account
- **Password** — stored in hashed form by Firebase Authentication (Google). We never have access to your plain-text password.

### 2.2 Profile Data

The following information is collected during onboarding and stored in your user profile:

- First name and last name
- Username (unique, public-facing identifier)
- Sex (Male, Female, Non-binary, or "Prefer not to say")
- Date of birth
- Height (in centimetres)
- Weight (in kilograms)
- Profile photo (optional)

This data is used to personalise your experience and calculate fitness estimates (e.g. calories burned, stride length).

### 2.3 Fitness & Activity Data

- **Lifetime step count** — an aggregate total of all steps you have logged
- **Journey progress** — your step contributions toward each journey goal
- **Badges** — achievement flags earned through activity milestones

Activity details you enter (activity type, duration, intensity) are used solely to calculate a step count on your device. **Raw activity details are not stored or transmitted.**

### 2.4 Journey & Location Data

When you create a journey, we store:

- Journey name, icon, and type (individual, cooperative, or race)
- Start and end coordinates (latitude and longitude) for the chosen route
- Your progress along the route (derived from step count)

Location data consists only of the fixed start and end points you choose for your journeys. **The app does not track your real-time GPS location, movement, or physical whereabouts at any time.**

To look up place names, your search queries and selected coordinates are sent to the OpenStreetMap Nominatim geocoding service (see Section 4).

### 2.5 Profile Photo

If you choose to upload a profile photo, the image is stored in Firebase Cloud Storage. A reference URL is saved in your user profile.

### 2.6 Data We Do NOT Collect

- Real-time device location or GPS tracking
- Health platform data (Apple HealthKit, Google Fit)
- Device identifiers, advertising IDs, or IMEI
- Phone number or contacts
- Raw activity logs (type, duration, intensity are not stored)
- Crash reports, usage analytics, or behavioural tracking

---

## 3. How We Use Your Data

| Purpose                                             | Data Used                | Legal Basis (GDPR)                         |
| --------------------------------------------------- | ------------------------ | ------------------------------------------ |
| Account creation and authentication                 | Email, password          | Contract performance                       |
| Personalising your fitness experience               | Profile data, step count | Contract performance                       |
| Calculating fitness estimates (calories, stride)    | Height, weight           | Contract performance                       |
| Displaying your journey on the map                  | Journey coordinates      | Contract performance                       |
| Group journey features (leaderboard, progress sync) | First name, step count   | Contract performance                       |
| Awarding badges and tracking milestones             | Lifetime step count      | Contract performance                       |
| Sending email verification and password reset links | Email address            | Contract performance / Legitimate interest |

We do not use your data for advertising, profiling, or any automated decision-making.

---

## 4. Data Shared with Third Parties

We use the following third-party services to operate the app. We do not sell your data to any third party.

### 4.1 Google Firebase (Firebase Authentication, Firestore, Cloud Storage)

Your account credentials, profile data, journey data, and profile photos are stored on Google's Firebase platform. Firebase operates under Google's privacy and security framework, which includes compliance with GDPR.

- Firebase Privacy Policy: https://firebase.google.com/support/privacy
- Google's data processing terms apply.

### 4.2 OpenStreetMap Nominatim

When you search for a journey start or end location, your search query and the selected coordinates are sent to Nominatim, a free public geocoding service operated by the OpenStreetMap Foundation. No personal account data is transmitted — only the location query itself. Nominatim does not require authentication and does not retain personally identifiable information.

- OpenStreetMap Privacy Policy: https://wiki.osmfoundation.org/wiki/Privacy_Policy

### 4.3 No Other Third Parties

The app does not integrate analytics platforms (e.g. Mixpanel, Amplitude), crash reporting tools (e.g. Sentry, Crashlytics), or advertising networks.

---

## 5. Data Shared with Other Users

Lépésről Lépésre includes cooperative and race group features. When you join or create a group journey:

- Your **first name** and **current step count** for that journey are visible to other members of the same group.
- Your **ranking position** is shown on the group leaderboard.

The following data is **never** shared with other users: last name, email, date of birth, height, weight, sex, profile photo, total lifetime steps, or any individual goals.

Group access is controlled by an 8-character share code. Only people you share the code with can join your group journey.

---

## 6. Data Retention

- **Account data** is retained for as long as your account is active.
- **Journey data** is retained until you delete the journey. Completed journeys are kept in your history unless explicitly deleted.
- **Profile photos** are retained in Firebase Cloud Storage until your account or photo is deleted.
- If you delete your account, please contact us at nemethzsofia442@gmail.com to request full deletion of your data from Firebase. We will process such requests within 30 days.

---

## 7. Your Rights (GDPR)

If you are located in the European Economic Area (EEA), you have the following rights regarding your personal data:

- **Right of access** — You can request a copy of the personal data we hold about you.
- **Right to rectification** — You can correct inaccurate or incomplete data through the app's profile settings at any time.
- **Right to erasure** — You can request deletion of your personal data ("right to be forgotten").
- **Right to data portability** — You can request your data in a machine-readable format.
- **Right to restrict processing** — You can ask us to limit how we use your data in certain circumstances.
- **Right to withdraw consent** — Where processing is based on consent, you may withdraw it at any time without affecting the lawfulness of prior processing.
- **Right to lodge a complaint** — You have the right to lodge a complaint with your local data protection authority.

To exercise any of these rights, please contact us at **nemethzsofia442@gmail.com**.

---

## 8. Children's Privacy

The app is not intended for use by children under the age of 13 (or under 16 in certain EEA countries). We do not knowingly collect personal data from children. If you believe a child has provided us with personal data, please contact us and we will delete it promptly.

---

## 9. Data Security

We take reasonable technical and organisational measures to protect your data. All communication with Firebase is encrypted in transit (HTTPS/TLS). Passwords are never stored in plain text. Access to Firestore data is governed by security rules that restrict each user to their own data.

However, no method of electronic transmission or storage is 100% secure. We cannot guarantee absolute security.

---

## 10. Changes to This Policy

We may update this Privacy Policy from time to time. We will notify you of significant changes by updating the "Last updated" date at the top of this document. Continued use of the app after changes constitutes acceptance of the updated policy.

---

## 11. Contact

If you have any questions about this Privacy Policy or how your data is handled, please contact:

**Zsófia Németh**
Email: nemethzsofia442@gmail.com
