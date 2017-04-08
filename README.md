# C - container managment

## Description

This a cover for LXC. This is a compiled collection of my scripts.

You can create LXC container and run this script for test. Nesting of containers depends only on the number of loopback devices.

### How to use 

**C [ls|create|delete|start|stop|backup|restore|console] name_of_container**

### List

**C ls**

Running *lxc-ls -f* - full info about container.

### Create

**C create name**

Creating container *name* like your system (if you running debian - you will have debian).

### Delete

**C delete name**

Removing container name.

### Start

**C start name**

### Stop

**C stop name**

### Backup

**C backup name**

Backup your container "name" to */root/backup/name.7z*.
7zip have best compression, but it will cost time.

### Restore

**C restore name**

Restoring your container from backup (/root/backup/name.7z). Removing current if exist.

### Console

**C console name**
