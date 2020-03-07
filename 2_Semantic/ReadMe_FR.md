Sémantique
==

Quelques mots sur les __concepts__ (de base et dérivés) que KeepLink (KL) utilise

Concepts de base
-
A la base, KL utilise essentiellement les 3 __concepts__ suivants : 
* l'__Item__ => Item
* Le __Lien__ => Link
* Et le __Type__ => Type

__Remarque - très - importante__ : Il est a noter que dans KL, tout les __Liens__ sont - aussi - des __Items__    
(Ce qui dote KL d'une fonctionalité de "réification" par défaut)

Concepts dérivés
-
Le concept de __Type__ pouvant se combiner avec __Item__ et __Lien__, on obtient les __concepts__  suivants : 
* Le __Type d'Item__ => Item Type
* Le __Type de Lien__ => Link Type

Par ailleurs, KL utilise également le __concept__ de __Propriété__ ...   
... qui peut également se combiner avec __Type d'Item__ et __Type de Lien__ pour obtenir les __concepts__ suivants :
* La __Propriété (de type) d'Item__ => Item (Type) Property
* La __Propriété (de type) de Lien__ => Link (Type) Property

En tout rigueur, on doit distinguer :
* La __Propriété de Type d'Item__ (qui défini un __Type d'Item__) et la __Propriété d'Item__ (qui caractérise un __Item__ une fois renseignée)
* La __Propriété de Type d'Lien__ (qui défini un __Type de Lien__) et la __Propriété de Lien__ (qui caractérise un __Lien__ une fois renseignée)


Illustration
-
![ConceptModel](https://github.com/iPlumb3r/KeepLink/blob/master/images/ConceptualModel%40KeepLink.png)

Annexe
-
Cette section tente de faire un parallèle entre les __concepts__ manipulés par KL ...   
... et ceux utilisés par d'autres paradigmes provenant d'autres disciplines (e.g. : maths, IS-IT)

Remarque 1 : An Angamis uniquement   
Remarque 2 : Dans cette section, la différence est faite entre : 
* __item__ (un élément particulier de __Item__) et __Item__ (l'ensemble de tous les __item__ particulier) 

<table>
    <thead>
        <tr>
            <th>Concept / KL Paradigme</th>
            <th>item</th>
            <th>Type</th>
            <th>Link / Link Type</th>
            <th>Item</th>
            <th>Property</th>          
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Set Theory (Math)</td>
            <td>Element</td>
            <td>Set</td>
            <td>N/A / N/A</td>
            <td>Set of all Sets</td>
            <td>N/A</td>
        </tr>
        <tr>
            <td>OWL (Semantic Web)</td>
            <td>Individual</td>
            <td>Class</td>
            <td>Predicat / ObjectProperty</td>
            <td>Thing</td>
            <td>DatatypeProperty</td>         
        </tr>
        <tr>
            <td>Topic Maps (Semantic Web)</td>
            <td>Topic</td>
            <td>Topic Type</td>
            <td>Association / Association TYpe</td>
            <td>N/A</td>
            <td>Occurence</td>
        </tr>
        <tr>
            <td>Langage O-O (Computer Science)</td>
            <td>Instance or Object</td>
            <td>Class</td>
            <td>Pointer / Object Attribute</td>
            <td>N/A</td>
            <td>Data Attribute</td>
        </tr>
    </tbody>
</table>


