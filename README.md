# SSG example
This project uses the very simple Vite-Vue template to demonstrate how to configure it to generate a static site, that is, to generate a first render of your website when building, so that search engines and browsers can have a preview of your site by simply loading the index.html file

The full tutorial can be found here: https://frankorellana.medium.com/creating-ssg-page-with-vue-and-vite-8478fe2e4ec6

## Develop and Build
To work with this example, simply clone it, install the dependencies and run `npm run dev` (or yarn or pnpm):

```bash
git clone https://github.com/frank-orellana/my-first-ssg.git
npm install
npm run dev
```

To build, run the build command and then deploy to a web server or preview the files in the dist folder:
```bash
npm run build
npm run preview # runs a server with the files in the dist folder
```

# Vue 3 + Vite

This template should help get you started developing with Vue 3 in Vite. The template uses Vue 3 `<script setup>` SFCs, check out the [script setup docs](https://v3.vuejs.org/api/sfc-script-setup.html#sfc-script-setup) to learn more.

## Recommended IDE Setup

- [VSCode](https://code.visualstudio.com/) + [Volar](https://marketplace.visualstudio.com/items?itemName=johnsoncodehk.volar)
