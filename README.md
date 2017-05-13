# Gender Latin

Detects gender from person's name in Latin script.

## Dependency

Required dependency is `PHP extension Gender`.

## Usage

```php
use peterkahl\GenderLatin\GenderLatin;

$latGen = new GenderLatin;
$latGen->firstName = 'Gaétan';
$latGen->lastName  = '';
$latGen->country   = 'FR';

echo $latGen->getGender(); # M
```

## Acknowledgement

This library contains code authored by [Pete Warden](https://github.com/petewarden).
