REPWISE IRON GOLD — reference-inspired UI update on v1.2

REPWISE — GOLD IRON EDITION (theme update on v1.2)
REPWISE — WORKOUT TRACKER (v1.2 functionality)
================================

WHAT'S INCLUDED
- Log strength exercise sets, repetitions, weights, optional RIR, and completion.
- Generate Push/Pull/Legs/Upper/Lower/Full Body sessions using Mix It Up.
- Reusable intelligent variation: compounds first; preference learning from completed logs after six strength sessions; optional accessory supersets and drop sets.
- Log cardio sessions by time and distance.
- Start and edit routines, add custom exercises, and repeat past workouts.
- Browse, search, edit, and delete workout history.
- See estimated 1-rep max, max weight, repetitions, session volume, RIR and near-failure volume charts, plus RIR-versus-volume scatter plots.
- Rest timer, weekly summaries, and lb/kg + mi/km conversion.
- Export JSON backups or CSV data; import a JSON backup.

FASTEST WAY TO TRY IT
Download the separate Repwise_Workout_Tracker.html file and open it in
an ordinary desktop browser. Everything is built into that one file.
The Files app/iPhone preview may not execute interactive HTML correctly,
so for your phone use the installable web-app option below.

USE ON AN IPHONE AS A HOME SCREEN APP
1) Extract the ZIP file. Keep its contents together: index.html,
   styles.css, app.js, manifest.webmanifest, service-worker.js,
   icon.svg and both icon PNGs.
2) Upload those files to a web host with HTTPS. GitHub Pages or Netlify
   are examples; these are third-party services with separate accounts.
3) Open the resulting HTTPS address in Safari on your iPhone.
4) Tap Share > Add to Home Screen > Add.
5) After the first successful load, the service worker caches the app for
   offline use. Keep regular JSON backups.

GITHUB PAGES OPTION (IN A DESKTOP BROWSER)
1) Sign in to GitHub and make a new repository, such as 'repwise-app'.
2) Upload the EXTRACTED files from the ZIP to the repository's top level
   (not the ZIP itself), then commit them.
3) In repository Settings > Pages, choose Deploy from a branch, select
   the main branch and /(root), and save.
4) Open the published https://YOURNAME.github.io/repwise-app/ link.
5) Follow iPhone Safari's Add to Home Screen steps above.

DATA / PRIVACY
- No server, account, or analytics are used by the app itself.
- Data is stored in the browser on EACH device, not synchronized.
- Browsers can remove stored data. Private browsing is not recommended.
- Backup: Settings > Download backup. Restore: Settings > Import JSON.
- Avoid storing sensitive information in exercise/workout notes.
- Republishing/hosting the code doesn't publish your workout records.

LIMITATIONS
- This is a web app, not a native iOS app or an App Store listing.
- No Apple Watch, Apple Health, login, or cloud syncing in this version.
- Actual installation on a physical iPhone has not been tested here.
- A standalone HTML file may not provide reliable storage on iOS.

No build tools, libraries, or API keys are required.


WHAT RIR MEANS
RIR (reps in reserve) = number of additional technically sound repetitions
you estimate you could have completed. RIR=0 means failure; RIR=2 means
approximately two more were possible. Leaving the field blank means
"unknown", not "0". Existing records without RIR remain valid.
Effort-aware charts exclude sets with no RIR from RIR-specific metrics.
The volume-versus-RIR graph is descriptive and is not proof of training
effectiveness, muscle growth, or causation.

UPGRADING
To update an existing hosted web app, replace all hosted app files with
these v1.1 files at the same URL and origin; then reopen online to let the
new service worker update. Do NOT clear browser/site data. Data is stored
locally for that exact origin and browser. Changing domains or opening a
standalone file may create a separate empty storage space. Export a JSON
backup from the older app before upgrading and import it into v1.1 if needed.
Backups stay compatible with the v1 data format.


GOLD THEME UPDATE
- Aged gold and dark gunmetal palette, vintage iron photography, matching gold app icon.
- No changes to workout data schema, import/export, saved routines or log logic.
- Existing records remain locally stored when files are upgraded at SAME origin/browser.
- Data key remains repwise_workouts_v1.
- Export JSON backup before updating; don't clear website data.
- The single-file HTML includes the decorative wallpaper embedded locally.

Cinematic metal plates + riveted frames are decorative; workout stats remain real.
The data key and schema are unchanged. Keep the same website origin to retain workouts; export JSON first.
