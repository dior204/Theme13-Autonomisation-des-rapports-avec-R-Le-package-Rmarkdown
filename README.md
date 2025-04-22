# Theme13- Autonomisation des rapports avec R le package Rmarkdown

## Description

Ce projet a été réalisé dans le cadre de l’unité d’enseignement *Projet statistique avec R*.  
Il porte sur l’utilisation du package **RMarkdown** pour automatiser la génération de rapports reproductibles, dynamiques et personnalisés.

## Objectifs

- Générer des rapports dynamiques en combinant code, texte et graphiques.
- Automatiser les analyses statistiques.
- Améliorer la reproductibilité des travaux.
- Créer une interface interactive avec **Shiny**.

# Différentes étapes

## Partie 1 : Introduction à Rmarkdown

Montrer les différentes parties  dans Rmarkdown et les béats bas dans Rmarkdown

## Partie 2 : Génération de rapports sur Word avec Rmarkdown

Générer un rapport puis intégrer les templates

# 🛠️Technologies et packages utilisés


- **R** : Langage principal utilisé pour le traitement, l’analyse de données et la génération des rapports.
- **RMarkdown** : Outil central du projet permettant de créer des documents dynamiques combinant texte, code R et résultats (tableaux, graphiques...).
- **ggplot2** : Utilisé pour produire des visualisations graphiques élégantes et personnalisées à partir des données analysées.
- **MSchart** : Utilisé pour intégrer des graphiques Microsoft Office (notamment dans des documents Word) et enrichir les rapports avec des visualisations adaptées à un format bureautique.
- **rvg** : Permet de générer des graphiques vectoriels (au format Office DrawingML) exportables dans Word et PowerPoint tout en conservant leur qualité d’édition.
- **tidyverse** : Ensemble de packages pour la manipulation, la transformation et la visualisation des données (incluant notamment `dplyr`, `readr`, etc.).

# Contenu du dépôt

Le dépôt est organisé autour de plusieurs exemples illustrant différentes possibilités offertes par RMarkdown pour l’automatisation des rapports :

- **Introduction_Rmarkdown/**  
  Contient un fichier `.Rmd` d’introduction à RMarkdown ainsi que sa sortie au format PDF.  
  → Objectif : présenter les bases de RMarkdown (syntaxe, blocs de code, rendu).

- **Sortie_Word_avec_Rmarkdown/**  
  Contient un fichier `.Rmd` destiné à produire un rapport Word ainsi que la sortie PDF.  
  → Objectif : montrer comment adapter le rendu pour des documents Word professionnels.

- **application_sans_template/**  
  Contient un fichier `.Rmd` simple (sans mise en forme avancée) et sa sortie au format Word.  
  → Objectif : illustrer un rendu minimaliste sans structure prédéfinie.

- **application/**  
  Contient un fichier `.Rmd` avec un **template personnalisé** ainsi que sa sortie Word.  
  → Objectif : démontrer l'utilisation de modèles personnalisés pour des rapports structurés et esthétiques.

Chaque dossier illustre une facette de l’autonomisation des rapports avec RMarkdown, du plus simple au plus abouti.



























# 📚Références

https://book.utilitr.org/03_Fiches_thematiques/Fiche_rmarkdown_param_report.html

https://youtu.be/lFdB4fIAcLM?si=h10PeeKg5rmzjwUS

https://youtu.be/vWGGlMHkhyY?si=ptxVeE2S_Jc0LKSC

https://r-graph-gallery.com/
