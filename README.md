# Tailwind

Basic configuration of tailwind css.

```sh
pnpm add @loongwoo/tailwind
```

Add code to the entry file：

- `scss` file

```scss
@use '@loongwoo/tailwind/index.css'
```

- `ts` or `js` file

```ts
import '@loongwoo/tailwind'
```

- `nuxt.config.ts` file

```ts
export default defineNuxtConfig({
  css: ['@loongwoo/tailwind/index.css']
})
```
