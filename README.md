
# Docker-Compose 

Install Docker Compose


##

Run the following command

```bash
sudo curl -L "https://github.com/docker/compose/releases/download/1.23.2/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose
sudo chmod +x /usr/local/bin/docker-compose
docker-compose --version
```
Execute yaml file using command
```bash
docker-compose up -d 
```
Test Services
```bash
docker ps -a
```
Remove/Stop service 
```bash
docker-compose down 
```

