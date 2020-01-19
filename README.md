Installation du site

Prérequis : Un serveur web hôte.

Installation d'application générant un serveur web en local :
* Jekyll : 
https://jekyllrb.com/docs/
* Wamp server : 
http://www.wampserver.com/
Après l'installation de votre serveur web, créer un site (Jekyll) ou un virtualhost (Wamp) est nécessaire.
Copiez simplement le contenu de ce repository ou clonez-le dans le dossier généré (Jekyll -> "_site" | Wamp -> www/<nomvirtualhost>)


Ce code fait appel à 2 API, celle de Mapbox pour le Geocoding (ici, obtenir les coordonnées latitude/longitude à partir d'adresse).
Mapbox étant basé sur OpenStreetMap, certains résultats n'aparaîtront pas à San Francisco. Les résultats ont été limités aux US cependant afin de garder de
la cohérence et une solution gratuite d'utilisation (Bonjour Google Maps API).

Le 2ème appel est sur l'API omdb (http://www.omdbapi.com/), qui référence les posters des films et permet ici d'obtenir les liens de ces images pour les afficher.

