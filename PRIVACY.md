# OnePulse privacy policy

*Last updated: 22 November 2026*

OnePulse is made by Subhash Jha (onesyntax.in). It's built so that your health data stays yours.

## What OnePulse reads

- **Apple Health** (iPhone): the types you allow, such as activity, heart, sleep, workouts, body
  measurements, vitals and nutrition. You choose them in the Health permission sheet and can change
  them any time in Settings › Health.
- **Files you add:** lab report PDFs and photos, and body check-in photos.
- **What you enter:** goals, medications, notes and tape measurements.

## Where it goes

- Your data is stored **on your devices** only. Your iPhone, iPad and Mac share it **directly with
  each other** over your local network or Apple's peer-to-peer Wi-Fi, once you pair them with a
  code, encrypted with a key only your paired devices hold. It is **not** stored in iCloud or any
  other cloud. (Like any app's data, it can be part of your device backups if you make them.)
- OnePulse has **no server**. I (the developer) never receive, see or store your health data.
- There's **no account, no advertising, no analytics and no tracking**, and nothing is sold or shared.
- Lab reports and photos are read **on your device** (Apple's Vision and PDFKit). The weekly review
  is written by Apple Intelligence on your device.
- OnePulse writes to Apple Health only the waist measurements and body-fat estimates you enter,
  and only when you allow it.

## Agents (Mac)

The Mac app includes an MCP server. It runs only when **you** connect an AI agent (such as Claude
or Codex) and that agent starts it. It then reads your local OnePulse data, read-only, and gives it
to that agent. What the agent does with it is governed by that agent's provider. If you don't
connect an agent, nothing is shared.

## Updates

The Mac app checks for updates by downloading a public feed (`appcast.xml`) from GitHub. That
request includes only standard information such as the app version and macOS version, not your data.

## Deleting your data

Delete the app on each device; OnePulse keeps no copy anywhere else. Data you allowed OnePulse to write to Health
stays in Health until you delete it there.

## Not medical advice

OnePulse shows your own data and general information. It is not a medical device and doesn't
diagnose or treat anything. Talk to a doctor about your health.

## Contact

Questions: open an issue at https://github.com/jhasubhash/onepulse-releases/issues.
