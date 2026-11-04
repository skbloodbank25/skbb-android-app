# SKBB Android APK Project

Capacitor wrapper for the live Samaj Kallyan Blood Bank application.

- Live app: https://broad-brook-9ad5.skbloodbank25.workers.dev/
- Android application ID: `org.samajkallyan.bloodbank`
- App name: `Samaj Kallyan Blood Bank`
- Website hosting: Cloudflare Workers
- Backend: Existing Supabase project

## Build
The GitHub Actions workflow builds a debug APK. Open **Actions**, run **Build SKBB Android APK**, then download the `SKBB-Android-Debug-APK` artifact.

The Android app loads the live hosted website, so online content updates are served from Cloudflare without rebuilding the APK. Internet access is required. This debug APK is for testing/sideloading; Play Store release requires signing configuration.
