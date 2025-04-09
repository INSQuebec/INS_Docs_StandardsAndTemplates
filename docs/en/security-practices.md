# 🔒 Security Practices (EN)

These are recommended practices to ensure the security of our organization’s GitHub repositories.

## 🔐 Access Management
- Create repositories as private by default
- Limit collaborators to only those who need access
- Revoke access when a collaborator leaves the project

## 🧪 Code Reviews & Checks
- Require at least one review before merging (via branch protection rules)
- Disallow direct pushes to `main` or `dev`
- Enable automated test checks

## 🛡️ Data Sensitivity
- Never commit personal, confidential, or medical data
- Add a `.gitignore` file to exclude sensitive files (e.g., `.env`, Excel files)
- Use GitHub Secrets to store API keys or tokens

## 🔄 Updates
- Regularly update dependencies (e.g., via Dependabot)
- Document and communicate critical security updates
