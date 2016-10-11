# genpkg
A script to generate Arch Linux packages from local sources.

You don't want to mess up your sistem with a make install but still are too lazy to
create a PKGBUILD for your sources? This script will make your life easier!

Features:
- Build an Arch Linux package from a Makefile based source directory
- Build and install the package quick n' dirty ('-i')
- Guess package name and version from folder name / git revision
- Optionally modify the generated PKGBUILD (-p) and feed it again (-s)
