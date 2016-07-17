# :package_name

[![Latest Version on Packagist][ico-version]][link-packagist]
[![Software License][ico-license]](LICENSE.md)
[![Coverage Status][ico-scrutinizer]][link-scrutinizer]
[![Quality Score][ico-code-quality]][link-code-quality]
[![Total Downloads][ico-downloads]][link-downloads]

**Note:** Replace ```:package_name``` ```:package_description``` with their
correct values in [README.md](README.md), [CHANGELOG.md](CHANGELOG.md), [CONTRIBUTING.md](CONTRIBUTING.md), [LICENSE.md](LICENSE.md) and
[composer.json](composer.json) files, then delete this line.

This is where your description should go. Try and limit it to a paragraph or
two, and maybe throw in a mention of what PSRs you support to avoid any
confusion with users and contributors.

Inspired by phpleague/skeleton, peterkokot/php-skeleton and koriym/PHP.Skeleton.

## Install

Via Composer

``` bash
composer require martiadrogue/:package_name
```

## Usage

``` php
$skeleton = new MartiAdrogue\Skeleton();
echo $skeleton->echoPhrase('Hello, world!');
```

## Change log

Please see [CHANGELOG](CHANGELOG.md) for more information what has changed
recently.

## Testing

`composer test` run phpcs, phpmd and phpunit. Run phpunit for unit test only.

``` bash
composer test
```

## Code Smell Fix

`composer format` run php-cs-fixer and phpcbf to fix up the PHP code to follow
the coding standards.

``` bash
composer format
```

## Contributing

Please see [CONTRIBUTING](CONTRIBUTING.md) and [CONDUCT](CONDUCT.md) for
details.

## Security

If you discover any security related issues, please email
marti.adrogue@gmail.com instead of using the issue tracker.

## Credits

-   [Martí Adrogué][link-author]
-   [All Contributors][link-contributors]

## License

The MIT License (MIT). Please see [License File](LICENSE.md) for more
information.

[ico-version]: https://img.shields.io/packagist/v/martiadrogue/:package_name.svg?style=flat-square
[ico-license]: https://img.shields.io/badge/license-MIT-brightgreen.svg?style=flat-square
[ico-scrutinizer]: https://img.shields.io/scrutinizer/coverage/g/martiadrogue/:package_name.svg?style=flat-square
[ico-code-quality]: https://img.shields.io/scrutinizer/g/martiadrogue/:package_name.svg?style=flat-square
[ico-downloads]: https://img.shields.io/packagist/dt/martiadrogue/:package_name.svg?style=flat-square

[link-packagist]: https://packagist.org/packages/martiadrogue/:package_name
[link-scrutinizer]: https://scrutinizer-ci.com/g/martiadrogue/:package_name/code-structure
[link-code-quality]: https://scrutinizer-ci.com/g/martiadrogue/:package_name
[link-downloads]: https://packagist.org/packages/martiadrogue/:package_name
[link-author]: https://github.com/martiadrogue
[link-contributors]: ../../contributors
