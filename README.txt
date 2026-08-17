COMPLETE VTO WEBSITE — MAC QUICK START

This package contains the complete webpage, not only the eyeglass images.

Contents
- index.html: the full virtual try-on webpage and JavaScript code
- Start VTO.command: one-click Mac local server launcher
- frames/: three local transparent PNG frame assets
- README.txt: these instructions

The three frames have no visible temple arms. Silver Aviator uses clear lenses rather than sunglass lenses.

Option 1 — easiest
1. Keep the entire folder together after unzipping.
2. Double-click “Start VTO.command”.
3. If macOS blocks it, right-click the file and choose Open.
4. Keep the Terminal window open.
5. In the browser, click “Start virtual try-on” and allow camera access.

Option 2 — Terminal
1. Open Terminal.
2. Type cd followed by one space.
3. Drag this complete website folder into Terminal and press Return.
4. Run: python3 -m http.server 8000
5. Open: http://localhost:8000
6. Stop the server with Control+C.

Important notes
- Do not open index.html through a file:/// address when testing the camera.
- The first MediaPipe face-tracking model load requires an internet connection.
- Chrome or Safari is recommended.
- For Prolific, upload the entire folder structure to an HTTPS host. Do not upload index.html without the frames folder.
