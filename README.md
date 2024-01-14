# React TypeScript Vite Template

It is a template created to help bootstrap a new project fast with previously configured settings.

## Installed Packages

- Vite

- React

- TypeScript

- ESLint

- Tailwind CSS

- Prettier Plugin for Tailwind CSS

- Vitest, React Testing Library, Jestdom

- ESLint auto sort import

## Setup Processes

- Tailwind CSS Installation following the [official docs (Vite template)](https://tailwindcss.com/docs/guides/vite)

- Tailwind CSS Prettier plugin [Automatic class sorting with Prettier](https://github.com/tailwindlabs/prettier-plugin-tailwindcss) in the [offical docs](https://tailwindcss.com/docs/editor-setup#automatic-class-sorting-with-prettier)

- Vitest, React Testing Library, Jestdom following [The Odin Project](https://www.theodinproject.com/lessons/node-path-react-new-introduction-to-react-testing), [this article](https://www.robinwieruch.de/vitest-react-testing-library/) this [Youtube video](https://youtu.be/G-4zgIPsjkU?si=hO_ZKEel3b7Gsd-h) to solve some errors (Make sure test files are in src folder, or else ESLint can't find 'describe' function)

- ESLint Auto Sort Imports following [this article](https://dev.to/julioxavierr/sorting-your-imports-with-eslint-3ped)

To auto sort the import on save on VsCode, paste this in your settings.json

```bash
 "editor.codeActionsOnSave": {
   "source.fixAll.eslint": true
 }
```

- Follow the instructions on the Readme file generated by Vite template to expand ESLint configuration

- Replace plugin:@typescript-eslint/recommended to plugin:@typescript-eslint/recommended-type-checked or plugin:@typescript-eslint/strict-type-checked

- Optionally add plugin:@typescript-eslint/stylistic-type-checked

- Install eslint-plugin-react and add plugin:react/recommended & plugin:react/jsx-runtime to the extends list

## Run Locally

Clone the project

```bash
  git clone https://github.com/LzhBryan/react-ts-vite-template.git my-project
```

Go to the project directory

```bash
  cd my-project
```

Install dependencies

```bash
  npm install
```

Start the server

```bash
  npm run dev
```

Running the test

```bash
  npm test
```

or

```bash
  npm t
```

Change your package.json "name" property if you wish to
