# 📘 Standards et modèles de l'INS Québec (FR)

Bienvenue dans la documentation des standards de développement de l'organisation.


## 📚 Standards et bonnes pratiques

- [Conventions de nomenclature](./conventions-nomenclature.md)
- [Stratégie de branches](./strategie-branches.md)
- [Pratiques de sécurité](./pratiques-securite.md)
- [Normes graphique](../INSQuebecNormesGraphiques_2024.pdf)

## 🧩 Modèles

- [Modèle de README](../../templates/README-fr.md)
- [Modèle de CONTRIBUTING](../../templates/CONTRIBUTING-fr.md)
- [Exemple de CODEOWNERS](../../templates/CODEOWNERS-fr)
- [Modèles de PR et d'issues](../../.github/)

## 🚀 Création d'un nouveau dépôt GitHub à l'aide des 🧩 Modèles

1. Créez un nouveau dépôt GitHub **privé** dans l'organisation GitHub INSQuebec en suivant les conventions de nomenclature ci-dessus  
	1a. Choisissez un modèle .gitignore en fonction du langage de programmation utilisé (optionel)
2. Clonez le dépôt localement
   ```bash
   git clone https://github.com/INSQuebec/nom-du-dépôt.git
   ```
3. Téléchargez les fichiers nécessaires depuis le dossier **/templates** de ce dépôt (au minimum le README-fr.md) et le dossier **.github/** (optionnel) puis copiez dans votre dépôt
4. Adaptez le contenu du README.md selon les besoins du projet
5. **Commit** vos additions/modifications et **Push** vers GitHub

💡 *Il est également possible d'ajouter ou modifier les fichiers directement via l'interface web de GitHub. Toutefois, pour copier plusieurs fichiers/dossiers comme `.github/`, un clonage local est recommandé.*

## 🔁 Renommer un dépôt existant

Si un dépôt existant ne respecte pas les conventions de nomenclature, voici comment le renommer et mettre à jour l'origine locale :

1. Allez dans **Paramètres** du dépôt GitHub

   ![https://docs.github.com/assets/images/help/repository/repo-settings-rename.png](https://docs.github.com/assets/cb-28260/mw-1440/images/help/repository/repo-actions-settings.webp)

2. Dans le champ **Repository Name**, écrivez le nouveau nom du dépôt
3. Cliquez **Rename**
4. Dans le dépôt Git sur votre poste local, mettez à jour l'URL GitHub de l'origine :

```bash
git remote set-url origin https://github.com/INSQuebec/nouveau-nom.git
git remote -v  # pour vérifier
```
5. Compléter les étapes 3 à 5 de la section **Création d'un nouveau dépôt** (au besoin)
