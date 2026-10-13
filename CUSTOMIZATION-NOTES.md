# Carrots P-Manager customization notes

This source tree is based on KeePassDX. Branding changes in this fork:

- App label changed to **Carrots P-Manager**.
- Launcher PNGs updated from the icon supplied by the project owner for both `free` and `libre` variants.
- Default forest theme adjusted to green with carrot-orange accents; alternate themes remain available.
- Base text appearance uses the Android sans font.
- Android application ID changed to `com.carrots.pmmanager` (the internal Kotlin namespace remains unchanged).

## Important licensing note

The upstream project is licensed under GPL-3.0. Keep the original `LICENSE`, copyright notices, and third-party license files. If you distribute modified binaries or source, comply with GPL-3.0 requirements, including providing the corresponding source and license notices. This fork is not an official KeePassDX release.

## Validation

Branding assets and XML/Gradle text were edited conservatively. Run the Gradle build and test tasks in Android Studio or GitHub Actions before installing or distributing an APK. This archive has not been represented as a successfully built APK.
