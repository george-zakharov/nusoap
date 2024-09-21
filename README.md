[![Latest Stable Version](https://img.shields.io/packagist/v/nguyenanhung/nusoap.svg?style=flat-square)](https://packagist.org/packages/nguyenanhung/nusoap)
[![Total Downloads](https://img.shields.io/packagist/dt/nguyenanhung/nusoap.svg?style=flat-square)](https://packagist.org/packages/nguyenanhung/nusoap)
[![Daily Downloads](https://img.shields.io/packagist/dd/nguyenanhung/nusoap.svg?style=flat-square)](https://packagist.org/packages/nguyenanhung/nusoap)
[![Monthly Downloads](https://img.shields.io/packagist/dm/nguyenanhung/nusoap.svg?style=flat-square)](https://packagist.org/packages/nguyenanhung/nusoap)
[![License](https://img.shields.io/packagist/l/nguyenanhung/nusoap.svg?style=flat-square)](https://packagist.org/packages/nguyenanhung/nusoap)
[![PHP Version Require](https://img.shields.io/packagist/dependency-v/nguyenanhung/nusoap/php)](https://packagist.org/packages/nguyenanhung/nusoap)

# NuSoap - Fix for Php >= 5.4 and <= 8.2

NuSphere's NuSOAP for Packagist/Composer

Refactor by me, use namespace

Fix NuSOAP for PHP `>=5.4` and PHP `<=8.2`

Donate me with PayPal: [https://www.paypal.com/paypalme/nguyenanhung](https://www.paypal.com/paypalme/nguyenanhung)

## Install

Step 1: Install packages

```shell
composer require nguyenanhung/nusoap
```

Step 2.1: Init to Project if PHP <= 7.0

```php
<?php 
require '/your/to/path/vendor/autoload.php';
use nguyenanhung\MyNuSOAP\nusoap_client;
$client = new nusoap_client();
```

Step 2.2: Init to Project if PHP >= 7.0

```php
<?php 
require '/your/to/path/vendor/autoload.php';
use nguyenanhung\MyFixNuSOAP\nusoap_client;
$client = new nusoap_client();
```

## Contact

If any question & request, please contact following information

| Name        | Email                | Skype            | Facebook      |
|-------------|----------------------|------------------|---------------|
| Hung Nguyen | dev@nguyenanhung.com | nguyenanhung5891 | @nguyenanhung |

From Hanoi with Love <3
