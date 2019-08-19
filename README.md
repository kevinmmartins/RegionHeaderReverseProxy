# RegionHeaderReverseProxy
Simple nginx docker project to add region header

## Requirements

* Docker Compose 1.21.2+

## Run

```bash
# building the container
sudo docker-compose build

# starting up a container
sudo docker-compose up
```

The exposed port is **8091** , you can change in docker-compose.yml file.

The header **x-country-code** will be added to all requests with the value **us**.
