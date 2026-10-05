## core: 0.7.7 - 2026-10-01
### :bug: Bug Fixes
- rewrite the async poll progress line in place on an interactive terminal and erase it before the final output, instead of printing a new line on every poll; the root command context is now canceled on interrupt so an interrupted command clears its progress line and exits through the normal error path *(commit by [@AshGodfrey](https://github.com/AshGodfrey))*
