# unplugin-solid-components WIP

## :hammer_and_wrench: under construction

[![NPM version](https://img.shields.io/npm/v/unplugin-solid-components?color=a1b858&label=)](https://www.npmjs.com/package/unplugin-solid-components)

On-demand components auto importing for SolidJS.

## Installation

```bash
npm i unplugin-solid-components -D
```

<details>
<summary>Vite</summary><br>

```ts
// vite.config.ts
import Components from 'unplugin-vue-components/vite'

export default defineConfig({
  plugins: [
    Components({ /* options */ }),
  ],
})
```

<br></details>

<details>
<summary>Rollup</summary><br>

```ts
// rollup.config.js
import Components from 'unplugin-vue-components/rollup'

export default {
  plugins: [
    Components({ /* options */ }),
  ],
}
```

<br></details>
