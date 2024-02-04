# LLM Driver for Ollama, OpenAi API, and Laravel

[![Latest Version on Packagist](https://img.shields.io/packagist/v/alnutile/llmdriver.svg?style=flat-square)](https://packagist.org/packages/alnutile/llmdriver)
[![Tests](https://img.shields.io/github/actions/workflow/status/alnutile/llmdriver/run-tests.yml?branch=main&label=tests&style=flat-square)](https://github.com/alnutile/llmdriver/actions/workflows/run-tests.yml)
[![Total Downloads](https://img.shields.io/packagist/dt/alnutile/llmdriver.svg?style=flat-square)](https://packagist.org/packages/alnutile/llmdriver)

I would like a library like Laravel Storage or Cache etc that can talk to different file systems or cache systems but all with the same api.

Starting with these docs [https://github.com/ollama/ollama/blob/main/docs/api.md](https://github.com/ollama/ollama/blob/main/docs/api.md) I will build out response objects that can be shared with OpenAi PHP library.

Then the driver can talk to either one and that will include Azures OpenAi

> NOTE NOTHING BELOW IS WORKING 
## Installation

You can install the package via composer:

```bash
composer require alnutile/llmdriver
```

## Usage

```php
$skeleton = new AlNutile\LlmDriver();
echo $skeleton->echoPhrase('Hello, AlNutile!');
```

## Testing

```bash
composer test
```

## Changelog

Please see [CHANGELOG](CHANGELOG.md) for more information on what has changed recently.

## Contributing

Please see [CONTRIBUTING](https://github.com/spatie/.github/blob/main/CONTRIBUTING.md) for details.

## Security Vulnerabilities

Please review [our security policy](../../security/policy) on how to report security vulnerabilities.

## Credits

- [Alfred Nutile](https://github.com/alnutile)
- [All Contributors](../../contributors)

## License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.
