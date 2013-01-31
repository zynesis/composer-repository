#Zynesis Composer Repository

Zynesis own Composer repository for in-house use with forked or non-open packages, or semi-open packages that we do not want to pollute Packagist.

http://zynesis.github.com/composer-repository/

## Set up

1. Set up Composer
1. `composer install` to install the dependencies of satis.

## Update

1. `bin/compile build`
2. Copy the content in `gh-pages` into [`gh-pages` branch](https://github.com/zynesis/composer-repository/tree/gh-pages) of this repository.
