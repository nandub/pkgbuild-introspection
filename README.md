This is a proof of concept used to extract metadata from PKGBUILDs.

  - pkgbuild_introspection: the actual work is done here
  - introspect: a test driver for pkgbuild_introspection
  - mkaurball: creates a source tarball (ala `makepkg --source`) with a
    generated `.AURINFO` file
  - parse_aurinfo.py: an implementation of an .AURINFO parser
  - compare.py: compares AURINFO to repo data

There's probably bugs, corner cases, and design discussions to be had before
this is more useful.
