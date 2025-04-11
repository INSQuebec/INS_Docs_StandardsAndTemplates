# 📘 INS Québec Standards and Templates (EN)

Welcome to the documentation for our organization's development standards.

## 📚 Standards and Best Practices

- [Naming Conventions](./naming-conventions.md)
- [Branching Strategy](./branch-strategy.md)
- [Security Practices](./security-practices.md)
- [Graphical Standards (FR)](../INSQuebecNormesGraphiques_2024.pdf)

## 🧩 Templates

- [README Template](../../templates/README-en.md)
- [CONTRIBUTING Template](../../templates/CONTRIBUTING-en.md)
- [CODEOWNERS Example](../../templates/CODEOWNERS-en)
- [Issue & PR Templates](../../templates/.github/)

## 🚀 Creating a new GitHub repo using the 🧩Templates

1. Create a new **private** repository in INSQuebec organization, according to the naming conventions above  
	- Choose a `.gitignore` template matching your programming language (optional)
2. Clone it locally
   ```bash
   git clone https://github.com/INSQuebec/repo-name.git
   ```
3. Download files from the `/templates` folder of this repo (minimally the `README-en.md`)
	- You don't need to copy `.github/` folder as the Issue and PR templates are already applied at the organization level
4. Customize the `README.md` as needed for your project (and other files if applicable)
5. **Commit** your additions/changes and **Push** to GitHub

💡 *You can also edit or create files directly via the GitHub web interface. However, cloning the repo locally is recommended when copying multiple files.*

## 🔁 Renaming an Existing Repository

If your existing repository doesn’t follow the naming conventions, you can rename it and update the local remote origin:

1. Go to your GitHub repo's **Settings**

   ![[Screenshot of the GitHub interface for renaming a repo](https://docs.github.com/assets/images/help/repository/repo-settings-rename.png)](https://docs.github.com/assets/cb-28260/mw-1440/images/help/repository/repo-actions-settings.webp)

2. Change the "Repository name" field
3. Click **Rename**
4. In your local clone, update the remote origin URL:

```bash
git remote set-url origin https://github.com/INSQuebec/new-repo-name.git
git remote -v  # to verify
```
5. Complete steps 3 to 5 of **Creating a new GitHub repo** section (if needed)
