# Monorepo starter code with Turborepo and PNPM

## Apps and Packages
- `api`: Backend app using [ExpressJS](https://expressjs.com/)
- `types`: Packages that contains all Typescript types for type-checking
- `web`: Frontend app using [ReactJS](https://react.dev/)

## How to get started
- Install all dependencies using [PNPM](https://pnpm.io/installation)
  ```
  pnpm install
  ```

- Start dev server
  ```bash
  turbo run dev
  ```

- Build all apps
  ```bash
  turbo run build
  ```

- Do type-check in all apps
  ```bash
  turbo run type-check
  ```