[![Latest Stable Version](https://poser.pugx.org/unisharp/doc-us/v/stable)](https://packagist.org/packages/unisharp/doc-us) [![Total Downloads](https://poser.pugx.org/unisharp/doc-us/downloads)](https://packagist.org/packages/unisharp/doc-us) [![License](https://poser.pugx.org/unisharp/doc-us/license)](https://packagist.org/packages/unisharp/doc-us)

# Doc Us

A MySQL Schema Documantation Generator for Laravel.

## Installation

1. Require this package with composer:

```bash
composer require unisharp/doc-us
```

2. After updating composer, add the ServiceProvider to the providers array in `config/app.php`:

```php
'providers' => [
    /* ... */

    UniSharp\DocUs\DocUsServiceProvider::class,

    /* ... */
];
```

## Usage

<http://{host}/schema?format={supported-format}>

Supported Formats

 - html
 - markdown
 - json

## Demo

#### HTML
![html](http://i.imgur.com/EQaDRXMg.png)
#### Markdown
![markdown](http://i.imgur.com/kt92Uflg.png)
#### Json
![json](http://i.imgur.com/VCzAw3Qg.png)

## Test

```
./vendor/bin/phpunit tests
```

## License

The DocUs released under [MIT license](https://unisharp.mit-license.org/).
