# Aqto
<!-- Lets do an image here for the images/aqto-logo-western.png -->
![Aqto Logo](images/aqto-logo-western.png)

Aqto is a PHP (Symfony by way of Drupal) based, composer driven opinionated CMS.

## Features
- Composer driven, geared for distributions via the [Aqto Upstream](https://github.com/twfahey1/aqto_upstream.git)
- Geared for [Docksal](https://docksal.io)
- Uses [Drupal](https://www.drupal.org) under the hood
- Paragraphs, Layout Builder, and Media Library are the primary content creation tools.

## Goals
- Easy to use examples for API integrations, Commerce, and other common use cases.
- Aqto Upstream will be the primary distribution for Aqto.
- Aqto will be a composer driven, opinionated CMS.
- A standard Tailwind theme aqto_theme_base will be included.
- Aqto will be a good starting point for a variety of web projects and encourage best practices for always facilitating customizability, maintability and scalability.

## Quickstart
```bash
composer create-project twfahey1/aqto_project -s dev my-aqto-project 
cd my-aqto-project
composer install
fin up && fin init-site && fin drush si -y
```

