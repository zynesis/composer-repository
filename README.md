#Zynesis Composer Repository

Zynesis own Composer repository for in-house use with forked or non-open packages, or semi-open packages that we do not want to pollute Packagist with.

http://zynesis.github.io/composer-repository/

## Set up

1. Set up Composer
1. `composer install` to install the dependencies of satis.

## Update

1. Edit `satis.json` and add/remove repositories in `master branch`.
2. `bin/satis build`
3. After done process, checkout to `[gh-pages](https://github.com/zynesis/composer-repository/tree/gh-pages) branch`.
3. Copy the content inside the `gh-pages folder`. (Normally, only have 2 files: index.html and packages.json)
4. Paste to root directory of `gh-pages branch`.