﻿# Wordpress & Docker
 
 ### Prerequisites

It is assumed that you have installed the following:

```
docker
```

This file will setup Wordpress, MySQL & PHPMyAdmin with a single command. Add the code below to a file called "docker-compose.yaml" and run the command

```
$ docker-compose up -d

# To Tear Down
$ docker-compose down --volumes
