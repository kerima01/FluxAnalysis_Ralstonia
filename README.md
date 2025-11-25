# Analyse des flux métaboliques sur un modèle genome-scale avec MetExplore

## Contexte
Ce projet présente l'analyse des flux métaboliques d’un modèle genome-scale de **Ralstonia solanacearum**.  
Les flux ont été calculés avec **COBRApy**, puis mappés sur le réseau métabolique de Ralstonia dans **MetExplore 3** pour visualisation et analyse.

---

## Contenu du dépôt
- `ralsto_metexplore3.xml` : Modèle SBML de Ralstonia solanacearum.  
- `fluxes_for_metexplore.csv` : Valeurs de flux des réactions, format tabulé pour MetExplore.  
- `essential_genes.csv` : Liste des gènes essentiels identifiés avec COBRApy.  
- `liste_voies.csv` : Résultats du mapping des gènes sur les voies métaboliques.  
- `graph.png` : Visualisation du sous-réseau glycolyse avec flux mappés.  
- `mod_cobraPy.ipynb` : Notebook Jupyter contenant toutes les analyses et visualisations.  

---

## Installation et utilisation
1. Installer les dépendances Python :
```bash
pip install cobra pandas cplex

