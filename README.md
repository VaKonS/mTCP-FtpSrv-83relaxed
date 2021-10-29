**mTCP-FtpSrv-83relaxed**

A fork of DOS FTP server from mTCP package by Michael B. Brutman (https://www.brutman.com/mTCP/), accepting any incoming names.

Differences so far:
- accepts any characters (non-DOS are converted to underscores);
- accepts names longer than 11 letters (they are truncated to 8.3 form);
- allows to use smaller passive ports range.

Initially forked from 2020-07-03 version.
