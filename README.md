# Kalantra releases

Built releases of Kalantra, a studio register for one teacher. The source lives
in a private repository; nothing here is source.

- **`v*` releases** carry the Android APK. Obtainium watches these.
- **`web-*` prereleases** carry signed web bundles, applied by the app over the
  air. Each is verified against a key built into the app before it is used.
- **`manifest.json`** names the current web bundle.
