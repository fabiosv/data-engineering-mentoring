# Zalenium

Setup:

```sh
docker pull elgalu/selenium
docker pull dosel/zalenium

docker run -d --name zalenium -p 4444:4444 -v /var/run/docker.sock:/var/run/docker.sock -v /tmp/videos:/home/seluser/videos --privileged dosel/zalenium start
```
