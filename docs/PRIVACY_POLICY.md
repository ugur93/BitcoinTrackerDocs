# Privacy Policy

**Effective date:** 2026-10-03  
**App:** Bitcoin Tracker  
**Contact:** proventuspro@protonmail.com

## 1. Scope
This Privacy Policy explains how Bitcoin Tracker ("we", "our", "us") handles information when you use the mobile application.

## 2. Data We Process
### 2.1 Data you enter
- Portfolio transaction entries (amounts, prices, notes, timestamps).
- Wallet addresses and extended public keys (xpub, ypub, zpub) you choose to track. Extended public keys are stored only on your device. The app derives the wallet's addresses on the device and looks up their balances and transactions at public block explorers (Blockstream and mempool.space). The extended key itself is never sent anywhere. Extended public keys can only view a wallet, never spend from it, and the app rejects private keys.
- App preferences (currency, display settings, feature toggles).

### 2.2 Data from device/app usage
- Notification permission status and local notification settings.
- App diagnostics needed for core functionality (when available from platform APIs).

### 2.3 Subscription and purchase data
If you use paid features, subscription and entitlement events are processed via Apple and RevenueCat (our subscription infrastructure provider), such as:
- Product identifiers.
- Purchase state / entitlement status.
- Anonymous app user identifiers used for subscription state.

### 2.4 Instant alerts, daily brief and weekly recap
If you create price alerts and allow notifications, the app sends the following to our alerts server (hosted on Cloudflare) so it can notify you when the app is closed. Free users send up to three price alerts; indicator alerts, the daily brief, the weekly recap and on-chain alerts are part of Hodler Pro:
- Your price alerts (direction, target price, currency, on/off state).
- Your daily brief and weekly recap settings (on/off, delivery time, time zone, currency).
- The kind and threshold of each indicator alert (24h move, Mayer Multiple, fee rate or Hash Ribbons).
- A push notification token, a random install identifier created by the app, and the anonymous RevenueCat app user identifier used to confirm your subscription.
- Only if you turn on a transaction alert: the transaction ID and the label you gave it. It is deleted once the transaction confirms or you turn the alert off.
- Only if you turn on payment alerts for a wallet: that wallet's address, or for an extended public key the next few unused receive addresses, plus the wallet's name and the total amount ever received by those addresses. The extended public key itself is never sent. They are deleted when you turn the alert off.

Portfolio transactions, extended public keys and balances are never sent to the alerts server, and wallet addresses only as described above when you turn on payment alerts. Notifications are delivered through Expo's push service and Apple Push Notification service, which receive the push token and the notification text.

### 2.5 Market/network data
The app requests public market and blockchain-related data from third-party endpoints (for example, pricing and network statistics providers). Those providers may receive your IP address and standard request metadata.

## 3. How We Use Data
We use data to:
- Deliver app functionality (charts, alerts, portfolio analytics).
- Sync/validate subscription entitlement status.
- Improve reliability and prevent abuse.
- Respond to support requests.

We do not sell your personal data.

## 4. Tracking and Advertising
Bitcoin Tracker is not designed for cross-app advertising tracking.  
If this changes, we will update this policy and request required platform permissions.

## 5. Data Storage and Retention
- Portfolio data, wallet addresses and extended public keys are stored only on your device.
- Alert data is stored on your device. With notifications allowed, your alerts (and, for Hodler Pro, daily brief and weekly recap settings) are also stored on the alerts server. They are deleted when you delete or turn off all of them, when the push token stops working (for example after you uninstall the app), or, for Pro-only items, when your subscription lapses. Records of fired alerts are kept for up to 30 days.
- Tax reports (CSV/PDF) are generated on your device and only leave it if you choose to share them.
- Subscription entitlement data is managed by Apple/RevenueCat as required for purchases.
- Retention duration depends on your device state, app uninstall, and provider retention policies.

## 6. Data Sharing
We may share limited data with service providers strictly to operate the app:
- **RevenueCat** (subscription management).
- **Cloudflare** (hosts the alerts server for price alerts and the Hodler Pro daily brief, weekly recap and indicator alerts).
- **Expo** and **Apple Push Notification service** (deliver push notifications).
- **Apple** (in-app purchase processing).
- **Market/network data providers** used by the app (for example CoinGecko, Coinbase, Yahoo Finance, Blockstream and mempool.space). They receive requests for public data, not your portfolio.

We may disclose information if required by law.

## 7. Your Choices
You can:
- Delete local app data from in-app settings (where available) or by uninstalling the app.
- Disable notifications at the OS level.
- Stop server-side alerts by turning off alerts, the Daily Market Brief, the Weekly Recap, transaction alerts and wallet payment alerts in the app.
- Manage subscriptions in your Apple ID subscription settings.

## 8. Children
The app is not directed to children under 13 (or equivalent minimum age in your jurisdiction).

## 9. International Transfers
Service providers may process data in countries different from your residence. We rely on provider safeguards where applicable.

## 10. Security
We use reasonable technical and organizational measures to protect information. No system is guaranteed to be 100% secure.

## 11. Changes to This Policy
We may update this policy. Material changes will be reflected by updating the effective date and, where required, providing notice.

## 12. Contact
For privacy questions or requests, contact: proventuspro@protonmail.com
