SpeakClear 2.0 — GitHub Pages update

Upload index.html, sw.js, manifest.webmanifest and icon.svg to the root of your existing speakclear repository, replacing the four files. Do not upload README.txt unless desired. Wait for GitHub Actions Pages deployment. Close and reopen the installed app; if necessary clear the site cache.

New feature: Start recognition uses browser SpeechRecognition (where available) to compare recognized German words with the target. The displayed word-match estimate is NOT a pronunciation score. Speech recognition may use a remote service; it may need internet and browser permissions. Record/replay is separate and existing local progress is preserved if site data is not cleared.
