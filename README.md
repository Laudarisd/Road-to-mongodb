Intallation
======================

## Install mondb in ubuntu 20.04

**Step one**
```
1. $ sudo apt update
2. $ sudo apt upgrade
```
**Step two**
```
$ sudo apt install mongodb
```
**Steep three**
```
$ sudo systemctl status mongodb
```

**Run mongodb**
```
$ sudo systemctl status mongodb
```
**Start & stop mongodb**
```
$ sudo systemctl start mongodb

$ sudo systemctl stop mongodb
```
**Restart mongodb**
```
$ sudo systemctl restart mongodb
```
**Disable mongodb**
```
$ sudo systemctl disable mongodb
```
---------------------------------------------------------------------------
---------------------------------------------------------------------------

#### To start the mongob shell, first `enable` db abd type the command in terminal

```
sudo mongo
```

#### Create db storeage in local

```
mongodb --dbpath ./ --logpath ./
```



===========================================================

Uninstall MongoDB:
===================================

```
$ sudo systemctl stop mongodb
$ sudo apt purge mongodb
$ sudo apt autoremove
```


