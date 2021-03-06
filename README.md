# Docker SMTP

![Docker Pulls](https://img.shields.io/docker/pulls/appwrite/smtp.svg)
[![Discord](https://img.shields.io/discord/564160730845151244)](https://discord.gg/GSeTUeA)

SMTP server docker container is used for sending emails. This container is based on the namshi docker image with Appwrite specific configuration settings. For a fresh installation of namshi SMTP image use the [docker original image](https://hub.docker.com/r/namshi/smtp).

## Getting Started

These instructions will cover usage information to help you run the Appwrite's SMTP docker container.

### Prerequisities

In order to run this container you'll need docker installed on the system.

* [Windows](https://docs.docker.com/windows/started)
* [OS X](https://docs.docker.com/mac/started/)
* [Linux](https://docs.docker.com/linux/started/)

### Usage

```shell
docker run appwrite/smtp
```

### Versioning

This image versioning is following Appwrite server versioning. This means that if you use Appwrite server version 1.1.* , you also use version 1.1.* of Appwrite SMTP docker image.

### Environment Variables

This container supports all environment variables supplied by the original namshi SMTP Docker image.

## Build
```bash
docker build -t appwrite/smtp:1.1.0 .
```

## Push
```bash
docker push appwrite/smtp:1.1.0
```

## Find Us

* [GitHub](https://github.com/appwrite)
* [Discord](https://discord.gg/GSeTUeA)
* [Twitter](https://twitter.com/appwrite_io)

## Maintainers

**Eldad Fux**

+ [https://twitter.com/eldadfux](https://twitter.com/eldadfux)
+ [https://github.com/eldadfux](https://github.com/eldadfux)

## Copyright and license

The MIT License (MIT) [http://www.opensource.org/licenses/mit-license.php](http://www.opensource.org/licenses/mit-license.php)
