A few weeks ago, Sean C. Davis wrote an article called ["The Evolution and the redefinition of Jamstack"](https://www.seancdavis.com/blog/jamstack-evolution-and-redefinition/), he had previously wrote [WTF is Jamstack](https://www.seancdavis.com/blog/wtf-is-jamstack/) back in 2018.

You can tell from both title that Jamstack is a very broad term coined by Netlify, for marketing purpose. It's a generic term to describe Netlify service, but the name sticked and is now use by every company out there trying to promote it's service that can be used through an API.

As Jeff Escalante wrote in a response, *JavaScript, APIs and Markup can be used on every website*,  you can build a IOS app with the very same API and it wouldn't be fall under the definition. Because the definition has to correspond to Netlify's current capabilities: static assets served from a CDN, possibly running serverless functions also on the edge (as close as possible to the end user) to deliver very performant websites.

A lot of tools allow you to generate a static output, your IDE if you write raw HTML, the first generation of static site generators that includes amongst many others Jekyll, Hugo and Eleventy can do that. React Frameworks like Next.js or Gatby, Vue frameworks like Nuxt.js or Gridsome, Sveltte Kit, the latest tool from the Snowpack team called Astro can do that. The common thing about all those tools is that they can output **static** assets and coupled to Git, it allows you to leverage à continuous deployment service (Netlifly, but also Vercel, CloudFlare, GitHub, etc.). Before Netlify coined the term, those sites were simply refered as **static** and it was not pejorative. It was simply describing the frontend output, generate with very modern tools and workdlows.

Netlify's vision was always to democratize [**microservices**](https://www.netlify.com/blog/2019/11/18/what-are-microservices/) architectures, an they added **serverless** [functions](https://www.netlify.com/blog/2018/03/20/netlifys-aws-lambda-functions-bring-the-backend-to-your-frontend-workflow/) (an abstraction of AWS Lambda) in 2018, and later background functions, and now On Demand Rendering (also based on AWS Lambda).

So yeah, in 2021 a site hosted on Netllify can mix all of those, static assets, serverless functions and on demand rendering, which is great and as demonstrated by Zach Leatherman on Eleventy's website can [save a lot of time on your builds](https://twitter.com/zachleat/status/1402687220541165568), if your assets don't change between builds.

While the initial promise was that it was easier to scale a static website, builds were always the bottlneck. Even today deploying a large static website with more than 10K pages can be painful and frameworks like Next.js or [Remix Run](https://remix.run/features) choosed to address this problem by leveraging Server Side Rendering or HTTP Caching.

So one thing is for sure, you don't build large websites in 2021 like you did in 1997 when I started coding HTML;

- Component-based approach has gone mainstream, large websites are often built with Deisgn Systems, more and more are using **Web Components**.
- Client-side JavaScript has evolved, and you can now import **ESM modules** in browsers, and load some JavaScript only when necessary 
- You can take leverage of Services Workers and serve your site as a **Progressive Web App**
- You have thousands of **APIs** at your disposal to enrich your site functionality: payment, shopping cart, search, even databases are now available as a service, more and more are available through ** GraphQL**.
- Control version systems like Git have changed the way we collaborate and ship code, many services allow you to deploy automatically on push, allowing for **atomic deployments** on some continuous deployment services.
- You can execute your code in the Cloud, serverless functions were first introduced by Amazon and now Microsoft, Google and other proviers all compete on that front. Netlify is an abstraction on top of those providers.

Software is hard, and Marketing does its best to sell products to developers, but before using one of those vague marketing term, please think twice on what problem you need to solve first, don't start from a solution (I'm gonna build a React website, or I'm gonna build a "Jamstack site" (WTF is that?), embrace progressive enhancement and web standards, learn the basics, before thinking you need to use all of the latest tech to get a job. 

There's a good chance a decoupled front-end served from the edge might make sense if you're mainly servnig content to users, but with SSR, Serveless, Database as a Service, microservices, the frontier between purely static and purely dynamic are more and more blurry and going hybrid might be the key for large projects, serve as many static assets as you can from the edge and rely on servers to render dynamic pages when you need to. 