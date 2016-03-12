# emtee [![Build Status](https://travis-ci.org/radiovisual/emtee.svg?branch=master)](https://travis-ci.org/radiovisual/emtee)

> A super-small echo module → returning values like nobody's business.

Useful for testing npm installation functionality, or echoing values like a champ.

## Install

```
$ npm install --save emtee
```

## The Entire Module

38 bytes of glory:
 
```js
module.exports=function(o){return o};
```

## API

### emtee(input)

Simply returns whatever input it receives.

## Note

This module has 3 deliberate releases so you can test npm versions:

```
npm install emtee@1.0.0
npm install emtee@2.0.0
npm install emtee@3.0.0
```

## License

MIT © [Michael Wuergler](http://numetriclabs.com)
