# banner
```bash
sudu su -
```
```bash
vim /etc/ssh/sshd_config
```
# We need to write this part
```bash
Banner /etc/issue.net
```
```bash
vim /etc/issue.net
```
```bash
###############################################################
#                  This is a private server!                  #
#       All connections are monitored and recorded.           #
#  Disconnect IMMEDIATELY if you are not an authorized user!  #
###############################################################
```
# OR
```bash
~~~~~~~~~~~~~~~~~~~~~~~~** WARNING **~~~~~~~~~~~~~~~~~~~~~~~~~~~~
#################################################################
#                   _    _           _   _                      #
#                  / \  | | ___ _ __| |_| |                     #
#                 / _ \ | |/ _ \ '__| __| |                     #
#                / ___ \| |  __/ |  | |_|_|                     #
#               /_/   \_\_|\___|_|   \__(_)                     #
#                                                               #
#  You are entering into a secured area! Your IP, Login Time,   #
#   Username has been noted and has been sent to the server     #
#                       administrator!                          #
#   This service is restricted to authorized users only. All    #
#            activities on this system are logged.              #
#  Unauthorized access will be fully investigated and reported  #
#        to the appropriate law enforcement agencies.           #
#################################################################
```
```bash
chmod 644 /etc/issue.net
```
### Default ISSUE file
```bash
********************************************************************
*                                                                  *
* This system is for the use of authorized users only.  Usage of   *
* this system may be monitored and recorded by system personnel.   *
*                                                                  *
* Anyone using this system expressly consents to such monitoring   *
* and is advised that if such monitoring reveals possible          *
* evidence of criminal activity, system personnel may provide the  *
* evidence from such monitoring to law enforcement officials.      *
*                                                                  *
********************************************************************
```
### Default MOTD file
```bash
**********************************************************************
Hostname:             server
Distribution:         Debian stretch (9.3)

Processors:       1
Memory Installed: 0.5GB
Memory Swapfile:  1.0GB
Mounts:
  Mount: /dev/sda1 (/) (7.7GB)

IPv4 default address:	192.168.93.109 (eth0)

Kernel:              4.9.0-4-amd64
Virtualization Role: guest
Virtualization Type: kvm

******************************** 2017-12-18 15:23:57.595459 **********
```
