# FrameworkCSS_2018
## Un Framework CSS basé sur SASS

### Structure des dossiers et fichiers
* index.html
* __css:__ dossier reprenant les fichiers css étendus et minifiés
  * app.css : fichier de surcharge étendu
  * app.min.css : fichier de surcharge minifié
  * framework.css: framework étendu
  * framework.min.css: framework minifié
* __documents:__ dossier reprenant la carte mentale du framework (png + mom)
  * framework.css.mom: fichier Mindomo
  * framework.png: capture d'écran
* __scss:__ dossier reprenant les fichiers de travail (SASS)
  * app.scss : fichier de surcharge
  * framework.scss : fichier principal du framework (chargement des modules)
  * __framework:__ dossier reprenant les éléments du Framework
    * _variables.scss : variables du Framework
    * __modules:__ dossier reprenant les modules du framework
      * _boites.scss : classes concernant les boites
      * _contenus.scss : classes concernant les contenus

### Les Variables
* Les couleurs
  * $couleur1: couleur principale
  * $couleur2: couleur secondaire

* Les dimensions
  * $dimension-boite-fixe: largeur des boites fixes

### Module des Boites
* Types de Boites:
  * .boite-fixe : boite de $dimension-boite-fixe centrée et responsive

* Boites colorées :
  * .boite-fond-coul1: boite de couleur principale
  * .boite-fond-coul2: boite de couleur secondaire

* Boites particulières:
  * .boites-marge-nulle: boite sans marges

### Module des Contenus
* Alignement des contenus:
  * .contenu-droite: alignement à droite
  * .contenu-centre: alignement centré
  * .contenu-justife: alignement justifié

* Type d'affichage:
  * contenu-inline: affichage du contenu en inline-block

### Module des Listes
* Types delistes :
  * .liste-sans-puces: liste sans puces
