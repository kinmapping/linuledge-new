# linuledge-new
linuledge-new is blog with notion


## Development

```bash
pnpm install
pnpm dev
```
https://code.visualstudio.com/docs/editor/intellisense

### lint と　format

```bash
pnpm add -D --save-exact @biomejs/biome
```

#### biome コマンド

https://biomejs.dev/guides/getting-started/

```bash
# format
pnpm biome format --write ./src
# lint (check only)
pnpm biome lint ./src
# lint fix
pnpm biome lint --apply ./src
# organize import, format, lint
pnpm biome check --apply ./src
```

```js
// biome-ignore lint: reason // すべての lint ルールを無効化
// biome-ignore lint/suspicious/noDebugger: reason // 特定の lint ルールを無効化

// biome-ignore format: reason // すべての format ルールを無効化
// biome-ignore format/noUnusedImports: reason // 特定の format ルールを無効化
```


## Build



---

# Astro Starter Kit: Basics

```sh
npm create astro@latest -- --template basics
```

[![Open in StackBlitz](https://developer.stackblitz.com/img/open_in_stackblitz.svg)](https://stackblitz.com/github/withastro/astro/tree/latest/examples/basics)
[![Open with CodeSandbox](https://assets.codesandbox.io/github/button-edit-lime.svg)](https://codesandbox.io/p/sandbox/github/withastro/astro/tree/latest/examples/basics)
[![Open in GitHub Codespaces](https://github.com/codespaces/badge.svg)](https://codespaces.new/withastro/astro?devcontainer_path=.devcontainer/basics/devcontainer.json)

> 🧑‍🚀 **Seasoned astronaut?** Delete this file. Have fun!

![just-the-basics](https://github.com/withastro/astro/assets/2244813/a0a5533c-a856-4198-8470-2d67b1d7c554)

## 🚀 Project Structure

Inside of your Astro project, you'll see the following folders and files:

```text
/
├── public/
│   └── favicon.svg
├── src/
│   ├── layouts/
│   │   └── Layout.astro
│   └── pages/
│       └── index.astro
└── package.json
```

To learn more about the folder structure of an Astro project, refer to [our guide on project structure](https://docs.astro.build/en/basics/project-structure/).

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Installs dependencies                            |
| `npm run dev`             | Starts local dev server at `localhost:4321`      |
| `npm run build`           | Build your production site to `./dist/`          |
| `npm run preview`         | Preview your build locally, before deploying     |
| `npm run astro ...`       | Run CLI commands like `astro add`, `astro check` |
| `npm run astro -- --help` | Get help using the Astro CLI                     |

## 👀 Want to learn more?

Feel free to check [our documentation](https://docs.astro.build) or jump into our [Discord server](https://astro.build/chat).
