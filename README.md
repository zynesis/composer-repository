#Zynesis Composer Repository

Zynesis own Composer repository for in-house use with forked or non-open packages, or semi-open packages that we do not want to pollute Packagist with.

http://zynesis.github.com/composer-repository/

## Set up

1. Set up Composer
1. `composer install` to install the dependencies of satis.

## Update

1. Edit `satis.json` and add/remove repositories.
2. `php bin/compile build`
3. Copy the content in `gh-pages` into [`gh-pages` branch](https://github.com/zynesis/composer-repository/tree/gh-pages) of this repository.
