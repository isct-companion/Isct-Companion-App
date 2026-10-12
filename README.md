# IsctCompanion

A local-first companion for Institute of Science Tokyo schedules, courses and
school services. This is the public download repository maintained by
[@Gliese129](https://github.com/Gliese129) and [@OHNope](https://github.com/OHNope).

## Downloads

Get the 1.0 release candidate from [Releases](https://github.com/isct-companion/Isct-Companion-App/releases).

| System | Download filename contains | Requirements |
| --- | --- | --- |
| Mac with Apple Silicon | `aarch64-apple-darwin.dmg` | macOS 14 or later |
| Mac with Intel processor | `x86_64-apple-darwin.dmg` | macOS 14 or later |
| Windows PC | `x86_64-pc-windows-msvc.exe` | Windows 10/11, x64; WebView2 |
| Android | `aarch64-android.apk` | Android 14 or later, arm64 |
| iPhone / iPad | TestFlight; `ios-ipados.ipa` also provided in Releases | iOS / iPadOS 17 or later |

On Mac, open the disk image and drag the app to Applications. On Windows, run
the installer; it installs WebView2 if needed (an internet connection may be
required). Intel Mac builds currently omit campus-card OCR.
On Android, download the signed APK and allow installation from the app used
to open it.

### iOS and iPadOS — TestFlight

Install [TestFlight from the App Store](https://apps.apple.com/app/testflight/id899247664),
then [join the IsctCompanion public beta](https://testflight.apple.com/join/kUZNQHG6).
The first 1.0 RC build becomes installable after Apple processes the upload
and approves external testing.

The IPA in Releases is signed for App Store distribution. Use TestFlight to
install it on an iPhone or iPad; downloading that IPA alone does not install
the app on an arbitrary device.

The 1.0 release candidates are prereleases. Each Release states its signing
and notarization status; unsigned installers may display security prompts.
Compatibility listed above is the build target; runtime testing on each system
is ongoing.

## License and data

The app is proprietary and free for personal use under [LICENSE](LICENSE).
[日本語版](LICENSE.ja.md) governs when the translations differ. Third-party
software keeps its own licenses; notices are bundled in the app.

Workspace data stays on your device. Optional backup uses your own Google
Drive or OneDrive account. School access uses your own school account. Verify
deadlines and academic records in the official university systems.

IsctCompanion is an independent project and is not an official university app.

## Support

Report problems in [Issues](https://github.com/isct-companion/Isct-Companion-App/issues).
Include your app version, operating system and steps to reproduce. Keep
passwords, authentication tokens and private school records out of reports.

This repository contains distribution documents and compiled releases. The
application source and build infrastructure are maintained privately.
