# Reproduction repo for [SvelteKit issue #7496](https://github.com/sveltejs/kit/issues/7496)

Run `npm run build` to reproduce the error.

[`service-worker.ts`](/src/service-worker.ts) imports code from [`lib/utils`](/src/lib/utils), using the `$utils` alias defined in [`svelte.config.js`](/svelte.config.js).
