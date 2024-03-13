Jekyll est un des tous premiers générateurs de site statiques. Il a été crée fin 2008 par Tom Preson-Werner, également fondateur de [[GitHub]] et auteur de SemVer, TOML ou plus récemment du framework fullstack [RedwoodJS](https://redwoodjs.com).

Il a servi d'inspiration à de nombreux générateurs, comme [[Hugo]]  ou [[Eleventy]] qui ont repris le principe de stocker ses contenus dans des fichiers Markdown, de pouvoir y associer des données via des entêtes YAML appelées [[front matter]].

Jekyll se veut un outil simple, à la base conçu pour le blog, il supporte également les collections de documents et les fichiers de données. Codé en Ruby, il est doté d'un écosystème de plugins et de thèmes, mais rien de comparable à ce qu'on peut trouver dans le monde JavaScript.

Malgré une syntaxe de templating très simple à apprendre, [[Liquid]], pensée pour les webdesigners, le plus gros handicap de Jekyll reste qu'il est difficile à installer. Ce qui lui est le plus souvent reproché est son temps de génération sur des gros sites, dans les faits, c'est souvent dû à du code ou des plugins tiers non performants.

[Astro](Astro.md)

Maintenu pendant jusqu'à la fin 2017 par Parker Moore et quelques personnes de chez GitHub, puisque Jekyll est le moteur par défaut des [[GitHub Pages]], son développement est en perte de vitesse depuis la version 3.7.x.

Sortie en  2019, la version 4.0 n'a de majeure que le nom et n'apporte guère de nouvelles fonctionnalités, toujours pas d'uniformisation des taxonomies et des catégories entre les posts et les documents de collection, pas de support officiel d'i18n, etc. 

 Jekyll 4.0 exige une version de Ruby > 2.4.0 et intègre le filtre  `relative_url` pour la gestion des liens internes. Ce simple changement fait que près de deux ans après sa sortie, Jekyll v4.0 n'est toujours pas supporté par GitHub Pages. L'équipe en charge de la maintenance s'est contentée de mettre à jour les dépendences, et d'optimiser certaines opérations mémoire, qui font que Jekyll 4.x peut afficher de meilleures performances en fonction du contexte.

Les GitHub Actions permettent d'utiliser Jekyll 4.x et les plugins de son choix, pour ceux qui ont le courage de se frotter à ce genre de configuration.

Le projet semble actuellement gelé et à moins d'un repreneur ou d'une volonté de GitHub d'investir dans cet outil historique, son utilisation risque de se cantonner à ceux qui ont des besoins simples, des blogs et des sites de moins de 3000 pages.

Jekyll reste un très bon moyen de s'initier au développement web et de modéliser simplement des données, mais ne suscite plus trop guère d'engouement de la part de la communauté des développeurs web, qui a préféré se tourner vers des projets basé sur Node et JavaScript comme [[Eleventy]] et qui sont déjà tout aussi matures en restant plutôt facile d'accès, même si l'écosystème n'est pas encore comparable.