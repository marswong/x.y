x.y
===

[![build status][travis-image]][travis-url]
[![Test coverage][coveralls-image]][coveralls-url]

## Features

- Generate 8-bit short link from raw link
- Recover raw link from short link

## Development

```bash
$ npm i
$ npm run dev
$ open http://localhost:7001/
```

Don't tsc compile at development mode, if you had run `tsc` then you need to `npm run clean` before `npm run dev`.

## Deployment

```bash
$ npm run tsc
$ npm start
```

## Requirement

- Node.js 8.x
- Typescript 2.8+

## Wiki

- System Design
- Database Design

## Apendix

- [Design Pastebin.com (or Bit.ly)][design-pastebin]
- [hackernews-async-ts][hackernews-async-ts]


[travis-image]: https://img.shields.io/travis/marswong/x.y/master.svg?style=flat-square
[travis-url]: https://travis-ci.org/marswong/x.y
[coveralls-image]: https://img.shields.io/codecov/c/github/marswong/x.y.svg?style=flat-square
[coveralls-url]: https://codecov.io/github/marswong/x.y?branch=master
[design-pastebin]: https://github.com/donnemartin/system-design-primer/blob/master/solutions/system_design/pastebin/README.md
[hackernews-async-ts]: https://github.com/eggjs/examples/tree/master/hackernews-async-ts
