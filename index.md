# Privacy Policy — Bounty Budget

**Effective date:** March 5, 2026  
**App name:** Bounty Budget  
**Developer:** Bounty LLC  
**Contact email:** support@bountyapps.com

This Privacy Policy explains how Bounty Budget (“the App”, “we”, “us”) collects, uses, and shares information when you use the App.

---

## 1) What Bounty Budget is (and is not)
Bounty Budget is a personal finance and budgeting app that helps you track income, expenses, and goals.

- **No bank sync:** The App does **not** connect to your bank accounts. You manually enter transactions and account data.
- **No user accounts:** The App does **not** require registration and does **not** ask for your name, email, phone number, or other direct identifiers.

---

## 2) Data you enter in the app
You may choose to enter:
- Transactions (amounts, dates, categories, descriptions/notes)
- Accounts (names, types, balances, notes)
- Budgets and spending targets
- Custom categories/subcategories
- Optional profile inputs for personalization (e.g., age range, income range, goals, spending style, housing situation, AI persona preference)

**Important:** The App provides free-form fields (like names, notes, descriptions).  
Please **do not** enter highly sensitive information (e.g., government ID numbers, full payment card numbers, bank routing/account numbers, medical information). If you type sensitive information into these fields, it may be processed by features you enable (including AI features).

---

## 3) What we do NOT collect
We do not collect or store:
- Real name
- Email address (unless you contact support)
- Phone number
- Physical address
- Government ID numbers (e.g., SSN)
- Bank account/routing numbers
- Full payment card numbers
- Precise location / GPS
- Contacts, calendars, photos/media, health data, biometrics

---

## 4) Where your finance data is stored
Your finance data (transactions, accounts, categories, budgets, and optional profile data) is stored **locally on your device** using iOS storage mechanisms. iOS provides device-level protections (e.g., encryption at rest and sandboxing).

We do **not** operate a user account system that stores your full financial database on our servers.

---

## 5) AI features (OpenAI via Cloudflare Worker)

### 5.1 When AI data is sent
AI features are used for:
- **Voice transaction parsing** (turning voice-dictated text into structured transactions)
- **AI financial insights** (generating insights based on your spending patterns and profile)

Your data is sent to the AI provider **only when**:
- you enable AI features in the App, and
- you accept the in-app AI User Agreement/consent flow, and
- you initiate an AI action (e.g., request insights, use AI voice parsing).

### 5.2 What data may be sent to OpenAI
Depending on the AI feature you use, the following data may be transmitted:
- **Voice transcript text** (the text produced from speech recognition)
- **Optional user profile inputs** (age range, income range, goals, spending style, housing situation, persona preference)
- **Transaction information** needed for insights (amounts, dates, categories, descriptions/notes), typically summarized/aggregated rather than your entire raw history
- **Category and account names** (to match what you say in voice commands)
- **Account balances** only if you explicitly enable the setting **“Share Account Balances”**
- **Insight feedback** (e.g., marking an insight as helpful/unhelpful)

### 5.3 What is NOT intentionally sent to OpenAI
We do not intentionally include:
- your device identifiers (e.g., IDFA) as part of AI prompts
- your full raw database export by default
- bank account numbers or full payment card numbers (and we ask you not to enter them)

### 5.4 How requests are routed
AI requests are transmitted securely over HTTPS and are **proxied through our Cloudflare Worker** to reach OpenAI. We use this proxy to secure the API, reduce abuse, and avoid sending OpenAI direct device identifiers.

We do not store your AI prompts/responses on our own servers as a normal part of providing the AI features. However, **OpenAI may retain and process data** according to their policies (e.g., for safety/abuse monitoring).

**Infrastructure metadata:** Our infrastructure providers (e.g., Cloudflare) may process basic network metadata (such as IP address and request timing) to deliver, secure, and protect the service.

### 5.5 AI is informational only
AI outputs are provided for general informational and educational purposes and **are not professional financial advice**. You are responsible for verifying information and making decisions.

---

## 6) Voice input and Apple speech recognition
If you use voice input:
- The App requests access to **Microphone** and **Speech Recognition**.
- Voice audio may be processed by **Apple’s speech recognition services** (server-based, depending on your iOS settings and language/feature availability).
- The App receives a **text transcript** from speech recognition. If you use AI voice parsing, that transcript may then be sent to OpenAI (as described above).

You can disable microphone/speech permissions any time in iOS Settings. Some voice features will stop working if disabled.

---

## 7) Analytics (Mixpanel)
We use **Mixpanel** to understand app usage and improve the product.

### 7.1 What Mixpanel collects
Mixpanel may receive:
- App events (e.g., app opens, screen views, feature usage)
- Session information (duration, frequency)
- Device and app info (device model, OS version, app version)
- An **anonymous identifier** (Mixpanel device ID)

### 7.2 What we do NOT send to Mixpanel
We do not intentionally send:
- your transaction amounts, account balances, budgets, categories, or financial notes
- your voice recordings or transcripts
- direct identifiers like your name/email/phone (because we do not collect them)

### 7.3 Analytics controls
At this time, Mixpanel analytics are enabled by default for app improvement and **may not have an in-app opt-out**. You can still limit some device-level sharing through iOS privacy settings, but those controls may not disable analytics entirely.

---

## 8) Subscriptions (RevenueCat + Apple App Store)
Bounty Budget uses **RevenueCat** for subscription status and entitlement management. Purchases are processed by **Apple App Store**.

Subscriptions may include a free trial. If you start a free trial, **Apple may automatically convert it to a paid subscription unless you cancel before the trial ends**. Subscriptions are typically **auto-renewing** unless canceled in your Apple ID subscription settings. Pricing and trial length are shown in the paywall and may vary by region/currency.

### 8.1 Data shared with RevenueCat
RevenueCat may receive:
- an **anonymous app user identifier** (generated by the app/RevenueCat; not your real name)
- App Store receipt / purchase transaction data (for subscription validation)
- subscription status (trial/active/expired/canceled)
- basic device/app info (platform, OS version)
- attribution data (install source, if available)

RevenueCat does **not** receive your payment card details; Apple processes payments.

### 8.2 Advertising ID (IDFA) and attribution
If you have enabled “Allow Tracking” in iOS, Apple may provide an advertising identifier (IDFA) that can be used for attribution. If you decline tracking, IDFA is not available to the App for that purpose.

---

## 9) Notifications
If you enable reminders, the App may schedule local notifications on your device (e.g., daily reminders to log transactions, **budget alerts**, or **subscription reminders**). We do not receive notification content on our servers.

---

## 10) Data retention
### 10.1 On-device data
Your finance data remains on your device until you delete it in the App or delete the App (which removes local storage).

### 10.2 Third-party retention
Data sent to third parties is retained according to their policies and configurations:
- **OpenAI:** retention/processing per OpenAI policies
- **Mixpanel:** retention per Mixpanel settings/policies
- **RevenueCat:** retention per RevenueCat policies and legal/accounting requirements
- **Apple (speech / App Store):** retention per Apple policies
- **Cloudflare (infrastructure):** retention per Cloudflare policies/configuration for security and service delivery logs (if enabled)

### 10.3 Deletion limitations
- We cannot retrieve or delete data already transmitted to OpenAI, Mixpanel, RevenueCat, Apple, or Cloudflare except as allowed by those providers’ processes.
- Because we do not maintain user accounts and do not collect your email/name by default, we may not be able to locate third-party records unless you provide relevant identifiers (e.g., Mixpanel distinct ID or RevenueCat App User ID, if available in your settings/support logs).

---

## 11) Security
We use reasonable safeguards to protect data:
- HTTPS/TLS for network communication
- AI requests proxied through Cloudflare Worker
- On-device storage protected by iOS security mechanisms

No system is 100% secure. You are responsible for securing your device (passcode, Face ID/Touch ID, OS updates).

---

## 12) International data transfers
Third-party providers may process data in the United States and other countries. By using AI features, analytics, or subscriptions, you understand data may be transferred and processed outside your country, depending on provider infrastructure.

---

## 13) Children’s privacy
The App is not directed to children under 13, and we do not knowingly collect personal information from children.

---

## 14) Changes to this policy
We may update this Privacy Policy. We will post the updated version on this page and update the effective date.

---

## 15) Contact
For privacy questions, contact: **[support@bountyapps.com]**  
Developer: **[Bounty LLC]**  
