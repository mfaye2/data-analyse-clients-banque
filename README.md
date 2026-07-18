# Analyse de l’attrition client — Primero Bank

## Présentation du projet

Ce projet de Business Intelligence et de data visualisation porte sur l’analyse de l’attrition des clients de **Primero Bank**.

La banque fait face à une augmentation du nombre de départs de clients. L’objectif de cette étude est d’utiliser les données disponibles pour comprendre les caractéristiques des clients ayant quitté la banque, identifier les principales causes possibles de ces départs et repérer les clients actuels présentant un risque d’attrition.

Le projet est réalisé dans le cadre d’une mission fictive au sein de l’ESN **ESN Data**, en tant que consultant Business Intelligence.

---

## Contexte métier

Primero Bank observe une vague importante de départs de clients.

Avant de mettre en place un plan d’action de fidélisation, la direction marketing souhaite comprendre :

- quels types de clients quittent le plus souvent la banque ;
- quelles caractéristiques sont communes aux clients partis ;
- quels comportements peuvent être associés au départ d’un client ;
- quels clients actuels présentent un profil similaire aux clients ayant quitté la banque ;
- quelles actions pourraient être mises en place pour réduire l’attrition.

L’analyse sera présentée à la directrice marketing de Primero Bank afin de l’aider à prendre des décisions basées sur les données.

---

## Problématique

La problématique principale de ce projet est la suivante :

> Comment utiliser les données clients de Primero Bank pour comprendre les causes de l’attrition et identifier les clients actuels susceptibles de quitter la banque ?

---

## Objectifs du projet

Le projet poursuit plusieurs objectifs :

1. Explorer et comprendre les données fournies par Primero Bank.
2. Vérifier la qualité des données.
3. Nettoyer et transformer les variables nécessaires à l’analyse.
4. Calculer le taux global d’attrition.
5. Identifier les caractéristiques communes des clients ayant quitté la banque.
6. Formuler au moins cinq pistes d’analyse expliquant les départs.
7. Comparer les clients actuels et les clients perdus.
8. Identifier les profils de clients actuels présentant un risque élevé de départ.
9. Créer des visualisations faciles à lire et adaptées à un public non technique.
10. Proposer des recommandations métier permettant de réduire l’attrition.

---

## Données disponibles

Le jeu de données contient des informations démographiques, commerciales et comportementales sur les clients de Primero Bank.

### Variables principales

| Variable | Description |
|---|---|
| N° du client | Identifiant unique du client |
| Statut du client | Indique si le client est actuel ou s’il a quitté la banque |
| Âge du client | Âge du client en années |
| Genre du client | Genre déclaré par le client |
| Nombre de personnes à charge | Nombre de personnes à charge |
| Niveau de diplôme | Niveau de formation du client |
| Statut marital | Situation matrimoniale du client |
| Catégorie du revenu annuel | Tranche de revenu annuel du client |
| Type de carte | Type de carte bancaire détenue |
| Durée d’engagement en mois | Ancienneté du client dans la banque |
| Nombre de mois inactifs | Nombre de mois sans transaction sur les douze derniers mois |
| Nombre d’interactions | Nombre de contacts entre le client et la banque |
| Montant du crédit renouvelé | Montant du crédit renouvelé mensuellement |
| Nombre de transactions | Nombre de transactions réalisées |
| Utilisation moyenne de la carte | Fréquence moyenne d’utilisation de la carte |

---

## Questions d’analyse

L’étude cherche notamment à répondre aux questions suivantes :

- Quel est le taux global d’attrition de Primero Bank ?
- Les clients perdus sont-ils plus âgés que les clients actuels ?
- L’attrition varie-t-elle selon le genre ?
- Le niveau de revenu influence-t-il le risque de départ ?
- Certains types de cartes sont-ils davantage associés à l’attrition ?
- Les clients inactifs quittent-ils plus souvent la banque ?
- Le nombre de transactions est-il plus faible chez les clients perdus ?
- Une faible utilisation de la carte est-elle un indicateur de départ ?
- Le nombre d’interactions avec la banque est-il lié à l’attrition ?
- L’ancienneté du client influence-t-elle sa fidélité ?
- Quels clients actuels possèdent un profil similaire aux clients ayant quitté la banque ?

---

## Hypothèses initiales

Avant l’analyse, plusieurs hypothèses peuvent être formulées :

1. Les clients ayant une faible activité transactionnelle présentent un risque plus élevé de départ.
2. Les clients ayant plusieurs mois d’inactivité quittent davantage la banque.
3. Un nombre élevé de contacts avec le service client peut signaler une insatisfaction.
4. Les clients utilisant peu leur carte sont plus susceptibles de partir.
5. Les clients possédant certains types de cartes peuvent avoir des comportements d’attrition différents.
6. L’âge, le revenu ou la situation familiale peuvent influencer le risque de départ.
7. Une faible ancienneté ou un faible engagement avec la banque peut augmenter le risque d’attrition.

Ces hypothèses devront être confirmées ou rejetées à partir des données.

---

## Méthodologie

Le projet est organisé en plusieurs étapes.

### 1. Compréhension des données

- analyse du dictionnaire des données ;
- identification des variables qualitatives et quantitatives ;
- compréhension de la variable cible représentant le statut du client.

### 2. Contrôle de la qualité des données

- recherche de valeurs manquantes ;
- détection des doublons ;
- vérification des types de données ;
- identification des valeurs incohérentes ;
- contrôle des catégories de variables.

### 3. Nettoyage et transformation

- renommage éventuel des colonnes ;
- conversion des types de données ;
- traitement des valeurs inconnues ;
- création d’indicateurs utiles à l’analyse ;
- création éventuelle de groupes d’âge ou de niveaux de risque.

### 4. Analyse exploratoire

- calcul du taux d’attrition ;
- analyse des distributions ;
- comparaison entre clients actuels et clients perdus ;
- calcul d’indicateurs par catégorie ;
- recherche des facteurs associés au départ.

### 5. Identification des profils à risque

Les profils des clients perdus seront comparés à ceux des clients actuels.

Un score ou des règles métier pourront être utilisés pour repérer les clients présentant plusieurs facteurs de risque, par exemple :

- plusieurs mois d’inactivité ;
- peu de transactions ;
- faible utilisation de la carte ;
- nombre élevé d’interactions avec la banque ;
- faible montant de crédit renouvelé.

### 6. Data visualisation

Les résultats seront présentés à l’aide de graphiques adaptés :

- indicateurs KPI ;
- diagrammes en barres ;
- histogrammes ;
- graphiques empilés ;
- boxplots ;
- nuages de points ;
- tableaux de synthèse ;
- tableau de bord Power BI.

### 7. Recommandations métier

Les résultats de l’analyse permettront de proposer des actions de fidélisation ciblées.

---

## Indicateurs clés envisagés

Les indicateurs principaux du projet sont :

- nombre total de clients ;
- nombre de clients actuels ;
- nombre de clients perdus ;
- taux d’attrition global ;
- âge moyen des clients perdus ;
- nombre moyen de mois d’inactivité ;
- nombre moyen de transactions ;
- utilisation moyenne de la carte ;
- taux d’attrition par type de carte ;
- taux d’attrition par tranche de revenu ;
- taux d’attrition par niveau de diplôme ;
- taux d’attrition par statut marital ;
- nombre de clients actuels considérés comme à risque.

### Formule du taux d’attrition

```text
Taux d’attrition =
Nombre de clients ayant quitté la banque
------------------------------------------------ × 100
Nombre total de clients
