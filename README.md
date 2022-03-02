# create-svelte

Everything you need to build a Svelte project, powered by
[`SvelteKit Crash Course w/ Tailwind CSS and DaisyUI, GraphQL and dynamic routes`](https://www.youtube.com/watch?v=zH2qG9YwN3s&t=590s).

## Creating a project

```bash
# create a new project in the current directory
npm init svelte@next

# create a new project in my-app
npm init svelte@next my-app
```

> Note: the `@next` is temporary

## Developing

Once you've created a project and installed dependencies with `npm install` (or `pnpm install` or
`yarn`), start a development server:

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

> To deploy your app, you may need to install an [adapter](https://kit.svelte.dev/docs/adapters) for
> your target environment.
