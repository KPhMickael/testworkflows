# Générer un PDF à partir d'un fichier Markdown

Ce projet fournit une méthode simple pour convertir un fichier Markdown, comme `README.md`, en un fichier PDF. Pour cela, nous utilisons **Pandoc** et **WeasyPrint**.

## Prérequis

Avant de pouvoir générer le fichier PDF, vous devez installer **Pandoc** et **WeasyPrint**. Voici les étapes pour installer les outils nécessaires sur votre machine :

### 1. Installation de Pandoc

Pandoc est un outil en ligne de commande pour convertir des fichiers entre différents formats. Pour installer Pandoc, suivez les instructions ci-dessous :

- **Sur Ubuntu/Debian** :

  ```bash
  sudo apt-get update
  sudo apt-get install pandoc
