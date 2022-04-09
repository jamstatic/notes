---
date: 2021-04-10
source: https://www.youtube.com/watch?v=mgkwZqVkrwo
tags: 
  - webdev
  - js
  - static
---
Fred Schott, l'auteur de [[Snowpack]] et Skypack, des outils qui tirent parti des [[EcmaScript Modules (ESM)]]  présente une preview d' [Astro](https://astro.build/) un outil qui  adopte une "nouvelle " architecture pour le développment d'applications web (static first).

Avec Astro, tout est [rendu côté serveur ](SSR) par défaut, on sert donc du HTML et pas de [JavaScript] et le framework offre la possibilité d’opter sur la manière d’importer du JavaScript quand c’est nécessaire. On bénéficie d'une  expérience de développement par composants tout en s'assurant une meilleure performance par défaut. 

Sous le capôt c'est un appel à un script JS et à `interactionObserver` qui permet de charger un composant seulement lorsqu'il est visible sur la page par exemple.

C’est très similaire à la philosophie des générateurs comme Eleventy mais ici on peut utiliser Astro avec son framework JS préféré ([[React]], Vue, Svelte, etc.). Fred Schott décrit Astro comme la conjugaison d’[[Eleventy]] et [[Snowpack]].

Astro s'inspire d'une [architecture en ilôts](https://jasonformat.com/islands-architecture/)  : chaque composant est un ilôt et Astro simplifie l'hydratation partielle.