# portefeuille_SIO
Actualisation locale (Lycée Rostand, Caen) de l'application de JF Pujol reprise par David Roumanet

Ajouts suivants dans l'application : 
  - Situations : 
    * les situations sont signalées aux enseignants d'informatique qui peuvent en retour signaler leurs commentaires
    * une alerte (en vert) apparaît dans l'interface utilisateur (prof/élève) quand une situation nécessite une intervention
    * en fin d'échange, les situations sont "visées" par l'enseignant.e (fin de l'interaction, possibilité de MAJ)
    * la déclaration de chaque situation peut être générée au format PDF (une seule page pour toutes rubriques)
  - Stages : 
    * Les stages sont déclarés sous forme de carnet de bord (informations nécessaires à l'établissement de la convention)
    * ils sont affectés pour le suivi à un.e enseigant.e (accès à tous les profs de la section)
    * ils font l'objet d'un enregistrement quotidien par le.la stagiaire avec un avis hebdomadaire. 
    * chaque semaine alimentée peut être générée en PDF pour diffusion au tuteur pro
    * le carnet de bord permet un échange entre référent (prof) et stagiaire (bug pour la sortie de l'onglet)
    * l'attestation de stage est générée en PDF en reprenant les situations déclarées dans le cadre Stage 1 ou 2
    * une page permet de consulter la liste des entreprises des stages précédents (par ville, année, département)
  - Notifications
    * Des notifications peuvent être déclarées par les enseignants pour signalement à une promotion (annonce de dates et échéances, etc)
    * Les notifications sont signalées (en orange) dans l'interface étudiant, elles doivent être "acquitées" pour disparaitre 
  - Comptes utilisateurs (menu Paramètres)
    * ils sont enrichis : 
      > pour les étudiants : adresses et  coordonnées de contact (nécessaires à l'établissement de l'attestation)
      > pour les enseignants : matière enseignées
  - Tableau de bord  : la page d'accueil est maintenant un tableau de bord présentant : 
    * pour les profs :
      + aux mois de stage (mai/juin ou janvier/février) la liste des stagiaires à suivre avec lien vers leur carnet de bord et stats sur l'alimentation hebdomadaire
      + la liste des situations à commenter suite à signalement par les étudiants
      + les stats sur les acquittements des notifications
    * pour les étudiants : 
      + aux mois de stage, les stats sur le remplissage hebdomadaire du carnet de bord
      + la liste des situations commentées par les enseignants et à rectifier
      + les notifications avec leur état d'acquittement
  - Synthèse
    * Le tableau de synthèse pour E6 est généré au format Excel (quelques bugs, nécessite une installation sous Debian 8)
  
