# Sluggable

[![Latest Version on Packagist][ico-version]][link-packagist]
[![Total Downloads][ico-downloads]][link-downloads]
[![Build Status][ico-travis]][link-travis]
[![StyleCI][ico-styleci]][link-styleci]

This is where your description should go. Take a look at [contributing.md](contributing.md) to see a to do list.

## Installation

Via Composer

``` bash
$ composer require luqta/sluggable
```

## Usage

Go to the model that you need to sluggable and use the Sluggable trait
```
<?php
namespace App;

**use Luqta\Sluggable\Traits\Sluggable;**

class User extends Model
{
    use **Sluggable**;
}
```

## Change log

Please see the [changelog](changelog.md) for more information on what has changed recently.

## Testing

``` bash
$ composer test
```

## Contributing

Please see [contributing.md](contributing.md) for details and a todolist.

## Security

If you discover any security related issues, please email author email instead of using the issue tracker.

## Credits

- [author name][link-author]
- [All Contributors][link-contributors]

## License

license. Please see the [license file](license.md) for more information.

[ico-version]: https://img.shields.io/packagist/v/luqta/sluggable.svg?style=flat-square
[ico-downloads]: https://img.shields.io/packagist/dt/luqta/sluggable.svg?style=flat-square
[ico-travis]: https://img.shields.io/travis/luqta/sluggable/master.svg?style=flat-square
[ico-styleci]: https://styleci.io/repos/12345678/shield

[link-packagist]: https://packagist.org/packages/luqta/sluggable
[link-downloads]: https://packagist.org/packages/luqta/sluggable
[link-travis]: https://travis-ci.org/luqta/sluggable
[link-styleci]: https://styleci.io/repos/12345678
[link-author]: https://github.com/luqta
[link-contributors]: ../../contributors
