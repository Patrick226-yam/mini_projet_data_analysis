# Mini Projet 

## Objectif
L’objectif de ce mini-projet est d’extraire, filtrer et analyser des sous-ensembles de données à partir d’une base plus large concernant le Burkina Faso. Les résultats sont sauvegardés sous différents formats pour visualisation et analyse.

---

## Contenu du dépôt

- **YAMEOGO_Patrick.ipynb** : Notebook Jupyter contenant le code complet et les sorties visibles.
- **data/** : Dossier contenant les données sources (`BF.txt`) et le fichier CSV intermédiaire (`burkina_location.csv`).
- **gounghin.csv** : Fichier généré avec les lieux contenant "gounghin".
- **A_to_P.csv** : Fichier généré avec les lieux dont les noms commencent par les lettres A à P.
- **Coord_lat11_long0.5.csv** : Fichier généré avec les lieux dont latitude >= 11 et longitude <= 0.5.
- **mini_projet.xlsx** : Fichier Excel contenant les données filtrées sur différentes feuilles.

---

## Explications des étapes

**Téléchargement et extraction** : Téléchargement du fichier `BF.zip` depuis GeoNames et extraction de `BF.txt`.

**Prétraitement** : Sélection des colonnes pertinentes, conversion des coordonnées en float et création du CSV intermédiaire `burkina_location.csv`.

**Filtres et extractions** :
   - Lieux contenant "gounghin"
   - Lieux dont la première lettre est comprise entre A et P
   - Latitude et longitude minimales avec les noms correspondants
   - Lieux avec latitude >= 11 et longitude <= 0.5

**Export Excel** : Création d’un fichier Excel `mini_projet.xlsx` avec les sous-ensembles sur différentes feuilles.

---

## Ressources
- Source des données : [GeoNames Burkina Faso](https://download.geonames.org/export/dump/BF.zip)
- Notebook Jupyter pour reproduire toutes les manipulations.

---

**Patrick YAMEOGO**

Lien GitHUB: https://github.com/Patrick226-yam/mini_projet_data_analysis.git
