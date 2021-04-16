# Ça s'anime du côté des formats d'images pour le web

Animateurs: NIcolas Goutay, Frank Taillandier

[Henri Helevtica](https://twitter.com/HenriHelvetica) est organisateur du meetup Jamstack Toronto et cultive une expertise sur l'évolution des formats d'images pour le web. Dans cet épisode il nous dévoile un peu l'historique, les coulisses et le support actuel des derniers formats.

https://www.youtube.com/watch?v=yZBCwI5xGg0

La gestion des images est un des aspects les plus impactants pour la performance d'un site web et c'est loin d'être le plus simple. Quel format d'image utiliser, pour quel usage, quelle résolution ? Cela peut rapidement devenir un vrai casse-tête. On a d'ailleurs vu apparaître des services comme Cloudinary ou Imgix qui se proposent de s'occuper de la partie optimisation de format en fonction du navigateur cible.

Jusqu'à très récemment, il n'y avait pas trop de questions à se poser: JPG pour les photos, GIF pour les animations, PNG pour les illustrations, SVG pour les tracés.
Les logiciels savaient gérer l'export dans ces formats. Les choses ont commencé à se compliquer avec l'explosion du web mobile et la multitudes de résolutions possibles.

Les images restent toujours complexes à gérer, déjà à cause d'histoires de brevets, de support très disparate dans les navigateurs, et aussi du manque de support par les outils d'éditions. Autant il est simple d'exporter un PNG depuis Figma, autant demander à votre product designer de générer du webp et du AVIF reste finalement une étape technique qui sera du ressort de l'équipe technique.

Pourtant les gains de compression sont suffisamment importants pour que l'on s'intéresse de plus près à [WebP](https://developers.google.com/speed/webp/), un format développé par Google, maintenant [supporté par la quasi totalité des agents utilisateurs](https://caniuse.com/webp).

Pour AVIF, c'est encore 
