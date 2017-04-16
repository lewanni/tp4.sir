# tp4.sir

## Objectifs
* Comprendre les mécanismes des Servlet
* Réaliser une application Web en utilisant Combinant JPA et les Servlet
* Comprendre les principes d’une architecture Rest
* Comprendre les bénéfices d’un framework comme Jersey

## Sujet
* L’objectif de ce projet est de continuer le développement d’une application type réseau social permettant de comparer sa consommation électrique avec ses amis, ses voisins,etc. dans la lignée de opower (voir TP2)

## Servlet
* A partir des entitées créées au TP2, on peut créer un servlet GET pour récupérer et afficher les données présentes la BDD dans du HTML
* Avec un formulaire HTML, on crée un servlet POST pour créer une nouvelle instance persistance à ajouter dans la BDD
* Remarques : Avec les servlet, on peut pas mettre deux chemins differents dans une même classe.

## Rest
L'architecture REST avec le framework Jersey : une solution alternative aux Servlets !

* Création d'un URI en JSON pour afficher en GET les données présentes dans la BDD
* Avec un formulaire HTML, on crée un URI POST pour créer une nouvelle instance persistance à ajouter dans la BDD
