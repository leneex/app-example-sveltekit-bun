# SvelteKit on Bun

Example [SvelteKit](https://svelte.dev/docs/kit) app running on [Bun](https://bun.sh/). SvelteKit is the official framework for building full-stack apps with Svelte. Bun is a fast all-in-one JavaScript runtime and package manager compatible with Node.js.

## Deploy settings

| Field | Value |
| --- | --- |
| Build | Static site — Railpack build |
| Single-page application (SPA) | off |
| Project directory | `/` |
| Output directory | `/build` |
| Install command | leave empty |
| Build command | leave empty |
| Health check path | `/` |

## <a name="dev"></a>Run locally

```bash
# install dependencies
bun install

# run in development mode
bun run dev

# build for production
bun run build

# preview the built static version
bun run preview
```
