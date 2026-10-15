# MPICH

> Anticloud offline package — upstream: pmodels/mpich @ `main`.

## What This Project Does

Official MPICH Repository

**Topics:** c, fortran, hpc, mpi

## Upstream README

# MPICH

MPICH is a high-performance and widely portable implementation of the Message Passing Interface (MPI) standard from the Argonne National Laboratory. This implementation provides all MPI functions and features required by the standard with comprehensive support for parallel computing applications.

MPICH is widely adopted by multiple vendor partners including Intel, Hewlett Packard Enterprise (HPE), ParTec, Ohio State University (X-ScaleSolutions), and has been deployed on many Top 500 HPC systems.

This README file should contain enough information to get you started with MPICH. More extensive installation and user guides can be found in the doc/installguide/install.pdf and doc/userguide/user.pdf files respectively in the release tarball, or the doc/wiki in the source code.

[![OpenSSF Best Practices](https://www.bestpractices.dev/projects/10611/badge)](https://www.bestpractices.dev/projects/10611)

## Table of Contents

1. [Getting Started](#1-getting-started)
2. [CH4 Netmods](#2-ch4-netmods)
3. [GPU Support](#3-gpu-support)
4. [Threading Supports](#4-threading-supports)
5. [Testing the MPICH Installation](#5-testing-the-mpich-installation)
6. [Reporting Installation or Usage Problems](#6-reporting-installation-or-usage-problems)
7. [Developer Builds](#7-developer-builds)
8. [Compiler Flags](#8-compiler-flags)
9. [Multiple Fortran Computer Support](#9-multiple-fortran-computer-support)
10. [ABI Compatibility](#10-abi-compatibility)
11. [Citing MPICH](#11-citing-mpich)

---

## 1. Getting Started

**Note:** this guide assumes you are building MPICH from a release tarball. If you are starting from a git checkout, you will need a few additional steps. Please refer to the [wiki page](https://github.com/pmodels/mpich/blob/main/doc/wiki/Index.md).

The following instructions take you through a sequence of steps to get the default configuration (CH4 device with OFI network module, Hydra process management) of MPICH up and running.

### Prerequisites

You will need the following prerequisites:

- **REQUIRED**: The MPICH source tarball
- **REQUIRED**: Perl
- **REQUIRED**: A C compiler (C99 support is required. See [Shifting Toward C99](https://github.com/pmodels/mpich/blob/main/doc/wiki/source_code/Shifting_Toward_C99.md), C11 is preferred for C11 Atomics)

- **OPTIONAL**: A C++ compiler, if C++ applications are to be used (g++, etc.). If you do not require support for C++ applications, you can disable this support using the configure option `--disable-cxx` (configuring MPICH is described in step 1(d) below).
- **OPTIONAL**: A Fortran compiler, if Fortran applications are to be used (gfortran, ifort, etc.). If you do not require support for Fortran applications, you can disable this support using `--disable-fortran` (configuring MPICH is described in step 1(d) below).
- **OPTIONAL**: Python 3. Python 3 is needed to generate Fortran bindings.

**Note:** For users of csh and tcsh shells, please refer to [Using csh and tcsh Shells](doc/wiki/how_to/

## License

Upstream terms preserved in `THIRD_PARTY_LICENSES/`. Overlay licensed under Anticommons 0.1.0.

## Verification

Recompute the SHA3-256 of `BENCH.json` and compare to this package’s register. Any drift = invalid package.
