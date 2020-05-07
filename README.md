# dictator-react-boilerplate

[![NPM](https://img.shields.io/npm/v/dictator-react-boilerplate.svg?style=flat-square)](https://www.npmjs.com/package/dictator-react-boilerplate)
[![Build Status](https://travis-ci.org/tomasbjerre/dictator-react-boilerplate.svg?branch=master)](https://travis-ci.org/tomasbjerre/dictator-react-boilerplate)

This is [react-boilerplate](https://github.com/react-boilerplate/react-boilerplate) packaged as a [dictator](https://github.com/tomasbjerre/dictator-builder).

## Usage

Example usage [here](https://github.com/tomasbjerre/dictator-react-boilerplate-example).

### Node

You can let it dictate your source repository by adding it to `package.json` like:

```json
{
  "scripts": {
    "prepare": "dictator-react-boilerplate"
  },
  "devDependencies": {
    "dictator-react-boilerplate": "a.b.c"
  }
}
```

And adjust what files you want dictated by the dictator by adding a `.dictatorconfig.json` perhaps like:

```json
{
  "ignore": [
    "/README.md",
    "/.github",
    "/app",
    "/package.json",
    "/package-lock.json",
    "/Changelod.md"
  ]
}
```
