RANCID Scripts for Ubiquiti/UBNT EdgeRouters
======

Ubiquiti/UBNT Edgerouter scripts for Rancid.  Forked from 
https://bitbucket.org/aquerubin/rancid-vyatta

Includes:

* uelogin - basic login script
* vrancid - the Rancid wrapper

To integrate into your RANCID install:

* Copy uelogin and uerancid to your 'bin' directory
* Modify 'rancid.types.conf', and add uerancid.. IE:

```
ubnt-er;script;uerancid
```
* Add a new device to your 'router.db', with the vendor of 'ubnt-er'
* Use it  :)

