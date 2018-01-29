
# TUTO EXPLICATIF RUBY ON RAILS 

===================

## Introduction 

Site statique et site dynamique : KEZAKO ?

Un **site web statique** ne présente aucune animation. Les pages affichées seront "figées". Elles seront néanmoins réalisées avec plus de facilité.

Un **site web dynamique** permet une interaction avec le visiteur : les informations sont affichées sous différentes formes, avec du mouvement. L'animation plus agréable et évolutive, demandera toutefois un travail de codage conséquent.

===================

## RubyOnRails (RoR) 

	a) Présentation

Ruby On Rails communénent surnommé Ror est un framework. 

Imaginons un restaurateur qui souhaite devenir mobile. RoR serait le Foodtruck tout équipé qui lui faciliterait le lancement son activité. Easy, simple et fonctionnel.		

	b) Puissance de Ruby

* Ruby repose sur une communauté importante. Celle-ci participe à son développement, notamment via un système de "gems" en libre disposition.

RoR est également une gem de Ruby.

* Les gems sont des éléments qui proposent des fonctionnalités diverses.

Certaines gems proposeront simplement des extraits de code qui pourront être réutilisés dans n'importe quel autre projet.

* Nb : Ruby est livré avec des gems préinstallées, idéal pour débuter.

===================

## Première application avec RoR

	a) les principaux dossiers

* Le dossier **CONFIG** comporte le coeur des éléments nécessaires au développement de notre application.


* Le dossier **APP** est le dossier principal, comportant notamment le *mvc* (Model View Controller). Y sont donc contenus les controllers, views et models.

-----

Le **model** est un gestionnaire qui structure les données dans les bases de données.

La **view** est le mécanisme d'affichage de la page web que tu voudras afficher.

Un **controller** est le manager/coordinateur de la view et du model. Son rôle est de collecter les données auprès du model et de donner l'ordre à la view de présenter ces données à l'utilisateur sur une page web.


* Le fichier **ROOTS** permet de gérer/configurer les différentes *routes* de notre application (une route est une *url* qu'on utilisera).

Chaque route interagira avec un controller.

La ligne de commandes `rails route` permet de voir l'état (statut) de nos différentes routes dans le terminal grâce au **CRUD**.

Le CRUD est un système de manipulation de données d'une base de données. On pourrait le quailifer d'interface de gestion de données via les 4 opérations : CREATE, READ, UPDATE, DESTROY.


* Le dossier **PUBLIC** comportera des images, fichiers html, robots.

	b) Premiers pas dans RoR

* Pour démarrer RoR, taper dans le terminal la ligne de commande `rails s`, qui initiera un serveur à l'adresse : <http://localhost:3000/>.

* Pour créer un nouveau projet, il suffira de taper dans notre terminal : "rails new_nomduprojet".

	c) Le CRUD (Create Read Update Destroy)

Le *CRUD* permet d'afficher, créer, modifier et supprimer des articles. Il interagira donc avec les bases de données.

Ligne de commande : `ressources :articles`.

	d) les migrations



















