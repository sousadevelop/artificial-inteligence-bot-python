# Merlin AI

## Vue d'ensemble

Assistant virtuel pédagogique pour Windows avec reconnaissance vocale, synthèse vocale et raccourcis locaux.

## Objectif

Ce projet de portfolio technique documente le flux implémenté et ses limites actuelles sans modifier le comportement de l'application.

## Stack

Python, pyttsx3, SpeechRecognition, keyboard, python-decouple

## Architecture

Le dépôt conserve sa structure applicative existante. Utilisez le diagramme d'architecture comme point d'entrée pour comprendre les composants implémentés.

See the [architecture diagram](../../assets/diagrams/architecture.mmd).

## Installation

```bash
python -m venv .venv
python -m pip install -r requirements.txt
Copy-Item .env.example .env
```

## Exécution locale

```bash
python main.py
```

## Variables d'environnement attendues

USER, BOT

Use [.env.example](../../.env.example) as a placeholder reference only.

## Structure des dossiers

Le dépôt conserve sa structure applicative existante. Utilisez le diagramme d'architecture comme point d'entrée pour comprendre les composants implémentés.

## Captures d'écran

Reviewed screenshots belong in [assets/screenshots/](../../assets/screenshots/).

## Limites

Il s'agit d'un projet pédagogique de portfolio. Consultez les notes de sécurité et la roadmap avant d'envisager un déploiement.

## Prochaines étapes

See the [roadmap](../../ROADMAP.md).

## Sécurité et contribution

Read [SECURITY.md](../../SECURITY.md) and [CONTRIBUTING.md](../../CONTRIBUTING.md).
