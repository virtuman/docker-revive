### revive - open source ad server

This uses the January 31, 2017 version of the Revive Adserver v4.0.1

##### quick start

###### run complete application: revive adserver and mysql (defaults to port 88)
```
docker-compose up -d
```

###### run revive adserver (without mysql)
```
docker run -d --name revive -p 8000:80 virtuman/revive
```

###### build from scratch
```
./build.sh
docker-compose up -d
```
