# grumphp-php-check-syntax

Check if the file permissions match that you've required. Dont' use yet. Work in progress!!!

### grumphp.yml:
````yml
parameters:
    tasks:
        check_file_permissions: ~
    extensions:
        - wunderio\CheckFilePermissions\ExtensionLoader
````

### Composer

``composer require --dev wunderio/grumphp-file-permissions``
