# ESMValTool Core package
[![Documentation Status](https://readthedocs.org/projects/esmvaltool/badge/?version=version2_development)](https://esmvaltool.readthedocs.io/en/version2_development/?badge=version2_development)
[![DOIBadge](https://img.shields.io/badge/DOI-10.17874%2Fac8548f0315-blue.svg)](https://doi.org/10.17874/ac8548f0315)
[![Gitter](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/ESMValGroup?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
[![CircleCI](https://circleci.com/gh/ESMValGroup/ESMValCore.svg?style=svg)](https://circleci.com/gh/ESMValGroup/ESMValCore)
[![Codacy Coverage Badge](https://api.codacy.com/project/badge/Coverage/79bf6932c2e844eea15d0fb1ed7e415c)](https://www.codacy.com/app/ESMValGroup/ESMValCore?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=ESMValGroup/ESMValCore&amp;utm_campaign=Badge_Coverage)
[![Codacy Badge](https://api.codacy.com/project/badge/Grade/79bf6932c2e844eea15d0fb1ed7e415c)](https://www.codacy.com/app/ESMValGroup/ESMValTool?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=ESMValGroup/ESMValTool&amp;utm_campaign=Badge_Grade)
[![Docker Build Status](https://img.shields.io/docker/build/esmvalgroup/esmvaltool.svg)](https://hub.docker.com/r/esmvalgroup/esmvaltool/)
[![Anaconda-Server Badge](https://anaconda.org/esmvalgroup/esmvalcore/badges/installer/conda.svg)](https://conda.anaconda.org/esmvalgroup)


ESMValTool Core: core functionalities for the ESMValTool, a community diagnostic and performance metrics tool for routine evaluation of Earth system models in CMIP

# Getting started
This is the development branch for ESMValTool Core. ESMValTool version 2 is under rapid development, an installation from source is recommended at the moment.

## Installing from source [recommended]
Please see [CONTRIBUTING.md](https://github.com/ESMValGroup/ESMValCore/blob/development/CONTRIBUTING.md) for instructions on installing ESMValTool from source.

## Installing from Anaconda
The Anaconda package can be found on [ESMValGroup Anaconda Channel.](https://anaconda.org/ESMValGroup)

If you already installed Anaconda, you can install ESMValTool by running:
```
conda install -c esmvalgroup -c conda-forge esmvalcore
```

## Running ESMValTool
- Review `config-user.yml`. To customize for your system, create a copy, edit and use the command line option `-c` to instruct `esmvaltool` to use your custom configuration.
- Optionally install the ESMValTool recipes and diagnostics
- Run e.g. `esmvaltool -c ~/config-user.yml examples/recipe_python.yml

## Getting help
The easiest way to get help if you cannot find the answer in the documentation on [readthedocs](https://esmvaltool.readthedocs.io), is to open an [issue on GitHub](https://github.com/ESMValGroup/ESMValCore/issues).

## Contributing
If you would like to contribute a new diagnostic or feature, please have a look at [CONTRIBUTING.md](https://github.com/ESMValGroup/ESMValCore/blob/development/CONTRIBUTING.md).

