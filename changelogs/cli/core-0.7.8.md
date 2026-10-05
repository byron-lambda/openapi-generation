## core: 0.7.8 - 2026-10-01
### :bug: Bug Fixes
- clear the plaintext config.yaml copy of a credential when auth login or configure stores it in the OS keychain, so a previously saved secret no longer lingers on disk; if the keychain later becomes unavailable, the credential must be entered again *(commit by [@2ynn](https://github.com/2ynn))*
