
# RUBY ON RAILS (RoR) pour tous

---

## Introduction 

> Site statique et site dynamique : KEZAKO ?

* Un **site web statique** ne présente aucune animation : les pages affichées seront "figées". 
- Elles seront néanmoins réalisées avec plus de facilité.

* Un **site web dynamique** permet une interaction avec le visiteur : les informations sont affichées avec du mouvement. 
- L'animation est plus agréable et évolutive, mais demandera toutefois un travail de codage conséquent.

---

## RubyOnRails (RoR) 

### Présentation

- Ruby On Rails communénent surnommé Ror est un framework. 

- Imaginons un restaurateur qui souhaite devenir mobile. RoR serait le Foodtruck fourni clé en main, tout équipé. Le lancement de son activité sera simplifié, plus qu'à démarrer puis cuisiner. 

![alt foodtruck](https://github.com/Polo94/Polo94-S4J1-ReadmeOnRails/blob/master/foodtruck2.png)

### Puissance de Ruby

* Ruby repose sur une communauté importante. Celle-ci participe à son développement, notamment via un système de "gems" en libre disposition.

- `RoR est également une gem de Ruby.`

* Les gems sont des éléments qui proposent des fonctionnalités diverses.

Certaines gems proposeront simplement des extraits de code qui pourront être réutilisés dans n'importe quel autre projet.

* Nb : Ruby est livré avec des gems préinstallées, idéal pour débuter.

---

## Afficher sa page web

### Fonctionnement du Model View Controller (MVC)

```Le Model View Controller (MVC) est une architecture logicielle permettant d'organiser et traiter son code. Les interactions entre les trois modules (model, view, controller) permettront d'afficher la page web demandée par l'utilisateur.```

![alt MVC](https://github.com/Polo94/Polo94-S4J1-ReadmeOnRails/blob/master/schema-mvc.png)


* Le **Model** est un gestionnaire qui structure les données dans les bases de données.

* La **View** est le mécanisme d'affichage de la page web que tu voudras afficher.

* Un **Controller** est le manager/coordinateur de la View et du Model. Son rôle est de collecter les données auprès du model et de donner l'ordre à la view de présenter ces données à l'utilisateur sur une page web.

Le MVC permet donc de passer du back end (code interprété du site) au front end (partie visible du site).


* Le fichier **ROOTS** de l'application rails que l'on crée, permet de gérer/configurer les différentes *routes* de notre application (une route est une *url* qu'on utilisera).

Chaque route interagira avec un controller.

La ligne de commande `rails route` tapée dans le terminal permet de voir l'état (statut) de nos différentes routes dans le terminal grâce au **CRUD**.


### Le CRUD (Create Read Update Destroy)

Le *CRUD* est un système de manipulation de données d'une base de données (BDD). On pourrait le quailifer d'interface de gestion de données via les 4 opérations : CREATE (créer), READ (lire), UPDATE (mettre à jour), DESTROY (supprimer).

Le CRUD permet d'afficher, créer, modifier et supprimer des articles. Il interagira donc avec les bases de données.

### GET et POST

* La requête GET permet de lire le contenu des bases de données (BDD).

* la requête POST permet de créer (écrire) de nouvelles ressources dans les bases de données (BDD).

* Il existe également d'autres requêtes : PUT (modifier une ressource existante) et DELETE (supprimer une ressource).


### Relation entre les bases de données (BDD) et les Models

* Les Models créeront continuellement des requêtes afin de récupérer en retour des données contenues dans les bases de données. Une fois les données nécessaires captées, les Models les enverront à la View.

### Les migrations

* La migration est l'adaptation d'une structure de données, en la faisant évoluer de façon à lui permettre de les adapter aux besoins de l'utilisateur lorsqu'il visite le site. On peut prendre l'exemple des mises à jour.

*[En cas de PLS](https://www.youtube.com/watch?v=caVUBl2UU3E&index=1&list=PL0TnHYy48T2w_341XcdDNcKFF307YB0KK)*



_A bientôt_













