# PHP 7.2 APACHE AND XDEBUG DOCKER IMAGE

With this image you can develop in php 7.2 with xdebug support

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

DOCKER

### Installing

In example_conf_files you have default.conf and php.ini examples prepared for some environments. Copy this files to the same folder where you have dockerfile.


```
cp ./example_conf_files/SYMFONY4/* .
```
Execute DOCKER build

```
docker build -t "tag" .
```

## Authors

* **Jose Carlos Duran** -  [josecarlosduran](https://github.com/josecarlosduran)

## License

This project is licensed under the GNU GENERAL PUBLIC LICENSE V3 - see the [LICENSE.md](LICENSE.md) file for details

