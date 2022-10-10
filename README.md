# Ashia V1 
This repo contains the starter project for ASHIA V1, configured with tailwind CSS, Storybook, ViTest and Nuxt 3. Nuxt 3 is a JavaScript meta framework on Vue 3 [learn more](https://v3.nuxtjs.org/guide/concepts/introduction).

## Getting Started

### Prequisites
Before running this project you will need to install the recommended setup: 

- Node.js (latest LTS version) [download](https://nodejs.org/en/download)
- Visual Studio Code or a similar IDE [download](https://code.visualstudio.com)
- Volar Extension [download](https://marketplace.visualstudio.com/items?itemName=vue.volar)
  - Either enable [Take Over Mode](https://github.com/johnsoncodehk/volar/discussions/471) (recommended)
  - Or add **Typescript Vue Plugin (Volar)** [download](https://marketplace.visualstudio.com/items?itemName=vue.vscode-typescript-vue-plugin)
- Yarn Package Manager
  - If already using NPM install using `npm install -g yarn`
  - Otherwise download yarn [here](https://yarnpkg.com/getting-started/install)

If you already have Node installed check with `node --version` that you are using version **14.16** or above **16.11**

### Installation
Download or clone this repo here [Ashia V1](https://github.com/MichaelWorms/Ashia.git)

Open up a terminal within the project root folder and install the packages using `yarn install`

The project should be ready to run.


### Running Nuxt 3
Using a terminal in the project root after installing the packages, the following commands are used to run Nuxt in different states: 

- `yarn run dev` Starts the application with a local server
- `yarn run build` Packages the nuxt application for deployment
- `yarn run generate` Pre Renders the application and serves the pages as a static website (no SSR)
- `yarn run preview` Starts a server to view the application after running the **build** commands

### Starting Storybook
Storybook can be started in a separate terminal instance to the nuxt application. Open a new terminal in the project and use `yarn run storybook` to start the storybook app

`yarn run build:storybook` will package the storybook for deployment.

### Testing
Multiple tests can be run using the following commands in terminal

- `yarn run test` runs a normal test (currently using Vitest)
- `yarn run test:ui` runs a test with a UI display
- `yarn run test:coverage` runs a test with a coverage report

## Vite
Vite (French word for "quick", pronounced /vit/, like "veet") is a build tool that aims to provide a faster and leaner development experience for modern web projects. 
[learn more](https://vitejs.dev/).

## Vitest
Vitest is a blazing fast unit test framework powered by Vite. Given Jest's massive adoption, Vitest provides a compatible API that allows you to use it as a drop-in replacement in most projects. 
[learn more](https://vitest.dev/).

## Vite-SVG-Loader
Vite plugin to load SVG files as Vue components, using SVGO for optimization.
[learn more](https://github.com/jpkleemans/vite-svg-loader).

## Storybook
Storybook is a tool for UI development. It makes development faster and easier by isolating components. This allows you to work on one component at a time. You can develop entire UIs without needing to start up a complex dev stack, force certain data into your database, or navigate around your application. 
[learn more](https://storybook.js.org/docs/vue/get-started/introduction).

## Tailwind CSS
Tailwind CSS works by scanning all of your HTML files, JavaScript components, and any other templates for class names, generating the corresponding styles and then writing them to a static CSS file. It's fast, flexible, and reliable — with zero-runtime. 
[learn more](https://tailwindcss.com).

## Sass
Sass is the most mature, stable, and powerful professional grade CSS extension language in the world. 
[learn more](https://sass-lang.com/).

## Pinia
Pinia started as an experiment to redesign what a Store for Vue could look like with the Composition API around November 2019. Since then, the initial principles are still the same, but Pinia works for both Vue 2 and Vue 3 and doesn't require you to use the composition API. The API is the same for both except for installation and SSR, and these docs are targeted to Vue 3 with notes about Vue 2 whenever necessary so it can be read by Vue 2 and Vue 3 users! 
[learn more](https://pinia.vuejs.org).

## TypeScript
TypeScript is a strongly typed programming language that builds on JavaScript, giving you better tooling at any scale. 
[learn more](https://www.typescriptlang.org/).
