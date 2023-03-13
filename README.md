# Installation de Wordpress
Ce fichier Readme contient les instructions d'installation de l'application WordPress sur votre serveur. Suivez attentivement les étapes ci-dessous pour une installation réussie.

## Prérequis
Avant de commencer l'installation de WordPress, vous devez vous assurer que votre environnement de serveur répond aux exigences suivantes :

PHP version 7.4 ou supérieure
MySQL version 5.6 ou supérieure OU MariaDB version 10.1 ou supérieure
Apache ou Nginx serveur web
Accès à un terminal en ligne de commande
Accès à un navigateur web
## Étapes d'installation
Téléchargez la dernière version de WordPress à partir du site officiel de WordPress (https://wordpress.org/download/).
Décompressez le fichier zip téléchargé sur votre serveur web à l'emplacement souhaité.
Créez une nouvelle base de données MySQL ou MariaDB pour WordPress à l'aide de votre interface d'administration de base de données préférée. Notez les informations suivantes : nom de la base de données, nom d'utilisateur de la base de données et mot de passe de la base de données.
Renommez le fichier wp-config-sample.php dans le dossier WordPress à wp-config.php.
Ouvrez le fichier wp-config.php dans un éditeur de texte et modifiez les informations de connexion de la base de données en remplaçant les valeurs suivantes :
database_name_here par le nom de la base de données que vous avez créée précédemment.
username_here par le nom d'utilisateur de la base de données que vous avez créé précédemment.
password_here par le mot de passe de la base de données que vous avez créé précédemment.
localhost par l'adresse de l'hôte de votre base de données (si vous utilisez un autre hôte).
Enregistrez le fichier wp-config.php.
Accédez au site WordPress dans votre navigateur web en accédant à l'URL correspondant au dossier WordPress sur votre serveur. Si vous avez installé WordPress dans le dossier racine de votre serveur, l'URL sera http://votredomaine.com. Si vous avez installé WordPress dans un dossier nommé wordpress, l'URL sera http://votredomaine.com/wordpress.
Suivez les instructions d'installation affichées dans votre navigateur pour terminer l'installation de WordPress.
