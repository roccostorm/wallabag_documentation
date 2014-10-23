# Téléchargement et installation
[Téléchargez la dernière version de wallabag](http://www.wallabag.org/download) et décompressez-la. Copiez les fichiers sur votre serveur web. 

## Pré-requis pour votre serveur web
* [PHP 5.3.3 ou plus](http://php.net/manual/en/install.php)
* [SQLite](http://php.net/manual/en/book.sqlite.php) ou [MySQL](http://php.net/manual/fr/book.mysql.php) ou [PostgreSQL](http://php.net/manual/en/book.pgsql.php)
* [XML pour PHP](http://php.net/xml)
* [PCRE](http://php.net/pcre)
* [Filtrage des données](http://php.net/manual/book.filter.php)
* [Tidy pour PHP](http://php.net/tidy)
* [cURL](http://php.net/curl)
* [allow_url_fopen](http://www.php.net/manual/en/filesystem.configuration.php#ini.allow-url-fopen)
* [gettext](http://php.net/manual/en/book.gettext.php)

Pour être sur que votre serveur possède tous les pré-requis, vous pouvez exécuter le fichier `wallabag_compatibility_test.php` qui se trouve dans le répertoire `install` de wallabag.

## Installation des dépendances
Pour pouvoir fonctionner, wallabag a besoin de dépendances. Pour les installer, vous devez utiliser `composer`. Dans votre dossier wallabag, exécutez les deux commandes suivantes :
```
curl -s http://getcomposer.org/installer | php
```
```
php composer.phar install
```

Si vous ne pouvez pas installer `composer` (dans le cas d'hébergement mutualisé par exemple), nous vous proposons un fichier [vendor.zip](http://wllbg.org/vendor) à décompresser dans votre répertoire wallabag.

## Installation de wallabag

...
