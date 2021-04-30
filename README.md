# semver-set

Tools to set semver. right now only intersect: return the most common semver of 2 or more given versions.

[![NPM](https://nodei.co/npm/@isaac.frontend/semver-set.png)](https://nodei.co/npm/@isaac.frontend/semver-set/)

[![npm version](https://badge.fury.io/js/%40isaac.frontend%2Fsemver-set.svg)](https://badge.fury.io/js/%40isaac.frontend%2Fsemver-set)
[![Open Source Love](https://badges.frapsoft.com/os/mit/mit.svg?v=102)](https://github.com/ellerbrock/open-source-badge/)

## Installation

Install this module through npm or clone it:

```javascript
npm install --save @isaac.frontend/semver-set
```

## Usage

```javascript
var intersect = require("semver-set").intersect;
intersect("^1.0.0", "^1.0.4"); // "^1.0.0"
```

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## Credits

Author - Izaak Schroeder (@izaakschroeder)
Contributor - Lucien Immink(@lucienimmink)

## License

The MIT License (MIT)

Copyright (c) 2017 Enrico Aleandri

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
