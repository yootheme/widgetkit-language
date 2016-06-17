![Widgetkit](https://img.shields.io/badge/Widgetkit-v2.7.4-green.svg?style=flat) ![Joomla](https://img.shields.io/badge/Joomla!-Compatible-yellow.svg?style=flat) ![Wordpress](https://img.shields.io/badge/Wordpress-Compatible-yellow.svg?style=flat)

## Overview
This project contains translation files for [Yootheme Widgetkit 2](https://yootheme.com/widgetkit). It allows you to work with Widgetkit in your native language. Yootheme provides only limited language support and has an opinion that users should use only English language, because in this case it's easier to communicate between Yootheme users when they speak one language and see the identical UI. That's why they don't accept pull requests for complete translations. This project's idea is to provide a complete up to date translation of the Widgetkit. 

## Version compatibility
The translation files provided in this project are compatible with Widgetkit 2, version 2.7.4. In most cases you may use the translation with earlier versions of Widgetkit 2.

## How to install translation
Find the translation file that refers to language you are interested in. For example, use `de_DE.json` for German language. Copy the file to the `languages` folder of the Widgetkit on your website:

* **For Joomla** copy the file into the directory `/administrator/components/com_widgetkit/languages/`
* **For WordPress** copy the file into the directory `/wp-content/plugins/widgetkit/languages/`

If a file already exists in the specified directory, then replace it. For safety reasons, it's better to make a copy of the original file before you replace it.

**Attention:** never copy, replace or update the `en_GB.json` file from this project! This file is used for translations and is not intended to be copied. The English language is already built in the Widgetkit. 

## Widgetkit updates
If you update the Widgetkit on your website, then the translation files will be overwritten and you will loose the translation. In this case, please, install the translation file again from this project.

## How to contribute
Read more about how to clone (fork) a repository in the [Github's manual](https://help.github.com/articles/fork-a-repo/).

### How to improve translation
Some language files may have incomplete translations or you may suggest a better translation. In this case update the appropriate json file of your language with correct translation strings.

### How to add new missing language
The `en_GB.json` file contains the original complete list of all translations. Copy the contents of this file into the new one that will contain translation for your language. The new file must have an appropriate name for your language in format `xx_XX.json`. Translate all the required strings, then make a call for a merge request to propose your changes into this repository.

### Translation rules
Translate only the strings that are on the right side of the semicolon on each line. For example, the original line in `en_GB.json` file contains a string:

``
"Icon Medium": "Icon Medium"
``

You should translate only the right part. For example, the German version of this string will be:

``
"Icon Medium": "Mittleres Symbolbild"
``

The words that are delimited by `%` character must be copied into the translated text "as is", for example, in the following string:

``
Posted in %categories%
`` 

all words must be translated except `%link%` which should be copied as is and placed in the correct position in the translated string. For example, the German translation of the string above will be:

``
Veröffentlicht in %categories%
``

### The Transifex
[Transifex](https://www.transifex.com) is a great tool for translation. However, translating non open-source project (Widgetkit) requires creating a paid project. If someone is willing to contribute by providing a paid Transifex project, then, it would greatly improve the speed, comfort and ease of translation process. After that you may add [me](https://www.transifex.com/user/profile/Limarlav/) into the project as a Manager or Coordinator.