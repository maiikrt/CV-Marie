# 📚 Documentation du projet – CV de Marie Eckert-Bergerin

---

## 🎯 Objectif du projet

Ce projet a été réalisé dans le cadre d'un exercice pédagogique. L'objectif est d'apprendre à :

- Utiliser le langage **Markdown** pour structurer un document.
- Manipuler un **répertoire Git** à l’aide de **GitHub Desktop**.
- **Déployer** le contenu sous la forme d’un site web **statique** via **GitHub Pages**.
- Organiser un dépôt de manière **claire et propre**.

---

## 🗂️ Structure du dépôt

| Élément | Rôle |
|--------|------|
| `README.md` | Fichier d'accueil du dépôt : il présente le projet, le lien du site, et résume le contenu du CV. |
| `docs/index.md` | Le fichier principal contenant le CV au format Markdown. |
| `docs.md` | Le présent fichier : il explique les choix techniques, outils et mise en forme. |
| `assets/photo.jpg` | Photo de profil affichée dans le CV. |
| `.gitignore`, `.gitattributes` | Fichiers de configuration Git |
| `LICENSE` | Licence du projet |

---

## 🛠️ Choix techniques

### Langage

Le **Markdown** a été utilisé pour sa simplicité et sa lisibilité. C’est un langage léger idéal pour créer des documents structurés sans code complexe.

### Organisation

- Le fichier principal (`index.md`) est placé dans un dossier `docs/` pour correspondre à la convention de GitHub Pages.
- Les images sont placées dans un dossier `assets/` pour séparer contenu et médias.
- L’image est insérée avec **balise HTML** afin de contrôler sa taille et l’esthétique :
  ```html
  <img src="/assets/photo.jpg" width="150" style="border-radius: 8px;" />
