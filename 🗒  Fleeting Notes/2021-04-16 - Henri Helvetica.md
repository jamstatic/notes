# Ça s'anime du côté des formats d'images pour le web

Animateurs: NIcolas Goutay, Frank Taillandier

Servir des pages statiques qui s'affichent aussi vite que possible, c'est une quête sans fin, outre la connexion et la latence réseau qu'on ne maîtrise pas ou le traitement et l'interprétation du JavaScript par le navigateur, la gestion des images est un des aspects les plus impactants pour la performance d'un site web et c'est loin d'être le plus simple. 

Quel format d'image utiliser, pour quel usage, quelle résolution ? Cela peut rapidement devenir un vrai casse-tête. On a d'ailleurs vu apparaître des services comme [Cloudinary](https://cloudinary.com) ou [Imgix](https://www.imgix.com) pour ne citer qu'eux qui se proposent de s'occuper de la partie optimisation de format en fonction du navigateur cible.

[Henri Helevtica](https://twitter.com/HenriHelvetica) est organisateur du meetup Jamstack Toronto et cultive une expertise sur l'évolution des formats d'images pour le web. Dans cet épisode il nous dévoile rapidement l'historique, les coulisses et le support actuel des derniers formats d'images pour le web.

https://twitter.com/HenriHelvetica/status/1383147022069420035

Jusqu'à très récemment, il n'y avait pas trop de questions à se poser, en simplifiant on pouvait se dire: OK, donc JPG pour les photos, GIF pour les animations, PNG et SVG pour les tracés et les illustrations.  Les logiciels d'édition savent gérer l'export dans ces formats historiques. Les choses ont cependant commencé à se compliquer avec l'explosion du web mobile et l'infinitié de résolutions possibles, le retina, la 4K puis la 8K, avec des appareils qui vont de la montre connectée à l'écran extra-large, de quoi donner le tourni...

Les formats d'images plus récents WebP, AVIF ou JPEGXL sont un peu plus complexes à gérer: entrte le support encore très disparate dans les navigateurs mais aussi dans les outils d'éditions majeurs comme ceux d'Adobe, [Figma](https://forum.figma.com/t/webp-support/2206) . Autant il est simple d'exporter un fichier PNG depuis Figma, autant demander à votre product designer de générer du webp et du AVIF reste finalement une étape technique qui sera du ressort de l'équipe technique.

Pourtant les gains de compression sont suffisamment importants pour que l'on s'intéresse de plus près à [WebP](https://developers.google.com/speed/webp/), un format développé par Google, maintenant [supporté par la quasi totalité des agents utilisateurs](https://caniuse.com/webp).

Pour [AVIF](https://jakearchibald.com/2020/avif-has-landed/), [JPEGXL](https://cloudinary.com/blog/how_jpeg_xl_compares_to_other_image_codecs) ou HEIC, le support n'est pas encore aussi large et dépend aussi du GPU de l'appareil utilisé, mais les gains sont en terme de compression et de qualité sont rééls, ce serait dommage de ne pas les inclure dans vos élément `source`.

Nous avons à peine eu le temps d'éffleurer le sujet, cela demanderait sans doute une autre émission dédiée à la gestion de ces formats dans la chaîne d'édition du designer et du développeur, mais nous espérons qu'elle aura eu le mérite de vous pousser à regarder de plus près ce qui se fait en 2021, Henri pense que c'est une évolution inéluctable et que ces formats vont petit à petit prendre la place de leurs ancêtres, si tous les acteurs jouent le jeu, vos sites web n'en seront que plus légers.

Si le sujet vous intéresse, nous vous conseillons de visionner la conférence qu'avait donné Henri à We Love Speed sur le sujet.

https://www.youtube.com/watch?v=yZBCwI5xGg0

La discussion continue sur Twitter.

