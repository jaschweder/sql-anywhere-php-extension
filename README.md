SQL Anywhere &copy; PHP extension

## Building this extension

```
// clone and go to the cloned folder
git clone git://github.com/jaschweder/sql-anywhere-php-extension
cd sql-anywhere-php-extension

// run phpize to create default files
phpize

// configure the installation, see ./configure --help for more options
./configure

// run make install in parallel with "number of processors" + 1 jobs
make -j$(($(nproc)+1))

// install the extension
sudo make install
```

## License

see [license](https://github.com/jaschweder/sql-anywhere-php-extension/blob/master/license.txt) file
