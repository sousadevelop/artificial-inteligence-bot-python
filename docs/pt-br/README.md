# Merlin AI

## Visão Geral

Assistente virtual educacional para Windows com reconhecimento de voz, síntese de fala e atalhos locais.

## Problema Resolvido

Explora interação por voz e automação desktop local em um protótipo Python.

## Stack

Python, pyttsx3, SpeechRecognition, keyboard, python-decouple

## Arquitetura

`main.py`: loop de voz e ações locais; `conv.py`: respostas auxiliares.

Consulte o [diagrama de arquitetura](../../assets/diagrams/architecture.mmd).

## Instalação

```bash
python -m venv .venv
python -m pip install -r requirements.txt
Copy-Item .env.example .env
```

## Execução Local

```bash
python main.py
```

## Variáveis de Ambiente Esperadas

USER, BOT

Use [.env.example](../../.env.example) apenas como referência e nunca versione valores reais.

## Estrutura de Pastas

`main.py`: loop de voz e ações locais; `conv.py`: respostas auxiliares.

## Screenshots

Adicione capturas revisadas em [assets/screenshots/](../../assets/screenshots/) sem dados sensíveis.

## Limitações

O protótipo é orientado a Windows e contém caminhos locais específicos. Revise atalhos e permissões antes de executar.

## Próximos Passos

Consulte o [roadmap](../../ROADMAP.md).

## Segurança e Contribuição

Leia [SECURITY.md](../../SECURITY.md) e [CONTRIBUTING.md](../../CONTRIBUTING.md).
