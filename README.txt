MY TRACKER - Android app (personal use, not from the Play Store)
=================================================================

INSTALL ON YOUR PHONE
1. Copy MyTracker.apk to your phone (USB cable, Google Drive, or send it to yourself on WhatsApp/email).
2. On the phone, tap the file in Files / Downloads.
3. Android asks to allow installing from that app (Files, Chrome, WhatsApp...). Tap Settings,
   turn on "Allow from this source", go back, and tap Install.
4. If Play Protect warns "Unknown app" or "App not scanned", tap "More details" then "Install anyway".
   This happens with every app that does not come from the Play Store.
5. Open "My Tracker" from your app drawer.

YOUR DATA
- Everything is saved on the phone as you type. The app has no internet permission.
- Tap "Back up" now and then. It saves a copy to Downloads/MyTracker on the phone.
- "Restore backup" loads a backup file (also works with the file from "Save to a file" on your computer).
- The phone app and the computer version (Finance_Tracker.html) keep separate data.
  To move data, use Back up on one and Restore backup / Open data file on the other.

UPDATING THE APP LATER
- After Finance_Tracker.html changes, double-click build.bat. It makes a new MyTracker.apk.
- Install it over the old one. Your entries stay.
- KEEP mytracker-signing-key.p12. Updates must be signed with this same key. If it is lost,
  you must uninstall the old app first, which deletes its data, so back up before that.

FILES
- MyTracker.apk                 the app to install
- build.bat / build_apk.py      rebuild the app
- mytracker-signing-key.p12     your signing key (keep it)
- src, res, AndroidManifest.xml the app wrapper
- Build tools live in C:\Users\is12765\AndroidBuildTools (about 350 MB; only needed for rebuilding)
