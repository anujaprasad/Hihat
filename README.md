# Cachet

[![StyleCI](https://styleci.io/repos/26730195/shield)](https://styleci.io/repos/26730195/)
[![Build Status](https://img.shields.io/travis/cachethq/Cachet.svg?style=flat-square)](https://travis-ci.org/cachethq/Cachet)
[![Quality Score](https://img.shields.io/scrutinizer/g/cachethq/Cachet.svg?style=flat-square)](https://scrutinizer-ci.com/g/cachethq/Cachet)
[![Software License](https://img.shields.io/badge/license-BSD3-brightgreen.svg?style=flat-square)](LICENSE)
[![Crowdin](https://d322cqt584bo4o.cloudfront.net/cachet/localized.png)](http://translate.cachethq.io/project/cachet)

![Screenshot](https://cachethq.io/img/main-interface.jpg)

## Features

- List your services components
- Log incidents
- Apply custom CSS to the status page
- Markdown support for incident messages
- JSON API
- Translated into eleven languages
- Metrics
- Cross-database support: MySQL, PostgreSQL and SQLite
- Subscriber notifications via Email
- Two factor authentication, with Google Authenticator

## Requirements

- PHP 5.5.9+ or newer
- [Composer](https://getcomposer.org)

### Development Requirements

Theses extra dependencies are required to develop Cachet:

- Node.js
- Bower
- Gulp

## Installation, Upgrades and Documentation

You can now find our documentation at [https://docs.cachethq.io](https://docs.cachethq.io).

### Demo Account

To test out the demo, you may login to the [Dashboard](https://demo.cachethq.io/dashboard) with the following:

- **Username:** test@test.com
- **Password:** test123

The demo is reset every half hour.

## What Cachet is not

Here is a list of things that Cachet is not or does not do:

1. It does not monitor your services. It works only as a way to display the status of your services. *However, Cachet is able to receive updates from third-party services via its API.*
2. It does not work on a plugin system. There are no monitoring services to extend.
3. It's not a Twitter clone.

## Installation Support

We've moved our installation guides for Apache, Nginx, Docker and Vagrant to our documentation page.

- [Installing Cachet](https://docs.cachethq.io/docs/installing-cachet)
- [Getting started with Docker](https://docs.cachethq.io/docs/get-started-with-docker)
- [Getting started with Vagrant](https://docs.cachethq.io/docs/get-started-with-vagrant)

## Translations

A special thank you to our [translators](https://crowdin.com/project/cachet/activity_stream), who have allowed us to share Cachet with the world. If you'd like to contribute translations, please check out our [CrowdIn project](https://crowdin.com/project/cachet).
