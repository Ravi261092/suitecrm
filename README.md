## SuiteCRM 7.8.20  LTS

### What's in this repository ###

This is the git repository for the SuiteCRM project.This repo is allowed to do customization in **SuiteCRM.**

### How to use it ###

you have to just clone this repo and move it to **/var/www/html/** and also change owner of our crm directory **sudo chown -R www-data:www-data <directory name>**.Make sure your mysql database already setup and change db config in **config.php** file inside in your crm directory.
After that hit this *http://yourServer/yourSuiteCRMDirectory/* this will redirect to login page *username* - *admin* and *password* - *admin* 

## Important ##

There are some files which not usable and not need to track so we just put in .gitignore file like -

/.htaccess*

/cache/*

!/cache/index.html

/custom/history/

/custom/modulebuilder/

/custom/working/

/custom/modules/*/Ext/

/custom/application/Ext/

/silentUpgrade*.php

/upload/*

!/upload/index.html

/upload_backup/

*.log

custom/

custom/history/*

custom/blowfish/*

custom/modulebuilder/*

custom/working/*

custom/modules/*/Ext/

custom/modules/unified_search_modules_display.php

modules/AOD_Index/Index/*

install/status.json

bower_components/

node_modules/

themes/SuiteP/css/*.map

themes/SuiteP/css/*/*.map

themes/SuiteP/css/*/color-palette.css

themes/SuiteP/css/*/variables.css

tests/_output/*


