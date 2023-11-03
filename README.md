# Nuxt Example

Deploy your [Nuxt](https://nuxt.com) project to Vercel with zero configuration.

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/vercel/vercel/tree/main/examples/nuxtjs&template=nuxtjs)

_Live Example: https://nuxtjs-template.vercel.app_

Look at the [Nuxt 3 documentation](https://v3.nuxtjs.org) to learn more.

-----

## Setup 🛠 🔨

Make sure to install the dependencies:

```bash
# yarn
yarn

# npm
npm install

# pnpm
pnpm install --shamefully-hoist
```

## Development Server 📥

Start the development server on http://localhost:3000

```bash
npm run dev
```

```bash
pnpm run dev
```

## Production

Build the application for production:

```bash
npm run build
```

```bash
pnpm run build
```

Locally preview production build:

```bash
npm run preview
```

```bash
npm run preview
```

Checkout the [deployment documentation](https://nuxt.com/docs/getting-started/deployment#presets) for more information.

------


## Screenshot 📸

![Alt text](./image/image.png)


## Languages and Tools are used 🗣️🔧

1. **Languages** 🗣️
    + [TypeScript](https://github.com/topics/typescript)
    + [Yarn](https://github.com/topics/yarn)
    + [Vue](https://github.com/topics/vue)
    + [Nuxtjs](https://github.com/topics/nuxtjs)

2. **Tools** 🔧
    + [Chrome](https://github.com/topics/chrome)
    + [Figma](https://github.com/topics/figma)
    + [VSCode](https://github.com/topics/vscode)
    + [Vercel](https://github.com/topics/vercel)


------

### Package Json

```
{
  "private": true,
  "scripts": {
    "build": "nuxt build",
    "dev": "nuxt dev",
    "generate": "nuxt generate",
    "preview": "nuxt preview",
    "postinstall": "nuxt prepare"
  },
  "devDependencies": {
    "nuxt": "^3.0.0"
  }
}
```


### App.vue

```
<template>
  <div>
    <NuxtWelcome />
  </div>
</template>
```

### Nuxt.config.ts

```
export default {
  nitro: {
    preset: 'vercel-edge',
  },
};
```