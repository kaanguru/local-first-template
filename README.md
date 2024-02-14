# SvelteKit SSG Starter with Zod Form Validation

## Local-First Development Template

Single User offline-first app template to start your next project.
Using Dexie.js, SuperForms with SvelteKit and Skeleton UI for TailwindCSS styling.

<div align="center">

[![License](https://img.shields.io/badge/License-MIT-blue)](#license)

[![Use this template](https://img.shields.io/badge/Generate-Use_this_template-2ea44f?style=for-the-badge)](https://github.com/kaanguru/local-first-template/generate)

![Static Badge](https://img.shields.io/badge/superforms-yellow?link=https%3A%2F%2Fsuperforms.rocks%2F)
![Static Badge](https://img.shields.io/badge/Skeleton_UI-red?link=https%3A%2F%2Fwww.skeleton.dev%2F)
![Static Badge](https://img.shields.io/badge/%20Dexie.js-blue?link=https%3A%2F%2Fdexie.org%2F)

<img src="data:image/svg+xml,%3c?xml%20version='1.0'%20encoding='UTF-8'?%3e%3csvg%20id='a'%20xmlns='http://www.w3.org/2000/svg'%20xmlns:xlink='http://www.w3.org/1999/xlink'%20viewBox='0%200%201080%201080'%3e%3cdefs%3e%3cstyle%3e.e{fill:%23b7a73f;}.e,.f,.g{fill-rule:evenodd;}.h{fill:%23182439;}.f,.g{fill:%23ecd11c;}.g{filter:url(%23d);}%3c/style%3e%3cfilter%20id='d'%3e%3cfeDropShadow%20dx='7'%20dy='7'%20flood-opacity='0.25'%20stdDeviation='7'/%3e%3c/filter%3e%3c/defs%3e%3cg%20id='b'%3e%3cpolygon%20class='h'%20points='530%20922%2083%20391%20275%20204.588%20834%20204.588%201011%20396%20530%20922'/%3e%3c/g%3e%3cg%20id='c'%3e%3cpath%20class='e'%20d='M741.251,662.107H334.31v64.28h406.941v-64.28Z'/%3e%3cpath%20class='e'%20d='M697.019,779.656H381.781v-64.28h315.239v64.28Zm-224.32-116.141h-168.684v-18.093h168.684v18.093Zm270.981,31.964L141.126,347.594l60.584-104.935,602.554,347.885-60.584,104.935Zm194.602-243.383l-386.157-222.949,12.445-21.555,386.157,222.949-12.445,21.555Z'/%3e%3cpath%20class='e'%20d='M963.286,415.916l-386.157-222.949-12.445,21.555,386.157,222.949,12.445-21.555Z'/%3e%3cpath%20class='e'%20d='M963.292,426.04l-386.157-222.949,12.445-21.555,386.157,222.949-12.445,21.555Zm-34.816,34.298l-408.373-235.774,9.801-16.976,408.373,235.774-9.801,16.976Z'/%3e%3cpath%20class='e'%20d='M928.475,456.992L504.426,212.167l-9.801,16.976,424.049,244.825,9.801-16.976Z'/%3e%3cpath%20class='e'%20d='M908.873,490.95L455.42,229.148l12.445-21.555,453.453,261.801-12.445,21.555Zm-590.686-107.299l-136.251-78.664,40.279-69.765,136.251,78.664-40.279,69.764Z'/%3e%3c/g%3e%3cpath%20class='g'%20d='M842.637,179.14H258.378L44.915,391.505l484.635,583.598,38.662-43.38,479.723-538.224-205.298-214.358h0Zm-21.344,50l158.572,165.579-448.973,503.732L112.578,394.719l166.433-165.579H821.292Z'/%3e%3cpath%20class='f'%20d='M842.637,179.14H258.378L44.915,391.505l484.635,583.598,38.662-43.38,479.723-538.224-205.298-214.358h0Zm-21.344,50l158.572,165.579-448.973,503.732L112.578,394.719l166.433-165.579H821.292Z'/%3e%3c/svg%3e" alt="SuperForms" width="100" height="100" />

<img src="https://pbs.twimg.com/profile_images/1587479781544759297/TINbbJLC_400x400.png"  alt="Skeleton UI" width="100" height="100" />

# ![Dexie.js](https://dexie.org/assets/images/dexie-logo-icon.svg)Dexie.js

</div>

## Ready for PWA development

**Using:**

- [Static site generation](https://kit.svelte.dev/docs/adapter-static) client-rendered single-page app (SPA) or (SSG)
- [Client-side Storage](https://dexie.org/)
IndexeDB database
- [SuperForms](https://superforms.rocks/concepts/spa) Single-page applications (SPA)

----

## Usage

- `pnpm install`
- `pnpm update`
- `pnpm dev`

## Used Formula

- [x] [Skeleton — UI Toolkit for Svelte + Tailwind](https://www.skeleton.dev/docs/get-started)
  - [x] `-pnpm create skeleton-app@latest my-skeleton-app`
- [x] [SvelteKit | Tauri Apps](https://tauri.app/v1/guides/getting-started/setup/sveltekit/#sveltekit-in-ssg-mode)
  - [ ] ` pnpm add -D @sveltejs/adapter-static `
  - [ ] Then update the `adapter` import in the `svelte.config.js` file
- [x] [Get started with Dexie in Svelte](https://dexie.org/docs/Tutorial/Svelte)
  - [ ]  ` pnpm install dexie@next `
  - [ ]  `src\lib\db.ts`
- [x] [Superforms for SvelteKit](https://superforms.rocks/concepts/spa)
  - [ ] `pnpm i -D sveltekit-superforms zod`
