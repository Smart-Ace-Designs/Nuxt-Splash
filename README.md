# Nuxt Template: Splash
Nuxt **Splash** is an opinionated Nuxt 4 starter template with built-in support for Tailwind CSS and Prettier and includes a blank default "index.vue" page.

Using `create nuxt@latest` provides everything you need to create a basic Nuxt application. However, it is missing a few useful items that you might find yourself manually adding to every new Nuxt project. The **Splash** template was created to automatically include these items. This provides a great starting point for a new Nuxt project with Tailwind.

The template includes:
- An initial Nuxt project structure
- [Tailwind CSS v4.1](https://tailwindcss.com/)
- [Prettier](https://prettier.io/)
- Initial <head> elements for language and title set in _nuxt.config.ts_
- A default _main.css_ file
- Default _.vscode_ files to properly handle Tailwind CSS, recommended extensions, and default Prettier formatters
- A blank _index.vue_ page
- The `dev` script set to `"nuxt dev -o"`

## Deployment Methods
### bun
```sh
bunx giget gh:smart-ace-designs/nuxt-splash project-name
```
### npm
```sh
npx giget gh:smart-ace-designs/nuxt-splash project-name
```

> [!Note]
> You should manually clear the contents of this README file after deployment.

## Project Structure
After deploying the Nuxt **Splash** template you will see the following files and directories in your project root:

```text
/
├── .vscode/
│   ├── extensions.json
│   └── settings.json
├── app/
│   ├── assets/
│   │   └── css
|   |       └── main.css
│   ├── pages/
│   │   └── index.vue
│   └── app.vue
├── public/
│   ├── favicon.ion
|   └── robots.txt
├── .gitignore
├── .prettierrc
├── nuxt.config.ts
├── package.json
├── README.md
└── tsconfig.json
```
