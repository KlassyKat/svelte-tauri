Boilerplate for Tauri with Svelte. Comes with a script to configure typescript.

## Create A Tauri + Svelte App

1. Create a new Tauri + Svelte project using

```bash
  npx degit KlassyKat/svelte-tauri svelte-tauri
  cd svelte-tauri
```

2. Edit the `config.json` and `src-tauri/tauri.config.json` files to configure your
   app.

## Development

Install the dependencies and start your Svelte development server:

```bash
cd svelte-tauri
npm run dev
```

In another console, start the Tauri development environment:

```bash
cd svelte-tauri
npm run tauri dev
```

You should see your Tauri app window display the Svelte "Hello World" app. This
will take a while to happen the first time you do this, while dependencies are
downloaded and built.

## Notice

Tauri changes very quickly and this boilerplate does not always keep up with that. If you are set on svelte and you can't find anything else fixing
this repo isn't too difficult. The easiest way is to use tauri's CLI to init a new vanilla tauri project, Then cross refernece with this boilerplate.
The main culprits of breaking changes are
`package.json`: tauri dependencies
`tauri.conf.json`
`Cargo.toml`
`main.rs`
`build.rs`

I welcome pul requests updating :smile:
