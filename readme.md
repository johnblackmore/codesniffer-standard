# Crowdcube Codesniffer Standard

[![Circle CI](https://circleci.com/gh/Crowdcube/codesniffer-standard.png?style=badge&circle-token=92d9baae489e35d2efb86eb6899f5527a8e6fb1b)](https://circleci.com/gh/Crowdcube/codesniffer-standard)

This is [our](https://www.crowdcube.com) `work-in-progress` [PHP_Codesniffer](http://www.squizlabs.com/php-codesniffer)
standard for validating the PHP code that we write.

It currently does not check/enforce all, but serves as a good first check to the Crowdcube coding standard. The remaining
checks will be picked up in code review.

## Installation

Add the following to your `composer.json` require and update:

```
"crowdcube/codesniffer-standard": "0.3.*"
```

## Checking

When running `./vendor/bin/phpcs` from your project, set the standard as follows:

```
--standard=vendor/crowdcube/codesniffer/Crowdcube
```
