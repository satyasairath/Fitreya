# Fitreya privacy policy

_Last updated: 28 October 2026_

Fitreya is a food, workout and health-records tracker for iPhone and Android. It is shared with a small group
of friends through Apple's TestFlight and Google Play's internal testing. **Everything you enter is stored only on
your phone.** There are no accounts, no Fitreya servers, no analytics of our own, no advertising and no tracking. On
Android, Google's ML Kit software inside the app sends Google some diagnostic information about how its
features run; see [Fitreya for Android](#fitreya-for-android).

## What leaves your phone

Fitreya never sends your health data, food log, photos, routes or recorded locations to the developer or anyone
else. Only these leave your phone, and each is described in the sections below:

- **Open Food Facts barcode lookups**: when you scan a product that isn't saved on your phone yet, its barcode
  number is sent to the Open Food Facts database (both apps).
- **Map images**: to show a map, the phone downloads the map pictures for the area on screen, from Apple Maps on
  iPhone and from OpenFreeMap on Android. Your route itself is not sent.
- **Google ML Kit diagnostics** (Android only): Google's ML Kit software, used for reading photos, the scanners and
  on-device AI, sends Google diagnostic information about how these features run, such as the phone model, app
  version, a random installation identifier and timings. It contains none of your photos, text, food or health
  data.
- **Strava**, only if you connect your own Strava account: Fitreya signs in and reads your activities.
- **Feedback emails**, only if you write one: "Send feedback" opens your own email app, and you choose whether to
  send it.
- **"Open in Maps"** (iPhone), only when you tap it: that one location opens in Apple Maps or Google Maps.
- **Downloading the on-device AI model** (Android), only if you tap Download: Google's AICore service downloads it.

Apple's TestFlight and Google Play share some testing information with the developer (see below), and your
phone's own backup (iCloud or Google), if you have it turned on, includes the app's data under your control.

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

The developer can't see any of this. It isn't uploaded anywhere by Fitreya. Like any app's data, it is
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
on; calories and heart rate are on by default. A card's route map is also on by default and can show where
the activity started, such as your home; to leave it out, switch off "Route map" under "Show on the card" on
the share screen (Fitreya remembers the choice). Photos are picked with Apple's photo picker, which gives
Fitreya only the photo you choose, not your library; the camera is used only when you tap Take photo. A shared
card is a freshly drawn picture: it carries none of the original photo's location or camera details.

## Apple Intelligence

On iPhones that support it, Fitreya uses Apple's **on-device** language model to read typed meal
descriptions, meal photos and lab report text. This runs on your iPhone; nothing is sent to Apple, the
developer or anyone else. Nutrition values always come from the food databases in the app, never from the
model. Without Apple Intelligence, the app works the same except for these features.

## Internet requests

Fitreya contacts only these services, and only when you use the feature:

- **Open Food Facts** ([world.openfoodfacts.org](https://world.openfoodfacts.org)), when you scan a barcode
  that isn't saved on your phone yet. Only the barcode number is sent. As with any web request, their server
  sees your IP address; see the [Open Food Facts privacy policy](https://world.openfoodfacts.org/privacy).
- **Strava**, only if you connect your own Strava account in Settings. Fitreya signs in with the Strava API
  details you enter, then reads your activities with their detail and keeps them in the app's storage on your
  iPhone, so Workouts can show and analyse them. The API details and Strava's access tokens are stored in your
  iPhone's Keychain. Nothing is sent to Strava apart from these requests. Disconnecting in Settings revokes the access. See
  [Strava's privacy policy](https://www.strava.com/legal/privacy).
- **Apple Maps or Google Maps**, only when you tap "Open in Maps": that one location opens in the app or
  website you pick, under its own privacy policy.

Nothing else is sent.

## TestFlight

Apple's TestFlight shares some information with the developer: your name or email address as invited, when
you install the app, crash reports, and any feedback or screenshots you choose to send. This is handled by
Apple under the [TestFlight terms](https://www.apple.com/legal/internet-services/itunes/testflight/sren/terms.html).
Fitreya itself adds nothing to it.

## Fitreya for Android

The Android app works like the iPhone app: what you enter (food log, targets, your foods and recipes, records and
report files, sleep you log, your profile photo and name) and the activities it reads from Health Connect, Strava
or activity files you import stay in the app's own storage on your phone. There are
no accounts and no Fitreya servers. If Android's backup is turned on, the app's data can be included in your
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
and never used for advertising or for any purpose other than showing you your own data in Fitreya. Fitreya's use
of information received from Health Connect follows the Health Connect permissions policy, including its Limited
Use requirements. You can change the permissions at any time in Health Connect › App permissions › Fitreya.
What Fitreya wrote stays in Health Connect until you delete it there.

### Location

Only while you record a run, walk, ride or hike (Fitreya shows a notification for as long as it records),
Fitreya uses your location to measure distance, pace and climb, and the phone's barometer, where it has one, for
the climb. The route is saved to Health Connect with the workout. Fitreya doesn't use your location at any other
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
the original photo's location or camera details.

### Internet requests

Besides Google's ML Kit diagnostics above, the Android app contacts only these services, and only when you use
the feature:

- **Open Food Facts**, when you scan a barcode that isn't saved on your phone yet: only the barcode number is
  sent (see the iPhone section above).
- **Strava**, only if you connect your own Strava account in Settings: Fitreya signs in with the Strava API
  details you enter and reads your activities, which it keeps on your phone. The API details and access tokens
  are stored encrypted on your phone. Nothing else is sent to Strava; Disconnect revokes the access.
- **OpenFreeMap**, for maps, as above.

**Send feedback** opens your own email app with Fitreya's address filled in; nothing is sent unless you send
that email yourself, and then it is an ordinary email.

### Google Play testing

Google Play shares some information with the developer: your email address if you join the testing, install
statistics, and crash and "app not responding" reports from phones whose owners allow usage and diagnostics
sharing with Google. This is handled by Google under Google Play's terms. Fitreya itself adds nothing to it.

## Deleting your data

Delete entries in the app, or delete the app to remove everything it stored. Anything Fitreya wrote to
Apple Health stays there until you delete it in the Health app; on Android, anything it wrote to Health Connect
stays there until you delete it in Health Connect.

## Children

Fitreya is intended for adults and is not directed at children.

## Changes to this policy

If this policy changes, the updated version will be posted on this page with a new date.

## Not medical advice

Fitreya shows the numbers you enter or import and the reference ranges printed by your lab. It doesn't
diagnose anything. Ask your doctor about your results.

## Contact

Questions: [fit.atreya@gmail.com](mailto:fit.atreya@gmail.com)
