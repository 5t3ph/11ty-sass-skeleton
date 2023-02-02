![logo](https://repository-images.githubusercontent.com/302921248/58478900-0adf-11eb-8f0b-74be58a898ef)

# 11ty Sass Skeleton

Featuring absolutely nothing beyond a base HTML5 template and the essential setup to watch and compile your Sass alongside 11ty.

Includes minifiying and autoprefixing of styles **during development and on build** using [Lightning CSS](https://lightningcss.dev/). The v3 update ensures processing also occurs during development.

If you have different preferred browser targets, be sure to modify the package `browserslist` or use a `.browserslistrc`.

> **Note** > **As of v3**, Sass + LightningCSS processing now provided [via the standalone plugin](https://github.com/5t3ph/eleventy-plugin-sass-lightningcss) which you can use to add this functionality to an existing 11ty project!

<small>Created by [@5t3ph](https://front-end.social/@5t3ph)</small>

## Development Scripts

**`npm start`**

> Run 11ty with hot reload at localhost:8080, including reload based on Sass changes

**`npm run build`**

> Production build includes minified, autoprefixed CSS

Use this as the "Publish command" if needed by hosting such as Netlify.

## Resources to extend this and learn 11ty

**A variety of tips, tutorials and resources** on [11ty Rocks!](https://11ty.rocks)

**Ensure accessible colors** by adding my [a11y-color-tokens package](https://www.npmjs.com/package/a11y-color-tokens)

**Learn to build an 11ty site in 20 mins** with my [egghead video course](https://5t3ph.dev/learn-11ty) and see how to add a blog and custom data.

**Explore advanced setup of custom data** through my [tutorial on building a community site](https://css-tricks.com/a-community-driven-site-with-eleventy-building-the-site/)
