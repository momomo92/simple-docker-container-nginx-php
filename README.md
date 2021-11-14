# Simple docker container nginx php

[![PHP Version][ico-php-version]](https://hub.docker.com/_/php)
[![NGINX Version][ico-nginx-version]](https://hub.docker.com/_/nginx)

This is a simple example for running a docker container with PHP-FPM and NGINX.

## Get it up and running

[Install docker on your machine.][install-docker]

[Install docker-compose on your machine.][install-docker-compose]

Clone this repository.

``` bash
$ git clone https://github.com/momomo92/simple-docker-container-nginx-php.git
```

Switch to the cloned directory.

``` bash
$ cd simple-docker-container-nginx-php
```

Start the stack.

``` bash
$ docker-compose up
```

[ico-php-version]: https://img.shields.io/badge/PHP-7.4--fpm-blue?style=flat-square
[ico-nginx-version]: https://img.shields.io/badge/NGINX-1.17-green?style=flat-square
[install-docker]: https://docs.docker.com/engine/installation
[install-docker-compose]: https://docs.docker.com/compose/install