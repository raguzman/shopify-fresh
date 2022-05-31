<!-- title / description (start) -->
<h2 align="center">Shopify Fresh</h2>

Shopify Fresh is a development environment for Shopify Online Store 2.0 theme development based off [Shopify Theme Lab](https://themelab.uicrooks.com/). It utilizes [Shopify CLI](https://shopify.dev/themes/tools/cli) and is bundled with [Alpine.js](https://alpinejs.dev/) and [Tailwind 3](https://tailwindcss.com/). Includes Webpack, SASS, ESLint, Autoprefixer.

### Installation
---

1) Install the [Shopify CLI](https://shopify.dev/themes/tools/cli/installation)

2) Create a [development store](https://shopify.dev/themes/tools/development-stores#create-a-development-store-to-build-and-test-your-theme)

3) Log out of your dev store and then log in again as admin
```
your-store.myshopify.com/admin
```
4) Log into your dev store with Shopify CLI.
```
shopify login --store <your-store.myshopify.com>
```

5) Clone the Shopify Fresh repo

```
shopify theme init -u https://github.com/raguzman/shopify-fresh
```

6) Install dependencies and run 

```
npm install
npm run start
```
