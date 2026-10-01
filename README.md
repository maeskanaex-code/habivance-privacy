# Habivance — Privacy Policy

**Last updated:** October 1, 2026

## Summary

Habivance is an offline-first Android habit tracker. **It does not collect, transmit, or share any personal data.** Everything you create in the app stays on your device.

## What Data Habivance Uses

Habivance stores the following information **locally on your device only**:

- Habit names, emojis, colors, and frequencies you create
- Completion history (the days you mark each habit done)
- Reminder times you configure per habit
- Your app preferences (theme, week start, notification settings, app lock PIN)
- Optional backup files you export yourself (JSON format)

**None of this data is ever sent to any server.** Habivance has no backend, no cloud sync, and no user accounts.

## What Habivance Does NOT Collect

- ❌ No personal information (name, email, phone number)
- ❌ No location data
- ❌ No device identifiers
- ❌ No usage analytics or crash reports
- ❌ No advertising identifiers
- ❌ No contacts, photos, or files
- ❌ No data shared with third parties

## Permissions Habivance Requests

Habivance asks for a small set of Android permissions, each for a specific reason:

| Permission | Why it's needed |
|---|---|
| **POST_NOTIFICATIONS** | To send you reminders at the times you set |
| **SCHEDULE_EXACT_ALARM** | To fire reminders at the exact minute you chose |
| **RECEIVE_BOOT_COMPLETED** | To restore your reminders after your phone restarts |
| **REQUEST_IGNORE_BATTERY_OPTIMIZATIONS** | (Optional) So reminders fire even in battery-saver mode |
| **VIBRATE** | For reminder vibration |
| **USE_BIOMETRIC** | (Optional) For app lock via fingerprint/Face |

**Every permission is optional and can be declined.** The app remains functional without any of them — reminders just may not fire as reliably.

## App Lock (Optional)

If you enable App Lock, your PIN is stored as a **one-way SHA-256 hash** on your device. The plain PIN is never stored or transmitted. Biometric data is handled entirely by Android's system biometric service — Habivance never accesses your fingerprint or Face data.

## Backups

If you use the Export feature, Habivance creates a JSON file at a location **you choose**. This file is under your control. Habivance does not upload it anywhere.

## Third-Party Services

**None.** Habivance does not include any analytics SDKs, advertising SDKs, crash reporting services, or third-party cloud services.

## Children's Privacy

Habivance does not collect any personal information from anyone, including children under 13.

## Changes to This Policy

If this policy changes, the "Last updated" date at the top will reflect the change. Continued use of Habivance after changes means you accept the updated policy.

## Contact

For questions about this privacy policy, contact:

**Mahmoud Shehata**
GitHub: [github.com/maeskanaex-code](https://github.com/maeskanaex-code)

---

*Habivance is an independent, offline-first Android app. Your data is yours.*
