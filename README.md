# Mémoire TNAH 2022

## Résumé
Ce présent mémoire rend compte du stage effectué entre avril et juillet 2022 au centre *Archivo Central Andrés Bello - Universidad de Chile* à Santiago du Chili pour le traitement éditorial des sources autour de l'*Occupation de l'Araucanie* (1850-1881). Il a conduit à la conception d'une chaîne de traitement de documents numérisés vers l'encodage TEI p5, décrit par une documentation ODD. Pour se faire, un modèle HTR a été produit afin de reproduire le contenu et la mise en page des documents numérisés *via* le moteur OCR Kraken.
	
Dans un second temps, le stage a donné lieu au développement d'un modèle de reconnaissance d'entités nommées sur la base du modèle BETO. Cette utilisation des techniques du traitement automatique du langage a eu pour effet de permettre l'indexation des personnes, lieux, organisations et dates présentes au sein des fichiers XML-TEI. Enfin, ces entités ont fait le fruit d'un processus d'enrichissement automatique à partir des bases de données Wikidata.

---
## Structure du dépôt

- `Araucania_MasterTNAH.pdf` : mémoire sous format pdf
- `latex/`: contient l'ensemble des fichiers non compilés LaTeX
- `livrables/`: contient les liens vers les différents travaux conçus durant le stage

---
## Citer le mémoire
```
@thesis{humeau_araucania_,
        location = {Paris},
        title = {Modélisation, enrichissement sémantique et diffusion d'un corpus textuel semi-structuré: le cas des catalogues de vente de manuscrits},
        url = {https://github.com/rayondemiel/master_TNAH_Araucania/},
        pagetotal = {171},
        institution = {École nationale des Chartes},
        type = {Mémoire pour le diplôme de master "Technologies numériques appliquées à l'histoire"},
        author = {Humeau, Maxime},
        urldate = {2022-09-15},
        date = {2022}
}
```
