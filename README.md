# Awesome PHP ![](https://github.com/correia-jpv/fucking-awesome-php/workflows/Awesome%20Bot/badge.svg)

A curated list of amazingly awesome PHP libraries, resources and shiny things.

## Contributing and Collaborating
Please see [CONTRIBUTING](https://github.com/correia-jpv/fucking-awesome-php/blob/master/CONTRIBUTING.md), [CODE-OF-CONDUCT](https://github.com/correia-jpv/fucking-awesome-php/blob/master/CODE-OF-CONDUCT.md) and [COLLABORATING](https://github.com/correia-jpv/fucking-awesome-php/blob/master/COLLABORATING.md) for details.

## Table of Contents
- [Awesome PHP](#awesome-php)
    - [Composer Repositories](#composer-repositories)
    - [Dependency Management](#dependency-management)
    - [Dependency Management Extras](#dependency-management-extras)
    - [Frameworks](#frameworks)
    - [Framework Extras](#framework-extras)
    - [Content Management Systems](#content-management-systems-cms)
    - [Components](#components)
    - [Micro Frameworks](#micro-frameworks)
    - [Micro Framework Extras](#micro-framework-extras)
    - [Routers](#routers)
    - [Templating](#templating)
    - [Static Site Generators](#static-site-generators)
    - [HTTP](#http)
    - [Scraping](#scraping)
    - [Middlewares](#middlewares)
    - [URL](#url)
    - [Email](#email)
    - [Files](#Files)
    - [Streams](#streams)
    - [Dependency Injection](#dependency-injection)
    - [Imagery](#imagery)
    - [Testing](#testing)
    - [Continuous Integration](#continuous-integration)
    - [Documentation](#documentation)
    - [Security](#security)
    - [Passwords](#passwords)
    - [Code Analysis](#code-analysis)
    - [Code Quality](#code-quality)
    - [Static Analysis](#static-analysis)
    - [Architectural](#architectural)
    - [Debugging and Profiling](#debugging-and-profiling)
    - [Build Tools](#build-tools)
    - [Task Runners](#task-runners)
    - [Navigation](#navigation)
    - [Asset Management](#asset-management)
    - [Geolocation](#geolocation)
    - [Date and Time](#date-and-time)
    - [Event](#event)
    - [Logging](#logging)
    - [E-commerce](#e-commerce)
    - [PDF](#pdf)
    - [Office](#office)
    - [Database](#database)
    - [Migrations](#migrations)
    - [NoSQL](#nosql)
    - [Queue](#queue)
    - [Search](#search)
    - [Command Line](#command-line)
    - [Authentication and Authorization](#authentication-and-authorization)
    - [Markup and CSS](#markup-and-css)
    - [JSON](#json)
    - [Strings](#strings)
    - [Numbers](#numbers)
    - [Filtering and Validation](#filtering-and-validation)
    - [API](#api)
    - [Caching and Locking](#caching-and-locking)
    - [Data Structure and Storage](#data-structure-and-storage)
    - [Notifications](#notifications)
    - [Deployment](#deployment)
    - [Internationalisation and Localisation](#internationalisation-and-localisation)
    - [Serverless](#serverless)
    - [Configuration](#configuration)
    - [Third Party APIs](#third-party-apis)
    - [Extensions](#extensions)
    - [Miscellaneous](#miscellaneous)
- [Software](#software)
    - [PHP Installation](#php-installation)
    - [Development Environment](#development-environment)
    - [Virtual Machines](#virtual-machines)
    - [Text Editors and IDEs](#text-editors-and-ides)
    - [Web Applications](#web-applications)
    - [Infrastructure](#infrastructure)
- [Resources](#resources)
    - [PHP Websites](#php-websites)
    - [PHP Books](#php-books)
    - [PHP Videos](#php-videos)
    - [PHP Podcasts](#php-podcasts)
    - [PHP Newsletters](#php-newsletters)
    - [PHP Reading](#php-reading)
    - [PHP Internals Reading](#php-internals-reading)

### Composer Repositories
*Composer Repositories.*

* 🌎 [Firegento](packages.firegento.com/) - Magento Module Composer Repository.
* 🌎 [Packagist](packagist.org/) - The PHP Package Repository.
* 🌎 [Private Packagist](packagist.com/) - Composer package archive as a service for PHP.
* 🌎 [WordPress Packagist](wpackagist.org/) - Manage your plugins with Composer.

### Dependency Management
*Libraries for dependency and package management.*

*  <b><code>&nbsp;&nbsp;1369⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;408🍴</code></b> [Composer Installers](https://github.com/composer/installers) - A  multi framework Composer library installer.
* 🌎 [Composer](getcomposer.org/) - A package and dependency manager.
* 🌎 [Phive](phar.io/) - A PHAR manager.
*  <b><code>&nbsp;&nbsp;1530⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;85🍴</code></b> [Pickle](https://github.com/FriendsOfPHP/pickle) - A PHP extension installer.

### Dependency Management Extras
*Extras related to dependency management.*

*  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;47⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3🍴</code></b> [Composed](https://github.com/joshdifabio/composed) - A library to parse your project's Composer environment at runtime.
*  <b><code>&nbsp;&nbsp;&nbsp;811⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;140🍴</code></b> [Composer Merge Plugin](https://github.com/wikimedia/composer-merge-plugin) - A composer plugin to merge several `composer.json` files.
*  <b><code>&nbsp;&nbsp;&nbsp;834⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;28🍴</code></b> [Composer Normalize](https://github.com/ergebnis/composer-normalize) - A plugin for normalising `composer.json` files. 
*  <b><code>&nbsp;&nbsp;1249⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;224🍴</code></b> [Composer Patches](https://github.com/cweagans/composer-patches) - A plugin for Composer to apply patches.
*  <b><code>&nbsp;&nbsp;&nbsp;686⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;59🍴</code></b> [Composer Require Checker](https://github.com/maglnet/ComposerRequireChecker) - CLI tool to analyze composer dependencies and verify that no unknown symbols are used in the sources of a package.
*  <b><code>&nbsp;&nbsp;1045⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;37🍴</code></b> [Composer Unused](https://github.com/composer-unused/composer-unused) - A CLI Tool to scan for unused composer packages.
*  <b><code>&nbsp;&nbsp;6283⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;178🍴</code></b> [Prestissimo](https://github.com/hirak/prestissimo) - A composer plugin which enables parallel install process.
* 🌎 [Repman](repman.io) - A private PHP package repository manager and Packagist proxy.
*  <b><code>&nbsp;&nbsp;2839⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;487🍴</code></b> [Satis](https://github.com/composer/satis) - A static Composer repository generator.
*  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;99⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;12🍴</code></b> [Tooly](https://github.com/tommy-muehle/tooly-composer-script) - A library to manage PHAR files in project using Composer.
* 🌎 [Toran Proxy](toranproxy.com) - A static Composer repository and proxy.

### Frameworks
*Web development frameworks.*

* 🌎 [CakePHP](cakephp.org/) - A rapid application development framework.
* 🌎 [Laminas](getlaminas.org/) - A framework comprised of individual components (previously Zend Framework).
* 🌎 [Laravel](laravel.com/) - A web application framework with expressive, elegant syntax.
* 🌎 [Nette](nette.org) - A web framework comprised of mature components.
* 🌎 [Phalcon](phalcon.io/en-us) - A framework implemented as a C extension.
* 🌎 [Spiral](spiral.dev/) - A high performance PHP/Go framework.
* 🌎 [Symfony](symfony.com/) - A set of reusable components and a web framework.
*  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Yii2](https://github.com/yiisoft/yii2/) - A fast, secure, and efficient web framework.

### Framework Extras
*Extras related to web development frameworks.*

*  <b><code>&nbsp;&nbsp;&nbsp;352⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;148🍴</code></b> [CakePHP CRUD](https://github.com/friendsofcake/crud) - A Rapid Application Development (RAD) plugin for CakePHP.
* 🌎 [Knp RAD Components](rad.knplabs.com/) - A set of Rapid Application Development (RAD) components for Symfony.
*  <b><code>&nbsp;&nbsp;3609⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;470🍴</code></b> [LaravelS](https://github.com/hhxsv5/laravel-s) - Glue for using Swoole in Laravel or Lumen.
*  <b><code>&nbsp;&nbsp;&nbsp;733⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;95🍴</code></b> [Symfony CMF](https://github.com/symfony-cmf/symfony-cmf) - A Content Management Framework to create custom CMS.
* 🌎 [Livewire](laravel-livewire.com/) - A full-stack framework for Laravel that takes the pain out of building dynamic UIs.

### Content Management Systems (CMS)
*Tools for managing digital content.*

* 🌎 [Backdrop](backdropcms.org) - A CMS targeting small-to-medium sized business and non-profits (a fork of Drupal).
* 🌎 [Concrete5](www.concretecms.com/) - A CMS targeting users with a minimum of technical skills.
*  <b><code>&nbsp;&nbsp;2863⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;596🍴</code></b> [CraftCMS](https://github.com/craftcms/cms) - A flexible, user-friendly CMS for creating custom digital experiences on the web and beyond.
* 🌎 [Drupal](www.drupal.org) - An enterprise level CMS.
*  <b><code>&nbsp;13358⭐</code></b> <b><code>&nbsp;&nbsp;1356🍴</code></b> [Grav](https://github.com/getgrav/grav) - A modern flat-file CMS.
* 🌎 [Joomla](www.joomla.org/) - Another leading CMS.
* 🌎 [Kirby](getkirby.com/) - A flat-file CMS that adapts to any project.
* 🌎 [Magento](business.adobe.com/products/magento/magento-commerce.html) - The most popular ecommerce platform.
* 🌎 [Moodle](moodle.org/) - An open-source learning platform.
* 🌎 [Pico CMS](picocms.org/) - A stupidly simple, blazing fast, flat file CMS.
* 🌎 [Statamic](statamic.com/) - Build beautiful, easy to manage websites.
* 🌎 [WordPress](wordpress.org/) - A blogging platform and CMS.

### Components
*Standalone components from web development frameworks and development groups.*

* 🌎 [Aura](auraphp.com/) - Independent components, fully decoupled from each other and from any framework.
* 🌎 [CakePHP Plugins](plugins.cakephp.org/) - A directory of CakePHP plugins.
*  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Laravel Components](https://github.com/illuminate) - The Laravel Framework components.
* 🌎 [League of Extraordinary Packages](thephpleague.com/) - A PHP package development group.
* 🌎 [Spatie Open Source](spatie.be/open-source) - A collection of open source PHP and Laravel packages.
* 🌎 [Symfony Components](symfony.com/components) - The components that make Symfony.
* 🌎 [Laminas Components](docs.laminas.dev/components/) - The components that make the Laminas Framework.

### Micro Frameworks
*Micro frameworks and routers.*

* 🌎 [Laravel-Zero](laravel-zero.com) - A micro-framework for console applications.
* 🌎 [Lumen](lumen.laravel.com/) - A micro-framework by Laravel.
* 🌎 [Mezzio](getexpressive.org/) - A micro-framework by Laminas.
*  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;52⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7🍴</code></b> [Radar](https://github.com/radarphp/Radar.Adr) - An Action-Domain-Responder implementation for PHP.
*  <b><code>&nbsp;&nbsp;&nbsp;839⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;53🍴</code></b> [Silly](https://github.com/mnapoli/silly) - A micro-framework for CLI applications.
* 🌎 [Slim](www.slimframework.com/) - Another simple micro framework.

### Micro Framework Extras
*Extras related to micro frameworks and routers.*

*  <b><code>&nbsp;&nbsp;1445⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;448🍴</code></b> [Slim Skeleton](https://github.com/slimphp/Slim-Skeleton) - A skeleton for Slim.
*  <b><code>&nbsp;&nbsp;&nbsp;304⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;57🍴</code></b> [Slim Twig View](https://github.com/slimphp/Slim-Views) - Integrate Twig into Slim.
*  <b><code>&nbsp;&nbsp;&nbsp;225⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;59🍴</code></b> [Slim PHP View](https://github.com/slimphp/PHP-View) - A simple PHP renderer for Slim.

### Routers
*Libraries for handling application routing.*

*  <b><code>&nbsp;&nbsp;&nbsp;463⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;72🍴</code></b> [Aura.Router](https://github.com/auraphp/Aura.Router) - A full-featured routing library.
*  <b><code>&nbsp;&nbsp;4668⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;407🍴</code></b> [Fast Route](https://github.com/nikic/FastRoute) - A fast routing library.
*  <b><code>&nbsp;&nbsp;2624⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;287🍴</code></b> [Klein](https://github.com/klein/klein.php) - A flexible router.
*  <b><code>&nbsp;&nbsp;1264⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;79🍴</code></b> [Pux](https://github.com/c9s/Pux) - Another fast routing library.
*  <b><code>&nbsp;&nbsp;&nbsp;595⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;120🍴</code></b> [Route](https://github.com/thephpleague/route) - A routing library built on top of Fast Route.

### Templating
*Libraries and tools for templating and lexing.*

* 🌎 [Latte](latte.nette.org/) - The safest and truly intuitive templates for PHP.
*  <b><code>&nbsp;&nbsp;&nbsp;360⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;50🍴</code></b> [MtHaml](https://github.com/arnaud-lb/MtHaml) - A PHP implementation of the HAML template language.
*  <b><code>&nbsp;&nbsp;3138⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;416🍴</code></b> [Mustache](https://github.com/bobthecow/mustache.php) - A PHP implementation of the Mustache template language.
* 🌎 [PHPTAL](phptal.org/) - A PHP implementation of the 🌎 [TAL](en.wikipedia.org/wiki/Template_Attribute_Language) templating language.
* [Plates](http://platesphp.com/) - A native PHP templating library.
* 🌎 [Smarty](www.smarty.net/) - A template engine to complement PHP.
* 🌎 [Twig](twig.symfony.com/) - A comprehensive templating language.

### Static Site Generators
*Tools for pre-processing content to generate web pages.*

* [Couscous](http://couscous.io) - Couscous turns Markdown documentation into beautiful websites. It's GitHub Pages on steroids.
* 🌎 [Jigsaw](jigsaw.tighten.com/) - Simple static sites with Laravel's Blade.
* 🌎 [Sculpin](sculpin.io) - A tool that converts Markdown and Twig into static HTML.
* [Spress](http://spress.yosymfony.com) - An extensible tool that converts Markdown and Twig into HTML.

### HTTP
*Libraries for working with HTTP.*

*  <b><code>&nbsp;&nbsp;1880⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;250🍴</code></b> [Buzz](https://github.com/kriswallsmith/Buzz) - Another HTTP client.
* [Guzzle]( https://github.com/guzzle/guzzle) - A comprehensive HTTP client.
* [HTTPlug](http://httplug.io) - An HTTP client abstraction without binding to a specific implementation.
*  <b><code>&nbsp;&nbsp;&nbsp;917⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;67🍴</code></b> [Nyholm PSR-7](https://github.com/Nyholm/psr7) - A super lightweight PSR-7 implementation. Very strict and very fast.
* 🌎 [PHP VCR](php-vcr.github.io/) - A library for recording and replaying HTTP requests.
*  <b><code>&nbsp;&nbsp;3468⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;496🍴</code></b> [Requests](https://github.com/WordPress/Requests) - A simple HTTP library.
*  <b><code>&nbsp;&nbsp;&nbsp;152⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;24🍴</code></b> [Retrofit](https://github.com/tebru/retrofit-php) - A library to ease creation of REST API clients.
*  <b><code>&nbsp;&nbsp;1553⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;44🍴</code></b> [Symfony HTTP Client](https://github.com/symfony/http-client) - A component to fetch HTTP resources synchronously or asynchronously.
*  <b><code>&nbsp;&nbsp;&nbsp;320⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;46🍴</code></b> [Laminas Diactoros](https://github.com/laminas/laminas-diactoros) - PSR-7 HTTP Message implementation.

### Scraping
*Libraries for scraping websites.*

*  <b><code>&nbsp;&nbsp;1502⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;199🍴</code></b> [Chrome PHP](https://github.com/chrome-php/chrome) - Instrument headless Chrome/Chromium instances from PHP. 
*  <b><code>&nbsp;&nbsp;1994⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;207🍴</code></b> [DiDOM](https://github.com/Imangazaliev/DiDOM) - A super fast HTML scrapper and parser.
*  <b><code>&nbsp;&nbsp;1875⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;292🍴</code></b> [Embed](https://github.com/oscarotero/Embed) - An information extractor from any web service or page.
*  <b><code>&nbsp;&nbsp;8991⭐</code></b> <b><code>&nbsp;&nbsp;1015🍴</code></b> [Goutte](https://github.com/FriendsOfPHP/Goutte) - A simple web scraper.
*  <b><code>&nbsp;&nbsp;2591⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;205🍴</code></b> [Symfony Panther](https://github.com/symfony/panther) - A browser testing and web crawling library for PHP and Symfony.
*  <b><code>&nbsp;&nbsp;1266⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;241🍴</code></b> [PHP Spider](https://github.com/mvdbos/php-spider) - A configurable and extensible PHP web spider.

### Middlewares
*Libraries for building application using middlewares.*

*  <b><code>&nbsp;&nbsp;&nbsp;656⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;57🍴</code></b> [PSR-7 Middlewares](https://github.com/oscarotero/psr7-middlewares) - Inspiring collection of handy middlewares.
*  <b><code>&nbsp;&nbsp;&nbsp;297⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;15🍴</code></b> [Relay](https://github.com/relayphp/Relay.Relay) - A PHP 5.5 PSR-7 middleware dispatcher.
*  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Stack](https://github.com/stackphp) - A library of stackable middleware for Symfony.
*  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;40⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;12🍴</code></b> [Laminas Stratigility](https://github.com/laminas/laminas-stratigility) - Middleware for PHP built on top of PSR-7.

### URL
*Libraries for parsing URLs.*

*  <b><code>&nbsp;&nbsp;&nbsp;987⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;116🍴</code></b> [PHP Domain Parser](https://github.com/jeremykendall/php-domain-parser) - A domain suffix parser library.
*  <b><code>&nbsp;&nbsp;&nbsp;906⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;122🍴</code></b> [Purl](https://github.com/jwage/purl) - A URL manipulation library.
*  <b><code>&nbsp;&nbsp;&nbsp;277⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;20🍴</code></b> [sabre/uri](https://github.com/sabre-io/uri) - A functional URI manipulation library.
*  <b><code>&nbsp;&nbsp;&nbsp;825⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;58🍴</code></b> [Uri](https://github.com/thephpleague/uri) - Another URL manipulation library.

### Email
*Libraries for sending and parsing email.*

*  <b><code>&nbsp;&nbsp;5562⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;180🍴</code></b> [CssToInlineStyles](https://github.com/tijsverkoyen/CssToInlineStyles) - A library to inline CSS in email templates.
*  <b><code>&nbsp;&nbsp;&nbsp;597⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;76🍴</code></b> [Email Reply Parser](https://github.com/willdurand/EmailReplyParser) - An email reply parser library.
*  <b><code>&nbsp;&nbsp;&nbsp;153⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;20🍴</code></b> [Email Validator](https://github.com/nojacko/email-validator) - A small email address validation library.
*  <b><code>&nbsp;&nbsp;&nbsp;499⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;158🍴</code></b> [Fetch](https://github.com/tedious/Fetch) - An IMAP library.
*  <b><code>&nbsp;&nbsp;5234⭐</code></b> <b><code>&nbsp;&nbsp;1960🍴</code></b> [Mautic](https://github.com/mautic/mautic) - Email marketing automation
*  <b><code>&nbsp;18464⭐</code></b> <b><code>&nbsp;&nbsp;9319🍴</code></b> [PHPMailer](https://github.com/PHPMailer/PHPMailer) - Another mailer solution.
*  <b><code>&nbsp;&nbsp;1447⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;443🍴</code></b> [PHP IMAP](https://github.com/barbushin/php-imap) - A library to access mailboxes via POP3, IMAP and NNTP.
*  <b><code>&nbsp;&nbsp;&nbsp;285⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;31🍴</code></b> [Stampie](https://github.com/Stampie/Stampie) - A library for email services such as 🌎 [SendGrid](sendgrid.com/), 🌎 [PostMark](postmarkapp.com), 🌎 [MailGun](www.mailgun.com/) and 🌎 [MailChimp](mailchimp.com/features/transactional-email/).
* 🌎 [SwiftMailer](swiftmailer.symfony.com) - A mailer solution.
*  <b><code>&nbsp;&nbsp;1007⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;29🍴</code></b> [Symfony Mailer](https://github.com/symfony/mailer) - A powerful library for creating and sending emails.

### Files
*Libraries for file manipulation and MIME type detection.*

*  <b><code>&nbsp;&nbsp;2944⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;305🍴</code></b> [CSV](https://github.com/thephpleague/csv) - A CSV data manipulation library.
*  <b><code>&nbsp;12531⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;747🍴</code></b> [Flysystem](https://github.com/thephpleague/Flysystem) - Abstraction for local and remote filesystems.
*  <b><code>&nbsp;&nbsp;2421⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;337🍴</code></b> [Gaufrette](https://github.com/KnpLabs/Gaufrette) - A filesystem abstraction layer.
*  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [PHP FFmpeg](https://github.com/PHP-FFmpeg/PHP-FFmpeg/) - A wrapper for the 🌎 [FFmpeg](www.ffmpeg.org/) video library.
*  <b><code>&nbsp;&nbsp;&nbsp;257⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;19🍴</code></b> [UnifiedArchive](https://github.com/wapmorgan/UnifiedArchive) - A unified reader and writer of compressed archives.

### Streams
*Libraries for working with streams.*

* 🌎 [ByteStream](amphp.org/byte-stream/) - An asynchronous stream abstraction.
*  <b><code>&nbsp;&nbsp;&nbsp;268⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;31🍴</code></b> [Streamer](https://github.com/fzaninotto/Streamer) - A simple object-orientated stream wrapper library.

### Dependency Injection
*Libraries that implement the dependency injection design pattern.*

*  <b><code>&nbsp;&nbsp;&nbsp;338⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;64🍴</code></b> [Aura.Di](https://github.com/auraphp/Aura.Di) - A serializable dependency injection container with constructor and setter injection, interface and trait awareness, configuration inheritance, and much more.
*  <b><code>&nbsp;&nbsp;&nbsp;216⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;14🍴</code></b> [Acclimate](https://github.com/AcclimateContainer/acclimate-container) - A common interface to dependency injection containers and service locators.
*  <b><code>&nbsp;&nbsp;&nbsp;722⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;65🍴</code></b> [Auryn](https://github.com/rdlowrey/Auryn) - A recursive dependency injector.
*  <b><code>&nbsp;&nbsp;&nbsp;763⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;93🍴</code></b> [Container](https://github.com/thephpleague/container) - Another flexible dependency injection container.
*  <b><code>&nbsp;&nbsp;&nbsp;136⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;17🍴</code></b> [Disco](https://github.com/bitExpert/disco) - A PSR-11 compatible, annotation-based dependency injection container.
* 🌎 [PHP-DI](php-di.org/) - A dependency injection container that supports autowiring.
* 🌎 [Pimple](pimple.symfony.com/) - A tiny dependency injection container.
*  <b><code>&nbsp;&nbsp;3780⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;82🍴</code></b> [Symfony DI](https://github.com/symfony/dependency-injection) - A dependency injection container component.

### Imagery
*Libraries for manipulating images.*

*  <b><code>&nbsp;&nbsp;1191⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;148🍴</code></b> [Color Extractor](https://github.com/thephpleague/color-extractor) - A library for extracting colours from images.
*  <b><code>&nbsp;&nbsp;2307⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;179🍴</code></b> [Glide](https://github.com/thephpleague/glide) - An on-demand image manipulation library.
*  <b><code>&nbsp;&nbsp;1803⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;161🍴</code></b> [Image Hash](https://github.com/jenssegers/imagehash) - A library for generating perceptual image hashes.
*  <b><code>&nbsp;&nbsp;&nbsp;863⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;131🍴</code></b> [Image Optimizer](https://github.com/psliwa/image-optimizer) - A library for optimizing images.
* 🌎 [Imagine](imagine.readthedocs.io/en/latest/index.html) - An image manipulation library.
*  <b><code>&nbsp;12700⭐</code></b> <b><code>&nbsp;&nbsp;1417🍴</code></b> [Intervention Image](https://github.com/Intervention/image) - Another image manipulation library.
*  <b><code>&nbsp;&nbsp;&nbsp;855⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;191🍴</code></b> [PHP Image Workshop](https://github.com/Sybio/ImageWorkshop) - Another image manipulation library.

### Testing
*Libraries for testing codebases and generating test data.*

*  <b><code>&nbsp;&nbsp;2344⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;335🍴</code></b> [Alice](https://github.com/nelmio/alice) - An expressive fixture generation library.
*  <b><code>&nbsp;&nbsp;&nbsp;766⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;113🍴</code></b> [AspectMock](https://github.com/Codeception/AspectMock) - A mocking framework for PHPUnit/Codeception.
*  <b><code>&nbsp;&nbsp;1414⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;162🍴</code></b> [Atoum](https://github.com/atoum/atoum) - A simple testing library.
* 🌎 [Behat](docs.behat.org/en/latest/) - A behaviour driven development (BDD) testing framework.
*  <b><code>&nbsp;&nbsp;4550⭐</code></b> <b><code>&nbsp;&nbsp;1313🍴</code></b> [Codeception](https://github.com/Codeception/Codeception) - A full stack testing framework.
*  <b><code>&nbsp;&nbsp;2439⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;198🍴</code></b> [Faker](https://github.com/fakerphp/faker) - A fake data generator library.
*  <b><code>&nbsp;&nbsp;&nbsp;415⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;35🍴</code></b> [Foundry](https://github.com/zenstruck/foundry) - A fixture factory generation library for Doctrine.
*  <b><code>&nbsp;&nbsp;&nbsp;385⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;59🍴</code></b> [HTTP Mock](https://github.com/InterNations/http-mock) - A library for mocking HTTP requests in unit tests.
*  <b><code>&nbsp;&nbsp;1732⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;142🍴</code></b> [Infection](https://github.com/infection/infection) - An AST-based PHP Mutation testing framework.
*  <b><code>&nbsp;&nbsp;1105⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;67🍴</code></b> [Kahlan](https://github.com/kahlan/kahlan) - Full stack Unit/BDD testing framework with built-in stub, mock and code-coverage support.
* 🌎 [Mink](mink.behat.org/en/latest/) - Web acceptance testing.
*  <b><code>&nbsp;10218⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;446🍴</code></b> [Mockery](https://github.com/mockery/mockery) - A mock object library for testing.
*  <b><code>&nbsp;&nbsp;1928⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;202🍴</code></b> [ParaTest](https://github.com/paratestphp/paratest) - A parallel testing library for PHPUnit.
* 🌎 [Pest](pestphp.com/) - A testing framework with a focus on simplicity.
*  <b><code>&nbsp;&nbsp;&nbsp;329⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;28🍴</code></b> [Peridot](https://github.com/peridot-php/peridot) - An event driven test framework.
*  <b><code>&nbsp;&nbsp;&nbsp;463⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;86🍴</code></b> [Phake](https://github.com/phake/phake) - Another mock object library for testing.
*  <b><code>&nbsp;&nbsp;&nbsp;284⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;13🍴</code></b> [Pho](https://github.com/danielstjules/pho) - Another behaviour driven development testing framework.
*  <b><code>&nbsp;&nbsp;&nbsp;320⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;15🍴</code></b> [PHP-Mock](https://github.com/php-mock/php-mock) - A mock library for built-in PHP functions (e.g. time()).
*  <b><code>&nbsp;&nbsp;&nbsp;510⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;35🍴</code></b> [PHP MySQL Engine](https://github.com/vimeo/php-mysql-engine) -  A MySQL engine written in pure PHP. 
*  <b><code>&nbsp;&nbsp;1814⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;280🍴</code></b> [PHPSpec](https://github.com/phpspec/phpspec) - A design by specification unit testing library.
* 🌎 [PHPT](qa.php.net/write-test.php) - A test tool used by PHP itself.
*  <b><code>&nbsp;18554⭐</code></b> <b><code>&nbsp;&nbsp;2113🍴</code></b> [PHPUnit](https://github.com/sebastianbergmann/phpunit) - A unit testing framework.
*  <b><code>&nbsp;&nbsp;8459⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;230🍴</code></b> [Prophecy](https://github.com/phpspec/prophecy) - A highly opinionated mocking framework.
*  <b><code>&nbsp;&nbsp;1338⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;107🍴</code></b> [VFS Stream](https://github.com/bovigo/vfsStream) - A virtual filesystem stream wrapper for testing.

### Continuous Integration
*Libraries and applications for continuous integration.*

* 🌎 [CircleCI](circleci.com) - A continuous integration platform.
* 🌎 [GitlabCi](about.gitlab.com/stages-devops-lifecycle/continuous-integration/) - Let GitLab CI test, build, deploy your code. TravisCi like.
* 🌎 [Jenkins](www.jenkins.io/) - A continuous integration platform with 🌎 [PHP support](www.jenkins.io/solutions/php/).
*  <b><code>&nbsp;&nbsp;&nbsp;658⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;47🍴</code></b> [JoliCi](https://github.com/jolicode/JoliCi) - A continuous integration client written in PHP and powered by Docker.
*  <b><code>&nbsp;&nbsp;2429⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;469🍴</code></b> [PHPCI](https://github.com/dancryer/phpci) - An open source continuous integration platform for PHP.
* 🌎 [SemaphoreCI](semaphoreci.com/) - A continuous integration platform for open source and private projects.
* 🌎 [Shippable](jfrog.com/blog/weve-acquired-shippable-to-complete-devops-pipeline-automation-from-code-to-production/) - A Docker based continious integration platform for open source and private projects.
* 🌎 [Travis CI](travis-ci.org/) - A continuous integration platform.
*  <b><code>&nbsp;&nbsp;2201⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;252🍴</code></b> [Setup PHP](https://github.com/shivammathur/setup-php) - A GitHub Action for PHP.

### Documentation
*Libraries for generating project documentation.*

*  <b><code>&nbsp;&nbsp;2094⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;320🍴</code></b> [APIGen](https://github.com/apigen/apigen) - Another API documentation generator.
*  <b><code>&nbsp;&nbsp;&nbsp;699⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;180🍴</code></b> [daux.io](https://github.com/dauxio/daux.io) - A documentation generator which uses Markdown files.
*  <b><code>&nbsp;&nbsp;3597⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;609🍴</code></b> [PHP Documentor 2](https://github.com/phpDocumentor/phpDocumentor) - A documentation generator.
* 🌎 [phpDox](phpdox.net/) - A documentation generator for PHP projects (that is not limited to API documentation).

### Security
*Libraries for generating secure random numbers, encrypting data and scanning and testing for vulnerabilities.*

* 🌎 [Halite](paragonie.com/project/halite) - A simple library for encryption using  <b><code>&nbsp;10289⭐</code></b> <b><code>&nbsp;&nbsp;1588🍴</code></b> [libsodium](https://github.com/jedisct1/libsodium).
*  <b><code>&nbsp;&nbsp;2541⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;294🍴</code></b> [HTML Purifier](https://github.com/ezyang/htmlpurifier) - A standards compliant HTML filter.
*  <b><code>&nbsp;&nbsp;1456⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;102🍴</code></b> [IniScan](https://github.com/psecio/iniscan) - A tool that scans PHP INI files for security.
*  <b><code>&nbsp;&nbsp;1175⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;70🍴</code></b> [Optimus](https://github.com/jenssegers/optimus) - Id obfuscation based on Knuth's multiplicative hashing method.
*  <b><code>&nbsp;&nbsp;2276⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;401🍴</code></b> [PHPGGC](https://github.com/ambionics/phpggc) - A library of PHP unserializable payloads along with a tool to generate them.
*  <b><code>&nbsp;&nbsp;3497⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;310🍴</code></b> [PHP Encryption](https://github.com/defuse/php-encryption) - Secure PHP Encryption Library.
*  <b><code>&nbsp;&nbsp;&nbsp;353⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;84🍴</code></b> [PHP SSH](https://github.com/Herzult/php-ssh) - An experimental object orientated SSH wrapper library.
* [PHPSecLib](http://phpseclib.sourceforge.net/) - A pure PHP secure communications library.
*  <b><code>&nbsp;&nbsp;8003⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;119🍴</code></b> [random_compat](https://github.com/paragonie/random_compat) - PHP 5.x support for `random_bytes()` and `random_int()`
*  <b><code>&nbsp;&nbsp;&nbsp;828⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;118🍴</code></b> [RandomLib](https://github.com/ircmaxell/RandomLib) - A library for generating random numbers and strings.
* 🌎 [Symfony Security Monitoring](security.symfony.com/) - A web tool to check your Composer dependencies for security advisories, previously known as "SensioLabs Security Check".
*  <b><code>&nbsp;24075⭐</code></b> <b><code>&nbsp;&nbsp;4900🍴</code></b> [SQLMap](https://github.com/sqlmapproject/sqlmap) - An automatic SQL injection and database takeover tool. 
*  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;55⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;13🍴</code></b> [TCrypto](https://github.com/timoh6/TCrypto) - A simple encrypted key-value storage library.
* 🌎 [VAddy](vaddy.net/) - A continuous security testing platform for web applications.
* 🌎 [Zap](owasp.org/www-project-zap/) - An integrated penetration testing tool for web applications.

### Passwords
*Libraries and tools for working with and storing passwords.*

*  <b><code>&nbsp;&nbsp;&nbsp;106⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8🍴</code></b> [GenPhrase](https://github.com/timoh6/GenPhrase) - A library for generating secure random passphrases.
*  <b><code>&nbsp;&nbsp;2152⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;431🍴</code></b> [Password Compat](https://github.com/ircmaxell/password_compat) - A compatibility library for the new PHP 5.5 password functions.
*  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;73⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;18🍴</code></b> [Password Policy](https://github.com/ircmaxell/password-policy) - A password policy library for PHP and JavaScript.
*  <b><code>&nbsp;&nbsp;&nbsp;142⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;15🍴</code></b> [Password Validator](https://github.com/jeremykendall/password-validator) - A library for validating and upgrading password hashes.
*  <b><code>&nbsp;&nbsp;&nbsp;250⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;33🍴</code></b> [Password-Generator](https://github.com/hackzilla/password-generator) - PHP library to generate random passwords.
*  <b><code>&nbsp;&nbsp;&nbsp;370⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;61🍴</code></b> [PHP Password Lib](https://github.com/ircmaxell/PHP-PasswordLib) - A library for generating and validating passwords.
* 🌎 [phpass](www.openwall.com/phpass/) - A portable password hashing framework.
*  <b><code>&nbsp;&nbsp;&nbsp;740⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;101🍴</code></b> [Zxcvbn PHP](https://github.com/bjeavons/zxcvbn-php) - A realistic PHP password strength estimate library based on Zxcvbn JS.

### Code Analysis
*Libraries and tools for analysing, parsing and manipulating codebases.*

*  <b><code>&nbsp;&nbsp;1037⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;117🍴</code></b> [Better Reflection](https://github.com/Roave/BetterReflection) - AST-based reflection library that allows analysis and manipulation of code
* 🌎 [Code Climate](codeclimate.com) - An automated code review.
*  <b><code>&nbsp;&nbsp;3785⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;410🍴</code></b> [GrumPHP](https://github.com/phpro/grumphp) - A PHP code-quality tool.
*  <b><code>&nbsp;15534⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;887🍴</code></b> [PHP Parser](https://github.com/nikic/PHP-Parser) - A PHP parser written in PHP.
*  <b><code>&nbsp;&nbsp;&nbsp;422⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;24🍴</code></b> [PHP Semantic Versioning Checker](https://github.com/tomzx/php-semver-checker) - A command line utility that compares two source sets and determines the appropriate semantic versioning to apply.
*  <b><code>&nbsp;&nbsp;&nbsp;805⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;79🍴</code></b> [Phpactor](https://github.com/phpactor/phpactor) - PHP completion, refactoring and introspection tool.
*  <b><code>&nbsp;&nbsp;2228⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;164🍴</code></b> [PHPLOC](https://github.com/sebastianbergmann/phploc) - A tool for quickly measuring the size of a PHP project.
*  <b><code>&nbsp;&nbsp;&nbsp;538⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;59🍴</code></b> [PHPQA](https://github.com/EdgedesignCZ/phpqa) - A tool for running QA tools (phploc, phpcpd, phpcs, pdepend, phpmd, phpmetrics).
*  <b><code>&nbsp;&nbsp;&nbsp;493⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;32🍴</code></b> [Qafoo Quality Analyzer](https://github.com/Qafoo/QualityAnalyzer) - A tool to visualize metrics and source code.
*  <b><code>&nbsp;&nbsp;5553⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;518🍴</code></b> [Rector](https://github.com/rectorphp/rector) - A tool to upgrade and refactor code.
* 🌎 [Scrutinizer](scrutinizer-ci.com/) - A web tool to  <b><code>&nbsp;&nbsp;&nbsp;441⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;56🍴</code></b> [scrutinise PHP code](https://github.com/scrutinizer-ci/php-analyzer).
*  <b><code>&nbsp;&nbsp;&nbsp;545⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;68🍴</code></b> [UBench](https://github.com/devster/ubench) - A simple micro benchmark library.

### Code Quality
*Libraries for managing code quality, formatting and linting.*

*  <b><code>&nbsp;&nbsp;&nbsp;757⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;68🍴</code></b> [CaptainHook](https://github.com/captainhookphp/captainhook) - An easy-to-use and flexible Git hook library. 
*  <b><code>&nbsp;&nbsp;9548⭐</code></b> <b><code>&nbsp;&nbsp;1455🍴</code></b> [PHP CodeSniffer](https://github.com/squizlabs/PHP_CodeSniffer) - A library that detects PHP, CSS and JS coding standard violations.
*  <b><code>&nbsp;11255⭐</code></b> <b><code>&nbsp;&nbsp;1422🍴</code></b> [PHP CS Fixer](https://github.com/FriendsOfPHP/PHP-CS-Fixer) - A coding standards fixer library.
*  <b><code>&nbsp;&nbsp;2072⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;347🍴</code></b> [PHP Mess Detector](https://github.com/phpmd/phpmd) - A library that scans code for bugs, sub-optimal code, unused parameters and more.
*  <b><code>&nbsp;&nbsp;&nbsp;154⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;30🍴</code></b> [PHPCheckstyle](https://github.com/PHPCheckstyle/phpcheckstyle) - A tool to help adhere to certain coding conventions.
*  <b><code>&nbsp;&nbsp;2190⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;176🍴</code></b> [PHPCPD](https://github.com/sebastianbergmann/phpcpd) - A library that detects copied and pasted code.

### Static Analysis
*Libraries for performing static analysis of PHP code.*

*  <b><code>&nbsp;&nbsp;&nbsp;368⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;41🍴</code></b> [Exakat](https://github.com/exakat/exakat) - A static analysis engine for PHP.
*  <b><code>&nbsp;&nbsp;1974⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;96🍴</code></b> [Deptrac](https://github.com/qossmic/deptrac) - A static code analysis tool that helps to enforce rules for dependencies between software layers.
*  <b><code>&nbsp;&nbsp;&nbsp;392⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;21🍴</code></b> [Mondrian](https://github.com/Trismegiste/Mondrian) - A code analysis tool using Graph Theory.
*  <b><code>&nbsp;&nbsp;5292⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;361🍴</code></b> [phan](https://github.com/phan/phan) - A static analyzer based on PHP 7+ and the php-ast extension.
*  <b><code>&nbsp;&nbsp;&nbsp;719⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;27🍴</code></b> [PHP Architecture Tester](https://github.com/carlosas/phpat) - Easy to use architecture testing tool for PHP.
*  <b><code>&nbsp;&nbsp;1809⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;160🍴</code></b> [PHPCompatibility](https://github.com/PHPCompatibility/PHPCompatibility) - A PHP compatibility checker for PHP CodeSniffer.
*  <b><code>&nbsp;&nbsp;&nbsp;542⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;41🍴</code></b> [PhpDependencyAnalysis](https://github.com/mamuz/PhpDependencyAnalysis) - A tool to create customisable dependency graphs.
*  <b><code>&nbsp;&nbsp;2236⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;255🍴</code></b> [PHP Metrics](https://github.com/phpmetrics/PhpMetrics) - A static metric library.
*  <b><code>&nbsp;&nbsp;&nbsp;194⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;19🍴</code></b> [PHP Migration](https://github.com/monque/PHP-Migration) - A static analyzer for PHP version migration.
*  <b><code>&nbsp;11177⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;802🍴</code></b> [PHPStan](https://github.com/phpstan/phpstan) - A PHP Static Analysis Tool.
*  <b><code>&nbsp;&nbsp;4847⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;537🍴</code></b> [Psalm](https://github.com/vimeo/psalm) - A static analysis tool for finding errors in PHP applications.

### Architectural
*Libraries related to design patterns, programming approaches and ways to organize code.*

*  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Design Patterns PHP](https://github.com/DesignPatternsPHP/DesignPatternsPHP ) - A repository of software patterns implemented in PHP.
* 🌎 [Finite](yohan.giarel.li/Finite/) - A simple PHP finite state machine.
*  <b><code>&nbsp;&nbsp;1883⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;198🍴</code></b> [Functional PHP](https://github.com/lstrojny/functional-php) - A functional programming library.
*  <b><code>&nbsp;&nbsp;1070⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;70🍴</code></b> [Iter](https://github.com/nikic/iter) - A library that provides iteration primitives using generators.
* 🌎 [Patchwork](patchwork2.org/) - A library for redefining userland functions.
*  <b><code>&nbsp;&nbsp;&nbsp;859⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;71🍴</code></b> [Pipeline](https://github.com/thephpleague/pipeline) - A pipeline pattern implementation.
*  <b><code>&nbsp;&nbsp;&nbsp;555⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;24🍴</code></b> [Porter](https://github.com/ScriptFUSION/Porter) - Data import abstraction library for consuming Web APIs and other data sources.
*  <b><code>&nbsp;&nbsp;&nbsp;861⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;78🍴</code></b> [RulerZ](https://github.com/K-Phoen/rulerz) - A powerful rule engine and implementation of the Specification pattern.

### Debugging and Profiling
*Libraries and tools for debugging errors and profiling code.*

* 🌎 [APM](pecl.php.net/package/APM) - Monitoring extension collecting errors and statistics into SQLite/MySQL/StatsD.
*  <b><code>&nbsp;&nbsp;1352⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;301🍴</code></b> [Barbushin PHP Console](https://github.com/barbushin/php-console) - Another web debugging console using Google Chrome.
* 🌎 [Blackfire.io](www.blackfire.io) - A low-overhead code profiler.
*  <b><code>&nbsp;&nbsp;2630⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;283🍴</code></b> [Kint](https://github.com/kint-php/kint) - A debugging and profiling tool.
*  <b><code>&nbsp;&nbsp;&nbsp;312⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;39🍴</code></b> [Metrics](https://github.com/beberlei/metrics) - A simple metrics API library.
*  <b><code>&nbsp;&nbsp;&nbsp;579⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;18🍴</code></b> [PCOV](https://github.com/krakjoe/pcov) - A self contained code coverage compatible driver.
*  <b><code>&nbsp;&nbsp;&nbsp;515⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;99🍴</code></b> [PHP Console](https://github.com/Seldaek/php-console) - A web debugging console.
* [PHP Debug Bar](http://phpdebugbar.com/) - A debugging toolbar.
*  <b><code>&nbsp;&nbsp;1611⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;110🍴</code></b> [PHPBench](https://github.com/phpbench/phpbench) - A benchmarking Framework.
*  <b><code>&nbsp;&nbsp;1267⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;55🍴</code></b> [PHPSpy](https://github.com/adsr/phpspy) - A low-overhead sampling profiler.
*  <b><code>&nbsp;&nbsp;6989⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;94🍴</code></b> [Symfony VarDumper](https://github.com/symfony/var-dumper) - A variable dumper component.
* 🌎 [Tideways.io](tideways.com/) - Monitoring and profiling tool.
*  <b><code>&nbsp;&nbsp;1540⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;216🍴</code></b> [Tracy](https://github.com/nette/tracy) - A simple error detection, logging and time measuring library.
*  <b><code>&nbsp;12783⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;595🍴</code></b> [Whoops](https://github.com/filp/whoops) - A pretty error handling library.
*  <b><code>&nbsp;&nbsp;2668⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;519🍴</code></b> [xDebug](https://github.com/xdebug/xdebug) - A debug and profile tool for PHP.
*  <b><code>&nbsp;&nbsp;2538⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;921🍴</code></b> [XHProf](https://github.com/phacility/xhprof) - A profiling tool originally developed by Facebook.
* 🌎 [Z-Ray](www.zend.com/products/z-ray) - A debug and profile tool for Zend Server.

### Build Tools
*Project build and automation tools.*

*  <b><code>&nbsp;&nbsp;&nbsp;799⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;82🍴</code></b> [Box](https://github.com/box-project/box) - A utility to build PHAR files.
*  <b><code>&nbsp;&nbsp;&nbsp;261⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;17🍴</code></b> [Construct](https://github.com/jonathantorres/construct) - A PHP project/micro-package generator.
* 🌎 [Phing](www.phing.info/) - A PHP project build system inspired by Apache Ant.
*  <b><code>&nbsp;&nbsp;&nbsp;440⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;45🍴</code></b> [RMT](https://github.com/liip/RMT) - A library for versioning and releasing software.

### Task Runners
*Libraries for automating and running tasks.*

* 🌎 [Bldr](bldr.io/) - A PHP Task runner built on Symfony components.
*  <b><code>&nbsp;&nbsp;1016⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;155🍴</code></b> [Jobby](https://github.com/jobbyphp/jobby) - A PHP cron job manager without modifying crontab.
*  <b><code>&nbsp;&nbsp;2479⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;298🍴</code></b> [Robo](https://github.com/consolidation/Robo) - A PHP Task runner with object-orientated configurations.
* 🌎 [Task](taskphp.github.io/) - A pure PHP task runner inspired by Grunt and Gulp.

### Navigation
*Tools for building navigation structures.*

*  <b><code>&nbsp;&nbsp;1296⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;195🍴</code></b> [KnpMenu](https://github.com/KnpLabs/KnpMenu) - A menu library.
*  <b><code>&nbsp;&nbsp;&nbsp;630⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;85🍴</code></b> [Menu](https://github.com/spatie/menu) - A flexible menu library with a fluent interface.

### Asset Management
*Tools for managing, compressing and minifying website assets.*

*  <b><code>&nbsp;&nbsp;&nbsp;666⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;144🍴</code></b> [JShrink](https://github.com/tedious/JShrink) - A JavaScript minifier library.
*  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Laravel Mix](https://github.com/laravel-mix/laravel-mix ) - An elegant wrapper around Webpack for the 80% use case.
*  <b><code>&nbsp;&nbsp;2882⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;15🍴</code></b> [Symfony Asset](https://github.com/symfony/asset) - Manages URL generation and versioning of web assets.
*  <b><code>&nbsp;&nbsp;2068⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;193🍴</code></b> [Symfony Encore](https://github.com/symfony/webpack-encore) - A simple but powerful API for processing and compiling assets built around Webpack.

### Geolocation
*Libraries for geocoding addresses and working with latitudes and longitudes.*

*  <b><code>&nbsp;&nbsp;4950⭐</code></b> <b><code>&nbsp;&nbsp;1535🍴</code></b> [Country List](https://github.com/umpirsky/country-list) - A list of all countries with names and ISO 3166-1 codes.
* 🌎 [GeoCoder](geocoder-php.org/) - A geocoding library.
*  <b><code>&nbsp;&nbsp;&nbsp;268⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;40🍴</code></b> [GeoJSON](https://github.com/jmikola/geojson) - A GeoJSON implementation.
*  <b><code>&nbsp;&nbsp;1263⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;119🍴</code></b> [GeoTools](https://github.com/thephpleague/geotools) - A library of geo-related tools.
*  <b><code>&nbsp;&nbsp;1406⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;186🍴</code></b> [PHPGeo](https://github.com/mjaschen/phpgeo) - A simple geo library.

### Date and Time
*Libraries for working with dates and times.*

* 🌎 [CalendR](yohan.giarel.li/CalendR/) - A calendar management library.
*  <b><code>&nbsp;15827⭐</code></b> <b><code>&nbsp;&nbsp;1219🍴</code></b> [Carbon](https://github.com/briannesbitt/Carbon) - A simple DateTime API extension.
*  <b><code>&nbsp;&nbsp;1283⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;54🍴</code></b> [Chronos](https://github.com/cakephp/chronos) - A DateTime API extension supporting both mutable and immutable date/time.
*  <b><code>&nbsp;&nbsp;&nbsp;937⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;152🍴</code></b> [Moment.php](https://github.com/fightbulc/moment.php) - Moment.js inspired PHP DateTime handler with i18n support.
*  <b><code>&nbsp;&nbsp;&nbsp;877⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;129🍴</code></b> [Yasumi](https://github.com/azuyalabs/yasumi) - An library to help you calculate the dates and names of holidays.

### Event
*Libraries that are event-driven or implement non-blocking event loops.*
*  <b><code>&nbsp;&nbsp;3647⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;221🍴</code></b> [Amp](https://github.com/amphp/amp) - An event driven non-blocking I/O library.
*  <b><code>&nbsp;&nbsp;1433⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;179🍴</code></b> [Broadway](https://github.com/broadway/broadway) - An event source and CQRS library.
*  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;19⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6🍴</code></b> [CakePHP Event](https://github.com/cakephp/event) - An event dispatcher library.
*  <b><code>&nbsp;&nbsp;1169⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;343🍴</code></b> [Elephant.io](https://github.com/Wisembly/Elephant.io) - Yet another web socket library.
*  <b><code>&nbsp;&nbsp;1168⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;69🍴</code></b> [Evenement](https://github.com/igorw/evenement) - An event dispatcher library.
*  <b><code>&nbsp;&nbsp;1441⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;41🍴</code></b> [Event](https://github.com/thephpleague/event) - An event library with a focus on domain events.
*  <b><code>&nbsp;&nbsp;&nbsp;515⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;77🍴</code></b> [Pawl](https://github.com/ratchetphp/Pawl) - An asynchronous web socket client.
*  <b><code>&nbsp;&nbsp;&nbsp;528⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;75🍴</code></b> [Prooph Event Store](https://github.com/prooph/event-store) - An event source component to persist event messages
*  <b><code>&nbsp;&nbsp;&nbsp;238⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;14🍴</code></b> [PHP Defer](https://github.com/php-defer/php-defer) - Golang's defer statement for PHP.
*  <b><code>&nbsp;&nbsp;5772⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;657🍴</code></b> [Ratchet](https://github.com/ratchetphp/Ratchet) - A web socket library.
*  <b><code>&nbsp;&nbsp;8376⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;749🍴</code></b> [ReactPHP](https://github.com/reactphp/reactphp) - An event driven non-blocking I/O library.
*  <b><code>&nbsp;&nbsp;1620⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;134🍴</code></b> [RxPHP](https://github.com/ReactiveX/RxPHP) - A reactive extension library.
*  <b><code>&nbsp;17483⭐</code></b> <b><code>&nbsp;&nbsp;3188🍴</code></b> [Swoole](https://github.com/swoole/swoole-src) - An event-driven asynchronous and concurrent networking communication framework with high performance for PHP written in C.
*  <b><code>&nbsp;&nbsp;9958⭐</code></b> <b><code>&nbsp;&nbsp;2211🍴</code></b> [Workerman](https://github.com/walkor/Workerman) - An event driven non-blocking I/O library.

### Logging
*Libraries for generating and working with log files.*

*  <b><code>&nbsp;19796⭐</code></b> <b><code>&nbsp;&nbsp;1826🍴</code></b> [Monolog](https://github.com/Seldaek/monolog) - A comprehensive logger.

### E-commerce
*Libraries and applications for taking payments and building online e-commerce stores.*

*  <b><code>&nbsp;&nbsp;4040⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;406🍴</code></b> [Money](https://github.com/moneyphp/money) - A PHP implementation of Fowler's money pattern.
*  <b><code>&nbsp;&nbsp;1128⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;60🍴</code></b> [Brick\Money](https://github.com/brick/money) - A money library for PHP, with support for contexts, cash roundings, currency conversion.
*  <b><code>&nbsp;&nbsp;5594⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;884🍴</code></b> [OmniPay](https://github.com/thephpleague/omnipay) - A framework agnostic multi-gateway payment processing library.
*  <b><code>&nbsp;&nbsp;1696⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;338🍴</code></b> [Payum](https://github.com/payum/payum) - A payment abstraction library.
*  <b><code>&nbsp;&nbsp;1282⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;840🍴</code></b> [Shopware](https://github.com/shopware/shopware) - Highly customizable e-commerce software
*  <b><code>&nbsp;&nbsp;1240⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;107🍴</code></b> [Swap](https://github.com/florianv/swap) - An exchange rates library.
* 🌎 [Sylius](sylius.com/) - An open source e-commerce solution.

### PDF
*Libraries and software for working with PDF files.*

*  <b><code>&nbsp;&nbsp;8981⭐</code></b> <b><code>&nbsp;&nbsp;1664🍴</code></b> [Dompdf](https://github.com/dompdf/dompdf) - A HTML to PDF converter.
*  <b><code>&nbsp;&nbsp;&nbsp;333⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;77🍴</code></b> [PHPPdf](https://github.com/psliwa/PHPPdf) - A library for generating PDFs and images from XML.
*  <b><code>&nbsp;&nbsp;4074⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;421🍴</code></b> [Snappy](https://github.com/KnpLabs/snappy) - A PDF and image generation library.
*  <b><code>&nbsp;12418⭐</code></b> <b><code>&nbsp;&nbsp;1620🍴</code></b> [WKHTMLToPDF](https://github.com/wkhtmltopdf/wkhtmltopdf) - A tool to convert HTML to PDF.

### Office
*Libraries for working with office suite documents.*

*  <b><code>&nbsp;&nbsp;1176⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;478🍴</code></b> [PHPPowerPoint](https://github.com/PHPOffice/PHPPresentation) - A library for working with Microsoft PowerPoint Presentations.
*  <b><code>&nbsp;&nbsp;6304⭐</code></b> <b><code>&nbsp;&nbsp;2486🍴</code></b> [PHPWord](https://github.com/PHPOffice/PHPWord) - A library for working with Microsoft Word documents.
*  <b><code>&nbsp;11342⭐</code></b> <b><code>&nbsp;&nbsp;2720🍴</code></b> [PHPSpreadsheet](https://github.com/PHPOffice/PhpSpreadsheet) - A pure PHP library for reading and writing spreadsheet files (successor of PHPExcel).
*  <b><code>&nbsp;&nbsp;4123⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;571🍴</code></b> [Spout](https://github.com/box/spout) - Read and write spreadsheet files (CSV, XLSX and ODS), in a fast and scalable way .

### Database
*Libraries for interacting with databases using object-relational mapping (ORM) or datamapping techniques.*

*  <b><code>&nbsp;&nbsp;&nbsp;429⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;23🍴</code></b> [Atlas.Orm](https://github.com/atlasphp/Atlas.Orm) - A data mapper implementation for your persistence model in PHP.
*  <b><code>&nbsp;&nbsp;&nbsp;522⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;93🍴</code></b> [Aura.Sql](https://github.com/auraphp/Aura.Sql) - Provides an extension to the native PDO along with a profiler and connection locator.
*  <b><code>&nbsp;&nbsp;&nbsp;410⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;82🍴</code></b> [Aura.SqlQuery](https://github.com/auraphp/Aura.SqlQuery) - Independent query builders for MySQL, PostgreSQL, SQLite, and Microsoft SQL Server.
*  <b><code>&nbsp;&nbsp;2201⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;468🍴</code></b> [Baum](https://github.com/etrepat/baum) - A nested set implementation for Eloquent.
*  <b><code>&nbsp;&nbsp;&nbsp;145⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;19🍴</code></b> [CakePHP ORM](https://github.com/cakephp/orm) - Object-Relational Mapper, implemented using the DataMapper pattern.
*  <b><code>&nbsp;&nbsp;1033⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;58🍴</code></b> [Cycle ORM](https://github.com/cycle/orm) - PHP DataMapper, ORM.
*  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Doctrine Extensions](https://github.com/doctrine-extensions/DoctrineExtensions ) - A collection of Doctrine behavioural extensions.
* 🌎 [Doctrine](www.doctrine-project.org/) - A comprehensive DBAL and ORM.
*  <b><code>&nbsp;&nbsp;2450⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;565🍴</code></b> [Laravel Eloquent](https://github.com/illuminate/database) - A simple ORM.
*  <b><code>&nbsp;&nbsp;&nbsp;161⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;32🍴</code></b> [Pomm](https://github.com/chanmix51/Pomm) - An Object Model Manager for PostgreSQL.
*  <b><code>&nbsp;&nbsp;4732⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;196🍴</code></b> [ProxyManager](https://github.com/Ocramius/ProxyManager) - A set of utilities to generate proxy objects for data mappers.
* 🌎 [RedBean](redbeanphp.com/index.php) - A lightweight, configuration-less ORM.
*  <b><code>&nbsp;&nbsp;&nbsp;176⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;23🍴</code></b> [Slimdump](https://github.com/webfactory/slimdump) - An easy dumper tool for MySQL.
*  <b><code>&nbsp;&nbsp;&nbsp;600⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;100🍴</code></b> [Spot2](https://github.com/spotorm/spot2) - A MySQL datamapper ORM.

### Migrations
Libraries to help manage database schemas and migrations.

* 🌎 [Doctrine Migrations](www.doctrine-project.org/projects/migrations.html) - A migration library for Doctrine.
*  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;38⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1🍴</code></b> [Migrations](https://github.com/icomefromthenet/Migrations) - A migration management library.
*  <b><code>&nbsp;&nbsp;4292⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;899🍴</code></b> [Phinx](https://github.com/cakephp/phinx) - Another database migration library.
*  <b><code>&nbsp;&nbsp;&nbsp;556⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;88🍴</code></b> [PHPMig](https://github.com/davedevelopment/phpmig) - Another migration management library.
*  <b><code>&nbsp;&nbsp;&nbsp;507⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;89🍴</code></b> [Ruckusing](https://github.com/ruckus/ruckusing-migrations) - Database migrations for PHP ala ActiveRecord Migrations with support for MySQL, Postgres, SQLite.

### NoSQL
*Libraries for working with "NoSQL" backends.*

*  <b><code>&nbsp;&nbsp;&nbsp;238⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;48🍴</code></b> [PHPMongo](https://github.com/sokil/php-mongo) - A MongoDB ORM.
*  <b><code>&nbsp;&nbsp;7121⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;943🍴</code></b> [Predis](https://github.com/predis/predis) - A feature complete Redis library.

### Queue
*Libraries for working with event and task queues.*

*  <b><code>&nbsp;&nbsp;1180⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;125🍴</code></b> [Bernard](https://github.com/bernardphp/bernard) - A multibackend abstraction library.
*  <b><code>&nbsp;&nbsp;&nbsp;619⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;79🍴</code></b> [BunnyPHP](https://github.com/jakubkulhan/bunny) - A performant pure-PHP AMQP (RabbitMQ) sync and also async (ReactPHP) library.
*  <b><code>&nbsp;&nbsp;1846⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;269🍴</code></b> [Pheanstalk](https://github.com/pheanstalk/pheanstalk) - A Beanstalkd client library.
*  <b><code>&nbsp;&nbsp;4098⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;997🍴</code></b> [PHP AMQP](https://github.com/php-amqplib/php-amqplib) - A pure PHP AMQP library.
*  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;60⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2🍴</code></b> [Tarantool Queue](https://github.com/tarantool-php/queue) - PHP bindings for Tarantool Queue.
*  <b><code>&nbsp;&nbsp;&nbsp;275⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;61🍴</code></b> [Thumper](https://github.com/php-amqplib/Thumper) - A RabbitMQ pattern library.
*  <b><code>&nbsp;&nbsp;2038⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;403🍴</code></b> [Enqueue](https://github.com/php-enqueue/enqueue-dev) - A message queue packages for PHP that supports RabbitMQ, AMQP, STOMP, Amazon SQS, Redis and Doctrine transports. 

### Search
*Libraries and software for indexing and performing search queries on data.*

*  <b><code>&nbsp;&nbsp;2181⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;719🍴</code></b> [Elastica](https://github.com/ruflin/Elastica) - A client library for ElasticSearch.
*  <b><code>&nbsp;&nbsp;4912⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;937🍴</code></b> [ElasticSearch PHP](https://github.com/elastic/elasticsearch-php) - The official client library for 🌎 [ElasticSearch](www.elastic.co/).
* 🌎 [Solarium](www.solarium-project.org/) - A client library for 🌎 [Solr](solr.apache.org/).
* 🌎 [SphinxQL Query Builder](foolcode.github.io/SphinxQL-Query-Builder/) - A query library for the 🌎 [Sphinx](sphinxsearch.com/) and 🌎 [Manticore](manticoresearch.com/) search engines.

### Command Line
*Libraries related to the command line.*

*  <b><code>&nbsp;&nbsp;&nbsp;101⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;21🍴</code></b> [Aura.Cli](https://github.com/auraphp/Aura.Cli) - Provides the equivalent of request ( Context ) and response ( Stdio ) objects for the command line interface, including Getopt support, and an independent Help object for describing commands.
*  <b><code>&nbsp;&nbsp;2177⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;118🍴</code></b> [Boris](https://github.com/borisrepl/boris) - A tiny PHP REPL.
*  <b><code>&nbsp;&nbsp;&nbsp;621⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;73🍴</code></b> [Cilex](https://github.com/Cilex/Cilex) - A micro framework for building command line tools.
*  <b><code>&nbsp;&nbsp;1829⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;100🍴</code></b> [CLI Menu](https://github.com/php-school/cli-menu) - A library for building CLI menus.
*  <b><code>&nbsp;&nbsp;&nbsp;421⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;50🍴</code></b> [CLIFramework](https://github.com/c9s/CLIFramework) - A command-line framework supports zsh/bash completion generation, subcommands and option constraints. It also powers phpbrew.
*  <b><code>&nbsp;&nbsp;1808⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;122🍴</code></b> [CLImate](https://github.com/thephpleague/climate) - A library for outputting colours and special formatting.
*  <b><code>&nbsp;&nbsp;&nbsp;791⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;79🍴</code></b> [Commando](https://github.com/nategood/commando) - Another simple command line opt parser.
*  <b><code>&nbsp;&nbsp;4900⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;316🍴</code></b> [Cron Expression](https://github.com/mtdowling/cron-expression) - A library to calculate cron run dates.
*  <b><code>&nbsp;&nbsp;&nbsp;319⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;63🍴</code></b> [GetOpt](https://github.com/getopt-php/getopt-php) - A command line opt parser.
*  <b><code>&nbsp;&nbsp;&nbsp;140⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;22🍴</code></b> [GetOptionKit](https://github.com/c9s/GetOptionKit) - Another command line opt parser.
*  <b><code>&nbsp;&nbsp;9318⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;287🍴</code></b> [PsySH](https://github.com/bobthecow/psysh) - Another PHP REPL.
*  <b><code>&nbsp;&nbsp;&nbsp;741⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;58🍴</code></b> [ShellWrap](https://github.com/MrRio/shellwrap) - A simple command line wrapper library.

### Authentication and Authorization
*Libraries for implementing user authentication and authorization.*

*  <b><code>&nbsp;&nbsp;&nbsp;124⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;26🍴</code></b> [Aura.Auth](https://github.com/auraphp/Aura.Auth) - Provides authentication functionality and session tracking using various adapters.
*  <b><code>&nbsp;&nbsp;&nbsp;501⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;94🍴</code></b> [SocialConnect Auth](https://github.com/socialConnect/auth) - An open source social sign (OAuth1\OAuth2\OpenID\OpenIDConnect).
*  <b><code>&nbsp;&nbsp;6694⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;553🍴</code></b> [Json Web Token](https://github.com/lcobucci/jwt) - Json Tokens to authenticate and transmit information.
*  <b><code>&nbsp;&nbsp;&nbsp;894⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;65🍴</code></b> [OAuth 1.0 Client](https://github.com/thephpleague/oauth1-client) - An OAuth 1.0 client library.
*  <b><code>&nbsp;&nbsp;3287⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;705🍴</code></b> [OAuth 2.0 Client](https://github.com/thephpleague/oauth2-client) - An OAuth 2.0 client library.
* 🌎 [OAuth2 Server](bshaffer.github.io/oauth2-server-php-docs/) - Another OAuth2 server implementation.
* 🌎 [OAuth2 Server](oauth2.thephpleague.com/) - An OAuth2 authentication server, resource server and client library.
*  <b><code>&nbsp;&nbsp;1658⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;257🍴</code></b> [Opauth](https://github.com/opauth/opauth) - A multi-provider authentication framework.
*  <b><code>&nbsp;&nbsp;3020⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;109🍴</code></b> [Paseto](https://github.com/paragonie/paseto) - Platform-Agnostic Security Tokens.
*  <b><code>&nbsp;&nbsp;1084⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;450🍴</code></b> [PHP oAuthLib](https://github.com/Lusitanian/PHPoAuthLib) - Another OAuth library.
* 🌎 [Sentinel Social](cartalyst.com/manual/sentinel-social/2.0) - A library for social network authentication.
* 🌎 [Sentinel](cartalyst.com/manual/sentinel/2.0) - A framework agnostic authentication & authorisation library.
*  <b><code>&nbsp;&nbsp;4182⭐</code></b> <b><code>&nbsp;&nbsp;1665🍴</code></b> [TwitterOAuth](https://github.com/abraham/twitteroauth) - A Twitter OAuth library.

### Markup and CSS
*Libraries for working with markup and CSS formats.

*  <b><code>&nbsp;&nbsp;&nbsp;976⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;135🍴</code></b> [Cebe Markdown](https://github.com/cebe/markdown) - An fast and extensible Markdown parser.
*  <b><code>&nbsp;&nbsp;2289⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;179🍴</code></b> [CommonMark PHP](https://github.com/thephpleague/commonmark) - Highly-extensible Markdown parser which fully supports the 🌎 [CommonMark spec](spec.commonmark.org/).
*  <b><code>&nbsp;&nbsp;&nbsp;195⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;53🍴</code></b> [Decoda](https://github.com/milesj/decoda) - A lightweight markup parser library.
*  <b><code>&nbsp;&nbsp;&nbsp;759⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;82🍴</code></b> [Essence](https://github.com/essence/essence) - A library for extracting web media.
*  <b><code>&nbsp;&nbsp;&nbsp;302⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;56🍴</code></b> [Embera](https://github.com/mpratt/Embera) - An Oembed consumer library.
*  <b><code>&nbsp;&nbsp;1489⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;194🍴</code></b> [HTML to Markdown](https://github.com/thephpleague/html-to-markdown) - Converts HTML into Markdown.
*  <b><code>&nbsp;&nbsp;1042⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;97🍴</code></b> [HTML5 PHP](https://github.com/Masterminds/html5-php) - An HTML5 parser and serializer library.
*  <b><code>&nbsp;14192⭐</code></b> <b><code>&nbsp;&nbsp;1084🍴</code></b> [Parsedown](https://github.com/erusev/parsedown) - Another Markdown parser.
*  <b><code>&nbsp;&nbsp;1555⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;128🍴</code></b> [PHP CSS Parser](https://github.com/sabberworm/PHP-CSS-Parser) - A Parser for CSS Files written in PHP.
*  <b><code>&nbsp;&nbsp;3297⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;539🍴</code></b> [PHP Markdown](https://github.com/michelf/php-markdown) - A Markdown parser.
*  <b><code>&nbsp;&nbsp;&nbsp;215⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;16🍴</code></b> [Shiki PHP](https://github.com/spatie/shiki-php) - A  <b><code>&nbsp;&nbsp;3527⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;144🍴</code></b> [Shiki](https://github.com/shikijs/shiki) code highlighting package in PHP.
*  <b><code>&nbsp;&nbsp;&nbsp;519⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;118🍴</code></b> [VObject](https://github.com/sabre-io/vobject) - A library for parsing VCard and iCalendar objects.

### JSON
*Libraries for working with JSON.*

*  <b><code>&nbsp;&nbsp;1259⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;56🍴</code></b> [JSON Lint](https://github.com/Seldaek/jsonlint) - A JSON lint utility.
*  <b><code>&nbsp;&nbsp;&nbsp;136⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;19🍴</code></b> [JSONMapper](https://github.com/JsonMapper/JsonMapper) - A library for mapping JSON to PHP objects.

### Strings
*Libraries for parsing and manipulating strings.*

*  <b><code>&nbsp;&nbsp;4050⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;398🍴</code></b> [Agent](https://github.com/jenssegers/agent) - A PHP desktop/mobile user agent parser, based on Mobiledetect.
*  <b><code>&nbsp;&nbsp;&nbsp;208⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;29🍴</code></b> [ANSI to HTML5](https://github.com/sensiolabs/ansi-to-html) - An ANSI to HTML5 converter library.
*  <b><code>&nbsp;&nbsp;&nbsp;281⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;28🍴</code></b> [Color Jizz](https://github.com/mikeemoo/ColorJizz-PHP) - A library for manipulating and converting colours.
*  <b><code>&nbsp;&nbsp;2258⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;411🍴</code></b> [Device Detector](https://github.com/matomo-org/device-detector) - Another library for parsing user agent strings.
*  <b><code>&nbsp;&nbsp;1184⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;247🍴</code></b> [Jieba-PHP](https://github.com/fukuball/jieba-php) - A PHP port of Python's jieba. Chinese text segmentation for natural language processing.
*  <b><code>&nbsp;10037⭐</code></b> <b><code>&nbsp;&nbsp;2677🍴</code></b> [Mobile-Detect](https://github.com/serbanghita/Mobile-Detect) - A lightweight PHP class for detecting mobile devices (including tablets).
*  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;78⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;12🍴</code></b> [Patchwork UTF-8](https://github.com/nicolas-grekas/Patchwork-UTF8) - A portable library for working with UTF-8 strings.
*  <b><code>&nbsp;&nbsp;&nbsp;332⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;22🍴</code></b> [Portable ASCII](https://github.com/voku/portable-ascii) - A library to convert strings to ascii.
*  <b><code>&nbsp;&nbsp;&nbsp;461⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;61🍴</code></b> [Portable UTF-8](https://github.com/voku/portable-utf8) - A string manipulation library with UTF-8 safe replacement methods.
*  <b><code>&nbsp;&nbsp;2757⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;239🍴</code></b> [Slugify](https://github.com/cocur/slugify) - A library to convert strings to slugs.
*  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [SQL Formatter](https://github.com/jdorn/sql-formatter/) - A library for formatting SQL statements.
*  <b><code>&nbsp;&nbsp;&nbsp;138⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;15🍴</code></b> [Stringy](https://github.com/voku/Stringy) - A string manipulation library with multibyte support.
*  <b><code>&nbsp;&nbsp;1984⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;515🍴</code></b> [UA Parser](https://github.com/tobie/ua-parser/tree/master/php) - A library for parsing user agent strings.
*  <b><code>&nbsp;&nbsp;&nbsp;651⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;80🍴</code></b> [URLify](https://github.com/jbroadway/urlify) - A PHP port of Django's URLify.js.
*  <b><code>&nbsp;11706⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;468🍴</code></b> [UUID](https://github.com/ramsey/uuid) - A library for generating UUIDs.

### Numbers
*Libraries for working with numbers.*

*  <b><code>&nbsp;&nbsp;1302⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;59🍴</code></b> [Brick\Math](https://github.com/brick/math) - A library providing large number support: `BigInteger`, `BigDecimal` and `BigRational`.
*  <b><code>&nbsp;&nbsp;&nbsp;155⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;16🍴</code></b> [ByteUnits](https://github.com/gabrielelana/byte-units) - A library to parse, format and convert byte units in binary and metric systems.
*  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;13⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7🍴</code></b> [DecimalObject](https://github.com/spryker/decimal-object) - A value object to handle decimals/floats easily and more precisely.
*  <b><code>&nbsp;&nbsp;&nbsp;214⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;15🍴</code></b> [IP](https://github.com/darsyn/ip) - An immutable value object for working with IPv4 and IPv6 addresses.
*  <b><code>&nbsp;&nbsp;4109⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;425🍴</code></b> [LibPhoneNumber for PHP](https://github.com/giggsey/libphonenumber-for-php) - A PHP implementation of Google's phone number handling library.
*  <b><code>&nbsp;&nbsp;&nbsp;127⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;17🍴</code></b> [PHP Conversion](https://github.com/Crisu83/php-conversion) - Another library for converting between units of measure.
*  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;20⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4🍴</code></b> [PHP Units of Measure](https://github.com/triplepoint/php-units-of-measure) - A library for converting between units of measure.
*  <b><code>&nbsp;&nbsp;2102⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;217🍴</code></b> [MathPHP](https://github.com/markrogoyski/math-php) - A math library for PHP. 

### Filtering and Validation
*Libraries for filtering and validating data.*

*  <b><code>&nbsp;&nbsp;2267⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;187🍴</code></b> [Assert](https://github.com/beberlei/assert) - A validation library with a rich set of assertions. Supports assertion chaining and lazy assertions.
*  <b><code>&nbsp;&nbsp;&nbsp;147⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;33🍴</code></b> [Aura.Filter](https://github.com/auraphp/Aura.Filter) - Provides tools to validate and sanitize objects and arrays.
*  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;37⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;11🍴</code></b> [CakePHP Validation](https://github.com/cakephp/validation) - Another validation library.
*  <b><code>&nbsp;&nbsp;&nbsp;452⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;56🍴</code></b> [Filterus](https://github.com/ircmaxell/filterus) - A simple PHP filtering library.
*  <b><code>&nbsp;&nbsp;&nbsp;759⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;74🍴</code></b> [ISO-codes](https://github.com/ronanguilloux/IsoCodes) - A library for validating inputs according standards from ISO, International Finance, Public Administrations, GS1, Book Industry, Phone numbers & Zipcodes for many countries.
*  <b><code>&nbsp;&nbsp;3302⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;340🍴</code></b> [JSON Schema](https://github.com/justinrainbow/json-schema) - A 🌎 [JSON Schema](json-schema.org/) validation library.
*  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;97⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;20🍴</code></b> [MetaYaml](https://github.com/romaricdrigon/MetaYaml) - A schema validation library that supports YAML, JSON and XML.
*  <b><code>&nbsp;&nbsp;5542⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;767🍴</code></b> [Respect Validation](https://github.com/Respect/Validation) - A simple validation library.
*  <b><code>&nbsp;&nbsp;1660⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;328🍴</code></b> [Upload](https://github.com/brandonsavage/Upload) - A library for handling file uploads and validation.
*  <b><code>&nbsp;&nbsp;1470⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;249🍴</code></b> [Valitron](https://github.com/vlucas/valitron) - Another validation library.
*  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;42⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9🍴</code></b> [Volan](https://github.com/serkin/Volan) - Another simplified validation library.

### API
*Libraries and web tools for developing APIs.*

* 🌎 [API Platform](api-platform.com ) - Expose in minutes an hypermedia REST API that embraces JSON-LD, Hydra format.
*  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;39⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;35🍴</code></b> [Laminas API Tool Skeleton](https://github.com/laminas-api-tools/api-tools-skeleton) - An API builder built with the Laminas Framework.
*  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;85⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;12🍴</code></b> [Drest](https://github.com/leedavis81/drest) - A library for exposing Doctrine entities as REST resource endpoints.
*  <b><code>&nbsp;&nbsp;&nbsp;203⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;38🍴</code></b> [HAL](https://github.com/blongden/hal) - A Hypertext Application Language (HAL) builder library.
*  <b><code>&nbsp;&nbsp;&nbsp;992⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;118🍴</code></b> [Hateoas](https://github.com/willdurand/Hateoas) - A HATEOAS REST web service library.
*  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Jane](https://github.com/janephp/janephp/) - An OpenApi client generator with validation support.
*  <b><code>&nbsp;&nbsp;1284⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;60🍴</code></b> [Negotiation](https://github.com/willdurand/Negotiation) - A content negotiation library.
*  <b><code>&nbsp;&nbsp;1346⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;318🍴</code></b> [Restler](https://github.com/Luracast/Restler) - A lightweight framework to expose PHP methods as RESTful web API.
*  <b><code>&nbsp;&nbsp;&nbsp;797⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;310🍴</code></b> [wsdl2phpgenerator](https://github.com/wsdl2phpgenerator/wsdl2phpgenerator) - A tool to generate PHP classes from SOAP WSDL files.

### Caching and Locking
*Libraries for caching data and acquiring locks.*

*  <b><code>&nbsp;&nbsp;&nbsp;109⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;26🍴</code></b> [APIx Cache](https://github.com/apix/cache) - A thin PSR-6 cache wrapper to various caching backends emphasising cache tagging and indexing.
*  <b><code>&nbsp;&nbsp;1353⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;134🍴</code></b> [CacheTool](https://github.com/gordalina/cachetool) - A tool to clear APC/opcode caches from the command line.
*  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;48⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;10🍴</code></b> [CakePHP Cache](https://github.com/cakephp/cache) - A caching library.
*  <b><code>&nbsp;&nbsp;7468⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;214🍴</code></b> [Doctrine Cache](https://github.com/doctrine/cache) - A caching library.
*  <b><code>&nbsp;&nbsp;&nbsp;101⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9🍴</code></b> [Metaphore](https://github.com/sobstel/metaphore) - Cache slam defense using a semaphore to prevent dogpile effect.
*  <b><code>&nbsp;&nbsp;&nbsp;939⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;134🍴</code></b> [Stash](https://github.com/tedious/Stash) - Another library for caching.
*  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;55⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;38🍴</code></b> [Laminas Cache](https://github.com/laminas/laminas-cache) - Another caching library.
*  <b><code>&nbsp;&nbsp;&nbsp;857⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;90🍴</code></b> [Lock](https://github.com/php-lock/lock) - A lock library to provide exclusive execution.

### Data Structure and Storage
*Libraries that implement data structure or storage techniques.*

*  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;82⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5🍴</code></b> [CakePHP Collection](https://github.com/cakephp/collection) - A simple collections library.
*  <b><code>&nbsp;&nbsp;3447⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;350🍴</code></b> [Fractal](https://github.com/thephpleague/fractal) - A library for converting complex data structures to JSON output.
*  <b><code>&nbsp;&nbsp;&nbsp;190⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;18🍴</code></b> [Ginq](https://github.com/akanehara/ginq) - Another PHP library based on .NET's LINQ.
*  <b><code>&nbsp;&nbsp;1421⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;173🍴</code></b> [JsonMapper](https://github.com/cweiske/jsonmapper) - A library that maps nested JSON structures onto PHP classes.
*  <b><code>&nbsp;&nbsp;&nbsp;733⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;45🍴</code></b> [JSON Machine](https://github.com/halaxa/json-machine) - Provides iteration over huge JSONs using simple `foreach`
*  <b><code>&nbsp;&nbsp;&nbsp;536⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;52🍴</code></b> [Knapsack](https://github.com/DusanKasan/Knapsack) - Collection library inspired by Clojure's sequences.
*  <b><code>&nbsp;&nbsp;&nbsp;359⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;17🍴</code></b> [msgpack.php](https://github.com/rybakit/msgpack.php) - A pure PHP implementation of the 🌎 [MessagePack](msgpack.org/) serialization format.
*  <b><code>&nbsp;&nbsp;&nbsp;465⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;18🍴</code></b> [PINQ](https://github.com/TimeToogo/Pinq) - A PHP library based on .NET's LINQ (Language Integrated Query).
*  <b><code>&nbsp;&nbsp;2202⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;584🍴</code></b> [Serializer](https://github.com/schmittjoh/serializer) - A library for serialising and de-serialising data.
*  <b><code>&nbsp;&nbsp;&nbsp;428⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;31🍴</code></b> [YaLinqo](https://github.com/Athari/YaLinqo) - Yet Another LINQ to Objects for PHP.
*  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;25⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;10🍴</code></b> [Laminas Serializer](https://github.com/laminas/laminas-serializer) - Another library for serialising and de-serialising data.

### Notifications
*Libraries for working with notification software.*

*  <b><code>&nbsp;&nbsp;1221⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;82🍴</code></b> [JoliNotif](https://github.com/jolicode/JoliNotif) - A cross-platform library for desktop notification (support for Growl, notify-send, toaster, etc)
*  <b><code>&nbsp;&nbsp;1165⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;275🍴</code></b> [Notification Pusher](https://github.com/Ph3nol/NotificationPusher) - A standalone library for device push notifications.
*  <b><code>&nbsp;&nbsp;&nbsp;221⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;44🍴</code></b> [Notificato](https://github.com/mac-cain13/notificato) - A library for handling push notifications.
*  <b><code>&nbsp;&nbsp;&nbsp;187⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;24🍴</code></b> [Notificator](https://github.com/namshi/notificator) - A lightweight notification library.
*  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;62⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;36🍴</code></b> [Php-pushwoosh](https://github.com/gomoob/php-pushwoosh) - A PHP Library to easily send push notifications with the Pushwoosh REST Web Services.

### Deployment
*Libraries for project deployment.*

*  <b><code>&nbsp;&nbsp;9323⭐</code></b> <b><code>&nbsp;&nbsp;1395🍴</code></b> [Deployer](https://github.com/deployphp/deployer) - A deployment tool.
*  <b><code>&nbsp;&nbsp;1473⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;174🍴</code></b> [Envoy](https://github.com/laravel/envoy) - A tool to run SSH tasks with PHP.
*  <b><code>&nbsp;&nbsp;2700⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;222🍴</code></b> [Rocketeer](https://github.com/rocketeers/rocketeer) - A fast and easy deployer for the PHP world.

### Internationalisation and Localisation
*Libraries for Internationalization (I18n) and Localization (L10n).*

*  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;84⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;22🍴</code></b> [Aura.Intl](https://github.com/auraphp/Aura.Intl) - Provides internationalization (I18N) tools, specifically package-oriented per-locale message translation.
*  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;26⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7🍴</code></b> [CakePHP I18n](https://github.com/cakephp/i18n) - Message translation and localization for dates and numbers.

### Serverless
*Libraries and tools to help build serverless web applications.*

* 🌎 [Bref](bref.sh/) - Serverless PHP on AWS Lambda.
* 🌎 [OpenWhisk](openwhisk.apache.org/) - An open-source serverless cloud platform.
* 🌎 [Serverless Framework](www.serverless.com/framework) - An open-source framework for building serverless applications.
* 🌎 [Laravel Vapor](vapor.laravel.com/) - A serverless deployment platform for Laravel, powered by AWS.

## Configuration
*Libraries and tools for configuration.*

*  <b><code>&nbsp;12037⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;586🍴</code></b> [PHP Dotenv](https://github.com/vlucas/phpdotenv) - Parse and load environment variables from `.env` files.
*  <b><code>&nbsp;&nbsp;3406⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;26🍴</code></b> [Symfony Dotenv](https://github.com/symfony/dotenv)- Parse and load environment variables from `.env` files.
*  <b><code>&nbsp;&nbsp;&nbsp;169⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;21🍴</code></b> [Yo! Symfony TOML](https://github.com/yosymfony/toml) - A PHP parser for  <b><code>&nbsp;17237⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;834🍴</code></b> [TOML](https://github.com/toml-lang/toml). 

### Third Party APIs
*Libraries for accessing third party APIs.*

*  <b><code>&nbsp;&nbsp;5584⭐</code></b> <b><code>&nbsp;&nbsp;1107🍴</code></b> [Amazon Web Service SDK](https://github.com/aws/aws-sdk-php) - The official PHP AWS SDK library.
* 🌎 [AsyncAWS](async-aws.com/) - An unofficial asynchronous PHP AWS SDK.
* 🌎 [Campaign Monitor](campaignmonitor.github.io/createsend-php/) - The official Campaign Monitor PHP library.
*  <b><code>&nbsp;&nbsp;1991⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;598🍴</code></b> [Github](https://github.com/KnpLabs/php-github-api) - A library to interface with the Github API.
*  <b><code>&nbsp;&nbsp;1029⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;314🍴</code></b> [Mailgun](https://github.com/mailgun/mailgun-php) The official Mailgun PHP API.
*  <b><code>&nbsp;&nbsp;&nbsp;114⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;54🍴</code></b> [Square](https://github.com/square/connect-php-sdk) - The official Square PHP SDK for payments and other Square APIs.
*  <b><code>&nbsp;&nbsp;3168⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;779🍴</code></b> [Stripe](https://github.com/stripe/stripe-php) - The official Stripe PHP library.
*  <b><code>&nbsp;&nbsp;1358⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;531🍴</code></b> [Twilio](https://github.com/twilio/twilio-php) - The official Twilio PHP REST API.

### Extensions
*Libraries to help build PHP extensions.*

* 🌎 [PHP CPP](www.php-cpp.com/) - A C++ library for developing PHP extensions.
*  <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Zephir](https://github.com/zephir-lang/zephir ) - A compiled language between PHP and C++ for developing PHP extensions.

### Miscellaneous
*Useful libraries or utilities that don't fit into the categories above.*

*  <b><code>&nbsp;&nbsp;6479⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;227🍴</code></b> [Annotations](https://github.com/doctrine/annotations) - An annotation library (part of Doctrine).
*  <b><code>&nbsp;&nbsp;5657⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;793🍴</code></b> [BotMan](https://github.com/botman/botman) - A framework agnostic PHP library to build cross-platform chat bots.
*  <b><code>&nbsp;&nbsp;&nbsp;352⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;32🍴</code></b> [ClassPreloader](https://github.com/ClassPreloader/ClassPreloader) - A library for optimising autoloading.
*  <b><code>&nbsp;&nbsp;1965⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;400🍴</code></b> [Hprose-PHP](https://github.com/hprose/hprose-php) - A cross-language RPC.
*  <b><code>&nbsp;&nbsp;&nbsp;332⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;36🍴</code></b> [noCAPTCHA](https://github.com/ARCANEDEV/noCAPTCHA) - Helper for Google's noCAPTCHA (reCAPTCHA).
*  <b><code>&nbsp;&nbsp;1611⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [Pagerfanta](https://github.com/whiteoctober/Pagerfanta) - A pagination library.
*  <b><code>&nbsp;&nbsp;2023⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;102🍴</code></b> [Safe](https://github.com/thecodingmachine/safe) - All PHP functions, rewritten to throw exceptions instead of returning false.
*  <b><code>&nbsp;&nbsp;1721⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;83🍴</code></b> [SuperClosure](https://github.com/jeremeamia/super_closure) - A library that allows Closures to be serialized.

# Software
*Software for creating a development environment.*

### PHP Installation
*Tools to help install and manage PHP on your computer.*

*  <b><code>&nbsp;&nbsp;&nbsp;835⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;85🍴</code></b> [Brew PHP Switcher](https://github.com/philcook/brew-php-switcher) - Brew PHP switcher.
* 🌎 [HomeBrew](brew.sh/) - A package manager for OSX.
* 🌎 [Laravel Valet](laravel.com/docs/master/valet) - A development environment for macOS.
*  <b><code>&nbsp;&nbsp;4919⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;367🍴</code></b> [PHP Brew](https://github.com/phpbrew/phpbrew) - A PHP version manager and installer.
*  <b><code>&nbsp;&nbsp;&nbsp;940⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;148🍴</code></b> [PHP Build](https://github.com/php-build/php-build) - Another PHP version installer.
* 🌎 [PHP OSX](php-osx.liip.ch/) - A PHP installer for OSX.

### Development Environment
*Software and tools for creating and sharing a development environment.*

* 🌎 [Ansible](www.ansible.com/) - A radically simple orchestration framework.
* 🌎 [Docker](www.docker.com/) - A containerization platform.
*  <b><code>&nbsp;&nbsp;2384⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;244🍴</code></b> [Docker PHP Extension Installer](https://github.com/mlocati/docker-php-extension-installer) - Easily install PHP extensions in Docker containers.
*  <b><code>&nbsp;&nbsp;3801⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;216🍴</code></b> [Expose](https://github.com/beyondcode/expose) - An open source PHP tunneling service.
* 🌎 [Lando](lando.dev/) - Push-button development environments.
* 🌎 [Laravel Homestead](laravel.com/docs/master/homestead) - A local development environment for Laravel. 
* [Laradock](http://laradock.io/) - A full PHP development environment based on Docker.
* 🌎 [Puppet](puppet.com/) - A server automation framework and application.
*  <b><code>&nbsp;&nbsp;1384⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;78🍴</code></b> [Takeout](https://github.com/tighten/takeout) - A Docker-based development-only dependency manager.
* 🌎 [Vagrant](www.vagrantup.com/) - A portable development environment utility.

### Virtual Machines
*Alternative PHP virtual machines.*

* 🌎 [Hack](hacklang.org/) - A programming language for HHVM.
*  <b><code>&nbsp;17318⭐</code></b> <b><code>&nbsp;&nbsp;2999🍴</code></b> [HHVM](https://github.com/facebook/hhvm) - A Virtual Machine, Runtime and JIT for PHP by Facebook.
*  <b><code>&nbsp;&nbsp;2035⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;198🍴</code></b> [PeachPie](https://github.com/peachpiecompiler/peachpie) - PHP compiler and runtime for .NET and .NET Core.

### Text Editors and IDEs
*Text Editors and Integrated Development Environments (IDE) with support for PHP.*

* 🌎 [Eclipse for PHP Developers](www.eclipse.org/downloads/) - A PHP IDE based on the Eclipse platform.
* 🌎 [Apache NetBeans](netbeans.apache.org/) - An IDE with support for PHP and HTML5.
* 🌎 [PhpStorm](www.jetbrains.com/phpstorm/) - A commercial PHP IDE.
* 🌎 [VS Code](code.visualstudio.com/) - An open source code editor.

### Web Applications
*Web-based applications and tools.*

* 🌎 [3V4L](3v4l.org/) - An online PHP & HHVM shell.
* 🌎 [Adminer](www.adminer.org/) - Database management in a single PHP file.
*  <b><code>&nbsp;12807⭐</code></b> <b><code>&nbsp;&nbsp;1542🍴</code></b> [Cachet](https://github.com/cachethq/cachet) - The open source status page system.
*  <b><code>&nbsp;&nbsp;1666⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;257🍴</code></b> [DBV](https://github.com/victorstanciu/dbv) - A database version control application.
*  <b><code>&nbsp;&nbsp;6064⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;705🍴</code></b> [Lychee](https://github.com/electerious/Lychee) - An easy to use and great looking photo-management-system.
*  <b><code>&nbsp;&nbsp;5689⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;534🍴</code></b> [MailCatcher](https://github.com/sj26/mailcatcher) - A web tool for capturing and viewing emails.
*  <b><code>&nbsp;&nbsp;6099⭐</code></b> <b><code>&nbsp;&nbsp;3172🍴</code></b> [phpMyAdmin](https://github.com/phpmyadmin/phpmyadmin) - A web interface for MySQL/MariaDB.
*  <b><code>&nbsp;&nbsp;&nbsp;643⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;66🍴</code></b> [PHP Queue](https://github.com/CoderKungfu/php-queue) - An application for managing queueing backends.
*  <b><code>&nbsp;&nbsp;2909⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;656🍴</code></b> [phpRedisAdmin](https://github.com/ErikDubbelboer/phpRedisAdmin) - A simple web interface to manage 🌎 [Redis](redis.io/) databases.
* 🌎 [PHPSandbox](phpsandbox.io) - An online IDE for PHP in the browser.

### Infrastructure
*Infrastructure for providing PHP applications and services.*

*  <b><code>&nbsp;&nbsp;&nbsp;944⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;106🍴</code></b> [appserver.io](https://github.com/appserver-io/appserver) - A multithreaded application server for PHP, written in PHP.
*  <b><code>&nbsp;&nbsp;6413⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;374🍴</code></b> [php-pm](https://github.com/php-pm/php-pm) - A process manager, supercharger and load balancer for PHP applications.
*  <b><code>&nbsp;&nbsp;6632⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;365🍴</code></b> [RoadRunner](https://github.com/roadrunner-server/roadrunner) - High-performance PHP application server, load-balancer and process manager.

# Resources
Various resources, such as books, websites and articles, for improving your PHP development skills and knowledge.

### PHP Websites
*Useful PHP-related websites.*

* 🌎 [libs.garden: PHP](libs.garden/php) - An overview of fastest growing PHP libraries.
* 🌎 [Nomad PHP](nomadphp.com/) - A online PHP learning resource.
* 🌎 [Laravel News](laravel-news.com/) - The official Laravel blog.
* 🌎 [PHP Annotated Monthly](blog.jetbrains.com/phpstorm/tag/php-annotated-monthly/) - A monthly digest of PHP news.
* 🌎 [PHP Best Practices](phpbestpractices.org/) - A PHP best practice guide.
* 🌎 [PHP FIG](www.php-fig.org/) - The PHP Framework Interoperability Group.
* [PHP Package Development Standards](http://php-pds.com) - Package development standards for PHP.
* 🌎 [PHP School](www.phpschool.io/) - Open Source Learning for PHP.
* 🌎 [PHP Security](phpsecurity.readthedocs.io/en/latest/index.html) - A guide to PHP security.
* 🌎 [PHP The Right Way](phptherightway.com/) - A PHP best practice quick reference guide.
* 🌎 [PHP UG](php.ug) - A website to help people locate their nearest PHP user group (UG).
* [PHP Versions](http://phpversions.info/) - Lists which versions of PHP are available on several popular web hosts.
* 🌎 [PHP Watch](php.watch/) - PHP articles, news, upcoming changes, RFCs and more.
* 🌎 [PHP Weekly](www.phpweekly.com/archive.html) - A weekly PHP newsletter.
* 🌎 [Seven PHP](7php.com/) - A website that interviews members of the PHP community.

### PHP Books
*Fantastic PHP-related books.*

* 🌎 [Domain-Driven Design in PHP](leanpub.com/ddd-in-php) - Real examples written in PHP showcasing DDD Architectural Styles.
* 🌎 [Functional Programming in PHP](www.functionalphp.com/) - This book will show you how to leverage these new PHP5.3+ features by understanding functional programming principles
* 🌎 [Grumpy PHPUnit](leanpub.com/grumpy-phpunit) - A book about unit testing with PHPUnit by Chris Hartjes.
* 🌎 [Mastering Object-Orientated PHP](www.brandonsavage.net/) - A book about object-orientated PHP by Brandon Savage.
* 🌎 [Modern PHP New Features and Good Practices](www.oreilly.com/library/view/~/9781491905173/) - A book about new PHP features and best practices by Josh Lockhart.
* 🌎 [Modernizing Legacy Applications in PHP](leanpub.com/mlaphp) - A book about modernizing legacy PHP applications by Paul M. Jones.
* 🌎 [PHP 7 Upgrade Guide](leanpub.com/php7) - An ebook covering all of the features and changes in PHP 7 by Colin O'Dell.
* 🌎 [PHP Pandas](daylerees.com/php-pandas/) - A book about learning to write PHP by Dayle Rees.
* 🌎 [Scaling PHP Applications](www.scalingphpbook.com) - An ebook about scaling PHP applications by Steve Corona.
* 🌎 [Securing PHP: Core Concepts](leanpub.com/securingphp-coreconcepts) - A book about common security terms and practices for PHP by Chris Cornutt.
* 🌎 [Signaling PHP](leanpub.com/signalingphp) - A book about catching PCNTL signals in CLI scripts by Cal Evans.
* 🌎 [The Grumpy Programmer's Guide to Building Testable PHP Applications](leanpub.com/grumpy-testing) - A book about building testing PHP applications by Chris Hartjes.
* 🌎 [XML Parsing with PHP](www.phparch.com/books/xml-parsing-with-php/) - This book covers parsing and validating XML documents, leveraging XPath expressions, and working with namespaces as well as how to create and modify XML files programmatically.

### PHP Videos
*Fantastic PHP-related videos.*

* 🌎 [Nomad PHP Lightning Talks](www.youtube.com/c/nomadphp) - 10 to 15 minute Lightning Talks by PHP community members.
* 🌎 [PHP UK Conference](www.youtube.com/user/phpukconference/videos) - A collection of videos from the PHP UK Conference.
* 🌎 [Programming with Anthony](www.youtube.com/playlist?list=PLM-218uGSX3DQ3KsB5NJnuOqPqc5CW2kW) - A video series by Anthony Ferrara.
* 🌎 [Taking PHP Seriously](www.infoq.com/presentations/php-history/) - A talk outlining PHP's strengths by Keith Adams of Facebook.
* 🌎 [Laracasts](laracasts.com) - Screencasts about Laravel, Vue JS and more.
* 🌎 [Laravel YouTube Channel](www.youtube.com/channel/UCfO2GiQwb-cwJTb1CuRSkwg) - The official Laravel YouTube channel.
* 🌎 [SymfonyCasts](symfonycasts.com/) - Screencasts and tutorials about PHP and Symfony.

### PHP Podcasts
*Podcasts with a focus on PHP topics.*

* 🌎 [Laravel Podcast](laravelpodcast.com/) - Laravel and PHP development news and discussion.
* 🌎 [PHP Internals News](phpinternals.news) - A podcast about PHP internals.
* 🌎 [PHP Roundtable](phproundtable.com/) - The PHP Roundtable is a casual gathering of developers discussing topics that PHP nerds care about.
* 🌎 [PHP Town Hall](phptownhall.com/) - A casual PHP podcast by Ben Edmunds and Phil Sturgeon.
* 🌎 [Voices of the ElePHPant](voicesoftheelephpant.com/) Interviews with the people that make the PHP community special.

### PHP Newsletters
*PHP-related news directly to your inbox.*

* 🌎 [PHP Weekly](www.phpweekly.com/) - A weekly newsletter about PHP.

### PHP Reading
*PHP-related reading materials.*

* [php[architect]](https://www.phparch.com/magazine/) - A monthly magazine dedicated to PHP.

### PHP Internals Reading
*Reading materials related to the PHP internals or performance.*

* 🌎 [PHP RFCs](wiki.php.net/rfc) - The home of PHP RFCs (Request for Comments).
* 🌎 [Externals](externals.io/) - PHP internal discussions. 
* 🌎 [PHP RFC Watch](php-rfc-watch.beberlei.de/) - Watch the latest PHP 🌎 [RFCs](wiki.php.net/rfc).
* 🌎 [PHP Internals Book](www.phpinternalsbook.com/) - An online book about PHP internals, written by three core developers.
