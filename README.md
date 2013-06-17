##Introduction

pacopa - a simple script for list old package archives.

Usage: `pacopa [-n=2] [dir]`

* use `-n` to specify the number of latest package archives to exclude for each package, default to `2`
* use `dir` to specify the package dir to scan, default to `/var/cache/pacman/pkg`

### Examples

* `pacopa -n 3`: list old package archives for each package in `/var/cache/pacman/pkg` except the lastest `3` verions.

* `pacopa ~/.cache/aur`: list old AUR package archives in a custom dir `~/.cache/aur`. In this case only the lastest 2 versions for each package would be filtered out.
