# GITHUP

## 1. Qu’est-ce que Git et GitHub ?

Git est un outil de gestion de version.  
Il garde l’historique de ton code, un peu comme un **CTRL+Z illimité**.  
GitHub est une plateforme en ligne où tu peux stocker, partager et collaborer sur tes projets Git.

---

## 2. Configuration de Git (identité)

```bash
git config --global user.name "Sadiloop"
git config --global user.email "sadibousow11@gmail.com"

git init                 # Démarrer un projet Git
git status               # Vérifier les fichiers modifiés
git add .                # Préparer tous les fichiers à être commités
git commit -m "Message"  # Sauvegarder une version
git push                 # Envoyer sur GitHub


---

##  Ce que tu peux faire maintenant :
1. Remplace le contenu actuel de ton fichier `README.md` par ce texte (dans VS Code ou TextEdit)
2. Puis dans ton terminal :

```bash
git add README.md
git commit -m "Correction bloc code dans le README"
git push
