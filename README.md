# alfred-docker

Docker-compose file for launching Alfred !

## Launch Alfred with Docker

```
git clone
cd alfred-docker
docker-compose up
```

To launch the stack in detached mode, then see the logs:
```
docker-compose up -d
docker-compose logs -f
```

#### Smart objects

Three objects are launched by Docker. Their ip and port are the following:

__Lamp__
```json
{
  "ip": chiros-lamp,
  "port": 9800
}
```
__Thermometer__
```json
{
  "ip": chiros-thermometer,
  "port": 9801
}
```
__RGB LED__
```json
{
  "ip": chiros-rgb-led,
  "port": 9802
}
```
