---
title: 'Eleventy Starter Boilerplate Presentation'
description: Everything you need to use this Eleventy Boilerplate template
date: 2020-05-05T00:00:00Z
---

[![Eleventy starter boilerplate banner](/assets/images/posts/eleventy-js-starter-boilerplate.png)](https://creativedesignsguru.com/demo/Eleventy-Starter-Boilerplate/)

🚀 Eleventy Starter Boilerplate is production-ready with SEO-friendly for quickly starting a blog. ⚡️ Built with [Eleventy](https://www.11ty.dev), [ESLint](https://eslint.org), [Prettier](https://prettier.io), [Webpack](https://webpack.js.org), [PostCSS](https://postcss.org), [Tailwind CSS](https://tailwindcss.com) and [Netlify CMS](https://www.netlifycms.org) (optional).

Clone this project and use it to create your own [Eleventy](https://www.11ty.dev) blog. You can check a [Eleventy js blog templates demo](https://creativedesignsguru.com/demo/Eleventy-Starter-Boilerplate/).

The GitHub repository is located [Eleventy Starter Boilerplate](https://github.com/ixartz/Eleventy-Starter-Boilerplate).

### Features

Production-ready in mind:

- 🔥 [11ty](https://www.11ty.dev) for Static Site Generator
- 🎨 Integrate with [Tailwind CSS](https://tailwindcss.com) (with [PurgeCSS](https://purgecss.com), remove unused CSS)
- 💅 [PostCSS](https://postcss.org) for processing [Tailwind CSS](https://tailwindcss.com)
- ⚡️ Lazy load images with [lazysizes](https://github.com/aFarkas/lazysizes)
- ✨ Compress image with [Imagemin](https://github.com/imagemin/imagemin)
- 🎈 Syntax Highlighting with [Prism.js](https://prismjs.com)
- ☕ Minify HTML & CSS with [HTMLMinifier](https://www.npmjs.com/package/html-minifier) and [cssnano](https://cssnano.co)
- ✏️ Linter with [ESLint](https://eslint.org)
- 🛠 Code Formatter with [Prettier](https://prettier.io)
- 💨 Live reload
- 📦 Module Bundler with [Webpack](https://webpack.js.org)
- 🦊 Templating with [EJS](https://ejs.co)
- 🤖 SEO metadata and [Open Graph](https://ogp.me/) tags
- ⚙️ [JSON-LD](https://developers.google.com/search/docs/guides/intro-structured-data) for richer indexing
- 🗺 Sitemap.xml
- ⚠️ 404 page
- 📖 Pagination
- ✅ Cache busting
- 💯 Maximize lighthouse score
- 🌈 Include a FREE minimalist blog theme
- 🗒 Netlify CMS (optional)

### Philosophy

- Minimal code (HTML, CSS & JS). Add what you need
- SEO-friendly
- 🚀 Production-ready

### Requirements

- Node.js and npm

### Premium Themes ([Eleventy Themes](https://creativedesignsguru.com/category/eleventy/))

| [Blue Dark Eleventy Theme](https://creativedesignsguru.com/blue-dark-eleventy-theme/) | [Blue Eclatant Eleventy Theme](https://creativedesignsguru.com/blue-eclatant-eleventy-theme/) |
| --- | --- |
| [![Blue Dark Eleventy Theme premium](https://creativedesignsguru.com/assets/images/themes/blue-dark-mode-eleventy-theme-homepage-xs.png)](https://creativedesignsguru.com/blue-dark-eleventy-theme/) | [![Blue Eclatant Eleventy Theme premium](https://creativedesignsguru.com/assets/images/themes/eclatant-blue-eleventy-theme-homepage-xs.png)](https://creativedesignsguru.com/blue-eclatant-eleventy-theme/) |

| [Blue Modern Eleventy Theme](https://creativedesignsguru.com/blue-modern-eleventy-theme/) | [Blue Minimalist Eleventy Theme](https://creativedesignsguru.com/blue-minimalist-eleventy-theme/) |
| --- | --- |
| [![Blue Modern Eleventy Theme premium](https://creativedesignsguru.com/assets/images/themes/modern-blue-eleventy-theme-homepage-xs.png)](https://creativedesignsguru.com/blue-modern-eleventy-theme/) | [![Blue Minimalist Eleventy Theme premium](https://creativedesignsguru.com/assets/images/themes/minimalist-blue-eleventy-theme-homepage-xs.png)](https://creativedesignsguru.com/blue-minimalist-eleventy-theme/) |

### Getting started

Run the following command on your local environment:

```shell
git clone --depth=1 https://github.com/ixartz/Eleventy-Starter-Boilerplate.git my-project-name
cd my-project-name
npm install
```

Then, you can run locally in development mode with live reload:

```shell
npm run dev
```

Open http://localhost:8080 with your favorite browser to see your blog.

### Project structure

```shell
.
├── public             # Static files
│   └── assets
│       └── images     # Images not needed by Webpack
└── src
    ├── _data          # Eleventy data folder
    ├── _includes
    │   └── layouts    # HTML layout files
    ├── assets         # Assets folder that needs to be processed by Webpack
    │   ├── images
    │   │   └── posts  # Images used in your blog posts (will be compressed by Webpack)
    │   └── styles     # Your blog CSS files
    └── posts          # Your blog posts
```

### Customization

You can easily configure Eleventy Starter Boilerplate. Please change the following file:

- `public/assets/images/logo.png`: your blog logo
- `public/apple-touch-icon.png`, `public/favicon.ico`, `public/favicon-16x16.png` and `public/favicon-32x32.png`: your blog favicon, you can generate from https://favicon.io/favicon-converter/
- `src/_data/site.json`: your blog configuration
- `src/_includes/layouts`: your blog HTML layout
- `src/assets/styles/main.css`: your blog CSS file using Tailwind CSS

### Deploy to production

You can see the results locally in production mode with:

```shell
npm run serve
```

The generated HTML and CSS files are minified. It will also removed unused CSS from [Tailwind CSS](https://tailwindcss.com).

You can create an optimized production build with:

```shell
npm run build
```

Now, your blog is ready to be deployed. All generated files are located at `_site` folder, which you can deploy with any hosting service.

### Deploy to Netlify

Clone this repository on own GitHub account and deploy to Netlify:

[![Netlify Deploy button](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/ixartz/Eleventy-Starter-Boilerplate)

### Remove Netlify files and Netlify CMS

If you don't use Netlify, you can easily remove all Netlify related files:

- `public/admin`, the entier folder
- `src/_includes/layouts/base.ejs`, the loaded script `netlify-identity-widget.js` and the inline script `if (window.netlifyIdentity) { ...`
- `netlify.toml`, the entire file

### Contributions

Everyone is welcome to contribute to this project. Feel free to open an issue if you have question or found a bug.

### License

Licensed under the MIT License, Copyright © 2020

See [LICENSE](https://github.com/ixartz/Eleventy-Starter-Boilerplate/blob/master/LICENSE) for more information.

### GitHub

The GitHub repository is located [Eleventy Starter Boilerplate](https://github.com/ixartz/Eleventy-Starter-Boilerplate) maintained by [Creative Design Guru](https://creativedesignsguru.com).
