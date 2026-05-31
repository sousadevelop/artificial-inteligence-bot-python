# Merlin AI

## Descripción general

Asistente virtual educativo para Windows con reconocimiento de voz, síntesis de voz y accesos directos locales.

## Objetivo

Este proyecto de portafolio técnico documenta el flujo implementado y sus límites actuales sin modificar el comportamiento de la aplicación.

## Stack

Python, pyttsx3, SpeechRecognition, keyboard, python-decouple

## Arquitectura

El repositorio conserva su estructura de aplicación existente. Use el diagrama de arquitectura como punto de entrada para comprender los componentes implementados.

See the [architecture diagram](../../assets/diagrams/architecture.mmd).

## Instalación

```bash
python -m venv .venv
python -m pip install -r requirements.txt
Copy-Item .env.example .env
```

## Ejecución local

```bash
python main.py
```

## Variables de entorno esperadas

USER, BOT

Use [.env.example](../../.env.example) as a placeholder reference only.

## Estructura de carpetas

El repositorio conserva su estructura de aplicación existente. Use el diagrama de arquitectura como punto de entrada para comprender los componentes implementados.

## Capturas de pantalla

Reviewed screenshots belong in [assets/screenshots/](../../assets/screenshots/).

## Limitaciones

Este es un proyecto educativo de portafolio. Revise las notas de seguridad y el roadmap antes de considerar un despliegue.

## Próximos pasos

See the [roadmap](../../ROADMAP.md).

## Seguridad y contribución

Read [SECURITY.md](../../SECURITY.md) and [CONTRIBUTING.md](../../CONTRIBUTING.md).
