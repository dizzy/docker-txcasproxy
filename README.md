# docker-txcasproxy

Docker image for txcasproxy (https://github.com/cwaldbieser/txcasproxy) - A CAS authenticating reverse proxy using Twisted

To run it:

- pull image
```
docker pull dizzy/docker-txcasproxy
```

- see help
```
docker run -i -t --name=casproxy dizzy/docker-txcasproxy
```

- run image with parameters
```
docker run -i -t --name=casproxy dizzy/docker-txcasproxy -n casproxy --endpoint="tcp:9191" -p 'http://127.0.0.1' -c 'https://server/cas'
```
