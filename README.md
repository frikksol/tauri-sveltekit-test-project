# Tauri + SvelteKit Typescript test project

This is a project for testing out Tauri with SvelteKit, which to me seems to be two of the most exiting new technologies out there.

So far this is mainly based on the awesome article by Dan Casler which you can find [here](https://medium.com/@cazanator/tauri-with-standard-svelte-or-sveltekit-ad7f103c37e7), with some minor modifications.

Other resources worth mentioning is [svelte](https://svelte.dev/) and [tauri](https://tauri.studio/).

## References for this project
- [This](https://medium.com/@cazanator/tauri-with-standard-svelte-or-sveltekit-ad7f103c37e7) awesome article by Dan Casler which is what I have based this project on
- [Tauri](https://tauri.studio/) The exciting new desktop (and likely soon mobile) cross platform framework based on rust and webviews
- [Svelte](https://svelte.dev/) Javscript compiler for efficient fron end code
- [Svelte Kit](https://kit.svelte.dev/) Awesome framework for writing Svelte apps
- [Typescript](https://www.typescriptlang.org/) The only way to write Javascript sensibly
- [Rust](https://www.rust-lang.org/) The most exciting new programming language. Maybe ever.

## Setup
Before starting you need to install [rust](https://www.rust-lang.org/learn/get-started), [nodejs](https://nodejs.org/en/) and [tauri](https://tauri.studio/docs/getting-started/prerequisites/) according to your system. The rest should be handled by npm and cargo

``` bash
# clone the repository
git clone git@github.com:frikksol/tauri-sveltekit-test-project.git

# cd into repo
cd tauri-sveltekit-test-project

# install npm dependencies
npm i

# verify that the svelte kit dev server works at this point
# dev server starts on https://localhost:3000
npm run dev

# verify tauri setup
# this should give you some info on the tauri setup
npm run tauri info

# run tauri in dev mode
# this should open the tauri app
npm run tauri dev

# build and bundle tauri app
# this should create a bundle ready to install on your system
npm run tauri build
```

Have fun! Feel free to report any issues you may find.