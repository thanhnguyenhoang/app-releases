# App Releases & OTA Config

Public OTA configuration and APK release repository for personal apps.

## Structure
- `sports-live/domains.json`: Dynamic domains, worker proxy, and OTA manifest for **Sports Live**.

## Release Naming Convention
- Tag: `<app-slug>-v<version>` (e.g. `sports-live-v1.0.9`)
- Asset: `<app-slug>-<version>.apk` (e.g. `sport-live-1.0.9.apk`)
- In each app's config JSON, point `apk_url` directly to the tag download URL:
  `https://github.com/thanhnguyenhoang/app-releases/releases/download/<tag>/<asset>.apk`
