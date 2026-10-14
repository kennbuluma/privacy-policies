# Privacy Policy for DSA Workbench

**Last Updated:** October 14, 2026  
**Effective Date:** October 14, 2026  
**Application Name:** DSA Workbench  
**Package / Application ID:** `com.bulums.dsa_workbench`  
**Current Version:** 3.0 (Build 3)  
**Data Controller / Publisher:** DSA Workbench Team  
**Data Protection Officer (DPO) Contact:** `dpo@dsaworkbench.internal`  
**Supervisory Authority Jurisdictions:** EU (GDPR / EDPS / CNIL), United States (CCPA / CPRA / FTC), Asia-Pacific (Singapore PDPA / Japan APPI)

---

## 1. Introduction & Overview

Welcome to **DSA Workbench** ("we," "our," or "us"). DSA Workbench is an educational mobile application designed for software engineers, computer science students, and interview candidates to master Data Structures and Algorithms through interactive visualizations, code comparisons, practice challenges, AI-guided algorithmic explanations, and technical interview simulations.

We are committed to protecting your privacy and ensuring you have complete control over your personal data. This Privacy Policy details the types of information we collect, how it is processed and protected, your legal rights under global data protection frameworks (including the **General Data Protection Regulation (GDPR)**, the **California Consumer Privacy Act (CCPA/CPRA)**, and the **Personal Data Protection Act (PDPA)**), and how to manage your privacy settings directly within the app.

---

## 2. Information We Collect

We only collect data necessary to provide and improve your educational learning experience. We categorize the information we collect as follows:

### A. Personal Information You Provide
- **Authentication Credentials:** When you sign in using Google Sign-In or other OAuth providers (GitHub, Apple, Microsoft, Facebook), we receive your display name, email address, profile photo URL, and a pseudonymous unique identifier (UID).
- **Guest / Offline Mode:** You can use DSA Workbench anonymously without creating an account or signing in. In this mode, no personal identifiers are collected.

### B. Educational Activity & Learning Progress
- **Problem Solving History:** Records of completed challenges, daily streaks, earned experience points (XP), unlocked achievement badges, and solved interview simulations.
- **Bookmarks & Saved Algorithms:** Algorithms, data structures, and custom code implementations you choose to bookmark.
- **Visualizer Inputs & Custom Test Cases:** Numerical sequences, graph vertices, or trees entered into the visualizer modules (processed strictly on-device in real-time).

### C. Technical, Device & Diagnostic Information
- **Device Identifiers:** Operating system version, device model, screen resolution, locale, and anonymous Firebase Installation IDs.
- **App Performance & Crash Diagnostics:** Crash logs, application freeze traces, and runtime telemetry collected via Firebase Crashlytics to diagnose defects and optimize frame rates during visualizer animations.
- **Network & Connectivity Status:** Network state checks (via `ConnectivityManager`) solely to determine offline vs. online synchronization state.

### D. What We DO NOT Collect
- **Zero Financial / Credit Card Storage:** We do not collect, process, or store credit card numbers or financial account credentials. In-app purchases and subscriptions are handled securely through Google Play Billing.
- **Zero Sensitive Data:** We do not collect biometric data, health data, racial/ethnic origin, political beliefs, or precise GPS geolocation.
- **Zero Broad Storage Access:** We do not request `READ_EXTERNAL_STORAGE` or `WRITE_EXTERNAL_STORAGE`. Media handling strictly utilizes the zero-permission Android Photo Picker.

---

## 3. How We Use Your Information

We process personal data for the following legitimate business and educational purposes:
1. **Core Learning Features:** To track problem completion, compute daily streaks, maintain leaderboard rankings, and award badges.
2. **Cloud Synchronization:** To securely synchronize your solved problems, bookmarked topics, and notes across devices via Google Cloud Firestore.
3. **AI Algorithmic Insights & Explanations:** To provide interactive hints, Big-O complexity breakdowns, and algorithm explanations using Google Gemini API. Algorithm queries do not include user personal identifiers.
4. **Offline Capability:** To cache catalog topics and problems in an encrypted local SQLite database (Room) so you can study without network connectivity.
5. **App Stability & Quality Assurance:** To identify visualizer bugs, fix crashes, and ensure smooth rendering across diverse Android devices.

---

## 4. Legal Bases for Processing (GDPR Article 6)

For individuals located in the European Economic Area (EEA), the United Kingdom, or Switzerland, our processing of your personal data is grounded in the following legal bases:
- **Contractual Necessity (Art. 6(1)(b)):** Providing your user account, cloud synchronization of your learning progress, and access to premium workbench features.
- **Consent (Art. 6(1)(a)):** For analytical telemetry, algorithmic personalization, and push notification reminders. You may grant or withdraw consent at any time via the in-app **Regulatory & Privacy Center**.
- **Legitimate Interests (Art. 6(1)(f)):** Protecting system integrity, preventing fraud, debugging performance issues, and ensuring app security.

---

## 5. Third-Party Service Providers & Data Disclosures

We never sell, rent, or monetize your personal information. We disclose information only to vetted service providers bound by strict confidentiality and data processing agreements:

| Service Provider | Purpose | Data Transferred | Privacy Policy Link |
|---|---|---|---|
| **Google Play Services** | Licensing, app updates, billing | Device model, purchase tokens | [Google Privacy Policy](https://policies.google.com/privacy) |
| **Firebase Authentication** | Secure user login via Google OAuth | Email, Name, Auth UID | [Firebase Security](https://firebase.google.com/support/privacy) |
| **Google Cloud Firestore** | Cloud database sync for progress & streaks | User progress, solved challenge IDs | [Google Cloud Privacy](https://cloud.google.com/terms/cloud-privacy-notice) |
| **Google Gemini API** | AI-driven algorithm tutor and hints | Educational queries & code inputs | [Google AI Privacy](https://policies.google.com/privacy) |
| **Firebase Crashlytics** | Crash logs and performance diagnostics | Stack traces, device OS version | [Firebase Privacy](https://firebase.google.com/support/privacy) |

---

## 6. International Data Transfers

DSA Workbench utilizes Google Cloud Platform data centers located in the European Union, the United States, and the Asia-Pacific region (Singapore and Tokyo). When data is transferred cross-border from the EEA or Asia, transfers are protected by:
- European Commission Standard Contractual Clauses (SCCs).
- Adequacy decisions recognized under GDPR Article 45.
- Explicit user consent toggles in the in-app Privacy Center for Asian PDPA cross-border transfers.

---

## 7. Data Retention & Account Erasure (Right to be Forgotten)

- **Retention Period:** We retain your learning progress as long as your account remains active. If your account is inactive for more than 24 consecutive months, account data is automatically scheduled for permanent deletion.
- **In-App Account & Data Deletion (GDPR Art. 17 / CCPA):** You can permanently delete your account and all associated records at any time directly within the app:
  1. Open the top-right menu and select **Privacy & Compliance**.
  2. Navigate to **Individual Privacy Rights**.
  3. Tap **"Right to Erasure: Delete All Account Data"** and confirm.
  4. All records in local SQLite/Room storage and Google Cloud Firestore will be permanently wiped within seconds.

---

## 8. Your Privacy Rights & In-App Self-Service Controls

Under global privacy regulations (GDPR, CCPA, CPRA, PDPA, APPI), you enjoy the following rights:
1. **Right of Access (GDPR Art. 15):** You have the right to request a copy of all personal information we hold about you.
2. **Right to Data Portability (GDPR Art. 20):** Tap **"Export Personal Data (JSON Machine-Readable)"** in the in-app Compliance Center to download or copy your full profile and problem history.
3. **Right to Rectification (GDPR Art. 16):** You can update your display name and preferences at any time.
4. **Right to Restriction / Opt-Out (CCPA "Do Not Sell or Share"):** We do not sell data. You can toggle off analytics and personalization at any time in the app settings.
5. **Right to Withdraw Consent:** Any consent given for telemetry, personalization, or notifications can be revoked immediately via the in-app consent toggles.

---

## 9. Security & Encryption Safeguards

We implement defense-in-depth security measures to protect your information:
- **Encryption in Transit:** 100% of network communications use HTTPS with TLS 1.3 encryption. Cleartext HTTP traffic is disabled system-wide.
- **Encryption at Rest:** Local caches are protected by Android Keystore and app sandbox isolation. Cloud databases in Firestore are encrypted at rest with AES-256.
- **Zero Plaintext Passwords:** Authentication uses tokenized OAuth 2.0; we never receive or store user passwords.
- **Code Hardening:** ProGuard / R8 optimization and obfuscation are enforced on release builds. Dynamic Code Loading (DCL) is strictly prohibited.

---

## 10. Children's Privacy (COPPA & Google Play Families Policy)

DSA Workbench is designed for general audiences, university students, and adult professionals (ages 13 and older, or 16+ in the European Union). We do not knowingly collect personal information from children under 13. If you believe a child has provided us with personal information, please contact our Data Protection Officer immediately at `dpo@dsaworkbench.internal`, and we will promptly purge the data.

---

## 11. Changes to This Privacy Policy

We may update this Privacy Policy from time to time to reflect changes in legal regulations, platform policies, or app features. When material changes occur, we will notify you through an in-app notice, banner, or release notes, and update the "Effective Date" at the top of this document.

---

## 12. Contact Us & Data Protection Officer

If you have questions, comments, or wish to exercise any of your privacy rights, please reach out to our team:

- **Data Protection Officer (DPO):** `dpo@dsaworkbench.internal`
- **Developer Support:** `kennbuluma@gmail.com`
- **Application:** DSA Workbench (`com.bulums.dsa_workbench`)
- **Supervisory Authority Inquiries:** If you are located in the EU, you have the right to lodge a complaint with your local Data Protection Authority (e.g., CNIL in France, BfDI in Germany, or the EDPS).
