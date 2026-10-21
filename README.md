# 🦊 Flowstate Downloads

Welcome to the official download repository for **Flowstate** — a calm, AI-assisted personal productivity companion engineered around your biological energy rhythms and accompanied by **Noya**.

🌐 **Official Website:** [flowstate-noya.pages.dev](https://flowstate-noya.pages.dev/)  
📦 **All Releases:** [GitHub Releases](https://github.com/Milindskii/Flowstate-Downloads/releases)

---

## ⚡ Latest Release: Flowstate 1.1.0 (Build 9)

**Build 9** is the current stable release of Flowstate for Android. It includes critical improvements to update notification behavior, refined out-of-charges dialog workflows, comprehensive ad diagnostics, and enabled rewarded ads for real-device testing.

### 📥 Download Links

| Asset | Description | Size | Link |
|---|---|---|---|
| **Flowstate.apk** | Standalone Android Application Package | ~145.6 MB (`152,668,223 bytes`) | [⬇️ Download APK](https://github.com/Milindskii/Flowstate-Downloads/releases/download/v1.1.0-build9/Flowstate.apk) |
| **Flowstate Bundle (ZIP)** | Complete bundle (APK, Checksum, Release Notes, README) | ~107.0 MB (`112,216,797 bytes`) | [📦 Download Bundle (.zip)](https://github.com/Milindskii/Flowstate-Downloads/releases/download/v1.1.0-build9/Flowstate-1.1.0-build9-ads-bundle.zip) |
| **SHA-256 Checksum** | Cryptographic verification file | `81 bytes` | [📄 View Checksum](https://github.com/Milindskii/Flowstate-Downloads/releases/download/v1.1.0-build9/Flowstate.apk.sha256) |

---

## 🌟 About Flowstate

Flowstate helps you design balanced, sustainable daily schedules rather than overwhelming to-do lists.

- **Rhythm-Based Day Planning & Build My Day:** Automatically aligns deep focus sessions with your natural energy peaks and places recovery breaks when your focus dips.
- **Noya Companion:** An interactive presence that celebrates completed commitments, offers contextual encouragement, and tracks your daily flow.
- **Focus Rooms & Rituals:** Built-in ambient soundscapes and distraction-free timers to help you enter and maintain a flow state.
- **Flow Shield & Streak Protection:** Keep your momentum safe from burnout with streak freeze shields, earned through focus sessions and daily consistency.
- **Flow Hub & Shop:** Access rewards, manage shields and coins, and optional rewarded ad interactions backed by server-side verification.

---

## 🛠️ What's New in Build 9

- **Update Dialog Dismissal Memory:** Dismissing the in-app "New Version Available" prompt (by tapping outside or selecting "Later") is now remembered for that specific build. The prompt will no longer repeatedly interrupt your flow on every app resume.
- **Dedicated Flow Charge Ad Placement:** The "Watch an ad" prompt has been removed from AI planning modals and centralized exclusively in the Flow Charges wallet.
- **Diagnostic Ad Reporting:** When a rewarded ad cannot load or display, the exact underlying SDK reason (stage, error code, and domain) is captured for troubleshooting rather than showing generic error text.
- **Rewarded Ads Enabled:** Client-side switch is enabled (`ENABLE_REWARDED_ADS=true`) for verified real-device testing against server-side verification (SSV).
- **All Improvements from Builds 6–8:** Includes Razorpay / Cashfree payment integration, bug report submission via Resend, and local notification enhancements.

---

## 📋 Release & Security Specifications

| Specification | Details |
|---|---|
| **Application ID** | `io.flowstate.app` |
| **Version Name** | `1.1.0` |
| **Build Number (`versionCode`)** | `9` |
| **Minimum Android Version** | Android 7.0 (API Level 24) |
| **Target Android Version** | Android 15 (API Level 36) |
| **APK File Size** | `152,668,223 bytes` (~145.6 MB) |
| **SHA-256 Checksum** | `5916451197c5ef6a1ba3dc63c355c76784b698c38613bed0f8a0b51e39039560` |
| **Signing Certificate Fingerprint** | `44:2D:CC:BE:7B:BE:03:CE:CE:AD:59:8B:71:8B:63:C3:CF:A0:CC:24:03:75:C2:AF:32:76:82:DF:63:7E:93:C7` |

---

## 📲 Installation & Update Instructions

### Fresh Installation
1. Tap the **[Download APK](https://github.com/Milindskii/Flowstate-Downloads/releases/download/v1.1.0-build9/Flowstate.apk)** link above directly on your Android phone.
2. Open the downloaded file from your browser's download tray or Files app.
3. If Android displays a prompt stating *"For your security, your phone is not allowed to install unknown apps from this source"*, tap **Settings** and enable **"Allow from this source"**.
4. Tap **Install** and launch Flowstate.

### Updating from an Existing Build
- **Builds 4, 5, 6, 7, and 8:** These builds share the permanent Flowstate release signing key. You can install Build 9 directly over your existing app without uninstalling or losing local data.
- **Legacy Pre-Release (v1.0.0):** If you are running an older test build signed with the debug key, please uninstall it first before installing Build 9 (Android does not permit signature changes during in-place updates).

---

## 🔒 Verification

Always verify the integrity of your downloaded APK before installing:

### Windows (PowerShell)
```powershell
Get-FileHash -Algorithm SHA256 .\Flowstate.apk
```
Confirm the output matches:
`5916451197C5EF6A1BA3DC63C355C76784B698C38613BED0F8A0B51E39039560`

### macOS / Linux
```bash
sha256sum Flowstate.apk
```

---

## 💬 Support & Contact

If you experience any issues, have feedback, or need assistance:

- **Email Support:** [Milindkrishnan24@gmail.com](mailto:Milindkrishnan24@gmail.com)
- **GitHub Issues:** [File a bug or request](https://github.com/Milindskii/Flowstate-Downloads/issues)
- **In-App:** Navigate to **Profile > Legal & Support > Report an Issue** to submit diagnostic reports directly to the team.
