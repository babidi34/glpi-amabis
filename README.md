# glpi-amabis

- VM Debian sur AWS EC2

- Base de données MySQL sur RDS

- Projet GLPI sur la VM Debian (serveur apache2) connecté à la base de Données MySQL et les sources sont stocké sur un bucket du service AWS S3

- site glpi : https://glpi-kb.tk    |  certificat let'sEncrypt pour le HTTPS  | La configuration d'Apache redirige automatiquement vers le port 443

- Sauvegarde Restic de  /{etc,var,home} dans /tmp/backup  |  Je n'ai utiliser que restic client car avec la version gratuite d'AWS je n'ai pas le droit d'avoir 2 VM allumées en même temps
