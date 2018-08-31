Munki Report PHP in a Container
=============

This Docker image runs [MunkiReport PHP](https://github.com/munkireport/munkireport-php).

The Docker image is built on Debian:Stretch for the newer versions

It uses Nginx and php7-fpm

* Branches / versions

There are multiple branches for each version, ensure you check out the tags for each branch.


- MunkiReport PHP version 3.2.2 (July 3, 2018) - Tag 3.2.2 

- MunkiReport PHP version 2.12.0 (December 23, 2016) - Tag 2.12.0 

- MunkiReport PHP version 2.8.4 (March 15, 2015) - Tag 2.8.4

- MunkiReport PHP version 2.7.3 (December 17, 2015) - Tag 2.7.3

- MunkiReport PHP version 2.6.0 (October 20, 2015) - Tag 2.6.0

- MunkiReport PHP version 2.5.3 (July 31, 2015) - Tag 2.5.3

- MunkiReport PHP version 2.4.3 (June 2, 2015) - Tag 2.4.3

- MunkiReport PHP version 2.3.0 (March 11, 2015) - Tag 2.3.0


# Settings

Modify the /var/www/config.php as per your needs

# Running the container

Running the container is quite simple.

```
$ docker run -d -p 80:80 -e TZ=Australia/Melbourne --name mr_webapp hunty1/munkireport-docker
```
