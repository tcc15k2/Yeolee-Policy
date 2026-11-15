# SnapSolve Privacy Policy

Effective date: 2026-11-13
Operator: Yeolee · Contact: tcc15k2@gmail.com

[한국어](../privacy.html)

## 1. What SnapSolve does
SnapSolve shows an AI-made answer and step-by-step solution when you take a photo of a math problem. You can use it without signing up, and it is for people 14 or older. We do not collect your name, email address or phone number.

## 2. Problem photos
- When you ask for a solution, the problem photo you chose is sent to the operator's server over an encrypted connection (HTTPS).
- The photo passes through a server in the Google Cloud Seoul region (Firebase Cloud Functions) and is sent to the Claude API of Anthropic, PBC (United States) to make the solution.
- The operator's server discards the photo after making the solution and does not store it. The photo and the solution are stored only on your phone.
- Please photograph only the problem, so that no personal information such as names, faces or contact details appears in the photo.
- Share images are made on your device and sent to the app you choose. The operator does not receive them.

## 3. Birth year and month
On first launch, the app checks on your phone whether you are 14 or older from the birth year and month you enter. The values you enter are not stored; only the result of the check is recorded on your phone.

## 4. Information stored only on your phone

| Information | Contents | Purpose |
|---|---|---|
| Solve history | Reduced copy of the problem photo, answer and solution, time of the solve | Viewing recent solves again |
| App settings | Age check result, whether you agreed to the terms | Keeping the app working |

## 5. Information stored on our server
Stored in Cloud Firestore (Google Cloud Seoul region) with an anonymous ID that the app creates automatically.

| Information | Purpose | Retention |
|---|---|---|
| Solve count per day, remaining ad-reward solves, time of last use | Managing usage limits and ad rewards | Deleted after 90 days without use. Kept while a subscription is active |
| Solve request records (request ID, processing status) | Preventing the same request from being counted twice | 1 day |
| Ad reward records (transaction ID, time granted) | Preventing the same reward from being granted twice | 30 days |
| Subscription information (Google Play purchase token, expiry time) | Checking the subscription | Deleted together with your account data |
| Reported solutions (answer and solution text, report reason, model name) | Improving solution quality and checking inappropriate content | 90 days. Photos are not kept |

## 6. Third-party services

| Service | Information sent | Purpose | How to turn it off |
|---|---|---|---|
| Google AdMob | Advertising ID and app set ID, IP address (may be used to estimate approximate location), ad interactions such as views and clicks, device information | Showing and measuring rewarded ads, preventing fraud | Delete the advertising ID in your phone settings. No ads with a subscription |
| Firebase Authentication (Google) | Anonymous ID | Linking usage limits and subscriptions to the anonymous ID | — |
| Firebase App Check, Google Play Integrity (Google) | Result of the app and device integrity check | Preventing unauthorized calls to the server | — |
| Firebase Cloud Functions, Cloud Firestore (Google) | Problem photo (passed through, not stored), the information in section 5 | Relaying solve requests and storing usage records | — |
| Firebase Analytics (Google) | Basic usage records such as first launch and sessions, solve starts and results, time taken to solve, ad rewards and failures, subscription screen views and purchases, report reasons, use of the share button, device information, app instance ID | Improving the app | — |
| Firebase Remote Config (Google) | App instance ID, app version | Showing usage limits and update notices | — |
| Claude API (Anthropic, PBC) | Problem photo and solution | Making the AI solution | — |
| Google Play billing | Purchase information (handled by Google Play; the app does not receive card details) | Subscription payment and checks | Cancel the subscription in Google Play |

- Apart from Anthropic, the information above is sent to Google and handled under the [Google Privacy Policy](https://policies.google.com/privacy).
- The operator does not sell personal information.

## 7. International transfers

**Google LLC (United States)**
- Information transferred: the AdMob, Firebase Analytics, Firebase Authentication, App Check, Remote Config and Google Play billing items in section 6
- When and how: sent over the network from time to time while you use the app
- Purpose and retention: the purposes in section 6. Retention follows Google's policies.
- Contact: [Google privacy inquiries](https://support.google.com/policies/contact/general_privacy_form)

**Anthropic, PBC (United States)**
- Information transferred: problem photo and solution
- When and how: sent over an encrypted network (HTTPS) when you ask for a solution
- Purpose and retention: making the AI solution. Anthropic deletes inputs and outputs within 30 days of receiving them and does not use them to train models. If a usage policy violation is detected they may be kept for up to 2 years, and where the law requires, for as long as it requires.
- Contact: [Anthropic Privacy Policy](https://www.anthropic.com/legal/privacy)

If you do not want these transfers, please delete the app. You can delete the advertising ID in your phone settings. The information in section 5 is stored in the Google Cloud Seoul region, and problem photos are not stored anywhere.

## 8. Deletion and your rights
- In the app's settings, "Delete my data" deletes the solve history on your phone and the server data linked to the current install.
- If you reinstall the app or clear its data, the previous anonymous ID can no longer be reached, so you cannot delete that data yourself. It is deleted automatically after 90 days without use. It is not deleted while a subscription is active.
- You can ask to access, correct, delete or stop processing your personal information at tcc15k2@gmail.com. Because information is stored only under an anonymous ID, we handle requests without delay to the extent we can identify the data.

## 9. Security
- Connections between the app and the server, and between the server and Anthropic, are all encrypted with HTTPS.
- The server rejects requests without an app integrity check and an authentication token. The Anthropic API key is kept only on the server.
- Server logs do not contain problem photos or solution text.

## 10. Children
This app is not intended for children under 14, and we do not knowingly collect their information. If we learn that information from a child under 14 was collected, we delete it without delay.

## 11. Changes
If this policy changes, we update this page and the effective date.

## 12. Privacy officer and contact
Yeolee · tcc15k2@gmail.com

## 13. Regional rights
- **Canada (PIPEDA):** You can ask to access the personal information we hold about you and to correct it, using the contact in section 12.
- **Singapore (PDPA):** Our data protection officer is the contact in section 12. You can ask to access or correct your personal data and withdraw consent; withdrawing consent may mean you can no longer use the app.
- **Australia (Privacy Act, Australian Privacy Principles):** You can ask to access or correct your personal information using the contact in section 12. If you are not satisfied with our response, you can complain to the Office of the Australian Information Commissioner (OAIC).
- **California:** We will review CCPA obligations if we meet its thresholds.
