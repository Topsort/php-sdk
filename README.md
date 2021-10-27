## Installation

The recommended way to install Topsort's SDK for PHP is with Composer. Composer
is a dependency management tool for PHP that allows you to declare the
dependencies your project needs and installs them into your project.

```json
{
  "require": {
    "topsort/php-sdk": "1.0.0"
  }
}
```

## Usage
```php
<?php
use Topsort\SDK;

$topsort_client = new SDK('my_marketplace', 'my_api_key');
$auction_result = $topsort_client->auction($slots, $products, $session)->wait();
```
