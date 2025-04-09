# 🌿 Stratégie de branches Git (FR)

Voici les conventions de branchement recommandées pour les projets gérés au sein de l'organisation.

## 🌱 Branche principale
- `main` : branche stable correspondant à la version de production.

## 🌾 Branches de développement
- `dev` : branche d’intégration continue (optionnelle, utile pour les projets plus complexes)

## 🌿 Branches de fonctionnalités
- Préfixe : `feature/`
- Exemples :
  - `feature/import-data`
  - `feature/visualisation-graphique`

## 🐛 Branches de correctifs
- Préfixe : `fix/`
- Exemples :
  - `fix/form-validation`
  - `fix/data-loading-error`

## 🚑 Branches d’urgence (hotfix)
- Préfixe : `hotfix/`
- Utilisées pour corriger rapidement des bogues en production.

## 🧪 Branches de test ou d’exploration
- Préfixe : `experiment/` ou `test/`
- Exemples : `experiment/new-ml-model`, `test/deployment-config`

## ✅ Bonnes pratiques
- Toujours créer une branche à partir de `main` ou `dev`
- Ouvrir une Pull Request (PR) dès que la fonctionnalité est testable
- Supprimer la branche une fois la PR fusionnée
