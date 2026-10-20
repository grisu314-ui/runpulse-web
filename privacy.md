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

RunPulse stores your workouts only on your device. The provider runs no server and does not receive your workouts, your location or your intervals.icu sign in. The app contains no ads, no tracking and no analytics.

## Data the app processes on your device

- Heart rate and the intervals between heartbeats (RR intervals) from your Bluetooth chest strap, its battery level and, if it reports it, where it sits (for example chest). From the RR intervals the app computes the signal quality and, after the workout, a measure of heart rate variability in the run (DFA α1, an estimate).
- Precise location from your device's GPS during a workout, every second through the Fused Location Provider of Google Play services on your device, and the air pressure for the elevation if your device has a barometer and you have not turned it off.
- Times, duration and steps of your workouts and the announcements of the app.
- Your optional answers after a workout: effort, feeling, legs, sleep, complaints and a note.
- Your optional entries in the morning: sleep, fatigue, soreness, stress and mood, and if you like a measurement at rest with the chest strap (RR intervals of 2 minutes lying down, optionally 2 more standing; giving heart rate variability as RMSSD and SDNN, resting heart rate, an estimated breathing rate and the values standing).
- Your planned runs and heart rate zones, which the app fetches from intervals.icu, and, when you load them in the history, your fitness and fatigue (CTL and ATL) of the last year; after uploading a workout its moving time, training load and your fitness and fatigue on that day.
- Your optional profile for the coach (goal, running days, duration, experience, year of birth, terrain, likes, other training, notes on health, wishes), your requests to the coach and what became of its answers, including your answers to its questions. For a request the app also fetches your other activities of the last 4 weeks from intervals.icu (sport, duration, training load, average heart rate, effort, feel).
- Your intervals.icu access token from the sign in and the name intervals.icu gives with it. The token is stored encrypted with a key from the Android Keystore. If you entered an intervals.icu API key in an older version, it is stored encrypted the same way, goes only to intervals.icu and applies until you first sign in via the browser; after that you no longer need it and can revoke it in your intervals.icu settings.

Heart rate, heart rate variability, resting heart rate and your wellbeing entries can be health data. The app processes them only with your explicit consent, which you give in the second to last step of the introduction, and only to guide, record and evaluate your training for you, for example to place your morning values within your own usual range, and to send your entries to intervals.icu when you ask it to. The evaluation happens only on your device, serves your training and is not a diagnosis. RunPulse is not a medical device.

## When data leaves your device

1. **intervals.icu** (intervals.icu Ltd, London, United Kingdom): You sign in to intervals.icu in your browser and allow the app access to calendar, settings, activities and wellness there; with the access token it fetches your planned runs and heart rate zones. When you sign out in the app, it withdraws its access at intervals.icu. A workout goes to intervals.icu only when you upload it; the app then sends the workout file with heart rate, RR intervals, DFA α1, location history, elevation and times. If you answered the questions after the workout, the answers go along as the description of the activity. Your morning entries go to the wellness values of the day at intervals.icu only when you send them: the questions answered, heart rate variability (RMSSD and SDNN) and resting heart rate; breathing rate and the values standing stay on the device. If intervals.icu already has other values for heart rate variability or resting heart rate on that day, the app asks first whether to replace them; for this it reads those values of the day from intervals.icu. When you load your training load in the history, the app fetches your fitness and fatigue of the last year. After an upload it reads moving time, training load, fitness and fatigue of the new activity to show them with the workout. When you ask the coach, it fetches your planned runs of the last 6 weeks, heart rate zones, other activities of the last 4 weeks and fitness and fatigue. When you apply the coach's plan, it creates the runs in your calendar at intervals.icu and deletes those you ticked to be replaced or deleted; when you agree to a proposal for new heart rate zones, it writes them to your settings at intervals.icu. When you apply a starter plan, it creates the plan's runs in your calendar the same way and deletes only those you ticked to be replaced in the preview. If intervals.icu reads a newly created run differently from how the app wrote it, the app deletes that one run again. The [privacy policy of intervals.icu](https://www.intervals.icu/privacy-policy/) applies to its processing.
2. **AI app of your choice (coach)**: When you ask the coach, the app makes a text with your workouts of the last 6 weeks, your answers after the workout, your morning entries and values at rest, training load, planned runs, heart rate zones and your profile including your notes on health; without places, without your sign in data and without identifiers of your account. You hand the text yourself, by sharing or copying, to an AI app of your choice, for example Claude by Anthropic; the app itself sends nothing to an AI. Before that it shows you the whole text and asks once for your consent. If you copy it, it lies in the clipboard of your device, marked as sensitive. The terms and privacy policy of the provider of the AI app apply to its processing; check there whether your chats are used to train its AI, and never share the chat by a public link. You paste the answer into the app yourself or share it to the app.
3. **OpenTopoMap** (opentopomap.org, a privately run project in Germany): Only if you have agreed to the map, the app loads map tiles when you open a report with GPS, share an image with the map or open the map page. On the map page you can zoom and pan; the app then loads further tiles, at most 200 per opened page. Without your consent the report shows the route without a map; you can change the choice in the settings under “Map”. The map service then receives your IP address and the numbers of the tiles, that is the area you are looking at: in the report to within a few hundred meters up to a few kilometers depending on the length of the route, on the map page when zoomed in closely to within a few hundred meters. It does not receive the route itself. OpenTopoMap does not state a privacy policy, the location of its servers or how long it logs requests. The app keeps the tiles in the cache of the device and loads them again after 30 days; Android can clear this cache at any time.
4. **Google Play and Google Play services**: Installation and updates run through Google Play. The app determines your location through Google Play services on your device; RunPulse itself does not send your location to Google. Whether Google Play services send data to Google, for example to determine the location more precisely using Wi-Fi and mobile networks, depends on your device's location settings and Google's terms. If you allowed Android to send usage and diagnostics data, Google receives data on crashes of the app, which the provider sees in the Play Console. Google's privacy policy applies.
5. **Export, sharing and backup**: When you export a workout, save its FIT file or back up all workouts as a ZIP file, the app saves the file where you put it in the Android file dialog, for example in Downloads or with a cloud service. When you share the FIT file or an image of the workout, it goes to the app you choose in the Android share dialog; the FIT file then contains your location history, the image the heart rate curve, steps, date, duration, distance and average heart rate, the map and route only if you switch on "With map" in the dialog; then it shows where you trained. Optionally the export contains no coordinates, only meters relative to the start point. The FIT file and the backup contain the location history; the backup also contains the upload state, your answers after the workout and your morning entries including the measurement at rest and the coach's profile and requests, never your sign in data.
6. **GitHub** (GitHub, Inc.): When you tap “Report a bug” or “Suggest an idea” in the app, the app opens the page at GitHub in the browser. For a bug, the address contains the app version, Android version and phone model so that they appear in the form; GitHub receives them when the page opens. Only what you submit there is published. GitHub's privacy policy applies.
7. **Email to the provider**: When you tap “By email” in the app, the app opens your email app with a message to the provider that contains the app version, Android version and phone model. Only what you send yourself is sent; the provider then receives your email address and your message.

Transfers to intervals.icu, OpenTopoMap and GitHub are encrypted with HTTPS.

## Transfers outside the EU

The provider itself does not transfer any data to countries outside the EU. intervals.icu Ltd is based in the United Kingdom, for which an adequacy decision of the European Commission applies, currently until 27 December 2031; according to intervals.icu, data are processed in Germany and Finland. Google (Google Play, Google Play services) and GitHub (feedback and this website) may transfer data to the USA and rely on the adequacy decision for the EU-US Data Privacy Framework and on standard contractual clauses. If you share a text with an AI app, its provider decides where it is processed; many are based in the USA.

## Backup and new devices

The app excludes its data from cloud backup. If you move to a new device with Android's direct device-to-device transfer, Android may take the data of the app along. You can back up your workouts yourself in the settings under “Data” (see export and backup).

## Legal basis

- **Health data** (heart rate, RR intervals, heart rate variability, resting heart rate, wellbeing entries): your explicit consent under Art. 9(2)(a) and Art. 6(1)(a) GDPR, which you give in the second to last step of the app's introduction. The app cannot be used without it. You can withdraw it at any time with effect for the future by clearing the app's data in the Android settings or uninstalling the app; processing until then remains lawful.
- **The other data in the app and the transfers to intervals.icu** that you start (fetching plans and zones, uploading, sending the morning values): Art. 6(1)(b) GDPR, because they are needed for the functions you use; where health data are transferred, your consent as well.
- **Handing data to an AI app (coach)**: your explicit consent under Art. 9(2)(a) and Art. 6(1)(a) GDPR, which you give before the first request and can withdraw at any time in the coach profile; you start each handover yourself. Writing your runs and, after your consent, your heart rate zones at intervals.icu is started by you with “Apply”: Art. 6(1)(b) GDPR. The same applies to the runs of a starter plan.
- **Map tiles from OpenTopoMap**: your consent under Art. 6(1)(a) GDPR, which you give before the first map and can take back at any time in the settings under “Map”.
- **Storage on your device, Bluetooth and location**: The app stores data on your device and uses the chest strap and location only as far as needed for the functions you use (§ 25(2) no. 2 of the German TDDDG).
- **Crash data through Google Play**: the provider's legitimate interest in a stable app under Art. 6(1)(f) GDPR; whether it is sent is set by you in the Android settings.
- **Emails to the provider**: Art. 6(1)(b) GDPR where they concern the use of the app, otherwise the legitimate interest in answering under Art. 6(1)(f) GDPR.

## Retention and deletion

The app never deletes your workouts by itself. When you uninstall the app or clear its data in the Android settings, all data of the app is removed, including the saved access token; you withdraw the access at intervals.icu with “Sign out” in the app or in the settings of intervals.icu. You delete uploaded workouts in intervals.icu. The provider deletes emails once the matter is settled and no legal duty to keep them applies.

## Your rights

You have the right of access, rectification, erasure, restriction of processing, data portability and objection, and the right to withdraw a consent at any time with effect for the future; processing until then remains lawful. You withdraw consent to health data by clearing the app's data in the Android settings or uninstalling the app; back up your workouts under “Data” first if you want to keep them. You withdraw consent to handing data to an AI app in the coach profile, and consent to map tiles in the settings under “Map”. The provider does not receive your workout data; for data at intervals.icu, contact intervals.icu; you manage the data on your device with the app and with Android.

You may lodge a complaint with any data protection authority, in particular in the country where you live or work (Art. 77 GDPR). The authority responsible for the provider is the Landesbeauftragter für den Datenschutz und die Informationsfreiheit Rheinland-Pfalz, Hintere Bleiche 34, 55116 Mainz, Germany, [datenschutz.rlp.de](https://www.datenschutz.rlp.de/).

## This website

The website is hosted on GitHub Pages (GitHub B.V., Amsterdam, and GitHub, Inc., USA). When you visit, GitHub receives your IP address and technical request details and may log them for security and legal reasons; GitHub decides how long ([GitHub Privacy Statement](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement)). The legal basis is the provider's legitimate interest in providing the site securely (Art. 6(1)(f) GDPR). The site sets no cookies, uses no analytics and loads no fonts or scripts from other servers. Links to GitHub Discussions, GitHub Issues and Google Play lead to those providers' services, whose terms apply.

## Further information

The app makes no automated decisions within the meaning of Art. 22 GDPR; alarms and analyses serve only your training. You are not obliged to provide data; without consent to health data, however, the app cannot be used. RunPulse is intended for adults. The provider has not appointed a data protection officer, as there is no obligation to do so. Material changes appear here with a new date.

## Contact

runpulse@der-asymmetriker.de

Last updated: 20 October 2026
