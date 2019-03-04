# ReactPHP PSR Cache Bridge

Bridge between React cache and PSR caching implementation.


## Install

Via [composer](http://getcomposer.org):

```shell
composer require niko9911/react-psr-cache-bridge
```

## Usage

Will work like normal PHP bridge.

Example:
```php
<?php
declare(strict_types=1);

$psr = new Cache(); // Object implementing PSR Cache.
$react = new \Niko9911\React\Cache\Bridge\ReactPsrCacheBridge($psr); 

```

## License

Licensed under the [MIT license](http://opensource.org/licenses/MIT).
