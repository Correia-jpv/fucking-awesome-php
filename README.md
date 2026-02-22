# Awesome PHP [![Awesome](https://cdn.jsdelivr.net/gh/sindresorhus/awesome@d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of awesome PHP libraries, resources, and useful tools.

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
  - [Error Tracking and Monitoring Services](#error-tracking-and-monitoring-services)
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
  - [Filtering, Sanitizing and Validation](#filtering-sanitizing-and-validation)
  - [API](#api)
  - [Caching and Locking](#caching-and-locking)
  - [Data Structure and Storage](#data-structure-and-storage)
  - [Notifications](#notifications)
  - [Deployment](#deployment)
  - [Internationalisation and Localisation](#internationalisation-and-localisation)
  - [Serverless](#serverless)
  - [Configuration](#configuration)
  - [LLMs](#llms)
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
  - [PHP Conferences](#php-conferences)
  - [PHP Podcasts](#php-podcasts)
  - [PHP Newsletters](#php-newsletters)
  - [PHP Reading](#php-reading)
  - [PHP Internals Reading](#php-internals-reading)

### Composer Repositories
*Composer Repositories.*

* 🌎 [Firegento](packages.firegento.com/) - Magento Module Composer Repository.
* 🌎 [Packagist](packagist.org/) - The PHP Package Repository.
* 🌎 [Packalyst](packalyst.com/) - The Laravel package repository.
* 🌎 [Private Packagist](packagist.com/) - Composer package archive as a service for PHP.
* 🌎 [WordPress Packagist](wpackagist.org/) - Manage your plugins with Composer.

### Dependency Management
*Libraries for dependency and package management.*

* <b><code>&nbsp;&nbsp;1438⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;403🍴</code></b> [Composer Installers](https://github.com/composer/installers)) - A  multi-framework Composer library installer.
* 🌎 [Composer](getcomposer.org/) - A package and dependency manager.
* <b><code>&nbsp;&nbsp;1735⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;54🍴</code></b> [Pie](https://github.com/php/pie)) - The official PHP installer for extensions.
* 🌎 [Phive](phar.io/) - A PHAR manager.
* <b><code>&nbsp;&nbsp;1653⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;88🍴</code></b> [Pickle](https://github.com/FriendsOfPHP/pickle)) - A PHP extension installer.

### Dependency Management Extras
*Extras related to dependency management.*

* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;53⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4🍴</code></b> [Composed](https://github.com/joshdifabio/composed)) - A library to parse your project's Composer environment at runtime.
* <b><code>&nbsp;&nbsp;&nbsp;993⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;170🍴</code></b> [Composer Merge Plugin](https://github.com/wikimedia/composer-merge-plugin)) - A composer plugin to merge several `composer.json` files.
* <b><code>&nbsp;&nbsp;1104⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;37🍴</code></b> [Composer Normalize](https://github.com/ergebnis/composer-normalize)) - A plugin for normalizing `composer.json` files.
* <b><code>&nbsp;&nbsp;1678⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;262🍴</code></b> [Composer Patches](https://github.com/cweagans/composer-patches)) - A plugin for Composer to apply patches.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;22⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2🍴</code></b> [Composer Prefer Lowest Validator](https://github.com/dereuromark/composer-prefer-lowest)) - A plugin to check if minimum dependencies can be installed and tested.
* <b><code>&nbsp;&nbsp;&nbsp;985⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;76🍴</code></b> [Composer Require Checker](https://github.com/maglnet/ComposerRequireChecker)) - CLI tool to analyze composer dependencies and verify that no unknown symbols are used in the sources of a package.
* <b><code>&nbsp;&nbsp;1655⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;56🍴</code></b> [Composer Unused](https://github.com/composer-unused/composer-unused)) - A CLI Tool to scan for unused composer packages.
* 🌎 [Repman](repman.io) - A private PHP package repository manager and Packagist proxy.
* <b><code>&nbsp;&nbsp;3250⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;530🍴</code></b> [Satis](https://github.com/composer/satis)) - A static Composer repository generator.
* <b><code>&nbsp;&nbsp;&nbsp;103⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;14🍴</code></b> [Tooly](https://github.com/tommy-muehle/tooly-composer-script)) - A library to manage PHAR files in a project using Composer.
* 🌎 [Toran Proxy](toranproxy.com) - A Composer proxy for speed and reliability. (:warning: Toran Proxy is being phased out.)

### Frameworks
*Web development frameworks.*

* 🌎 [CakePHP](cakephp.org/) - A rapid application development framework.
* 🌎 [CodeIgniter](codeigniter.com/) - A powerful PHP framework with a very small footprint.
* 🌎 [Laminas](getlaminas.org/) - A framework comprised of individual components (previously Zend Framework).
* 🌎 [Laravel](laravel.com/) - A web application framework with expressive, elegant syntax.
* 🌎 [Nette](nette.org) - A web framework comprised of mature components.
* 🌎 [Phalcon](phalcon.io/en-us) - A framework implemented as a C extension.
* 🌎 [Spiral](spiral.dev/) - A high-performance PHP/Go framework.
* 🌎 [Symfony](symfony.com/) - A set of reusable components and a web framework.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Yii2](https://github.com/yiisoft/yii2/)) - A fast, secure, and efficient web framework.

### Framework Extras
*Extras related to web development frameworks.*

* <b><code>&nbsp;&nbsp;&nbsp;376⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;142🍴</code></b> [CakePHP CRUD](https://github.com/friendsofcake/crud)) - A Rapid Application Development (RAD) plugin for CakePHP.
* 🌎 [Filament PHP](filamentphp.com/) - A powerful open source UI framework for Laravel.
* <b><code>&nbsp;&nbsp;3886⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;474🍴</code></b> [LaravelS](https://github.com/hhxsv5/laravel-s)) - An out-of-the-box adapter between Laravel/Lumen and Swoole.
* 🌎 [Livewire](livewire.laravel.com/) - Powerful, dynamic, front-end UIs without leaving PHP.

### Content Management Systems (CMS)
*Tools for managing digital content.*

* 🌎 [Backdrop](backdropcms.org) - A CMS targeting small-to-medium-sized business and non-profits (a fork of Drupal).
* 🌎 [Concrete5](www.concretecms.com/) - A CMS targeting users with a minimum of technical skills.
* <b><code>&nbsp;&nbsp;3536⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;681🍴</code></b> [CraftCMS](https://github.com/craftcms/cms)) - A flexible, user-friendly CMS for creating custom digital experiences on the web and beyond.
* 🌎 [Drupal](new.drupal.org/home) - An enterprise level CMS.
* <b><code>&nbsp;15395⭐</code></b> <b><code>&nbsp;&nbsp;1420🍴</code></b> [Grav](https://github.com/getgrav/grav)) - A modern flat-file CMS.
* 🌎 [Joomla](www.joomla.org/) - Another leading CMS.
* 🌎 [Kirby](getkirby.com/) - A flat-file CMS that adapts to any project.
* <b><code>&nbsp;12043⭐</code></b> <b><code>&nbsp;&nbsp;9404🍴</code></b> [Magento](https://github.com/magento/magento2)) - The most popular e-commerce platform.
* 🌎 [Moodle](moodle.org/) - An open-source learning platform.
* <b><code>&nbsp;&nbsp;&nbsp;914⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;451🍴</code></b> [OpenMage](https://github.com/OpenMage/magento-lts)) - Fork of EoL Magento 1 e-commerce platform.
* 🌎 [Pico CMS](picocms.org/) - A stupidly simple, blazing fast, flat file CMS.
* 🌎 [Statamic](statamic.com/) - Build beautiful, easy-to-manage websites.
* 🌎 [Sulu](sulu.io/) - A user and developer friendly focused CMS and Platform based on the Symfony Framework.
* 🌎 [TYPO3](typo3.org) - An enterprise level CMS.
* <b><code>&nbsp;20903⭐</code></b> <b><code>&nbsp;12930🍴</code></b> [WordPress](https://github.com/WordPress/WordPress)) - A blogging platform and CMS.

### Components
*Standalone components from web development frameworks and development groups.*

* 🌎 [Aura](auraphp.com/) - Independent components, fully decoupled from each other and from any framework.
* 🌎 [CakePHP Plugins](plugins.cakephp.org/) - A directory of CakePHP plugins.
* [Laravel Components](https://github.com/illuminate) - The Laravel Framework components.
* 🌎 [League of Extraordinary Packages](thephpleague.com/) - A PHP package development group.
* 🌎 [Spatie Open Source](spatie.be/open-source) - A collection of open-source PHP and Laravel packages.
* 🌎 [Symfony Packages](symfony.com/packages) - Decoupled libraries for PHP applications.
* 🌎 [Laminas Components](docs.laminas.dev/components/) - The components that make the Laminas Framework.

### Micro Frameworks
*Micro frameworks and routers.*

* 🌎 [Laravel Zero](laravel-zero.com) - A micro-framework for console applications.
* 🌎 [Mezzio](getexpressive.org/) - A micro-framework by Laminas.
* <b><code>&nbsp;&nbsp;1073⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;57🍴</code></b> [Minicli](https://github.com/minicli/minicli)) - Minimalist, dependency-free framework for building CLI-centric PHP applications.
* <b><code>&nbsp;&nbsp;&nbsp;930⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;51🍴</code></b> [Silly](https://github.com/mnapoli/silly)) - A micro-framework for CLI applications.
* 🌎 [Slim](www.slimframework.com/) - Another simple micro framework.

### Micro Framework Extras
*Extras related to micro frameworks and routers.*

* <b><code>&nbsp;&nbsp;1622⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;479🍴</code></b> [Slim Skeleton](https://github.com/slimphp/Slim-Skeleton)) - A skeleton for Slim.
* <b><code>&nbsp;&nbsp;&nbsp;304⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;54🍴</code></b> [Slim Twig View](https://github.com/slimphp/Slim-Views)) - Integrate Twig into Slim.
* <b><code>&nbsp;&nbsp;&nbsp;273⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;61🍴</code></b> [Slim PHP View](https://github.com/slimphp/PHP-View)) - A simple PHP renderer for Slim.

### Routers
*Libraries for handling application routing.*

* <b><code>&nbsp;&nbsp;&nbsp;502⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;77🍴</code></b> [Aura.Router](https://github.com/auraphp/Aura.Router)) - A full-featured routing library.
* <b><code>&nbsp;&nbsp;5261⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;454🍴</code></b> [Fast Route](https://github.com/nikic/FastRoute)) - A fast routing library.
* <b><code>&nbsp;&nbsp;2658⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;288🍴</code></b> [Klein](https://github.com/klein/klein.php)) - A flexible router.
* <b><code>&nbsp;&nbsp;1264⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;80🍴</code></b> [Pux](https://github.com/c9s/Pux)) - Another fast routing library.
* <b><code>&nbsp;&nbsp;&nbsp;663⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;126🍴</code></b> [Route](https://github.com/thephpleague/route)) - A routing library built on top of Fast Route.

### Templating
*Libraries and tools for templating and lexing.*

* 🌎 [Latte](latte.nette.org/) - The safest and truly intuitive templates for PHP.
* <b><code>&nbsp;&nbsp;&nbsp;358⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;53🍴</code></b> [MtHaml](https://github.com/arnaud-lb/MtHaml)) - A PHP implementation of the HAML template language.
* <b><code>&nbsp;&nbsp;3277⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;436🍴</code></b> [Mustache](https://github.com/bobthecow/mustache.php)) - A PHP implementation of the Mustache template language.
* 🌎 [PHPTAL](phptal.org/) - A PHP implementation of the 🌎 [TAL](en.wikipedia.org/wiki/Template_Attribute_Language) templating language.
* [Plates](http://platesphp.com/) - A native PHP templating library.
* 🌎 [Smarty](www.smarty.net/) - A template engine to complement PHP.
* 🌎 [Twig](twig.symfony.com/) - A comprehensive templating language.

### Static Site Generators
*Tools for pre-processing content to generate web pages.*

* [Couscous](http://couscous.io) - Couscous turns Markdown documentation into beautiful websites. It's GitHub Pages on steroids.
* 🌎 [Jigsaw](jigsaw.tighten.com/) - Simple static sites with Laravel's Blade.
* 🌎 [Sculpin](sculpin.io) - A tool that converts Markdown and Twig into static HTML.

### HTTP
*Libraries for working with HTTP.*

* <b><code>&nbsp;&nbsp;1925⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;250🍴</code></b> [Buzz](https://github.com/kriswallsmith/Buzz)) - Another HTTP client.
* [Guzzle]( https://github.com/guzzle/guzzle) - A comprehensive HTTP client.
* [HTTPlug](http://httplug.io) - An HTTP client abstraction without binding to a specific implementation.
* <b><code>&nbsp;&nbsp;1266⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;79🍴</code></b> [Nyholm PSR-7](https://github.com/Nyholm/psr7)) - A super lightweight PSR-7 implementation. Very strict and very fast.
* 🌎 [PHP VCR](php-vcr.github.io/) - A library for recording and replaying HTTP requests.
* <b><code>&nbsp;&nbsp;3586⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;502🍴</code></b> [Requests](https://github.com/WordPress/Requests)) - A simple HTTP library.
* <b><code>&nbsp;&nbsp;&nbsp;155⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;23🍴</code></b> [Retrofit](https://github.com/tebru/retrofit-php)) - A library to ease creation of REST API clients.
* <b><code>&nbsp;&nbsp;2029⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;53🍴</code></b> [Symfony HTTP Client](https://github.com/symfony/http-client)) - A component to fetch HTTP resources synchronously or asynchronously.
* <b><code>&nbsp;&nbsp;&nbsp;538⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;76🍴</code></b> [Laminas Diactoros](https://github.com/laminas/laminas-diactoros)) - PSR-7 HTTP Message implementation.

### Scraping
*Libraries for scraping websites and detecting crawlers.*

* <b><code>&nbsp;&nbsp;2612⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;311🍴</code></b> [Chrome PHP](https://github.com/chrome-php/chrome)) - Instrument headless Chrome/Chromium instances from PHP.
* <b><code>&nbsp;&nbsp;2327⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;276🍴</code></b> [CrawlerDetect](https://github.com/JayBizzle/Crawler-Detect)) - A PHP class for detecting bots/crawlers/spiders via the user agent.
* <b><code>&nbsp;&nbsp;2207⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;200🍴</code></b> [DiDOM](https://github.com/Imangazaliev/DiDOM)) - A super-fast HTML scrapper and parser.
* <b><code>&nbsp;&nbsp;2143⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;320🍴</code></b> [Embed](https://github.com/php-embed/Embed)) - An information extractor from any web service or page.
* <b><code>&nbsp;&nbsp;1343⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;232🍴</code></b> [PHP Spider](https://github.com/mvdbos/php-spider)) - A configurable and extensible PHP web spider.
* <b><code>&nbsp;&nbsp;3062⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;237🍴</code></b> [Symfony Panther](https://github.com/symfony/panther)) - A browser testing and web crawling library for PHP and Symfony.

### Middlewares
*Libraries for building application using middlewares.*

* <b><code>&nbsp;&nbsp;&nbsp;413⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;14🍴</code></b> [PSR-15 Middlewares](https://github.com/middlewares/psr15-middlewares)) - Inspiring collection of handy middlewares.
* <b><code>&nbsp;&nbsp;&nbsp;329⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;19🍴</code></b> [Relay](https://github.com/relayphp/Relay.Relay)) - A PHP 5.5 PSR-7 middleware dispatcher.
* [Stack](https://github.com/stackphp) - A library of stackable middleware for Symfony.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;57⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;13🍴</code></b> [Laminas Stratigility](https://github.com/laminas/laminas-stratigility)) - Middleware for PHP built on top of PSR-7.

### URL
*Libraries for parsing URLs.*

* <b><code>&nbsp;&nbsp;1226⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;127🍴</code></b> [PHP Domain Parser](https://github.com/jeremykendall/php-domain-parser)) - A domain suffix parser library.
* <b><code>&nbsp;&nbsp;&nbsp;902⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;121🍴</code></b> [Purl](https://github.com/jwage/purl)) - A URL manipulation library.
* <b><code>&nbsp;&nbsp;&nbsp;294⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;19🍴</code></b> [sabre/uri](https://github.com/sabre-io/uri)) - A functional URI manipulation library.
* <b><code>&nbsp;&nbsp;1119⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;71🍴</code></b> [Uri](https://github.com/thephpleague/uri)) - Another URL manipulation library.

### Email
*Libraries for sending and parsing email.*

* <b><code>&nbsp;&nbsp;5842⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;192🍴</code></b> [CssToInlineStyles](https://github.com/tijsverkoyen/CssToInlineStyles)) - A library to inline CSS in email templates.
* <b><code>&nbsp;&nbsp;&nbsp;649⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;79🍴</code></b> [Email Reply Parser](https://github.com/willdurand/EmailReplyParser)) - An email reply parser library.
* <b><code>&nbsp;&nbsp;&nbsp;164⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;20🍴</code></b> [Email Validator](https://github.com/nojacko/email-validator)) - A small email address validation library.
* <b><code>&nbsp;&nbsp;&nbsp;505⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;157🍴</code></b> [Fetch](https://github.com/tedious/Fetch)) - An IMAP library.
* <b><code>&nbsp;&nbsp;9226⭐</code></b> <b><code>&nbsp;&nbsp;3161🍴</code></b> [Mautic](https://github.com/mautic/mautic)) - Email marketing automation
* <b><code>&nbsp;22027⭐</code></b> <b><code>&nbsp;&nbsp;9859🍴</code></b> [PHPMailer](https://github.com/PHPMailer/PHPMailer)) - Another mailer solution.
* <b><code>&nbsp;&nbsp;1696⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;461🍴</code></b> [PHP IMAP](https://github.com/barbushin/php-imap)) - A library to access mailboxes via POP3, IMAP and NNTP.
* <b><code>&nbsp;&nbsp;&nbsp;294⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;30🍴</code></b> [Stampie](https://github.com/Stampie/Stampie)) - A library for email services such as 🌎 [SendGrid](sendgrid.com/en-us), 🌎 [PostMark](postmarkapp.com), 🌎 [MailGun](www.mailgun.com/) and 🌎 [MailChimp](mailchimp.com/features/transactional-email/).
* 🌎 [SwiftMailer](swiftmailer.symfony.com/docs/introduction.html) - A mailer solution.
* <b><code>&nbsp;&nbsp;1589⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;49🍴</code></b> [Symfony Mailer](https://github.com/symfony/mailer)) - A powerful library for creating and sending emails.

### Files
*Libraries for file manipulation and MIME type detection.*

* <b><code>&nbsp;&nbsp;3464⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;344🍴</code></b> [CSV](https://github.com/thephpleague/csv)) - A CSV data manipulation library.
* <b><code>&nbsp;13556⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;847🍴</code></b> [Flysystem](https://github.com/thephpleague/Flysystem)) - Abstraction for local and remote filesystems.
* <b><code>&nbsp;&nbsp;2475⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;352🍴</code></b> [Gaufrette](https://github.com/KnpLabs/Gaufrette)) - A filesystem abstraction layer.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [PHP FFmpeg](https://github.com/PHP-FFmpeg/PHP-FFmpeg/)) - A wrapper for the 🌎 [FFmpeg](www.ffmpeg.org/) video library.
* <b><code>&nbsp;&nbsp;&nbsp;279⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;24🍴</code></b> [UnifiedArchive](https://github.com/wapmorgan/UnifiedArchive)) - A unified reader and writer of compressed archives.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;40⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2🍴</code></b> [Parquet](https://github.com/flow-php/parquet)) - PHP implementation of Parquet file format

### Streams
*Libraries for working with streams.*

* 🌎 [ByteStream](amphp.org/byte-stream) - An asynchronous stream abstraction.
* <b><code>&nbsp;&nbsp;&nbsp;264⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;31🍴</code></b> [Streamer](https://github.com/fzaninotto/Streamer)) - A simple object-orientated stream wrapper library.

### Dependency Injection
*Libraries that implement the dependency injection design pattern.*

* <b><code>&nbsp;&nbsp;&nbsp;353⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;63🍴</code></b> [Aura.Di](https://github.com/auraphp/Aura.Di)) - A serializable dependency injection container with constructor and setter injection, interface and trait awareness, configuration inheritance, and much more.
* <b><code>&nbsp;&nbsp;&nbsp;219⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;17🍴</code></b> [Acclimate](https://github.com/AcclimateContainer/acclimate-container)) - A common interface to dependency injection containers and service locators.
* <b><code>&nbsp;&nbsp;&nbsp;726⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;65🍴</code></b> [Auryn](https://github.com/rdlowrey/Auryn)) - A recursive dependency injector.
* <b><code>&nbsp;&nbsp;&nbsp;863⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;105🍴</code></b> [Container](https://github.com/thephpleague/container)) - Another flexible dependency injection container.
* <b><code>&nbsp;&nbsp;&nbsp;139⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;16🍴</code></b> [Disco](https://github.com/bitExpert/disco)) - A PSR-11 compatible, annotation-based dependency injection container.
* 🌎 [PHP-DI](php-di.org/) - A dependency injection container that supports autowiring.
* <b><code>&nbsp;&nbsp;2667⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;304🍴</code></b> [Pimple](https://github.com/silexphp/Pimple)) - A tiny dependency injection container.
* <b><code>&nbsp;&nbsp;4171⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;91🍴</code></b> [Symfony DI](https://github.com/symfony/dependency-injection)) - A dependency injection container component.

### Imagery
*Libraries for manipulating images.*

* <b><code>&nbsp;&nbsp;1318⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;156🍴</code></b> [Color Extractor](https://github.com/thephpleague/color-extractor)) - A library for extracting colours from images.
* <b><code>&nbsp;&nbsp;2631⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;205🍴</code></b> [Glide](https://github.com/thephpleague/glide)) - An on-demand image manipulation library.
* <b><code>&nbsp;&nbsp;2046⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;174🍴</code></b> [Image Hash](https://github.com/jenssegers/imagehash)) - A library for generating perceptual image hashes.
* <b><code>&nbsp;&nbsp;&nbsp;913⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;141🍴</code></b> [Image Optimizer](https://github.com/psliwa/image-optimizer)) - A library for optimizing images.
* 🌎 [Imagine](imagine.readthedocs.io/en/latest/index.html) - An image manipulation library.
* <b><code>&nbsp;14319⭐</code></b> <b><code>&nbsp;&nbsp;1499🍴</code></b> [Intervention Image](https://github.com/Intervention/image)) - Another image manipulation library.
* <b><code>&nbsp;&nbsp;&nbsp;860⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;185🍴</code></b> [PHP Image Workshop](https://github.com/Sybio/ImageWorkshop)) - Another image manipulation library.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [PHP QR Code](https://github.com/chillerlan/php-qrcode/)) - QR Code generator and reader.

### Testing
*Libraries for testing codebases and generating test data.*

* <b><code>&nbsp;&nbsp;2540⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;330🍴</code></b> [Alice](https://github.com/nelmio/alice)) - An expressive fixture generation library.
* <b><code>&nbsp;&nbsp;1444⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;146🍴</code></b> [Atoum](https://github.com/atoum/atoum)) - A simple testing library.
* 🌎 [Behat](docs.behat.org/en/latest/) - A behaviour driven development (BDD) testing framework.
* <b><code>&nbsp;&nbsp;4856⭐</code></b> <b><code>&nbsp;&nbsp;1290🍴</code></b> [Codeception](https://github.com/Codeception/Codeception)) - A full stack testing framework.
* <b><code>&nbsp;&nbsp;3932⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;418🍴</code></b> [Faker](https://github.com/fakerphp/faker)) - A fake data generator library.
* <b><code>&nbsp;&nbsp;&nbsp;775⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;108🍴</code></b> [Foundry](https://github.com/zenstruck/foundry)) - A fixture factory generation library for Doctrine.
* <b><code>&nbsp;&nbsp;2173⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;177🍴</code></b> [Infection](https://github.com/infection/infection)) - An AST-based PHP Mutation testing framework.
* <b><code>&nbsp;&nbsp;1148⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;70🍴</code></b> [Kahlan](https://github.com/kahlan/kahlan)) - Full stack Unit/BDD testing framework with built-in stub, mock and code-coverage support.
* 🌎 [Mink](mink.behat.org/en/latest/) - Web acceptance testing.
* <b><code>&nbsp;10731⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;464🍴</code></b> [Mockery](https://github.com/mockery/mockery)) - A mock object library for testing.
* <b><code>&nbsp;&nbsp;&nbsp;481⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;73🍴</code></b> [Nette Tester](https://github.com/nette/tester)) - A productive and enjoyable parallel unit testing framework.
* <b><code>&nbsp;&nbsp;2450⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;251🍴</code></b> [ParaTest](https://github.com/paratestphp/paratest)) - A parallel testing library for PHPUnit.
* 🌎 [Pest](pestphp.com/) - A testing framework with a focus on simplicity.
* <b><code>&nbsp;&nbsp;&nbsp;476⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;87🍴</code></b> [Phake](https://github.com/phake/phake)) - Another mock object library for testing.
* <b><code>&nbsp;&nbsp;&nbsp;369⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;20🍴</code></b> [PHP-Mock](https://github.com/php-mock/php-mock)) - A mock library for built-in PHP functions (e.g. time()).
* <b><code>&nbsp;&nbsp;&nbsp;560⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;49🍴</code></b> [PHP MySQL Engine](https://github.com/vimeo/php-mysql-engine)) -  A MySQL engine written in pure PHP.
* <b><code>&nbsp;&nbsp;1901⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;287🍴</code></b> [PHPSpec](https://github.com/phpspec/phpspec)) - A design by specification unit testing library.
* 🌎 [PHPT](qa.php.net/write-test.php) - A test tool used by PHP itself.
* <b><code>&nbsp;20004⭐</code></b> <b><code>&nbsp;&nbsp;2228🍴</code></b> [PHPUnit](https://github.com/sebastianbergmann/phpunit)) - A unit testing framework.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [PHPUnit Polyfills](https://github.com/Yoast/PHPUnit-Polyfills/)) - Simplifies running PHPUnit tests on multiple PHPUnit versions.
* <b><code>&nbsp;&nbsp;8491⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;246🍴</code></b> [Prophecy](https://github.com/phpspec/prophecy)) - A highly opinionated mocking framework.
* <b><code>&nbsp;&nbsp;1440⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;104🍴</code></b> [VFS Stream](https://github.com/bovigo/vfsStream)) - A virtual filesystem stream wrapper for testing.

### Continuous Integration
*Libraries and applications for continuous integration.*

* 🌎 [CircleCI](circleci.com) - A continuous integration platform.
* 🌎 [GitlabCi](about.gitlab.com/solutions/continuous-integration/) - Let GitLab CI test, build, deploy your code. TravisCi like.
* 🌎 [Jenkins](www.jenkins.io/) - A continuous integration platform with 🌎 [PHP support](www.jenkins.io/solutions/php/).
* <b><code>&nbsp;&nbsp;&nbsp;651⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;46🍴</code></b> [JoliCi](https://github.com/jolicode/JoliCi)) - A continuous integration client written in PHP and powered by Docker.
* <b><code>&nbsp;&nbsp;2400⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;429🍴</code></b> [PHPCI](https://github.com/dancryer/phpci)) - An open-source continuous integration platform for PHP.
* 🌎 [SemaphoreCI](semaphore.io/) - A continuous integration platform for open-source and private projects.
* 🌎 [Travis CI](www.travis-ci.com) - A continuous integration platform.
* <b><code>&nbsp;&nbsp;3180⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;405🍴</code></b> [Setup PHP](https://github.com/shivammathur/setup-php)) - A GitHub Action for PHP.

### Documentation
*Libraries for generating project documentation.*

* <b><code>&nbsp;&nbsp;2167⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;308🍴</code></b> [APIGen](https://github.com/apigen/apigen)) - Another API documentation generator.
* <b><code>&nbsp;&nbsp;&nbsp;824⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;191🍴</code></b> [daux.io](https://github.com/dauxio/daux.io)) - A documentation generator that uses Markdown files.
* 🌎 [phpDocumentor](phpdoc.org/) - A documentation generator.
* 🌎 [phpDox](phpdox.net/) - A documentation generator for PHP projects (that is not limited to API documentation).
* <b><code>&nbsp;&nbsp;5289⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;946🍴</code></b> [zircote/swagger-php](https://github.com/zircote/swagger-php)) - Generate OpenAPI documentation for your RESTful API.

### Security
*Libraries for generating secure random numbers, encrypting data and scanning and testing for vulnerabilities.*

* <b><code>&nbsp;&nbsp;&nbsp;704⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;116🍴</code></b> [AntiXSS](https://github.com/voku/anti-xss)) - A library that tries to preventing Cross-Site Scripting (XSS) attacks by blacklisting.
* 🌎 [Halite](paragonie.com/project/halite) - A simple library for encryption using <b><code>&nbsp;13472⭐</code></b> <b><code>&nbsp;&nbsp;1854🍴</code></b> [libsodium](https://github.com/jedisct1/libsodium)).
* <b><code>&nbsp;&nbsp;1277⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;75🍴</code></b> [Optimus](https://github.com/jenssegers/optimus)) - Id obfuscation based on Knuth's multiplicative hashing method.
* 🌎 [OWASP](owasp.org/) - Explore the world of cyber security.
* <b><code>&nbsp;&nbsp;3750⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;542🍴</code></b> [PHPGGC](https://github.com/ambionics/phpggc)) - A library of PHP unserializable payloads along with a tool to generate them.
* <b><code>&nbsp;&nbsp;3872⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;313🍴</code></b> [PHP Encryption](https://github.com/defuse/php-encryption)) - Secure PHP Encryption Library.
* 🌎 [PHPSecLib](phpseclib.sourceforge.net) - A pure PHP secure communications library.
* <b><code>&nbsp;&nbsp;8166⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;147🍴</code></b> [random_compat](https://github.com/paragonie/random_compat)) - PHP 5.x support for `random_bytes()` and `random_int()`
* <b><code>&nbsp;&nbsp;2871⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;111🍴</code></b> [Roave Security Advisories](https://github.com/Roave/SecurityAdvisories)) - This package ensures that your application doesn't have installed dependencies with known security vulnerabilities.
* <b><code>&nbsp;&nbsp;&nbsp;548⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;47🍴</code></b> [Secure Headers](https://github.com/BePsvPT/secure-headers)) - A package that adds security related headers to HTTP response.
* <b><code>&nbsp;36652⭐</code></b> <b><code>&nbsp;&nbsp;6204🍴</code></b> [SQLMap](https://github.com/sqlmapproject/sqlmap)) - An automatic SQL injection and database takeover tool.
* <b><code>&nbsp;14780⭐</code></b> <b><code>&nbsp;&nbsp;2515🍴</code></b> [Zap](https://github.com/zaproxy/zaproxy)) - An integrated penetration testing tool for web applications.

### Passwords
*Libraries and tools for working with and storing passwords.*

* <b><code>&nbsp;&nbsp;&nbsp;118⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9🍴</code></b> [GenPhrase](https://github.com/timoh6/GenPhrase)) - A library for generating secure random passphrases.
* <b><code>&nbsp;&nbsp;2137⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;411🍴</code></b> [Password Compat](https://github.com/ircmaxell/password_compat)) - A compatibility library for the new PHP 5.5 password functions.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;78⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;20🍴</code></b> [Password Policy](https://github.com/ircmaxell/password-policy)) - A password policy library for PHP and JavaScript.
* <b><code>&nbsp;&nbsp;&nbsp;142⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;16🍴</code></b> [Password Validator](https://github.com/jeremykendall/password-validator)) - A library for validating and upgrading password hashes.
* <b><code>&nbsp;&nbsp;&nbsp;303⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;37🍴</code></b> [Password-Generator](https://github.com/hackzilla/password-generator)) - PHP library to generate random passwords.
* <b><code>&nbsp;&nbsp;&nbsp;372⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;59🍴</code></b> [PHP Password Lib](https://github.com/ircmaxell/PHP-PasswordLib)) - A library for generating and validating passwords.
* 🌎 [phpass](www.openwall.com/phpass/) - A portable password hashing framework.
* <b><code>&nbsp;&nbsp;&nbsp;866⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;115🍴</code></b> [Zxcvbn PHP](https://github.com/bjeavons/zxcvbn-php)) - A realistic PHP password strength estimate library based on Zxcvbn JS.

### Code Analysis
*Libraries and tools for analysing, parsing and manipulating codebases.*

* <b><code>&nbsp;&nbsp;1232⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;137🍴</code></b> [Better Reflection](https://github.com/Roave/BetterReflection)) - AST-based reflection library that allows analysis and manipulation of code
* 🌎 [Code Climate](codeclimate.com) - An automated code review.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;74⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;17🍴</code></b> [Editorconfig-Checker](https://github.com/editorconfig-checker/editorconfig-checker.php)) - A command line utility which verifies that your files implement your `.editorconfig` rules.
* <b><code>&nbsp;&nbsp;4269⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;446🍴</code></b> [GrumPHP](https://github.com/phpro/grumphp)) - A PHP code-quality tool.
* 🌎 [PHP AST Viewer](php-ast-viewer.com/) - A tool for viewing the Abstract Syntax Tree of PHP code.
* <b><code>&nbsp;&nbsp;&nbsp;579⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;46🍴</code></b> [PHP Magic Number Detector](https://github.com/povils/phpmnd)) - A library that detects magic numbers in code.
* <b><code>&nbsp;17409⭐</code></b> <b><code>&nbsp;&nbsp;1122🍴</code></b> [PHP Parser](https://github.com/nikic/PHP-Parser)) - A PHP parser written in PHP.
* <b><code>&nbsp;&nbsp;&nbsp;434⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;28🍴</code></b> [PHP Semantic Versioning Checker](https://github.com/tomzx/php-semver-checker)) - A command line utility that compares two source sets and determines the appropriate semantic versioning to apply.
* <b><code>&nbsp;&nbsp;1807⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;156🍴</code></b> [Phpactor](https://github.com/phpactor/phpactor)) - PHP completion, refactoring and introspection tool.
* <b><code>&nbsp;&nbsp;2351⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;163🍴</code></b> [PHPLOC](https://github.com/sebastianbergmann/phploc)) - A tool for quickly measuring the size of a PHP project.
* <b><code>&nbsp;&nbsp;&nbsp;561⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;58🍴</code></b> [PHPQA](https://github.com/EdgedesignCZ/phpqa)) - A tool for running QA tools (phploc, phpcpd, phpcs, pdepend, phpmd, phpmetrics).
* <b><code>&nbsp;10201⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;739🍴</code></b> [Rector](https://github.com/rectorphp/rector)) - A tool to upgrade and refactor code.
* 🌎 [Scrutinizer](scrutinizer-ci.com/) - A web tool to <b><code>&nbsp;&nbsp;&nbsp;440⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;50🍴</code></b> [scrutinise PHP code](https://github.com/scrutinizer-ci/php-analyzer)).
* <b><code>&nbsp;&nbsp;&nbsp;564⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;69🍴</code></b> [UBench](https://github.com/devster/ubench)) - A simple micro-benchmark library.

### Code Quality
*Libraries for managing code quality, formatting and linting.*

* <b><code>&nbsp;&nbsp;1094⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;89🍴</code></b> [CaptainHook](https://github.com/captainhook-git/captainhook)) - An easy-to-use and flexible Git hook library.
* <b><code>&nbsp;&nbsp;1467⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;92🍴</code></b> [PHP CodeSniffer](https://github.com/PHPCSStandards/PHP_CodeSniffer)) - A library that detects and can auto-fix PHP, CSS and JS coding standard violations.
* <b><code>&nbsp;13465⭐</code></b> <b><code>&nbsp;&nbsp;1634🍴</code></b> [PHP CS Fixer](https://github.com/PHP-CS-Fixer/PHP-CS-Fixer)) - A coding standards fixer library.
* 🌎 [PHP CS Fixer Configurator](mlocati.github.io/php-cs-fixer-configurator/) - A web application to help configure PHP CS Fixer rule sets.
* <b><code>&nbsp;&nbsp;2417⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;348🍴</code></b> [PHP Mess Detector](https://github.com/phpmd/phpmd)) - A library that scans code for bugs, sub-optimal code, unused parameters and more.
* <b><code>&nbsp;&nbsp;&nbsp;166⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;32🍴</code></b> [PHPCheckstyle](https://github.com/PHPCheckstyle/phpcheckstyle)) - A tool to help adhere to certain coding conventions.
* <b><code>&nbsp;&nbsp;2213⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;189🍴</code></b> [PHPCPD](https://github.com/sebastianbergmann/phpcpd)) - A library that detects copied and pasted code.
* <b><code>&nbsp;&nbsp;3095⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;177🍴</code></b> [Laravel Pint](https://github.com/laravel/pint)) - A coding standards fixer library for Laravel.

### Static Analysis
*Libraries for performing static analysis of PHP code.*

* <b><code>&nbsp;&nbsp;&nbsp;378⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;41🍴</code></b> [Exakat](https://github.com/exakat/exakat)) - A static analysis engine for PHP.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [Deptrac](https://github.com/qossmic/deptrac)) - A static code analysis tool that helps to enforce rules for dependencies between software layers.
* <b><code>&nbsp;&nbsp;&nbsp;394⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;22🍴</code></b> [Mondrian](https://github.com/Trismegiste/Mondrian)) - A code analysis tool using Graph Theory.
* <b><code>&nbsp;&nbsp;5600⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;366🍴</code></b> [phan](https://github.com/phan/phan)) - A static analyzer based on PHP 7+ and the php-ast extension.
* <b><code>&nbsp;&nbsp;1234⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;60🍴</code></b> [PHP Architecture Tester](https://github.com/carlosas/phpat)) - Easy-to-use architecture testing tool for PHP.
* <b><code>&nbsp;&nbsp;2278⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;206🍴</code></b> [PHPCompatibility](https://github.com/PHPCompatibility/PHPCompatibility)) - A PHP compatibility checker for PHP CodeSniffer.
* <b><code>&nbsp;&nbsp;&nbsp;572⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;43🍴</code></b> [PhpDependencyAnalysis](https://github.com/mamuz/PhpDependencyAnalysis)) - A tool to create customizable dependency graphs.
* <b><code>&nbsp;&nbsp;1515⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;69🍴</code></b> [PHPDoc Parser](https://github.com/phpstan/phpdoc-parser)) - Next-gen phpDoc parser with support for intersection types and generics
* <b><code>&nbsp;&nbsp;2586⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;265🍴</code></b> [PHP Metrics](https://github.com/phpmetrics/PhpMetrics)) - A static metric library.
* <b><code>&nbsp;&nbsp;&nbsp;203⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;18🍴</code></b> [PHP Migration](https://github.com/monque/PHP-Migration)) - A static analyzer for PHP version migration.
* <b><code>&nbsp;13829⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;939🍴</code></b> [PHPStan](https://github.com/phpstan/phpstan)) - A PHP Static Analysis Tool.
* <b><code>&nbsp;&nbsp;5805⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;691🍴</code></b> [Psalm](https://github.com/vimeo/psalm)) - A static analysis tool for finding errors in PHP applications.

### Architectural
*Libraries related to design patterns, programming approaches and ways to organize code.*

* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Design Patterns PHP](https://github.com/DesignPatternsPHP/DesignPatternsPHP )) - A repository of software patterns implemented in PHP.
* <b><code>&nbsp;&nbsp;1340⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;186🍴</code></b> [Finite](https://github.com/yohang/Finite)) - A simple PHP finite state machine.
* <b><code>&nbsp;&nbsp;1986⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;209🍴</code></b> [Functional PHP](https://github.com/lstrojny/functional-php)) - A functional programming library.
* <b><code>&nbsp;&nbsp;1145⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;69🍴</code></b> [Iter](https://github.com/nikic/iter)) - A library that provides iteration primitives using generators.
* <b><code>&nbsp;&nbsp;&nbsp;149⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;13🍴</code></b> [IterTools PHP](https://github.com/markrogoyski/itertools-php)) - A library that provides functionality for working with iterable entities (similar to itertools library in Python).
* <b><code>&nbsp;&nbsp;1000⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;74🍴</code></b> [Pipeline](https://github.com/thephpleague/pipeline)) - A pipeline pattern implementation.
* <b><code>&nbsp;&nbsp;&nbsp;614⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;25🍴</code></b> [Porter](https://github.com/ScriptFUSION/Porter)) - Data import abstraction library for consuming Web APIs and other data sources.
* <b><code>&nbsp;&nbsp;&nbsp;881⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;97🍴</code></b> [RulerZ](https://github.com/K-Phoen/rulerz)) - A powerful rule engine and implementation of the Specification pattern.

### Debugging and Profiling
*Libraries and tools for debugging errors and profiling code.*

* 🌎 [APM](pecl.php.net/package/APM) - Monitoring extension collecting errors and statistics into SQLite/MySQL/StatsD.
* <b><code>&nbsp;&nbsp;1338⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;282🍴</code></b> [Barbushin PHP Console](https://github.com/barbushin/php-console)) - Another web debugging console using Google Chrome.
* <b><code>&nbsp;&nbsp;2825⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;287🍴</code></b> [Kint](https://github.com/kint-php/kint)) - A debugging and profiling tool.
* <b><code>&nbsp;&nbsp;&nbsp;322⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;38🍴</code></b> [Metrics](https://github.com/beberlei/metrics)) - A simple metrics API library.
* <b><code>&nbsp;&nbsp;&nbsp;769⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;37🍴</code></b> [PCOV](https://github.com/krakjoe/pcov)) - A self-contained code coverage compatible driver.
* <b><code>&nbsp;&nbsp;&nbsp;526⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;90🍴</code></b> [PHP Console](https://github.com/Seldaek/php-console)) - A web debugging console.
* [PHP Debug Bar](http://phpdebugbar.com/) - A debugging toolbar.
* <b><code>&nbsp;&nbsp;1980⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;130🍴</code></b> [PHPBench](https://github.com/phpbench/phpbench)) - A benchmarking Framework.
* <b><code>&nbsp;&nbsp;1477⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;69🍴</code></b> [PHPSpy](https://github.com/adsr/phpspy)) - A low-overhead sampling profiler.
* <b><code>&nbsp;&nbsp;7446⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;101🍴</code></b> [Symfony VarDumper](https://github.com/symfony/var-dumper)) - A variable dumper component.
* <b><code>&nbsp;&nbsp;1818⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;220🍴</code></b> [Tracy](https://github.com/nette/tracy)) - A simple error detection, logging and time measuring library.
* <b><code>&nbsp;13245⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;601🍴</code></b> [Whoops](https://github.com/filp/whoops)) - A pretty error-handling library.
* <b><code>&nbsp;&nbsp;3373⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;594🍴</code></b> [xDebug](https://github.com/xdebug/xdebug)) - A debug and profile tool for PHP.
* <b><code>&nbsp;&nbsp;2613⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;913🍴</code></b> [XHProf](https://github.com/phacility/xhprof)) - A profiling tool originally developed by Facebook.
* 🌎 [Z-Ray](www.zend.com/products/z-ray) - A debug and profile tool for Zend Server.

### Error Tracking and Monitoring Services
*Self-hosted or cloud-based application performance monitoring & error tracking tools*

* 🌎 [Blackfire](www.blackfire.io) - A low-overhead code profiler.
* 🌎 [BugSnag](www.bugsnag.com/) - Error and Real User Monitoring.
* 🌎 [Honeybadger](www.honeybadger.io/) - Error Tracking & Application Monitoring for Developers.
* 🌎 [Rollbar](rollbar.com/) - Error Logging & Tracking Service for Software Teams.
* 🌎 [Sentry](sentry.io/welcome/) - Application Performance Monitoring & Error Tracking Software.
* 🌎 [Tideways](tideways.com/) - Monitoring and profiling tool.

### Build Tools
*Project build and automation tools.*

* <b><code>&nbsp;&nbsp;1282⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;106🍴</code></b> [Box](https://github.com/box-project/box)) - A utility to build PHAR files.
* <b><code>&nbsp;&nbsp;&nbsp;265⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;16🍴</code></b> [Construct](https://github.com/jonathantorres/construct)) - A PHP project/micro-package generator.
* 🌎 [Phing](www.phing.info/) - A PHP project build system inspired by Apache Ant.
* <b><code>&nbsp;&nbsp;&nbsp;458⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;46🍴</code></b> [RMT](https://github.com/liip/RMT)) - A library for versioning and releasing software.

### Task Runners
*Libraries for automating and running tasks.*

* 🌎 [Bldr](bldr.io/) - A PHP Task runner built on Symfony components.
* <b><code>&nbsp;&nbsp;1048⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;152🍴</code></b> [Jobby](https://github.com/jobbyphp/jobby)) - A PHP cron job manager without modifying crontab.
* <b><code>&nbsp;&nbsp;2704⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;303🍴</code></b> [Robo](https://github.com/consolidation/Robo)) - A PHP Task runner with object-orientated configurations.
* 🌎 [Task](taskphp.github.io/) - A pure PHP task runner inspired by Grunt and Gulp.

### Navigation
*Tools for building navigation structures.*

* <b><code>&nbsp;&nbsp;1402⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;192🍴</code></b> [KnpMenu](https://github.com/KnpLabs/KnpMenu)) - A menu library.
* <b><code>&nbsp;&nbsp;&nbsp;757⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;101🍴</code></b> [Menu](https://github.com/spatie/menu)) - A flexible menu library with a fluent interface.

### Asset Management
*Tools for managing, compressing and minifying website assets.*

* <b><code>&nbsp;&nbsp;&nbsp;762⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;146🍴</code></b> [JShrink](https://github.com/tedious/JShrink)) - A JavaScript minifier library.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Laravel Mix](https://github.com/laravel-mix/laravel-mix )) - An elegant wrapper around Webpack for the 80% use case.
* <b><code>&nbsp;&nbsp;3161⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;12🍴</code></b> [Symfony Asset](https://github.com/symfony/asset)) - Manages URL generation and versioning of web assets.
* <b><code>&nbsp;&nbsp;2234⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;198🍴</code></b> [Symfony Encore](https://github.com/symfony/webpack-encore)) - A simple but powerful API for processing and compiling assets built around Webpack.

### Geolocation
*Libraries for geocoding addresses and working with latitudes and longitudes.*

* <b><code>&nbsp;&nbsp;5248⭐</code></b> <b><code>&nbsp;&nbsp;1541🍴</code></b> [Country List](https://github.com/umpirsky/country-list)) - A list of all countries with names and ISO 3166-1 codes.
* 🌎 [GeoCoder](geocoder-php.org/) - A geocoding library.
* <b><code>&nbsp;&nbsp;&nbsp;304⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;47🍴</code></b> [GeoJSON](https://github.com/jmikola/geojson)) - A GeoJSON implementation.
* <b><code>&nbsp;&nbsp;1401⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;126🍴</code></b> [GeoTools](https://github.com/thephpleague/geotools)) - A library of geo-related tools.
* <b><code>&nbsp;&nbsp;1610⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;200🍴</code></b> [PHPGeo](https://github.com/mjaschen/phpgeo)) - A simple geo library.

### Date and Time
*Libraries for working with dates and times.*

* <b><code>&nbsp;&nbsp;&nbsp;465⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;65🍴</code></b> [CalendR](https://github.com/yohang/CalendR)) - A calendar management library.
* <b><code>&nbsp;16630⭐</code></b> <b><code>&nbsp;&nbsp;1293🍴</code></b> [Carbon](https://github.com/briannesbitt/Carbon)) - A simple DateTime API extension.
* <b><code>&nbsp;&nbsp;1360⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;68🍴</code></b> [Chronos](https://github.com/cakephp/chronos)) - A DateTime API extension supporting both mutable and immutable date/time.
* <b><code>&nbsp;&nbsp;&nbsp;971⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;152🍴</code></b> [Moment.php](https://github.com/fightbulc/moment.php)) - Moment.js inspired PHP DateTime handler with i18n support.
* <b><code>&nbsp;&nbsp;1077⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;164🍴</code></b> [Yasumi](https://github.com/azuyalabs/yasumi)) - A library to help you calculate the dates and names of holidays.

### Event
*Libraries that are event-driven or implement non-blocking event loops.*
* <b><code>&nbsp;&nbsp;4399⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;257🍴</code></b> [Amp](https://github.com/amphp/amp)) - An event driven non-blocking I/O library.
* <b><code>&nbsp;&nbsp;1511⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;173🍴</code></b> [Broadway](https://github.com/broadway/broadway)) - An event source and CQRS library.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;22⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3🍴</code></b> [CakePHP Event](https://github.com/cakephp/event)) - An event dispatcher library.
* <b><code>&nbsp;&nbsp;&nbsp;134⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;39🍴</code></b> [Elephant.io](https://github.com/ElephantIO/elephant.io)) - Yet another web socket library.
* <b><code>&nbsp;&nbsp;1340⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;74🍴</code></b> [Evenement](https://github.com/igorw/evenement)) - An event dispatcher library.
* <b><code>&nbsp;&nbsp;1567⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;48🍴</code></b> [Event](https://github.com/thephpleague/event)) - An event library with a focus on domain events.
* <b><code>&nbsp;&nbsp;&nbsp;563⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;33🍴</code></b> [Fast CGI Client](https://github.com/hollodotme/fast-cgi-client)) - A client to make synchronous/asynchronous requests through php-fpm socket.
* 🌎 [FrankenPHP](frankenphp.dev/) - A modern PHP app server written in Go.
* <b><code>&nbsp;&nbsp;&nbsp;614⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;100🍴</code></b> [Pawl](https://github.com/ratchetphp/Pawl)) - An asynchronous web socket client.
* <b><code>&nbsp;&nbsp;&nbsp;547⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;76🍴</code></b> [Prooph Event Store](https://github.com/prooph/event-store)) - An event source component to persist event messages
* <b><code>&nbsp;&nbsp;&nbsp;307⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;17🍴</code></b> [PHP Defer](https://github.com/php-defer/php-defer)) - Golang's defer statement for PHP.
* <b><code>&nbsp;&nbsp;6427⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;790🍴</code></b> [Ratchet](https://github.com/ratchetphp/Ratchet)) - A web socket library.
* <b><code>&nbsp;&nbsp;9083⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;719🍴</code></b> [ReactPHP](https://github.com/reactphp/reactphp)) - An event driven non-blocking I/O library.
* <b><code>&nbsp;&nbsp;1733⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;141🍴</code></b> [RxPHP](https://github.com/ReactiveX/RxPHP)) - A reactive extension library.
* <b><code>&nbsp;18848⭐</code></b> <b><code>&nbsp;&nbsp;3159🍴</code></b> [Swoole](https://github.com/swoole/swoole-src)) - An event-driven asynchronous and concurrent networking communication framework with high performance for PHP written in C.
* <b><code>&nbsp;11515⭐</code></b> <b><code>&nbsp;&nbsp;2271🍴</code></b> [Workerman](https://github.com/walkor/Workerman)) - An event driven non-blocking I/O library.

### Logging
*Libraries for generating and working with log files.*

* <b><code>&nbsp;21382⭐</code></b> <b><code>&nbsp;&nbsp;1906🍴</code></b> [Monolog](https://github.com/Seldaek/monolog)) - A comprehensive logger.

### E-commerce
*Libraries and applications for taking payments and building online e-commerce stores.*

* <b><code>&nbsp;&nbsp;4811⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;443🍴</code></b> [Money](https://github.com/moneyphp/money)) - A PHP implementation of Fowler's money pattern.
* <b><code>&nbsp;&nbsp;1882⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;111🍴</code></b> [Brick Money](https://github.com/brick/money)) - A money library for PHP, with support for contexts, cash roundings, currency conversion.
* <b><code>&nbsp;&nbsp;6045⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;930🍴</code></b> [OmniPay](https://github.com/thephpleague/omnipay)) - A framework agnostic multi-gateway payment processing library.
* <b><code>&nbsp;&nbsp;1920⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;350🍴</code></b> [Payum](https://github.com/payum/payum)) - A payment abstraction library.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Shopsys Framework](https://github.com/shopsys/shopsys/)) - An open source e-commerce platform for in-house development teams.
* <b><code>&nbsp;&nbsp;3277⭐</code></b> <b><code>&nbsp;&nbsp;1159🍴</code></b> [Shopware](https://github.com/shopware/shopware)) - Highly customizable e-commerce software
* <b><code>&nbsp;&nbsp;1328⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;144🍴</code></b> [Swap](https://github.com/florianv/swap)) - An exchange rates library.
* 🌎 [Sylius](sylius.com/) - An open source e-commerce solution.

### PDF
*Libraries and software for working with PDF files.*

* <b><code>&nbsp;&nbsp;5177⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;507🍴</code></b> [Browsershot](https://github.com/spatie/browsershot)) - Convert HTML to an image, PDF or string.
* <b><code>&nbsp;11075⭐</code></b> <b><code>&nbsp;&nbsp;1832🍴</code></b> [Dompdf](https://github.com/dompdf/dompdf)) - A HTML to PDF converter.
* <b><code>&nbsp;&nbsp;&nbsp;364⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;21🍴</code></b> [Gotenberg](https://github.com/gotenberg/gotenberg-php)) - A PHP client for interacting with Gotenberg.
* <b><code>&nbsp;&nbsp;4469⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;437🍴</code></b> [Snappy](https://github.com/KnpLabs/snappy)) - A PDF and image generation library.
* 🌎 [TCPDF](tcpdf.org/) - An open source PHP class for generating PDF documents.

### Office
*Libraries for working with office suite documents.*

* <b><code>&nbsp;&nbsp;1362⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;538🍴</code></b> [PHPPowerPoint](https://github.com/PHPOffice/PHPPresentation)) - A library for working with Microsoft PowerPoint Presentations.
* <b><code>&nbsp;&nbsp;7547⭐</code></b> <b><code>&nbsp;&nbsp;2736🍴</code></b> [PHPWord](https://github.com/PHPOffice/PHPWord)) - A library for working with Microsoft Word documents.
* <b><code>&nbsp;13896⭐</code></b> <b><code>&nbsp;&nbsp;3631🍴</code></b> [PHPSpreadsheet](https://github.com/PHPOffice/PhpSpreadsheet)) - A pure PHP library for reading and writing spreadsheet files (successor of PHPExcel).
* <b><code>&nbsp;&nbsp;1094⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;130🍴</code></b> [OpenSpout](https://github.com/openspout/openspout)) - A community driven fork of `box/spout`, a PHP library to read and write spreadsheet files (CSV, XLSX and ODS), in a fast and scalable way.
### Database
*Libraries for interacting with databases using object-relational mapping (ORM) or datamapping techniques.*

* <b><code>&nbsp;&nbsp;&nbsp;428⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;22🍴</code></b> [Atlas.Orm](https://github.com/atlasphp/Atlas.Orm)) - A data mapper implementation for your persistence model in PHP.
* <b><code>&nbsp;&nbsp;&nbsp;564⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;104🍴</code></b> [Aura.Sql](https://github.com/auraphp/Aura.Sql)) - Provides an extension to the native PDO along with a profiler and connection locator.
* <b><code>&nbsp;&nbsp;&nbsp;456⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;87🍴</code></b> [Aura.SqlQuery](https://github.com/auraphp/Aura.SqlQuery)) - Independent query builders for MySQL, PostgreSQL, SQLite, and Microsoft SQL Server.
* <b><code>&nbsp;&nbsp;2231⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;454🍴</code></b> [Baum](https://github.com/etrepat/baum)) - A nested set implementation for Eloquent.
* <b><code>&nbsp;&nbsp;&nbsp;148⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;15🍴</code></b> [CakePHP ORM](https://github.com/cakephp/orm)) - Object-Relational Mapper, implemented using the DataMapper pattern.
* <b><code>&nbsp;&nbsp;1327⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;84🍴</code></b> [Cycle ORM](https://github.com/cycle/orm)) - PHP DataMapper, ORM.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Doctrine Extensions](https://github.com/doctrine-extensions/DoctrineExtensions )) - A collection of Doctrine behavioural extensions.
* 🌎 [Doctrine](www.doctrine-project.org/) - A comprehensive DBAL and ORM.
* <b><code>&nbsp;&nbsp;2757⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;610🍴</code></b> [Laravel Eloquent](https://github.com/illuminate/database)) - A simple ORM.
* <b><code>&nbsp;&nbsp;&nbsp;164⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;31🍴</code></b> [Pomm](https://github.com/chanmix51/Pomm)) - An Object Model Manager for PostgreSQL.
* <b><code>&nbsp;&nbsp;4973⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;190🍴</code></b> [ProxyManager](https://github.com/Ocramius/ProxyManager)) - A set of utilities to generate proxy objects for data mappers.
* 🌎 [RedBean](redbeanphp.com/index.php) - A lightweight, configuration-less ORM.
* <b><code>&nbsp;&nbsp;&nbsp;187⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;27🍴</code></b> [Slimdump](https://github.com/webfactory/slimdump)) - An easy dumper tool for MySQL.
* <b><code>&nbsp;&nbsp;&nbsp;599⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;98🍴</code></b> [Spot2](https://github.com/spotorm/spot2)) - A MySQL datamapper ORM.

### Migrations
Libraries to help manage database schemas and migrations.

* 🌎 [Doctrine Migrations](www.doctrine-project.org/projects/migrations.html) - A migration library for Doctrine.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;39⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1🍴</code></b> [Migrations](https://github.com/icomefromthenet/Migrations)) - A migration management library.
* <b><code>&nbsp;&nbsp;4517⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;889🍴</code></b> [Phinx](https://github.com/cakephp/phinx)) - Another database migration library.
* <b><code>&nbsp;&nbsp;&nbsp;570⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;95🍴</code></b> [PHPMig](https://github.com/davedevelopment/phpmig)) - Another migration management library.
* <b><code>&nbsp;&nbsp;&nbsp;502⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;98🍴</code></b> [Ruckusing](https://github.com/ruckus/ruckusing-migrations)) - Database migrations for PHP ala ActiveRecord Migrations with support for MySQL, Postgres, SQLite.

### NoSQL
*Libraries for working with "NoSQL" backends.*

* <b><code>&nbsp;&nbsp;&nbsp;918⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;212🍴</code></b> [MongoDB](https://github.com/mongodb/mongo-php-driver)) - MongoDB PHP Driver.
* <b><code>&nbsp;&nbsp;&nbsp;239⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;46🍴</code></b> [PHPMongo](https://github.com/sokil/php-mongo)) - A MongoDB ORM.
* <b><code>&nbsp;&nbsp;7752⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;998🍴</code></b> [Predis](https://github.com/predis/predis)) - A feature-complete Redis library.

### Queue
*Libraries for working with event and task queues.*

* <b><code>&nbsp;&nbsp;1212⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;129🍴</code></b> [Bernard](https://github.com/bernardphp/bernard)) - A multibackend abstraction library.
* <b><code>&nbsp;&nbsp;&nbsp;741⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;107🍴</code></b> [BunnyPHP](https://github.com/jakubkulhan/bunny)) - A performant pure-PHP AMQP (RabbitMQ) sync and also async (ReactPHP) library.
* <b><code>&nbsp;&nbsp;1925⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;283🍴</code></b> [Pheanstalk](https://github.com/pheanstalk/pheanstalk)) - A Beanstalkd client library.
* <b><code>&nbsp;&nbsp;4597⭐</code></b> <b><code>&nbsp;&nbsp;1032🍴</code></b> [PHP AMQP](https://github.com/php-amqplib/php-amqplib)) - A pure PHP AMQP library.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;64⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7🍴</code></b> [Tarantool Queue](https://github.com/tarantool-php/queue)) - PHP bindings for Tarantool Queue.
* <b><code>&nbsp;&nbsp;&nbsp;276⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;62🍴</code></b> [Thumper](https://github.com/php-amqplib/Thumper)) - A RabbitMQ pattern library.
* <b><code>&nbsp;&nbsp;2214⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;437🍴</code></b> [Enqueue](https://github.com/php-enqueue/enqueue-dev)) - A message queue packages for PHP that supports RabbitMQ, AMQP, STOMP, Amazon SQS, Redis and Doctrine transports.

### Search
*Libraries and software for indexing and performing search queries on data.*

* <b><code>&nbsp;&nbsp;2272⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;731🍴</code></b> [Elastica](https://github.com/ruflin/Elastica)) - A client library for ElasticSearch.
* <b><code>&nbsp;&nbsp;5340⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;974🍴</code></b> [ElasticSearch PHP](https://github.com/elastic/elasticsearch-php)) - The official client library for 🌎 [ElasticSearch](www.elastic.co/).
* 🌎 [Solarium](www.solarium-project.org/) - A client library for 🌎 [Solr](solr.apache.org/).
* 🌎 [SphinxQL Query Builder](foolcode.github.io/SphinxQL-Query-Builder/) - A query library for the 🌎 [Sphinx](sphinxsearch.com/) and 🌎 [Manticore](manticoresearch.com/) search engines.

### Command Line
*Libraries related to the command line.*

* <b><code>&nbsp;&nbsp;&nbsp;102⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;20🍴</code></b> [Aura.Cli](https://github.com/auraphp/Aura.Cli)) - Provides the equivalent of request ( Context ) and response ( Stdio ) objects for the command line interface, including Getopt support, and an independent Help object for describing commands.
* <b><code>&nbsp;&nbsp;&nbsp;618⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;67🍴</code></b> [Cilex](https://github.com/Cilex/Cilex)) - A micro framework for building command line tools.
* <b><code>&nbsp;&nbsp;1947⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;108🍴</code></b> [CLI Menu](https://github.com/php-school/cli-menu)) - A library for building CLI menus.
* <b><code>&nbsp;&nbsp;&nbsp;435⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;51🍴</code></b> [CLIFramework](https://github.com/c9s/CLIFramework)) - A command-line framework supports zsh/bash completion generation, subcommands and option constraints. It also powers phpbrew.
* <b><code>&nbsp;&nbsp;1883⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;124🍴</code></b> [CLImate](https://github.com/thephpleague/climate)) - A library for outputting colors and special formatting.
* <b><code>&nbsp;&nbsp;&nbsp;803⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;83🍴</code></b> [Commando](https://github.com/nategood/commando)) - Another simple command line opt parser.
* <b><code>&nbsp;&nbsp;4869⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;332🍴</code></b> [Cron Expression](https://github.com/mtdowling/cron-expression)) - A library to calculate cron run dates.
* <b><code>&nbsp;&nbsp;&nbsp;342⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;63🍴</code></b> [GetOpt](https://github.com/getopt-php/getopt-php)) - A command line opt parser.
* <b><code>&nbsp;&nbsp;&nbsp;149⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;24🍴</code></b> [GetOptionKit](https://github.com/c9s/GetOptionKit)) - Another command line opt parser.
* <b><code>&nbsp;&nbsp;9829⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;316🍴</code></b> [PsySH](https://github.com/bobthecow/psysh)) - Another PHP REPL.
* <b><code>&nbsp;&nbsp;&nbsp;738⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;54🍴</code></b> [ShellWrap](https://github.com/MrRio/shellwrap)) - A simple command line wrapper library.

### Authentication and Authorization
*Libraries for implementing user authentication and authorization.*

* <b><code>&nbsp;&nbsp;&nbsp;134⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;28🍴</code></b> [Aura.Auth](https://github.com/auraphp/Aura.Auth)) - Provides authentication functionality and session tracking using various adapters.
* <b><code>&nbsp;&nbsp;&nbsp;563⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;110🍴</code></b> [SocialConnect Auth](https://github.com/socialConnect/auth)) - An open source social sign (OAuth1\OAuth2\OpenID\OpenIDConnect).
* <b><code>&nbsp;&nbsp;7472⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;603🍴</code></b> [Json Web Token](https://github.com/lcobucci/jwt)) - Json Tokens to authenticate and transmit information.
* <b><code>&nbsp;&nbsp;&nbsp;998⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;74🍴</code></b> [OAuth 1.0 Client](https://github.com/thephpleague/oauth1-client)) - An OAuth 1.0 client library.
* <b><code>&nbsp;&nbsp;3782⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;766🍴</code></b> [OAuth 2.0 Client](https://github.com/thephpleague/oauth2-client)) - An OAuth 2.0 client library.
* 🌎 [OAuth2 Server](bshaffer.github.io/oauth2-server-php-docs/) - Another OAuth2 server implementation.
* 🌎 [OAuth2 Server](oauth2.thephpleague.com/) - An OAuth2 authentication server, resource server and client library.
* <b><code>&nbsp;&nbsp;1638⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;238🍴</code></b> [Opauth](https://github.com/opauth/opauth)) - A multi-provider authentication framework.
* <b><code>&nbsp;&nbsp;3369⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;107🍴</code></b> [Paseto](https://github.com/paragonie/paseto)) - Platform-Agnostic Security Tokens.
* <b><code>&nbsp;&nbsp;1080⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;449🍴</code></b> [PHP oAuthLib](https://github.com/daviddesberg/PHPoAuthLib)) - Another OAuth library.
* 🌎 [Sentinel Social](cartalyst.com/manual/sentinel-social/2.0) - A library for social network authentication.
* 🌎 [Sentinel](cartalyst.com/manual/sentinel/2.0) - A framework agnostic authentication & authorisation library.
* <b><code>&nbsp;&nbsp;4307⭐</code></b> <b><code>&nbsp;&nbsp;1696🍴</code></b> [TwitterOAuth](https://github.com/abraham/twitteroauth)) - A Twitter OAuth library.

### Markup and CSS
*Libraries for working with markup and CSS formats.*

* <b><code>&nbsp;&nbsp;1009⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;137🍴</code></b> [Cebe Markdown](https://github.com/cebe/markdown)) - A fast and extensible Markdown parser.
* <b><code>&nbsp;&nbsp;2933⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;206🍴</code></b> [CommonMark PHP](https://github.com/thephpleague/commonmark)) - Highly-extensible Markdown parser which fully supports the 🌎 [CommonMark spec](spec.commonmark.org/).
* <b><code>&nbsp;&nbsp;&nbsp;192⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;52🍴</code></b> [Decoda](https://github.com/milesj/decoda)) - A lightweight markup parser library.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;21⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1🍴</code></b> [Djot](https://github.com/php-collective/djot-php)) - A PHP parser for 🌎 [Djot](djot.net/), a modern light markup language (successor of Markdown).
* <b><code>&nbsp;&nbsp;&nbsp;770⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;81🍴</code></b> [Essence](https://github.com/essence/essence)) - A library for extracting web media.
* <b><code>&nbsp;&nbsp;&nbsp;352⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;59🍴</code></b> [Embera](https://github.com/mpratt/Embera)) - An Oembed consumer library.
* <b><code>&nbsp;&nbsp;1867⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;212🍴</code></b> [HTML to Markdown](https://github.com/thephpleague/html-to-markdown)) - Converts HTML into Markdown.
* <b><code>&nbsp;&nbsp;1765⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;117🍴</code></b> [HTML5 PHP](https://github.com/Masterminds/html5-php)) - An HTML5 parser and serializer library.
* <b><code>&nbsp;15013⭐</code></b> <b><code>&nbsp;&nbsp;1149🍴</code></b> [Parsedown](https://github.com/erusev/parsedown)) - Another Markdown parser.
* <b><code>&nbsp;&nbsp;1820⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;150🍴</code></b> [PHP CSS Parser](https://github.com/MyIntervals/PHP-CSS-Parser)) - A Parser for CSS Files written in PHP.
* <b><code>&nbsp;&nbsp;3461⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;527🍴</code></b> [PHP Markdown](https://github.com/michelf/php-markdown)) - A Markdown parser.
* <b><code>&nbsp;&nbsp;&nbsp;303⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;32🍴</code></b> [Shiki PHP](https://github.com/spatie/shiki-php)) - A <b><code>&nbsp;12948⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;572🍴</code></b> [Shiki](https://github.com/shikijs/shiki)) code highlighting package in PHP.
* <b><code>&nbsp;&nbsp;&nbsp;593⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;133🍴</code></b> [VObject](https://github.com/sabre-io/vobject)) - A library for parsing VCard and iCalendar objects.

### JSON
*Libraries for working with JSON.*

* <b><code>&nbsp;&nbsp;1319⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;59🍴</code></b> [JSON Lint](https://github.com/Seldaek/jsonlint)) - A JSON lint utility.
* <b><code>&nbsp;&nbsp;&nbsp;218⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;29🍴</code></b> [JSONMapper](https://github.com/JsonMapper/JsonMapper)) - A library for mapping JSON to PHP objects.

### Strings
*Libraries for parsing and manipulating strings.*

* <b><code>&nbsp;&nbsp;4734⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;518🍴</code></b> [Agent](https://github.com/jenssegers/agent)) - A PHP desktop/mobile user agent parser, based on Mobiledetect.
* <b><code>&nbsp;&nbsp;&nbsp;252⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;36🍴</code></b> [ANSI to HTML5](https://github.com/sensiolabs/ansi-to-html)) - An ANSI to HTML5 converter library.
* <b><code>&nbsp;&nbsp;&nbsp;285⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;32🍴</code></b> [Color Jizz](https://github.com/mikeemoo/ColorJizz-PHP)) - A library for manipulating and converting colors.
* <b><code>&nbsp;&nbsp;3435⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;507🍴</code></b> [Device Detector](https://github.com/matomo-org/device-detector)) - Another library for parsing user agent strings.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;54⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;13🍴</code></b> [Hyphenation](https://github.com/heiglandreas/Org_Heigl_Hyphenator)) - Text-Hyphenation based on the TeX-hyphenation Algorithm
* <b><code>&nbsp;&nbsp;1374⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;258🍴</code></b> [Jieba-PHP](https://github.com/fukuball/jieba-php)) - A PHP port of Python's jieba. Chinese text segmentation for natural language processing.
* <b><code>&nbsp;10688⭐</code></b> <b><code>&nbsp;&nbsp;2637🍴</code></b> [Mobile-Detect](https://github.com/serbanghita/Mobile-Detect)) - A lightweight PHP class for detecting mobile devices (including tablets).
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;79⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;12🍴</code></b> [Patchwork UTF-8](https://github.com/nicolas-grekas/Patchwork-UTF8)) - A portable library for working with UTF-8 strings.
* <b><code>&nbsp;&nbsp;&nbsp;571⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;42🍴</code></b> [Portable ASCII](https://github.com/voku/portable-ascii)) - A library to convert strings to ASCII.
* <b><code>&nbsp;&nbsp;&nbsp;519⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;91🍴</code></b> [Portable UTF-8](https://github.com/voku/portable-utf8)) - A string manipulation library with UTF-8 safe replacement methods.
* <b><code>&nbsp;&nbsp;2905⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;249🍴</code></b> [Slugify](https://github.com/cocur/slugify)) - A library to convert strings to slugs.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [SQL Formatter](https://github.com/jdorn/sql-formatter/)) - A library for formatting SQL statements.
* <b><code>&nbsp;&nbsp;&nbsp;177⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;24🍴</code></b> [Stringy](https://github.com/voku/Stringy)) - A string manipulation library with multibyte support.
* <b><code>&nbsp;&nbsp;1972⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;490🍴</code></b> [UA Parser](https://github.com/tobie/ua-parser/tree/master/php)) - A library for parsing user agent strings.
* <b><code>&nbsp;&nbsp;&nbsp;100⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1🍴</code></b> [Url highlight](https://github.com/vstelmakh/url-highlight)) - A library for parsing URLs from text and converting them into clickable links.
* <b><code>&nbsp;&nbsp;&nbsp;675⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;77🍴</code></b> [URLify](https://github.com/jbroadway/urlify)) - A PHP port of Django's URLify.js.
* <b><code>&nbsp;12620⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;517🍴</code></b> [UUID](https://github.com/ramsey/uuid)) - A library for generating UUIDs.

### Numbers
*Libraries for working with numbers.*

* <b><code>&nbsp;&nbsp;2119⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;92🍴</code></b> [Brick Math](https://github.com/brick/math)) - A library providing large number support: `BigInteger`, `BigDecimal` and `BigRational`.
* <b><code>&nbsp;&nbsp;&nbsp;167⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;17🍴</code></b> [ByteUnits](https://github.com/gabrielelana/byte-units)) - A library to parse, format and convert byte units in binary and metric systems.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;25⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4🍴</code></b> [DecimalObject](https://github.com/php-collective/decimal-object)) - A value object to handle decimals/floats easily and more precisely.
* <b><code>&nbsp;&nbsp;&nbsp;258⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;20🍴</code></b> [IP](https://github.com/darsyn/ip)) - An immutable value object for working with IPv4 and IPv6 addresses.
* <b><code>&nbsp;&nbsp;4997⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;483🍴</code></b> [LibPhoneNumber for PHP](https://github.com/giggsey/libphonenumber-for-php)) - A PHP implementation of Google's phone number handling library.
* <b><code>&nbsp;&nbsp;&nbsp;132⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;19🍴</code></b> [PHP Conversion](https://github.com/Crisu83/php-conversion)) - Another library for converting between units of measure.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;22⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5🍴</code></b> [PHP Units of Measure](https://github.com/triplepoint/php-units-of-measure)) - A library for converting between units of measure.
* <b><code>&nbsp;&nbsp;2397⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;242🍴</code></b> [MathPHP](https://github.com/markrogoyski/math-php)) - A math library for PHP.

### Filtering, Sanitizing and Validation
*Libraries for filtering, sanitizing and validating data.*

* <b><code>&nbsp;&nbsp;2432⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;188🍴</code></b> [Assert](https://github.com/beberlei/assert)) - A validation library with a rich set of assertions. Supports assertion chaining and lazy assertions.
* <b><code>&nbsp;&nbsp;&nbsp;158⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;33🍴</code></b> [Aura.Filter](https://github.com/auraphp/Aura.Filter)) - Provides tools to validate and sanitize objects and arrays.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;42⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8🍴</code></b> [CakePHP Validation](https://github.com/cakephp/validation)) - Another validation library.
* <b><code>&nbsp;&nbsp;&nbsp;448⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;52🍴</code></b> [Filterus](https://github.com/ircmaxell/filterus)) - A simple PHP filtering library.
* <b><code>&nbsp;&nbsp;3391⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;355🍴</code></b> [HTML Purifier](https://github.com/ezyang/htmlpurifier)) - A standards compliant HTML filter.
* <b><code>&nbsp;&nbsp;&nbsp;802⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;81🍴</code></b> [ISO-codes](https://github.com/ronanguilloux/IsoCodes)) - A library for validating inputs according to standards from ISO, International Finance, Public Administrations, GS1, Book Industry, Phone numbers & Zipcodes for many countries.
* <b><code>&nbsp;&nbsp;3627⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;367🍴</code></b> [JSON Schema](https://github.com/jsonrainbow/json-schema)) - A 🌎 [JSON Schema](json-schema.org/) validation library.
* <b><code>&nbsp;&nbsp;&nbsp;103⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;21🍴</code></b> [MetaYaml](https://github.com/romaricdrigon/MetaYaml)) - A schema validation library that supports YAML, JSON and XML.
* <b><code>&nbsp;&nbsp;5929⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;775🍴</code></b> [Respect Validation](https://github.com/Respect/Validation)) - A simple validation library.
* <b><code>&nbsp;&nbsp;&nbsp;278⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;11🍴</code></b> [Symfony HTML Sanitizer](https://github.com/symfony/html-sanitizer)) - An HTML sanitizer library.
* <b><code>&nbsp;&nbsp;1657⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;314🍴</code></b> [Upload](https://github.com/brandonsavage/Upload)) - A library for handling file uploads and validation.
* <b><code>&nbsp;&nbsp;1602⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;253🍴</code></b> [Valitron](https://github.com/vlucas/valitron)) - Another validation library.
* <b><code>&nbsp;&nbsp;1480⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;86🍴</code></b> [Valinor](https://github.com/CuyZ/Valinor)) - A library for mapping to strongly typed value objects.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;45⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;10🍴</code></b> [Volan](https://github.com/serkin/Volan)) - Another simplified validation library.

### API
*Libraries and web tools for developing APIs.*

* 🌎 [API Platform](api-platform.com ) - Expose in minutes a hypermedia REST API that embraces JSON-LD, Hydra format.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;53⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;72🍴</code></b> [Laminas API Tool Skeleton](https://github.com/laminas-api-tools/api-tools-skeleton)) - An API builder built with the Laminas Framework.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;87⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;12🍴</code></b> [Drest](https://github.com/leedavis81/drest)) - A library for exposing Doctrine entities as REST resource endpoints.
* <b><code>&nbsp;&nbsp;&nbsp;201⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;43🍴</code></b> [HAL](https://github.com/blongden/hal)) - A Hypertext Application Language (HAL) builder library.
* <b><code>&nbsp;&nbsp;1045⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;121🍴</code></b> [Hateoas](https://github.com/willdurand/Hateoas)) - A HATEOAS REST web service library.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Jane](https://github.com/janephp/janephp/)) - An OpenApi client generator with validation support.
* <b><code>&nbsp;&nbsp;1423⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;64🍴</code></b> [Negotiation](https://github.com/willdurand/Negotiation)) - A content negotiation library.
* <b><code>&nbsp;&nbsp;1369⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;311🍴</code></b> [Restler](https://github.com/Luracast/Restler)) - A lightweight framework to expose PHP methods as RESTful web API.
* <b><code>&nbsp;&nbsp;&nbsp;434⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;74🍴</code></b> [PackageGenerator](https://github.com/WsdlToPhp/PackageGenerator)) - Package Generator generates a PHP SDK from any WSDL.

### Caching and Locking
*Libraries for caching data and acquiring locks.*

* <b><code>&nbsp;&nbsp;&nbsp;115⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;24🍴</code></b> [APIx Cache](https://github.com/apix/cache)) - A thin PSR-6 cache wrapper to various caching backends emphasizing cache tagging and indexing.
* <b><code>&nbsp;&nbsp;1796⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;156🍴</code></b> [CacheTool](https://github.com/gordalina/cachetool)) - A tool to clear APC/opcode caches from the command line.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;49⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7🍴</code></b> [CakePHP Cache](https://github.com/cakephp/cache)) - A caching library.
* <b><code>&nbsp;&nbsp;7884⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;211🍴</code></b> [Doctrine Cache](https://github.com/doctrine/cache)) - A caching library.
* <b><code>&nbsp;&nbsp;&nbsp;100⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9🍴</code></b> [Metaphore](https://github.com/sobstel/metaphore)) - Cache slam defense using a semaphore to prevent dogpile effect.
* <b><code>&nbsp;&nbsp;&nbsp;962⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;131🍴</code></b> [Stash](https://github.com/tedious/Stash)) - Another library for caching.
* <b><code>&nbsp;&nbsp;&nbsp;106⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;58🍴</code></b> [Laminas Cache](https://github.com/laminas/laminas-cache)) - Another caching library.
* <b><code>&nbsp;&nbsp;&nbsp;946⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;91🍴</code></b> [Lock](https://github.com/php-lock/lock)) - A lock library to provide exclusive execution.

### Data Structure and Storage
*Libraries that implement data structure or storage techniques.*

* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;89⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5🍴</code></b> [CakePHP Collection](https://github.com/cakephp/collection)) - A simple collections library.
* <b><code>&nbsp;&nbsp;3547⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;347🍴</code></b> [Fractal](https://github.com/thephpleague/fractal)) - A library for converting complex data structures to JSON output.
* <b><code>&nbsp;&nbsp;&nbsp;192⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;19🍴</code></b> [Ginq](https://github.com/akanehara/ginq)) - Another PHP library based on .NET's LINQ.
* <b><code>&nbsp;&nbsp;1570⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;184🍴</code></b> [JsonMapper](https://github.com/cweiske/jsonmapper)) - A library that maps nested JSON structures onto PHP classes.
* <b><code>&nbsp;&nbsp;1290⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;74🍴</code></b> [JSON Machine](https://github.com/halaxa/json-machine)) - Provides iteration over huge JSONs using simple `foreach`
* <b><code>&nbsp;&nbsp;&nbsp;535⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;60🍴</code></b> [Knapsack](https://github.com/DusanKasan/Knapsack)) - Collection library inspired by Clojure's sequences.
* <b><code>&nbsp;&nbsp;&nbsp;407⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;20🍴</code></b> [msgpack.php](https://github.com/rybakit/msgpack.php)) - A pure PHP implementation of the 🌎 [MessagePack](msgpack.org/) serialization format.
* <b><code>&nbsp;&nbsp;&nbsp;462⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;20🍴</code></b> [PINQ](https://github.com/TimeToogo/Pinq)) - A PHP library based on .NET's LINQ (Language Integrated Query).
* <b><code>&nbsp;&nbsp;2345⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;585🍴</code></b> [Serializer](https://github.com/schmittjoh/serializer)) - A library for serializing and de-serializing data.
* <b><code>&nbsp;&nbsp;&nbsp;451⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;40🍴</code></b> [YaLinqo](https://github.com/Athari/YaLinqo)) - Yet Another LINQ to Objects for PHP.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;34⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;20🍴</code></b> [Laminas Serializer](https://github.com/laminas/laminas-serializer)) - Another library for serialising and de-serialising data.

### Notifications
*Libraries for working with notification software.*

* <b><code>&nbsp;&nbsp;1437⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;99🍴</code></b> [JoliNotif](https://github.com/jolicode/JoliNotif)) - A cross-platform library for desktop notification (support for Growl, notify-send, toaster, etc)
* <b><code>&nbsp;&nbsp;1182⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;268🍴</code></b> [Notification Pusher](https://github.com/Ph3nol/NotificationPusher)) - A standalone library for device push notifications.
* <b><code>&nbsp;&nbsp;&nbsp;225⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;44🍴</code></b> [Notificato](https://github.com/mac-cain13/notificato)) - A library for handling push notifications.
* <b><code>&nbsp;&nbsp;&nbsp;192⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;26🍴</code></b> [Notificator](https://github.com/namshi/notificator)) - A lightweight notification library.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;67⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;37🍴</code></b> [Php-pushwoosh](https://github.com/gomoob/php-pushwoosh)) - A PHP Library to easily send push notifications with the Pushwoosh REST Web Services.

### Deployment
*Libraries for project deployment.*

* <b><code>&nbsp;11003⭐</code></b> <b><code>&nbsp;&nbsp;1522🍴</code></b> [Deployer](https://github.com/deployphp/deployer)) - A deployment tool.
* <b><code>&nbsp;&nbsp;1610⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;177🍴</code></b> [Envoy](https://github.com/laravel/envoy)) - A tool to run SSH tasks with PHP.
* <b><code>&nbsp;&nbsp;2641⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;217🍴</code></b> [Rocketeer](https://github.com/rocketeers/rocketeer)) - A fast and easy deployer for the PHP world.

### Internationalisation and Localisation
*Libraries for Internationalization (I18n) and Localization (L10n).*

* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;89⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;22🍴</code></b> [Aura.Intl](https://github.com/auraphp/Aura.Intl)) - Provides internationalization (I18N) tools, specifically package-oriented per-locale message translation.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;28⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4🍴</code></b> [CakePHP I18n](https://github.com/cakephp/i18n)) - Message translation and localization for dates and numbers.

### Serverless
*Libraries and tools to help build serverless web applications.*

* 🌎 [Bref](bref.sh/) - Serverless PHP on AWS Lambda.
* 🌎 [OpenWhisk](openwhisk.apache.org/) - An open-source serverless cloud platform.
* 🌎 [Serverless Framework](www.serverless.com/framework) - An open-source framework for building serverless applications.
* 🌎 [Laravel Vapor](vapor.laravel.com/) - A serverless deployment platform for Laravel, powered by AWS.

## Configuration
*Libraries and tools for configuration.*

* <b><code>&nbsp;13513⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;655🍴</code></b> [PHP Dotenv](https://github.com/vlucas/phpdotenv)) - Parse and load environment variables from `.env` files.
* <b><code>&nbsp;&nbsp;3799⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;30🍴</code></b> [Symfony Dotenv](https://github.com/symfony/dotenv))- Parse and load environment variables from `.env` files.
* <b><code>&nbsp;&nbsp;&nbsp;208⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;31🍴</code></b> [Yo! Symfony TOML](https://github.com/yosymfony/toml)) - A PHP parser for <b><code>&nbsp;20377⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;888🍴</code></b> [TOML](https://github.com/toml-lang/toml)).

### LLMs
*Libraries for working with Large Language Models.*

* <b><code>&nbsp;&nbsp;&nbsp;307⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;23🍴</code></b> [Instructor for PHP](https://github.com/cognesy/instructor-php)) - Structured data outputs with LLMs, in PHP.
* <b><code>&nbsp;&nbsp;1426⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;148🍴</code></b> [LLPhant](https://github.com/LLPhant/LLPhant)) - A comprehensive PHP Generative AI Framework using OpenAI GPT 4. Inspired by Langchain.
* <b><code>&nbsp;&nbsp;5719⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;672🍴</code></b> [OpenAI Client](https://github.com/openai-php/client)) - OpenAI PHP is a supercharged community-maintained PHP API client that allows you to interact with OpenAI API.
* <b><code>&nbsp;&nbsp;3707⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;256🍴</code></b> [OpenAI Client for Laravel](https://github.com/openai-php/laravel)) - OpenAI PHP for Laravel is a supercharged PHP API client that allows you to interact with OpenAI API.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;15⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3🍴</code></b> [PHP Mistral AI SDK](https://github.com/SoftCreatR/php-mistral-ai-sdk)) - A powerful and easy-to-use PHP SDK for the Mistral AI API, allowing seamless integration of advanced AI-powered features into your PHP projects.

### Third Party APIs
*Libraries for accessing third party APIs.*

* <b><code>&nbsp;&nbsp;6180⭐</code></b> <b><code>&nbsp;&nbsp;1236🍴</code></b> [Amazon Web Service SDK](https://github.com/aws/aws-sdk-php)) - The official PHP AWS SDK library.
* 🌎 [AsyncAWS](async-aws.com/) - An unofficial asynchronous PHP AWS SDK.
* 🌎 [Campaign Monitor](campaignmonitor.github.io/createsend-php/) - The official Campaign Monitor PHP library.
* <b><code>&nbsp;&nbsp;2197⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;593🍴</code></b> [Github](https://github.com/KnpLabs/php-github-api)) - A library to interface with the Github API.
* <b><code>&nbsp;&nbsp;1133⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;317🍴</code></b> [Mailgun](https://github.com/mailgun/mailgun-php)) The official Mailgun PHP API.
* <b><code>&nbsp;&nbsp;&nbsp;116⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;51🍴</code></b> [Square](https://github.com/square/connect-php-sdk)) - The official Square PHP SDK for payments and other Square APIs.
* <b><code>&nbsp;&nbsp;3980⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;891🍴</code></b> [Stripe](https://github.com/stripe/stripe-php)) - The official Stripe PHP library.
* <b><code>&nbsp;&nbsp;1633⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;581🍴</code></b> [Twilio](https://github.com/twilio/twilio-php)) - The official Twilio PHP REST API.

### Extensions
*Libraries to help build PHP extensions.*

* 🌎 [PHP CPP](www.php-cpp.com/) - A C++ library for developing PHP extensions.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Zephir](https://github.com/zephir-lang/zephir )) - A compiled language between PHP and C++ for developing PHP extensions.

### Miscellaneous
*Useful libraries or utilities that don't fit into the categories above.*

* <b><code>&nbsp;&nbsp;6744⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;230🍴</code></b> [Annotations](https://github.com/doctrine/annotations)) - An annotation library (part of Doctrine).
* <b><code>&nbsp;&nbsp;6168⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;820🍴</code></b> [BotMan](https://github.com/botman/botman)) - A framework agnostic PHP library to build cross-platform chatbots.
* <b><code>&nbsp;&nbsp;&nbsp;376⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;30🍴</code></b> [ClassPreloader](https://github.com/ClassPreloader/ClassPreloader)) - A library for optimizing autoloading.
* <b><code>&nbsp;&nbsp;&nbsp;660⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;46🍴</code></b> [Ganesha](https://github.com/ackintosh/ganesha)) - A PHP implementation of Circuit Breaker pattern.
* <b><code>&nbsp;&nbsp;2068⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;385🍴</code></b> [Hprose-PHP](https://github.com/hprose/hprose-php)) - A cross-language RPC.
* <b><code>&nbsp;&nbsp;&nbsp;598⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;42🍴</code></b> [Laravel Serializable Closure](https://github.com/laravel/serializable-closure)) - A library that allows Closures to be serialized.
* <b><code>&nbsp;&nbsp;&nbsp;366⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;57🍴</code></b> [noCAPTCHA](https://github.com/ARCANEDEV/noCAPTCHA)) - Helper for Google's noCAPTCHA (reCAPTCHA).
* <b><code>&nbsp;&nbsp;1580⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2🍴</code></b> [Pagerfanta](https://github.com/whiteoctober/Pagerfanta)) - A pagination library.
* <b><code>&nbsp;&nbsp;2479⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;166🍴</code></b> [Safe](https://github.com/thecodingmachine/safe)) - All PHP functions, rewritten to throw exceptions instead of returning false.

# Software
*Software for creating a development environment.*

### PHP Installation
*Tools to help install and manage PHP on your computer.*

* <b><code>&nbsp;&nbsp;1005⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;92🍴</code></b> [Brew PHP Switcher](https://github.com/philcook/brew-php-switcher)) - Brew PHP switcher.
* 🌎 [HomeBrew](brew.sh/) - A package manager for OSX.
* <b><code>&nbsp;&nbsp;5524⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;369🍴</code></b> [PHP Brew](https://github.com/phpbrew/phpbrew)) - A PHP version manager and installer.
* <b><code>&nbsp;&nbsp;1043⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;159🍴</code></b> [PHP Build](https://github.com/php-build/php-build)) - Another PHP version installer.
* <b><code>&nbsp;&nbsp;1827⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;358🍴</code></b> [Static PHP CLI](https://github.com/crazywhalecc/static-php-cli)) - Build or 🌎 [download](dl.static-php.dev/static-php-cli/) static versions of PHP CLI and FPM.

### Development Environment
*Software and tools for creating and sharing a development environment.*

* 🌎 [Ansible](www.redhat.com/en/ansible-collaborative) - A radically simple orchestration framework.
* <b><code>&nbsp;&nbsp;3502⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;693🍴</code></b> [DDEV](https://github.com/ddev/ddev)) - a local web development environment system for PHP.
* 🌎 [Docker](www.docker.com/) - A containerization platform.
* <b><code>&nbsp;&nbsp;4865⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;426🍴</code></b> [Docker PHP Extension Installer](https://github.com/mlocati/docker-php-extension-installer)) - Easily install PHP extensions in Docker containers.
* <b><code>&nbsp;&nbsp;&nbsp;715⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;177🍴</code></b> [Docksal](https://github.com/docksal/docksal)) - Unified, Docker :whale: powered web development environments for macOS, Windows, and Linux.
* <b><code>&nbsp;&nbsp;4523⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;305🍴</code></b> [Expose](https://github.com/exposedev/expose)) - An open-source PHP tunneling service.
* 🌎 [Lando](lando.dev/) - Push-button development environments.
* 🌎 [Laravel Homestead](laravel.com/docs/master/homestead) - A local development environment for Laravel.
* 🌎 [Laravel Herd](herd.laravel.com/windows) - A one click PHP development environment for macOS and Windows.
* [Laradock](http://laradock.io/) - A full PHP development environment based on Docker.
* 🌎 [PHPMon](phpmon.app/) - A macOS menu bar app for managing PHP installations (works with 🌎 [Laravel Valet](laravel.com/docs/master/valet)).
* 🌎 [Puppet](www.puppet.com) - A server automation framework and application.
* <b><code>&nbsp;&nbsp;1648⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;80🍴</code></b> [Takeout](https://github.com/tighten/takeout)) - A Docker-based development-only dependency manager.
* 🌎 [Vagrant](www.vagrantup.com/) - A portable development environment utility.

### Virtual Machines
*Alternative PHP virtual machines.*

* 🌎 [Hack](hacklang.org/) - A programming language for HHVM.
* <b><code>&nbsp;18606⭐</code></b> <b><code>&nbsp;&nbsp;3076🍴</code></b> [HHVM](https://github.com/facebook/hhvm)) - A Virtual Machine, Runtime and JIT for PHP by Facebook.
* <b><code>&nbsp;&nbsp;2469⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;212🍴</code></b> [PeachPie](https://github.com/peachpiecompiler/peachpie)) - PHP compiler and runtime for .NET and .NET Core.

### Text Editors and IDEs
*Text Editors and Integrated Development Environments (IDE) with support for PHP.*

* 🌎 [Eclipse for PHP Developers](www.eclipse.org/downloads/) - A PHP IDE based on the Eclipse platform.
* 🌎 [Apache NetBeans](netbeans.apache.org/front/main/index.html) - An IDE with support for PHP and HTML5.
* 🌎 [PhpEd](www.nusphere.com/products/phped.htm) - An IDE with professional commercial debugger.
* 🌎 [PhpStorm](www.jetbrains.com/phpstorm/) - A commercial PHP IDE.
* 🌎 [VS Code](code.visualstudio.com/) - An open source code editor.

### Web Applications
*Web-based applications and tools.*

* 🌎 [3V4L](3v4l.org/) - An online PHP & HHVM shell.
* 🌎 [Adminer](www.adminer.org/en/) - Database management in a single PHP file.
* <b><code>&nbsp;14932⭐</code></b> <b><code>&nbsp;&nbsp;1606🍴</code></b> [Cachet](https://github.com/cachethq/cachet)) - The open source status page system.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [DBV](https://github.com/victorstanciu/dbv)) - A database version control application.
* <b><code>&nbsp;&nbsp;6372⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;663🍴</code></b> [Lychee](https://github.com/electerious/Lychee)) - An easy to use and great looking photo-management-system.
* <b><code>&nbsp;&nbsp;6727⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;596🍴</code></b> [MailCatcher](https://github.com/sj26/mailcatcher)) - A web tool for capturing and viewing emails.
* <b><code>&nbsp;&nbsp;7798⭐</code></b> <b><code>&nbsp;&nbsp;3554🍴</code></b> [phpMyAdmin](https://github.com/phpmyadmin/phpmyadmin)) - A web interface for MySQL/MariaDB.
* <b><code>&nbsp;&nbsp;&nbsp;665⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;69🍴</code></b> [PHP Queue](https://github.com/CoderKungfu/php-queue)) - An application for managing queueing backends.
* <b><code>&nbsp;&nbsp;3185⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;667🍴</code></b> [phpRedisAdmin](https://github.com/ErikDubbelboer/phpRedisAdmin)) - A simple web interface to manage 🌎 [Redis](redis.io/) databases.
* 🌎 [PHPSandbox](phpsandbox.io) - An online IDE for PHP in the browser.

### Infrastructure
*Infrastructure for providing PHP applications and services.*

* <b><code>&nbsp;&nbsp;&nbsp;962⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;101🍴</code></b> [appserver.io](https://github.com/appserver-io/appserver)) - A multithreaded application server for PHP, written in PHP.
* <b><code>&nbsp;&nbsp;6564⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;372🍴</code></b> [php-pm](https://github.com/php-pm/php-pm)) - A process manager, supercharger and load balancer for PHP applications.
* <b><code>&nbsp;&nbsp;8396⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;421🍴</code></b> [RoadRunner](https://github.com/roadrunner-server/roadrunner)) - High-performance PHP application server, load-balancer and process manager.

# Resources
Various resources, such as books, websites and articles, for improving your PHP development skills and knowledge.

### PHP Websites
*Useful PHP-related websites.*

* 🌎 [Nomad PHP](nomadphp.com/) - A online PHP learning resource.
* 🌎 [Laravel News](laravel-news.com/) - The official Laravel blog.
* 🌎 [PHP Annotated Monthly](blog.jetbrains.com/phpstorm/tag/php-annotated-monthly/) - A monthly digest of PHP news.
* 🌎 [PHP FIG](www.php-fig.org/) - The PHP Framework Interoperability Group.
* [PHP Package Development Standards](http://php-pds.com) - Package development standards for PHP.
* 🌎 [PHP School](www.phpschool.io/) - Open Source Learning for PHP.
* 🌎 [PHP The Right Way](phptherightway.com/) - A PHP best practice quick reference guide.
* 🌎 [PHP UG](php.ug) - A website to help people locate their nearest PHP user group (UG).
* 🌎 [PHP Watch](php.watch/) - PHP articles, news, upcoming changes, RFCs and more.
* 🌎 [Unit Testing Tips](testing-tips.sarvendev.com/) - Unit Testing Tips by examples in PHP.

### PHP Books
*Fantastic PHP-related books.*

* 🌎 [Domain-Driven Design in PHP](leanpub.com/ddd-in-php) - Real examples written in PHP showcasing DDD Architectural Styles.
* 🌎 [Functional Programming in PHP](www.functionalphp.com/) - This book will show you how to leverage these new PHP5.3+ features by understanding functional programming principles
* 🌎 [Grumpy PHPUnit](leanpub.com/grumpy-phpunit) - A book about unit testing with PHPUnit by Chris Hartjes.
* 🌎 [Mastering Object-Orientated PHP](masteringobjectorientedphp.com/) - A book about object-orientated PHP by Brandon Savage.
* 🌎 [PHP Cookbook](www.oreilly.com/library/view/php-cookbook/9781098121310/) - This cookbook provides code recipes to help you resolve a variety of coding issues.
* 🌎 [Modernizing Legacy Applications in PHP](leanpub.com/mlaphp) - A book about modernizing legacy PHP applications by Paul M. Jones.
* 🌎 [Scaling PHP Applications](www.scalingphpbook.com) - An ebook about scaling PHP applications by Steve Corona.
* 🌎 [Securing PHP: Core Concepts](leanpub.com/securingphp-coreconcepts) - A book about common security terms and practices for PHP by Chris Cornutt.
* 🌎 [Signaling PHP](leanpub.com/signalingphp) - A book about catching PCNTL signals in CLI scripts by Cal Evans.
* 🌎 [XML Parsing with PHP](www.phparch.com/books/xml-parsing-with-php/) - This book covers parsing and validating XML documents, leveraging XPath expressions, and working with namespaces as well as how to create and modify XML files programmatically.

### PHP Videos
*Fantastic PHP-related videos.*

* 🌎 [Laracasts](laracasts.com) - Screencasts about Laravel, Vue JS and more.
* 🌎 [Laravel YouTube Channel](www.youtube.com/channel/UCfO2GiQwb-cwJTb1CuRSkwg) - The official Laravel YouTube channel.
* 🌎 [Program With Gio](www.youtube.com/playlist?list=PLr3d3QYzkw2xabQRUpcZ_IBk9W50M9pe-) - PHP 8 course by Gio.
* 🌎 [Programming with Anthony](www.youtube.com/playlist?list=PLM-218uGSX3DQ3KsB5NJnuOqPqc5CW2kW) - A video series by Anthony Ferrara.
* 🌎 [SymfonyCasts](symfonycasts.com/) - Screencasts and tutorials about PHP and Symfony.

### PHP Conferences
*PHP conferences.*

* 🌎 [Laracon EU](www.youtube.com/@LaraconEU) - Laracon EU is a 2-day event for people who are interested in learning Laravel and related technologies, or who want to share their knowledge with others.
* [PHP[TEK]](https://phptek.io/) - The longest-running web developer conference in the United States that has a focus on the PHP programming language.
* 🌎 [PHP UK Conference](www.youtube.com/user/phpukconference/videos) - A collection of videos from the PHP UK Conference.

### PHP Podcasts
*Podcasts with a focus on PHP topics.*

* 🌎 [Laravel News Podcast](podcast.laravel-news.com/) - The Laravel News Podcast brings you all the latest news and events related to the Laravel PHP Framework.
* 🌎 [Mostly Technical](mostlytechnical.com/) - Hosted by Ian Landsman and Aaron Francis, Mostly Technical is a lively discussion on Laravel, business, and an eclectic mix of related topics.
* 🌎 [No Compromises](show.nocompromises.io/) - Two seasoned salty programming veterans talk best practices based on years of working with Laravel SaaS teams.
* 🌎 [North Meets South Web Podcast](www.northmeetssouth.audio/) - Jacob Bennett and Michael Dyrynda conquer a 14.5 hour time difference to talk about life as web developers.
* 🌎 [Over Engineered](overengineered.fm/) - A podcast in mini-series where we explore unimportant programming questions in extreme detail.
* 🌎 [PHP Internals News](phpinternals.news) - A podcast about PHP internals.
* 🌎 [PHP Town Hall](phptownhall.com/) - A casual PHP podcast by Ben Edmunds and Phil Sturgeon.
* [php[podcast] episodes from php[architect]](https://www.phparch.com/podcast/) - The official podcast of php[architect] the industry's leading tech magazine and publisher focused on PHP and web development.
* 🌎 [PHPUgly](www.phpugly.com/) - The ramblings of a few overworked PHP Developers.
* 🌎 [The Laracasts Snippet](laracasts.simplecast.com) - The Laracasts snippet, each episode, offers a single thought on some aspect of web development.
* 🌎 [The Laravel Podcast](laravelpodcast.com/) - Laravel and PHP development news and discussion.
* 🌎 [The PHP Roundtable](phproundtable.com/) - The PHP Roundtable is a casual gathering of developers discussing topics that PHP nerds care about.

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
* <b><code>&nbsp;&nbsp;&nbsp;127⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;15🍴</code></b> [PHP RFC Watch](https://github.com/beberlei/php-rfc-watch)) - Watch the latest PHP 🌎 [RFCs](wiki.php.net/rfc).
* 🌎 [PHP Internals Book](www.phpinternalsbook.com/) - An online book about PHP internals, written by three core developers.

## Source
<b><code>&nbsp;32377⭐</code></b> <b><code>&nbsp;&nbsp;5145🍴</code></b> [ziadoz/awesome-php](https://github.com/ziadoz/awesome-php))