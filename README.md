# Dashboard Applications — Processus v1.1

Widget Grist pour suivre le positionnement des applications dans un processus, à partir de la table `B_Applications`.

## Correctifs v1.1

- Diagramme entièrement redessiné dans un SVG unique : les textes, connecteurs et losanges partagent le même repère.
- Connecteurs arrêtés aux limites des étapes et raccordés aux losanges.
- Résolution des colonnes Grist de type `Ref`, `RefList`, `Choice`, `ChoiceList` ou texte.
- La colonne `Statut` peut donc être une référence vers `REF_Backend`.
- Utilisation prioritaire de la table source associée au widget.
- Actualisation automatique après modification de `B_Applications`, plus bouton manuel `Rafraîchir`.
- KPI présents dès l’ouverture et recalculés après le chargement des données.

## Installation

Publier `index.html` sur GitHub Pages, puis ajouter l’URL comme custom widget Grist.

Le widget doit être associé à `B_Applications` et disposer de `Full document access`.
