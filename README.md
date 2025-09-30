# Wordpress Portal for tests

Playground for WordPress testing.

## Installation

```
$ git clone https://github.com/acepace/dvwp.git
$ cd dvwp/
$ docker compose up -d --build
$ docker compose run --rm wp-cli install-wp
```

## Usage
```
$ docker-compose up -d
$ docker-compose down
```

## Shell
`docker exec -ti dvwp-wordpress-1 /bin/bash`

## Interface Loopback IP
* [http://127.0.0.1:31337](http://127.0.0.1:31337)
* [http://127.0.0.1:31337/wp-login.php](http://127.0.0.1:31337/wp-login.php)
* [http://127.0.0.1:31338/phpmyadmin/](http://127.0.0.1:31338/phpmyadmin/)
## OR localhost
* [http://localhost:31337](http://localhost:31337)
* [http://localhost:31337/wp-login.php](http://localhost:31337/wp-login.php)
* [http://localhost:31338/phpmyadmin/](http://localhost:31338/phpmyadmin/)

## OR Interface PRIVATE IP
* [http://YOUR-PRIVATE-IP:31337](http://YOUR-PRIVATE-IP:31337)
* [http://YOUR-PRIVATE-IP:31337/wp-login.php](http://YOUR-PRIVATE-IP:31337/wp-login.php)
* [http://YOUR-PRIVATE-IP:31338/phpmyadmin/](http://YOUR-PRIVATE-IP:31338/phpmyadmin/)

## Credentials
* Wordpress: admin/admin
* MySQL: root/password

