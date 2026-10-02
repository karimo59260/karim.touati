PME de 45 postes  alternance en service informatique  Mars 2026
CONTEXTE
Je suis en alternance dans le service informatique d'une PME. 
En mars on m'a indiquer qu'une assistante commerciale arrivait et que je devais lui préparer son poste pour le lundi suivant 9h.

DEMARCHES
Un ordinateur portable était revenu trois semaines plus tôt et je devais le réinitialiser pour la nouvelle commerciale.
J'ai tout d'abord copier les documents déjà présent sur le poste sur le serveur des fichiers et envoyer une copie au responsable.
J'ai réinstaller Windows 11 avec une clé USB que j'ai préparé avec l'outil de création de support MICROSOFT. 
Ensuite j'ai installer les logiciels standards de l'entreprise, j'ai joins le poste au domaine et j'ai créer le compte dans Active Directory avec les droits du groupe commerce.
J'ai aussi ajouter l'imprimante réseau et mis à jour la fiche du poste dans GLPI 10.0 avec un numéro de série et le nouveau nom de machine.
Pour finir je lui ai communiquer le mot de passe à son arrivée et lui ai demander de le changer.

RESULTATS
J'ai effacé 1,2 giga octet de données et l'ancien compte du salarié. J'ai installer le poste pour qu'il soit opérationnel le lundi matin.

PROBLEMATIQUE
J'avais deux façons de procéder
La première était plus rapide mais j'aurais du perdre les documents présent sur le poste.
J'ai préférer tout sauvegarder pour ensuite tout réinstaller afin de sécuriser les données.

OUTILS MOBILISEES
Clé USB
Outil de création MICROSOFT Windows 11
PC portable
GLPI 10.0

BILAN PERSONNEL
EN réalisant la suppression des fichiers je me suis rendu compte que j'aurais du vérifier la licence OFFICE afin d'éviter de perdre 40 min à la retrouver dans le portail administration.
