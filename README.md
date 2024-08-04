# Traitement des Valeurs Manquantes dans le Dataset Horse.csv

Ce projet utilise le dataset `horse.csv` pour démontrer des techniques de traitement des valeurs manquantes, en utilisant notamment l'imputation par les k plus proches voisins (KNN).

## Description du Dataset

Le dataset `horse.csv` contient des données médicales sur des chevaux atteints de coliques. Il est fréquemment utilisé pour des exercices d'apprentissage automatique et de traitement des valeurs manquantes.
Le dataset inclut des variables telles que la température rectale, le pouls, la fréquence respiratoire, ainsi que des indicateurs de douleur et d'autres paramètres médicaux.

## Variables du Dataset

- surgery : Indicateur de la nécessité d'une intervention chirurgicale (1 = Oui, 2 = Non).
- age : Âge du cheval (1 = Adulte, 2 = Jeune).
- hospital_number : Numéro d'identification unique de l'hôpital.
- rectal_temp : Température rectale (en degrés Celsius).
- pulse : Pouls (battements par minute).
- respiratory_rate : Fréquence respiratoire (respirations par minute).
- temp_of_extremities : Température des extrémités (Normal, Froid, Chaud, Froid et Froid).
- peripheral_pulse : Pouls périphérique (Normal, Réduit, Absent).
- mucous_membrane : État des muqueuses (Normal, Pâle, Cyanotique, Rouge, Ictérique, Injecté).
- capillary_refill_time : Temps de remplissage capillaire (en secondes).
- pain : Niveau de douleur (Aucun, Léger, Modéré, Sévère, Très Sévère).
- peristalsis : Péristaltisme (Hyperactif, Normal, Hypoactif, Absent).
- abdominal_distention : Distension abdominale (Aucune, Légère, Modérée, Sévère).
- nasogastric_tube : Présence de tube nasogastrique (Aucun, Légère, Modérée, Sévère).
- nasogastric_reflux : Reflux nasogastrique (Aucun, Légère, Modérée, Sévère).
- nasogastric_reflux_ph : pH du reflux nasogastrique.
- rectal_exam_feces : Résultats de l'examen rectal des fèces.
- abdomen : État de l'abdomen.
- packed_cell_volume : Volume cellulaire compacté (%).
- total_protein : Protéine totale (g/dL).
- abdomo_appearance : Apparence de l'abdomen.
- abdomo_protein : Protéine de l'abdomen (g/dL).
- outcome : Issue du traitement (Vivant, Mort, Euthanasié).
- surgical_lesion : Présence de lésion chirurgicale (Oui, Non).
- lesion_1 : Première lésion.
- lesion_2 : Deuxième lésion.
- lesion_3 : Troisième lésion.
- cp_data : Données de traitement clinique.

## Objectif du Projet

L'objectif de ce projet est de traiter les valeurs manquantes dans le dataset en utilisant une approche en deux phases :

1. Imputation des valeurs manquantes pour les variables numériques à l'aide de la moyenne des k plus proches voisins.
2. Imputation des valeurs manquantes pour les variables catégorielles en les codant et en utilisant le mode des k plus proches voisins.

## Utilisation

### Prérequis

- Python 3.x
- pandas
- numpy
- scikit-learn
- scipy

### Contribution
Les contributions sont les bienvenues ! Veuillez soumettre un problème ou une pull request pour toute amélioration ou suggestion.
