Montapacking PHP API Wrapper
=========================

A simple PHP wrapper for the montapacking API.

## Installation

This project can easily be installed through Composer.

```
composer require qubiqx/montapacking
```

## Example: Get product

```php
<?php

require __DIR__ . '/vendor/autoload.php';

$username = '-montapacking-username-';
$password = '-montapacking-password-';

$apiclient = new Qubiqx\Montapacking\Client($username, $password);

$product = $apiclient->getProduct('-sku-');
var_dump($product);
```

####Forked from arjennz