# GLPI Library for AngularJS

![GLPI banner](https://user-images.githubusercontent.com/29282308/31666160-8ad74b1a-b34b-11e7-839b-043255af4f58.png)

[![Greenkeeper badge](https://badges.greenkeeper.io/flyve-mdm/angularjs-glpi.svg)](https://greenkeeper.io/)
[![License](https://img.shields.io/github/license/flyve-mdm/flyve-mdm-android-inventory-agent.svg?&label=License)](https://github.com/flyve-mdm/angularjs-glpi/blob/master/LICENSE.md)
[![Follow twitter](https://img.shields.io/twitter/follow/FlyveMDM.svg?style=social&label=Twitter&style=flat-square)](https://twitter.com/FlyveMDM)
[![Telegram Group](https://img.shields.io/badge/Telegram-Group-blue.svg)](https://t.me/flyvemdm)
[![Conventional Commits](https://img.shields.io/badge/Conventional%20Commits-1.0.0-yellow.svg)](https://conventionalcommits.org)

GLPI (_Gestionnaire Libre de Parc Informatique_) is a free IT Asset Management, issue tracking system and service desk solution. This open source software is written in PHP.

It helps companies to manage their information system, since it's able to build an inventory of all the organization's assets and to manage administrative and financial tasks.

## Table of Contents

* [Synopsis](#synopsis)
* [Build Status](#build-status)
* [Installation](#installation)
* [Documentation](#documentation)
* [Versioning](#versioning)
* [Contact](#contact)
* [Contribute](#contribute)
* [Copying](#copying)

## Synopsis

This library is specifically designed for using AngularJS with GLPI, features several functionalities common to all GLPI APIs, for example:

- HTTP transport to APIs.
- Error handling
- Authentication
- JSON parsing
- Media download/upload
- Batching.

You will be able to call to all the methods that belong to the [GLPI REST API](https://dev.flyve.org/glpi/apirest.php), for more information such as the list of the main functions and item types of the project on the website visit the [website](http://flyve.org/angularjs-glpi/).

## Build Status

|**Release channel**|**Beta Channel**|
|:---:|:---:|
|[![Travis build](https://api.travis-ci.org/flyve-mdm/angularjs-glpi.svg?branch=master)](https://travis-ci.org/flyve-mdm/angularjs-glpi)|[![Travis build](https://api.travis-ci.org/flyve-mdm/angularjs-glpi.svg?branch=develop)](https://travis-ci.org/flyve-mdm/angularjs-glpi)|

## Installation

1. `bower install angularjs-glpi`.
1. Include the `service.js` script, and this script's dependencies are included in your app.
1. Add `ngGLPI` as a module dependency to your app.

## Documentation

We maintain a detailed documentation of the project in the [project's website](http://flyve.org/angularjs-glpi/).

## Versioning

In order to provide transparency on our release cycle and to maintain backward compatibility, Flyve MDM is maintained under [the Semantic Versioning guidelines](http://semver.org/). We are committed to following and complying with the rules, the best we can.

See [the tags section of our GitHub project](https://github.com/flyve-mdm/angularjs-glpi/tags) for changelogs for each release version of Flyve MDM. Release announcement posts on [the official Teclib' blog](http://www.teclib-edition.com/en/communities/blog-posts/) contain summaries of the most noteworthy changes made in each release.

## Contact

For notices about major changes and general discussion of Flyve MDM development, subscribe to the [/r/FlyveMDM](http://www.reddit.com/r/FlyveMDM) subreddit.
You can also chat with us via IRC in [#flyve-mdm on freenode](http://webchat.freenode.net/?channels=flyve-mdm]) or [@flyvemdmdev on Telegram](https://t.me/flyvemdmdev).

## Contribute

Want to file a bug, contribute some code, or improve documentation? Excellent! Read up on our
guidelines for [contributing](./CONTRIBUTING.md) and then check out one of our issues in the [Issues Dashboard](https://github.com/flyve-mdm/angularjs-glpi/issues).

## Copying

* **Name**: [Flyve MDM](https://flyve-mdm.com/) is a registered trademark of [Teclib'](http://www.teclib-edition.com/en/).
* **Code**: you can redistribute it and/or modify
    it under the terms of the GNU General Public License ([GPLv3](https://www.gnu.org/licenses/gpl-3.0.en.html)).
* **Documentation**: released under Attribution 4.0 International ([CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)).
