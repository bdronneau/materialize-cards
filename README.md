# Materialize-cards [![Build Status](https://travis-ci.org/bdronneau/materialize-cards.svg?branch=master)](https://travis-ci.org/bdronneau/materialize-cards)

Theme for [Hugo](https://gohugo.io/) base on [materializecss](http://materializecss.com/)

## Features
  * Cards presentation with [masonry](http://masonry.desandro.com/)
  * Google Analytics
  * Socials sharing : twitter, facebook, g+
  * Disclaimer cookies : based on localstorage key
  * highlight syntax
  * Disqus comments

## Installation

```bash
$ mkdir themes
$ cd themes
$ git clone https://github.com/bdronneau/Materialize-cards.git
$ npm i
```
See [the Hugo documentation](http://gohugo.io/themes/installing/) for more information.

## Development
### Installation
```bash
npm i
```

### Checks syntaxes
```bash
npm run tests:syntax -s
```

### SASS
In order to compile SASS
```bash
npm run build:scss -s
```

For auto building on .scss change use :
```bash
npm run watch:scss -s
```
