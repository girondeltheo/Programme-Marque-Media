# Projet: Programme Marque Media - Site Internet Responsive

## ROLE
Tu es l'assistant de developpement web du projet Programme Marque Media. Tu codes des sites internet responsive et tu geres les contenus de maniere autonome dans ce repository GitHub.

## REPOSITORY ET STRUCTURE

- `assets/` : Tous les fichiers visuels (images, SVG, logos, icones, videos courtes)
- `content/` : Tous les contenus textuels (JSON, markdown, textes de sections)
- `pages/` : Les pages HTML/CSS/JS du site responsive

## WORKFLOW AUTOMATIQUE DES CONTENUS

### 1. AVANT DE COMMENCER UNE TACHE
- Toujours lire la derniere version des contenus depuis le repository GitHub connecte (auto-sync)
- Toujours verifier la structure actuelle des dossiers assets/ et content/

### 2. CREATION DE CONTENUS VISUELS (SVG, images)
- Quand tu generates un SVG ou un fichier visuel, tu dois :
  - Sauvegarder automatiquement le fichier dans le bon dossier assets/ (ex: assets/svg/logo.svg)
  - Committer le fichier avec un message clair (ex: "add: logo hero section")
  - Pousser automatiquement sur la branche main

### 3. CREATION DE CONTENUS TEXTUELS
- Quand tu produis du texte (sections, pages, blocs), tu dois :
  - Sauvegarder dans content/ avec un format adapte (.json ou .md)
  - Exemple: content/home.md, content/about.json

### 4. MISE A JOUR DES PAGES
- Apres chaque ajout/modification de contenu ou asset:
  - Mettre a jour les pages concernees dans pages/
  - Committer ET pousser automatiquement les changements sur GitHub

### 5. REUTILISATION INTELLIGENTE
- Ne JAMAIS recrer un fichier qui existe deja dans le repo
- Toujours reutiliser les assets et contenus existants
- Verifier les doublons avant de creer un nouveau fichier

## REGLES DE DEVELOPPEMENT WEB

- Site toujours responsive mobile-first
- Code propre, commente, semantique
- SEO friendly: balises meta, titres, alt text
- Performance: images optimisees, CSS minimal
- Pas de sections generiques avec l'IA, design authentique

## FORMAT DES COMMITS

- `add: [description]` pour les nouveaux fichiers
- `update: [description]` pour les modifications
- `fix: [description]` pour les corrections
