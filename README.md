![Bronyspeak](./app/Resources/doc/img/sympony.png)

## What

Welcome to my Symfony 2.3 Fat Free Boilerplate - a release of [symfony 2.3][5]
that you can use as the skeleton for your new applications when
you don't need all the bundles of the Universe.

When you need to start a project in 15 seconds, use this release.
It does not include heavy & slow components like Doctrine or Swiftmailer.

All components extending Annotations are removed because it is a known
anti-pattern : the [Inner-platform Effect][16]

## Installing this edition

### With Composer

    php composer.phar create-project trismegiste/sympony MyApp 2.3.x-dev

## Start hacking
This edition is intended to be a **seed** to grow your own project very fast !

It is not intended to build your app *on* it but *in* it. Modify, redefine or delete
files, it is for you ! Yes it sounds like [duct tape programing][19] but even
in space, [engineers use duct tape][20] and with [symfony 2.3][5]
you can do that in an elegant and clean way, thanx Fabien you're awsum.

## Y U NO use Silex ?
Yes, [Silex][7] is cool. But who can say what is the best : A fat Silex or a light
Symfony ? I prefer light Symfony. Now you can choose.

## Contributing
Since this repository is mainly for me, I don't think it will evolve, it is already
very specific. Too more features will be pointless.

## What's inside?

This light boilerplate is configured with the following defaults:

  * Twig is the only configured template engine;

  * [Twitter Bootstrap][17] : default for the base twig, we are in 21st century now

  * [DokudokiBundle][18] : A full-schemaless-database-layer for MongoDB

  * It features an auto-installer : after the first install, a script will
    create a file named after your server name
    and asks you some parameters (MongoDB server, locale etc...). 
    See [trismegiste/symfony-prelude][14]

  * It has a default security route and login form. The provider is hardcoded in security.yml.
    See the documentation of the [SecurityBundle][9] to change it.

  * It adds a configuration for multiple developers with a parameter
    named "developer.name" in dev environment.

It comes pre-configured with the following bundles:

  * **FrameworkBundle** - The core Symfony framework bundle

  * [**TwigBundle**][8] - Adds support for the Twig templating engine

  * [**SecurityBundle**][9] - Adds security by integrating Symfony's security
    component

  * [**MonologBundle**][11] - Adds support for Monolog, a logging library

  * [**AsseticBundle**][12] - Adds support for Assetic, an asset processing
    library

  * **WebProfilerBundle** (in dev/test env) - Adds profiling functionality and
    the web debug toolbar

  * **SensioDistributionBundle** (in dev/test env) - Adds functionality for
    configuring and working with Symfony distributions


Enjoy!

[1]:  http://symfony.com/doc/2.3/book/installation.html
[2]:  http://getcomposer.org/
[3]:  http://symfony.com/download
[4]:  http://symfony.com/doc/2.3/quick_tour/the_big_picture.html
[5]:  http://symfony.com/doc/2.3/index.html
[6]:  http://symfony.com/doc/2.3/bundles/SensioFrameworkExtraBundle/index.html
[7]:  http://symfony.com/doc/2.3/book/doctrine.html
[8]:  http://symfony.com/doc/2.3/book/templating.html
[9]:  http://symfony.com/doc/2.3/book/security.html
[10]: http://symfony.com/doc/2.3/cookbook/email.html
[11]: http://symfony.com/doc/2.3/cookbook/logging/monolog.html
[12]: http://symfony.com/doc/2.3/cookbook/assetic/asset_management.html
[13]: http://symfony.com/doc/2.3/bundles/SensioGeneratorBundle/index.html
[14]: https://github.com/Trismegiste/symfony-prelude
[16]: http://en.wikipedia.org/wiki/Inner-platform_effect
[17]: http://twitter.github.com/bootstrap/
[18]: https://github.com/Trismegiste/DokudokiBundle
[19]: http://www.joelonsoftware.com/items/2009/09/23.html
[20]: http://www.universetoday.com/13794/the-best-engineering-tool-in-space-duct-tape/
