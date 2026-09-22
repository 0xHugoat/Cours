# Cours commande Linux

## Fichiers

Créer un fichier vide : mkdir NomDuDossier

Afficher le contenu d'un fichier : cat NomDuDossier

Renommer ou déplacer un fichier : mv AncienNom NouveauNom

Copier un fichier : cp Fichier Destination

Supprimer un fichier : rm NomDuFichier

Ouvrir un fichier avec l'éditeur nano : nano NomDuFichier

Changer le propriétaire d'un fichier : sudo chown NouveauPropriétaire NomDuFichier

Changer le groupe d'un fichier : chgrp NomDuGroupe NomDuFichier

Changer le propriétaire ET le groupe en même temps : chown utilisateur:groupe NomDuFichier

Changer les permissions d'un fichier : chmod 755 NomDuFichier

Rendre un script exécutable : chmod +x NomDuScript.sh

Créer un lien symbolique : ln -s CibleOriginale NomDuLien

## Dossiers

Afficher le dossier courant : pwd

Changer de dossier : cd NomDuDossier

Revenir au dossier parent : cd ..

Revenir directement dans son dossier personnel : cd~

Créer un dossier : mkdir NomDuDossier

Créer un dossier et ses sous-dossiers en une seule commande : mkdir -p Dossier/SousDossier/SousSousDossier

Lister le contenu d'un dossier avec les détails et fichiers cachés : ls -la

Copier un dossier et tout son contenu : cp -r DossierSource DossierDestination

Supprimer un dossier vide : rmdir NomDuDossier

Supprimer un dossier non vide et tout son contenu : rm -rf NomDuDossier
