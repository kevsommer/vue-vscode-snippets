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
| `von`             | v-on click handler with arguments   |
| `vslot-named`     | Named slot                          |
| `vel-props`       | Component element with props        |
| `vsrc`            | Image src binding                   |
| `vclass`          | Class binding                       |
| `vclass-arr`      | Class binding with arrays           |
| `vclass-obj`      | Class binding with objects          |

### Script

| Snippet           | Purpose                                                                  |
| ----------------- | ------------------------------------------------------------------------ |
| `vdata`           | Component data as a function                                             |
| `vmethod`         | Vue method                                                               |
| `vcomputed`       | Vue computed property                                                    |
| `v2watcher`       | Vue watcher with new and old value args                                  |
| `vbeforecreate`   | beforeCreate lifecycle method                                            |
| `vcreated`        | created lifecycle method                                                 |
| `vbeforemount`    | beforeMount lifecycle method                                             |
| `vmounted`        | vmounted lifecycle method                                                |
| `vbeforeupdate`   | beforeUpdate lifecycle method                                            |
| `vupdated`        | updated lifecycle method                                                 |
| `vbeforedestroy`  | beforeDestroy lifecycle method                                           |
| `vdestroyed`      | destroyed lifecycle method                                               |
| `vprops`          | Props without defaults                                                   |
| `vpropsdef`       | Props with defaults                                                      |
| `v2props`         | Props with defaults in Options API                                       |
| `vimport-dynamic` | Import one component that should be lazy loaded by webpack               |
| `vcomponents`     | Import one component into another within the export statement            |
| `vimport-export`  | Import one component into another and use it within the export statement |
| `vc-direct`       | Vue create a custom directive                                            |
| `vimport-lib`     | Import a library                                                         |

### Vue Composition API

| Snippet             | Purpose                                               |
| ------------------- | ----------------------------------------------------- |
| `vreactive`         | Vue Composition API - reactive                        |
| `vcomp`             | Vue Composition API - computed                        |
| `vwatch`            | Vue Composition API - watcher single source           |
| `vwatcharr`         | Vue Composition API - watch as array                  |
| `vwatcheff`         | Vue Composition API - watchEffect                     |
| `vref`              | Vue Ref                                               |

### Extra (plaintext)

| Snippet     | Purpose                 |
| ----------- | ----------------------- |
| `gitignore` | .gitignore file presets |

## Contributing

This is an open source project open to anyone. Contributions are welcome [github](https://github.com/sdras/vue-vscode-snippets)

If you are contributing a snippet, please be sure to add the documentation for it in the tables in the README, the pull request cannot be accepted without this addition. Thanks!
