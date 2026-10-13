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

- Heart rate and the intervals between heartbeats (RR intervals) from your Bluetooth chest strap, its battery level and, if it reports it, where it sits (for example chest). From the RR intervals the app computes the signal quality.
- Precise location from your device's GPS during a workout, and the air pressure for the elevation if your device has a barometer and you have not turned it off.
- Times, duration and steps of your workouts and the announcements of the app.
- Your optional answers after a workout: effort, feeling, legs, sleep, complaints and a note.
- Your optional entries in the morning: sleep, fatigue, soreness, stress and mood, and if you like a measurement at rest with the chest strap (RR intervals of 2 minutes lying down, optionally 2 more standing; giving heart rate variability as RMSSD and SDNN, resting heart rate, an estimated breathing rate and the values standing).
- Your planned runs and heart rate zones, which the app fetches from intervals.icu, and, when you load them in the history, your fitness and fatigue (CTL and ATL) of the last year.
- Your personal intervals.icu API key, stored encrypted with a key from the Android Keystore.

Heart rate, heart rate variability, resting heart rate and your wellbeing entries can be health data. The app processes them only with your explicit consent, which you give at the end of the introduction, and only to guide, record and evaluate your training for you, for example to place your morning values within your own normal range, and to send your entries to intervals.icu when you ask it to. The evaluation happens only on your device and is not a diagnosis.

## When data leaves your device

1. **intervals.icu** (intervals.icu Ltd, London, United Kingdom): The app fetches your planned runs and heart rate zones with your key. A workout goes to intervals.icu only when you upload it; the app then sends the workout file with heart rate, RR intervals, location history, elevation and times. If you answered the questions after the workout, the answers go along as the description of the activity. Your morning entries go to the wellness values of the day at intervals.icu only when you send them: the questions answered, heart rate variability (RMSSD and SDNN) and resting heart rate; breathing rate and the values standing stay on the device. If intervals.icu already has other values for heart rate variability or resting heart rate on that day, the app asks first whether to replace them; for this it reads those values of the day from intervals.icu. When you load your training load in the history, the app fetches your fitness and fatigue of the last year. The [privacy policy of intervals.icu](https://www.intervals.icu/privacy-policy/) applies to its processing.
2. **OpenTopoMap** (opentopomap.org): Only if you have agreed to the map, the app loads map tiles for the area of your route when you open a report with GPS. Without your consent the report shows the route without a map; you can change the choice in the settings under “Map”. The map service then receives your IP address and the numbers of the tiles, that is the area of your workout, to within a few hundred meters up to a few kilometers depending on the length of the route. It does not receive the route itself. The app keeps the tiles in the cache of the device and loads them again after 30 days; Android can clear this cache at any time.
3. **Google Play**: Installation and updates run through Google Play. If you allowed Android to send usage and diagnostics data, Google receives data on crashes of the app, which the provider sees in the Play Console. Google's privacy policy applies.
4. **Export, sharing and backup**: When you export a workout, save its FIT file or back up all workouts as a ZIP file, the app saves the file where you put it in the Android file dialog, for example in Downloads or with a cloud service. When you share the FIT file or an image of the workout, it goes to the app you choose in the Android share dialog; the FIT file then contains your location history, the image only the heart rate curve, steps, date, duration, distance and average heart rate, no map and no route. Optionally the export contains no coordinates, only meters relative to the start point. The FIT file and the backup contain the location history; the backup also contains the upload state, your answers after the workout and your morning entries including the measurement at rest, never your key.
5. **GitHub** (GitHub, Inc.): When you tap “Report a bug” or “Suggest an idea” in the app, the app opens the page at GitHub in the browser. For a bug, the address contains the app version, Android version and phone model so that they appear in the form; GitHub receives them when the page opens. Only what you submit there is published. GitHub's privacy policy applies.
6. **Email to the provider**: When you tap “By email” in the app, the app opens your email app with a message to the provider that contains the app version, Android version and phone model. Only what you send yourself is sent; the provider then receives your email address and your message.

Transfers to intervals.icu, OpenTopoMap and GitHub are encrypted with HTTPS.

## Backup and new devices

The app excludes its data from cloud backup. If you move to a new device with Android's direct device-to-device transfer, Android may take the data of the app along. You can back up your workouts yourself in the settings under “Data” (see export and backup).

## Legal basis

- **Health data** (heart rate, RR intervals, heart rate variability, resting heart rate, wellbeing entries): your explicit consent under Art. 9(2)(a) and Art. 6(1)(a) GDPR, which you give at the end of the app's introduction. The app cannot be used without it. You can withdraw it at any time with effect for the future by clearing the app's data in the Android settings or uninstalling the app; processing until then remains lawful.
- **The other data in the app and the transfers to intervals.icu** that you start (fetching plans and zones, uploading, sending the morning values): Art. 6(1)(b) GDPR, because they are needed for the functions you use; where health data are transferred, your consent as well.
- **Map tiles from OpenTopoMap**: your consent under Art. 6(1)(a) GDPR, which you give before the first map and can take back at any time in the settings under “Map”.
- **Crash data through Google Play**: the provider's legitimate interest in a stable app under Art. 6(1)(f) GDPR; whether it is sent is set by you in the Android settings.
- **Emails to the provider**: Art. 6(1)(b) GDPR where they concern the use of the app, otherwise the legitimate interest in answering under Art. 6(1)(f) GDPR.

## Retention and deletion

The app never deletes your workouts by itself. When you uninstall the app or clear its data in the Android settings, all data of the app is removed, including the saved key. You delete uploaded workouts in intervals.icu. The provider deletes emails once the matter is settled and no legal duty to keep them applies.

## Your rights

You have the right of access, rectification, erasure, restriction of processing, data portability and objection, the right to withdraw a consent at any time, and the right to lodge a complaint with a data protection authority. The provider does not receive your workout data; for data at intervals.icu, contact intervals.icu; you manage the data on your device with the app and with Android.

## Contact

runpulse@der-asymmetriker.de

Last updated: 13 October 2026
