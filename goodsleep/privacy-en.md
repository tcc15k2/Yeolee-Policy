# GoodSleep Privacy Policy

Effective date: 2026-10-15
Operator: Yeolee · Contact: tcc15k2@gmail.com
Korean version: https://tcc15k2.github.io/Yeolee-Policy/goodsleep/privacy.html · German version: https://tcc15k2.github.io/Yeolee-Policy/goodsleep/privacy-de.html

## 1. What GoodSleep does
GoodSleep is a free app that tracks your sleep and plays sounds designed to reflect acoustic characteristics identified in sleep research. It is not a medical device and does not replace diagnosis or treatment.

## 2. Information stored only on your phone
Every feature works without signing in. The information below is, by default, stored **only on your phone**.

| Information | Contents | Purpose |
|---|---|---|
| Sleep records | Bedtime and wake time, estimated sleep stages in 30-second steps, quality and metrics, mood and notes | Journal, statistics, weekly report |
| Sound events | Time and length of detected snoring, coughing and sleep talking | Sound events in the journal |
| Sound clips | **Short segments (up to about 10 seconds, low quality)** around detected events. Continuous recordings are never stored | Listening again in the journal |
| Mixes, sleep goals, settings | Saved sound combinations, goals per weekday, app settings | App behavior |
| Diagnostic log | Times and names of sound-service, session and playback events (for example "playback error", "output device removed") and why the app process last ended. It contains no audio, no sleep data and no personal identifiers | Finding out why sound stopped. It is stored on your phone and leaves it when you choose Profile > Send diagnostic log. If the app crashes or hits an error, the recent entries are included in the crash report (section 4) |

- Microphone audio is **analyzed only on your phone** and is never sent to a server. A sound-classification model that runs on the device (YAMNet) is used for the analysis.
- Sound clips are deleted automatically according to "Sound clip retention" in Profile (do not save / 1 / 20 / 100 nights), and you can delete them immediately with "Delete data".
- If you choose phone movement (accelerometer) for tracking, the microphone is not used.

## 3. Information that leaves your phone only if you turn on an optional feature
### 3-1. Account and backup (Google sign-in, optional)
If you turn on backup, you sign in with your Google account (identifier, email, name) and the following is stored in your own private area of **Google Firebase (Firestore)**:
- Sleep records (including the 30-second chart), notes and tags, mixes, sleep goals, settings
- **Not included**: sound clips, advertising ID, device information

You can delete the server data and your account with "Delete account and backups" in the app. The records on your phone remain.

### 3-2. Health Connect (optional)
If you connect it, sleep times and sleep stages are **written** to Health Connect. The app does not request read permission. You can withdraw the permission at any time in Health Connect settings.

## 4. Services that are always used

| Service | Information sent | Purpose | How to turn off |
|---|---|---|---|
| Firebase Analytics | Events such as how often features are used (sleep records and sounds are not sent), device and app version. **Off by default; sent only if you turn on Profile > "Send usage statistics"** | Improving the product | Profile > Send usage statistics |
| Firebase Crashlytics | Crash and error reports (device model, OS, stack trace, and the recent diagnostic log — app event names and times only, no audio or sleep data) | Stability | — |
| Firebase Remote Config | (Receive only) feature switch values | Turning a feature off remotely if there is a problem | — |
| Google AdMob | Advertising ID and app set ID, IP address (which may be used to estimate approximate location), interactions such as app launches and taps, and diagnostic information about app and ad SDK performance | Showing banner and native (card-style) ads, measuring and analyzing ad performance, preventing misuse | Profile > Privacy and ad consent |

- Ads appear only on the Sounds, Journal, Statistics, Profile and Sleep home screens (before tracking starts). **They never appear while you sleep, during the alarm or at the morning check-in.** Banners are hidden from 00:00 to 06:00.
- In regions where ad consent is required, consent is collected with Google's User Messaging Platform (UMP) form, which you can reopen from Profile.
- Information sent by AdMob is transmitted (shared) to Google and handled under Google's privacy policy (https://policies.google.com/privacy). All transmission is encrypted with TLS. You can reset or delete your advertising ID in Android settings.

## 5. Retention and deletion
- Information on your phone: deleted when you uninstall the app or choose Profile > "Delete data".
- Backup information: delete it with "Delete account and backups" or with the web deletion request below.
- If you cannot delete it in the app, email tcc15k2@gmail.com and we will handle it within 7 days.

## 6. Children
GoodSleep is not directed to children under 14 (or the equivalent minimum age in your country), and we do not knowingly collect information from children.

## 7. Changes
If this policy changes, we will say so in the app and in this document together with the effective date.

## 8. Users in the EU/EEA, the UK and Switzerland
- **Controller**: Yeolee (individual developer), tcc15k2@gmail.com.
- **Legal bases (GDPR Art. 6(1))**: account and backup — performance of the service you requested (b); Health Connect — your consent (a), which you can withdraw in Health Connect at any time; advertising (AdMob) — your consent through the UMP form (a); usage statistics (Firebase Analytics) — your consent (a), given by turning it on in Profile, which you can withdraw at any time; crash reports and Remote Config — legitimate interest in stable and secure operation (f). Information that stays on your phone (section 2) is not transmitted to us.
- **International transfers**: Firebase and AdMob are provided by Google, and data may be transferred to the United States. Google LLC is certified under the EU-US Data Privacy Framework, and the European Commission's standard contractual clauses also apply.
- **Your rights**: access, rectification, erasure, restriction of processing, data portability (for example through the CSV export in the app), and objection to processing based on legitimate interests. You can withdraw consent at any time with effect for the future. You also have the right to lodge a complaint with a data protection supervisory authority, in particular in the member state where you live. Send requests to tcc15k2@gmail.com.

## 9. Contact
Yeolee · tcc15k2@gmail.com
Web deletion request page: https://tcc15k2.github.io/Yeolee-Policy/goodsleep/account-deletion/en/
