docker-onlyoffice
===

Docker compose for onlyoffice meant to be used with nextcloud or similar services (on the same server). The [default docker-compose](https://github.com/ONLYOFFICE/Docker-DocumentServer/blob/master/docker-compose.yml) is certainly overkill. To set it up simply copy `docker-compose.yml` where you want to, open it and enable volumes (if desired), and just run it like you normally would a docker-compose service.

In the nginx folder you have the `/onlyoffice` location entry that you can plug in your already existing nginx server definition.

In the config folder you have the default onlyoffice configuration file.
