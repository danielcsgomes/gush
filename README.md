## Gush

Gush is a rapid workflow for project maintainers and contributors

[![Build Status](https://travis-ci.org/cordoval/gush.png?branch=master)](https://travis-ci.org/cordoval/gush)
[![Scrutinizer Quality Score](https://scrutinizer-ci.com/g/cordoval/gush/badges/quality-score.png?s=f54effe2042a7eb161b0263322b3b4979d2de900)](https://scrutinizer-ci.com/g/cordoval/gush/)
[![SensioLabsInsight](https://insight.sensiolabs.com/projects/160ad92b-b065-482e-9ebd-4cff2b931451/mini.png)](https://insight.sensiolabs.com/projects/160ad92b-b065-482e-9ebd-4cff2b931451)

### What is this?

Gush is an app console whose intention is to automate common maintainer and contributor tasks.

- create a Pull Request with a formatted table description of the changes
- create github release notes
- change the base branch of a Pull Request
- automate retrieval of issue's message, title and comments as a text
- merge a PR with just the number and include all github discussion on the commit message
- tagging signing off, change branch name and some queue of common tasks

### Usage

There are different ways to use Gush but we recommend this one:

```
$ composer global require 'cordoval/gush=dev-master'
```

If it is the first time you install globally a dependency then make sure
you follow the instructions [here](http://getcomposer.org/doc/03-cli.md#global).