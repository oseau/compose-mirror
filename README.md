# compose-mirror

# option 1

download from https://github.com/docker/compose/releases/download/1.28.0/docker-compose-Linux-x86_64

```
sudo curl -L "https://cdn.jsdelivr.net/gh/oseau/compose-mirror@latest/docker-compose-Linux-x86_64" -o /usr/local/bin/docker-compose
sudo chmod +x /usr/local/bin/docker-compose
```

# option 2, using docker container
download from https://github.com/docker/compose/releases/download/1.28.0/run.sh
```
sudo curl -L --fail "https://cdn.jsdelivr.net/gh/oseau/compose-mirror@latest/run.sh" -o /usr/local/bin/docker-compose
sudo chmod +x /usr/local/bin/docker-compose
```
