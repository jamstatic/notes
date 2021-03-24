Unn générateur de site statique (Static Site Generator ou SSG en anglais) se propose de compiler les fichiers source d'un site web en amont afin de pouvoir les servir depuis un [[CDN]].

Cela procure plusieurs avantages notamment en terme de performance et de sécurité.

Cela a également permis à des sociétés d'hébergement d'innover qui en couplant le pouvoir du contrôle de version de [[Git]] avec un réseau de CDN propose des fonctionnalités comme la prévisualisation de branche de travail ou des déploiements immutables instantanément réversibles.

Leur utilisation longtemps cantonnée aux blogs et aux documentations a commencé à s'étendre de plus en plus avec la promotion des applications découplées et décentralisées faite notamment dès 2015 par la société [[Netlify]] sous le terme fourre-tout de [[Jamstack]].

Aujourd'hui la frontière avec le [[SSR]] est de plus en plus floue car les frameworks d'applications JavaScript comme [[Next.js]] permettent aussi de générer des versions statiques des pages.

Parmi les générateurs les plus populaires on peut nommer: [[Jekyll]] le vétéran, [[Hugo]] le plus rapide, [[Eleventy]] le plus flexible.

Avec la popularité des frameworks applicatifs JavaScript, on a vu également d'autres générateurs émerger comme [[Next.js]] ou [[Gatsby]] basés sur [[React]], et leur pendants [[Vue]] [[Nuxt.js]] et [[Gridsome]]. De nouveaux générateurs d'applications web continuent d'émerger comme récemment [[Svelte Kit]] basé lui sur [[Svelte]].

Il existe des [centaines de générateurs](https://jamstack.org/generators/