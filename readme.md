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

## License

MIT © [Michael Wuergler](http://numetriclabs.com)
