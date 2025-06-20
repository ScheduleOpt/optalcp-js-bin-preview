# OptalCP binaries for JavaScript (Preview Version)

This is a JavaScript `npm` module named `@scheduleopt/optalcp-bin-preview`.
It contains compiled binaries (executables) of [OptalCP solver](https://optalcp.com).
The preview version solves all problems but reports only objective values, not values of the variables.

The following architectures are supported:

* Linux x64
* Windows x64
* macOS x64
* macOS arm64

## Installation

The module can be installed directly from [optalcp-js-bin-preview GitHub repository](https://github.com/ScheduleOpt/optalcp-js-bin-preview) by running:

```sh
npm install scheduleopt/optalcp-js-bin-preview#latest
```

The line above also installs npm package `@scheduleopt/optalcp` from [optalcp-js repository](https://github.com/ScheduleOpt/optalcp-js).
This package contains JavaScript (and TypeScript) API for the solver.

To test the installation, run:

```sh
npx optalcp --version
```

The documentation can be found on the [OptalCP web page](https://optalcp.com/docs/api).

## Versions and tags

You can use the `#latest` suffix to get the latest stable version.
You can also install a particular version by specifying its tag, for example:

```sh
npm install scheduleopt/optalcp-js-bin-preview#v2024.5.0
```
