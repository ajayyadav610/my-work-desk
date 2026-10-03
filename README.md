# My Work Desk

A personal, offline-first work tracker for the phone: daily updates from people, case ATR follow-ups, bulletin and report items, social media posts, and tasks.

Live app: https://ajayyadav610.github.io/my-work-desk/

## Install on Android

1. Open the link above in Chrome (needs internet only this first time).
2. Tap ⋮ (top right), then **Install app** or **Add to Home screen**.
3. Open it from the new icon. It works without internet from now on.

## Where the data lives

Everything is saved only on the phone (IndexedDB). Nothing is sent to any server, and this repository holds no data.
Use **Settings → Save backup file** every week, and **Import backup** to restore or move to a new phone.

## Files

- `index.html`: the whole app
- `sw.js`: keeps the app working offline (bump `VERSION` on every release)
- `manifest.webmanifest`, `icons/`: home-screen install
