# lum.uuid.php

## Summary

UUID generation methods.

## Classes

| Class                   | Description                                       |
| ----------------------- | ------------------------------------------------- |
| Lum\UUID                | A class with UUID methods.                        |

## Methods

All of the methods are static, and should be called as such.

| Method                          | Description                               |
| ------------------------------- | ----------------------------------------- |
| ```Lum\UUID::v3($ns,$name)```   | Generate a version 3 UUID.                |
| ```Lum\UUID::v4()```            | Generate a version 4 UUID.                |
| ```Lum\UUID::v5($ns,$name)```   | Generate a version 5 UUID.                |
| ```Lum\UUID::is_valid($uuid)``` | Is the string a valid UUID?               |

## Official URLs

This library can be found in two places:

 * [Github](https://github.com/supernovus/lum.uuid.php)
 * [Packageist](https://packagist.org/packages/lum/lum-uuid)

## Authors

- Andrew Moors
- Timothy Totten

## License

[MIT](https://spdx.org/licenses/MIT.html)
