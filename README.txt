ATLAS & OAK — IRON GOLD EDITION (v2.0)
======================================

A private, offline-friendly strength training, cardio, and daily goals web app.
Working name: Atlas & Oak. Not a trademark or publication clearance opinion.

WHAT'S NEW
- Daily Fundamentals: training or planned rest, protein, calorie range,
  hydration, sleep, and optional mobility; plus user-defined checkbox habits.
- Progress entries, custom numeric targets, water/protein quick-add buttons,
  weekly consistency chart, and a compact home-screen summary.
- Weekly training planner with workout/rest/flexible days and routine choices.
- Adjustable tracking-day reset hour for unusual and overnight schedules.
- Body-weight trend, weekly body-weight averages, measurements, and optional
  progress photos compressed and stored locally in IndexedDB.
- Local safety snapshots after completed workouts, plus manual JSON backups
  that include saved photos if the browser allows accessing them.
- Updated Atlas & Oak branding with the same aged-gold vintage iron look.

RETAINED
- Weight, reps, RIR, cardio, workout history, custom exercise library,
  routines, estimated 1RM, best sets, muscle-group exposure, progression and
  volume charts, adaptive Mix It Up, rest timer and unit conversion.

UPGRADING YOUR CURRENT REPWISE GITHUB PAGES SITE
1. IMPORTANT: In the current Repwise app, open Settings and Download backup.
   Keep the JSON in iCloud Drive or another reliable location.
2. In GitHub, open the repository hosting your old app. Upload/replace the
   files from THIS extracted ZIP at the SAME repository path, on the same
   branch; do not upload the ZIP as a single file or put the files in a nested
   folder. The root must contain index.html, app.js and styles.css.
3. GitHub Pages will redeploy. Return to the SAME GitHub Pages website URL.
   Do not clear your browser/site data or remove the existing Home Screen
   app before checking your workout records.
4. Atlas & Oak intentionally keeps the prior localStorage key
   repwise_workouts_v1 and backup schema version 1 to preserve your data.
5. If history does not appear (for example after changing domains or devices),
   go to Settings > Restore from backup and select the saved JSON file.
6. On your iPhone, refresh or reopen the Home Screen app to fetch the update.

FOR A NEW INSTALLATION
1. Extract the ZIP contents.
2. Upload ALL files (not the ZIP) to a PUBLIC GitHub Pages repository or
   another HTTPS web host, at the same directory level as index.html.
3. Enable GitHub Pages from the main branch and / (root).
4. Open your Pages website in Safari and choose Share > Add to Home Screen.

DATA SAFETY
- Workout history, plans, goals, and measurements are stored locally in the
  browser via localStorage under repwise_workouts_v1 (unchanged on purpose).
- Progress photos are stored separately in this browser's IndexedDB. They are
  compressed for space. The full JSON backup attempts to bundle photos too.
- Photo and safety-copy storage depends on IndexedDB being available.
- A local safety snapshot is NOT a cloud backup; clearing all website data,
  using another device, or losing your phone can erase it.
- Download a JSON backup regularly, especially BEFORE EVERY update.
- There is no login, automatic cloud sync, server data store, or advertising.
- Targets shown on first launch are EXAMPLES, not individualized nutrition,
  hydration, or health advice. Adjust them in Daily > Goals.
- Plan/rest-day completion is automatic; a logged workout also completes
  the training category. Missing goal data means not recorded, not failure.
- 1RM, RIR and set-volume charts are descriptive and not validated measures
  of muscle growth or physiological recovery.

ONE-FILE BROWSER PREVIEW
The separate Atlas_and_Oak_Tracker_v2.html file is a self-contained preview
suitable for testing in a desktop browser. It is not an installable PWA.
For iPhone use, install from the HTTPS-hosted app in this ZIP.

FILES
 index.html             App entry point
 app.js                 Workout + Daily Fundamentals functionality
 styles.css             Vintage Iron Gold theme
 manifest.webmanifest   Home Screen app metadata
 service-worker.js      Offline cache (requires HTTPS)
 icon.svg               Vector app icon
 icon-192.png           Home Screen icon
 icon-512.png           Larger icon
 iron-gold-bg.webp      Textured background
 iron-plate.webp        Cast-iron plate hero artwork
 iron-texture.webp      Repeating industrial metal texture

For private distribution, GitHub Pages is not an access-control system. A
private repository does not by itself make a published Pages website private.
