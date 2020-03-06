Comment démarrer avec KeepLink (KL) ?
==

Cette page explique comment démarrer avec KL sur la base d'un exemple basique, mais fait appel à toutes les fonctionnalitées nécessaires à la création d'application plus élaborées.

__Remarque :__ Les concepts clefs de KL (__Item, Link, Type, Property__) sont volontairement nommés en Anglais (et en __gras__) et les concepts du modèle que l'on va construire sont volontairement nommés en Anglais (et en _italique_) 

List des fonctions :
* Créer un Item
* Créer un Link
* Naviguer un Link
* Classifier/typer un Item

Cliquer sur le boutton "Home" pour commencer ...
__Remarque :__ On est en <a href="https://github.com/iPlumb3r/KeepLink">mode</a> "Normal"

Créer un __Item__
-
Liste des étapes :

<table>
    <thead>
        <tr>
            <th>Action</th>
            <th>Result</th>
            <th>Comment</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Cliquer sur le boutton "+"</td>
            <td>Un champ "Name of the new Home" apparait</td>
            <td>Le champ porte ce nom car le contexte courant est "Home"</td>
        </tr>
        <tr>
            <td>Saisir dans le champ le nom de l'Item et cliquer sur "OK"</td>
            <td>L'Item correspondant est crée, il apprait sous "Home"</td>
            <td>ex : "Tim Berner Lee"</td>
        </tr>
       <tr>
            <td>Choisir une image et cliquer sur "Clos internet picture </td>
            <td>Et voilà !</td>
            <td>KL est un outil qui s'appui sur le visuel</td>
        </tr>
    </tbody>
</table>

Répéter cette opération pour un 2nd __Item__ (ex : "W3C")   
Maitenant que nous avont 2 __Items__ dans KL, nous allons pouvoir les relier avec un __Link__ ...

__Remarque__ : Lorsqu'on crée un __Item__ dans KL (Quand on est sous "Home" entout cas), il n'a pas de __Type__ ; c'est à dire que KL ne sais pas (pas encore en tout cas) que : 
* _Tim Berner Lee_ est une _Person_
* _W3C_ est une _Organization_

Créer un __Link__
-

Liste des étapes :
<table>
    <thead>
        <tr>
            <th>Action</th>
            <th>Result</th>
            <th>Comment</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Faire glisser "Tim Berner Lee" sous "W3C"</td>
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
            <th>Result</th>
            <th>Comment</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Cliquer sur "Tim Berner Lee"</td>
            <td>Il devient le nouveau contexte à la place de "Home" ; et on vois qu'il est relié à "W3C"</td>
            <td></td>
        </tr>
        <tr>
            <td>Cliquer sur "W3C"</td>
            <td>Il devient le nouveau contexte à la place de "Tim Berner Lee" ; et on vois qu'il est relié à ce dernier</td>
            <td></td>
        </tr>
    </tbody>
</table>

__Remarque__ : Lorsqu'on crée un __Link__ dans KL, il n'a - par defaut - pas de __Type__ ; c'est à dire que KL ne sais pas (pas encore en tout cas) que :
* Tim Berner Lee _is affilited to_ W3C
Oui que, dit "à l'envers" :
* W3C _affiliates_ Tim Berner Lee

Naviguer un __Link__
-

Liste des étapes :
<table>
    <thead>
        <tr>
            <th>Action</th>
            <th>Result</th>
            <th>Comment</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Cliquer sur "Tim Berner Lee"</td>
            <td>Il devient le nouveau contexte à la place de "Home" ; et on vois qu'il est relié à "W3C"</td>
            <td></td>
        </tr>
        <tr>
            <td>Cliquer sur "W3C"</td>
            <td>Il devient le nouveau contexte à la place de "Tim Berner Lee" ; et on vois qu'il est relié à ce dernier</td>
            <td></td>
        </tr>
    </tbody>
</table>

C'est la base de la navigation dans KL, on passe d'un contexte l'autre ...
... et à chaque fois on peux visualiser les éléments de ce contexte.

Le contexte courant s'affiche en haut (juste en dessous de la barre d'historique ...
... et ses éléments s'affiche en dessous. Et pour chaque élément : 
* La partie "3/4 droite" (qui contient du texte) représente l'élément lui-même
* La partie "1/4 gauche" (qui contient un icone) représente le lien entre l'élement du contexte et cet élement
Le nom 

Classifier/type un __Item__
-
Créer un nouvel __Item__ nommé _Person_

__Remarque :__ Pour cette étape, il est bécessaire de passer en <a href="https://github.com/iPlumb3r/KeepLink">mode</a> "Advanced"

Liste des étapes :
<table>
    <thead>
        <tr>
            <th>Action</th>
            <th>Result</th>
            <th>Comment</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Cliquer sur "Tim Berner Lee"</td>
            <td>Il devient le nouveau contexte à la place de "Home" ; et on vois qu'il est relié à "W3C"</td>
            <td></td>
        </tr>
        <tr>
            <td>Cliquer sur "W3C"</td>
            <td>Il devient le nouveau contexte à la place de "Tim Berner Lee" ; et on vois qu'il est relié à ce dernier</td>
            <td></td>
        </tr>
    </tbody>
</table>
