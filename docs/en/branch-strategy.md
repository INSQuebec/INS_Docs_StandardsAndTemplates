# 🌿 Git Branching Strategy (EN)

This document outlines the recommended branching conventions for projects within the organization.

## 🌱 Main Branch
- `main`: the stable branch reflecting production-ready code.

## 🌾 Development Branch
- `dev`: optional integration branch used in more complex projects.

## 🌿 Feature Branches
- Prefix: `feature/`
- Examples:
  - `feature/import-data`
  - `feature/graph-visualization`

## 🐛 Fix Branches
- Prefix: `fix/`
- Examples:
  - `fix/form-validation`
  - `fix/data-loading-error`

## 🚑 Hotfix Branches
- Prefix: `hotfix/`
- Used to quickly fix bugs in production.

## 🧪 Experiment or Test Branches
- Prefix: `experiment/` or `test/`
- Examples: `experiment/new-ml-model`, `test/deployment-config`

## ✅ Best Practices
- Always branch off from `main` or `dev`
- Open a Pull Request (PR) as soon as the feature is testable
- Delete the branch once the PR merged
