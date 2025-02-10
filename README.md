# Designer Decisions Minimal Boilerplate

![](https://raw.githubusercontent.com/noodlestan/designer/refs/heads/main/docs/designer-decisions/public/designer-decisions-og-1280x640.png)

## Getting started

System requirements: [Node.js](https://nodejs.org/) (recommended: [NVM](https://github.com/nvm-sh/nvm)).

```
npm install
npm run build:decisions
```

## Project Structure

Inside of your **Designer Decisions** project, you will find the following folders and files:

```
.
├── data/
│   ├── color/
│   ├── space/
│   └── typography/
├── scripts/
│   └── build-decisions.js/
├── package.json
└── tsconfig.json
```

### Authoring decisions

Design decisions are loaded from the `data/` directory.

You can validate all data by running the `build:decisions` script. It reports all validation errors and broken references.

```
npm run build:decisions
```

## Designer Decisions Commands

All commands are run from the root of the project, from a terminal:

| Command                   | Action                                 |
| :------------------------ | :------------------------------------- |
| `npm run build:decisions` | Validate design decisions in `./data/` |

### Learn more

-   [Designer Decisions Guides](https://designer-decisions.noodlestan.org/guides/welcome)

## Noodlestan 🐘 Collective

We are an open collective of people dedicated to the design and software crafts: UX, design, code, web, 3d, audio, the works. Learn more about us and our projects at [Noodlestan.org](https://noodlestan.org).

**👐 Your contribution is welcome! 👐**

If would like to share your ideas, report a bug, ask for improvements - or simply say hi! 👋 - don't hesitate to join us on [Noodlestan's Discord](https://discord.gg/b8DkbJSF9z) or to drop us a line at `hello@noodlestan.org`.

## MIT License

Copyright (c) 2024 [Noodlestan](https://noodlestan.org/).

Published under a [MIT license](https://noodlestan.mit-license.org/).
