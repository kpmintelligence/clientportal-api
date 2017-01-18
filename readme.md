# TODO API

## Docker on Windows

1)Install Docker Toolbox
https://www.docker.com/products/docker-toolbox

2) Use docker Quickstart Terminal to access in docker cli
3) clone the todoapi repo into one of your c:\Users folder

4) clone the tododocker repo into the todoapi folder

5) open the tododocker folder in the Docker Quickstart terminal and use the “docker-compose up -d nginx” command (at first it will takes ~5-6 mins, later it will takes 2-3 seconds to boot up)

6) check the ‘docker-machine ip’

6) check the workspace container id and log in: ‘docker ps’ and ‘docker exec -it <workspace_id> bash’

7) login to the todoapi’s root folder and run ‘composer install’

8) now, you can see/use the api in your browser with the docker-machine ip, you can run unit tests in the workspace container with phpunit and you can check the coding standards in the workspace container with the ‘phpcs --standard=PSR2 --colors --ignore=vendor,storage,tododocker’

9) Client: clone the todoclient repo, run npm install, npm serve, npm test - you’ll need an installed NodeJS


## Lumen PHP Framework

[![Build Status](https://travis-ci.org/laravel/lumen-framework.svg)](https://travis-ci.org/laravel/lumen-framework)
[![Total Downloads](https://poser.pugx.org/laravel/lumen-framework/d/total.svg)](https://packagist.org/packages/laravel/lumen-framework)
[![Latest Stable Version](https://poser.pugx.org/laravel/lumen-framework/v/stable.svg)](https://packagist.org/packages/laravel/lumen-framework)
[![Latest Unstable Version](https://poser.pugx.org/laravel/lumen-framework/v/unstable.svg)](https://packagist.org/packages/laravel/lumen-framework)
[![License](https://poser.pugx.org/laravel/lumen-framework/license.svg)](https://packagist.org/packages/laravel/lumen-framework)

Laravel Lumen is a stunningly fast PHP micro-framework for building web applications with expressive, elegant syntax. We believe development must be an enjoyable, creative experience to be truly fulfilling. Lumen attempts to take the pain out of development by easing common tasks used in the majority of web projects, such as routing, database abstraction, queueing, and caching.

## Official Documentation

Documentation for the framework can be found on the [Lumen website](http://lumen.laravel.com/docs).

## Security Vulnerabilities

If you discover a security vulnerability within Laravel, please send an e-mail to Taylor Otwell at taylor@laravel.com. All security vulnerabilities will be promptly addressed.

## License

The Lumen framework is open-sourced software licensed under the [MIT license](http://opensource.org/licenses/MIT)
