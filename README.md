# Laraver validator for spanish stuff: NIF, NIE, CIF, NSS, IBAN, Postal Code, Phone numbers 

[![Latest Version on Packagist](https://img.shields.io/packagist/v/spatie/laravel-validation-rules.svg?style=flat-square)](https://packagist.org/packages/spatie/laravel-validation-rules)
[![Code coverage](https://scrutinizer-ci.com/g/spatie/laravel-validation-rules/badges/coverage.png)](https://scrutinizer-ci.com/g/spatie/laravel-validation-rules)
[![Build Status](https://img.shields.io/travis/spatie/laravel-validation-rules/master.svg?style=flat-square)](https://travis-ci.org/spatie/laravel-validation-rules)
[![StyleCI](https://github.styleci.io/repos/152587206/shield?branch=master)](https://github.styleci.io/repos/152587206)
[![Quality Score](https://img.shields.io/scrutinizer/g/spatie/laravel-validation-rules.svg?style=flat-square)](https://scrutinizer-ci.com/g/spatie/laravel-validation-rules)
[![Total Downloads](https://img.shields.io/packagist/dt/spatie/laravel-validation-rules.svg?style=flat-square)](https://packagist.org/packages/spatie/laravel-validation-rules)

This package is a set of diferent validation rules for spanish national id numbers like:

- **NIF**: _"Número de Identificación Fiscal"_ (tax number for individuals).
- **NIE**: _"Número de Idenfiticación para Extranjeros"_ (identity number for foreigners).
- **CIF**: _"Código de Identificación Fiscal"_ (tax number for companies).
- **NSS**: _"Número de la Seguridad Social"_ (national security number).

Also the package include validators for:

- **IBAN**: International Bank Account Number.
- **Postal codes**: Spanish postal codes.
- **Phone number**: Spanish phone numbers format.


The package can be installed via composer:

```bash
composer require orumad/laravel-spanish-validator
```

The package will automatically register itself.


## Available rules

- [`nif`](#nif)
- [`nie`](#nie)
- [`cif`](#cif)
- [`spanish_tax_number`](#spanish_tax_number)
- [`nss`](#nss)
- [`iban`](#iban)
- [`spanish_postal_code`](#spanish_postal_code)
- [`spanish_phone`](#spanish_phone)


### `NIF`

Determine if the input is a valid _"Número de Identificación Fiscal"_ (tax number for individuals).


### `NIE`

Determine if the field under validation is a valid _"Número de Idenfiticación para Extranjeros"_ (identity number for foreigners).


### `CIF`

This rule will validate if the input field is a valid _"Código de Identificación Fiscal"_ (tax number for companies).


### `Spanish Tax Number`

This rule validates if the input is a valid spanish tax number: NIF or NIE or CIF.


### Testing

``` bash
composer test
```

### Changelog

Please see [CHANGELOG](CHANGELOG.md) for more information on what has changed recently.

## Contributing

Please see [CONTRIBUTING](CONTRIBUTING.md) for details.

### Security

If you discover any security related issues, please email dev@danielmunoz.io instead of using the issue tracker.

## License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.
