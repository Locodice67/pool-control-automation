# 💧 Gestion Intelligente Piscine

![Version](https://img.shields.io/github/v/release/Locodice67/pool-control-automation?label=Version)
![Last Release](https://img.shields.io/github/release-date/Locodice67/pool-control-automation?label=Dernière%20release)
![HACS](https://img.shields.io/badge/HACS-Blueprint-41BDF5)

Blueprint Home Assistant pour gérer la filtration et les traitements de piscine.

## 📦 Versions

Ce blueprint utilise un système de versioning sémantique (`v1.0.0`, `v1.1.0`, etc.).
- La version est définie dans le fichier blueprint YAML (champ `version`)
- Chaque modification du blueprint sur `main` déclenche automatiquement la création d'un tag Git et d'une GitHub Release
- **Home Assistant** : lors de la réimportation du blueprint, la version est affichée
- **HACS** : si vous ajoutez ce dépôt comme dépôt blueprint dans HACS, les mises à jour seront détectées automatiquement

## 🚀 Installation

### Via l'URL directe (HA natif)

1. Aller dans **Paramètres → Automations → Blueprints → Importer un blueprint**
2. Coller l'URL suivante :
   ```
   https://github.com/Locodice67/pool-control-automation/blob/main/blueprints/pool-control-automation.yaml
   ```

### Via HACS (recommandé pour les mises à jour automatiques)

1. Installer [HACS](https://hacs.xyz/) si ce n'est pas déjà fait
2. Aller dans **HACS → Blueprints → 3 points en haut à droite → Dépôts personnalisés**
3. Ajouter : `https://github.com/Locodice67/pool-control-automation`
4. Type : **Blueprint**
5. Cliquer sur **Installer** sur le blueprint "💧 Gestion Intelligente Piscine"
6. Une notification HACS vous préviendra lorsqu'une nouvelle version sera disponible

## 🔄 Mises à jour

- Quand une nouvelle version est publiée sur GitHub, vous recevrez une notification dans Home Assistant
- Via HACS : mettre à jour depuis l'interface HACS
- Via URL directe : réimporter le blueprint (une nouvelle version sera créée)

## 📄 Licence

MIT
