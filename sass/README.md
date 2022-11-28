Ce dépôt contient le *frontend* du site __ohmyfood__ qui permet de réaliser des commandes en ligne dans des restaurants gastronomiques à Paris.
Ce site a été réalisé grâce au pre-processeur SASS afin de faciliter sa maintenance et son évolution.
Voici quelle est l'architecture du site :

    1. Un dossier utils qui contient les fichiers :
    - "_variables" où se trouvent les variables (couleurs, fonts, media queries, les variables utilisées dans les fonctions)
    - _extensions: les extensions
    - "_mixins" où sont les mixins utilisées pour créer le header en position fixe et les media queries
    - "_animations" où se trouvent les animations pour valider le choix des menus

    2. Un dossier Layouts qui contient :
    - "_header", le header
    - "_footer", le footer

    3. Un dossier modules qui contient :
    - "_hearticon" qui coorespond aux styles du bouton like en forme de coeur
    - "_loader" aux styles du LOADER

    4. Un dossier "accueil" qui contient tous les éléments propres à la page d'accueil  :
    - "_home-presentation", correspond aux styles généraux de mise en page
    - "_localisation", aux styles du formulaire de localisation
    - "_navigation", aux styles de la description du site et de son bouton d'exploration
    - "_fonctionnement", aux styles des boutons expliquant le fonctionnement du site pour réaliser sa commande en ligne
    - "_restaurants", aux styles des cartes des restaurants

    5. Un dossier "restaurants" qui contient tous les éléments propres aux différentes pages de chacun des restaurants:
    - "_restau-presentations", correspond aux styles généraux de mise en page des pages de chaque restaurant
    - "_topsection" correspond aux styles de l'image des restaurants 
    - "_menus" correspond aux styles de la carte des menus à sélectionner
    - "_button" correspond aux styles du bouton commmander

    6. Un fichier "_generalsettings" pour les styles généraux et communs à toutes les pages du site

    7. Un fichier "styles.scss" pour créer le lien entre le fichier css et tous les fichiers scss
