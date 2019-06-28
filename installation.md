__Prérequis__

Le serveur doit disposer de PHP et Mysql dans des versions récentes. 
David Roumanet a réécrit le code MySql pour utiliser les fonctions _mysqli_.

__Problème__ : Pour faire fonctionner l'export Excel utilisant la bibliothèque PHPExcel (abandonnée depuis 2015), il faut un serveur PHP5.  On peut toutefois se passer de cette option et installer sur un serveur PHP7. Il faudrait faire un portage vers la bibliothèque PhpSpreadsheet qui remplace PhpExcel. 

__Procédure__

Les modifications apportées à l'application n'ont pas été intégrées dans le module d'installation. 
De même, la sauvegarde n'a pas été actualisée (elle est désactivée dans le menu prof/élève). 

L'installation de cette version suit les étapes suivantes : 
  - Recopier l'application fournie ici dans le dossier du serveur Web 
  - Donner les droits en écriture sur le dossier _../dirrw_
  - Implanter la base de données sur votre serveur Mysql avec le script fourni
  - Configurer le fichier _../dirrw/param/param.ini.php_ avec vos informations : 
    * $nomServeur="localhost";    _serveur mysql_
    * $loginAdminServeur="";      _compte mysql pour l'accès à la base_
    * $motPasseAdminServeur="";   _mot de passe du compte_
    * $nomBaseDonnee="portfolio"; _nom de la base_ __A adapter__
    * $prefixeTable="port_";      _préfixe des tables (on peut le modifier : non testé)_
    * $crypte=true;               _les mots de apsse des utilisateurs sont encodés en MD5_
    * $smtp=false;                _pas de serveur de messagerie utilisé pour l'envoi de mail_
    * $melContact="";
    * $lngmdp=9;
  - Se connecter avec le compte de base du script fourni (admin@lycee.fr / ABCD) et procéder à la création des promotions et comptes. 
  
  __Cadeau__ 
  
  Un lien est présent dans le menu prof/élève qui renvoie vers le Wiki de la section SIO de Rostand... C'est offert, c'est plaisir ;-)
  
