# is-ci

Returns `true` if the current environment is a Continuous Integration
server.

Please [open an issue](https://github.com/watson/is-ci/issues) if your
CI server isn't properly detected :)

[![Build status](https://travis-ci.org/watson/is-ci.svg?branch=master)](https://travis-ci.org/watson/is-ci)
[![js-standard-style](https://img.shields.io/badge/code%20style-standard-brightgreen.svg?style=flat)](https://github.com/feross/standard)

## Installation

```
npm install is-ci
```

## Usage

```js
var isCI = require('is-ci')

if (isCI) {
  console.log('The code is running on a CI server')
}
```
## Supported CI tools

Currently detects:

- TravisCI
- Appveyor
- Bamboo
- Buildkite
- CircleCI
- CodeShip
- GitlabCI
- Hudson
- Jenkins
- Magnum CI
- Semaphore CI
- Snip CI
- TeamCity

Other CI tools using environment variables like 'BUILD_ID' or 'CI' would be detected as well.

## License

MIT
