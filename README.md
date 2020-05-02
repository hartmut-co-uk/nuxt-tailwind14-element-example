# nuxt-tailwind14-element-example

> My fabulous Nuxt.js project

## Live Preview

[Preview here](https://hartmut-co-uk.github.io/nuxt-tailwind14-element-example/)

## Libraries & References :trophy:

- https://github.com/nuxt-community/tailwindcss-module
- https://github.com/tailwindcss/tailwindcss/releases/tag/v1.4.0#built-in-purgecss

## Build Setup

```bash
# install dependencies
$ yarn install

# serve with hot reload at localhost:3000
$ yarn dev

# build for production and launch server
$ yarn build
$ yarn start

# generate static project
$ yarn generate

# generate static for GitHub Pages
$ yarn generate:gh-pages

# deploy `dist` folder for GitHub Pages (branch 'gh-pages')
$ yarn deploy:gh-pages
```

## Deployment: Github Actions > Github Pages

:muscle: This repo has been setup for fully automated deployment of the [Live Preview](https://hartmut-co-uk.github.io/nuxt-vuex-persist-shared-mutations-example/) via *Github Actions* as *Github Pages*.

For details, check following files + references below:   
`nuxt.config.js` -> `routerBase`   
`package.json` -> scripts `generate:gh-pages` + `deploy:gh-pages`   
`.github/workflows/gh-pages-deploy.yml`   
   
### Credits

- https://nuxtjs.org/faq/github-pages/
- https://github.com/L33T-KR3W/push-dir

### References Github :octocat: :sparkles: 

- https://pages.github.com/   
- https://github.com/features/actions   
