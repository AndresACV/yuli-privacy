---
layout: default
title: Privacy Policy
---

# Privacy Policy — Yuli

**Last updated:** August 18, 2026

**Document version:** 1

Yuli ("us", "we", or "our") operates the Yuli mobile application (the "App"). This Privacy Policy explains how we collect, use, store, and protect your personal information when you use the App.

This notice explains Yuli's data practices. Acknowledging that you have read it is not blanket consent to every form of processing. When Yuli relies on consent for optional processing, it requests that consent separately for a specific purpose and provides a way to withdraw it.

---

## 1. Information We Collect

### 1.1 Information You Provide Directly

| Data Type | Purpose | Storage |
|---|---|---|
| Age group selection | Determine age-appropriate features and content | On-device (encrypted) |
| Cycle/period dates | Cycle tracking and predictions | On-device (encrypted) |
| Symptoms and moods | Health tracking and pattern detection | On-device (encrypted) |
| Sexual activity logs | Fertility tracking and health insights | On-device (encrypted) |
| Pregnancy data | Pregnancy companionship and week-by-week guidance | On-device (encrypted) |
| Health log entries | Personal health journal (conditions, treatments) | On-device (encrypted) |
| Notes | Calendar-linked personal notes | On-device (encrypted) |
| Appointments | Doctor appointment scheduling and reminders | On-device (encrypted) |
| Medications | Medication tracking and reminders | On-device (encrypted) |
| AI chat messages | Conversations with the in-app health assistant | On-device (encrypted) |

### 1.2 Information Collected Through Third-Party Services

| Data Type | Service | Purpose |
|---|---|---|
| Email address, display name, profile photo | Firebase Authentication (Google Sign-In) | Account creation and sign-in |
| Purchase history, subscription status | RevenueCat | In-app purchase processing and subscription management |

### 1.3 Information We Do NOT Collect

- We do **not** collect device location (GPS) without your explicit consent
- We do **not** collect analytics or usage telemetry that includes personally identifiable information (PII)
- We do **not** track you across apps or websites
- We do **not** sell your data to any third party

---

## 2. How We Use Your Information

We use your information solely to:

- Provide cycle tracking, predictions, and health insights
- Detect health patterns and alert you to potential irregularities
- Deliver age-appropriate content and features
- Process in-app purchases and manage subscriptions
- Authenticate your account (if you choose to sign in)
- Provide AI-powered health consultations (when available)

We do **not** use your data for advertising, profiling, or any purpose unrelated to the App's core functionality.

---

## 3. Data Storage and Security

### 3.1 Local-First Architecture

All your health data (cycles, symptoms, moods, sexual activity, pregnancy data, health logs, notes, appointments, medications, and AI chat history) is stored **exclusively on your device** in an encrypted database.

### 3.2 Encryption

- **At rest**: All local data is encrypted using **SQLCipher (AES-256-CBC)**. The encryption key is derived from your device's secure key storage (Android Keystore / iOS Keychain) and is never transmitted or stored in plaintext.
- **In transit**: All network communications use **HTTPS/TLS 1.2+** encryption.

### 3.3 Optional App Lock

You may enable a PIN code or biometric lock (fingerprint, face) to prevent unauthorized access to the App on your device.

---

## 4. Third-Party Services

Yuli integrates the following third-party services, each governed by their own privacy policies:

| Service | Purpose | Data Shared | Privacy Policy |
|---|---|---|---|
| **Firebase Authentication** (Google) | User sign-in via Google account | Email, display name, profile photo | [Firebase Privacy](https://firebase.google.com/support/privacy) |
| **RevenueCat** | In-app purchase and subscription management | Purchase receipts, subscription status | [RevenueCat Privacy](https://www.revenuecat.com/privacy/) |

We do **not** share your health data (cycles, symptoms, moods, sexual activity, pregnancy data, etc.) with any third-party service.

---

## 5. Children's Privacy (COPPA Compliance)

Yuli is intended for users who are at least 13 years old. The App asks for an age group before offering account authentication or requesting personal information.

- If a user indicates that they are under 13, account creation stops and Yuli does not request a Google sign-in or parental email.
- Yuli does not knowingly collect personal information from children under 13.
- If we learn that we received personal information from a child under 13, we will delete it. A parent or guardian may contact us using the email below.

If Yuli's target audience changes in the future, we will update the App, this policy, and the applicable parental-consent process before allowing children under 13 to create accounts.

---

## 6. Your Rights

### 6.1 Access Your Data

You can view all data stored by the App directly within the App's interface.

### 6.2 Export Your Data

From Settings, you can export every category stored by Yuli in its encrypted on-device database as **JSON**. The JSON export is created from one consistent database snapshot and fails rather than producing a knowingly incomplete file. You can also export cycle records as **CSV**. Neither export includes Firebase account metadata or purchase and subscription records held by Google, Apple, or RevenueCat.

### 6.3 Delete Your Data

Choose **Settings → Data → Delete local data** to permanently erase all Yuli data stored on your device, including health records, preferences, community activity, and mascot progress. The App also cancels its scheduled local notifications and signs you out. This irreversible action does not delete your Firebase account.

### 6.4 Account Deletion

Choose **Delete account** below your account in Settings to permanently delete your Firebase Authentication account. Yuli asks you to authenticate with Google again before deletion, then erases all Yuli data stored on the device and cancels scheduled local notifications. Purchase and subscription records retained by Google Play, Apple, or RevenueCat are governed by those services and remain available for purchase restoration.

### 6.5 GDPR Rights (European Union)

If you are a resident of the European Economic Area, you have the right to:

- **Access** your personal data
- **Rectify** inaccurate data
- **Erase** your data ("right to be forgotten")
- **Port** all categories stored by Yuli on your device through the JSON export described above
- **Object** to data processing
- **Withdraw consent** at any time where processing relies on consent

### 6.6 CCPA Rights (California)

If you are a California resident:

- You have the right to know what personal information we collect
- You have the right to delete your personal information
- We do **not** sell personal information — "Do Not Sell My Personal Information" does not apply, but we include this disclosure as required

---

## 7. Data Retention

- **On-device data**: Retained until you delete it or uninstall the App
- **Firebase Authentication data**: Retained while your account exists. You may delete your account at any time
- **RevenueCat purchase data**: Retained per RevenueCat's data retention policy to manage subscriptions and restore purchases

---

## 8. Advertising

Yuli currently does **not** display any advertisements. If advertising is introduced in the future, this policy and the App's age-appropriate safeguards will be updated before ads are enabled.

---

## 9. Cloud Sync (Future Feature)

A future version of Yuli may offer opt-in cloud sync. If implemented:

- Cloud sync will be **opt-in only** — never enabled by default
- All data will be **end-to-end encrypted** before leaving your device
- The server will store only encrypted blobs and will never have access to your plaintext health data
- You will be able to revoke sync and delete all server-side data at any time

This policy will be updated before any cloud sync feature is released.

---

## 10. Changes to This Privacy Policy

We may update this Privacy Policy from time to time. Changes will be posted within the App and at this URL, with the document version and "Last updated" date revised accordingly. Yuli requires an in-app review before normal use resumes when a material change affects processing purposes, data categories, recipients, retention, user rights, or other substantive practices. Editorial corrections do not trigger another review. Immutable copies of released versions remain available in this repository.

---

## 11. Contact Us

If you have questions, concerns, or requests regarding this Privacy Policy or your data, please contact us:

**Email:** privacy@yuli.app

---

*This privacy policy is available in [English](privacy-policy) and [Español](privacy-policy-es).*
