# Dashboard Applications — Processus v2

Ce widget Grist corrèle trois tables :

- `B_Applications` : une demande = un service utilisateur + une application ;
- `REF_Applications Qualifiées` : qualification de l’application, avec suivi séparé SSI et fonctionnel ;
- `REF_Flux Applications` : travaux de flux par couple service demandeur + application.

## Fonctions principales

- filtres par service utilisateur et priorité ;
- liste synthétique des demandes applicatives ;
- statut de qualification et statut des flux dans chaque demande ;
- mise en évidence de plusieurs étapes simultanées dans le processus ;
- compteurs par étape, séparant Qualification (`Q`) et Flux (`F`) ;
- détail de la qualification SSI / fonctionnelle et des lignes de flux ;
- configuration manuelle des identifiants techniques de tables.

## Installation

1. Publier `index.html` via GitHub Pages.
2. Ajouter un widget `Custom` dans Grist.
3. Renseigner l’URL GitHub Pages.
4. Accorder `Full document access`.
5. Utiliser le bouton `Configurer` si les tables ne sont pas détectées automatiquement.

Le widget est en lecture seule : il ne modifie pas les tables sources.
