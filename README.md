# Catalogue public Tools Launcher

Extensions signées par **wood51** pour [Tools Launcher](https://github.com/wood51/tools-launcher).

## Ajouter le catalogue

Dans Tools Launcher : **Catalogue → Source… → Ajouter… → Dépôt Git**.

- Adresse : `https://github.com/wood51/tools-launcher-public-catalog.git`
- Branche : `main`
- Sous-dossier et jeton : laisser vides. Ce catalogue est public.

Actualiser le Catalogue, sélectionner une extension et choisir Installer. Les signatures et empreintes sont vérifiées par le launcher.

## Contenu

| Extension | Version | Usage |
|---|---|---|
| Le Tableau | 1.5.0 | Tableau de tâches partagé, récurrences, corbeille et guide illustré |
| Fichier (Files) | 1.0.1 | Menu de fichiers favoris et éditeur de la liste |
| Nord | 1.0.0 | Thème sombre bleu glacé |
| Océan | 1.0.0 | Thème sombre bleu nuit |
| Papier | 1.0.0 | Thème clair |

Sombre et Clair sont intégrés au launcher. Forêt est volontairement exclu de ce catalogue.

Le Tableau fonctionne aussi sans launcher via `Lancer Le Tableau.cmd` après extraction de son ZIP. Ce mode nécessite Python et les dépendances indiquées dans son README ; ce paquet ne contient pas d'EXE. Les données et sauvegardes des tableaux restent dans le dossier choisi par l'utilisateur.

## Publication du 1er novembre 2026

Le Tableau 1.5.0 ajoute l'édition Catalogue et son lancement Python autonome, les tâches récurrentes, la configuration par onglets, la suppression par glisser-déposer, les dialogues français et le guide illustré. Les tableaux existants et leurs sauvegardes gardent leur emplacement.

Ce dépôt contient uniquement `index.json`, les ZIP signés et cette documentation. Il ne contient aucune donnée utilisateur ni clé privée. Les signatures correspondent à la clé publique wood51 distribuée avec Tools Launcher.
