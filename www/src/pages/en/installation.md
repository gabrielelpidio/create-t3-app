---
title: Installation
description: Installation instructions for Create T3 App
layout: ../../layouts/blog.astro
---

To install `create-t3-app`, run any of the following three commands and answer the command prompt questions:

### npm

```bash
npx create-t3-app@latest
```

### yarn

```bash
yarn create t3-app
```

### pnpm

```bash
pnpm dlx create-t3-app@latest
```

## Advanced usage

| Option/Flag       | Description                                                             |
| ----------------- | ----------------------------------------------------------------------- |
| `[dir]`           | Include a directory argument with a name for the project                |
| `--noGit`         | Explicitly tell the CLI to not initialize a new git repo in the project |
| `-y`, `--default` | Bypass the CLI and use all default options to bootstrap a new t3-app    |
| `--noInstall`     | Generate project without installing dependencies                        |

## Experimental

If you prefer using the [experimental v10 version of tRPC](https://trpc.io?v10), use `create-t3-app@next`. Note that the alpha versions of tRPC that it uses may contain API changes. We will try our best to keep on top of these, please file an issue if we have missed something.
