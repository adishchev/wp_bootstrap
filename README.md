# To create new project
git clone https://github.com/adishchev/wp_bootstrap.git dir
cd dir/ && rm -rf .git/
composer install


# To install a plugin, use this format:
composer require "wpackagist-plugin/the-events-calendar:*"

# To install a theme, use this format:
composer require "wpackagist-theme/:"