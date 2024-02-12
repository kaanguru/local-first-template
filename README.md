# Client-Side development template
Single User offline-first app template

**Ready for PWA development**

**Using:**

- [Static site generation](https://kit.svelte.dev/docs/adapter-static) client-rendered single-page app (SPA) or (SSG)
- [Client-side Storage](https://dexie.org/)
IndexeDB database
- [SuperForms](https://superforms.rocks/concepts/spa) Single-page applications (SPA)

----

## Used Formula

- [x] [Skeleton — UI Toolkit for Svelte + Tailwind](https://www.skeleton.dev/docs/get-started)
  - [x] `-npm create skeleton-app@latest my-skeleton-app`
- [x] [SvelteKit | Tauri Apps](https://tauri.app/v1/guides/getting-started/setup/sveltekit/#sveltekit-in-ssg-mode)
  - [x] ` pnpm add -D @sveltejs/adapter-static `
  - [x] Then update the `adapter` import in the `svelte.config.js` file
- [x] [Get started with Dexie in Svelte](https://dexie.org/docs/Tutorial/Svelte)
  - [x]  ` pnpm install dexie@next `
  - [x]  `src\lib\db.ts`
- [x] [Superforms for SvelteKit](https://superforms.rocks/concepts/spa)
  - [ ] `pnpm i -D sveltekit-superforms zod`

