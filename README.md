# Flarum Brazilian Portuguese Language Pack (pt-BR)

https://discuss.flarum.org

Complete; Flarum version **0.1.0-beta8**. Portuguese (Brazil) language pack. Português (Brasil), pt-BR

A [little helper script](https://gist.github.com/renato/f584a99b6eb2a50a593b0f427616fbc7) is used to to diff these files with the updated english strings.

## Installation:

### Using composer (recommended):

Flarum uses Composer to manage its dependencies and extensions. The brazilian Portuguese language pack is available on Packagist and can be managed that way. Make sure that Composer is installed on your machine, then run the following command in the location where Flarum is installed:

`composer require renatoat/flarum-ext-brazilian-portuguese`

The same command can be used to update independently the brazilian Portuguese language pack, without updating anything else. Note that because the brazilian Portuguese language pack will be added as a Flarum's dependency, it will also be automatically updated when updating Flarum and its dependencies via Composer.

### Using zip:

1. Download the file https://github.com/renato/flarum-ext-brazilian-portuguese/archive/master.zip
2. Unzip it in `flarum_root_directory/extensions/`
3. Go to the Administration panel, then "Extensions" tab and enable the "Brazilian Portuguese" language pack extension.
4. Go to "Basics" tab and change the language. `Português (Brasileiro)(pt-BR)`.

### Using git:

1. Via command line go to `cd flarum_root_directory/extensions/` directory.
2. Clone this repository with the command `git clone https://github.com/renato/flarum-ext-brazilian-portuguese.git`.
3. Go to the Administration panel, then "Extensions" tab and enable the "Brazilian Portuguese" language pack extension.
4. Go to "Basics" tab and change the language. `Português (Brasileiro)(pt-BR)`.
