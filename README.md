# sergeydertan.github.io

Privacy policies and support pages for my apps, served by GitHub Pages at
https://sergeydertan.github.io/.

## Layout
- `_config.yml`: site settings and the values every page uses (developer, the publisher on each store, contact email, each app's privacy policy date, the Mac app's name)
- `index.md`: list of apps
- `multitool/privacy.md`, `multitool/support.md`: privacy policy and help page, English only
- `android-files/privacy.md`, `android-files/support.md`: the same for the Android file transfer app for Mac (PhonePorter; its name is `android_files_name` in `_config.yml`), English only
- `android-files/android-file-transfer-not-working.md`: a troubleshooting page for people whose Mac doesn't see their Android phone, which ends with the app; link the App Store page there at launch

The apps link to these URLs, so don't move pages:
- `/multitool/privacy/`, `/multitool/support/` (Multitool: Settings → Privacy policy, Help & FAQ)
- `/android-files/privacy/`, `/android-files/support/` (Mac app: Help menu and Settings)
- `/android-files/android-file-transfer-not-working/` (linked from the support page; meant to be found by search)

## Before publishing a change
- No value in `_config.yml` may still be a `[TODO: ...]`.
- A privacy policy change gets a new date: `privacy_effective` (Multitool) or `android_files_privacy_effective` (Mac app).
