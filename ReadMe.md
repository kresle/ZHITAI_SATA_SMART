# Instructions
Use with smartctl. Copy the contents in drivedb.h of this repos

1. Install `smartmontools`;
2. Download the 'https://github.com/mirror/smartmontools/blob/master/drivedb.h' to '/opt/share/smartmontools/drivedb.h';
3. Copy the contents of 'drivedb.h' of this repo to '/opt/share/smartmontools/drivedb.h';
4. `smartctl -d sat -a /dev/sdx` should works.
