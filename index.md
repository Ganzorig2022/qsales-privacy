# Privacy Policy — QSales

**App:** QSales (`mn.qpay.qsales`)
**Provider:** KKTT LLC (QPay) — a Mongolian company, registered in Ulaanbaatar, Mongolia
**Contact:** ganzorig.n@qpay.mn
**Address:** NM Tower, 8th Floor Mahatma Gandhi Street 15th Khoroo, Khan-Uul District Ulaanbaatar
**Last updated:** 2026-06-25

## 1. Who this app is for
QSales is a **business tool for QPay sales agents** (bank staff / KKTT operators).
Accounts are **provisioned by QPay**, not self-registered by the public. It is not
directed to children; we do not knowingly process data of anyone under 18.

## 2. What we collect and why

| Data | Why | Where it goes |
|------|-----|---------------|
| **Account login** (username, password) | Authenticate the agent | Sent over HTTPS to the QPay contract backend. |
| **Session token (JWT)** | Keep you signed in | Stored **encrypted on-device** (Android Keystore via secure storage); cleared on logout / 15-min inactivity. |
| **Saved login password** *(only if you enable biometric quick-login)* | Re-authenticate after fingerprint/face unlock | Stored **encrypted on-device** only. Removed when you disable biometric login. |
| **Biometric (fingerprint/face)** | Unlock the app | Handled **entirely by your device's OS.** We **never receive, store, or transmit biometric data.** |
| **Merchant onboarding data** (business name, contractor name, phone, email, **bank account details**, business category) | Create/manage merchant contracts & payment QR | Sent over HTTPS to the QPay backend. |
| **Location** (approximate & precise) | Let you place a merchant's location on a map | Used by Google Maps to show the map; the chosen coordinates are sent to the QPay backend with the contract. Requested only when you open the map. |
| **Photos / documents** (camera or files) | Attach merchant documents and your profile avatar | Sent over HTTPS to QPay backend storage. Chosen by you per upload; we don't browse your gallery in the background. |
| **Push notification token (FCM)** + basic device info (model, OS) | Deliver account/contract notifications | Token registered with the QPay backend; push delivered via Firebase Cloud Messaging (Google). |

We process this data to **provide and secure the service** and to **comply with
legal/financial-record obligations**. We do **not** sell personal data, and the app
contains **no advertising or analytics SDKs**.

## 3. Third parties
- **QPay backend (`sales.qpay.mn`)** — first-party processor for all business data.
- **Google Firebase Cloud Messaging** — delivers push notifications (receives the device push token).
- **Google Maps SDK** — renders the map and processes location while the map screen is open
  (see Google's Privacy Policy).

## 4. Security
All network traffic uses **HTTPS/TLS**. Tokens and any saved login credential are stored
in the platform's encrypted keystore. No method is 100% secure, but we apply reasonable
technical and organizational safeguards.

## 5. Your choices
- **Permissions:** camera, location, photos, and notifications are requested only when you
  use the related feature; you can revoke any of them in Android Settings → Apps → QSales.
- **Notifications:** turn them off in system settings at any time.
- **Access / correction / deletion:** request it at **ganzorig.n@qpay.mn**. Because accounts
  are provisioned by QPay, deletion may also require contacting your QPay administrator.

## 6. Data deletion requests
To request deletion of your data from **QSales** (provided by KKTT LLC / QPay):

1. Email **ganzorig.n@qpay.mn** from your registered address, with the subject
   **"QSales data deletion request"** and your QSales username.
2. We verify the request with your QPay administrator (accounts are provisioned by
   QPay, not self-registered).
3. We action it within **30 days** and confirm by email.

**Deleted on request:** your account profile (username, name, email, phone), saved
login credentials, push-notification token, and uploaded photos/documents.

**Kept:** merchant contracts and bank-account/financial records are retained only as
long as required by Mongolian financial-record and legal obligations, after which they
are deleted or anonymized.

## 7. Changes & contact
We may update this policy; the "Last updated" date will change. Questions:
**ganzorig.n@qpay.mn**.
