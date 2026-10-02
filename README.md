# ReqTone releases

Official installers for **ReqTone**, a native desktop API client for REST,
GraphQL and Server-Sent Events. Website: https://reqtone.com

This repository holds release files only. The application is closed-source and
free to use under the [ReqTone licence](https://reqtone.com/terms).

## Download

Get the latest version from the **[Releases](../../releases/latest)** page or
from https://reqtone.com/download.

| Platform | Status |
|---|---|
| Windows 10 / 11 (x64) | Available — per-user setup `.exe`, no admin rights needed |
| macOS | Not published yet |
| Linux | Not published yet |

## The installer is not code-signed yet

Windows SmartScreen will show "Windows protected your PC". Click **More info**,
check the file name, then **Run anyway**.

## Verify your download

Every release includes `SHA256SUMS.txt`. In PowerShell:

```powershell
Get-FileHash .\ReqTone_<version>_x64-setup.exe -Algorithm SHA256
```

The output must match the hash in `SHA256SUMS.txt` and on
https://reqtone.com/download.

## Issues

Report problems on this repository's Issues tab.
