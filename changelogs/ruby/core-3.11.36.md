## core: 3.11.36 - 2026-09-24
### :bug: Bug Fixes
- emit a gem-name entry file when packageName differs from the snake_case module file so Bundler.require and tapioca load the SDK; a name that differs only by case gets no entry file, so keep packageName lowercase for Bundler autoloading on case-sensitive filesystems *(commit by [@AshGodfrey](https://github.com/AshGodfrey))*
