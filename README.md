<!-- vim: set tw=79 sw=4 ts=4 et ft=markdown : -->
# PPI Framework

[@website]:       http://www.ppi.io/                              "PPI Framework"
[@documentation]: http://docs.ppi.io                              "PPI Framework Documentation"
[@download]:      http://www.ppi.io/files/ppi-skeletonapp-without-vendors.tar.gz
[@gitweb]:        https://github.com/ppi/framework                "ppi/framework"
[@php]:           http://php.net/                                 "PHP: Hypertext Preprocessor"
[@twitter]:       https://twitter.com/ppi_framework               "PPI Framework at Twitter"

[![Gitter](https://badges.gitter.im/ppi/framework.svg)](https://gitter.im/ppi/framework?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge)
[![Latest Stable Version](https://poser.pugx.org/ppi/framework/v/stable.png)](https://packagist.org/packages/ppi/framework)
[![Latest Unstable Version](https://poser.pugx.org/ppi/framework/v/unstable.png)](https://packagist.org/packages/ppi/framework)
[![Travis-CI Build Status](https://secure.travis-ci.org/ppi/framework.png?branch=master)](http://travis-ci.org/ppi/framework)
[![Scrutinizer Code Quality](https://scrutinizer-ci.com/g/ppi/framework/badges/quality-score.png?b=master)](https://scrutinizer-ci.com/g/ppi/framework/?branch=master)
[![License](https://poser.pugx.org/ppi/framework/license.png)](https://packagist.org/packages/ppi/framework)

[PPI][@website] is the PHP Interoperability Framework. It provides an equal and open platform to empower PHP developers to pick the best tools from the best PHP frameworks

PPI bootstraps framework components for you from the top frameworks such as ZendFramework2, Symfony2, Laravel4 and FuelPHP.

* [Official website][@website]
* [Download][@download]
* [Documentation][@documentation]

## Requirements

* [PHP][@php] 5.4.0 or above

## Installation

There is no actual "installation" of PPI, you can download it from
http://www.ppi.io/downloads and drop it in your document root.

## Contributing

PPI is an open source, community-driven project. If you'd like to contribute, check out our issues list. You can find us
on IRC, Google Plus or Twitter ([@ppi_framework][@twitter]).

If you're submitting a pull request, please do so on your own branch on [GitHub][@gitweb].
 
Start by forking the PPI Framework repository and cloning your fork locally:

    $ git clone git@github.com:YOUR_USERNAME/framework.git
    $ git remote add upstream git://github.com/ppi/framework.git
    $ git checkout -b feature/BRANCH_NAME master
    
Apply PPI Coding Standards using the PHP-CS-Fixer tool (uses PPI custom fixers):

    $ ./vendor/bin/php-cs-fixer fix -v

After your work is finished rebase the feature branch and push it:

    $ git checkout master
    $ git fetch upstream
    $ git merge upstream/master
    $ git checkout feature/BRANCH_NAME
    $ git rebase master
    $ git push --force origin feature/BRANCH_NAME

Go to GitHub again and make a pull request on the ppi/framework repository. Thank you for making PPI better!
