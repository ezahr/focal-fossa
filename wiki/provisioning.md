Focal fossa



## 	20200827 09:00 gitsync

## 	20200827 09:00 git	

## 	20200827 09:00 /dev/sda5

## 	20200827 09:00 rsync dockuwiki

## 	ssh-keygen

````
boscp08@boscp08-HP-Compaq-8510p:~$ ssh-keygen
Generating public/private rsa key pair.
Enter file in which to save the key (/home/boscp08/.ssh/id_rsa): 
Enter passphrase (empty for no passphrase): 
Enter same passphrase again: 
Your identification has been saved in /home/boscp08/.ssh/id_rsa
Your public key has been saved in /home/boscp08/.ssh/id_rsa.pub
The key fingerprint is:
SHA256:Xz2KHgD+gtbKj9tKAEIyHwrq9TrncYsMCvQ6TX4Xlt4 boscp08@boscp08-HP-Compaq-8510p
The key's randomart image is:
+---[RSA 3072]----+
|+..              |
|=+ .             |
|= ..  .          |
|o.. .. .     .   |
| o.  .. S   . o  |
|. .o.o = o o . . |
|. +=+o=.+ + .    |
|..o**=++.E .     |
| o. BB+.  .      |
+----[SHA256]-----+
boscp08@boscp08-HP-Compaq-8510p:~$ cd .ssh
boscp08@boscp08-HP-Compaq-8510p:~/.ssh$ ks
lks: command not found
boscp08@boscp08-HP-Compaq-8510p:~/.ssh$ ls
id_rsa  id_rsa.pub
boscp08@boscp08-HP-Compaq-8510p:~/.ssh$ cat id_rsa.pub 
ssh-rsa AAAAB3NzaC1yc2EAAAADAQABAAABgQDmIvwY8gJrf601nii0W3e6zQoogKyhlpr9cWBfBMsN3qX2WT5RiYQlyP37yQ/o9OPOPsh0S/wZstg1o7UqGhJCkz0DFdKDSd+U0+jsdFZ836BsvOxynSI/r19hxMZJFcDD8R+QwZpeuCJw5JIeYFtuFDkAbH8wt3ug16w7uLpP4CpWvhjtP6wGMpd+z1NdcHVkcCaGyCwpCwb4JYPmb2Lv5ifq4cIDUK5qIs/XJ5Sr0M7dHPFNT/aNAZXLdfTsZCwf+AzNm2BS/rVbynRRuw3OoVzmHMVq4aLaZsEjSgtE0C5mMkHKo45yuU1fzbkEBzVVxyx02y4/anoGmGqKRWLIcXdZEj2YtNlm75dUcDsECxfU/dGMUA8neqZ98TMkChqyjmZkrNE2qv4i4c7bxMe5KJxjQfAUui2el1v2PC55QQKPqfn4Iw1RjiMlJ5P+sbnx5LUKFZH1vkt7aPCAjlDP7tg6YRGveP4BeyjFHKe8ePA8T4XLlqZ8KdEz50qA+zs= boscp08@boscp08-HP-Compaq-8510p

````


## 	20200827 /dev/sda5       466G   14G  429G   4% /


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
