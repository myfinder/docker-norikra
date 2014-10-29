docker-norikra
==============

Dockerfile for norikra

```
docker run -d -p 26578:26578 -p 26571:26571 -v /var/tmp/norikra:/var/tmp/norikra:rw -t myfinder/docker-norikra norikra start --stats /var/tmp/norikra/stats.json -l /var/tmp/norikra
```
