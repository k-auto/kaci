
# Knexyce Package

This repository contains a **Knexyce Package (KP)**.
Knexyce Packages are encrypted archives that provide a way to share, build, and secure data, powered by KGPH.

## What is KGPH (Knexyce GitHub Package Handler)?

**KGPH (Knexyce GitHub Package Handler)** is a lightweight Python tool for managing Knexyce Packages.

## Installing This Package

```bash
python3 kgph.py getpkg -a <author> -p <package_name> -k <encryption_key> -l <download_location>
```

Replace:

* `<author>` -> GitHub username that published the package.
* `<package_name>` -> Repository’s name.
* `<encryption_key>` -> Passphrase used to encrypt the package.
* `<download_location>` -> Folder where the package should be extracted (optional).

Make sure `kgph.py` is installed before installing this package.
