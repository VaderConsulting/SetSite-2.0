# SetSite 2.0

VB6 site-settings bag (`SetSite 2.0`): Set Site Wizard / `SetSite2` UI for Siteloc, Siteserver, Policy, and Prtloc; plus local registry demo, remote PolicyDistro, and Getinfo helpers. Open `Setsite2.vbp` or `Mywizard.vbp` (and the Reg - Local / Reg - Remote projects) in the VB6 IDE.

**Source last updated:** 2026-08-27 · **Language:** VB6 · **Target:** VB6 Win32 · **Output:** WinForms exe

_Note: original OneDrive LastWriteTime values were wiped to 2026-08-27 by a zip transfer; date above uses best available evidence (headers/copyright where helpful)._

## Solution structure

| Project | Language | Type | Purpose |
|---------|----------|------|---------|
| `SetSite2` (`Setsite2.vbp`) | VB6 | WinForms exe | Set Siteloc/Siteserver/Policy/Prtloc settings |
| `SetSite2` (`Mywizard.vbp`) | VB6 | WinForms exe | Set Site Wizard UI template |
| `prjRegistry` (`Reg - Local/prjRegistry.vbp`) | VB6 | WinForms exe | Local registry demo helpers |
| `PolDist` (`Reg - Remote/PolicyDistro.vbp`) | VB6 | WinForms exe | Remote policy distribution |
| `PolDist` (`Reg - Remote/Getinfo/Getinfo.vbp`) | VB6 | WinForms exe | Remote registry/Getinfo helper |

## How to open

Open the `.vbp` in Visual Basic 6.0 IDE:
- `Setsite2.vbp` (main Set Site UI)
- `Mywizard.vbp` (Set Site Wizard template)
- `Reg - Local/prjRegistry.vbp` (local registry demo)
- `Reg - Remote/PolicyDistro.vbp` (remote policy distribution)
- `Reg - Remote/Getinfo/Getinfo.vbp` (Getinfo helper)

## Requirements

- Visual Basic 6.0 IDE

## Attribution and provenance

Working copy from my Historical Dev folder `VB/Old/SetSite 2.0`.

## License

MIT © 2026 VaderConsulting for Dave Robinson's code. See `LICENSE`.
