# Défi de pipeline Retroverse

## Table des matières
1. [Introduction](#introduction)
2. [Étape de développement](#étape-de-développement)
3. [Étape de production](#étape-de-production)
4. [Autres Étapes](#autres-étapes)
5. [Gestion des Erreurs](#gestion-des-erreurs)
6. [Licence](#licence)

## Introduction
Ce projet est une application Vue.js avec un processus de construction à deux étapes. La première étape est dédiée au développement et la seconde à la production.

## Étape de développement
L'étape de développement contient l'interface principale de Vue.js. Le processus de construction comprend :

- Installation des dépendances avec `npm install`
- Compilation et rechargement à chaud pour le développement avec `npm run serve`
- Exécution des tests avec `npm run test`

## Étape de production
L'étape de production contient également les fichiers Jenkins pour le pipeline. Le processus de construction comprend :

- Compilation et minification pour la production avec `npm run build`

## Autres Étapes
Il existe trois autres étapes :

- Dépôt Git : Cette étape implique la récupération du code depuis le dépôt Git.
- Construction Docker : Cette étape consiste à construire une image Docker à partir du fichier Dockerfile dans le dépôt.
- Étiquetage Docker : Cette étape consiste à étiqueter l'image Docker avec un numéro de version.

## Gestion des Erreurs
Il existe une option pour intercepter les erreurs en envoyant des courriels via SMTP. Ceci est utile pour le débogage et la surveillance du processus de construction.





