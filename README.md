# Vue VSCode Snippets

## Description

This is a fork of ![Vue VS Code Snippets](https://github.com/sdras/vue-vscode-snippets)
These snippets were built to supercharge a workflow in the most seamless manner possible.

This repo was built for real world use. It strips down the functionalities of the original project, adds custom functionalities and is opinionated to some extent. 
Therefore, it supports the Composition API first, with its use of the `script setup` block. 
It is focused on Vue 3 functionalities only, and is opinionated about TypeScript use in Vue 3. 

_Versions Supported: Vue 3_

## Installation

Clone the repo, install the dependencies via `yarn install` and build it via `yarn build`. You can open the resulting .vsix file in your VS Code editor and right-click to install it.

In the future, I plan to publish it to the VS Code extension store.

You can enable tab completion (recommended) by opening `Code > Preferences > Settings` (on a Mac) and applying `"editor.tabCompletion": "onlySnippets"` to your personal settings

## Snippets

### Vue

| Snippet            | Purpose                                                      |
| ------------------ | ------------------------------------------------------------ |
| `vtempl`           | Template Block                                               |
| `vscript`          | Typescript Setup Script Block                                |
| `vstyle`           | Style Block                                                  |
| `vts`              | Single File Component Setup with Typescript                  |
| `vtss`             | Single File Component Setup with Typescript and Style        |
| `vto`              | Single File Options Component with Typescript                |
| `vtos`             | Single File Options Component with Typescript and Style      |

### Template

| Snippet           | Purpose                             |
| ----------------- | ----------------------------------- |
| `vfor`            | v-for directive                     |
| `vmodel`          | Semantic v-model directive          |
| `vmodel-num`      | Semantic v-model number directive   |
| `von`             | v-on click handler with arguments   |
| `vslot-named`     | Named slot                          |
| `vel-props`       | Component element with props        |
| `vsrc`            | Image src binding                   |
| `vstyle`          | Inline style binding                |
| `vstyle-obj`      | Inline style binding with objects   |
| `vclass`          | Class binding                       |
| `vclass-obj`      | Class binding with objects          |
| `vclass-obj-mult` | Multiple conditional class bindings |
| `vanim`           | Transition component with JS hooks  |
| `vnuxtl`          | Nuxt Routing Link                   |
| `vroutename`      | router-link Named Routing           |
| `vroutenameparam` | router-link Named with Parameters   |
| `vroutepath`      | router-link Path Routing Link       |
| `vemit-child`     | Emit event from child component     |
| `vemit-parent`    | Emit event to parent component      |

### Script

| Snippet           | Purpose                                                                  |
| ----------------- | ------------------------------------------------------------------------ |
| `vdata`           | Component data as a function                                             |
| `vmethod`         | Vue method                                                               |
| `vcomputed`       | Vue computed property                                                    |
| `vwatcher`        | Vue watcher with new and old value args                                  |
| `vbeforecreate`   | beforeCreate lifecycle method                                            |
| `vcreated`        | created lifecycle method                                                 |
| `vbeforemount`    | beforeMount lifecycle method                                             |
| `vmounted`        | vmounted lifecycle method                                                |
| `vbeforeupdate`   | beforeUpdate lifecycle method                                            |
| `vupdated`        | updated lifecycle method                                                 |
| `vbeforedestroy`  | beforeDestroy lifecycle method                                           |
| `vdestroyed`      | destroyed lifecycle method                                               |
| `vprops`          | Props with type and default                                              |
| `vimport`         | Import one component into another                                        |
| `vimport-dynamic` | Import one component that should be lazy loaded by webpack               |
| `vcomponents`     | Import one component into another within the export statement            |
| `vimport-export`  | Import one component into another and use it within the export statement |
| `vmapstate`       | import mapState from Vuex into vue component component                   |
| `vmapgetters`     | import mapGetters from Vuex into vue component component                 |
| `vmapmutations`   | import mapMutations from Vuex into vue component component               |
| `vmapactions`     | import mapActions from Vuex into vue component component                 |
| `vfilter`         | Vue filter                                                               |
| `vmixin`          | Create a Vue Mixin                                                       |
| `vmixin-use`      | Bring a mixin into a component to use                                    |
| `vc-direct`       | Vue create a custom directive                                            |
| `vimport-lib`     | Import a library                                                         |
| `vimport-gsap`    | Import GreenSock                                                         |
| `vanimhook-js`    | Using the Transition component JS hooks in methods                       |
| `vcommit`         | Commit to Vuex store in methods for mutation                             |
| `vdispatch`       | Dispatch to Vuex store in methods for action                             |
| `vtest`           | A simple unit testing component                                          |

### Vue Composition API

| Snippet             | Purpose                                               |
| ------------------- | ----------------------------------------------------- |
| `v3reactive`        | Vue Composition API - reactive                        |
| `v3reactive-setup`  | Vue Composition API - reactive with setup boilerplate |
| `v3computed`        | Vue Composition API - computed                        |
| `v3watch`           | Vue Composition API - watcher single source           |
| `v3watch-array`     | Vue Composition API - watch as array                  |
| `v3watcheffect`     | Vue Composition API - watchEffect                     |
| `v3ref`             | Vue Ref                                               |
| `v3onmounted`       | Lifecycle hook - onMounted                            |
| `v3onbeforemount`   | Lifecycle hook - onBeforeMount                        |
| `v3onbeforeupdate`  | Lifecycle hook - onBeforeUpdate                       |
| `v3onupdated`       | Lifecycle hook - onUpdated                            |
| `v3onerrorcaptured` | Lifecycle hook - onErrorCaptured                      |
| `v3onunmounted`     | Lifecycle hook - (destroyed) onUnmounted              |
| `v3onbeforeunmount` | Lifecycle hook - (beforeDestroy) onBeforeUnmount      |
| `v3useinoptions`    | Use Composition API in Options API                    |

### Vuex

| Snippet         | Purpose                        |
| --------------- | ------------------------------ |
| `vstore`        | Base for Vuex store.js         |
| `vgetter`       | Vuex Getter                    |
| `vmutation`     | Vuex Mutation                  |
| `vaction`       | Vuex Action                    |
| `vmodule`       | Vuex Module                    |
| `vstore-import` | Import vuex store into main.js |
| `vstore2`       | Updated Base for Vuex store    |

### Vue Router

| Snippet              | Purpose                                       |
| -------------------- | --------------------------------------------- |
| `vrouter`            | Vue Router base                               |
| `vscrollbehavior`    | Vue Router scrollBehavior                     |
| `vbeforeeach`        | Vue Router global guards beforeEach           |
| `vbeforeresolve`     | Vue Router global guards beforeResolve        |
| `vaftereach`         | Vue Router global guards afterEach            |
| `vbeforeenter`       | Vue Router per-route guard beforeEnter        |
| `vbeforerouteenter`  | Vue Router component guards beforeRouteEnter  |
| `vbeforerouteupdate` | Vue Router component guards beforeRouteUpdate |
| `vbeforerouteleave`  | Vue Router component guards beforeRouteLeave  |

### Vue Config

| Snippet   | Purpose                                                              |
| --------- | -------------------------------------------------------------------- |
| `vplugin` | Import a plugin to main.js or plugins file                           |
| `vconfig` | vue.config.js file, example imports a sass file into every component |

### Nuxt Config

| Snippet | Purpose                                                 |
| ------- | ------------------------------------------------------- |
| `nfont` | link to include fonts in a nuxt project, in nuxt-config |
| `ncss`  | link to css assets such as normalize                    |

### Nuxt Page

| Snippet           | Purpose                          |
| ----------------- | -------------------------------- |
| `nasyncdata`      | Nuxt asyncData                   |
| `nasyncdataaxios` | Nuxt asyncData with Axios module |
| `nfetch`          | Nuxt Fetch                       |
| `nfetchaxios`     | Nuxt Fetch with Axios module     |
| `nhead`           | Nuxt Head                        |
| `nparam`          | Nuxt Route Params                |

### Extra (plaintext)

| Snippet     | Purpose                 |
| ----------- | ----------------------- |
| `gitignore` | .gitignore file presets |

## Contributing

This is an open source project open to anyone. Contributions are welcome [github](https://github.com/sdras/vue-vscode-snippets)

If you are contributing a snippet, please be sure to add the documentation for it in the tables in the README, the pull request cannot be accepted without this addition. Thanks!
