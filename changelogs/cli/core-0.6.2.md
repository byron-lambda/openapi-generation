## core: 0.6.2 - 2026-09-29
### :bug: Bug Fixes
- flag help and examples: a backticked word in the description is no longer shown as the value placeholder; the options, JSON array, and required hints go on their own line after a multi-line description, and trailing whitespace is trimmed from descriptions; every array flag that takes a JSON array shows the (JSON array) hint, renders a single JSON token in command examples (e.g. '[123]' instead of <value>), and is not marked variadic in --usage *(commit by [@2ynn](https://github.com/2ynn))*
