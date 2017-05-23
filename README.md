# postcss-typescript-kickstart

[![Travis](https://img.shields.io/travis/ezavile/postcss-typescript-kickstart.svg?style=flat-square)](https://travis-ci.org/ezavile/postcss-typescript-kickstart)
[![Codecov](https://img.shields.io/codecov/c/github/ezavile/postcss-typescript-kickstart.svg?style=flat-square)](https://codecov.io/gh/ezavile/postcss-typescript-kickstart)
[![npm](https://img.shields.io/npm/v/postcss-typescript-kickstart.svg?style=flat-square)](https://www.npmjs.com/package/postcss-typescript-kickstart)
[![MIT License](https://img.shields.io/npm/l/postcss-typescript-kickstart.svg?style=flat-square)](http://opensource.org/licenses/MIT)

Simple boilerplate to kickstart your new PostCSS plugin with TypeScript, also include AVA to test and generate a code coverage report.

## Usage

Clone the boilerplate and create your own git repo.

```javascript
git clone git@github.com:ezavile/postcss-typescript-kickstart.git
```

Install the dependencies and start the server.

```javascript
npm/yarn install
```

## Scripts

To compile TypeScript files.
```javascript
npm run compile
```

To compile TypeScript files and watch for changes.
```javascript
npm run compile:watch
```
Lint the code and generate a code coverage report. Anything less than 100% coverage will throw an error.
```javascript
npm run test
```

## Thanks
Inspired by [postcss-font-pack] to create the structure of the project.

## Contributing
* ⇄ Pull requests and ★ Stars are always welcome.
* For bugs and feature requests, please create an issue.
* Pull requests must be accompanied by passing automated tests (`npm test`).

[MIT License]

[postcss-font-pack]: https://github.com/jedmao/postcss-font-pack
[MIT License]: https://github.com/ezavile/postcss-typescript-css/blob/master/LICENSE
