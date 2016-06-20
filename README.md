## SQL Anywhere &copy; PHP extension

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
