1. `mkdir caddy-config  caddy-data`
2. create Caddyfile
3. Download caddy file from caddy download website : https://caddyserver.com/download
4. Updated the docker-compose.yml with candy networks etc
5. Run `sudo docker compose up`
6. A permissions issue will arise for the `mydata` folder 
7. Provide permissions to `mydata` folder : `sudo chmod 777 ./mydata/`

Thanks to https://github.com/digtalaloha/synology-private-vaultwarden for showing how to use caddy with docker images. His video here : https://www.youtube.com/watch?v=pH_LZVfuSWo&t=13s 

A similar implementation is used here. 


