# ApplicationStarter

Command Line Handler meant to be used as superclass for an application entry point.

**[Explore the Docs](docs/)**

[Report a defect](https://github.com/ba-st/ApplicationStarter/issues/new?labels=Type%3A+Defect) | 
[Request feature](https://github.com/ba-st/ApplicationStarter/issues/new?labels=Type%3A+Feature)

[![Build Status](https://travis-ci.org/ba-st/ApplicationStarter.svg?branch=master)](https://travis-ci.org/ba-st/ApplicationStarter) [![Coverage Status](https://coveralls.io/repos/github/ba-st/ApplicationStarter/badge.svg?branch=master)](https://coveralls.io/github/ba-st/ApplicationStarter?branch=master)

Useful when you want to start up your image from the command line, using parameters, this provides a framework to use: mandatory and optional arguments, logging and error handling.

If an error stops the application, it dumps a fuel file with `thisContext` allowing you to debug the error later. More details about this in the [documentation](docs/Debugging.md)

## License
- The code is licensed under [MIT](LICENSE).
- The documentation is licensed under [CC BY-SA 4.0](http://creativecommons.org/licenses/by-sa/4.0/).

## Quick Start

- Download the latest [Pharo 32](https://get.pharo.org/) or [64 bits VM](https://get.pharo.org/64/).
- Load the project using Metacello using the script in [Basic Installation](docs/Installation.md#basic-installation)
- Explore the [documentation](docs/), starting with [How To](docs/HowTo.md) is recommended.

## Installation

To load the project in a Pharo image, or declare it as a dependency of your own project follow this [instructions](docs/Installation.md).

## Contributing

Check the [Contribution Guidelines](CONTRIBUTING.md)
