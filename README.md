# Nuxt v3.0.0 Ionic Capacitor Starter Template 
---

Last updated: 03-12-2024

Node Version: 18.20.5

Note: There is an Error in VS Code in nuxt.config.ts ( buildAssetDir ) but it will build ...

Look at the [nuxt 3 documentation](https://v3.nuxtjs.org) to learn more.

## Setup

Make sure to install the dependencies:

# npm
npm install

## Development Server

Start the development server on http://localhost:3000

# npm
npm run dev


## Production

Build the application for production:

# npm
npm run build


Locally preview production build:

# npm
npm run preview


Checkout the [deployment documentation](https://v3.nuxtjs.org/docs/deployment) for information about deployment

Useuful links for building this application:
- [Nuxt 3](https://nuxt.com/)
- [Vue 3](https://vuejs.org)
- [Inonic](https://ionicframework.com)
- [Nuxt/Inonic](https://ionic.nuxtjs.org)
- [Capacitor](https://capacitorjs.com)
- [Nitro.js](https://nitro.unjs.io)
- [Vite](https://vitejs.dev)
- [The Ionic VS Code Extention](https://marketplace.visualstudio.com/items?itemName=ionic.ionic)

Deployment to GitHub Pages - Importants steps to take

- The repository at GitHub have the name: "nuxt-3-ionic-capacitor-part-2-gh-pages"
- Make sure the repository have READ and WRITE permissons which can be found here: "Settings - Actions - General"
- Open the file "nuxt.config.ts" and add the statements "baseURL: '/nuxt-3-ionic-capacitor-part-2-gh-pages/'" and "buildAssetDir: 'assets'"
- Then also add "ssr:false" in the "nuxt.config.ts"
- Open the yml file inside the github action workflow: ".github/workflows/node.js.yml" and make sure it has the following line:
- "run: npm run generate && touch ./.output/public/.nojekyll"
- Now make a commit and go to "Settings - Actions - Pages" and select the branch just created "gh-pages" and click save
- Now make a second commit and take a make sure the GH Actions make the build and deployment
- Finally go to your subdomain at GitHub Pages https://your-root-github-name.github.io/nuxt-3-ionic-capacitor-part-2-gh-pages/ to se the change online
