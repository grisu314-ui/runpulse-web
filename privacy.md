---
title: Privacy policy
lang: en
---

# Privacy policy for the RunPulse app

## Controller

Dirk Rausch<br>
Hintere Fröhnstraße 12, 66849 Landstuhl, Germany<br>
runpulse@der-asymmetriker.de

## Principle

RunPulse stores your workouts only on your device. The provider runs no server and does not receive your workouts, your location or your key. The app contains no ads, no tracking and no analytics.

## Data the app processes on your device

- Heart rate and the intervals between heartbeats (RR intervals) from your Bluetooth chest strap, and its battery level.
- Precise location from your device's GPS during a workout, and the air pressure for the elevation if your device has a barometer and you have not turned it off.
- Times, duration and steps of your workouts and the announcements of the app.
- Your optional answers after a workout: effort, feeling, legs, sleep, complaints and a note.
- Your optional entries in the morning: sleep, fatigue, soreness, stress and mood, and if you like a measurement at rest with the chest strap (RR intervals of 2 minutes, giving heart rate variability as RMSSD and resting heart rate).
- Your planned runs and heart rate zones, which the app fetches from intervals.icu.
- Your personal intervals.icu API key, stored encrypted with a key from the Android Keystore.

Heart rate, heart rate variability, resting heart rate and your wellbeing entries can be health data. The app processes them only to guide and record your workout and to send your entries to intervals.icu when you ask it to. It does not judge them.

## When data leaves your device

1. **intervals.icu** (intervals.icu Ltd, London, United Kingdom): The app fetches your planned runs and heart rate zones with your key. A workout goes to intervals.icu only when you upload it; the app then sends the workout file with heart rate, RR intervals, location history, elevation and times. If you answered the questions after the workout, the answers go along as the description of the activity. Your morning entries go to the wellness values of the day at intervals.icu only when you send them: the questions answered, heart rate variability and resting heart rate. If intervals.icu already has other values for heart rate variability or resting heart rate on that day, the app asks first whether to replace them; for this it reads those values of the day from intervals.icu. The [privacy policy of intervals.icu](https://www.intervals.icu/privacy-policy/) applies to its processing.
2. **OpenTopoMap** (opentopomap.org): Only if you have agreed to the map, the app loads map tiles for the area of your route when you open a report with GPS. Without your consent the report shows the route without a map; you can change the choice in the settings under “Map”. The map service then receives your IP address and the numbers of the tiles, that is the area of your workout, to within a few hundred meters up to a few kilometers depending on the length of the route. It does not receive the route itself. The app keeps the tiles in the cache of the device and loads them again after 30 days; Android can clear this cache at any time.
3. **Google Play**: Installation and updates run through Google Play. If you allowed Android to send usage and diagnostics data, Google receives data on crashes of the app, which the provider sees in the Play Console. Google's privacy policy applies.
4. **Export and backup**: When you export a workout, save its FIT file or back up all workouts as a ZIP file, the app saves the file where you put it in the Android file dialog, for example in Downloads or with a cloud service. Optionally the export contains no coordinates, only meters relative to the start point. The FIT file and the backup contain the location history; the backup also contains the upload state, your answers after the workout and your morning entries including the measurement at rest, never your key.

5. **GitHub** (GitHub, Inc.): When you tap “Report a bug” or “Suggest an idea” in the app, the app opens the page at GitHub in the browser. For a bug, the address contains the app version, Android version and phone model so that they appear in the form; GitHub receives them when the page opens. Only what you submit there is published. GitHub's privacy policy applies.

Transfers to intervals.icu, OpenTopoMap and GitHub are encrypted with HTTPS.

## Backup and new devices

The app excludes its data from cloud backup. If you move to a new device with Android's direct device-to-device transfer, Android may take the data of the app along. You can back up your workouts yourself in the settings under “Data” (see export and backup).

## Legal basis

[to be added]

## Retention and deletion

The app never deletes your workouts by itself. When you uninstall the app or clear its data in the Android settings, all data of the app is removed, including the saved key. You delete uploaded workouts in intervals.icu.

## Your rights

You have the right of access, rectification, erasure, restriction of processing, data portability and objection, and the right to lodge a complaint with a data protection authority. The provider does not receive your workout data; for data at intervals.icu, contact intervals.icu; you manage the data on your device with the app and with Android.

## Contact

[Email address]

Last updated: [date]
