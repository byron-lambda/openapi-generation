## core: 3.13.57 - 2026-09-01
### :bug: Bug Fixes
- serialize optional-nullable fields in multipart and urlencoded bodies as their bare value, transmitting explicit null only for JSON-tagged fields, and skip typed-nil wrapped pointers in deepObject parameters *(commit by [@AshGodfrey](https://github.com/AshGodfrey))*
