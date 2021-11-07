# Hemo-Bank

![GitHub all releases](https://img.shields.io/github/downloads/FaizaFaisal/Hemo-Bank/total?color=Blue&label=Downloads)
[![Contributor Covenant](https://img.shields.io/badge/Contributor%20Covenant-2.1-4baaaa.svg)](code_of_conduct.md)

An open source software to create and manage an online blood bank administration mobile app. Blood transfusion safety and availability is a major problem in Bahrain, which is working hard to build a world-class healthcare system for its inhabitants. To do so, a well-functioning open source blood bank system is necessary. The app also intends to encourage citizens to donate blood by providing services such as online donation appointments and blood donation pickup at their homes.

This app makes it easier for hospitals to check the available and needed blood types. Likewise, there will be blood donors’ registration, thus, ensuring that blood transfusion services will be safe and secured. The app will be of great help to all users, donors, hospital staff, administration ensuring a better healthcare system. The app allows the blood bank to make inventories of their blood bags online, thus, allowing each hospital to check the availability of blood bags anytime. Likewise, proper management of blood donors ensures that the expected blood transfusion services will be safe and secured.

[![Build Status](https://travis-ci.org/ekalinin/github-markdown-toc.svg?branch=master)](https://travis-ci.org/ekalinin/github-markdown-toc)

Table of contents
=================

<!--ts-->
   * [Installation](#installation)
   * [Usage](#usage)
      * [STDIN](#stdin)
      * [Local files](#local-files)
      * [Remote files](#remote-files)
      * [Multiple files](#multiple-files)
      * [Combo](#combo)
      * [Auto insert and update TOC](#auto-insert-and-update-toc)
      * [GitHub token](#github-token)
      * [TOC generation with Github Actions](#toc-generation-with-github-actions)
   * [Tests](#tests)
   * [Dependency](#dependency)
   * [Docker](#docker)
     * [Local](#local)
     * [Public](#public)
<!--te-->


Installation
============

Linux (manual installation)
```bash
$ wget https://raw.githubusercontent.com/ekalinin/github-markdown-toc/master/gh-md-toc
$ chmod a+x gh-md-toc
```

MacOS (manual installation)
```bash
$ curl https://raw.githubusercontent.com/ekalinin/github-markdown-toc/master/gh-md-toc -o gh-md-toc
$ chmod a+x gh-md-toc
```

Linux or MacOS (using [Basher](https://github.com/basherpm/basher))
```bash
$ basher install ekalinin/github-markdown-toc
# `gh-md-toc` will automatically be available in the PATH
```

Usage
=====


STDIN
-----

Here's an example of TOC creating for markdown from STDIN:

```bash
➥ cat ~/projects/Dockerfile.vim/README.md | ./gh-md-toc -
  * [Dockerfile.vim](#dockerfilevim)
  * [Screenshot](#screenshot)
  * [Installation](#installation)
        * [OR using Pathogen:](#or-using-pathogen)
        * [OR using Vundle:](#or-using-vundle)
  * [License](#license)
```




