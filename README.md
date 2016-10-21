# cFS: Memory Dwell

[![GitHub release](https://img.shields.io/github/release/lassondesat/cfs-md.svg)](https://github.com/lassondesat/cfs-md/releases)

* [Original README](cfs-md-app-OSS-readme.txt)

## Description

The Memory Dwell application (MD) is a core Flight System (cFS) application that
is a plug in to the Core Flight Executive (cFE) component of the cFS.

The cFS is a platform and project independent reusable software framework and
set of reusable applications developed by NASA Goddard Space Flight Center. This
framework is used as the basis for the flight software for satellite data
systems and instruments, but can be used on other embedded systems. More
information on the cFS can be found at http://cfs.gsfc.nasa.gov

The MD application monitors memory addresses accessed by the CPU. This task is
used for both debugging and monitoring unanticipated telemetry that had not been
previously defined in the system prior to deployment.

## Requirements

* [Operating System Abstraction Layer][osal] 4.1.1 or higher
* [core Flight Executive][cfe] 6.4.1 or higher
* [cFS Application Library][cfs_lib]

## Sources

* https://sourceforge.net/projects/cfs-md/

[osal]: https://github.com/lassondesat/osal
[cfe]: https://github.com/lassondesat/coreflightexec
[cfs_lib]: https://github.com/lassondesat/cfs_lib
