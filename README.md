![img](https://openzfs.github.io/openzfs-docs/_static/img/logo/480px-Open-ZFS-Secondary-Logo-Colour-halfsize.png)

OpenZFS is an advanced file system and volume manager which was originally
developed for Solaris and is now maintained by the OpenZFS community.
This repository contains the code for running OpenZFS on Linux and FreeBSD.

[![codecov](https://codecov.io/gh/openzfs/zfs/branch/master/graph/badge.svg)](https://codecov.io/gh/openzfs/zfs)
[![coverity](https://scan.coverity.com/projects/1973/badge.svg)](https://scan.coverity.com/projects/openzfs-zfs)

# Official Resources

  * [Documentation](https://openzfs.github.io/openzfs-docs/) - for using and developing this repo
  * [ZoL Site](https://zfsonlinux.org) - Linux release info & links
  * [Mailing lists](https://openzfs.github.io/openzfs-docs/Project%20and%20Community/Mailing%20Lists.html)
  * [OpenZFS site](http://open-zfs.org/) - for conference videos and info on other platforms (illumos, OSX, Windows, etc)

# Installation

Full documentation for installing OpenZFS on your favorite Linux distribution can
be found at the [ZoL Site](https://zfsonlinux.org/).

# Contribute & Develop

We have a separate document with [contribution guidelines](./.github/CONTRIBUTING.md).

We have a [Code of Conduct](./CODE_OF_CONDUCT.md).

# Release

OpenZFS is released under a CDDL license.
For more details see the NOTICE, LICENSE and COPYRIGHT files; `UCRL-CODE-235197`

OpenZFS does not follow a hard/specific release schedule for point releases.
Staging branches do exist however for commits planned to be merged into the next point release (e.g. zfs-x.y.z-staging)

# Supported Kernels
  * The `META` file contains the officially recognized supported Linux kernel versions.
  * Point releases will be tagged as needed in order to support the stable Linux kernel available from kernel.org. 
  * The oldest supported Linux kernel is 2.6.32 due to its prominence in Enterprise Linux distributions.
  * Supported FreeBSD versions are 12-STABLE and 13-CURRENT.
