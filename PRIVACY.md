# Better Weigh — Privacy Policy

**Effective:** May 9, 2026
**App:** Better Weigh (Android package `com.betterweigh.betterweigh`)
**Developer:** Gold Lumen Softworks (independent developer, T. Hobbs)
**Contact:** https://ko-fi.com/goldlumensoftworks

---

## Summary

Better Weigh is an open, ad-free nutrition and fitness tracker. **All of your
personal health data — food logs, weigh-ins, profile, and step counts — is
stored locally on your device.** It is never sold, shared with advertisers, or
used for marketing. We do not run analytics, tracking SDKs, or fingerprinting.

---

## Data We Collect On-Device (stays on your phone)

The following information is created and stored **only on your device**, in the
app's private storage area:

- **Profile data** you enter: name, sex, age, height, weight, activity level,
  unit preference, and goal.
- **Food log entries:** what you ate, portion sizes, and the resulting calorie /
  macro totals.
- **Weigh-ins:** dates and weights you record over time.
- **Step counts:** daily totals read from your device's step counter sensor or
  from Health Connect (if you grant permission).
- **App settings:** theme, accent color, and display preferences.

This data is **not transmitted to us** in normal use. Uninstalling the app
removes it. You can also export it at any time from inside the app
(Settings → Export Data) as a JSON file you control.

---

## Health Connect (Android)

If you grant the app permission, Better Weigh reads your daily **step count**
from Google Health Connect to show calories burned from walking. Specifically,
the app requests:

- `android.permission.health.READ_STEPS` — daily step totals
- `android.permission.ACTIVITY_RECOGNITION` — fallback for the on-device
  hardware step counter when Health Connect is unavailable

The step count is used **only** to display today's steps and estimated calorie
burn on your home screen, and is saved to the local daily-log file. Step data
is never transmitted off your device unless you choose to use one of the
optional features described below.

You can revoke Health Connect permissions at any time in:
**Settings → Apps → Health Connect → App Permissions** on Android, or by
uninstalling the app.

---

## Optional Features That Send Data Off-Device

Two optional, **off-by-default** features in Better Weigh transmit data to a
relay server operated by Gold Lumen Softworks (`ch.betterweigh.org`). You must
explicitly enable each before any data leaves your device.

### 1. Anonymous Community Health Submission

If you opt in (Settings → Community Health), the app may upload an
**anonymous, aggregated** snapshot containing:

- A randomly generated, locally stored user ID (a UUID — not linked to your
  name, email, phone, or device ID)
- Your age range, sex, height range, weight range, and BMI category
- Aggregate weekly summaries (average calories, average steps)
- App version

This data is used only to compute community-wide health statistics. It is
never sold and contains no direct identifiers. You can opt out at any time;
opting out stops further submissions but cannot retroactively delete already-
submitted anonymous records (because they are not linked to you).

### 2. Bug Reports

If you submit a bug report from inside the app, we transmit:

- The text of your report
- The category you selected
- An optional contact field (only what you type)
- Your random user ID, app version, and OS version

**No log files, food data, or health data are included in bug reports.**

---

## What We Do **Not** Do

- We do **not** sell your data.
- We do **not** show ads.
- We do **not** use third-party analytics, tracking, or advertising SDKs.
- We do **not** share data with insurers, employers, or marketers.
- We do **not** require an account or sign-in.

---

## Data Retention

- **On-device data:** kept until you delete it or uninstall the app.
- **Bug reports:** retained on the relay server only as long as needed to
  triage the issue, then deleted.
- **Anonymous community submissions:** retained indefinitely in aggregated
  form because they are not linked to you and cannot be individually deleted.

---

## Your Rights

You can:

- **Export** your data at any time (Settings → Export).
- **Delete** all on-device data by uninstalling the app or using
  Settings → Wipe Data.
- **Stop transmitting** community / bug data by disabling those features in
  Settings.

For questions or to request deletion of identifiable bug-report records,
contact us via https://ko-fi.com/goldlumensoftworks.

---

## Children

Better Weigh is **not directed to children under 13** (or the equivalent
minimum age in your country). We do not knowingly collect data from children.

---

## Changes

If this policy changes materially, the new version will be published at the
URL above with an updated effective date.

---

## Source Code

Better Weigh is open source. You can review the code at
https://github.com/thobbs265/Better-Weigh.
