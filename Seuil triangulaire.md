# Seuil triangulaire

Ce fichier a permet de traiter des mesures de débit effectués dans les réseaux d'assainissement.

## Principe des mesures

Un seuil trinagulaire est installé dans la canalisation d'assainissement, en travers de l'écoulement. Il permet d'avoir une section de passage controlé, correspondant à une loi de conversion hauteur/débit. Une sonde de mesure de hauteur est installé, effectuant une mesure toutes les minutes, ainsi qu'un module enregistreur.

## Traitement des mesures
Une fois les données de hauteurs exportées du module en format csv, il suffit de les copier-coller dans les deux premières colonnes de la première feuille ("corrections") et de rentrer les bons paramètres dans les cellules en rouge.
De même, les données de pluie doivent être rentrées dans la feuille "Pluie"
La feuille suivante "horaire" calcule les moyennes horaires correspondantes. Ces données horaires vont permettre de construire le tableau et le graphique récapitulatif sur les feuilles suivantes.
Enfin, les deux derniers onglets s'intéressent spécifiquement aux jours sans pluviométrie et calculent un certains nombre de paramètres, utiles au diagnostic des réseaux d'assainissement.
