---
url: https://github.com/evanw/esbuild
tags:
  - js
  - bundler
  - go
---

Un des goulots d'étranglement c'est la génération du code JS qui va bien pour son application, webpack est complet mais complexe à configurer et surtout [ne scale pas bien](https://slashgear.github.io/fr/esbuild-bundler-incroyablement-rapide-et-prometteur/).

On voit apparaître une nouvelle génération d'outils: [[esbuild]], [[Snowpack]], [[vite]] dont le but est à la fois de proposer une meilleure DX via des [performances accrues](https://esbuild.github.io/) (x10 minimum) et des conventions qui font qui cela demande pas ou peu de configuration par défaut. On peut également étendre les possibilités via un [écosystème de plugins](https://github.com/esbuild/community-plugins) grandissant.

Cette nouvelle génération d'outils pour générer du JavaScript coincide avec l'avènement des [[EcmaScript Modules (ESM)]] et de [[WASM]] dans les navigateurs web.

Écrit en Go, esbuild a déjà été adopté par plus de 18000 dépots GitHub.
Esbuild propose également une API JavaSript.

Projet notables qui utilisent esbuild:

- [[Hugo]] 
- [Just](https://github.com/microsoft/just) une librairie de gestion de tâches de Microsoft