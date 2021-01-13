# blog_Symfony

A simple blog application made with the Symfony Framework

(In progress)

The "bin" folder
This folder contains the executables available in the project, whether those provided with the framework (the Symfony console) or those of the dependencies (phpunit, simple-phpunit, php-cs-fixer, phpstan).

The "config" folder
It contains all the configuration of your application, whether it is the framework, the dependencies (Doctrine, Twig) or the routes.

The "public" folder
By default, it only contains your application's front controller, the file whose responsibility is to receive all user requests.
(Only this folder should be accessible by a user).

The "src" folder
This is where your app is! Controllers, forms, event listeners, models, and all of your services should be in this folder. It is also in this folder that the "engine" of your application, the kernel, is located.

The "tests" folder
In this folder are the unit, integration and interface tests.
By default, the namespace for the tests folder is App \ Tests and the namespace for the src folder is App.

The "templates" folder
This folder contains the templates that are used in your project.

The "translations" folder
Symfony provides a component called Translation capable of handling many translation formats, including yaml, xliff, po, mo ... These files will be located in this folder.

The "var" folder
This folder contains three main things:
cache files in the cache folder;
log files in the log folder;
and sometimes, if the framework is configured to handle PHP sessions in the filesystem, we find the sessions folder.

The "vendor" folder
This folder contains your dependency loader (or "autoloader") and all the dependencies of your PHP project installed using Composer. Another way to find out about your dependencies is to use the "composer show" command.
