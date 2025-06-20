# AI-Driven Dev - Ressources

Contexte : On se partage beaucoup de liens sur Discord, et il y a des informations qui se perdent.

Objectif : Essayons de tout centraliser dans un même endroit.

- [📝 Nomenclature](#-nomenclature)
  - [Comment rajouter des lignes ?](#comment-rajouter-des-lignes-)
  - [Attribuer le bon statut](#attribuer-le-bon-statut)
  - [Tri des données](#tri-des-données)
- [🚀 Flow et méthodes](#-flow-et-méthodes)
- [🤖 LLM](#-llm)
  - [Desktop](#desktop)
  - [Benchmark](#benchmark)
- [💻 IDE](#-ide)
  - [🎯 Cursor - Ressources spécialisées](#-cursor---ressources-spécialisées)
    - [Extensions](#extensions)
    - [Cursor Rules](#cursor-rules)
    - [Tutoriels et Guides](#tutoriels-et-guides)
- [🤖 Agents](#-agents)
- [🔌 MCP](#-mcp)
- [🧠 Mémoire, tâches et Knowledge Base](#-mémoire-tâches-et-knowledge-base)
  - [Mémoire](#mémoire)
  - [Memory Bank](#memory-bank)
  - [Tasks Management](#tasks-management)
- [⚡ Prompt Engineering](#-prompt-engineering)
  - [Vibe Coding](#vibe-coding)
  - [Langages sémantiques](#langages-sémantiques)
- [📚 Guides](#-guides)
  - [Tutoriels](#tutoriels)
- [👥 Communauté AIDD](#-communauté-aidd)
  - [Présentation](#présentation)
- [🔧 Sans IA](#-sans-ia)
  - [Frontend](#frontend)
    - [Components](#components)
    - [Icônes](#icônes)
  - [Autres (UI/UX, Productivité…)](#autres-uiux-productivité)
- [🗂️ Hub de ressources](#️-hub-de-ressources)

## 📝 Nomenclature

### Comment rajouter des lignes ?

- `Nom` + `lien officiel` (démo ? - optionnelle)
- `Description` : unique, en français et qui reflète la réelle différence avec des outils similaires (Claude vs. GPT ou Cursor vs. Windsurf, soyons très spécifique ici pour les discerner
- `Date` : Ajout ou mise à jour
- `Statut` : (voir ci-dessous)
- `Testé par` @handle GitHub/Discord de vous si vous l'avez testé

### Attribuer le bon statut

Ultra important pour savoir si on a resté la solution et si on la recommande.

|     | Description                                |
| --- | ------------------------------------------ |
| ✅  | Validé et utilisé par la communauté        |
| 🔥  | Trending, on est en train de tester        |
| ❌  | Abandonné, on ne l'utilise plus (+ raison) |

### Tri des données

- Par statut ✅ -> 🔥 -> ❌
- Par nom (ordre alphabétique)

---

## 🚀 Flow et méthodes

Méthodologies et workflows pour optimiser le développement avec l'IA.

| Nom                                                             | **Description**                       | **Statut** | **Testé par** |
| --------------------------------------------------------------- | ------------------------------------- | ---------- | ------------- |
| [rUv-dev](https://github.com/ruvnet/rUv-dev)                    | Architecture RAG avec UI modulaire    |            |               |
| [Claude Code Flow](https://github.com/ruvnet/claude-code-flow/) | Workflow automatisé pour Claude Code  |            |               |
| [SPARC Framework](https://github.com/agenticsorg/sparc2)        | Framework de structuration de prompts |            |               |

## 🤖 LLM

Modèles de langage pour générer du code et assister le développement.

| Nom                                               | **Description**                      | **Statut** | **Testé par** |
| ------------------------------------------------- | ------------------------------------ | ---------- | ------------- |
| [GPT-4.1](https://openai.com/index/gpt-4/)        | Raisonnement étendu, API robuste     | ✅         |               |
| [Claude Sonnet 4](https://claude.ai/)             | Contexte 200k, artefacts interactifs | ✅         |               |
| [Gemini Pro 2.5](https://ai.google.dev/gemini)    | Multimodal natif, intégration Google | ✅         |               |
| [Codestral](https://mistral.ai/fr/news/codestral) | LLM spécialisé code par Mistral      | ❌         |               |

### Desktop

Applications desktop pour interagir avec les LLM.

| Nom                                         | **Description**                        | **Statut** | **Testé par** |
| ------------------------------------------- | -------------------------------------- | ---------- | ------------- |
| [ChatGPT](https://chatgpt.com/)             | GPT avec interface web et canvas       | ✅         | @alexsoyes    |
| [Claude Desktop](https://claude.ai/desktop) | Claude avec MCP et accès système local | ✅         | @alexsoyes    |

### Benchmark

Outils pour évaluer et comparer les performances des IDE IA.

| Nom                                         | **Description**                       | **Statut** | **Testé par** |
| ------------------------------------------- | ------------------------------------- | ---------- | ------------- |
| [Roo Code Evals](https://roocode.com/evals) | Benchmarks de performance pour IDE IA |            |               |

## 💻 IDE

Environnements de développement intégrés avec assistance IA.

| Nom                                                                                | **Description**                         | **Statut** | **Testé par**                 |
| ---------------------------------------------------------------------------------- | --------------------------------------- | ---------- | ----------------------------- |
| [Claude Code](https://claude.ai/code)                                              | CLI officiel d'Anthropic, accès système | ✅         | @thomas, @alexsoyes, @mickael |
| [Cursor](https://cursor.sh/) ([démo](https://www.youtube.com/watch?v=6fBHvKTYMCM)) | VSCode fork, composer multi-fichiers    | 🔥         |                               |
| [Windsurf](https://codeium.com/windsurf)                                           | Mode Cascade, flux de travail AI-first  | ✅         |                               |
| [GitHub Copilot](https://github.com/features/copilot)                              | Autocomplétion, intégré GitHub          | ✅         |                               |
| [Roo Code](https://roocode.com/)                                                   | VSCode fork, interface flottante        | ✅         |                               |
| [Kilo Code](https://kilo.ai/)                                                      | 100% web, collaboration temps réel      | 🔥         |                               |
| [Cline](https://github.com/cline/cline)                                            | Extension VSCode, agent autonome        | ✅         |                               |
| [Codeium](https://codeium.com/)                                                    | Gratuit, modèles propriétaires          | ❌         |                               |

### 🎯 Cursor - Ressources spécialisées

Ressources dédiées pour optimiser l'utilisation de Cursor.

#### Extensions

Extensions pour enrichir les fonctionnalités de Cursor.

| Nom                                                  | **Description**                                                                                  | **Statut** | **Testé par** |
| ---------------------------------------------------- | ------------------------------------------------------------------------------------------------ | ---------- | ------------- |
| [SpecStory](https://docs.specstory.com/introduction) | Sauvegarde automatiquement vos discussions avec Cursor pour enrichir votre base de connaissances | ✅         |               |

#### Cursor Rules

Règles et configurations pour personnaliser le comportement de Cursor.

| Nom                                                                                                      | **Description**                        | **Statut** | **Testé par** |
| -------------------------------------------------------------------------------------------------------- | -------------------------------------- | ---------- | ------------- |
| [Cursor Custom Agents Rules Generator](https://github.com/bmadcode/cursor-custom-agents-rules-generator) | Générateur de règles Cursor            | ✅         |               |
| [Cursor Rules Deep Dive](https://forum.cursor.com/t/a-deep-dive-into-cursor-rules-0-45/60721/2)          | Guide approfondi sur les règles Cursor |            |               |

#### Tutoriels et Guides

Ressources pour apprendre et maîtriser Cursor.

| Nom                                                                                 | **Description**                             | **Statut** | **Testé par** |
| ----------------------------------------------------------------------------------- | ------------------------------------------- | ---------- | ------------- |
| [Cursor Changelog](https://www.cursor.com/changelog)                                | Dernières mises à jour de Cursor            |            |               |
| [Cursor Tips - Builder.io](https://www.builder.io/blog/cursor-tips)                 | Conseils et astuces pour Cursor             |            |               |
| [Cursor Guide - Enlight](https://enlightby.ai/projects/35)                          | Guide complet d'utilisation                 |            |               |
| [Cursor AI for Large Projects](https://getstream.io/blog/cursor-ai-large-projects/) | Guide pour les gros projets                 |            |               |
| [Cursor Tools](https://github.com/eastlondoner/cursor-tools)                        | Noms additionnels pour Cursor               |            |               |
| [GHuntley Stdlib](https://ghuntley.com/stdlib/)                                     | Bibliothèque standard pour le développement |            |               |

## 🤖 Agents

Agents autonomes capables d'exécuter des tâches de développement.

| Nom                                                     | **Description**                        | **Statut** | **Testé par** |
| ------------------------------------------------------- | -------------------------------------- | ---------- | ------------- |
| [Codex](https://openai.com/index/openai-codex/)         | -                                      |            |               |
| [Jules](https://jules.google.com/task)                  | Agent Google, gestion de tâches GitHub |            |               |
| [Open Hands](https://github.com/All-Hands-AI/OpenHands) | Agent open source, ex-Devin            |            |               |

## 🔌 MCP

Model Context Protocol - protocole pour étendre les capacités des LLM.

| Nom       | **Description** | **Statut** | **Testé par** |
| --------- | --------------- | ---------- | ------------- |
| Context 7 | -               |            |               |

## 🧠 Mémoire, tâches et Knowledge Base

Systèmes pour conserver le contexte et gérer les connaissances des projets.

### Mémoire

Outils de mémoire persistante pour les LLM.

| Nom                                                         | **Description**                  | **Statut** | **Testé par** |
| ----------------------------------------------------------- | -------------------------------- | ---------- | ------------- |
| [Mem0 OpenMemory](https://docs.mem0.ai/openmemory/overview) | Mémoire persistante multi-agents |            |               |

### Memory Bank

Implémentations du concept Memory Bank pour différents IDE.

| Nom                                                                                | **Description**                     | **Statut** | **Testé par** |
| ---------------------------------------------------------------------------------- | ----------------------------------- | ---------- | ------------- |
| [RooFlow](https://github.com/GreatScottyMac/RooFlow)                               | Memory Bank avec workflow intégré   |            |               |
| [Roo Code Memory Bank](https://github.com/GreatScottyMac/roo-code-memory-bank)     | Memory Bank original pour Roo Code  |            |               |
| [Cursor Memory Bank](https://github.com/vanzan01/cursor-memory-bank)               | Adaptation Memory Bank pour Cursor  |            |               |
| [Memory Bank MCP](https://github.com/alioshr/memory-bank-mcp)                      | Memory Bank avec protocole MCP      |            |               |
| [RooCode Workspace](https://github.com/enescingoz/roocode-workspace)               | Workspace complet avec mémoire      |            |               |
| [Cursor Bank](https://github.com/tacticlaunch/cursor-bank)                         | Knowledge base pour Cursor          |            |               |
| [Roo Advanced Memory Bank](https://github.com/enescingoz/roo-advanced-memory-bank) | Memory Bank avec fonctions avancées |            |               |
| [Cascade Memory Bank](https://github.com/GreatScottyMac/cascade-memory-bank)       | Memory Bank pour mode Cascade       |            |               |

### Tasks Management

Outils pour organiser et automatiser les tâches de développement.

| Nom                                                                                | **Description**                       | **Statut** | **Testé par** |
| ---------------------------------------------------------------------------------- | ------------------------------------- | ---------- | ------------- |
| [Claude Task Master](https://github.com/eyaltoledano/claude-task-master/tree/main) | Gestion de tâches pour Claude Desktop |            |               |
| [Task Magic](https://github.com/iannuttall/task-magic)                             | Automatisation de tâches répétitives  |            |               |

## ⚡ Prompt Engineering

Techniques et langages pour optimiser la communication avec les LLM.

### Vibe Coding

Approche intuitive du prompt engineering basée sur les "vibes".

| Nom                                                                                       | **Description**                   | **Statut** | **Testé par** |
| ----------------------------------------------------------------------------------------- | --------------------------------- | ---------- | ------------- |
| [Vibe Coding Prompts](https://gist.github.com/mberman84/98fa7d02a2d4c11071bf2bf63faa4713) | Collection de prompts style vibes |            |               |
| [Vibe Coding Guide](https://github.com/EnzeD/vibe-coding/blob/main/README.md)             | Guide pratique du vibe coding     |            |               |

### Langages sémantiques

Langages spécialisés pour structurer les prompts.

| Nom                                                                                          | **Description**              | **Statut** | **Testé par** |
| -------------------------------------------------------------------------------------------- | ---------------------------- | ---------- | ------------- |
| [SudoLang](https://github.com/paralleldrive/sudolang-llm-support/blob/main/sudolang.sudo.md) | Langage pseudo-code pour LLM |            |               |

## 📚 Guides

Ressources éducatives pour apprendre le développement assisté par IA.

### Tutoriels

Formations et guides pratiques.

|                                                                 | **Description**                                               | **Statut** | **Testé par** |
| --------------------------------------------------------------- | ------------------------------------------------------------- | ---------- | ------------- |
| [Formation Cursor](https://www.youtube.com/watch?v=6fBHvKTYMCM) | 1h15 de formation complète et gratuite sur Cursor (avec démo) | ✅         | @alexsoyes    |

## 👥 Communauté AIDD

Membres actifs de la communauté AI-Driven Dev.

### Présentation

Présentations et contributions des membres.

| Membre  | **Description**                                        | **Statut** | **Date** |
| ------- | ------------------------------------------------------ | ---------- | -------- |
| Elodie  | -                                                      |            |          |
| Mickael | <https://app.excalidraw.com/l/7ad586Zigro/6wmQ9YSH4Az> | ✅         |          |

## 🔧 Sans IA

Outils de développement traditionnels mais utiles dans un workflow AI.

### Frontend

Ressources pour le développement frontend.

#### Components

Bibliothèques de composants UI.

| Nom                          | **Description**                | **Statut** | **Testé par** |
| ---------------------------- | ------------------------------ | ---------- | ------------- |
| [UI Pub](https://uipub.com/) | Composants UI prêts à l'emploi |            |               |

#### Icônes

Ressources d'icônes et outils de conversion.

| Nom                                                                                    | **Description**                    | **Statut** | **Testé par** |
| -------------------------------------------------------------------------------------- | ---------------------------------- | ---------- | ------------- |
| [Lobe Hub Icons](https://lobehub.com/fr/icons)                                         | Bibliothèque d'icônes pour AI apps |            |               |
| [PNG to SVG Converter](https://www.adobe.com/express/feature/image/convert/png-to-svg) | Conversion PNG vers SVG            |            |               |
| [Model Icons](https://custom.typingmind.com/tools/model-icons)                         | Icônes spécifiques aux modèles AI  |            |               |

---

### Autres (UI/UX, Productivité…)

Outils divers pour améliorer la productivité.

| Nom                                                                       | **Description**                | **Statut** | **Testé par** |
| ------------------------------------------------------------------------- | ------------------------------ | ---------- | ------------- |
| [Productivity Tools](https://x.com/soltwagner/status/1903310764804542618) | Liste d'outils de productivité |            |               |

## 🗂️ Hub de ressources

Autres dépôts et collections d'outils AI pour développeurs.

| Nom                                                   | **Description**                       | **Statut** | **Testé par** |
| ----------------------------------------------------- | ------------------------------------- | ---------- | ------------- |
| [AI Code Tools](https://aicode.danvoronov.com/tools/) | Répertoire complet d'outils AI coding |            |               |
