# Paraguay Educa Dependencies
Set of files that help create a metapackage, containing the dependencies used to create the iso based on Ubuntu20.04 https://github.com/ParaguayEduca/os-builder

## Debian Information
- **source/format:** Indicates the package format, 3.0 (quilt), used for any Debian package.
- **changelog:** This is the format used by dpkg and other programs to get the version, revision, distribution and urgency of your package.
- **compat:** defines the level of compatibility with debhelper which is the tool used to create the packages.
- **control:** defines the package name, priority, maintainer, dependencies, version, etc. The first lines, up to the blank line, correspond to the information for the source package, while the following lines correspond to the binary package.
- **rules:** defines the rules of what to do