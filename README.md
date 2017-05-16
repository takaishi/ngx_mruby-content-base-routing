
# 1. build images

```
$ docker-compose build
```

# 2. up services

```
$ docker-compose run
```

# 3. test routing

production access.

```
$ curl http://localhost:8000
Hello World!
```


If add header, staging access.

```
$ curl http://localhost:8000 -H 'X-Environment:STAGING'
[staging] Hello World!
```
