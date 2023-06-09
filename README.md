# React-Intl-Tel-Input

[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)
[![CICD](https://github.com/patw0929/react-intl-tel-input/actions/workflows/main.yml/badge.svg)](https://github.com/patw0929/react-intl-tel-input/actions/workflows/main.yml)
[![npm version](https://badge.fury.io/js/react-intl-tel-input.svg)](http://badge.fury.io/js/react-intl-tel-input)
[![Coverage Status](https://coveralls.io/repos/github/patw0929/react-intl-tel-input/badge.svg?branch=master)](https://coveralls.io/github/patw0929/react-intl-tel-input?branch=master)
[![npm](https://img.shields.io/npm/l/express.svg?maxAge=2592000)]()

[![NPM](https://nodei.co/npm/react-intl-tel-input.png?downloads=true&downloadRank=true&stars=true)](https://nodei.co/npm/react-intl-tel-input/)

Rewrite [International Telephone Input](https://github.com/jackocnr/intl-tel-input) in React.js.


## Collaborators Wanted!

Due to the long commuting time, I do not have much time to maintain this project often. 😣

So if anybody else is willing to take on the work of bug fixes, integrating pull requests, etc,
please let me know. 🙌

I hope we can maintain the project together, and make this project better! 💪

## Demo & Examples

Live demo: [patw0929.github.io/react-intl-tel-input](https://patw0929.github.io/react-intl-tel-input/)

To build the examples locally, run:

```bash
yarn
yarn website:start
```

Then open [`localhost:3000`](http://localhost:3000) in a browser.


## Installation

```bash
yarn add react-intl-tel-input
```


### TypeScript

`react-intl-tel-input` ships with official type declarations out of the box.


## Usage

```javascript
import IntlTelInput from 'react-intl-tel-input';
import 'react-intl-tel-input/dist/main.css';

<IntlTelInput
  containerClassName="intl-tel-input"
  inputClassName="form-control"
/>
```

### Properties

Please see the [Demo Page](https://patw0929.github.io/react-intl-tel-input/)


## Development (`src` and the build process)

To build, watch and serve the examples (which will also watch the component source), run `yarn website:start`.

You can prepare a distribution build using `yarn build`.

## Contributing

Any kind of contribution including proposals, doc improvements, enhancements, bug fixes are always welcome. 

To contribute to `react-intl-tel-input`, clone this repo locally and commit your code on a separate branch. Please write tests for your code, and run the linter before opening a pull-request:

```bash
yarn test    # if you are enhancing the JavaScript modules
yarn test:ts # if you are enhancing the TypeScript type declarations
yarn lint
```

Also, please let us know if you encounter any issue by filing an [issue](https://github.com/patw0929/react-intl-tel-input/issues).

## Inspired by

[International Telephone Input](https://github.com/jackocnr/intl-tel-input) - [@jackocnr](https://github.com/jackocnr)


## License

MIT

Copyright (c) 2015-2019 patw.
