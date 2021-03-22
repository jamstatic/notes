---
url: https://github.com/evanw/esbuild
tags:
  - js
  - bundler
  - go
---

Un des goulots d'étranglement c'est la génération du code JS qui va bien pour son application, webpack est complet mais complexe à configurer et surtout [ne scale pas bien](https://slashgear.github.io/fr/esbuild-bundler-incroyablement-rapide-et-prometteur/).

On voit apparaître une nouvelle génération d'outils: [[esbuild]], [[snowpack]], [[vite]] dont le but est à la fois de proposer une meilleure DX via des performances accrues (x10 minimum) et des conventions qui font qui cela demande pas ou peu de configuration par défaut. On peut également étendre les possibilités via un [écosystème de plugins](https://github.com/esbuild/community-plugins) grandissant.

Cette nouvelle génération d'outils pour générer du JavaScript coincide avec l'avènement des [[ES Modules]] et de [[WASM]] dans les navigateurs web.

Écrit en Go, esbuild a déjà été adopté par [[Hugo]] pour générer le JS.
