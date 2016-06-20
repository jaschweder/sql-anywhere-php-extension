## PHP 5.6 Sybase SQL Anywhere &copy; extension

[![Build Status](https://travis-ci.org/jaschweder/sql-anywhere-php-extension.svg?branch=master)](https://travis-ci.org/jaschweder/sql-anywhere-php-extension)

### Building this extension

```
git clone git://github.com/jaschweder/sql-anywhere-php-extension
cd sql-anywhere-php-extension
phpize
./configure
make -j$(($(nproc)+1))
sudo make install
```

### License

see [license](https://github.com/jaschweder/sql-anywhere-php-extension/blob/master/license.txt)
