**Squelette Globale**

**Clés du squelette ajoutées manuellement:**   
*Exemple : Nom de la clé (type) Description*

(*Respecter la langue original du document*)


* Annotateur (nombre) numéro d'anonymat
* PAuteur (String) Prénom 
* NAuteur  (String) Nom 
* TypeDeMail (CDD, CDI, Stage, Evenement, These-HdR, PostDocs, Formations, Autre)
* LienExtrene (boolean) Le mail contient un lien externe
* DureeM (nombre) Exprimé en mois (*N'en remplir qu'un*) valable pour un contrat ou un événement
* DureeJ (nombre) Exprimé en jours (*N'en remplir qu'un*)valable pour un contrat ou un événement
* DatedeDebut (date format aaaa/mm/jj) ex 2015/01/28 valable pour un contrat ou un événement
* Renouvelable (boolean) 
* PContact (string) Prénom de la personne à contacter
* NContact (string) Nom de la personne à contacter
* Langue (string) fr / en 
* Institut (string) Abréviation en Majuscules
* Equipe  (string) Nom de l'unité de recherche ou de l'équipe
* Ville (string) 
* Tags (string) sans les crochets, sauf le tag bioinformatique
* Motscles (String) déterminés à partir du corps du message
* CompetencesProg (liste) Languages de programmation attendus, séparés par une tabulation


**Informations récupérés automatiquement : **
* IdMail (nombre)
* Date d'envoi (date) 
* Sujet du mail (string)



Définir un champs vide : null 

Format des fichiers annotés : 
* Textuel (TSV) (Éviter d'utiliser Word)
* Séparateur : Tabulation


Pour les mails ne contenant que le lien : 
* Si le lien est vers la SFBI : ouvrir le lien et réutiliser les métadonnées fournies / analyser le contenu du document.
* Si le lien n'est pas vers la SFBI : Ne pas ouvrir mais annoter à partir du mail
