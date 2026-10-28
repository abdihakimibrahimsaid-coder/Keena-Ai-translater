KEENA AI TRANSLATOR — FIRST VERSION

This is an installable Android-friendly Progressive Web App (PWA), not a compiled APK.
It provides:
- Online text translation
- Browser speech recognition (Chrome on Android; availability/languages depend on device)
- Image text extraction (OCR; downloads its engine from the internet)
- Turn-taking conversation mode
- Paste copied messages from other apps

Translation service:
Uses Google's public web translation endpoint. This is an unofficial endpoint and can change, limit, or stop working. It does not require a key in this prototype. For a reliable production app, use a supported translation API with a backend and API key.

INSTALL ON ANDROID:
1. Unzip this folder.
2. Host the folder on an HTTPS website (for example, GitHub Pages or Netlify). A PWA cannot be properly installed from a local file:// address.
3. Open the hosted URL in Chrome on Android.
4. Tap Chrome's ⋮ menu > Install app (or Add to Home screen).
5. Confirm. Keena will appear on your home screen.

CAMERA/OCR:
Choose the photo input, take/select a picture, tap Read image text, review the extracted text, then Translate recognized text.

VOICE:
Allow microphone access when prompted. Speech recognition needs compatible browser services and internet. The first prototype uses the selected source language; Auto detect currently defaults speech recognition to English.

MESSAGES:
Android doesn't permit an ordinary app to read other apps' messages silently. Copy the message in the other app, open Keena, then paste. Clipboard access may require permission or manual paste.

This is a prototype, not a native APK. To publish a native Android APK, wrap it with Capacitor or build a native app, then configure permissions and API services.
