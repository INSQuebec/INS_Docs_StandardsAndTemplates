# 🔒 Pratiques de sécurité (FR)

Voici les pratiques recommandées pour assurer la sécurité des dépôts GitHub de l'organisation.

## 🔐 Gestion des accès
- Créer les dépôts en mode privé par défaut
- Limiter les collaborateurs aux personnes nécessaires
- Révoquer l’accès dès qu’un collaborateur quitte un projet

## 🧪 Validation et revue de code
- Exiger au moins une revue avant toute fusion (via règles de branche)
- Interdire les pushes directs sur `main` ou `dev`
- Activer les vérifications de tests automatisés

## 🛡️ Sensibilité des données
- Ne jamais inclure de données personnelles, confidentielles ou médicales dans le dépôt
- Ajouter un fichier `.gitignore` pour exclure les fichiers sensibles (ex : `.env`, fichiers Excel, etc.)
- Utiliser des secrets GitHub pour stocker des clés API ou des tokens

## 🔄 Mises à jour
- Mettre à jour régulièrement les dépendances (via Dependabot ou autre)
- Documenter les mises à jour de sécurité critiques
