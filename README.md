# 🚀 AVM - Auto Video Maker

## 📌 Introduction

AVM (Auto Video Maker) est un logiciel innovant fonctionnant sous Windows qui exploite la technologie de Voice Cloning et une base de données d'images Google pour générer automatiquement du contenu multimédia. 

### 📝 Description
Le projet, en cours de développement et actuellement en phase pré-alpha, est sous licence GPL-3.0. Il utilise l'invite de commande comme interface utilisateur. Le logiciel AVM (Auto Video Maker) a pour principal objectif de faciliter la création de contenu multimédia. 

Grâce à la puissance de l'IA, il automatise le processus complexe de génération de vidéos. Il crée des scènes, génère des voix à partir des textes contenus dans le fichier `scene.json`, et assemble les vidéos de manière presque autonome, nécessitant une intervention minimale de l'utilisateur. Cette innovation vise à révolutionner la manière dont les vidéos sont créées, en rendant le processus plus rapide et plus efficace.

## 🔧 Installation et Configuration

**Installation du Projet** : Cliquez sur `LANCEUR.bat` pour installer le projet. Cela configurera également l'environnement virtuel et installera les dépendances nécessaires via `lib.py`.

**Mise à jour des Dépendances** : Pour mettre à jour les dépendances après l'installation, cliquez simplement à nouveau sur `LANCEUR.bat`.

## 📂 Structure du Projet

- **assets** : Contient toutes les images nécessaires pour le projet.
- **src** : Contient les scripts, y compris un traducteur automatique pour les mots générés dans l'invite de commande.
- **utils** : Contient des utilitaires, comme un exemple de scène et des requirements alternatifs pour des versions plus stables de certains modules.
- **storyboard** : Le dossier principal où le script s'exécute, contenant un sous-dossier "0ld" pour les anciens projets et un dossier utilisateur pour les scènes.json.

## 💼 Utilisation

Pour utiliser l'AVM, suivez les étapes ci-dessous :

1. **Préparation des Assets** : Préparez manuellement les animations de personnages et les templates de scène.
2. **Génération de Scène** : Utilisez le script pour générer une scène à partir des assets préparés.
3. **Lancement du Logiciel** : Pour lancer le logiciel, cliquez soit sur le raccourci créé sur le bureau lors de l'installation, soit sur `shortcut.bat`.

## 📜 Licence

Ce projet est distribué sous la licence GPL-3.0. Voir le fichier `LICENSE` pour plus de détails.

<!--
## 🤝 Contribution

Le projet est actuellement en phase de développement pré-alpha. Nous accueillons volontiers les contributions pour améliorer le projet. N'hésitez pas à ouvrir des issues ou à soumettre des pull requests.
-->

## 📚 Ressources Externes

| Ressource                       | Lien                                                         |
|---------------------------------|--------------------------------------------------------------|
| Tortoise (Voice Cloning)        | [GitHub](https://github.com/neonbjb/tortoise-tts)            |
| RVC (Voice Cloning)             | [GitHub](https://github.com/RVC-Project/Retrieval-based-Voice-Conversion-WebUI) |
| Roberts Slisans (Liaison des éléments) | [GitHub](https://github.com/rsxdalv/tts-generation-webui)   |
| Base de données d'images Google | [Site Web](https://storage.googleapis.com/openimages/web/download_v7.html) |

<!--
## 🙏 Remerciements

Merci de soutenir et de contribuer à ce projet en développement.
-->
