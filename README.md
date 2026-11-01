# AIMS Calculator

Prototype statique pour la cotation de l’Alberta Infant Motor Scale, avec les quatre positions sur une même page.

## Utilisation

Ouvrir `index.html`, ou consulter le site GitHub Pages. Aucun serveur applicatif ni dépendance n’est nécessaire.

- Sélections des items acquis et étoiles de surveillance.
- Fenêtres automatiques et calcul des sous-scores / total.
- Historique dans le stockage local du navigateur et export JSON.
- État déterministe `AIMS1.…`, restaurable via `?state=…` ou par collage du code.
- Le code contient les champs de la séance et n’est pas chiffré. Ne pas publier de données cliniques identifiantes dans les liens ou dans ce dépôt.

## Limites du prototype

Une plage de percentiles est calculée par tranche d’âge mensuelle à partir des colonnes canadiennes du tableau 3 de l’étude https://doi.org/10.1186/s12887-023-04055-5. Les seuils sont consignés dans `percentiles-source.json`. Il ne s’agit pas de la lecture hebdomadaire interpolée de la grille du manuel. Une lecture manuelle séparée reste disponible. Les descriptions en anglais et les illustrations sont extraites du feuillet fourni ; certains passages sont tronqués ou pâles dans le scan. Vérifier les critères dans le manuel avant toute utilisation clinique.

Les contenus AIMS appartiennent à leurs ayants droit respectifs. Ce dépôt ne leur attribue aucune licence de réutilisation.

## Publication

GitHub Pages sert la racine de la branche `main`. Les modifications poussées sur cette branche sont publiées automatiquement.

## Source des illustrations

Les 58 illustrations proviennent des pages 44 à 47 du PDF conservé par l’Université de Brasília : https://bdm.unb.br/bitstream/10483/13862/6/2015_MilenaFelipeFelix.pdf. Elles remplacent les découpes de la première numérisation.
