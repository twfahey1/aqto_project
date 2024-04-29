# Aqto
<!-- Lets do an image here for the images/aqto-logo-western.png -->
![Aqto Logo](images/aqto-logo-western.png)

Aqto is an opinionated stack of frameworks aiming to provide maximum flexibility, longevity, and maintainability.
## Preqrequisites
- Docksal - https://docksal.io
- Composer - https://getcomposer.org/download

## Quickstart
```bash
composer create-project twfahey1/aqto_project -s dev my-aqto-project 
cd my-aqto-project
composer install
fin up && fin init-site && fin drush si -y
# Optional: enable some default modules and login as admin
fin drush en -y aqto_defaults -y && fin uli
```

## Features
- Composer driven with an upstream setup to facilitate platform models via the [Aqto Upstream](https://github.com/twfahey1/aqto_upstream.git)
- Geared for [Docksal](https://docksal.io)
- Uses [Drupal](https://www.drupal.org) under the hood
- Paragraphs, Layout Builder, and Media Library are the primary content creation tools.
- TailwindCSS and AlpineJS are leveraged for the front end.

## Goals
- Easy to use examples for API integrations, Commerce, and other common use cases.
- Aqto Upstream will be the primary distribution for Aqto.
- Aqto will be a composer driven, opinionated CMS.
- A standard Tailwind theme aqto_theme_base will be included.
- Aqto will be a good starting point for a variety of web projects and encourage best practices for always facilitating customizability, maintability and scalability.


