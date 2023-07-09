# Vue Sandbox

## Prerequisites

* Node 18.16.1 (npm 9.5.1)
* Yarn 1.22.19

## Recommended IDE Setup

* [VSCode](https://code.visualstudio.com/)
* [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar)
* [TypeScript Vue Plugin (Volar)](https://marketplace.visualstudio.com/items?itemName=Vue.vscode-typescript-vue-plugin)
* Disable Vetur (still uses Vue 2 rules)

## Yarn Commands

* Local Development

  ```sh
  yarn install
  yarn dev
  ```

* Compile and Minify for Production

  ```sh
  yarn build
  ```

* Lint with [ESLint](https://eslint.org/) and Prettier formatting

  ```sh
  yarn lint
  ```

* Full command list in `package.json` under `scripts`.

---

## Customize Vite Dev Server

* See [Vite Configuration Reference](https://vitejs.dev/config/).

## Type Support for `.vue` Imports in TS

TypeScript cannot handle type information for `.vue` imports by default, so we replace the `tsc` CLI with `vue-tsc` for type checking. In editors, we need [TypeScript Vue Plugin (Volar)](https://marketplace.visualstudio.com/items?itemName=Vue.vscode-typescript-vue-plugin) to make the TypeScript language service aware of `.vue` types.

If the standalone TypeScript plugin doesn't feel fast enough to you, Volar has also implemented a [Take Over Mode](https://github.com/johnsoncodehk/volar/discussions/471#discussioncomment-1361669) that is more performant. You can enable it by the following steps:

1. Disable the built-in TypeScript Extension
    1) Run `Extensions: Show Built-in Extensions` from VSCode's command palette
    2) Find `TypeScript and JavaScript Language Features`, right click and select `Disable (Workspace)`
2. Reload the VSCode window by running `Developer: Reload Window` from the command palette.
