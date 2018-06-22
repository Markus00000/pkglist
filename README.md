# pkglist analyzes installed packages on Arch Linux

## Usage

### pkglist --analyze <pkglist>

Compare a list of packages that should be installed to actually installed packages. See `packages.txt` for an example list.

### pkglist --date

List explicitly installed packages by installation date.

### pkglist --explicit

List explicitly installed packages.

### pkglist --opt

List installed optional dependencies not required by any package.

### pkglist --size

List explicitly installed packages by size excluding the size of their dependencies.

### pkglist --usage

List explicitly installed packages by disk space that would be freed if uninstalled.

## Dependencies

`expac`: `--size` and `--usage`
