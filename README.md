# unit-synonyms-luminous-intensity

[![Build Status](https://travis-ci.org/javiercejudo/unit-synonyms-luminous-intensity.svg)](https://travis-ci.org/javiercejudo/unit-synonyms-luminous-intensity)
[![Coverage Status](https://coveralls.io/repos/javiercejudo/unit-synonyms-luminous-intensity/badge.svg?branch=master)](https://coveralls.io/r/javiercejudo/unit-synonyms-luminous-intensity?branch=master)
[![Code Climate](https://codeclimate.com/github/javiercejudo/unit-synonyms-luminous-intensity/badges/gpa.svg)](https://codeclimate.com/github/javiercejudo/unit-synonyms-luminous-intensity)

Luminous intensity units synonyms

## Install

    npm i unit-synonyms-luminous-intensity

## Units

- [Candela](https://en.wikipedia.org/wiki/Candela)
- [Candlepower](https://en.wikipedia.org/wiki/Candlepower)
- [Hefnerkerze](https://en.wikipedia.org/wiki/Hefner_lamp)

## Usage

```js
var synonyms = require('unit-synonyms-luminous-intensity').synonyms;

synonyms['cd']; // => candela
synonyms['candlepowers']; // => candlepower
```

## Related projects

- [linear-presets](https://github.com/javiercejudo/linear-presets): linear presets for common units.
- [linear-converter](https://github.com/javiercejudo/linear-converter): flexible linear converter.
