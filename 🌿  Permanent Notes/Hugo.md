[Hugo](https://gohugo.io) est un générateur de site statique crée par Steve Francia et maintenu depuis maintenant plusieurs années par Bjørn Erik Pedersen, souvent appelé par son diminutif [bep](https://github.com/bep).

Hugo est écrit en Go, et livré sous forme de fichier binaire, ce qui lui procure une facilité d'installation, et une rapidité d'exécution inégalée. Il est d'usage de dire qu'Hugo peut générer 1000 pages à la seconde, dans les faits cela peut varier en fonction de sa configutation et de ce qui est généré. 

 Hugo n'est pas extensible, on ne peut pas lui ajouter des fonctionnalités. C'est donc un outil dont il faut bien comprendre le périmètre fonctionnel : il est avant tout conçu pour générer des sites de contenus. De par ses performances, Hugo peut générer sans problèmes des dizaines de milliers de pages, comme c'est le cas de [Smashing Magazine](https://www.smashingmagazine.com).

Hugo s'inspire à la base de [[Jekyll]] mais a sû au fil de temps amener tout un tas de concepts qui en font aujourd'hui un outil très complet pour peu que l'on prenne le temps de se familiariser avec toutes les conventions et son langage de templating Go HTML.

Hugo intègre une gestion native des assets (CSS, JS) et seule l'utilisation de PostCSS fait qu'aujourd'hui il puisse nécessiter de recourir à [[npm]]. C'est notamment le cas quand on utilise le framework CSS [[Tailwind]].

Hugo dispose de son propre gestionnaire de dépendances, Hugo modules, permet en effet à la manière des [[EcmaScript Modules (ESM)]] de découper son site en modules réutilisables et des les importer dans ses différents projets. 

Le manque de guides et de HOWTOs fait que peu de membres de la communauté semblent à ce jour partager des modules.

Hugo fonctionne principalement avec des données stockées localement et ne permet pas encore de générer des pages à partir de données récupérées depuis une API tierce. Il est possible de le faire mais cela demande de passer par des fonctions serverless par exemple.

On trouve une vingtaine d'[articles consacrés à Hugo sur Jamstatic.fr](https://jamstatic.fr/categories/hugo/), notamment des articles écrit par [Régis Philibert](https://regisphilibert.com) contributeur et développeur front-end Hugo à temps plein pour l'agence [The New Dyanmic](https://www.thenewdynamic.com).