# Poplar

[![license](https://img.shields.io/github/license/synyi/poplar.svg)](https://github.com/synyi/poplar/blob/master/LICENSE)
[![version](https://img.shields.io/npm/v/poplar-annotation.svg)](https://www.npmjs.com/package/poplar-annotation)


A web-based annotation tool for natural language processing (NLP) needs, inspired by [brat rapid annotation tool](http://brat.nlplab.org/).

![screenshot](http://i.v2ex.co/t690JyZS.png)

> Poplar is the new version and not production ready. Please report an issue if you find any problems.

## Demo

See [https://yanjinghou.github.io/poplar/](https://yanjinghou.github.io/poplar/)

## Quick start

### Install
```shell
npm i poplar-annotation
```
or if you'd like to use yarn
```shell
yarn add poplar-annotation
```
### Create
```typescript
import {Annotator} from 'poplar-annotation'
/**
  * Create an Annotator object
  * @param data          can be JSON or string
  * @param htmlElement   the html element to bind to
  * @param config        config object
  */
new Annotator(data: string, htmlElement: HTMLElement, config?: Object)
```

### More info

View our [API Reference](https://github.com/synyi/poplar/tree/master/doc) here.

## Want to contribute?

See our [Developer's Guide](https://github.com/synyi/poplar/blob/master/doc/Develop_Guides.md).


## Support

