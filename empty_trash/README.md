# empty_trash

[trash-cli](https://github.com/andreafrancia/trash-cli) is a opensource project to clear all your system trashes. It can oly run in user space because the Linux Trash is user id dependent.


make sure to install the latest pip package not the predefined binaries.
## install

use [taskfile](https://taskfile.dev/) to install the software. All functions to install the service are preperated. use ***trash_make*** will install start and enable your service.

```bash
task trash_make
```

## options

```bash 
* trash_cli:            install the python trash cli package
* trash_enable:         enable the service
* trash_install:        install the service to user space
* trash_make:           make the trash empty
```