# calculator
Contexto del proyecto
Requisitos mínimos Calculadora:

Mobil First
La calculadora deberá poder realizar las operaciones básicas: suma, resta, multiplica, división
Teclas obligatorias:
· númericas del 0 al 9
· suma, resta, multiplicar, división
· signo "igual"
· signo "." para la coma
· CE (para resetear)
​

Requisitos mínimos Conversor de Divisas:

Deberá estar integrado en la calculadora
Divisas a utilizar : Euro (€), Dólar ($), Yen (¥), Lempira Hondureño (Honduras)
​

Extra:

Tecla M+ para poner en memoria el número actual (se deberá utilizar el local storage del navegador para almacenar la info)
Tecla MR para recuperar el dato almacenado
Tecla MC para borrar los datos guardados en memoria
​

Stack a utilizar:

Se deberá realizar la aplicación con Vue 3 y realizar test unitarios con Vitest. Se podrá utilizar Bootstrap, Vuetify o cualquier otra libreria CSS.

​


## Recommended IDE Setup

[VSCode](https://code.visualstudio.com/) + [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar) (and disable Vetur) + [TypeScript Vue Plugin (Volar)](https://marketplace.visualstudio.com/items?itemName=Vue.vscode-typescript-vue-plugin).

## Type Support for `.vue` Imports in TS

TypeScript cannot handle type information for `.vue` imports by default, so we replace the `tsc` CLI with `vue-tsc` for type checking. In editors, we need [TypeScript Vue Plugin (Volar)](https://marketplace.visualstudio.com/items?itemName=Vue.vscode-typescript-vue-plugin) to make the TypeScript language service aware of `.vue` types.

If the standalone TypeScript plugin doesn't feel fast enough to you, Volar has also implemented a [Take Over Mode](https://github.com/johnsoncodehk/volar/discussions/471#discussioncomment-1361669) that is more performant. You can enable it by the following steps:

1. Disable the built-in TypeScript Extension
    1) Run `Extensions: Show Built-in Extensions` from VSCode's command palette
    2) Find `TypeScript and JavaScript Language Features`, right click and select `Disable (Workspace)`
2. Reload the VSCode window by running `Developer: Reload Window` from the command palette.

## Customize configuration

See [Vite Configuration Reference](https://vitejs.dev/config/).

## Project Setup

```sh
npm install
```

### Compile and Hot-Reload for Development

```sh
npm run dev
```

### Type-Check, Compile and Minify for Production

```sh
npm run build
```

### Run Unit Tests with [Vitest](https://vitest.dev/)

```sh
npm run test:unit
```

### Lint with [ESLint](https://eslint.org/)

```sh
npm run lint
```
