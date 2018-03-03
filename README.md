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
  * framework.mom: fichier Mindomo
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
  * $largeurBoiteFixe: largeur des boites fixes

### Module des Boites
* Types de Boites:
  * .boite-fixe : boite de $dimension-boite-fixe centrée et responsive

### Module des Contenus
