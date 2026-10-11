# LoggedOnUsers

VB6 Logged On Users utility (`LoggedOn.exe`) that lists domain computers via WinNT ADSI (optional name filter), then queries each with WMI `Win32_ComputerSystem` for the interactive `UserName`, shown in a list and TreeView. Open `LoggedOn.vbp` in the VB6 IDE.

**Source last updated:** 2026-08-27 · **Language:** VB6 · **Target:** VB6 Win32 · **Output:** WinForms exe

## Solution structure

| Project | Language | Type | Purpose |
|---------|----------|------|---------|
| `Project1` (`LoggedOn.vbp`) | VB6 | WinForms exe | Project1 |

## How to open

Open the `.vbp` in Visual Basic 6.0 IDE:
- `LoggedOn.vbp`

## Requirements

- Visual Basic 6.0 IDE
- Registered OCX/DLL dependencies referenced by the `.vbp` (may need to be installed separately):
  - `MSCOMCTL.OCX`

## Attribution and provenance

Working copy from my Historical Dev folder `VB/LoggedOnUsers`.
Company names in `.vbp` files: Freelance.

## License

MIT © 2026 Vader Consulting for Dave Robinson's code. See `LICENSE`.
