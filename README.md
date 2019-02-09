# _Purely_ static μWSGI
[![semantic-release](https://img.shields.io/badge/%20%20%F0%9F%93%A6%F0%9F%9A%80-semantic--release-e10079.svg?longCache=true&style=flat-square)](//semantic-release.gitbook.io/semantic-release)
[![ISC License](https://img.shields.io/badge/license-ISC-brightgreen.svg?longCache=true&style=flat-square)](//www.isc.org/downloads/software-support-policy/isc-license/)
[![Build Status](https://travis-ci.org/concatime/uwsgi-zero.svg?branch=master)](//travis-ci.org/concatime/uwsgi-zero)

Package | Version | Latest available
:------:|---------|-
μWSGI   | 2.0.18  | ![](https://repology.org/badge/latest-versions/uwsgi.svg)
MUSL    | 1.1.21  | [![](https://repology.org/badge/latest-versions/musl.svg)](//git.musl-libc.org/cgit/musl/tree/WHATSNEW)
PCRE    | 8.42    | [![](https://repology.org/badge/latest-versions/pcre.svg)](//pcre.org/original/changelog.txt)
ZLIB    | 1.2.11  | [![](https://repology.org/badge/latest-versions/zlib.svg)](//zlib.net/ChangeLog.txt)
EXPAT   | 2.2.6   | [![](https://repology.org/badge/latest-versions/expat.svg)](//github.com/libexpat/libexpat/blob/master/expat/Changes)
LIBRESSL| 2.9.0   | [![](https://repology.org/badge/latest-versions/libressl.svg)](//raw.githubusercontent.com/libressl-portable/portable/master/ChangeLog)

The script (`uwsgi-zero`) requires:
 - gcc or clang>=3.5 (otherwise, `ld: cannot find -l-user-{start,end}`)
 - tar (+gzip)
 - git
 - make
 - cmake
 - patch

To clone:
`git clone --recurse-submodules -j8 https://github.com/concatime/uwsgi-zero.git`

To install, download the release file called `uwsgi.tar.gz`, and then
`sudo tar xf uwsgi.tar.gz -C/opt`
