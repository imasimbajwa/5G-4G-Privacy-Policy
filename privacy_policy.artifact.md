# Privacy Policy — 5G / 4G LTE Network Tools

**Effective Date:** October 13, 2026
**Last Updated:** October 13, 2026
**App:** 5G / 4G LTE Network Tools (`com.asdev.network5g`)
**Developer:** MUHAMMAD ASIM BAJWA ( AS )
**Contact:** imasimbajwa@gmail.com

---

## 1. Introduction
This Privacy Policy explains what information **5G / 4G LTE Network Tools** ("the app", "we", "us") accesses, how it is used, and the choices you have. By using the app, you agree to this policy.

**In short:** We do not have user accounts, do not run analytics or ad SDKs, and do not sell or share your personal data. Most data stays on your device. The only network traffic is the speed test, ping, and public IP checks that you start, as described in Section 4.

---

## 2. Information the App Accesses on Your Device
The app requests the permissions below to provide its features. This data is read and processed locally on your device.

| Permission | Data accessed | Why |
|---|---|---|
| `READ_PHONE_STATE` | SIM/subscription details, carrier name, network type (5G/4G/3G), signal strength | Live signal gauges and cellular diagnostics |
| `ACCESS_FINE_LOCATION` / `ACCESS_COARSE_LOCATION` | Location permission required by Android to read cell tower info (`CellInfo`) and Wi-Fi scan results | Show RSRP/RSRQ, cell IDs, and Wi-Fi channel data. Your location coordinates are **not** stored or sent to us or any server |
| `PACKAGE_USAGE_STATS` (special access, granted by you in Settings) | Per-app mobile and Wi-Fi data usage from `NetworkStatsManager` | Data Usage monitor |
| `QUERY_ALL_PACKAGES` | Installed app names and icons | Show readable app names and icons in the Data Usage monitor |
| `INTERNET` / `ACCESS_NETWORK_STATE` | Connection state | Speed test, ping, and IP lookup (see Section 4) |

The app does **not** use background location.

---

## 3. How We Use This Information
- Show live cellular and Wi-Fi signal information on your dashboard
- Run speed tests, ping, and DNS checks that you start
- Show per-app data usage
- Save your settings (theme, language, options) with Jetpack DataStore
- Save speed test history with a Room database

---

## 4. Network Requests and Third-Party Services
When you run a speed test, ping/DNS test, or public IP lookup, the app connects to external servers. These servers can see your **IP address** and basic request details (such as timestamp and data transferred for the test), as with any standard internet connection.

| Feature | Service contacted | Data seen by the service |
|---|---|---|
| Speed test | Cloudflare (`speed.cloudflare.com`) | IP address, test traffic |
| Public IP lookup | ipapi.co, ipwho.is, ipinfo.io | IP address |
| Ping / DNS test | Cloudflare (`1.1.1.1`), Google (`8.8.8.8`), Quad9 (`9.9.9.9`), AdGuard (`94.140.14.14`) | IP address, test queries |

These services have their own privacy policies, and we do not control them. We do not send your location, SIM details, installed apps list, or usage statistics to them.

---

## 5. Data Storage, Retention, and Security
- **Local storage:** Settings and speed test history are stored only on your device.
- **Retention:** Data stays until you clear it in the app, clear the app's storage in Android Settings, or uninstall the app.
- **No selling or sharing:** We do not sell your data or share it with advertisers.
- **Security:** We follow Android security practices, but no method of storage is 100% secure.

---

## 6. Third-Party Libraries
The app uses open-source libraries (such as Jetpack Compose, OkHttp, and Haze) that run on your device under their own licenses. Release builds contain no analytics, advertising, or tracking SDKs.

---

## 7. Your Choices and Rights
- **Permissions:** You can grant or revoke any permission at any time in Android Settings. Some features will not work without them.
- **Delete data:** Clear speed test history in the app, or clear storage / uninstall to remove all app data.
- **Requests:** Because we do not collect personal data on our servers, we hold nothing to access or delete. If you have a privacy request, contact us at the email above.

---

## 8. Children's Privacy
The app is not directed at children under 13, and we do not knowingly collect personal information from them. If you believe a child has provided information, contact us, and we will help.

---

## 9. Changes to This Policy
We may update this policy. The new version will be posted with an updated "Last Updated" date. Continued use of the app means you accept the changes.

---

## 10. Contact
**Developer:** MUHAMMAD ASIM BAJWA ( AS )
**Email:** imasimbajwa@gmail.com
