# IsctCompanion

A local-first companion for Institute of Science Tokyo schedules, courses and
school services. This is the public download repository maintained by
[@Gliese129](https://github.com/Gliese129) and [@OHNope](https://github.com/OHNope).

## Downloads

Get desktop installers from [Releases](https://github.com/isct-companion/Isct-Companion-App/releases).

| System | Download filename contains | Requirements |
| --- | --- | --- |
| Mac with Apple Silicon | `aarch64-apple-darwin.dmg` | macOS 14 or later |
| Mac with Intel processor | `x86_64-apple-darwin.dmg` | macOS 14 or later |
| Windows PC | `x86_64-pc-windows-msvc.exe` | Windows 10/11, x64; WebView2 |

On Mac, open the disk image and drag the app to Applications. On Windows, run
the installer; it installs WebView2 if needed (an internet connection may be
required). Intel Mac builds currently omit campus-card OCR.

The initial desktop releases are previews. Their installers are not signed or
notarized, so macOS or Windows may display security prompts. Compatibility
listed above is the build target; runtime testing on each system is ongoing.
Check `SHA256SUMS.txt` in the Release to verify downloaded files.

## License and data

The app is proprietary and free for personal use under [LICENSE](LICENSE).
[日本語版](LICENSE.ja.md) governs when the translations differ. Third-party
software keeps its own licenses; notices are bundled in the app and attached
to each Release.

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
