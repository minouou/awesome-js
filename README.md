# Awesome JS  [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated collection of awesome **JavaScript** libraries, tools, runtimes, resources, and shiny things — across **browser**, **Node.js**, **Deno**, **Bun**, **edge/serverless**, **desktop**, and **mobile**.

> Scope: anything primarily built for JavaScript/TypeScript ecosystems (not just browser-side).

* [Awesome JS](#awesome-js)
  * [Runtimes](#runtimes)
  * [Package Managers](#package-managers)
  * [Monorepo & Workspace Tools](#monorepo--workspace-tools)
  * [Module Systems](#module-systems)
  * [Build Tools](#build-tools)
    * [Transpilers](#transpilers)
    * [Bundlers](#bundlers)
    * [Minimizers](#minimizers)
  * [Type Checking & Validation](#type-checking--validation)
  * [Testing](#testing)
    * [Test Runners](#test-runners)
    * [Assertion & Mocking](#assertion--mocking)
    * [E2E / Browser Automation](#e2e--browser-automation)
    * [Coverage](#coverage)
  * [Code Quality](#code-quality)
  * [Documentation](#documentation)
  * [Frontend](#frontend)
    * [UI Frameworks](#ui-frameworks)
    * [State Management](#state-management)
    * [Data Visualization](#data-visualization)
    * [Editors](#editors)
    * [Animations](#animations)
    * [Maps](#maps)
  * [Backend](#backend)
    * [Web Frameworks](#web-frameworks)
    * [API Clients & Data Fetching](#api-clients--data-fetching)
    * [Authentication](#authentication)
    * [ORM & Databases](#orm--databases)
    * [Queues & Jobs](#queues--jobs)
    * [WebSockets](#websockets)
    * [CMS](#cms)
  * [Utilities](#utilities)
    * [Files](#files)
    * [Functional Programming](#functional-programming)
    * [Reactive Programming](#reactive-programming)
    * [Data Structures](#data-structures)
    * [Date & Time](#date--time)
    * [String](#string)
    * [Number](#number)
    * [Storage](#storage)
    * [Color](#color)
    * [I18n & L10n](#i18n--l10n)
    * [Control Flow](#control-flow)
    * [Routing](#routing)
    * [RegExp](#regexp)
    * [Security](#security)
    * [Logging](#logging)
    * [Benchmarking](#benchmarking)
  * [Cross-Platform](#cross-platform)
    * [CLI](#cli)
    * [Desktop Apps](#desktop-apps)
    * [Mobile Apps](#mobile-apps)
  * [AI & ML](#ai--ml)
  * [Generative AI](#generative-ai)
  * [Articles & Posts](#articles--posts)
* [Worth Reading](#worth-reading)
* [Other Awesome Lists](#other-awesome-lists)
* [Contributing](#contributing)
* [License](#license)

----

## Runtimes
*Where JavaScript runs.*

* [Node.js](https://nodejs.org/) - Server-side JavaScript runtime.
* [Deno](https://deno.com/runtime) - Secure runtime with modern tooling built-in.
* [Bun](https://bun.sh/) - Fast runtime + bundler + package manager.
* [Cloudflare Workers](https://developers.cloudflare.com/workers/) - Edge/serverless JavaScript runtime.
* [Electron](https://www.electronjs.org/) - Build cross-platform desktop apps with JavaScript.
* [React Native](https://reactnative.dev/) - Build native mobile apps with JavaScript/TypeScript.

## Package Managers
*Host libraries and provide tools for fetching and packaging them.*

* [npm](https://www.npmjs.com/) - Package manager for JavaScript.
* [yarn](https://yarnpkg.com/) - Fast, reliable dependency management.
* [pnpm](https://pnpm.io/) - Fast, disk space efficient package manager.
* [bun](https://bun.sh/) - Runtime + package manager.
* [jspm](https://github.com/jspm/jspm-cli) - Package management & import maps tooling.

<details>
<summary>Legacy / historical</summary>

* [Bower](https://github.com/bower/bower) - Legacy front-end package manager.
* [component](https://github.com/componentjs/component) - Client package management for building web apps.
* [Ender](https://github.com/ender-js/Ender) - The no-library library.
</details>

## Monorepo & Workspace Tools
*Manage multiple packages/apps in one repo.*

* [Nx](https://nx.dev/) - Smart, fast monorepos for JS/TS.
* [Turborepo](https://turbo.build/repo) - High-performance build system for monorepos.
* [Lerna](https://lerna.js.org/) - Monorepo tooling (often combined with npm/yarn/pnpm workspaces).
* [Changesets](https://github.com/changesets/changesets) - Versioning + changelogs for monorepos.
* [Bit](https://github.com/teambit/bit) - Create, find, and reuse components across apps.

## Module Systems
*How code is loaded (ESM/CJS + loaders).*

* [ES Modules](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Modules) - Standard module system for modern JS.
* [SystemJS](https://github.com/systemjs/systemjs) - Dynamic module loader for browsers and Node.
* [RequireJS](https://github.com/requirejs/requirejs) - AMD module loader.
* [browserify](https://github.com/substack/node-browserify) - Bundle Node-style `require()` for browsers.

## Build Tools

### Transpilers
*Convert modern JS/TS syntax into target environments.*

* [SWC](https://swc.rs/) - Fast compiler platform (JS/TS).
* [Babel](https://github.com/babel/babel) - JavaScript compiler.

### Bundlers
*Bundle modules and assets.*

* [Vite](https://vite.dev/) - Modern dev server + bundler.
* [webpack](https://github.com/webpack/webpack) - Mature bundler for complex apps.
* [Rollup](https://github.com/rollup/rollup) - Great for libraries (ESM-first).
* [Parcel](https://github.com/parcel-bundler/parcel) - Zero-config bundler.
* [esbuild](https://github.com/evanw/esbuild) - Extremely fast bundler/transpiler.
* [Microbundle](https://github.com/developit/microbundle) - Zero-config bundler for tiny modules.
* [FuseBox](https://github.com/fuse-box/fuse-box) - A bundler that does it right.
* [Snowpack](https://www.snowpack.dev/) - Modern dev/build tool (historically popular).
* [bundlephobia](https://bundlephobia.com/) - Quick npm package size checker.

### Minimizers
*Minify JS for production.*

* [Terser](https://github.com/terser/terser) - Minifier for ES6+.
* [UglifyJS](https://github.com/mishoo/UglifyJS) - Classic minifier (legacy for modern syntax).

## Type Checking & Validation

* [TypeScript](https://www.typescriptlang.org/) - Typed superset of JavaScript.
* [Flow](https://flow.org/) - Static type checker for JavaScript.
* [Zod](https://github.com/colinhacks/zod) - TypeScript-first schema validation.
* [Yup](https://github.com/jquense/yup) - Schema builder and validator.
* [io-ts](https://github.com/gcanti/io-ts) - Runtime types + decoding.
* [Ajv](https://github.com/ajv-validator/ajv) - Fast JSON Schema validator.

## Testing

### Test Runners
* [Vitest](https://vitest.dev/) - Fast unit test framework powered by Vite.
* [Jest](https://github.com/facebook/jest) - Painless JavaScript unit testing.
* [Mocha](https://github.com/mochajs/mocha) - Flexible test framework for Node and browser.
* [AVA](https://github.com/avajs/ava) - Futuristic JavaScript test runner.
* [Tape](https://github.com/substack/tape) - Tap-producing test harness.
* [QUnit](https://github.com/qunitjs/qunit) - Easy-to-use unit testing framework.

### Assertion & Mocking
* [Chai](https://github.com/chaijs/chai) - BDD/TDD assertion library.
* [Sinon](https://github.com/sinonjs/sinon) - Spies, stubs, and mocks.
* [Testing Library](https://testing-library.com/) - Test UI the way users interact.

### E2E / Browser Automation
* [Playwright](https://github.com/microsoft/playwright) - Automate Chromium/Firefox/WebKit.
* [Puppeteer](https://github.com/GoogleChrome/puppeteer) - Headless Chrome/Chromium automation.
* [Cypress](https://www.cypress.io/) - End-to-end testing framework.
* [TestCafe](https://github.com/DevExpress/testcafe) - Automated browser testing.
* [WebdriverIO](https://webdriver.io/) - Node.js browser/mobile automation.

### Coverage
* [Istanbul / nyc](https://github.com/istanbuljs/nyc) - Coverage reporting.
* [c8](https://github.com/bcoe/c8) - Coverage using V8’s built-in coverage.

## Code Quality
*Format, lint, and keep code healthy.*

* [ESLint](https://github.com/eslint/eslint) - Pluggable linting utility.
* [Prettier](https://github.com/prettier/prettier) - Opinionated formatter.
* [Biome](https://biomejs.dev/) - Fast formatter + linter (JS/TS).
* [Standard](https://github.com/standard/standard) - JavaScript Standard Style.
* [Husky](https://github.com/typicode/husky) - Git hooks made easy.
* [lint-staged](https://github.com/lint-staged/lint-staged) - Run linters on staged files.

## Documentation
*Write and publish docs, API refs, and guides.*

* [DevDocs](https://devdocs.io/) - Fast API documentation browser.
* [Docusaurus](https://docusaurus.io/) - Documentation site generator.
* [VitePress](https://vitepress.dev/) - Vite-powered docs.
* [Docsify](https://docsify.js.org/) - Docs site without a build step.
* [Storybook](https://storybook.js.org/) - UI component workshop + docs.
* [typedoc](https://typedoc.org/) - TypeScript API documentation.

## Frontend

### UI Frameworks
* [React](https://react.dev/) - UI library.
* [Vue](https://vuejs.org/) - Progressive framework.
* [Svelte](https://svelte.dev/) - Compiler-based UI framework.
* [Angular](https://angular.dev/) - Full-featured framework (TypeScript).
* [Preact](https://github.com/preactjs/preact) - Fast, small React alternative.
* [Solid](https://www.solidjs.com/) - Fine-grained reactivity.
* [Alpine.js](https://github.com/alpinejs/alpine) - Minimal reactive framework.

### State Management
* [Redux](https://redux.js.org/) - Predictable state container.
* [Zustand](https://github.com/pmndrs/zustand) - Small, fast state management for React.
* [MobX](https://github.com/mobxjs/mobx) - Simple, scalable state management.
* [XState](https://xstate.js.org/) - State machines and statecharts.

### Data Visualization
* [D3](https://github.com/d3/d3) - Visualization library for HTML/SVG/Canvas.
* [Chart.js](https://github.com/chartjs/Chart.js) - Simple canvas charts.
* [ECharts](https://github.com/apache/echarts) - Powerful charting.
* [Three.js](https://github.com/mrdoob/three.js) - 3D library.
* [Vega](https://github.com/vega/vega) - Visualization grammar.
* [Cytoscape.js](https://github.com/cytoscape/cytoscape.js) - Graph theory visualizations.

### Editors
* [CodeMirror](https://github.com/codemirror/dev) - Code editor.
* [Monaco Editor](https://microsoft.github.io/monaco-editor/) - VS Code editor core.
* [Ace](https://github.com/ajaxorg/ace) - Browser code editor.
* [Quill](https://github.com/quilljs/quill) - Rich text editor.
* [TinyMCE](https://github.com/tinymce/tinymce) - Rich text editor.

### Animations
* [GSAP](https://gsap.com/) - High-performance animations.
* [anime.js](https://animejs.com/) - Animation engine.
* [motion](https://motion.dev/) - Modern animation library.
* [three.js](https://github.com/mrdoob/three.js) - 3D animations and scenes.
* [TouchFlip3D](https://github.com/labsisouleimen/TouchFlip3D-Web) - A lightweight (3KB) 3D card flip container using pure math matrices.

### Maps
* [Leaflet](https://github.com/Leaflet/Leaflet) - Interactive maps.
* [MapLibre GL JS](https://maplibre.org/maplibre-gl-js/docs/) - Open-source WebGL maps.
* [OpenLayers](https://openlayers.org/) - Feature-packed mapping library.
* [Cesium](https://github.com/CesiumGS/cesium) - 3D globes and maps.

## Backend

### Web Frameworks
* [Express](https://expressjs.com/) - Minimal Node.js web framework.
* [Fastify](https://www.fastify.io/) - Fast, schema-based framework.
* [NestJS](https://nestjs.com/) - Opinionated framework (TypeScript-first).
* [Koa](https://koajs.com/) - Lightweight middleware framework.
* [Hono](https://hono.dev/) - Small, fast framework for edge runtimes (also Node).
* [SvelteKit](https://kit.svelte.dev/) - Full-stack Svelte framework.
* [Next.js](https://nextjs.org/) - Full-stack React framework.

### API Clients & Data Fetching
* [axios](https://github.com/axios/axios) - HTTP client for Node and browser.
* [ky](https://github.com/sindresorhus/ky) - Tiny Fetch-based HTTP client.
* [SWR](https://github.com/vercel/swr) - React Hooks data fetching.
* [TanStack Query](https://github.com/TanStack/query) - Async state + caching.

### Authentication
* [Passport](https://www.passportjs.org/) - Authentication middleware for Node.
* [Lucia](https://lucia-auth.com/) - Auth library (TypeScript-friendly).
* [NextAuth.js](https://authjs.dev/) - Authentication for Next.js and beyond.

### ORM & Databases
* [Prisma](https://github.com/prisma/prisma) - Type-safe ORM.
* [Drizzle ORM](https://github.com/drizzle-team/drizzle-orm) - SQL-first TypeScript ORM.
* [Sequelize](https://github.com/sequelize/sequelize) - Feature-rich ORM.
* [TypeORM](https://github.com/typeorm/typeorm) - ORM for TS/JS.
* [Mongoose](https://github.com/Automattic/mongoose) - MongoDB object modeling.
* [Knex](https://github.com/knex/knex) - SQL query builder.
* [Kysely](https://github.com/kysely-org/kysely) - Type-safe SQL query builder.

### Queues & Jobs
* [BullMQ](https://github.com/taskforcesh/bullmq) - Redis-backed queue.
* [Agenda](https://github.com/agenda/agenda) - Job scheduling for Node.
* [Bree](https://github.com/breejs/bree) - Job scheduler using worker threads.

### WebSockets
* [Socket.IO](https://github.com/socketio/socket.io) - Realtime framework with fallbacks.
* [ws](https://github.com/websockets/ws) - Fast WebSocket implementation.

### CMS
* [Strapi](https://github.com/strapi/strapi) - Open-source headless CMS.
* [Ghost](https://github.com/tryghost/Ghost) - Publishing platform.
* [KeystoneJS](https://github.com/keystonejs/keystone) - CMS + app framework.

## Utilities

### Files
* [Papa Parse](https://github.com/mholt/PapaParse) - CSV parsing.
* [jsPDF](https://github.com/parallax/jsPDF) - PDF generation.
* [PDF.js](https://github.com/mozilla/pdf.js) - PDF reader in JavaScript.
* [diff2html](https://github.com/rtfpessoa/diff2html) - Git diff → pretty HTML.

### Functional Programming
* [lodash](https://github.com/lodash/lodash) - Utility library.
* [underscore](https://github.com/jashkenas/underscore) - Utility belt.
* [ramda](https://github.com/ramda/ramda) - Practical FP library.
* [fxjs](https://github.com/marpple/FxTS) - Lazy evaluation + concurrency helpers.

### Reactive Programming
* [RxJS](https://github.com/ReactiveX/rxjs) - Reactive programming library.
* [Most.js](https://github.com/cujojs/most) - High-performance FRP library.
* [Bacon.js](https://github.com/baconjs/bacon.js) - FRP library.

### Data Structures
* [immutable-js](https://github.com/immutable-js/immutable-js) - Persistent data structures.
* [js-sdsl](https://github.com/zly201/js-sdsl) - STL-like containers for JS.

### Date & Time
* [date-fns](https://github.com/date-fns/date-fns) - Modern date utility library.
* [dayjs](https://github.com/iamkun/dayjs) - Small Moment-like API.
* [luxon](https://github.com/moment/luxon) - Dates and times with Intl.
* [ms](https://github.com/vercel/ms) - Millisecond conversion utility.

### String
* [he](https://github.com/mathiasbynens/he) - HTML entity encoder/decoder.
* [query-string](https://github.com/sindresorhus/query-string) - Parse/stringify URL query strings.
* [sprintf.js](https://github.com/alexei/sprintf.js) - sprintf implementation.

### Number
* [Numeral.js](https://github.com/adamwdraper/Numeral-js) - Number formatting.
* [chance](https://github.com/chancejs/chancejs) - Random generator helpers.
* [Fraction.js](https://github.com/infusion/Fraction.js) - Rational numbers.

### Storage
* [localForage](https://github.com/localForage/localForage) - Offline storage wrapper.
* [Dexie.js](https://github.com/dexie/Dexie.js) - IndexedDB wrapper.
* [js-cookie](https://github.com/js-cookie/js-cookie) - Cookie API.

### Color
* [chroma.js](https://github.com/gka/chroma.js) - Color manipulations.
* [randomColor](https://github.com/davidmerfield/randomColor) - Color generator.
* [TinyColor](https://github.com/bgrins/TinyColor) - Color manipulation/conversion.

### I18n & L10n
* [i18next](https://github.com/i18next/i18next) - Internationalization framework.
* [ttag](https://github.com/ttag-org/ttag) - Modern i18n using tagged templates.

### Control Flow
* [async](https://github.com/caolan/async) - Async utilities.
* [p-limit](https://github.com/sindresorhus/p-limit) - Limit concurrent promises.
* [p-retry](https://github.com/sindresorhus/p-retry) - Retry async functions.

### Routing
* [director](https://github.com/flatiron/director) - Isomorphic router.
* [page.js](https://github.com/visionmedia/page.js) - Micro client-side router.

### RegExp
* [Regex101](https://regex101.com/#javascript) - Online regex tester/debugger.
* [RegExr](https://regexr.com/) - Regex editor and learning tool.

### Security
* [DOMPurify](https://github.com/cure53/DOMPurify) - XSS sanitizer for HTML/SVG/MathML.
* [sanitize-html](https://github.com/apostrophecms/sanitize-html) - HTML sanitizer.
* [js-xss](https://github.com/leizongmin/js-xss) - Sanitize untrusted HTML.

### Logging
* [pino](https://github.com/pinojs/pino) - Very fast logger for Node.
* [winston](https://github.com/winstonjs/winston) - Multi-transport async logging.
* [loglevel](https://github.com/pimterry/loglevel) - Minimal log level wrapper.

### Benchmarking
* [benchmark.js](https://github.com/bestiejs/benchmark.js) - Benchmarking library.
* [matcha](https://github.com/logicalparadox/matcha) - Simple benchmarking runner.

## Cross-Platform

### CLI
* [commander](https://github.com/tj/commander.js) - CLI framework.
* [yargs](https://github.com/yargs/yargs) - CLI argument parsing.
* [oclif](https://github.com/oclif/oclif) - Opinionated CLI framework.
* [zx](https://github.com/google/zx) - Write shell scripts in JavaScript.

### Desktop Apps
* [Electron](https://www.electronjs.org/) - Cross-platform desktop apps.
* [Tauri](https://tauri.app/) - Smaller desktop apps (JS frontend + Rust core).

### Mobile Apps
* [React Native](https://reactnative.dev/) - Native mobile apps with JS/TS.
* [Expo](https://expo.dev/) - Tooling + platform for React Native apps.
* [Ionic](https://ionicframework.com/) - Hybrid app framework.

## AI & ML
* [TensorFlow.js](https://www.tensorflow.org/js/) - Train/deploy ML models in JS.
* [Brain.js](https://github.com/BrainJS/brain.js) - Neural networks in JavaScript.
* [ml5.js](https://ml5js.org/) - Friendly ML for the web.

## Generative AI
* [OpenAI SDK](https://github.com/openai/openai-node) - Official JavaScript/TypeScript library for the OpenAI API.
* [LangChain.js](https://github.com/langchain-ai/langchainjs) - LLM application framework for JS/TS.
* [Vercel AI SDK](https://sdk.vercel.ai/docs) - Build AI features for web apps.

## Articles & Posts
* [Clean Code JavaScript](https://github.com/ryanmcdermott/clean-code-javascript) - Clean Code ideas adapted for JS.
* [javascript-algorithms](https://github.com/trekhleb/javascript-algorithms) - Algorithms and data structures in JS.
* [Roadmap.sh JavaScript Roadmap](https://roadmap.sh/javascript) - Community learning roadmap.

# Worth Reading
* [You Don’t Know JS Yet](https://github.com/getify/You-Dont-Know-JS) - Deep dive series on JS fundamentals and internals.
* [Superhero.js](http://superherojs.com) - Resources for creating and maintaining large JS codebases.
* [braziljs/js-the-right-way](https://github.com/braziljs/js-the-right-way/) - Quick reference for JS best practices.

# Other Awesome Lists
* [sindresorhus/awesome](https://github.com/sindresorhus/awesome)
* [enaqx/awesome-react](https://github.com/enaqx/awesome-react)
* [denolib/awesome-deno](https://github.com/denolib/awesome-deno)
* [apvarun/awesome-bun](https://github.com/apvarun/awesome-bun)

# Contributing
Contributions welcome! Read the [contribution guidelines](CONTRIBUTING.md) first.

# License
[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the authors have waived all copyright and related or neighboring rights to this work.
