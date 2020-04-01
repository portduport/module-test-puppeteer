Tests avec puppeteer
====================

Repo cloned from https://github.com/le-campus-numerique/module-test-puppeteer - Based on the work done by Philippe Le Van

[![Build Status](https://travis-ci.org/portduport/module-test-puppeteer.svg?branch=master)](https://travis-ci.org/portduport/module-test-puppeteer) [![Coverage Status](https://coveralls.io/repos/github/portduport/module-test-puppeteer/badge.svg?branch=master)](https://coveralls.io/github/portduport/module-test-puppeteer?branch=master)

Quick start
-----------

```bash
# installer puppeteer à partir du package.json
npm install

# lancer les tests (de façon séquentielle)
npm test -- --runInBand
```

Ce qu'il faut regarder
----------------------

Les premiers fichiers à regarder sont dans l'ordre :

* tests/basic.test.js
* tests/shorten.test.js

Principe
--------

Ces tests utilisent 2 outils :

* Jest : c'est l'outil de tests utilisé principalement par React (un framework JS, comme VueJS)
* Puppeteer : un outil qui permet de contrôler le navigateur chrome à distance
