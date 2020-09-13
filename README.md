# Aciton-Rclone

gd两个团队盘之间自动同步备份，防翻车

secrets设置

`RCLONE_CONFIG`
```
[nameA]
type = drive
client_id = 
client_secret = 
scope = drive
token = 
team_drive = 

[nameB]
type = drive
client_id = 
client_secret = 
scope = drive
token = 
team_drive = 

```


`SOURCE_DEST`
```
source:sourcepath dest:destpath
```
