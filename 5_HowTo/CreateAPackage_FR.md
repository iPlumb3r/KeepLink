Comment créer un package ?
==

KeepLink permet de créer différents types de Package :
* Package "Collaboratif"
* Package "Static"
* Package "One-Off"

__Remarque__ : Le niveau d'utilisateur requis n'est pas le même pour tous les types de Package.   
Vous trouverez <a href="https://github.com/iPlumb3r/KeepLink/blob/master/5_HowTo/ChangeUserLevel_FR.md">ici</a> les instructions pour changer de niveau d'utilisateur.

Package "Collaboratif"
-
Les caractéristiques de ce type de Package sont les suivantes : 
* Niveau d'utilisateur requis : Normal
* Localisation du menu : Cliquer sur un Item => Menu "Share Item ..." / "Create a collaborative Item"
* Mode de définition : Ajout des Items les uns après les autres
* Mode de réalisation : A chaque "Build", un "Delta" est créé
* Mode d'utilisation : Celui qui reçois le Package peut ajouter d'autre Items nouveaux, mais également supprimer des Items existants (=> MAIS cela les supprimera chez tous les collaborateurs, y compris l'émetteur du Package lors de l'application des mises à jour)
* Avancé : Possibilité de spécifier l'inclusion d'un Package "Static"

Package "Static"
-
Les caractéristiques de ce type de Package sont les suivantes : 
* Niveau d'utilisateur requis : Packager
* Localisation du menu : Menu "Settings" / "Packages" => Boutton "+"
* Mode de définition : Via une "recette" à base d'Item "inclus" et de "niveaux" d'inclusion
* Mode de réalisation : A chaque "Build", tout les Items sont regénérés
* Mode d'utilisation : Celui qui reçois les Items ne peux PAS les supprimer individuellement (=> Il peut juste "dés-installer" le Package dans son intégralité).


Package "One-Off"
-
Les caractéristiques de ce type de Package sont les suivantes : 
* TO-BE-COMPLETED
