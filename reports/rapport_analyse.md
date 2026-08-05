# Rapport d’analyse — Primero Bank

## 1. Contexte

Primero Bank fait face à des départs de clients. L’objectif du projet est d’identifier les profils des clients perdus, de comprendre les facteurs associés à l’attrition et de repérer les clients actuels présentant des signaux de risque.

## 2. Méthodologie

- Exploration du jeu de données
- Audit de qualité
- Nettoyage avec Python et pandas
- Analyse comparative des clients actuels et perdus
- Création d’un score métier de risque
- Visualisation avec Power BI

## 3. Principaux résultats

- Taux d’attrition global : 16,15 %
- Les clients perdus réalisent moins de transactions
- Ils utilisent moins fréquemment leur carte
- Ils présentent davantage de mois d’inactivité
- Ils ont davantage d’interactions avec la banque
- Leur montant moyen de crédit renouvelé est plus faible

## 4. Clients à risque

Le score métier repose sur cinq signaux :

- forte inactivité
- nombreuses interactions
- faible montant de crédit renouvelé
- faible nombre de transactions
- faible utilisation de la carte

61 clients ont été classés en risque élevé.

## 5. Recommandations

- Réactiver les clients inactifs
- Cibler les clients dont les transactions diminuent
- Étudier les motifs des interactions répétées
- Encourager l’utilisation de la carte
- Contacter en priorité les clients à risque élevé

## 6. Limites

Le score de risque est une règle métier exploratoire. Il ne constitue pas une probabilité statistique de départ et devra être validé sur de nouvelles données.