# Visualisation de données du Stade Brestois 29


Bienvenue sur ce projet de data visualisation dédié au Stade Brestois 29 (SB29).
L'objectif est de centraliser les données clés des joueurs du club et les rendre lisibles via un dashboard Power BI simple mais efficace.

Ce projet a été réalisé avant tout pour le plaisir, avec l’envie de mettre en valeur mes compétences en data visualisation et en Power BI. L’idée était de créer un dashboard clair, esthétique et informatif, sans y passer des semaines, mais en prenant le temps de bien structurer les données et d’offrir un rendu professionnel.

<p align="center">
  <img src="https://github.com/user-attachments/assets/6603b7d2-ab7d-4b45-a00f-2e42c712cadd" width="90%" />
</p>

## Pourquoi ce projet ?
Les clubs professionnels exploitent de plus en plus la data pour analyser les performances des joueurs, affiner leur recrutement, ou encore prévenir les blessures. Grâce aux statistiques, aux données biométriques et aux analyses vidéo, les équipes peuvent prendre des décisions plus éclairées, qu’il s’agisse de tactique, de gestion de carrière ou de stratégie d’investissement

J’ai voulu explorer les statistiques des joueurs du SB29 à travers un tableau de bord visuel.

- Quelles sont les caractéristiques des joueurs ?
- Qui a marqué le plus de buts ?
- Quelle est l’évolution de la valeur marchande d’un joueur ?
- Quelles infos peut-on extraire d’un simple dataset ?

Toutes ces questions ont guidé la conception du projet.

## Étapes du projet 
#### 1. Récupération des données sur Kaggle (issues de Transfermarkt)
#### 2.Nettoyage et transformation avec Python et Pandas (jointures, filtrage, sélection des joueurs du SB29)
#### 3.Création du dashboard dans Power BI :
- Infos principales par joueur (poste, âge, taille, matchs joués, buts marqués, etc.)
- Visualisation de la valeur du joueur dans le temps
- Quelques débuts de heatmaps/statistiques avancées (travail en cours)


## Outils
<!-- Badges des outils utilisés -->
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=for-the-badge&logo=plotly&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-3776AB?style=for-the-badge&logo=matplotlib&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-0D76A8?style=for-the-badge&logo=python&logoColor=white)

- Pandas pour la manipulation de données
- Plotly / Matplotlib / Seaborn pour les visualisations
- Power BI pour la création du tableau de bord 


## Source 

Les données utilisées dans ce projet proviennent de ce tadaset de la plateforme [Kaggle](https://www.kaggle.com/datasets/davidcariboo/player-scores)
, où le jeu de données Player Scores a été récupéré. Ce jeu de données fournit des informations détaillées et structurées sur les performances des joueurs de football, tirées de Transfermarkt. Il inclut plus de **60 000 matchs** de plusieurs saisons et compétitions majeures, ainsi que des données sur plus de 400 clubs et **30 000 joueurs**. Les informations couvrent également plus de **400 000 évaluations de marché** historiques des joueurs, ainsi que plus d'**1,2 million de dossiers d'apparitions de joueurs dans les matchs**. 

<p align="center">
  <img src="https://github.com/user-attachments/assets/baa89661-769b-4eeb-88ec-9872924fff87" width="100%" />
</p>
<p align="center"><em>Schéma des données</em></p>

## Autres avancés
Je n'ai pas souhaité passer trop de temps sur la suite du projet, donc j'ai exploré les visualisations en créant des heatmaps des corners et coups francs marqués, sans les intégrer au dashboard. Voici un aperçu : une heatmap utilise des couleurs pour visualiser l'intensité d'un événement, avec des zones chaudes (rouge/orange) indiquant une forte activité et des zones froides (bleu/vert) une faible concentration.

<p align="center">
  <img src="https://github.com/user-attachments/assets/fbc24557-3067-4dc3-bbaf-5e5a96a2a2d0" width="75%" />
</p>
<p align="center"><em>Heatmap des corners et coups francs des joueurs du SB29</em></p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/7ba1025e-4310-4fc3-a55b-7dabc41fc0d7" width="75%" />
</p>
<p align="center"><em>Aperçu d'un autre joueur</em></p>




