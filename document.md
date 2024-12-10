# Générer un PDF avec GitHub Actions

Ce document explique comment utiliser GitHub Actions pour automatiser la génération d'un fichier PDF à partir d'un fichier Markdown, en utilisant **Pandoc** et **LaTeX**. Le workflow GitHub Actions convertira un fichier Markdown en PDF et téléchargera le fichier généré en tant qu'artefact.

---

## Prérequis

Avant de pouvoir utiliser ce workflow, voici ce que tu dois avoir :

- **Un dépôt GitHub** : Ce workflow est conçu pour fonctionner dans un dépôt GitHub.
- **Un fichier Markdown (`.md`)** : Le fichier source que tu souhaites convertir en PDF. Tu peux le créer directement dans ton dépôt ou laisser le workflow créer un fichier de test.
- **Un moteur LaTeX** : GitHub Actions installera automatiquement LaTeX pendant l'exécution du workflow, donc tu n'as rien à installer localement.

---

## Étapes pour utiliser le workflow

1. **Cloner le dépôt**

   Assure-toi d'avoir cloné le dépôt contenant le fichier Markdown que tu veux convertir en PDF. Si tu n'as pas encore de dépôt, crée-en un sur GitHub.

   ```bash
   git clone https://github.com/ton-utilisateur/ton-depot.git
   cd ton-depot
