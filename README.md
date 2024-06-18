# The 2077 Collective
---



```sh
git clone '<repo>'
```

## 🚀 Project Structure

Inside of your cloned project folder, you'll see the following folders and files:

```text
/
├── public/
    ├── fonts/
    ├── images/
    ├── add.svg
    ├── arrow.svg
    ├── arrowRight.svg
    ├── favicon.svg
    ├── ghost.svg
│   └── google.svg
├── src/
│   ├── components/
        ├── Footer.astro
│   │   └── H1.astro
        └── H1AlignLeft.astro
        └── Header.astro
        └── Main.astro
        └── MobileMenu.astro
        └── Post.astro
        └── PostList.astro
        └── PrimaryCta.astro
        └── Project.astro
        └── ProjectList.astro
    └── content/
│   ├── css/
│   ├── fonts/
│   ├── layouts/
│   │   └── Layout.astro
│   └── pages/
│       └── blog
            ├── [slug].astro
│       └── projects
            ├── [slug].astro
│       └── community.astro
│       └── index.astro
│       └── manifesto.astro
│       └── projects.astro
│       └── resources.astro
    └── env.d.ts
└── astro.config.mjs
└── astro.config.mjs
└── package-lock.json
└── README.md.json
└── tailwind.config.mjs
└── tsconfig.json
```

Astro looks for `.astro` or `.md` files in the `src/pages/` directory. Each page is exposed as a route based on its file name.

Componets folder: `src/components/`, but that's where we like to put any Astro/React/Vue/Svelte/Preact components.

Any static assets, like images, can be placed in the `public/` directory.

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


