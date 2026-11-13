# Registre EPI — versions publiées

Ce dépôt ne contient que les versions du Registre EPI sous forme de fichiers zip (`releases/`) et le fichier `latest.json`, qui annonce la dernière version avec une signature numérique.

Le registre installé sur un serveur lit `latest.json`, vérifie la signature avec la clé publique intégrée à son code, et refuse toute version qui n'est pas signée par le mainteneur.

Le code source est dans un dépôt privé. Aucun mot de passe, aucune clé secrète et aucun fichier `config.php` ne se trouve ici.
