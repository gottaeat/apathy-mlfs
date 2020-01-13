## apathy-mlfs
apathy-mlfs aims to provide instructions for building a small linux install utilizing musl libc.

#### features
 * `musl libc 1.1.24`
 * `binutils 2.32`
 * `linux 5.2.14` (libre)
 * `gcc 9.2.0` (c,c++), can be replaced with the latest `gcc 9.2.1` snapshot.
 * `isl 0.21`, `mpfr 4.0.2`, `gmp 6.1.2`, `mpc 1.1.0`
 * statically linked `defconfig` `busybox 1.31.0` for emergency situations and ash.
 * `libressl 3.0.2`
 * `sysvinit 2.96`, `sysklogd 1.5.1` (w/ posixly correct self-written init scripts)
 * `bash 5.00` as `/bin/sh` at toolchain and cross-toolchain steps, for bracket and array support.
 * `yash 2.49` as final system interactive shells.
 * `ash` (busybox) as final system `/bin/sh` as it allows configure scripts to execute properly without needing bash.

#### used sources
 * http://www.linuxfromscratch.org
 * https://github.org/dslm4545/Musl-LFS
 * https://voidlinux.org
 * https://alpinelinux.org
