# Restic System backup

this software makes a snapshot every 2 hour starting 30 minutes after boot.

## IMPORTANT
install [RESTIC](https://restic.net/). this is a wonderful exelent backup solution.
Set up the **restic-backup.conf** file otherwise the service crashes.

## install
use [taskfile](https://taskfile.dev/) to install the software. All functions to install the service are preperated. use ***baskup_make*** will install start and enable your service.
make sure you installed *restic* and have the configuration variables set

```bash
task baskup_make
```

## option
* backup_enable:        enable the service
* backup_install:       install the service to user space
* backup_make:          make the backup
