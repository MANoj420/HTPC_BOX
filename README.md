# HTPC_BOX

## CONFIG.SH
* It will create config directory, run at home directory

## BASE .env CONFIG FILE

* Terminal
```
$ id $USER
$ ip route | awk '!/ (docker0|br-)/ && /src/ {print $1}'
```
Configure
* PUID 
* PGID 
* TZ 
* ROOT-directory 
* CONFIG-directory VPN-config

## WEB-PORT 
* Qbittorrent :- http://localhost:8080/
* Jakett :- http://localhost:9117/
* Radarr :- http://localhost:7878/
* Plex:- http://localhost:32400/

## DOCKER-COMPOSE
* Modify as per your requirement
```
$ docker-compose up
```
