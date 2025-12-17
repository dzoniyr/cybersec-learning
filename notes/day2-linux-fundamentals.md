# Day 2 – Commands and Important Directories

- `touch` – creates an empty file or updates the timestamp of an existing file. [web:262]
- `mkdir` – creates a new directory (folder). [web:262]
- `cp` – copies files or directories from one location to another. [web:262]
- `mv` – moves or renames files and directories. [web:262]
- `rm` – removes files; with `-r` it can remove directories recursively. [web:262]
- `file` – identifies the type of a file (text, binary, script, etc.). [web:259]

## Important Linux directories

- `/etc` – system-wide configuration files for the OS and services. [web:254]
- `/var` – variable data like logs, mail, caches and spool files. [web:254]
- `/root` – home directory of the root (administrator) user. [web:254]
- `/tmp` – temporary files, often cleared on reboot. [web:254]

## User switching

- `su` – switch user (by default to root if no username is given), keeping the current environment. [web:254]
- `su -` – switch user and start a full login shell with the target user's environment. [web:254]
