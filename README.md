# webgriffe/psalm-dist

Psalm phar distribution for Webgriffe projects.

Provides the `psalm` binary via Composer without pulling in Psalm's full dependency tree.

## Installation

```bash
composer require --dev webgriffe/psalm-dist
```

## Usage

```bash
vendor/bin/psalm
```

## Versioning

Versions mirror [Psalm upstream releases](https://github.com/vimeo/psalm/releases).

## How it works

This package is automatically updated by [webgriffe/php-tools-dist](https://github.com/webgriffe/php-tools-dist).
When a new Psalm release is published, the phar is downloaded and a new tagged version is pushed here within 24 hours.
