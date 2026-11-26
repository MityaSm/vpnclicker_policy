# Privacy Policy

**Last Updated: November 26, 2026**

## Introduction
This Privacy Policy describes how **Ignis Apps** ("we", "us", or "our") collects, uses, shares, and protects information when you use the mobile game **"Hacker: Idle Tycoon"** ("the Game") on iOS (Apple App Store) and Android (Google Play).

We are committed to protecting your privacy in compliance with applicable laws and platform policies, including the Apple App Store Review Guidelines, Google Play Policies, the General Data Protection Regulation (GDPR / UK GDPR), the California Consumer Privacy Act (CCPA / CPRA), and children’s privacy laws (such as COPPA).

## Information We Collect

### 1. Gameplay & Account Data (Local and Cloud)
* **Local Game Data:** Game progress (in-game currency, levels, upgrades, settings, VIP status expiration, and processed transaction IDs) is stored locally on your device via Unity `PlayerPrefs`.
* **Anonymous Cloud Profile:** To enable leaderboards, competitive features, referrals, and VIP status synchronization, we assign you a pseudonymous identifier via **Firebase Authentication (Anonymous Sign-In)** (or a locally generated fallback ID if offline).
* **Cloud Gameplay Data:** Through **Cloud Firestore**, we store pseudonymous gameplay records linked to your anonymous User ID, including lifetime and weekly earnings, player and season levels, equipped virtual items, country/region code (derived from your device’s regional settings), in-game shield timestamps, Cyber VIP expiration dates, referral/invite records, and in-game attack/defense inbox notifications.

### 2. Technical, Device & Advertising Identifiers
Depending on your platform, region, and consent choices, we and our third-party SDK partners may collect:
* **On iOS:** **Identifier for Advertisers (IDFA)** — collected **only** if you grant permission through Apple’s App Tracking Transparency (ATT) prompt; **Identifier for Vendor (IDFV)**; and **SKAdNetwork** attribution data.
* **On Android:** **Google Advertising ID (AAID)** and Android / App Set IDs.
* **Device & Network Information:** IP address, device model, operating system version, system language, and time zone/region settings.

### 3. In-App Purchases
The Game offers optional in-app purchases (such as the 30-day **Cyber VIP** pass) processed directly by **Apple (App Store / StoreKit)** or **Google (Google Play Billing)** via Unity IAP.
* We do **not** collect, process, or have access to your credit card numbers, bank details, billing address, or Apple ID / Google account credentials.
* We only receive non-sensitive purchase confirmations and transaction identifiers to grant and restore your in-game VIP benefits.

### 4. Local Notifications
With your permission, the Game schedules **local** on-device notifications (such as boost expiration, daily rewards, offline earnings, and gameplay cooldown reminders). These notifications are processed locally on your device and do not collect remote push notification tokens.

## Third-Party Services
The Game integrates the following third-party services, each governed by its own privacy policy:

1. **Google AdMob & Google UMP SDK (Advertising & Consent Management):**
   - Delivers optional rewarded video ads and manages regional privacy consent dialogs (GDPR/EEA/UK and US state laws).
   - Processes device/advertising identifiers (AAID, or IDFA if authorized via ATT), IP addresses, and ad interaction data.
   - [Google Privacy Policy](https://policies.google.com/privacy)

2. **Unity Ads (Ad Mediation via Google AdMob):**
   - Acts as an advertising mediation partner to deliver rewarded ads.
   - May process device identifiers, IP addresses, and ad performance metrics in accordance with your consent and ATT settings.
   - [Unity Privacy Policy](https://unity.com/legal/privacy-policy)

3. **Google Firebase (Authentication, Cloud Firestore, Analytics, Remote Config):**
   - **Firebase Authentication:** Provides anonymous authentication without requiring names, emails, or passwords.
   - **Cloud Firestore:** Stores pseudonymous leaderboard, country ranking, hacking inbox, invite, and VIP sync data.
   - **Firebase Analytics (with Google Consent Mode v2):** Collects gameplay events, session duration, and feature usage, and uses IP addresses for approximate geographic location (country/city level) without storing precise GPS location.
   - **Firebase Remote Config:** Delivers in-game news and configuration updates.
   - [Firebase Privacy Information](https://firebase.google.com/support/privacy)

4. **Apple App Store (StoreKit) & Unity Technologies (Unity Engine / Unity IAP):**
   - Collects basic hardware/OS telemetry for engine stability and processes store transactions and purchase restoration.
   - [Apple Privacy Policy](https://www.apple.com/legal/privacy/)
   - [Unity Privacy Policy](https://unity.com/legal/privacy-policy)

5. **External Links (Discord):**
   - The Game contains an optional link to our official Discord community. Clicking that link takes you outside the Game to a third-party platform governed by [Discord’s Privacy Policy](https://discord.com/privacy).

## How We Use Your Information
We use the collected information strictly for:
- **Game Functionality:** Saving progress, calculating offline earnings, powering leaderboards and PvP/hacking mechanics, and delivering in-game news.
- **In-App Purchases:** Verifying and restoring Cyber VIP access across sessions.
- **Advertising:** Serving optional rewarded video ads, preventing ad fraud, and measuring ad performance.
- **Analytics & Optimization:** Understanding gameplay progression, balancing economy, and improving performance across iOS and Android devices.
- **Security & Fair Play:** Detecting automated abuse/bots and protecting competitive leaderboards.

## Limited Personal Data Collection
We do **NOT** collect direct personal identification data such as:
- Real names, email addresses, or phone numbers (unless you voluntarily contact us by email for support).
- Physical addresses or payment card details.
- Contacts, photos, camera, microphone, or precise GPS location.

## Data Retention, Security & Deletion
- **Encryption:** All network communications with Firebase, AdMob, Unity Ads, and App Store / Google Play services are encrypted in transit via HTTPS/TLS.
- **Retention:** Local data remains on your device until you uninstall the Game or clear app data. Cloud leaderboard and gameplay records are retained while the Game operates or until deleted upon request.
- **How to Delete Your Data:**
  - **Local Data:** Uninstall the Game (or clear app storage in Android settings).
  - **Cloud Data (Firestore & Analytics):** You may request deletion of your pseudonymous cloud profile and associated gameplay records by emailing us at **ge.vovabelikov@gmail.com** and providing your in-game **Player ID** (displayed in the Profile/Statistics screen). We will process verified deletion requests within 30 days.

## Children’s Privacy
The Game is intended for a general audience and is **not** directed at children under the age of 13 (or the minimum age required for digital consent in your country, such as 13–16 in the EEA/UK). We do not knowingly collect personal information from children. If you are a parent or guardian and believe your child has provided personal data, please contact us at **ge.vovabelikov@gmail.com** so we can delete it promptly.

## International Data Transfers
Your information may be processed on servers located outside your country of residence (including the United States) where Google, Unity, and our infrastructure partners operate. Such transfers rely on appropriate safeguards recognized under applicable data protection laws (such as Standard Contractual Clauses).

## Your Rights and Choices
Depending on your location, you have the right to manage your privacy and request access to or deletion of your data:
- **iOS Tracking (ATT / IDFA):** You can allow, deny, or revoke ad tracking at any time in **iOS Settings > Privacy & Security > Tracking** (or **Settings > Hacker: Idle Tycoon > Tracking**).
- **Android Ads Personalization:** You can reset or delete your Advertising ID or opt out of personalized ads in **Android Settings > Google > Ads**.
- **In-Game Privacy Settings (GDPR / EEA / UK):** You can review or withdraw your advertising and analytics consent at any time using the **Privacy** button in the in-game **Profile / Statistics** menu.
- **Notifications:** You can enable or disable local game notifications at any time in your device’s system settings.
- **Access & Deletion Requests:** Contact us at **ge.vovabelikov@gmail.com** to exercise your rights under GDPR, UK GDPR, or CCPA/CPRA.

## Contact Information
If you have questions or requests regarding this Privacy Policy, please contact:
- **Developer:** Ignis Apps
- **Email:** [ge.vovabelikov@gmail.com](mailto:ge.vovabelikov@gmail.com)

## Changes to This Policy & Consent
We may update this Privacy Policy from time to time to reflect updates to the Game or legal requirements. The "Last Updated" date at the top indicates the latest revision. By installing or continuing to use **"Hacker: Idle Tycoon"**, you acknowledge the practices described in this Privacy Policy (subject to your explicit consent choices where required by law).
