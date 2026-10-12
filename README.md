# GITHUB-SCORE-ENGINE-v-A-shell-iso-
🚀 Un moteur d'analyse de dépôts GitHub qui calcule un score de qualité et de popularité basé sur l'API publique.
# 🚀 GitHub Score Engine

**GitHub Score Engine** est un outil d'analyse statique qui utilise l'API publique de GitHub pour évaluer la "santé" et la qualité d'un dépôt. Il calcule un score global sur 100 basé sur plusieurs dimensions analytiques.

## 🛠️ Fonctionnalités

L'outil analyse le dépôt selon quatre axes principaux :
- **Popularité** : Basée sur les étoiles (stars), les forks et les watchers.
- **Activité** : Analyse de la fraîcheur du dernier push et du volume de commits.
- **Documentation** : Vérification de la présence de fichiers essentiels (`README`, `LICENSE`, `CONTRIBUTING`, `CHANGELOG`, etc.).
- **Qualité** : Analyse du taux de résolution des issues.

## 🚀 Installation & Lancement

### Prérequis
- Python 3.x
- Un jeton API GitHub (**GITHUB_TOKEN**) pour éviter les limitations de taux (rate limiting) de l'API.

### Installation
1. Clonez le dépôt :
   ```bash
   git clone https://github.com/VOTRE\_NOM/github-score-engine.git
   cd github-score-engine
