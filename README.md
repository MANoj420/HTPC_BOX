# HTPC_BOX

## base env cofig file
```
$ id $USER
$ ip route | awk '!/ (docker0|br-)/ && /src/ {print $1}'
```

configure PUID PGID TZ ROOT-directory CONFIG-directory VPN-config

## WEB-PORT 
* Qbittorrent :- http://localhost:8080/
* Jakett :- http://localhost:9117/
* Radarr :- http://localhost:7878/
* Plex:- http://localhost:32400/
