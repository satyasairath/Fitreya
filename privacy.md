# Fitreya privacy policy

_Last updated: 22 November 2026_

Fitreya is a food, workout and health-records tracker for iPhone and Android, free on the App Store and Google
Play. **Everything you enter is stored only on your phone.** There are no accounts, no Fitreya servers, no analytics of our own, no advertising and no tracking. On
Android, Google's ML Kit software inside the app sends Google some diagnostic information about how its
features run; see [Fitreya for Android](#fitreya-for-android).

## What leaves your phone

Fitreya never sends your health data, food log, photos, routes or recorded locations to the developer or anyone
else. Only these leave your phone, and each is described in the sections below:

- **Open Food Facts barcode lookups**: when you scan a product that isn't saved on your phone yet, its barcode
  number is sent to the Open Food Facts database (both apps).
- **Map images**: to show a map, the phone downloads the map pictures for the area on screen, from Apple Maps on
  iPhone and from OpenFreeMap on Android. Your route itself is not sent.
- **The satellite court picture** (iPhone): while "Satellite court picture" is on for a tennis card, opening the share
  screen asks Apple's map service for the satellite picture of the court's area. The request carries the map area only
  (its centre and span, and the picture's size), never your track's points, the heat map or any figure; the heat map
  and the court's lines are drawn on your phone, and Fitreya stores no picture.
- **Google ML Kit diagnostics** (Android only): Google's ML Kit software, used for reading photos, the scanners and
  on-device AI, sends Google diagnostic information about how these features run, such as the phone model, app
  version, a random installation identifier and timings. It contains none of your photos, text, food or health
  data.
- **Strava**, only if you connect your own Strava account: Fitreya signs in and reads your activities. Strava
  activities are kept on this phone for 7 days, then Fitreya deletes Strava's copy, even if you don't open the app (as far
  as your phone lets it run; what came from Apple Health, Health Connect or an activity file stays); Disconnect deletes everything from
  Strava.
  Strava may collect usage data about how Fitreya uses its API (Strava's API Policy §6.5).
- **Feedback emails**, only if you write one: "Send feedback" opens your own email app, and you choose whether to
  send it. Emails to fit.atreya@gmail.com (a Gmail address, so Google also stores them) are copied to the
  developer's computer, where they are kept to fix problems and are read with the help of an AI assistant
  (Anthropic's Claude), and they may get an automatic reply; ask that address to have yours deleted.
- **"Open in Maps"** (iPhone), only when you tap it: that one location opens in Apple Maps or Google Maps.
- **Downloading the on-device AI model** (Android), only if you tap Download: Google's AICore service downloads it.

Apple and Google share some information with the developer: crash reports and usage statistics only if you allow
sharing with app developers in your phone's settings, and, if you test a pre-release version, what TestFlight or
Google Play testing shares (see below). Your phone's own backup (iCloud or Google), if you have it turned on,
includes the app's data under your control.

The sections up to "Internet requests" describe the iPhone app; the Android app is described in its own section
below.

## What Fitreya stores, and where

| What | Where it stays |
|---|---|
| Food log, targets, your foods and recipes, saved barcode products | In the app's storage on your iPhone |
| Blood pressure, glucose, HbA1c, lipid and other test results you enter or import | In the app's storage on your iPhone |
| Lab report files and photos you import | In the app's storage on your iPhone, with the results read from them |
| Meal, label and barcode photos | Kept with the food entry they were used for, so you can see them later |
| Your profile photo and name, if you add them | In the app's storage on your iPhone (the photo is saved small, 512 × 512); the photo shows on a share card only when you turn that on |
| A photo you put behind a share card | Not stored: it is used to draw that one card and forgotten when you close the share screen |
| GPS routes of runs, walks, rides and hikes you record | Saved to Apple Health with the workout |
| Activities read from Apple Health, Strava or activity files you import, with their detail (route, heart rate, pace, laps) | In the app's storage on your iPhone, so Workouts can show and analyse them |
| Recipe photos and recipe text you import | In the app's storage on your iPhone, with the recipe |
| Dictated recipes | Speech is turned into text on the iPhone (Apple's on-device dictation model; iOS downloads the model once); no audio is recorded or kept |
| A note you type for a share card (how it felt, where, the weather) | In the app's storage on your iPhone, with that workout or day; a workout's is deleted with the workout, a day's stays on this phone for 90 days, or until you clear it that day or delete the app; never written to Apple Health, never given to the on-device AI |
| A tennis workout's court positions from its Apple Health route | In the app's storage on your iPhone, with the session, until the session is deleted |

The developer can't see any of this. It isn't uploaded anywhere by Fitreya. Your lab results, and the reports
they were read from, are kept on your phone; Fitreya never sends them to the developer or anyone else. A result
leaves the phone only on a share card where you switch it on, or in Apple Health for the blood pressure and
glucose readings Fitreya writes there. Like any app's data, it is
included in your iPhone backups (iCloud Backup or a computer backup) if you have those turned on. Those
backups are controlled by you and Apple.

## Apple Health

With your permission, Fitreya reads workouts (with their routes, laps and segments, and the running form,
power and cadence an Apple Watch records), steps, flights climbed, heart rate, active energy, blood pressure and blood
glucose from Apple Health. It writes the energy, protein, carbs, fat and fibre of meals you log, and the blood
pressure, pulse and glucose readings you enter. You can change or turn off these permissions at any time in
Settings › Apps › Health › Data Access & Devices › Fitreya, or from your profile in the Health app. Use
Change Access to choose what Fitreya can read and write, or Turn Off All to stop it entirely. Health data is
never used for advertising or shared with anyone.

## Location and motion

Only while you record a run, walk, ride or hike, Fitreya uses your location to measure distance, pace and
climb, the iPhone's motion sensor (walking, running, cycling or still) to pause automatically when you stop, and
its barometer to measure how much you climbed (floors).
The route is saved to Apple Health with the workout. Nothing about your location or movement is sent anywhere
by Fitreya. The map on the recording screen and on workout details is Apple Maps (MapKit), which loads map
images from Apple like the Maps app does.

## Share cards

Share cards are images Fitreya draws on your iPhone. Nothing is shared unless you choose an app in the
share sheet or tap Save to Photos (which only adds the picture to your library; Fitreya can't read your
photos). A card you save to Photos may sync to iCloud Photos if you have that turned on, and health figures
(weight, body fat and BMI, blood pressure, glucose and lab values) appear on a card only when you switch them
on; calories and heart rate are on by default. A card's route map, which can show where the activity started
(such as your home), is off unless you switch on "Route map" under "Show on the card" on the share screen;
Fitreya remembers the choice. A card can include workouts and figures that came from Strava (a Strava workout's
card, a day card with a Strava workout on it, a figure Strava supplied): the share screen says so when it does,
nothing is sent by Fitreya, only by you through the share sheet, and such a card carries the "Powered by Strava"
logo. A tennis card can carry a satellite picture of the court, which shows where you play: it is on unless you
turn off "Satellite court picture" (with positions that came from Strava, only once you have answered that your
Strava hides nothing). While it is on, opening the share screen asks Apple's map service for the satellite picture
of the court's area; the request carries the map area only (its centre and span, and the picture's size), never
your track's points, the heat map or any figure; the heat map and the court's lines are drawn on your phone, and
Fitreya stores no picture. A Strava workout's route and court can be drawn on a card for the 7 days Fitreya holds
them, by your answer to one question the first time such a card opens (for a route, when you turn "Route map" on),
"Does your Strava hide the start and end of your activities?" (closing it saves nothing): hides nothing → the route
and the satellite court as any other workout's; hides 200 m or more → the court drawing only, and the route without
the same stretch at each end; hides the whole map, or an activity marked "Only You" on Strava → the court drawing
only and no route. The answer is the setting "What Strava hides on your maps" under Settings › Strava. You can add a
note of your own to a workout's or the day's card (how it felt, where, the weather): it is kept on this phone with
that workout or day (a workout's note is deleted with the workout; a day's stays on this phone for 90 days, or until you clear it
that day or delete the app), never written to Apple Health, never sent anywhere except on a card you share, and never given to the on-device AI. Photos are
picked with Apple's
photo picker, which gives
Fitreya only the photo you choose, not your library; the camera is used only when you tap Take photo. A shared
card is a freshly drawn picture: it carries none of the original photo's location or camera details.

## Apple Intelligence

On iPhones that support it, Fitreya uses Apple's **on-device** language model to read typed meal
descriptions, meal photos and lab report text. This runs on your iPhone; nothing is sent to Apple, the
developer or anyone else. Nutrition values always come from the food databases in the app, never from the
model. No data from Strava is ever given to the model. Without Apple Intelligence, the app works the same except
for these features.

## Internet requests

Fitreya contacts only these services, and only when you use the feature:

- **Apple's map service**, for the map pictures of the area on screen and, on a tennis share card while "Satellite
  court picture" is on, the satellite picture of the court's area (see "What leaves your phone": the request carries
  the map area only).
- **Open Food Facts** ([world.openfoodfacts.org](https://world.openfoodfacts.org)), when you scan a barcode
  that isn't saved on your phone yet. Only the barcode number is sent. As with any web request, their server
  sees your IP address; see the [Open Food Facts privacy policy](https://world.openfoodfacts.org/privacy).
- **Strava**, only if you connect your own Strava account in Settings. Before Strava's sign-in page opens, Fitreya
  shows what it reads and keeps, and connects only if you tap Continue. Fitreya signs in with the Strava API
  details you enter, then reads your activities with their detail and keeps them in the app's storage on your
  iPhone, so Workouts can show and analyse them, shown only to you. Strava activities are kept on this phone for 7
  days, then Fitreya deletes Strava's copy (even if you don't open the app, as far as iOS lets it run; an activity
  that also came from Apple Health or an activity file keeps that copy), and an activity you delete on Strava is
  deleted here too when Fitreya next checks (when it syncs, at most every 12 hours). The API
  details and Strava's access tokens are stored in your iPhone's Keychain. Nothing is sent to Strava apart from
  these requests. Disconnecting in Settings revokes the access, deletes everything from Strava on this iPhone at
  once and confirms it on screen with the date. Strava may collect usage data about how Fitreya uses its API
  (Strava's API Policy §6.5). See [Strava's privacy policy](https://www.strava.com/legal/privacy).
- **Apple Maps or Google Maps**, only when you tap "Open in Maps": that one location opens in the app or
  website you pick, under its own privacy policy.

Nothing else is sent.

## The App Store and TestFlight

Apple shares with the developer the crash reports and usage statistics of the App Store version only if you have
allowed sharing with app developers (Settings › Privacy & Security › Analytics & Improvements); Fitreya itself
adds nothing to them. If you test a pre-release version through Apple's TestFlight, TestFlight shares some
information with the developer: your name or email address as invited, when you install the app, crash reports,
and any feedback or screenshots you choose to send. This is handled by Apple under the
[TestFlight terms](https://www.apple.com/legal/internet-services/itunes/testflight/sren/terms.html).
The developer copies the crash reports, screenshots and comments you send through TestFlight or Google Play to
their own computer, where they are kept to fix problems and are read with the help of an AI assistant
(Anthropic's Claude); ask fit.atreya@gmail.com to have yours deleted.

## Fitreya for Android

The Android app works like the iPhone app: what you enter (food log, targets, your foods and recipes, records and
report files, sleep you log, your profile photo and name) and the activities it reads from Health Connect, Strava
or activity files you import stay in the app's own storage on your phone. There are
no accounts and no Fitreya servers. Your lab results and report files stay on your phone; Fitreya never sends them
to the developer or anyone else. A result leaves the phone only on a share card where you switch it on, or in
Health Connect for the blood pressure and glucose readings Fitreya writes there. If Android's backup is turned on, the app's data can be included in your
phone's backup to your Google account, which you and Google control.

### Health Connect

With your permission, Fitreya reads from Health Connect: steps, heart rate, exercise sessions with their
distance, speed, power and cadence, active calories, weight, body fat, hydration, blood pressure, blood glucose,
resting heart rate, heart-rate variability, VO₂ max, sleep, respiratory rate, floors climbed and mindfulness
sessions. If you also allow access to past data, it reads data older than 30 days, so it can show a year of
weight, VO₂ max and steps and two years of blood pressure and glucose readings; without it, those screens show a
shorter history. Another app's workout route is read only when you tap "Load the route" for that workout and
Health Connect asks you. Fitreya reads Health Connect only while the app is open.

Fitreya writes to Health Connect what you log or record in it: the food (nutrition) and drinks (hydration) you
log, workouts you record or log with their route, distance, active calories and climb (elevation gained), weight,
blood pressure with its pulse (heart rate), blood glucose, sleep and mindfulness sessions.

Health data from Health Connect stays on your phone. It is never sent to the developer or anyone else, never sold,
and never used for advertising or for any purpose other than showing you your own data in Fitreya (a figure from it
leaves the phone only on a share card you make and send yourself: see Share cards below). Fitreya's use
of information received from Health Connect follows the Health Connect permissions policy, including its Limited
Use requirements. You can change the permissions at any time in Health Connect › App permissions › Fitreya.
What Fitreya wrote stays in Health Connect until you delete it there. The same lists, with why each kind of data
is read or written, are in the app: Settings › Connections & data › "Health Connect and your privacy", the screen
Health Connect's own privacy-policy link for Fitreya opens.

### Location

Only while you record a run, walk, ride or hike (Fitreya shows a notification for as long as it records),
Fitreya uses your location to measure distance, pace and climb, and the phone's barometer, where it has one, for
the climb. While it records, Fitreya holds a "wake lock" (Android's WAKE_LOCK permission, which asks nothing of you)
that keeps the recording going while the screen is off; it is released when you stop. The route is saved to Health
Connect with the workout. Fitreya doesn't use your location at any other
time and doesn't send it anywhere.

### Maps

Maps on the recording screen, on workout details and on share cards are drawn from OpenFreeMap
([openfreemap.org](https://openfreemap.org)), with map data © OpenStreetMap contributors. To show a map, the
phone downloads the map pictures for the area on screen, so OpenFreeMap's servers see which area is shown and
your IP address, as with any web request. Your route and other data are not sent.

### Photos, scanners and on-device AI (Google ML Kit)

Reading text from photos (nutrition labels, recipes, lab reports), the document scanner, the barcode scanner and,
on phones that have Gemini Nano, reading a typed meal, all run on your phone: the photos, the text and the results
stay on the phone. The camera is used through your phone's camera app or Google's document scanner, and photos
through Android's photo picker, which gives Fitreya only the photos you choose.

These features use Google's ML Kit, and Google's ML Kit sends Google diagnostic information about how they run:
the phone's maker, model and Android version, the app's name and version, a random identifier for this
installation (for Gemini Nano features also user, device or other identifiers), and figures such as how long a
step took, its settings and any error codes; for the barcode scanner also the zoom steps and where the barcode
was in the frame. It is sent over an encrypted connection, and Google says it doesn't pass it on to third
parties; see [Google's ML Kit data disclosure](https://developers.google.com/ml-kit/android-data-disclosure).
If you download the Gemini Nano model (Settings › Privacy & app › On-device AI), Google's AICore service downloads it.

### Share cards

Share cards are pictures drawn on your phone, shared only when you choose an app in Android's share sheet or tap
Save to Photos (which saves the picture to Pictures › Fitreya). A shared card is a freshly drawn picture without
the original photo's location or camera details. A card's route map, which can show where the activity started
(such as your home), is off unless you switch on "Route map" under "Show on the card" on the share screen;
Fitreya remembers the choice. A card can include workouts and figures that came from Strava (a Strava workout's
card, a day card with a Strava workout on it, a figure Strava supplied): the share screen says so when it does,
nothing is sent by Fitreya, only by you through the share sheet, and such a card carries the "Powered by Strava"
logo. Strava's route is not drawn on a card in this version: a route map comes only from your phone's own recording or
your activity file. No data from Strava is ever given to the on-device AI. You can add a note of your own to a
workout's or the day's card (how it felt, where, the weather): it is kept in the app's own storage on this phone with
that workout or day (a workout's note is deleted with the workout; a day's stays on this phone for 90 days, or until you clear it that
day or delete the app), never written to Health Connect, never sent anywhere except on a card you share, and never given to the on-device AI.
A workout's card has four layouts (Classic, Photo band, Route art and Corner); the three besides Classic draw your route's shape as a
line without a map, from the route kept with the workout on your phone (your recording, your activity file, or the one read from
Health Connect; never Strava's), and ask nothing of any map service.

### Internet requests

Besides Google's ML Kit diagnostics above, the Android app contacts only these services, and only when you use
the feature:

- **Open Food Facts**, when you scan a barcode that isn't saved on your phone yet: only the barcode number is
  sent (see the iPhone section above).
- **Strava**, only if you connect your own Strava account in Settings: before Strava's sign-in page opens, Fitreya
  shows what it reads and keeps, and connects only if you tap Continue. It signs in with the Strava API
  details you enter and reads your activities, which it keeps on your phone for 7 days, shown only to you, then
  deletes Strava's copy (even if you don't open the app, as far as Android lets it run; an activity that also came
  from Health Connect or an activity file keeps that copy); an activity you delete on Strava is deleted here too when
  Fitreya next checks (when it syncs, at most every 12 hours). The API details and access
  tokens are stored encrypted on your phone. Nothing else is sent to Strava; Disconnect revokes the access,
  deletes everything from Strava on this phone at once and confirms it on screen with the date. Strava may collect
  usage data about how Fitreya uses its API (Strava's API Policy §6.5).
- **OpenFreeMap**, for maps, as above.

**Send feedback** opens your own email app with Fitreya's address filled in; nothing is sent unless you send
that email yourself, and then it is an ordinary email. Like every email to that address, it is kept on the
developer's computer and read with the help of Anthropic's Claude (see "What leaves your phone").

### Google Play

Google Play shares some information with the developer: install statistics, and crash and "app not responding"
reports from phones whose owners allow usage and diagnostics sharing with Google; if you join a test of a
pre-release version, also your email address. This is handled by Google under Google Play's terms. Fitreya itself
adds nothing to it.
The developer copies the crash reports, screenshots and comments you send through TestFlight or Google Play to
their own computer, where they are kept to fix problems and are read with the help of an AI assistant
(Anthropic's Claude); ask fit.atreya@gmail.com to have yours deleted.

## Deleting your data

Delete entries in the app, or delete the app to remove everything it stored. Anything Fitreya wrote to
Apple Health stays there until you delete it in the Health app; on Android, anything it wrote to Health Connect
stays there until you delete it in Health Connect.

**Strava:** Disconnect in Settings › Strava deletes everything Fitreya kept from Strava on your phone at once and
confirms it on screen with the date; you can also remove Fitreya on strava.com › Settings › My Apps. Or email
[fit.atreya@gmail.com](mailto:fit.atreya@gmail.com) and the developer will explain how; the developer holds no
copy of your data to delete.

## Your rights

Fitreya processes your data on your own phone, with your consent (you choose what to enter, which permissions to
give and whether to connect Strava). The developer receives none of your health, food or activity data: only an email you
choose to send, the crash reports and statistics Apple or Google pass on if you allow them, and what TestFlight or
Google Play testing shares if you test a pre-release version (see above).
You can see, correct and delete your data in the app at any time, withdraw your consent by turning off a permission
or disconnecting Strava (or by deleting the app), and contact the developer at
[fit.atreya@gmail.com](mailto:fit.atreya@gmail.com) with any question about your data. You also have the right to
complain to your data-protection supervisory authority.

## Children

Fitreya is intended for adults and is not directed at children.

## Changes to this policy

If this policy changes, the updated version will be posted on this page with a new date.

## Not medical advice

Fitreya shows the numbers you enter or import and the reference ranges printed by your lab. It doesn't
diagnose anything. Ask your doctor about your results.

## Contact

Questions: [fit.atreya@gmail.com](mailto:fit.atreya@gmail.com)
