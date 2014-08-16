## Dockerfile for Core-Distro-Base Image

Base image for all the [regional builds](https://github.com/radial/core-distro).

This base image is the official Ubuntu LTS image plus:

* Multiverse repository enabled
* Bash color support and command completion in terminal
* Locale settings

This particular build is for the American English locale. Alternate locales can
be added upon request.

All resulting images can be found on the
[Docker Index](https://index.docker.io/u/radial/distro/).

### Credits

Some inspiration from [The Dockerfile Project](http://dockerfile.github.io/).
