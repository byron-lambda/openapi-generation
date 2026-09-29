## core: 0.4.6 - 2026-09-28
### :bug: Bug Fixes
- report install.ps1 failures with throw instead of exit so a failed install piped into Invoke-Expression no longer closes the calling PowerShell session *(commit by [@2ynn](https://github.com/2ynn))*
