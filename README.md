## apathy-mlfs
apathy-mlfs aims to provide instructions for building a small musl libc using linux install. features as of the time of writing the README are:
 * musl libc 1.1.23
 * libressl 2.9.2
 * gcc 9.2.0 (c,c++)
 * sysvinit-2.96 + sysklogd 1.5.1 (w/ posixly correct self-written init scripts)
 * busybox 1.31.0 (for ash at /bin/sh and recovery purposes.)(statically linked, defconfig.)
 * libre kernel, headers and firmware.

#### used sources
*this project is a fork of `dslm4515/Musl-LFS` with moderate changes, rewrites, difference in software of choices and updated packages/patches.*
 * http://www.linuxfromscratch.org
 * https://github.org/dslm4545/Musl-LFS
 * https://voidlinux.org
 * https://alpinelinux.org
 * https://dragora.org
