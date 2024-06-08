# css-bans-egg
A egg for pterodactyl.io

## Setup
- Create Nest> upload this egg
- Go to ```Files>nginx>conf.d``` Eidt ```default.conf``` and replace the below
```
Replace root /home/container/webroot

with

root /home/container/webroot/public
```
- Restart server
- Upload CSS BANS to ```/home/container/webroot/``` 
- Give 777 permission to storage folder recursively

