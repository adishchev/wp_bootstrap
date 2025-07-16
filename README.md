#  How to use
```console
git clone https://github.com/adishchev/wp_bootstrap.git <DIR>
cd <DIR>/ && rm -rf .git/
cp .env.example .env
```
## Define your variables
```console
vim .env
```
## Install dependencies
```console
composer install --no-dev
```
## To install a plugin use this format:
```console
composer require "wpackagist-plugin/the-events-calendar:*"
```
## To install a theme use this format:
```console
composer require "wpackagist-theme/:"
```
