##Introduction

pacopa - a simple script for list old package archives.

Usage: `pacopa [-n=2] [dir]`

### Examples

To list old package archives for each package in `/var/cache/pacman/pkg` except the lastest `3` verions, use:

`pacopa -n 3`

To list old AUR package archives in a custom dir, e.g. `~/.cache/aur`, use:

`pacopa ~/.cache/aur`

In this case only the lastest 2 versions for each package would be filtered out, as `2` is the default number of package archives.
