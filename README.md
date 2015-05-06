# php-zf2-module-public-asset-symlink-generator
This PHP CLI script allows ZF2 modules to have routable public asset folders. Urls like /module/rods-zf2-module/css/style.css will map to /vendor/rod/RodsZf2Module/public/css/style.css This is accomplished by creating symlinks. This script must run from your ZF2 project root folder. This script is similar to the Symfony 2 command  "php app/console assets:install"..
 
