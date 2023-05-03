# Laravel Vue i18n Generator

[![Latest Stable Version](https://poser.pugx.org/testmonitor/laravel-vue-i18n-generator/v/stable)](https://packagist.org/packages/testmonitor/laravel-vue-i18n-generator)
[![CircleCI](https://img.shields.io/circleci/project/github/testmonitor/laravel-vue-i18n-generator.svg)](https://circleci.com/gh/testmonitor/laravel-vue-i18n-generator)
[![StyleCI](https://styleci.io/repos/634942834/shield)](https://styleci.io/repos/634942834)
[![License](https://poser.pugx.org/testmonitor/laravel-vue-i18n-generator/license)](https://packagist.org/packages/testmonitor/laravel-vue-i18n-generator)

This package compiles your Laravel translation files into a [Vue i18n](https://kazupon.github.io/vue-i18n/) compatible JSON file.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Examples](#examples)
- [Changelog](#changelog)
- [Contributing](#contributing)
- [Credits](#credits)
- [License](#license)

## Installation

To install the client you need to require the package using composer:

	$ composer require testmonitor/laravel-vue-i18n-generator

Optionally publish the package assets:

    $ php artisan vendor:publish --provider="TestMonitor\VueI18nGenerator\VueI18nGeneratorServiceProvider" --tag="config"

You're all set up now!

## Usage

When installed, use the Artisan command to generate a Vue i18n file:

    $ php artisan vue:translations

By default, this combine your json and PHP language files into a single Javascript file called `vue-i18n-locales.js`
located in `/resources/js/i18n`.

You can configure the language path and output file in the configuration file.

## Changelog

Refer to [CHANGELOG](CHANGELOG.md) for more information.

## Contributing

Refer to [CONTRIBUTING](CONTRIBUTING.md) for contributing details.

## Credits

* **Thijs Kok** - *Lead developer* - [ThijsKok](https://github.com/thijskok)
* **Stephan Grootveld** - *Developer* - [Stefanius](https://github.com/stefanius)
* **Frank Keulen** - *Developer* - [FrankIsGek](https://github.com/frankisgek)

## License

The MIT License (MIT). Refer to the [License](LICENSE.md) for more information.