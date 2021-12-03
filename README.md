VAT number validator
====================

PHP library to validate VAT numbers.

Installation
------------

Open a command console, enter your project directory and execute the
following command to download the latest stable version of this library:

```bash
$ composer require wpovernight/vat-number-validator
```

This command requires you to have Composer installed globally, as explained
in the [installation chapter](https://getcomposer.org/doc/00-intro.md)
of the Composer documentation.

Basic usage
-----------

To validate a VAT number:

```php
use WPO\Component\VatNumberValidator\VatNumberValidator;

$validator = new VatNumberValidator;
$valid = $validator->validate('ATU37675002');
```

Origin
------

This library is the PHP rewrite of [original JavaScript library](http://www.braemoor.co.uk/software/vat.shtml) by Braemoor Software
Freebies. Original contributors are found [here](http://www.braemoor.co.uk/software/vatupdates.shtml).

License
-------

This library is under [MIT License](http://opensource.org/licenses/mit-license.php).
