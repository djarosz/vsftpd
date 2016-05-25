# vsftpd - Secure, fast FTP server for UNIX-like systems with patches

This is fork of original vsfptd server which includes some patches (described below)

vsftpd is an FTP server, or daemon. The "vs" stands for Very Secure. Obviously
this is not a guarantee, but a reflection that I have written the entire
codebase with security in mind, and carefully designed the program to be
resilient to attack.

vsftpd now powers some of the largest and most prestigious sites on the
internet.

## Upstream project

Author: Chris Evans
Contact: scarybeasts@gmail.com
Website: http://vsftpd.beasts.org/
* All options are documented in the vsftpd.conf.5 manual page.
* See the FAQ file for solutions to frequently asked questions.
* Visit http://vsftpd.beasts.org/ for vsftpd news and releases.

## Patches

- Automatic conversion of windows path separator enabled by setting 
  _translate_windows_paths_ configuration parameter to *YES*

## Installation

Please see the [INSTALL file](./INSTALL).

## Configuration

All configuration options are documented in the manual page vsftpd.conf.5.
Various example configurations are discussed in the EXAMPLE directory.
Frequently asked questions are tackled in the [FAQ file](./FAQ).

## License

vsftpd is licensed under the [GPL v2](./COPYING).
