# HDD Cleaner

this software deletes all files oder then a specific day intervall from the harddrive.
Please make sure to set the parameter in the **hdd_clean.conf** file right. this is **important!!!**

## IMPORTANT
Please make sure to set the parameter in the **hdd_clean.conf** file right before installation.

## install

use [taskfile](https://taskfile.dev/) to install the software. All functions to install the service are preperated. use ***hdd_clean_make*** will install start and enable your service.

```bash
task hdd_clean_make
```

## options

```bash 
* hdd_clean_enable:     enable can setup service
* hdd_clean_install:    install hdd clean service
* hdd_clean_make:       make service
* hdd_clean_setup:      set up the hdd clean environment
* hdd_clean_start:      start the service
```