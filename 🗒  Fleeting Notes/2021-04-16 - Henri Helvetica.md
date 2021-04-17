# La hot révolution des images pour le web

Animateurs: NIcolas Goutay, Frank Taillandier

Servir des pages statiques qui s'affichent aussi vite que possible, c'est une quête sans fin, outre la connexion et la latence réseau qu'on ne maîtrise pas ou le traitement et l'interprétation du JavaScript par le navigateur, la gestion des images est un des aspects les plus impactants pour la performance d'un site web et c'est loin d'être le plus simple. 

Quel format d'image utiliser, pour quel usage, quelle résolution ? Cela peut rapidement devenir un vrai casse-tête. On a d'ailleurs vu apparaître des services comme [Cloudinary](https://cloudinary.com) ou [Imgix](https://www.imgix.com) pour ne citer qu'eux qui se proposent de s'occuper de la partie optimisation de format en fonction du navigateur cible.

[Henri Helevtica](https://twitter.com/HenriHelvetica) est organisateur du meetup Jamstack Toronto et cultive une expertise sur l'évolution des formats d'images pour le web. Dans cet épisode il nous dévoile rapidement l'historique, les coulisses et le support actuel des derniers formats d'images pour le web.

https://twitter.com/HenriHelvetica/status/1383147022069420035

Jusqu'à très récemment, il n'y avait pas trop de questions à se poser, en simplifiant on pouvait se dire: OK, donc JPG pour les photos, GIF pour les animations, PNG et SVG pour les tracés et les illustrations.  Les logiciels d'édition savent gérer l'export dans ces formats historiques. Les choses ont cependant commencé à se compliquer avec l'explosion du web mobile et l'infinitié de résolutions possibles, le retina, la 4K puis la 8K, avec des appareils qui vont de la montre connectée à l'écran extra-large, de quoi donner le tourni...

Les formats d'images plus récents AVIF ou JPEGXL sont un peu plus complexes à gérer: entrte le support encore très disparate dans les navigateurs mais aussi dans les outils d'éditions majeurs comme ceux d'Adobe.  Pour WebP, Il existe néanmoins des plugins pour [Photoshop](https://github.com/webmproject/WebPShop) et  [Figma](https://forum.figma.com/t/webp-support/2206) , tandis cque Sketch supporte nativement [l'export au format webp](https://www.sketch.com/docs/exporting/).  Autant il est simple d'exporter un fichier PNG depuis Figma, autant demander à votre product designer de générer du AVIF reste encore une étape qui sera du ressort de l'équipe technique.

Pourtant les gains de compression sont suffisamment importants pour que l'on adopte dès aujourd'hui [WebP](https://developers.google.com/speed/webp/), un format développé par Google, maintenant [supporté par la quasi totalité des agents utilisateurs](https://caniuse.com/webp).

Pour [AVIF](https://jakearchibald.com/2020/avif-has-landed/), [JPEGXL](https://cloudinary.com/blog/how_jpeg_xl_compares_to_other_image_codecs) ou encore HEIC, le support n'est pas encore aussi large et dépend aussi du CPU de l'appareil utilisé, mais les gains sont en terme de compression et de qualité sont rééls, ce serait dommage de ne pas les inclure dans vos éléments `source`. N'oubliez pas que vous pouvez aussi [déférer le chargement des images](https://addyosmani.com/blog/lazy-loading/) qui ne sont pas visibles par défaut grâce à l'attribut `loading`.

Nous avons à peine eu le temps d'éffleurer le sujet, cela demanderait sans doute une autre émission dédiée à la gestion de ces formats dans la chaîne d'édition du designer et du développeur, mais nous espérons qu'elle aura eu le mérite de vous pousser à vous pencher d'un peu plus près sur ces formats.

Henri pense que c'est une évolution inéluctable et que WebP, AVIF ou JPEGXL vont petit à petit prendre la place de leurs ancêtres… à condition que tous les acteurs jouent le jeu. Vos sites web statiques n'en seront que plus légers, à vous le score parfait dans LightHouse.

Si vous souhaitez en savoir plus sur l'appaarition de ces formats d'images, nous vous conseillons de visionner la conférence qu'avait donné Henri à [We Love Speed](https://www.welovespeed.com/), la conférence des mordus de performance web.

https://www.youtube.com/watch?v=yZBCwI5xGg0

[Réagissez sur Twitter](https://twitter.com/jamstatic_fr).

