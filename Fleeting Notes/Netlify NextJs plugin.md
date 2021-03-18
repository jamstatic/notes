---
date: {{ date }}
url: https://www.netlify.com/blog/2021/03/16/try-the-new-essential-next.js-plugin-now-with-auto-install/
tags:
 - netlify
 - nextjs
---

Le plugin est maintenant installé automatiquement quand Netlify détecte un projet Next.js. Le support des fonctionnalités de Next.js est *presque* complet, excepté pour le [mode de generation statique incrémentale que Patrick Faramaz pour un projet de 11 000 pages](https://jamstatic.fr/2021/03/09/11000-pages-statiques/#la-r%C3%A9g%C3%A9n%C3%A9ration-incr%C3%A9mentale-%C3%A0-la-rescousse).

Cassidy Williams, qui s'occupe des DevRel Next.js a indiqué dans un [article](https://www.netlify.com/blog/2021/03/08/incremental-static-regeneration-its-benefits-and-its-flaws/) que Netlify tenait à ce que les déploiements restent atomiques et immutables afin de pouvoir revenir en arrière facilement. Hors ISR peut entraîner des problèmes de cache pour les pages générées à la volée. Ils sont en train de travailler sur le sujet, à suivre....

Netlify est forcé de supporter le framework React le plus populaire pour ne pas perdre trop d'utilisateurs de sa plateforme. Couplé aux différentes annonces de Gatsby, de Cloudflare Pages, etc.  etlify est petit à petit en train de perdre une partie de sa base d'utilisateurs qui se morcèlent sur différentes plateformes, plus ou moins liées à un framework (Next.js et Gatsby).

Question: Quel intérêt à utiliser Netlify au lieu de Vercel pour un projet Next.js?

- Netlify Identify?


