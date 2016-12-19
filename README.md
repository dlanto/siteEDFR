# siteEDFR

#Version : 
2.0

#Installation :
- A l'aide de mySQL, importez la base de données à l'aide du fichier bdd.sql. L'utilisateur par défaut est "root" mais peut être modifié dans le fichier conf.php.
- Dans la console windows rentrez la commande suivante (nécessite composer):
composer create-project -s dev zendframework/skeleton-application path/to/install

- il est nécessaire d'installer les packages :
Zend\I18n
Zend\Form
Zend\InputFilter
Zend\Filter
Zend\Hydrator
Zend\Db
Zend\Router
Zend\Validator

- exemple d'une commande pour installer un package :
composer require zendframework/zend-db


- modifiez le nom de la base de données et le nom d'hôte dans le fichier : config/autoload/global.php pour qu'ils correspondent à votre configuration.

- copier le dossier siteEDFR sur votre serveur web.

#Utilisation :
Pour afficher le site, on utilise : Localhost/siteEDFR/public/album

(localhost change en fonction du nom d'hote virtuel que vous utiliserez)
