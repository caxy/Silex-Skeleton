Caxy Silex Skeleton
===================

Welcome to Caxy's Silex Skeleton - a fully-functional Silex application that
you can use as the skeleton for your new applications. We use this as a
platform for learning and experimentation.

This document contains information on how to start using the Silex Skeleton.

Creating a Silex Application
----------------------------

Silex uses [Composer][] to ease the creation of a new project:

```bash
composer create-project caxy/silex-skeleton path/to/install
```

Composer will create a new Silex project under the path/to/install directory.

Browsing the Demo Application
-----------------------------

Congratulations! You're now ready to use Silex.

To see a real-live Silex page in action, start the PHP built-in web server with
command:

```bash
cd path/to/install
COMPOSER_PROCESS_TIMEOUT=0 composer run
```

Then, browse to <http://localhost:8888/>.

Getting started with Silex
--------------------------

This distribution is meant to be the starting point for your Silex applications.

A great way to start learning Silex is via the [Documentation][], which will
take you through all the features of Silex.

What's inside?
--------------

The Silex Skeleton is configured with the following service providers:

* [UrlGeneratorServiceProvider][] - Provides a service for generating URLs for
  named routes.
* [ServiceControllerServiceProvider][] - As your Silex application grows, you
  may wish to begin organizing your controllers in a more formal fashion.
  Silex can use controller classes out of the box, but with a bit of work,
  your controllers can be created as services, giving you the full power of
  dependency injection and lazy loading.
* [TwigServiceProvider][] - Provides integration with the Twig template engine.
* [WebProfilerServiceProvider][] - Enable the Symfony web debug toolbar and
  the Symfony profiler in your Silex application when developing.
* [MonologServiceProvider][] - Enable logging in the development environment.

Read the [Providers][] documentation for more details about Silex Service
Providers.

Enjoy!

[Composer]: http://getcomposer.org/
[Documentation]: http://silex.sensiolabs.org/documentation
[UrlGeneratorServiceProvider]: http://silex.sensiolabs.org/doc/providers/url_generator.html
[ServiceControllerServiceProvider]: http://silex.sensiolabs.org/doc/providers/service_controller.html
[TwigServiceProvider]: http://silex.sensiolabs.org/doc/providers/twig.html
[WebProfilerServiceProvider]: http://github.com/silexphp/Silex-WebProfiler
[MonologServiceProvider]: http://silex.sensiolabs.org/doc/providers/monolog.html
[Providers]: http://silex.sensiolabs.org/doc/providers.html
