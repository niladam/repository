# Laravel Implementation of Repository Pattern (forked from [LazyElePHPant/repository](https://github.com/LazyElePHPant/repository))

Laravel package to facilitate repository design pattern implementation across multiple projects.

This package is a forked version of [LazyElePHPant/repository](https://github.com/LazyElePHPant/repository), with the changes provided by [@calvinchiulele](https://github.com/calvinchiulele) in the pull request [#2](https://github.com/LazyElePHPant/repository/pull/2)

The reason behind this fork is that it looks like [@LazyElePHPant](https://github.com/LazyElePHPant) ignored or didn't have time to handle the pull request and i wanted to use this in a project of mine.

Contributing to this is welcome, but this is mainly for may own personal use. Since i didn't want to clash with lazy's namespacing, this fork's namespace has been changed.

Credits for this package (at least for now) are entirely [@LazyElePHPant](https://github.com/LazyElePHPant) and [@calvinchiulele](https://github.com/calvinchiulele).

## Installation

```
composer require niladam/repository
```

## Plain Repository Class

To generate a repository class without a specific model simply run the following command:

```
php artisan make:repository NameRepository
```

## Model Repository Class

To generate a repository class for a specific model you may specify by defining the `--model`:

```
php artisan make:repository NameRepository --model=User
```
