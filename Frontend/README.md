# sv

Everything you need to build a Svelte project, powered by [`sv`](https://github.com/sveltejs/cli).

## Developing

Once you've created a project and installed dependencies with `npm install` (or `pnpm install` or `yarn`), start a development server:

```bash
npm run dev

# or start the server and open the app in a new browser tab
npm run dev -- --open
```

## Building

To create a production version of your app:

```bash
npm run build
```

You can preview the production build with `npm run preview`.

## Deploy

Deploy works automatically with each push to github pages. The template is deployed to [dhbw-ka-webengineering.github.io/Template_Svelte/](https://dhbw-ka-webengineering.github.io/Template_Svelte/)

Because of the _Template_Svelte_ path in the URL, `base: process.env.NODE_ENV === 'production' ? '/Template_Svelte' : ''` is required in line 16 of the [svelte.config.js file](svelte.config.js). If you deploy the repo to a different URL, you will need to adapt or remove this part.
