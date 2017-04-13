---
title: Bolt Internals
---
## [routing](routing)
## [templating](templating)
## [the-model](the-model)
## [bolt-storage-internals](bolt-storage-internals)
## [bootstrapping](bootstrapping)
## [debug-bar](debug-bar)
## [dump-twig-tag](dump-twig-tag)
## [backtrace-twig-tag](backtrace-twig-tag)
## [container-service-references](container-service-references)
## [task-scheduler](task-scheduler)
## [javascript_css_build](javascript_css_build)

LegionMarket Internals
==============

LegionMarket is an application built on top of the awesome [Silex micro-framework][silex],
and uses a lot of components from the [Symfony framework][comp]. Bolt strives to
adhere to [the PSR-2 coding style][psr2]. When writing your own
[Bolt extensions][ext], you should try to do the same.

This chapter serves as a reference guide for those who want to get the most out
of the templates, those who want to create extensions or basically anybody who's
curious what makes Bolt tick.

[silex]: http://silex.sensiolabs.org
[comp]: http://symfony.com/components
[psr2]: https://github.com/php-fig/fig-standards/blob/master/accepted/PSR-2-coding-style-guide.md
[ext]: extensions/introduction
