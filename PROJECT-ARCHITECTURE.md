# References to the directory architecture

# CodeIgniter

```
project-root/
application/ # Contains your application logic
cache/ # Stores cached files
config/ # Keeps configuration files
controllers/ # All application controllers are defined here
core/ # Contains custom core classes that extend system files
helpers/ # This directory is used for user-defined helper functions
hooks/ # Used for custom hooks
language/ # Used to store language files for applications that use more than one language
libraries/ # Used to store custom created libraries
logs/ # Application log files are kept here
models/ # All application models should be defined here
third_party/ # This is used for custom many packages that you or other developers have created
views/ # Application views go into this directory
system/ # Contains the framework core files. It is not advised to make changes in this directory or put your own application code into this directory
user_guide/ # Contains the user manual for CodeIgniter
vendor/ # Contains composer packages source code
public_html/ # Browser-accessible portion of your web application, preventing direct access to your source code
images/
js/
index.php # This is the entry point into the application

```

# Bing Suggestion

[link](https://docs.php.earth/faq/misc/structure/)

```
project-root/
.git/ # Git configuration and source directory
assets/ # Uncompiled/raw CSS, LESS, Sass, JavaScript, images
bin/ # Command line scripts
config/ # Application configuration
node_modules/ # Node.js modules for managing front end
public/ # Publicly accessible files
index.php # Main entry point - front controller
...
src/ # PHP source code files
Controller/ # Controllers
...
templates/ # Template files
tests/ # Unit and functional tests
translations/ # Translation files
en_US.yaml
var/ # Temporary application files
cache/ # Cache files
log/ # Application specific log files
vendor/ # 3rd party packages and components with Composer
.gitignore # Ignored files and dirs in Git (node_modules, var, vendor...)
composer.json # Composer dependencies file
phpunit.xml.dist # PHPUnit configuration file

```
