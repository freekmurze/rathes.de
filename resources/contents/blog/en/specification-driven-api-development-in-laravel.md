---
id: 20180131
title: Specification Driven Dvelopment in Laravel using API Blueprint and Dredd
date: 2018-01-31T08:54:00+00:00
author: Rathes Sachchithananthan
template: post
image: 
description: Step-by-step instructions on how to add API Blueprint to your Laravel project and how to use Dredd to test you API specifications
categories:
  - web
tags:
  - laravel
  - php
  - webdev
locale: en_US
---

- basic laravel project
- api blueprint
    - what is api blueprint
    - why api blueprint
- dredd
    - what is dredd
    - why dredd (vs. unit testing)
- getting started
    - npm install (-g) dredd
    - dredd init to create a config file
        - set language to `vendor/bin/dredd-hooks-php`
        - server can be php artisan serve --env=testing
        - blueprint to file
        - endpoint will be localhost
    - why this setup?
    - Hooks to integrate Laravel
        - running artisan (setup db)
        - setting env (and adding testing env)
    - how to run tests
- last note on what dredd does not (and why you still need unit tests)