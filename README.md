# afc-scout

[![CI status](https://github.com/dominiksalvet/afc-scout/workflows/CI/badge.svg)](https://github.com/dominiksalvet/afc-scout/commits)
[![GitPack](https://img.shields.io/badge/-GitPack-571997)](https://github.com/dominiksalvet/gitpack)
[![standard-readme compliant](https://img.shields.io/badge/readme_style-standard-brightgreen.svg)](https://github.com/RichardLitt/standard-readme)

> ACPI scout of asus-fan-control.

This is the ACPI scout of [asus-fan-control](https://github.com/dominiksalvet/asus-fan-control). Once a new laptop model is to be added to asus-fan-control as tested, it may not work out of the box. The problem might be caused by a different base ACPI fan address as well as different number of temperatures from the default values.

This tool might be useful in those cases, which are referred to as advanced configuration. It helps to find the correct ACPI fan address of your device by dumping ACPI address ranges (everything is in decimal form). Then, you can watch carefully for any temperatures pattern and try to use asus-fan-control with the respective address.

## Table of Contents

* [Install](#install)
  * [Dependencies](#dependencies)
* [Usage](#usage)
  * [Example](#example)
* [Contributing](#contributing)
* [License](#license)

## Install

Afc-scout supports [GitPack](https://github.com/dominiksalvet/gitpack). Global installation/update:

```sh
sudo gitpack install github.com/dominiksalvet/afc-scout
```

### Dependencies

* [asus-fan-control](https://github.com/dominiksalvet/asus-fan-control)

## Usage

Usage content.

### Example

Example content.

## Contributing

Do you want to contribute? Do you have any questions? Then the [*CONTRIBUTING.md*](CONTRIBUTING.md) file is here for you.

## License

Afc-scout is licensed under the [MIT License](LICENSE).
