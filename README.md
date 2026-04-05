# Le Garage de Mat — Portfolio

Portfolio personnel auto-généré depuis GitHub, conçu pour exposer des projets avec un design sombre et élaboré.

## Présentation

Site statique mono-fichier (`index.html`) qui récupère dynamiquement les dépôts GitHub publics via l'API GitHub et les présente sous forme de cards filtrables. Aucun backend, aucune dépendance externe installée — juste du HTML/CSS/JS pur.

## Fonctionnalités

- Récupération automatique des repos GitHub via l'API REST
- Filtres par langage et recherche full-text
- Vue détaillée par projet (README, CHANGELOG, infos)
- Mode admin protégé par mot de passe (token GitHub, configuration des repos)
- Design glassmorphism dark — tokens Material You adaptés
- 100 % responsive

## Structure

```
le-garage-de-mat/
├── index.html        # Application complète (HTML + CSS + JS inline)
├── screenshots/      # Captures d'écran
├── README.md         # Ce fichier
└── CHANGELOG.md      # Historique des modifications (généré automatiquement)
```

## Utilisation

Ouvrir `index.html` dans un navigateur ou déployer sur GitHub Pages. Aucune installation requise.

Pour configurer le token GitHub et la liste des repos affichés, accéder au panneau **Config** (icône ⚙) depuis le site.

## Déploiement

Le site est hébergé sur GitHub Pages. Tout push sur la branche `main` déclenche une mise à jour automatique.

---

*CHANGELOG généré automatiquement à chaque commit.*
