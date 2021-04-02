Quelle est la différence entre un Single Page Application et un framework hybride?

Par hybrique on entend un mix entre statique et [[SSR]]

- Certaines pages sont générées à la demande lors de la première requête

> _Hydration_ is the process of using client-side JavaScript to add application state and interactivity to server-rendered HTML.

Contexte 

> A typical React application relies on client-side rendering. Instead of parsing HTML to create the [DOM](https://www.gatsbyjs.com/docs/glossary#dom), client-side rendering uses JavaScript to create it. A minimal HTML document serves as the application container, and only contains links to the JavaScript and CSS necessary to render the application.
> Because they make fewer network requests, applications rendered in the browser provide a blazing-fast user experience — after the initial download.
> [Server-side rendering](SSR) makes HTML available to the client _before_ JavaScript loads. Your site visitors can see and read your content even if it is not fully interactive. Server rendering eliminates the blank page problem. Rendered HTML also makes it easier for search engine and social media crawlers to consume your site. Server-side rendering also has a drawback: every URL request requires another round trip to the server.