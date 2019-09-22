## apathy-mlfs
this project is a fork of `dslm4515/Musl-LFS` which uses the `linux from scratch` as its base and replaces `openssl` with `libressl` and `sysvinit`,`sysklogd` with `s6`.

#### differences between mlfs and apathy-mlfs
 * no `bash`, replaced with `yash`.
 * uses the traditional `sysvinit` and `sysklogd` instead of the `s6` utilities, with my own posixly correct init scripts.
 * no `porg`, package management is done by hand.
 * kernel, headers and firmware are all deblobbed using the `linux-libre` patchset.
 * additional recipe for a statically linked `busybox-1.31.0` binary, `/bin/sh` is linked to `/bin/busybox`.

#### used sources
 * http://www.linuxfromscratch.org
 * https://github.org/dslm4545/Musl-LFS
 * https://voidlinux.org
 * https://alpinelinux.org
 * https://dragora.org
