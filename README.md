# bun-musl
A script and wrapper for running bun on musl libc based linux distributions

<img src="./icon.png" width=256>

## Usage
```bash
$ ./bun-musl
bun-musl: Wrapper for bun.js runtime on musl systems

  install       Installs bun, prepares libraries and patches bun
  upgrade       Upgrades installed bun, works as override for bun upgrade
  patch         Patch allready installed bun

Note:
  bun will run through a wrapper, both the wrapper and this script share the same upgrade function
```
