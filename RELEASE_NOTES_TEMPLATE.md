# Erect Banana vX.Y.Z

<!--
  Copy this template when creating a new GitHub Release.
  Drop it into the "Describe this release" box.

  Title format: vX.Y.Z — short tagline (e.g., "v1.1.0 — Faster generation + Mac alpha")
-->

## Highlights

- One-line summary of the headline change
- Second highlight
- Third highlight

## What's new

### Added
- New feature 1
- New feature 2

### Changed
- Behavior change 1 (and why)

### Fixed
- Bug 1: short description (issue #N if applicable)
- Bug 2: short description

### Removed / deprecated
- (only when applicable)

## Downloads

| File | For | Size |
|---|---|---|
| `ErectBanana-X.Y.Z-Setup-Pro.exe` | Standard Adobe Photoshop | ~XX MB |
| `ErectBanana(Portable)-X.Y.Z-Setup-Pro.exe` | Portable / standalone PS | ~XX MB |

**A license key is required to activate.** Buy at [Gumroad ($15)](https://junshaon.gumroad.com/l/erect-banana) or 闲鱼 (¥29-39).

## Install / upgrade

**Fresh install**: download → run installer → done.

**Upgrade from previous version**:
1. Close Photoshop
2. Run the new installer over the existing install (it handles the upgrade)
3. License keys from previous Pro versions remain valid

If you hit any weirdness, run the clean-uninstall first:
```powershell
# (only needed if upgrade misbehaves)
.\clean_uninstall.ps1 -Force
```

## China mirror

国内下载慢：[Gitee Releases](https://gitee.com/shuaige-dev/erect-banana/releases)

## Verify download (optional)

SHA-256 checksums:
```
XXXXXXXXXXXX  ErectBanana-X.Y.Z-Setup-Pro.exe
XXXXXXXXXXXX  ErectBanana(Portable)-X.Y.Z-Setup-Pro.exe
```

Compute locally:
```powershell
Get-FileHash ErectBanana-X.Y.Z-Setup-Pro.exe -Algorithm SHA256
```

## Feedback

- Bug reports: [GitHub Issues](https://github.com/shuaige-dev/erect-banana/issues)
- Feature requests: same
- Pro support: junshaonan@outlook.com
