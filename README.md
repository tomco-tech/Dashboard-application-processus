
# Dashboard Applications — Processus V1.2

Correction du diagramme pour reproduire exactement la logique métier de référence :

- Récupérer l’APK → Qualification SSI ;
- sorties SSI vers JIRA, PFAI et mise en conformité éditeur ;
- fusion JIRA / PFAI avant la première décision ;
- traitement spécifique supplémentaire → qualification fonctionnelle ;
- branche OK vers Déploiement et tests CU ;
- branche KO vers Support N3 ACMOSS, puis Support Éditeur.

Le widget utilise uniquement `B_Applications` et la colonne `Statut`.
