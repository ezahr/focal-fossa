Focal fossa



## 	20200827 09:00 gitsync

## 	20200827 09:00 git	

## 	20200827 09:00 /dev/sda5

## 	20200827 09:00 rsync dockuwiki

## 	20200827 09:00 ssh

## 	20200827 09:00 /dev/sda5	


## sudo timeshift --create

````
boscp08@boscp08-HP-Compaq-8510p:~$ sudo timeshift --create
First run mode (config file not found)
Selected default snapshot type: RSYNC
Mounted '/dev/sda5' at '/run/timeshift/backup'
Selected default snapshot device: /dev/sda5
------------------------------------------------------------------------------
Estimating system size...
Creating new snapshot...(RSYNC)
Saving to device: /dev/sda5, mounted at path: /run/timeshift/backup
Synching files with rsync...
Created control file: /run/timeshift/backup/timeshift/snapshots/2020-08-27_10-06-04/info.json
RSYNC Snapshot saved successfully (124s)
Tagged snapshot '2020-08-27_10-06-04': ondemand
------------------------------------------------------------------------------
````

## sudo apt install timeshift

## sudo apt-get update && sudo apt-get upgrade -y

##	20200827 09:00 /dev/sda5	/dev/sda5 466G 7,1G 435G 2% /
