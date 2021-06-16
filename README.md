Number Formatter
=========

A small library that adds commas to numbers

[![Build Status](https://travis-ci.org/balakarthikeyan/number-formatter.svg?branch=master)](https://travis-ci.org/balakarthikeyan/number-formatter)

## How to create this Project from Scratch

```
Create Account in Github, NPM
npm set init.author.name "Balakarthikeyan"
npm set init.author.email "balakarthikeyan07@gmail.com"
npm set init.author.url "http://www.cutcopyshare.com"
npm login
npm init

git add .
git commit -m “Initial release”
git tag v1.0.0
git push origin master --tags

npm publish --access=public
```

## Installation

  `npm install @balakarthikeyan/bob-number-formatter`

## Usage

    var numFormatter = require('@balakarthikeyan/bob-number-formatter');

    var formattedNum = numFormatter(12345678);
  
  
  Output should be `12,345,678`


## Tests

  `npm test`

## Contributing

Add unit tests for any new or changed functionality. Lint and test your code.

## Updating the version

npm version patch|minor|major -m "Version %s - <Message>"
git push && git push --tags (or git push origin master --tags)
npm publish
