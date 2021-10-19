# nuxt-typo3-with-composition-api

Project setup was done through

```bash 
$ npm create nuxt-typo3
$ npm i -S @nuxtjs/composition-api
```

Install deps and start dev server

```bash
$ npm install
$ npm run dev
```

Error output:
```bash
 ERROR  Cannot read property 'includes' of undefined                        

  at node_modules/nuxt-typo3/lib/module.js:26:60
  at Array.findIndex (<anonymous>)
  at Object.Typo3.options.extendPlugins (node_modules/nuxt-typo3/lib/module.js:26:33)
  at Builder.normalizePlugins (node_modules/@nuxt/builder/dist/builder.js:396:44)
  at Builder.generateRoutesAndFiles (node_modules/@nuxt/builder/dist/builder.js:371:42)
  at Builder.build (node_modules/@nuxt/builder/dist/builder.js:319:16)
  at async Object._buildDev (node_modules/@nuxt/cli/dist/cli-dev.js:107:5)
  at async Object.startDev (node_modules/@nuxt/cli/dist/cli-dev.js:65:7)
  at async Object.run (node_modules/@nuxt/cli/dist/cli-dev.js:52:5)
  at async NuxtCommand.run (node_modules/@nuxt/cli/dist/cli-index.js:413:7)
```
