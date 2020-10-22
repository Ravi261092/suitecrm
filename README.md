## SuiteCRM 7.8.20  LTS

### What's in this repository ###

  This is the git repository for the SuiteCRM project.  Suitecrm is Customer Relationship Management (CRM) software application. The version of suitecrm in this repo is **SuiteCRM 7.8.20 LTS**. This repo is allowed to do customization in SuiteCRM.

### How to use it ###

Follow the below steps for setting up suitecrm
  1. You have to just clone this repo and move it to /var/www/html/
  2. Change the owner of crm directory by using command sudo chown -R www-data:www-data <directory name>
  3. Make sure your mysql database is already setup -
      
    a) If mysql Db is not set up , then in that case 1st set up an empty mysql db and then open the link in the browser  http://yourServer/yourSuiteCRMDirectory/install.php and fill details related to database. 
     
    b) If mysql Db is already ready , then simply change the configuration of database in config.php.
 
 4. After above successful steps open  http://yourServer/yourSuiteCRMDirectory/   in browser.  This will redirect to login page having username and password  (Default is admin:admin)

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


