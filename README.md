# ![RealWorld Example App](logo.png)

[![Codecov branch](https://img.shields.io/codecov/c/github/goodhabitz/conduit-vue/master?logo=codecov&style=for-the-badge)](https://app.codecov.io/gh/goodhabitz/conduit-vue/branch/master)
[![GitHub Workflow Status (branch)](https://img.shields.io/github/workflow/status/goodhabitz/conduit-vue/Test/master?label=master&logo=github&style=for-the-badge)](https://github.com/goodhabitz/conduit-vue/actions?query=branch%3Amaster)
[![GitHub Workflow Status (branch)](https://img.shields.io/github/workflow/status/goodhabitz/conduit-vue/Test/script-setup?label=ref-sugar&logo=github&style=for-the-badge)](https://github.com/goodhabitz/conduit-vue/actions?query=branch%3Aref-sugar)

> ### [Vue3](https://v3.vuejs.org/) codebase containing real world examples (CRUD, auth, advanced patterns, etc) that adheres to the [RealWorld](https://github.com/gothinkster/realworld) spec and API.

- [Demo](https://goodhabitz-conduit-vue.pages.dev/)
- [RealWorld](https://github.com/gothinkster/realworld)


This codebase was created to demonstrate a fully fledged fullstack application built with **Vue3** including CRUD operations, authentication, routing, pagination, and more.

We've gone to great lengths to adhere to the **Vue3** community styleguides & best practices.

For more information on how to this works with other frontends/backends, head over to the [RealWorld](https://github.com/gothinkster/realworld) repo.

# What works?

- [x] [Vite](https://github.com/vitejs/vite)
- [x] [Composition API](https://composition-api.vuejs.org/)
- [x] [SFC \<script setup> sugar](https://v3.vuejs.org/api/sfc-script-setup.html)
- [x] [Suspense](https://v3.vuejs.org/guide/component-dynamic-async.html#using-with-suspense) (Experimental)
- [x] [Vue router](https://next.router.vuejs.org/)
- [x] State management ([Harlem](https://github.com/andrewcourtice/harlem) ([await Vuex v5](https://github.com/goodhabitz/conduit-vue/issues/15)))
- [x] Type system [TypeScript](https://www.typescriptlang.org/) [Vue tsc](https://github.com/johnsoncodehk/vue-tsc)
- [x] Linter [ESLint](https://eslint.vuejs.org/)
- [x] Unit test ([Vue Testing Library](https://testing-library.com/docs/vue-testing-library/intro))
- [x] E2E test ([Cypress](https://docs.cypress.io))

# Getting started

```shell script
yarn install

# Development
yarn dev

# Build dist
yarn build

# Run unit tests
yarn test:unit

# Run E2E tests
yarn cypress open # with GUI
yarn test:e2e # headless
```

# Contributors

<a href="https://github.com/goodhabitz/conduit-vue/graphs/contributors">
  <img src="https://contributors-img.web.app/image?repo=goodhabitz/conduit-vue" />
</a>

Made with [contributors-img](https://contributors-img.web.app).
