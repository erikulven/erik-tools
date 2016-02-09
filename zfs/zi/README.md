# H1 ZI - ZFS information

Convenience script for working with ZFS on FreeBSD.

# H2 Functions

1. snapshot versions of file/dir

Implemented function for showing snapshots for 
file/dir with/without diff

```sh
$ zi snaps <filename> # list snapshots containing file
$ zi snaps <filename> -d 2 # diff with snapshot id 2
```