# dpe_project

Objectif = développer un modèle de prédiction de l’impact des caractéristiques structurelles des logements sur l’étiquette DPE afin de prioriser les travaux les plus impactants et les budgétiser pour les clients d'une entreprise dans le BTP.

Base de donnée utilisée : "DPEs de maisons réalisés entre 2021 et 2024

Le projet comprend :
- une EDA du jeu de données
- le pré-processing des données
- la construction d'un modèle de régression de la variable "consommation d'énergie par m2 par an" avec les variables de description des logements
- la construction d'un modèle d'arbres aléatoires pour prédire cette même variable
- l'emploi de ce modèle pour préconiser les travaux les plus impactants pour un logement donné
