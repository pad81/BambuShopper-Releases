# BambuShopper – Releases

Binary downloads and update feeds of **BambuShopper**, a desktop application that helps you buy Bambu Lab filament, spare parts and
accessories in the official German/EU Bambu Lab shop at the best price (compare with your Spoolman stock, track spare parts, transparent bulk
discount calculation, prepare the official cart – checkout and payment always stay with you).

> **Beta.** All releases here are pre-releases. BambuShopper is an unofficial tool and is **not affiliated with, endorsed or supported by Bambu Lab**.

## Download

Get the latest file from the [Releases](../../releases) page:

| Platform | File |
|---|---|
| Windows 10/11 x64 | `BambuShopper-<version>-win-x64-Setup.exe` (installer) or `…-win-x64-portable.zip` |
| macOS 12+ Apple Silicon | `BambuShopper-<version>-osx-arm64.zip` (contains `BambuShopper.app`) or `…-osx-arm64-Setup.pkg` |

Verify a download with `SHA256SUMS.txt` (`shasum -a 256 -c SHA256SUMS.txt --ignore-missing`, or `Get-FileHash` on Windows).

The builds are **not code-signed** (Windows) / only ad-hoc signed and not notarized (macOS), so the first start shows a SmartScreen or Gatekeeper warning
(Windows: *More info → Run anyway*; macOS: right-click → *Open*, or `xattr -dr com.apple.quarantine /Applications/BambuShopper.app`).

## Updates

BambuShopper checks this repository for newer releases (Settings → Updates; channels *Stable* and *Beta*). The `releases.*.json`, `RELEASES-*`
and `*.nupkg` files in each release are the update feed and must not be renamed.

## Source code

The source code is **not publicly distributed**; this repository only contains binaries, update metadata and this description.

## Security

Please report security problems privately to the repository owner (GitHub: [@pad81](https://github.com/pad81)); see [SECURITY.md](SECURITY.md).
