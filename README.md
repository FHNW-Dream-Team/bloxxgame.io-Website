# bloxxgame.io Website

The project for the bloxxgame.io website

Project

[![License](https://img.shields.io/github/license/FHNW-Dream-Team/bloxxgame.io-Website)](LICENSE.md)
[![Docker Stars](https://img.shields.io/docker/stars/d3strukt0r/craftcms-blueprint-nginx.svg?label=docker%20stars%20(nginx))][docker-nginx]
[![Docker Pulls](https://img.shields.io/docker/pulls/d3strukt0r/craftcms-blueprint-nginx.svg?label=docker%20pulls%20(nginx))][docker-nginx]
[![Docker Stars](https://img.shields.io/docker/stars/d3strukt0r/craftcms-blueprint-php.svg?label=docker%20stars%20(php))][docker-php]
[![Docker Pulls](https://img.shields.io/docker/pulls/d3strukt0r/craftcms-blueprint-php.svg?label=docker%20pulls%20(php))][docker-php]
[![Contributor Covenant](https://img.shields.io/badge/Contributor%20Covenant-2.0-4baaaa.svg)](.github/CODE_OF_CONDUCT.md)

main-branch (alias stable, latest)

[![GH Action CI/CD](https://github.com/FHNW-Dream-Team/bloxxgame.io-Website/workflows/CI/CD/badge.svg?branch=main)][gh-action]
<!--
[![Codacy grade](https://img.shields.io/codacy/grade/{id}/main)][codacy]
-->

<!--
develop-branch (alias nightly)

[![GH Action CI/CD](https://github.com/FHNW-Dream-Team/bloxxgame.io-Website/workflows/CI/CD/badge.svg?branch=develop)][gh-action]
[![Codacy grade](https://img.shields.io/codacy/grade/{id}/develop)][codacy]
-->

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

What things you need to install the software and how to install them

```
Give examples
```

### Installing

Inside the CraftCMS PHP container run:
```shell
./craft install --language de-CH --site-name 'Blueprint' --site-url \$SITE_URL --username admin --email admin@local.test --password 'password'
```

A step by step series of examples that tell you how to get a development env running

Say what the step will be

```
Give the example
```

And repeat

```
until finished
```

End with an example of getting some data out of the system or using it for a little demo

## Deployment

Add additional notes about how to deploy this on a live system

## Built With

* [PHP](https://www.php.net/) - Programming language
* [Composer](https://getcomposer.org/) - Dependency management
* [CraftCMS](https://craftcms.com) - Web framework
* [Github Actions](https://github.com/features/actions) - CI (Testing) / CD (Deployment)
* [Docker](https://www.docker.com) - Containerization

## Contributing

Please read [CODE_OF_CONDUCT.md](.github/CODE_OF_CONDUCT.md) for details on our code of conduct, and [CONTRIBUTING.md](.github/CONTRIBUTING.md) for the process for submitting pull requests to us.

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository][gh-tags].

## Authors

All the authors can be seen in the [AUTHORS.md](.github/AUTHORS.md) file.

Contributors can be seen in the [CONTRIBUTORS.md](.github/CONTRIBUTORS.md) file.

See also the full list of [contributors][gh-contributors] who participated in this project.

## License

This project is licensed under the GNU General Public License v3.0 - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

A list of used libraries and code with their licenses can be seen in the [ACKNOWLEDGMENTS.md](.github/ACKNOWLEDGMENTS.md) file.

[docker-nginx]: https://hub.docker.com/repository/docker/d3strukt0r/bloxxgame.io-api-nginx
[docker-php]: https://hub.docker.com/repository/docker/d3strukt0r/bloxxgame.io-api-php
[gh-action]: https://github.com/FHNW-Dream-Team/bloxxgame.io-Website/actions
[gh-tags]: https://github.com/FHNW-Dream-Team/bloxxgame.io-Website/tags
[gh-contributors]: https://github.com/FHNW-Dream-Team/bloxxgame.io-Website/contributors
[codacy]: https://www.codacy.com/manual/FHNW-Dream-Team/bloxxgame.io-Website
