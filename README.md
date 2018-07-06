Default currency per language - Opencart extension
===============

This extension provide to set default currency per language. Along with this all other currencies will be disabled.
For example: if you have two languages (English and German) and two currencies (USD, EUR) and set EUR to be default currency for German languge then the currency switcher will be disabled in German version.
Except that you can set different currency for different language you can also set the same currency for several languages:
English -> USD, Bulgarian - BGN, German -> EUR, Italian -> **also EUR** Russian -> RUB, and etc.

## Requirements:
* ![vQmod for OpenCart](https://github.com/vqmod/vqmod/releases)

## Notes:
The module is tested on:

* OpenCart 2.2.0.0
* OpenCart 2.3.0.2

But it may work on all 2.x versions

## Install:
1. First, you have to run the SQL query in your database provided with the module (install.sql) by using some software for database management (phpMyAdmin, MySQL Workbench) or through command-line.
2. Copy **vqmod** folder to your OpenCart installation. Make sure to keep the OpenCart folders structure intact.

## Configuration:
1. Go to **System > Localisation > Languages > Edit some language**
2. Now you can see the **Default currency** dropdown.
3. Choose the currency for this language and click **Save**.
![Default currency](https://image.ibb.co/jbZkrd/default_currency.png)