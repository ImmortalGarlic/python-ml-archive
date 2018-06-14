## Common Linux commands
### File & folder operations
|Description|Command|
| ------------- |-------------|
|How many lines in a file?|`wc -l filepath`|
|Split a file|`split -l 60000 filepath`|
|Size of a folder|`du -sh filepath`|
|Disk status|`df -Th`|
### External disk
|Description|Command|
| ------------- |-------------|
|Reformat disk to attachment|`sudo mkfs -t ext4 /dev/[your disk name]`|
- [cannot mount when not properly unmounted last time](https://ubuntuforums.org/showthread.php?t=1898721)
### Network
|Description|Command|
| ------------- |-------------|
|Port status|`netstat -nat \| grep 8080`|
### crontab
- [Tutorial(JP)](https://qiita.com/shunyooo/items/69c3523a8c500b37f33f)
- [cron command generator](http://www.cronmaker.com/)
### Privileges
|Description|Command|
| ------------- |-------------|
|Allow super user privilege through folder|`chmod -R 0777 ./folder/you/mount/to/`|
|Make key private|`chmod 400 [yourkey.pem]`|
- TODO: [Abusing SUDO (Linux Privilege Escalation)](http://touhidshaikh.com/blog/?p=790)
