Partie 1

Q.1.1.1
Creation du user Lionel LEMARCHAND avec les attributs de directeur des ressources humaines et present dans le groupe grpusersdirectiondesressourceshumaines

Q.1.1.3

user kelly.rhameur supprimé du groupe grpusersdirectiondesressourceshumaines




Partie 2 





Q.2.1.2

preconisations:
- choix d un mot de passe fort
- securisation ssh avec clé

  Q .2.4.1

  bareos-dir (Director) :

Le composant Director est responsable de la coordination globale du système Bareos.
Il gère la configuration, le calendrier des sauvegardes, les pools de stockage, les volumes de sauvegarde, et la gestion des tâches de sauvegarde et de restauration.

bareos-sd (Storage Daemon) :

Le composant Storage Daemon gère le stockage physique des données de sauvegarde.
Il contrôle les pools de stockage, les volumes de sauvegarde, et est responsable de l'écriture et de la lecture des données vers et depuis les supports de stockage tels que disques, bandes, ou autres dispositifs.

bareos-fd (File Daemon) :

Le composant File Daemon est installé sur chaque machine que vous souhaitez sauvegarder.
Il est responsable de collecter les données à sauvegarder sur la machine locale et de les envoyer au Director via le Storage Daemon


Q.2.5.6

communication ssh
ICMP ( ping) 
