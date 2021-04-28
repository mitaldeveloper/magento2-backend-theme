# BackendTheme module for Magento 2

The module for translate text of admin and can override all admin theme files.

## Installation

1. Go to Magento 2 root directory

2. Install module:

 
- Download [the latest version here](https://github.com//mitaldeveloper/magento2-backend-theme/archive/refs/heads/master.zip) 
- Extract `master.zip` file to root folder.
- Go to Magento root folder and run upgrade command line to install `Mital_BackendTheme`:



3. Enter following commands to enable module:


   php bin/magento module:enable Mital_BackendTheme
   php bin/magento setup:upgrade
   php bin/magento cache:clean


## Modify admin files

1. Go to app/design/adminhtml/Shah/default and override your filed

## Translate Texts for admin

1. Go to app/code/Mital/BackendTheme/i18n. Add your language file and add your text in csv file
