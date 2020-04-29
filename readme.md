# afc-scout

[![CI status](https://github.com/dominiksalvet/afc-scout/workflows/CI/badge.svg)](https://github.com/dominiksalvet/afc-scout/commits)
[![GitPack](https://img.shields.io/badge/-GitPack-571997)](https://github.com/dominiksalvet/gitpack)
[![standard-readme compliant](https://img.shields.io/badge/readme_style-standard-brightgreen.svg)](https://github.com/RichardLitt/standard-readme)

> ACPI scout of asus-fan-control.

This is the ACPI scout of [asus-fan-control](https://github.com/dominiksalvet/asus-fan-control). Once a new laptop model is to be added to asus-fan-control as tested, it may not work out of the box. The problem might be caused by a different base ACPI fan address as well as different number of temperatures from the default values.

This tool might be useful in those cases, which are referred to as advanced configuration in asus-fan-control. It helps to find the correct ACPI fan address of your device by dumping ACPI address ranges (everything is in decimal form). Then, you can watch carefully for any temperatures pattern and try to use asus-fan-control with the respective address.

## Table of Contents

* [Install](#install)
  * [Dependencies](#dependencies)
* [Usage](#usage)
  * [Example](#example)
* [Questions](#questions)
* [Contributing](#contributing)
* [License](#license)

## Install

Afc-scout supports [GitPack](https://github.com/dominiksalvet/gitpack). Global installation/update:

```sh
sudo gitpack install github.com/dominiksalvet/afc-scout
```

### Dependencies

* **acpi_call** module (see [asus-fan-control](https://github.com/dominiksalvet/asus-fan-control))

## Usage

To dump the most interesting ACPI address range, use:

```sh
sudo afc-scout
```

If you want to use your own address range, use:

```
sudo afc-scout <start> <end>
```

### Example

<p align="center">
    <img src="img/example.png" alt="afc-scout example">
</p>

This example has been demonstrated on the UX430UA laptop model to detect the ACPI fan base address based on the values characteristics. As you can see, the base ACPI fan address might be 1335 with 8 temperatures (in fact it is).

## Questions

If you have any questions, you can find out how to get them answered in [*support.md*](support.md) file.

## Contributing

Do you want to contribute somehow? Then [*contributing.md*](contributing.md) file is here for you.

## License

Afc-scout is licensed under the [MIT License](license).
