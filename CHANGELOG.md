# Changelog

All notable changes to Erect Banana will be documented here.
This project follows [Semantic Versioning](https://semver.org/).

## [1.0.0] — 2026-05-24

First public release.

### Added
- AI generative fill via Google Gemini 2.5 Flash Image ("Nano Banana")
- BYOK (Bring Your Own Key) — direct calls to Google AI Studio, no proxy server
- Two install targets:
  - Standard Photoshop installer
  - Portable Photoshop installer
- Two build flavors:
  - Free build (no license validation)
  - Pro build (HWID-bound license validation against author's license server)
- Chinese + English UI
- Auto-start bridge process via Windows Startup folder
- Watchdog: bridge auto-launches when Photoshop opens, exits when PS closes
- Inno Setup installer with silent uninstall support
- Singleton enforcement for `ps_monitor` via named Mutex (no zombie processes)

### Known issues
- macOS not supported in 1.x — planned for v2.0
- Chinese mainland users on certain ISPs may need to use Gitee mirror for fast download
- Gemini API key must be set per-user (cannot be pre-configured by the installer)

### Notes
- License server: HTTPS via license.liangzai.ltd (for webhook intake from foreign payment processors) + HTTP direct IP at 8.137.181.235:5001 (for client validation, bypasses Chinese ISP blocking of unregistered ICP domains)

---

## Release naming convention

- `ErectBanana-X.Y.Z-Setup-Pro.exe` — standard PS, license required
- `ErectBanana(Portable)-X.Y.Z-Setup-Pro.exe` — portable PS, license required

Both Pro builds are published to GitHub Releases (downloads are free, but a license key is required to activate). License keys are sold via Gumroad (international)。

Free builds (no license validation) are built internally for testing but are **not** distributed publicly.
