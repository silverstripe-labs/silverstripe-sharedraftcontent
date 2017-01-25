# Share Draft Content

[![Build Status](http://img.shields.io/travis/silverstripe/silverstripe-sharedraftcontent.svg?style=flat-square)](https://travis-ci.org/silverstripe/silverstripe-sharedraftcontent)
[![Code Quality](http://img.shields.io/scrutinizer/g/silverstripe/silverstripe-sharedraftcontent.svg?style=flat-square)](https://scrutinizer-ci.com/g/silverstripe/silverstripe-sharedraftcontent)
[![Code Coverage](http://img.shields.io/scrutinizer/coverage/g/silverstripe/silverstripe-sharedraftcontent.svg?style=flat-square)](https://scrutinizer-ci.com/g/silverstripe/silverstripe-sharedraftcontent)
[![Version](http://img.shields.io/packagist/v/silverstripe/sharedraftcontent.svg?style=flat-square)](https://packagist.org/packages/silverstripe/silverstripe-sharedraftcontent)
[![License](http://img.shields.io/packagist/l/silverstripe/sharedraftcontent.svg?style=flat-square)](LICENSE.md)
![helpfulrobot](https://helpfulrobot.io/silverstripe/sharedraftcontent/badge)

Share draft page content with non-CMS users.

## Overview

This module adds a 'Share draft' action menu to the CMS. This enables Content Authors to generate tokenised links to draft pages. Content authors can share these links with anyone, allowing non-CMS user to view draft page content. Each preview link is valid for 30 days.

## Requirements

- SilverStripe ^4.0

## Installation

```
$ composer require silverstripe/sharedraftcontent
```

You'll also need to run `dev/build`.

## Documentation

See the [docs/en](docs/en/introduction.md) folder.

## Versioning

This library follows [Semver](http://semver.org). According to Semver, you will be able to upgrade to any minor or patch version of this library without any breaking changes to the public API. Semver also requires that we clearly define the public API for this library.

All methods, with `public` visibility, are part of the public API. All other methods are not part of the public API. Where possible, we'll try to keep `protected` methods backwards-compatible in minor/patch versions, but if you're overriding methods then please test your work before upgrading.

## Reporting Issues

Please [create an issue](http://github.com/silverstripe/silverstripe-sharedraftcontent/issues) for any bugs you've found, or features you're missing.
