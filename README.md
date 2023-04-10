# vite documentation ![My Skills](https://skillicons.dev/icons?i=vite)

### What is Vite.js?
**Vite.js** is a development tool that comes with a dev server and is used for modern web applications. It offers a faster and smoother workflow in terms of development. It has two major parts:
- A **dev server** serves the source files over native ES modules, with build-in features and fast Hot Module Replacement (HMR) for updating modules during the execution of the application. When changes are made to the source code of an application, only those changes are updated, without the need to reload the entire application. This helps speed up the development time.

- A **build command** enables us to bundle our code with Rollup and offers highly optimized static assets for production.

### Vite :zap:
>Next Generation Frontend Tooling

- :bulb: Instant Server Start
- :zap: Lightning Fast HMR
- :hammer_and_wrench: Rich Features
- :package: Optimized Build
- :nut_and_bolt: Universal Plugin Interface
- :key: Fully Typed APIs

### Working
Vite uses esbuild to pre-bundle the dependencies and then immediately launches the server. It then analyzes the code and processes via route-based code splitting. Vite then uses native <ins>ESM support</ins> to deliver the code. This enables the browser to do the bundling and development. To implement other performance optimizations, Vite uses Rollup, which bundles the application. 

## Get started with Vite.js
To start with Vite, we can use create-app bootstrapper. The tool supports popular front-end libraries, including React and Vue.

The following command will run a Vite-bootstrapped application:
> **Compatibility Note:** Vite requires [Node.js](https://nodejs.org/en) version 14.18+, 16+. However, some templates require a higher Node.js version to work, please upgrade if your package manager warns about it.

With NPM:
```
$ npm create vite@latest
```
With Yarn:
```
$ yarn create vite
```
With PNPM:
```
$ pnpm create vite
```
Then follow the prompts!

You can also directly specify the project name and the template you want to use via additional command line options. For example, to scaffold a Vite + Vue project, run:
```
# npm 6.x
npm create vite@latest my-vue-app --template vue

# npm 7+, extra double-dash is needed:
npm create vite@latest my-vue-app -- --template vue

# yarn
yarn create vite my-vue-app --template vue

# pnpm
pnpm create vite my-vue-app --template vue
```
Currently supported template presets include:

- `vanilla`
- `vanilla-ts`
- `vue`
- `vue-ts`
- `react`
- `react-ts`
- `react-swc`
- `react-swc-ts`
- `preact`
- `preact-ts`
- `lit`
- `lit-ts`
- `svelte`
- `svelte-ts`

You can use `.` for the project name to scaffold in the current directory.

### Community Templates

create-vite is a tool to quickly start a project from a basic template for popular frameworks. Check out Awesome Vite for [community maintained templates](https://github.com/vitejs/awesome-vite#templates) that include other tools or target different frameworks. You can use a tool like [degit](https://github.com/Rich-Harris/degit) to scaffold your project with one of the templates.
```
npx degit user/project my-project
cd my-project

npm install
npm run dev
```
If the project uses main as the default branch, suffix the project repo with #main
```
npx degit user/project#main my-project
```
