# AWS Bucket PHP

[![Latest Version](https://img.shields.io/github/v/release/kiwfy/aws-bucket-php.svg?style=flat-square)](https://github.com/kiwfy/aws-bucket-php/releases)
[![codecov](https://codecov.io/gh/kiwfy/aws-bucket-php/branch/master/graph/badge.svg)](https://codecov.io/gh/kiwfy/aws-bucket-php)
[![Build Status](https://img.shields.io/github/workflow/status/kiwfy/aws-bucket-php/CI?label=ci%20build&style=flat-square)](https://github.com/kiwfy/aws-bucket-php/actions?query=workflow%3ACI)
[![Total Downloads](https://img.shields.io/packagist/dt/kiwfy/aws-bucket-php.svg?style=flat-square)](https://packagist.org/packages/kiwfy/aws-bucket-php)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)

PHP library to connect to and use AWS S3 Bucket.

### Installation

Requires [PHP](https://php.net) 7.1.

The recommended way to install is through [Composer](https://getcomposer.org/).

```sh
composer require kiwfy/aws-bucket-php
```

### Sample

it's a good idea to look in the sample folder to understand how it works.

First verify if all dependencies is installed (if need anyelse)
```sh
composer install --no-dev --prefer-dist
```

and run
```sh
php sample/AwsBucketSample.php
```

### Development

Want to contribute? Great!

The project using a simple code.
Make a change in your file and be careful with your updates!
**Any new code will only be accepted with all viladations.**

To ensure that the entire project is fine:

First install all the dev dependences
```sh
composer install --dev --prefer-dist
```

Second run all validations
```sh
composer check
```

**Kiwfy - Open your code, open your mind!**
