Comment démarrer avec KeepLink (KL) ?
==

Cette page explique comment démarrer avec KL sur la base d'un exemple basique, mais qui fait appel à toutes les fonctionnalitées nécessaires à la création d'applications personnelles ou professionelles plus élaborées (Cf quelques exemples <a href="https://github.com/iPlumb3r/KeepLink/blob/master/ReadMe_FR.md">ici</a>.

__Remarque :__ Les concepts clefs de KL (__Item, Link, Type, Property__) sont volontairement nommés en Anglais (et en __gras__) et ainsi que les concepts du modèle que l'on va construire (qui sont eux en _italique_). 

Liste des fonctions présentées sur cette page :
* Créer un __Item__
* Créer un __Link__
* Naviguer un __Link__
* Classifier/typer un __Item__ (Explicitement)
* Classifier/typer un __Item__ (Implicitement)
* Définir un __Type__ de __Link__
* Définir une __Property__ sur un __Type__ d'__Item__
* Définir une __Property__ sur un __Type__ de __Link__

__(WORK IN PROGRESS ...)__

__Remarque :__ Pour l'instant, on est en <a href="https://github.com/iPlumb3r/KeepLink">mode</a> "Normal"

Cliquer sur le boutton "Home" pour commencer ...   

Créer un __Item__
-
Liste des étapes :

<table>
    <thead>
        <tr>
            <th>Action</th>
            <th>Resultat</th>
            <th>Commentaire</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Cliquer sur le boutton "+"</td>
            <td>Un champ "Name of the new Home" apparait</td>
            <td>Le champ porte ce nom car le contexte courant est "Home"</td>
        </tr>
        <tr>
            <td>Saisir "Tim Berner Lee" dans le champ le nom de l'Item et cliquer sur "OK"</td>
            <td>L'Item correspondant est crée, il apprait sous "Home"</td>
            <td></td>
        </tr>
       <tr>
            <td>Choisir une photo de Tim et cliquer sur "Close internet picture"</td>
            <td>Et voilà !</td>
            <td>KL est un outil qui s'appui sur le visuel en permanence</td>
        </tr>
    </tbody>
</table>

Répéter cette opération pour un 2nd __Item__ (ex : "W3C")

__Remarque__ : Lorsqu'on crée un __Item__ dans KL (Quand on est sous "Home" en tout cas), il n'a pas de __Type__ ; c'est à dire que KL ne sais pas (pas encore en tout cas) que : 
* _Tim Berner Lee_ est une _Person_
* _W3C_ est une _Organization_

Maintenant que nous avons 2 __Items__ dans KL, nous allons pouvoir les relier avec un __Link__ ...

Créer un __Link__
-

Liste des étapes :
<table>
    <thead>
        <tr>
            <th>Action</th>
            <th>Resultat</th>
            <th>Commentaires</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Faire glisser "Tim Berner Lee" sur "W3C"</td>
            <td>Un lien est crée entre ces 2 Item, visible en haut à gauche dans la barre d'historique</td>
            <td>Ou le contraire, ça n'a pas vraiment d'importance ;-)</td>
        </tr>
        <tr>
            <td>Et c'est tout !</td>
            <td></td>
            <td></td>
        </tr>
    </tbody>
</table>
<table>
    <thead>
        <tr>
            <th>Action</th>
            <th>Resultat</th>
            <th>Commentaire</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Cliquer sur l'Item "Tim Berner Lee"</td>
            <td>Il devient le nouveau contexte à la place de "Home" ; et on vois qu'il est relié à "W3C"</td>
            <td></td>
        </tr>
        <tr>
            <td>Cliquer sur l'Item "W3C"</td>
            <td>Il devient le nouveau contexte à la place de "Tim Berner Lee" ; et on vois qu'il est relié à ce dernier</td>
            <td></td>
        </tr>
    </tbody>
</table>

__Remarque__ : Lorsqu'on crée un __Link__ dans KL, il n'a pas - par défaut - de __Type__ ; c'est à dire que KL ne sais pas (pas encore en tout cas) que :
* Tim Berner Lee _is affiliated to_ W3C   
Oui que, dit "à l'envers" :   
* W3C _affiliates_ Tim Berner Lee

Naviguer un __Link__
-

Liste des étapes :
<table>
    <thead>
        <tr>
            <th>Action</th>
            <th>Resultat</th>
            <th>Commentaire</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Cliquer sur l'Item "Tim Berner Lee"</td>
            <td>Il devient le nouveau contexte à la place de "Home" ; et on vois qu'il est relié à "W3C"</td>
            <td></td>
        </tr>
        <tr>
            <td>Cliquer sur l'Item "W3C"</td>
            <td>Il devient le nouveau contexte à la place de "Tim Berner Lee" ; et on vois qu'il est relié à ce dernier</td>
            <td></td>
        </tr>
    </tbody>
</table>

C'est la base de la navigation dans KL, on passe d'un contexte l'autre ...   
... et à chaque fois on peux visualiser les __Items__ associé à ce contexte.

Le contexte courant s'affiche en haut (juste en dessous de la barre d'historique ...   
... et ses __Items__ s'affiche en dessous. Et pour chaque __Item__ : 
* La partie "3/4 droite" (qui contient du texte) représente l'__Item__ lui-même
* La partie "1/4 gauche" (qui contient un icône) représente le __Link__ entre l'__Item__ du contexte et cet __Item__
La sémantique du lien entre l'__Item__ "source" et l'__Item__ "cible" apparait entre ces 2 parties

Classifier/type un __Item__ (Explicitement)
-
Créer un nouvel __Item__ nommé _Person_ (En utilisant la fonction vu précédemment "Créer un __Item__")

__Remarque :__ Pour cette étape, il est nécessaire de passer en <a href="https://github.com/iPlumb3r/KeepLink">mode</a> "Advanced"

Liste des étapes :
<table>
    <thead>
        <tr>
            <th>Action</th>
            <th>Resultat</th>
            <th>Commentaire</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Cliquer sur l'Item "Person"/</td>
            <td>Un menu apparait</td>
            <td></td>
        </tr>
        <tr>
            <td>Cliquer l'entré "Show all properties"</td>
            <td>Un menu apparait</td>
            <td></td>
        </tr>
        <tr>
            <td>Cliquer l'entrée "Is a type"</td>
            <td>L'Item "Person" est maintenant un Type/td>
            <td></td>
        </tr>
        <tr>
            <td>Faire glisser "Tim Berner Lee" sur "Person"</td>
            <td>Un Link "is a" est créé entre "Tim Berner Lee" et "Person"</td>
            <td></td>
        </tr>
    </tbody>
</table>

Nous venons de "dire" à KL que "Tim Berner Lee" est une _"Person"_ en ayant défini "Person" comme un __Type__ au préalable (puis en ayant associé l'un à l'autre)   
Nous allons maintenant "dire" à KL que W3C est une _"Organization"_ en faisant l'inverse ; c'est à dire en définissant un lien "is a" entre les 2 (c-a-d sans définir explicitement que _"Organization"_ est un __Type__).

Classifier/typer un __Item__ (Implicitement)
-

Créer un nouvel __Item__ nommé _Organzation_ (En utilisant la fonction vu précédemment "Créer un __Item__")
Liste des étapes :
<table>
    <thead>
        <tr>
            <th>Action</th>
            <th>Resultat</th>
            <th>Commentaire</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Cliquer sur l'Item "Organization"</td>
            <td>Un menu apparait</td>
            <td></td>
        </tr>
        <tr>
            <td>Faire glisser "W3C" sur "Organization"</td>
            <td>Un Link - quelconque - (dit "simple link") est créé entre "W3C" et "Organization"</td>
            <td></td>
        </tr>
        <tr>
            <td>Cliquer sur lien qui vient d'être créé"</td>
            <td>Un menu apparait</td>
            <td></td>
        </tr>
        <tr>
            <td>Sélectionner l'option "W3C i as Organization"</td>
            <td>L'Item "Organization" est "de facto" défini comme étant un Type</td>
            <td>Ce que vous pouvez vérifier en cliquant du "Organization", puis menu "Show all properties" et regardez l'interrupteur "Is a type" qui doit être activé</td>
        </tr>
    </tbody>
</table>

Définir un __Type__ de __Link__ (et l'utiliser)
-
__Remarque :__ Pour cette étape, il est nécessaire de passer en <a href="https://github.com/iPlumb3r/KeepLink">mode</a> "Designer"

Liste des étapes :
<table>
    <thead>
        <tr>
            <th>Action</th>
            <th>Resultat</th>
            <th>Commentaire</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Ouvrir le menu "Tools / Design / Link" et appuyer sur "+"</td>
            <td>Un champ "Name of the new Link" apparait</td>
            <td></td>
        </tr>
        <tr>
            <td>Entrer "affiliated to" et appuyer sur "OK"</td>
            <td>Un nouveau Type de Link est créé</td>
            <td></td>
        </tr>
        <tr>
            <td>Faire glisser Link  "affiliated to" sur le Type d'Item "Person"</td>
            <td>Un lien ("affiliated to" starts from "Person") est créé</td>
            <td></td>
        </tr>
        <tr>
            <td>Faire glisser Link "affiliated to" sur le Type d'Item "Organization"</td>
            <td>Un lien ("affiliated to" ends to "Organization") est créé</td>
            <td></td>
        </tr>
        <tr>
            <td>Cliquer sur la Property "Reverse link name" du Link "affiliated to"</td>
            <td>Un champ "Reverse link name" apparait</td>
            <td></td>
        </tr>   
        <tr>
            <td>Saisir dans ce champ "affiliates" et cliquer sur "OK"</td>
            <td>Une sémantique de lien est maintenant disponible dans les 2 sens</td>
            <td></td>
        </tr>  
        <tr>
            <td>Sélectionner "Tim Berner Lee" (dans la barre d'historique par exemple)</td>
            <td>L'Item "Tim Berner Lee" devient le context courant</td>
            <td></td>
        </tr>
         <tr>
            <td>Swaper vers la gauche le texte "W3C"</td>
            <td>Un menu apparait</td>
            <td></td>
        </tr>
        <tr>
            <td>Selectionner "Edit Link"</td>
            <td>Un menu apparait</td>
            <td></td>
        </tr>
        <tr>
            <td>Choisir la sémantique "Tim Berner Lee" affiliated to "W3C</td>
            <td>KL sait maintenant que TBL travaille pour le W3C ;-)</td>
            <td></td>
        </tr>
        <tr>
            <td>Sélectionner l'Item "W3C"</td>
            <td>On doit pouvoir observer cette même relation, mais avec la sémantique inverse</td>
            <td></td>
        </tr>
    </tbody>
</table>

Définir une Property sur un Type d'Item
-
Liste des étapes :
<table>
    <thead>
        <tr>
            <th>Action</th>
            <th>Resultat</th>
            <th>Commentaire</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Ouvrir le menu "Tools / Design / Properties / Dates" et appuyer sur "+"</td>
            <td>Un champ "Name of the new Date" apparait</td>
            <td>On aurait pu tout aussi bien créer un autre type de Property : Text, Number, ... </td>
        </tr>
        <tr>
            <td>Entrer "birth date" et appuyer sur "OK"</td>
            <td>Une nouvelle Property est créé</td>
            <td></td>
        </tr>
        <tr>
            <td>Faire glisser la Property  "birth date" sur le Type d'Item "Person"</td>
            <td>Un lien ("birth date" defines "Person") est créé</td>
            <td></td>
        </tr>
        <tr>
            <td>Sélectionner "Tim Berner Lee" (dans la barre d'historique par exemple)</td>
            <td>L'Item "Tim Berner Lee" devient le contexte courant et on peut constater qu'une Property "birth date "est disponible dans la liste de ses propriétés</td>
            <td></td>
        </tr>

    </tbody>
</table>


Définir une Property sur un Type de Link
-

Liste des étapes :
<table>
    <thead>
        <tr>
            <th>Action</th>
            <th>Resultat</th>
            <th>Commentaire</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Ouvrir le menu "Tools / Design / Properties / Dates" et appuyer sur "+"</td>
            <td>Un champ "Name of the new Text" apparait</td>
            <td></td>
        </tr>
        <tr>
            <td>Entrer "hiring date" et appuyer sur "OK"</td>
            <td>Une nouvelle Property est créé</td>
            <td></td>
        </tr>
        <tr>
            <td>Faire glisser la Property  "birth date" sur le Type d'Linf "affiliated to"</td>
            <td>Un lien ("hiring date" defines "affiliated to") est créé</td>
            <td></td>
        </tr>
        <tr>
            <td>Sélectionner "Tim Berner Lee" (dans la barre d'historique par exemple)</td>
            <td>L'Item "Tim Berner Lee" devient le contexte courant et on peut constater qu'une Property "hiring date "est disponible sur le lien entre "Tim Berner Lee" et "W3C"</td>
            <td></td>
        </tr>
    </tbody>
</table>

Voilà un mini-modèle qui peut être étendu à loisir ou bien adapté en fonction des besoins de chaque application ...

Pour allez plus loin...
-
KL supporte la fonctionnalité de multi-typing, ce qui signifie qu'il est possible par exemple : 
* De créer un __Item__ "Oxford University Alumni"
* De faire de cet __Item__ un __Type__
* D'associer "Tim Berner Lee" à ce __Type__ via un __Link__ "is a"
* De créer 2 __Property__ de type Date : "study start date" et "study end date"
* D'associer ces __Properties__ au _Type_ "Oxford University Alumni" via un __Link__ "defines"
Alors elle seront disponible sur l'Item "Tim Berner Lee" car il est à la fois :
* Une "Person"
&
* Un "Oxford University Alumni"

Globalement, cette fonctionnalité de multi-typing permet de "voir" un même ensemble d'__Item__ selon des "prismes" différents

Pour allez plus loin...
-
Il existe dans KL des fonctionnalités qui permettent de faire des calcul avec les __Property__ et/ou de propager des propriété le long de certaines sémantiques de __Link__ ...

(To Be Completed)

