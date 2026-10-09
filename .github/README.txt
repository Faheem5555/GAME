1. Create a GitHub repo, upload everything in this folder (keep .github).
2. Actions tab -> "Build APK" -> run; download artifact SiegeWheels-apk (app-debug.apk).
3. Multiplayer: create a free Firebase project, add Realtime Database (test-mode rules
   {".read":true,".write":true}), paste the web config into CFG in www/index.html.
