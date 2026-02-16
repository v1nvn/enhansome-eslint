# Awesome ESLint [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) with stars

[<img src="https://eslint.org/icon.svg" width="160" align="right" alt="eslint">](http://eslint.org)

> A list of awesome ESLint configs, plugins, etc.

If you want to contribute, please read the [contribution guidelines](origin/contributing.md).

## Contents

* [Configs](#configs)
  * [Configs by Well-Known Companies/Organizations](#configs-by-well-known-companiesorganizations)
  * [Other Prominent Configs (100 stars or so)](#other-prominent-configs-100-stars-or-so)
  * [Other Configs](#other-configs)
* [Preconfigured Configs with ESLint Set up](#preconfigured-configs-with-eslint-set-up)
* [Plugins](#plugins)
  * [Code Quality](#code-quality)
  * [Compatibility](#compatibility)
  * [CSS in JS](#css-in-js)
  * [Deprecation](#deprecation)
  * [Embedded](#embedded)
  * [Frameworks](#frameworks)
  * [Languages and Environments](#languages-and-environments)
  * [Libraries](#libraries)
  * [Misc](#misc)
  * [Practices and Specific ES Features](#practices-and-specific-es-features)
  * [Performance](#performance)
  * [Security](#security)
  * [Style](#style)
  * [Testing Tools](#testing-tools)
* [Parsers](#parsers)
* [Formatters](#formatters)
* [Globals](#globals)
* [Tools](#tools)
* [Developing for ESLint](#developing-for-eslint)
* [Tutorials](#tutorials)
* [Installation and Setup](#installation-and-setup)

## Configs

### Configs by Well-Known Companies/Organizations

* [Airbnb](https://github.com/airbnb/javascript/tree/master/packages/eslint-config-airbnb) ⭐ 148,087 | 🐛 185 | 🌐 JavaScript | 📅 2025-11-06 - Shareable config for [Airbnb's style guide](https://github.com/airbnb/javascript) ⭐ 148,087 | 🐛 185 | 🌐 JavaScript | 📅 2025-11-06.
* [ESLint](https://github.com/eslint/eslint/tree/master/packages/eslint-config-eslint) ⭐ 26,898 | 🐛 94 | 🌐 JavaScript | 📅 2026-02-15 - Contains the ESLint configuration used for projects maintained by the ESLint team.
* [Alloy](https://github.com/AlloyTeam/eslint-config-alloy) ⭐ 2,644 | 🐛 10 | 🌐 JavaScript | 📅 2024-01-11 - Progressive ESLint config for your React/Vue/TypeScript projects.
* [Shopify](https://github.com/Shopify/web-foundation/blob/main/packages/eslint-plugin/README.md) ⭐ 488 | 🐛 21 | 🌐 JavaScript | 📅 2026-01-27 - Shareable config for [Shopify's style guide](https://github.com/Shopify/javascript) ⭐ 261 | 🐛 13 | 📅 2022-07-14.
* [Wikimedia](https://github.com/wikimedia/eslint-config-wikimedia) ⭐ 33 | 🐛 36 | 🌐 JavaScript | 📅 2026-02-06 - Shareable config for [Wikimedia's style guide](https://www.mediawiki.org/wiki/Manual:Coding_conventions/JavaScript), used by [MediaWiki](https://www.mediawiki.org/).
* [Feedzai](https://github.com/feedzai/eslint-config-feedzai) ⭐ 9 | 🐛 7 | 🌐 JavaScript | 📅 2024-07-12 - Feedzai's shareable config for JavaScript/React projects.
* [Airbnb-babel](https://github.com/davidjbradshaw/eslint-config-airbnb-babel) ⭐ 3 | 🐛 0 | 🌐 JavaScript | 📅 2023-02-25 - Airbnb's ESLint config with Babel Support.
* [Facebook](https://www.npmjs.com/package/eslint-config-fbjs) - Sharable config for Facebook's style guide.

### Other Prominent Configs (100 stars or so)

* [Canonical](https://github.com/gajus/eslint-config-canonical) ⭐ 621 | 🐛 4 | 🌐 TypeScript | 📅 2026-01-26 - Shareable config for [Canonical style guide](https://github.com/gajus/canonical) ⭐ 19 | 🐛 6 | 🌐 JavaScript | 📅 2017-01-11.
* [Auto](https://github.com/davidjbradshaw/eslint-config-auto) ⭐ 402 | 🐛 19 | 🌐 JavaScript | 📅 2024-05-01 - Automatically configure ESLint based on your project's dependencies.

<!-- lint disable double-link -->

* [Antfu Eslint Config](https://github.com/antfu/eslint-config) ⭐ 6,050 | 🐛 54 | 🌐 JavaScript | 📅 2026-02-11 - Anthony's ESLint config preset.
* [Standard](https://github.com/feross/eslint-config-standard) ⭐ 2,651 | 🐛 29 | 🌐 TypeScript | 📅 2026-02-15 - Shareable config for JavaScript [Standard Style](https://github.com/feross/standard) ⭐ 29,427 | 🐛 128 | 🌐 JavaScript | 📅 2025-07-11.
* [XO](https://github.com/xojs/eslint-config-xo) ⭐ 282 | 🐛 1 | 🌐 JavaScript | 📅 2026-02-07 - Shareable config for [XO](https://github.com/xojs/xo) ⭐ 7,949 | 🐛 64 | 🌐 TypeScript | 📅 2026-02-10.

### Other Configs

* [Hardcore](https://github.com/EvgenyOrekhov/eslint-config-hardcore) ⭐ 461 | 🐛 46 | 🌐 JavaScript | 📅 2026-01-22 - The most strict (but practical) ESLint config out there.
* [Sheriff](https://github.com/AndreaPontrandolfo/sheriff) ⭐ 179 | 🐛 16 | 🌐 TypeScript | 📅 2025-11-30 - Comprehensive and highly opinionated Eslint configuration. Typescript oriented.
* [Problems](https://github.com/RyanZim/eslint-config-problems) ⭐ 67 | 🐛 3 | 🌐 JavaScript | 📅 2026-02-07 - Shareable config that only catches actual problems, and doesn't enforce stylistic preferences.
* [Adjunct](https://github.com/davidjbradshaw/eslint-config-adjunct) ⭐ 52 | 🐛 1 | 🌐 JavaScript | 📅 2026-02-09 - A reasonable collection of plugins to use alongside your main ESLint configuration.
* [Ash-Nazg](https://github.com/brettz9/eslint-config-ash-nazg) ⭐ 8 | 🐛 0 | 🌐 JavaScript | 📅 2026-02-04 - One config to rule them all!
* [Cecilia](https://github.com/SandroMiguel/eslint-config-cecilia) ⭐ 7 | 🐛 3 | 🌐 JavaScript | 📅 2025-11-17 - ESLint configuration for awesome projects.
* [Supermind](https://github.com/supermind/eslint-config-supermind) ⭐ 4 | 🐛 7 | 🌐 JavaScript | 📅 2021-08-11 - Shareable config for Supermind style.
* [clean-typescript](https://github.com/cunarist/eslint-config-clean-typescript) - Enforce classic JavaScript featuress in TypeScript codebase by banning excessive keywords.

## Preconfigured Configs with ESLint Set up

* [Standard](https://github.com/feross/standard) ⭐ 29,427 | 🐛 128 | 🌐 JavaScript | 📅 2025-07-11 - JavaScript Standard Style.
* [XO](https://github.com/sindresorhus/xo) ⭐ 7,949 | 🐛 64 | 🌐 TypeScript | 📅 2026-02-10 - JavaScript happiness style linter ❤️.
* [eslint-config-prettier](https://github.com/prettier/eslint-config-prettier) ⭐ 5,851 | 🐛 16 | 🌐 JavaScript | 📅 2026-02-14 - Prettier config for ESlint maintained by Prettier team.
* [Node.js Standard Style](https://github.com/geek/node-style) ⭐ 6 | 🐛 0 | 🌐 JavaScript | 📅 2017-01-28 - Node.js core config.
* [Superlint](https://github.com/supermind/superlint) ⭐ 5 | 🐛 0 | 🌐 JavaScript | 📅 2017-07-21 - JavaScript Supermind Style.

## Plugins

### Code Quality

* [Unicorn](https://github.com/sindresorhus/eslint-plugin-unicorn) ⭐ 4,926 | 🐛 385 | 🌐 JavaScript | 📅 2026-02-15 - Various awesome ESLint rules.
* [SonarJS](https://github.com/SonarSource/SonarJS/blob/master/packages/jsts/src/rules/README.md) ⭐ 1,198 | 🐛 17 | 🌐 TypeScript | 📅 2026-02-16 - Rules detecting bugs and suspicious patterns.
* [depend](https://github.com/es-tooling/eslint-plugin-depend) ⭐ 473 | 🐛 8 | 🌐 TypeScript | 📅 2025-11-12 - Helps detect dependency tree bloat and redundant polyfills.
* [GitHub](https://github.com/github/eslint-plugin-github) ⭐ 326 | 🐛 13 | 🌐 JavaScript | 📅 2026-02-09 - Misc. rules from GitHub.
* [De Morgan](https://github.com/azat-io/eslint-plugin-de-morgan) ⭐ 305 | 🐛 0 | 🌐 TypeScript | 📅 2026-02-07 - Transforms logical expressions in code to make them easier to understand.
* [@mysticatea/eslint-plugin](https://github.com/mysticatea/eslint-plugin) ⭐ 26 | 🐛 25 | 🌐 JavaScript | 📅 2022-11-14 - Misc. rules.
* [eslint-plugin-code-complete](https://github.com/aryelu/eslint-plugin-code-complete) ⭐ 12 | 🐛 1 | 🌐 TypeScript | 📅 2025-12-27 - A custom ESLint plugin that enforces principles of clean, maintainable software design — inspired by Code Complete.
* [@brettz9/eslint-plugin](https://github.com/brettz9/eslint-plugin) ⭐ 2 | 🐛 0 | 🌐 JavaScript | 📅 2024-07-18 - Misc. rules. of `@mysticatea` without the personal config.

### Compatibility

* [Compat](https://github.com/amilajack/eslint-plugin-compat) ⭐ 3,163 | 🐛 90 | 🌐 TypeScript | 📅 2026-01-23 - Lint browser compatibility of APIs used ([caniuse](http://caniuse.com/#search=fetch) as an ESLint plugin).
* [es-x](https://github.com/eslint-community/eslint-plugin-es-x) ⭐ 147 | 🐛 3 | 🌐 JavaScript | 📅 2026-02-07 - Disable specific ECMAScript language versions or individual features. Properly maintained fork of no longer maintained `eslint-plugin-es`.
* [ecmascript-compat](https://github.com/robatwilliams/es-compat) ⭐ 69 | 🐛 14 | 🌐 JavaScript | 📅 2025-08-18 - Disable ECMAScript language features not supported by your browserslist targets.
* [es5](https://github.com/nkt/eslint-plugin-es5) ⭐ 55 | 🐛 13 | 🌐 JavaScript | 📅 2022-12-30 - ESLint plugin for ES5 users (forbid ES2015+ usage).
* [ie11](https://github.com/Volox/eslint-plugin-ie11) ⭐ 15 | 🐛 1 | 🌐 JavaScript | 📅 2021-02-19 - Detect unsupported ES6 features in IE11.

### CSS in JS

* [Emotion](https://github.com/emotion-js/emotion/tree/master/packages/eslint-plugin) ⭐ 17,999 | 🐛 368 | 🌐 JavaScript | 📅 2025-11-04 - ESLint rules for emotion.
* [CSS-modules](https://github.com/atfzl/eslint-plugin-css-modules) ⭐ 155 | 🐛 35 | 🌐 JavaScript | 📅 2024-11-29 - Lint undefined or unused rules for css modules.
* Styled Components
  * [styled-components-a11y](https://github.com/brendanmorrell/eslint-plugin-styled-components-a11y) ⭐ 153 | 🐛 7 | 🌐 JavaScript | 📅 2026-01-22 - A11y for Styled Components.
  * [Better Styled Components](https://github.com/tinloof/eslint-plugin-better-styled-components) ⭐ 66 | 🐛 12 | 🌐 JavaScript | 📅 2022-12-30 - Auto fixable ESlint's rules for styled components.
* [vanilla-extract](https://github.com/antebudimir/eslint-plugin-vanilla-extract) ⭐ 31 | 🐛 1 | 🌐 TypeScript | 📅 2025-12-01 - An ESLint plugin for enforcing CSS property ordering in [vanilla-extract CSS](https://github.com/vanilla-extract-css/vanilla-extract) ⭐ 10,300 | 🐛 88 | 🌐 TypeScript | 📅 2025-12-28 styles.

### Deprecation

* [deprecate](https://github.com/AlexMost/eslint-plugin-deprecate) ⭐ 84 | 🐛 10 | 🌐 JavaScript | 📅 2025-06-30 - Mark functions or modules as deprecated and get lint messages when they are used.
* [disable](https://github.com/mradionov/eslint-plugin-disable) ⭐ 56 | 🐛 3 | 🌐 JavaScript | 📅 2023-03-04 - Disable specified plugins using file path patterns and inline comments.

### Embedded

* [Markdown](https://github.com/eslint/eslint-plugin-markdown) ⭐ 539 | 🐛 20 | 🌐 JavaScript | 📅 2026-02-15 - Linting for JavaScript inside of Markdown.
* [HTML](https://github.com/BenoitZugmeyer/eslint-plugin-html) ⭐ 452 | 🐛 17 | 🌐 JavaScript | 📅 2026-02-16 - Linting for JavaScript inside of HTML `<script>` tags.

### Frameworks

* React
  * [React Hooks](https://github.com/facebook/react/tree/master/packages/eslint-plugin-react-hooks) ⭐ 243,009 | 🐛 1,121 | 🌐 JavaScript | 📅 2026-02-16 - Linting rules for React Hooks.
  * [React](https://github.com/yannickcr/eslint-plugin-react) ⭐ 9,258 | 🐛 367 | 🌐 JavaScript | 📅 2026-02-10 - Linting rules for React and JSX.
  * [JSX a11y](https://github.com/jsx-eslint/eslint-plugin-jsx-a11y) ⭐ 3,562 | 🐛 125 | 🌐 JavaScript | 📅 2026-01-06 - Accessibility rules on JSX elements.
  * [React Native](https://github.com/Intellicode/eslint-plugin-react-native) ⭐ 761 | 🐛 85 | 🌐 JavaScript | 📅 2024-12-30 - React Native specific linting rules.
  * [React Refresh](https://github.com/ArnaudBarre/eslint-plugin-react-refresh) ⭐ 323 | 🐛 7 | 🌐 TypeScript | 📅 2026-02-01 - Improve HMR experience when using Vite.
  * [React-Redux](https://github.com/DianaSuvorova/eslint-plugin-react-redux) ⭐ 83 | 🐛 31 | 🌐 JavaScript | 📅 2025-03-25 - React-Redux specific linting rules.
* [Meteor](https://github.com/meteor/meteor/tree/devel/npm-packages/eslint-plugin-meteor) ⭐ 44,780 | 🐛 340 | 🌐 JavaScript | 📅 2026-02-13 - Meteor specific linting rules for ESLint.
* Vue
  * [VueJS](https://github.com/vuejs/eslint-plugin-vue) ⭐ 4,600 | 🐛 206 | 🌐 JavaScript | 📅 2026-02-15 - Plugin for VueJS.
  * [VueJS Scoped CSS](https://github.com/future-architect/eslint-plugin-vue-scoped-css) ⭐ 107 | 🐛 20 | 🌐 TypeScript | 📅 2026-02-13 - Plugin for Scoped CSS in VueJS.
* [Angular](https://github.com/angular-eslint/angular-eslint) ⭐ 1,773 | 🐛 36 | 🌐 TypeScript | 📅 2026-02-13 - Linting rules for Angular (v2+).
* [AngularJS](https://github.com/Gillespie59/eslint-plugin-angular) ⭐ 620 | 🐛 74 | 🌐 JavaScript | 📅 2025-11-14 - Linting rules to adhere to the [John Papa's AngularJS Styleguide](https://github.com/johnpapa/angular-styleguide) ⭐ 23,716 | 🐛 78 | 📅 2022-05-19.
* [Astro](https://github.com/ota-meshi/eslint-plugin-astro) ⭐ 400 | 🐛 23 | 🌐 TypeScript | 📅 2026-02-14 - Plugin for [Astro components](https://docs.astro.build/en/core-concepts/astro-components/).
* [Svelte](https://github.com/sveltejs/eslint-plugin-svelte) ⭐ 389 | 🐛 128 | 🌐 TypeScript | 📅 2026-02-12 - Linting rules for Svelte v3 Components.
* [Ember](https://github.com/ember-cli/eslint-plugin-ember) ⭐ 261 | 🐛 174 | 🌐 JavaScript | 📅 2026-02-16 - Linting rules for Ember.
* [Solid](https://github.com/joshwilsonvu/eslint-plugin-solid) ⭐ 255 | 🐛 41 | 🌐 TypeScript | 📅 2026-01-29 - Linting rules for Solid and JSX.
* [Backbone](https://github.com/ilyavolodin/eslint-plugin-backbone) ⭐ 92 | 🐛 4 | 🌐 JavaScript | 📅 2018-01-08 - Linting rules for Backbone.
* [Hapi](https://github.com/continuationlabs/eslint-plugin-hapi) ⭐ 22 | 🐛 2 | 🌐 JavaScript | 📅 2024-10-22 - Linting rules for hapi.

### Languages and Environments

* [Babel](https://github.com/babel/babel/tree/main/eslint/babel-eslint-plugin) ⭐ 43,875 | 🐛 750 | 🌐 TypeScript | 📅 2026-02-15 - Adds replacements for built-in rules to include Babel features.
* Flow
  * [Flow](https://github.com/gajus/eslint-plugin-flowtype) ⭐ 1,070 | 🐛 40 | 🌐 JavaScript | 📅 2024-02-29 - Flow type linting rules.
  * [Flow Errors](https://github.com/amilajack/eslint-plugin-flowtype-errors) ⭐ 403 | 🐛 14 | 🌐 JavaScript | 📅 2022-03-26 - Run Flow as an ESLint plugin.
* [N](https://github.com/eslint-community/eslint-plugin-n) ⭐ 324 | 🐛 50 | 🌐 JavaScript | 📅 2026-02-15 - Additional ESLint's rules for Node.js. Properly maintained fork of no longer maintained `eslint-plugin-node`.
* [MDX](https://github.com/mdx-js/eslint-mdx/tree/master/packages/eslint-plugin-mdx) ⭐ 297 | 🐛 21 | 🌐 TypeScript | 📅 2026-02-13 - ESLint Parser/Plugin for MDX.
* [HTML](https://github.com/yeonjuan/html-eslint) ⭐ 253 | 🐛 30 | 🌐 JavaScript | 📅 2026-02-14 - ESLint plugin for HTML.
* JSON
  * [JSON with Comments](https://github.com/ota-meshi/eslint-plugin-jsonc) ⭐ 231 | 🐛 15 | 🌐 TypeScript | 📅 2026-02-12 - ESLint plugin for JSON, JSONC and JSON5.
  * [eslint-plugin-package-json](https://github.com/JoshuaKGoldberg/eslint-plugin-package-json) ⭐ 224 | 🐛 40 | 🌐 TypeScript | 📅 2026-02-16 - Rules for consistent, readable, and valid package.json files.
  * [JSON](https://github.com/azeemba/eslint-plugin-json) ⭐ 216 | 🐛 19 | 🌐 JavaScript | 📅 2024-08-14 - Lint your JSON files.
  * [JSON Schema](https://github.com/ota-meshi/eslint-plugin-json-schema-validator) ⭐ 91 | 🐛 10 | 🌐 TypeScript | 📅 2026-02-12 - Validates data defined in JavaScript, JSON, YAML and TOML using JSON Schema Validator.
  * [JSON, package.json](https://github.com/Bkucera/eslint-plugin-json-format) ⭐ 41 | 🐛 39 | 🌐 JavaScript | 📅 2023-01-04 - Lint, format, and auto-fix your JSON files. Sort your `package.json`.
* [eslint-plugin-eslint-plugin](https://github.com/not-an-aardvark/eslint-plugin-eslint-plugin) ⭐ 226 | 🐛 35 | 🌐 TypeScript | 📅 2026-02-13 - An ESLint plugin for linting ESLint plugins.
* [YAML](https://github.com/ota-meshi/eslint-plugin-yml) ⭐ 173 | 🐛 13 | 🌐 TypeScript | 📅 2026-02-09 - ESLint plugin for YAML.
* [TypeScript](https://typescript-eslint.io) - Linting rules for TypeScript.
  * [eslint-plugin-expect-type](https://github.com/JoshuaKGoldberg/eslint-plugin-expect-type) ⭐ 118 | 🐛 19 | 🌐 TypeScript | 📅 2026-02-14 - Provides Twoslash, $ExpectError, and $ExpectType type assertions.
  * [eslint-plugin-erasable-syntax-only](https://github.com/JoshuaKGoldberg/eslint-plugin-erasable-syntax-only) ⭐ 50 | 🐛 17 | 🌐 TypeScript | 📅 2026-02-13 - Granularly enforces TypeScript's erasableSyntaxOnly flag.
* [SQL](https://github.com/gajus/eslint-plugin-sql) ⭐ 111 | 🐛 4 | 🌐 TypeScript | 📅 2026-01-12 - SQL linting rules for ESLint.
* [TOML](https://github.com/ota-meshi/eslint-plugin-toml) ⭐ 32 | 🐛 2 | 🌐 TypeScript | 📅 2026-02-07 - ESLint plugin for TOML.

### Libraries

* [Tailwind CSS](https://github.com/francoismassart/eslint-plugin-tailwindcss) ⭐ 2,045 | 🐛 132 | 🌐 JavaScript | 📅 2025-09-15 - Linting rules for Tailwind CSS classnames.
* GraphQL
  * [apollostack/eslint-plugin-graphql](https://github.com/apollostack/eslint-plugin-graphql) ⭐ 1,216 | 🐛 100 | 🌐 JavaScript | 📅 2026-02-12 - Check your GraphQL query strings against a schema.
  * [dotansimha/graphql-eslint](https://github.com/dotansimha/graphql-eslint) ⭐ 833 | 🐛 67 | 🌐 TypeScript | 📅 2026-02-14 - Validates, prettifies and checks your GraphQL operations and GraphQL schema for best-practices.
* [JSDoc](https://github.com/gajus/eslint-plugin-jsdoc) ⭐ 1,197 | 🐛 36 | 🌐 JavaScript | 📅 2026-02-15 - Linting rules for JSDoc comments (including the JavaScript within `@example`).
* [Tailwind CSS v4](https://github.com/schoero/eslint-plugin-better-tailwindcss) ⭐ 685 | 🐛 19 | 🌐 TypeScript | 📅 2026-02-15 - ESLint plugin to help you write better tailwindcss by improving readability with formatting rules and enforcing best practices with linting rules.
* Lodash
  * [Lodash](https://github.com/wix/eslint-plugin-lodash) ⭐ 275 | 🐛 64 | 🌐 JavaScript | 📅 2024-02-01 - Lodash specific linting rules.
  * [Lodash/fp](https://github.com/jfmengels/eslint-plugin-lodash-fp) ⭐ 151 | 🐛 33 | 🌐 JavaScript | 📅 2023-01-04 - Lodash/fp specific linting rules.
  * [Lodash template](https://github.com/ota-meshi/eslint-plugin-lodash-template) ⭐ 17 | 🐛 12 | 🌐 JavaScript | 📅 2026-02-12 - Plugin for Lodash template/Underscore template.
  * [Microtemplates](https://github.com/platinumazure/eslint-plugin-microtemplates) ⭐ 4 | 🐛 5 | 🌐 JavaScript | 📅 2016-03-05 (Used in Lodash and Underscore.js)
* [Ramda](https://github.com/ramda/eslint-plugin-ramda) ⭐ 117 | 🐛 10 | 🌐 JavaScript | 📅 2021-08-20 - Ramda specific linting rules.
* [jQuery](https://github.com/wikimedia/eslint-plugin-no-jquery) ⭐ 32 | 🐛 15 | 🌐 JavaScript | 📅 2026-01-27 - Linting rules for jQuery, including versioned configs for deprecated features.
* [RequireJS](https://github.com/cvisco/eslint-plugin-requirejs) ⭐ 29 | 🐛 12 | 🌐 JavaScript | 📅 2023-01-11 - Linting rules for RequireJS.
* [Mongodb](https://github.com/nfroidure/eslint-plugin-mongodb) ⭐ 20 | 🐛 5 | 🌐 JavaScript | 📅 2022-12-08 - Mongodb native Node.js driver linting rules.
* [TypeGraphQL](https://github.com/borremosch/eslint-plugin-type-graphql) ⭐ 19 | 🐛 6 | 🌐 TypeScript | 📅 2022-07-26 - Linting rules for TypeGraphQL, targeted at finding common mistakes.

### Misc

* [PutOut](https://github.com/coderaiser/putout/tree/master/packages/eslint-plugin-putout) ⭐ 782 | 🐛 0 | 🌐 JavaScript | 📅 2026-02-15 - an ESLint plugin integrates [putout](https://github.com/coderaiser/putout) ⭐ 782 | 🐛 0 | 🌐 JavaScript | 📅 2026-02-15 linter into ESLint.
* [Diff](https://github.com/paleite/eslint-plugin-diff) ⭐ 209 | 🐛 26 | 🌐 TypeScript | 📅 2026-01-22 - Run ESLint on your changed lines only. Also supports CI!
* [Only-Warn](https://github.com/bfanger/eslint-plugin-only-warn) ⭐ 181 | 🐛 1 | 🌐 JavaScript | 📅 2024-06-01 - Convert all rules to warnings.
* [TypeLint](https://github.com/yarax/eslint-plugin-typelint) ⭐ 173 | 🐛 1 | 🌐 JavaScript | 📅 2018-06-13 - Introduces types, based on existing schemas (Swagger, Redux) and linting access to object properties, preventing `undefined` errors.
* [Woke](https://github.com/amwmedia/eslint-plugin-woke) ⭐ 38 | 🐛 7 | 🌐 JavaScript | 📅 2024-10-16 - Helps catch insensitive words, promoting an inclusive codebase.
* [Notice](https://github.com/nickdeis/eslint-plugin-notice) ⭐ 27 | 🐛 6 | 🌐 JavaScript | 📅 2025-02-19 - An eslint rule that checks the top of files and fixes them too!
* [Only-Error](https://github.com/davidjbradshaw/eslint-plugin-only-error) ⭐ 17 | 🐛 1 | 🌐 JavaScript | 📅 2024-06-22 - Convert all rules to errors.
* [Misc](https://github.com/ilyub/eslint-plugin-misc) ⭐ 12 | 🐛 1 | 🌐 TypeScript | 📅 2024-08-27 - Miscellaneous rules including rules for creating custom checks and wrapping (modifying) third-party rules.

### Practices and Specific ES Features

* [import](https://github.com/benmosher/eslint-plugin-import) ⭐ 5,870 | 🐛 594 | 🌐 JavaScript | 📅 2025-12-30 - Linting of ES2015+ import/export syntax, and prevent issues with misspelling of file paths and import names.
* [fp](https://github.com/jfmengels/eslint-plugin-fp) ⭐ 972 | 🐛 31 | 🌐 JavaScript | 📅 2021-01-01 - ESLint rules for functional programming.
* [functional](https://github.com/jonaskello/eslint-plugin-functional) ⭐ 961 | 🐛 10 | 🌐 TypeScript | 📅 2026-02-16 - ESLint rules to disable mutation and promote fp in JavaScript and TypeScript.
* [Immutable](https://github.com/jhusain/eslint-plugin-immutable) ⭐ 912 | 🐛 13 | 🌐 JavaScript | 📅 2019-11-06 - Disable all mutation in JavaScript.
* [boundaries](https://github.com/javierbrea/eslint-plugin-boundaries) ⭐ 784 | 🐛 31 | 🌐 TypeScript | 📅 2026-02-03 - Ensures that your architecture boundaries are respected by the elements in your project checking file structure and dependencies.
* [import-x](https://github.com/un-ts/eslint-plugin-import-x) ⭐ 651 | 🐛 72 | 🌐 TypeScript | 📅 2025-10-29 - Linting of ES2015+ import/export syntax, and prevent issues with misspelling of file paths and import names. Lightweight fork of `eslint-plugin-import`, but which breaks backwards compatibility.
* [eslint-plugin-hexagonal-architecture](https://github.com/CodelyTV/eslint-plugin-hexagonal-architecture) ⭐ 313 | 🐛 3 | 🌐 TypeScript | 📅 2022-09-23 - A plugin that helps you to enforce hexagonal architecture best practices.
* [arrow functions](https://github.com/getify/eslint-plugin-proper-arrows) ⭐ 311 | 🐛 5 | 🌐 JavaScript | 📅 2024-12-27 - ESLint rules to ensure proper arrow function definitions.
* [array-func](https://github.com/freaktechnik/eslint-plugin-array-func) ⭐ 96 | 🐛 11 | 🌐 JavaScript | 📅 2026-02-16 - Avoid redundancy when using es2015 array methods and functions.
* [@eslint-community/eslint-plugin-eslint-comments](https://github.com/eslint-community/eslint-plugin-eslint-comments) ⭐ 92 | 🐛 36 | 🌐 JavaScript | 📅 2026-02-08 - Best practices about ESLint directive comments (`/*eslint-disable*/`, etc.). Properly maintained fork of no longer maintained `eslint-plugin-eslint-comments`.
* [eslint-plugin-exception-handling](https://github.com/Akronae/eslint-plugin-exception-handling) ⭐ 59 | 🐛 2 | 🌐 TypeScript | 📅 2025-10-25 - Lints unhandled functions that might throw errors.
* [eslint-plugin-write-good-comments](https://github.com/kantord/eslint-plugin-write-good-comments) ⭐ 41 | 🐛 2 | 🌐 JavaScript | 📅 2023-12-15 - Enforce good writing style in comments.
* [new-with-error](https://github.com/Trott/eslint-plugin-new-with-error) ⭐ 26 | 🐛 0 | 🌐 JavaScript | 📅 2026-02-13 - Require errors to be thrown using `new`.
* [eslint-plugin-error-cause](https://github.com/Amnish04/eslint-plugin-error-cause) ⚠️ Archived - A plugin to preserve original error context when re-throwing exceptions.
* [Math](https://github.com/ota-meshi/eslint-plugin-math) ⭐ 15 | 🐛 4 | 🌐 TypeScript | 📅 2026-02-11 - ESLint plugin related to Math object and Number.
* [eslint-plugin-signature-design](https://github.com/Vladyslav-Soldatenko/eslint-plugin-signature-design) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2025-06-05 - Forbids functions with too many parameters of the same type, encouraging object-based signatures and preventing primitive obsession.
* [mutate](https://github.com/gchumillas/eslint-plugin-mutate) ⭐ 1 | 🐛 2 | 🌐 JavaScript | 📅 2025-06-25 - Prevent accidental parameter mutations by enforcing explicit `mut` prefix (JavaScript) or `Mut<T>` type annotation (TypeScript).

<!-- lint ignore awesome-spell-check -->

* [Promise](https://github.com/xjamundx/eslint-plugin-promise) ⭐ 987 | 🐛 50 | 🌐 JavaScript | 📅 2026-02-12 - Best practices when working with promises.
* [RegExp](https://github.com/ota-meshi/eslint-plugin-regexp) ⭐ 757 | 🐛 17 | 🌐 TypeScript | 📅 2026-02-10 - ESLint plugin for finding regexp mistakes and style guide violations.
* [no-loops](https://github.com/buildo/eslint-plugin-no-loops) ⭐ 130 | 🐛 2 | 🌐 JavaScript | 📅 2025-11-21 - It's 2019 and you still use loops?
* [sort-keys-fix](https://github.com/leo-buneev/eslint-plugin-sort-keys-fix) ⭐ 102 | 🐛 24 | 🌐 JavaScript | 📅 2024-06-18 - Adds fixer for ESLint `sort-keys` rule.
* [no-use-extend-native](https://github.com/dustinspecker/eslint-plugin-no-use-extend-native) ⭐ 57 | 🐛 5 | 🌐 JavaScript | 📅 2025-05-08 - Prevent using extended native objects.
* [pure](https://github.com/purely-functional/eslint-plugin-pure) ⭐ 32 | 🐛 1 | 🌐 JavaScript | 📅 2016-06-07 - Enforce pure functions (without side effects).
* [no-inferred-method-name](https://github.com/johnstonbl01/eslint-no-inferred-method-name) ⭐ 27 | 🐛 6 | 🌐 JavaScript | 📅 2022-02-12 - Custom rule for ESLint that checks for inferred method names within object literals.
* [toplevel](https://github.com/HKalbasi/eslint-plugin-toplevel) ⭐ 20 | 🐛 3 | 🌐 JavaScript | 📅 2026-01-29 - An eslint plugin for disallow side effect at module toplevel.
* [no-comments](https://github.com/wisniewski94/eslint-plugin-no-comments) ⭐ 16 | 🐛 3 | 🌐 JavaScript | 📅 2025-05-25 - Prevents leaking comments into production if bundler is not used and stops developers from commenting out old lines of code.
* [this](https://github.com/matijs/eslint-plugin-this) ⭐ 16 | 🐛 0 | 🌐 JavaScript | 📅 2023-03-09 - Write pure functions, don't allow `this`.
* [no-constructor-bind](https://github.com/markalfred/eslint-plugin-no-constructor-bind) ⭐ 12 | 🐛 5 | 🌐 JavaScript | 📅 2023-03-04 - Encourages use of class properties by reporting use of `this` with `bind` or setting state in constructors.
* [ReDoSDetector](https://github.com/tjenkinson/eslint-plugin-redos-detector) ⭐ 12 | 🐛 10 | 🌐 TypeScript | 📅 2026-02-16 - ESLint plugin for finding possible ReDoS vulnerabilities.
* [no-restricted-syntax](https://github.com/brettz9/eslint-plugin-query) ⭐ 5 | 🐛 0 | 🌐 JavaScript | 📅 2025-08-28 - Show queried syntax's content in messages.
* [no-argument-spread](https://github.com/causalhq/eslint-plugin-no-argument-spread) ⭐ 3 | 🐛 0 | 🌐 JavaScript | 📅 2022-06-16 - Lints against expressions like `Math.max(...args)` that can lead to a stack overflow for large arrays.
* [ReDoS](https://makenowjust-labs.github.io/recheck/docs/usage/as-eslint-plugin/) - ESLint plugin for finding possible ReDoS vulnerabilities.

### Performance

* [Optimize Regex](https://github.com/BrainMaestro/eslint-plugin-optimize-regex) ⭐ 76 | 🐛 8 | 🌐 JavaScript | 📅 2024-06-20 - Optimize regex literals.
* Perf-Standard [plugin](https://github.com/Raynos/eslint-plugin-perf-standard) ⭐ 24 | 🐛 2 | 🌐 JavaScript | 📅 2016-12-29 and [Config](https://github.com/Raynos/eslint-config-perf-standard) ⭐ 3 | 🐛 3 | 🌐 JavaScript | 📅 2016-04-13
* [DOM](https://github.com/amilajack/eslint-plugin-dom) ⭐ 9 | 🐛 5 | 🌐 JavaScript | 📅 2018-10-03

### Security

* [Security](https://github.com/nodesecurity/eslint-plugin-security) ⭐ 2,322 | 🐛 14 | 🌐 JavaScript | 📅 2026-02-13 - ESLint rules for Node Security.
* [no-unsanitized](https://github.com/mozilla/eslint-plugin-no-unsanitized) ⭐ 240 | 🐛 36 | 🌐 JavaScript | 📅 2026-02-13 - Checks for `innerHTML`, `outerHTML`, etc.
* [no-secrets](https://github.com/nickdeis/eslint-plugin-no-secrets) ⭐ 162 | 🐛 8 | 🌐 TypeScript | 📅 2026-02-10 - An eslint plugin that detects potential secrets/credentials.
* [xss](https://github.com/Rantanen/eslint-plugin-xss) ⭐ 70 | 🐛 6 | 🌐 JavaScript | 📅 2023-08-29 - Tries to detect XSS issues in codebase before they end up in production.
* [pii](https://github.com/shiva-hack/eslint-plugin-pii) ⭐ 11 | 🐛 1 | 🌐 JavaScript | 📅 2022-04-25 - Checks and enforces PII Compliance of the code. i.e. no email address, birth date, IP address or phone number in comments or string literals.
* [pg](https://github.com/interlace-collie/eslint/tree/main/packages/eslint-plugin-pg) - PostgreSQL/node-postgres security: SQL injection prevention (CWE-89), connection pool leak detection (CWE-772), transaction safety. 13 rules with CWE mapping.

### Style

* [perfectionist sorting](https://github.com/azat-io/eslint-plugin-perfectionist) ⭐ 2,811 | 🐛 6 | 🌐 TypeScript | 📅 2026-02-13 - Sort objects, imports, TypeScript types, enums, JSX props, etc.
* [Simple import sort](https://github.com/lydell/eslint-plugin-simple-import-sort) ⭐ 2,408 | 🐛 8 | 🌐 JavaScript | 📅 2026-01-22 - Easy autofixable import sorting.
* [filenames](https://github.com/selaux/eslint-plugin-filenames) ⭐ 321 | 🐛 26 | 🌐 JavaScript | 📅 2024-07-27 - Ensure consistent filenames for your JavaScript files. No longer maintained and does not work with ESlint 9 at all.
* [paths](https://github.com/vitonsky/eslint-plugin-paths) ⭐ 86 | 🐛 19 | 🌐 TypeScript | 📅 2025-06-17 - Use paths from tsconfig/jsconfig and auto fix relative paths to aliases.
* [Switch case](https://github.com/lukeapage/eslint-plugin-switch-case) ⭐ 18 | 🐛 6 | 🌐 JavaScript | 📅 2024-08-02 - Switch-case-specific linting rules for ESLint.
* [editorconfig](https://github.com/platinumazure/eslint-plugin-editorconfig) ⭐ 17 | 🐛 4 | 🌐 JavaScript | 📅 2023-10-07 - Derive rules from [`.editorconfig`](https://editorconfig.org/).
* [padding](https://github.com/mu-io/eslint-plugin-padding) ⭐ 6 | 🐛 0 | 🌐 TypeScript | 📅 2025-11-05 - Allows/disallows padding between statements.
* [split-and-sort-imports](https://github.com/sngn/eslint-plugin-split-and-sort-imports) ⭐ 1 | 🐛 0 | 🌐 JavaScript | 📅 2025-04-21 - Sorts imports and splits 'multiple' imports into single line imports.
* [ESLint Stylistic](https://eslint.style/) - [Formatting and stylistic ESLint core rules moved to this project and are maintained by the community.](https://eslint.org/blog/2023/10/deprecating-formatting-rules/)
* [const case](https://www.npmjs.com/package/eslint-plugin-const-case) - Enforce capitalization of constant primitive literals.
* [@gitbutler/no-relative-imports](https://www.npmjs.com/package/@gitbutler/no-relative-imports) - Use paths from tsconfig and auto fix relative paths to aliases. Observes tsconfig inheritance.

### Testing Tools

* Jest
  * [Enforcing practices](https://github.com/jest-community/eslint-plugin-jest) ⭐ 1,167 | 🐛 24 | 🌐 TypeScript | 📅 2026-02-16 - Linting rules for Jest.
  * [Jest-DOM](https://github.com/testing-library/eslint-plugin-jest-dom) ⭐ 366 | 🐛 13 | 🌐 JavaScript | 📅 2026-02-13 - Linting rules for Jest-DOM.
  * [Enforcing consistent formatting](https://github.com/dangreenisrael/eslint-plugin-jest-formatting) ⭐ 156 | 🐛 5 | 🌐 JavaScript | 📅 2023-05-21 - Formatting rules for Jest.
  * [Jest-async](https://www.npmjs.com/package/eslint-plugin-jest-async) - Async linting rule for Jest.
* [Testing Library](https://github.com/testing-library/eslint-plugin-testing-library) ⭐ 1,043 | 🐛 30 | 🌐 TypeScript | 📅 2026-02-13 - Linting rules for Testing Library.
* [Cypress](https://github.com/cypress-io/eslint-plugin-cypress) ⭐ 721 | 🐛 24 | 🌐 JavaScript | 📅 2026-02-09 - Linting rules for Cypress.
* [Playwright](https://github.com/playwright-community/eslint-plugin-playwright) ⭐ 368 | 🐛 14 | 🌐 TypeScript | 📅 2026-01-29 - Linting rules for Playwright.
* Mocha
  * [Enforcing practices](https://github.com/lo1tuma/eslint-plugin-mocha) ⭐ 289 | 🐛 28 | 🌐 TypeScript | 📅 2025-10-13 - Linting rules for Mocha.
  * [Enforcing manageability](https://github.com/onechiporenko/eslint-plugin-mocha-cleanup/) ⭐ 13 | 🐛 14 | 🌐 JavaScript | 📅 2026-02-13
* [AVA](https://github.com/avajs/eslint-plugin-ava) ⭐ 230 | 🐛 0 | 🌐 JavaScript | 📅 2026-02-10 - Linting rules for AVA.
* [Jasmine](https://github.com/tlvince/eslint-plugin-jasmine) ⭐ 101 | 🐛 75 | 🌐 JavaScript | 📅 2024-10-14 - Linting rules for Jasmine.
* Chai
  * [with unused expressions](https://github.com/ihordiachenko/eslint-plugin-chai-friendly) ⭐ 56 | 🐛 5 | 🌐 JavaScript | 📅 2025-11-18
  * [expect practices](https://github.com/turbo87/eslint-plugin-chai-expect) ⭐ 28 | 🐛 18 | 🌐 JavaScript | 📅 2026-02-12
  * [with chai-as-promised plugin](https://github.com/fintechstudios/eslint-plugin-chai-as-promised) ⭐ 4 | 🐛 5 | 🌐 JavaScript | 📅 2024-07-26
  * [permitted keywords](https://github.com/gavinaiken/eslint-plugin-chai-expect-keywords) ⭐ 1 | 🐛 0 | 🌐 JavaScript | 📅 2024-07-28
  <!-- lint disable double-link -->
  * [globals](https://github.com/t-huth/eslint-plugin-chai-assert-bdd) ⭐ 2 | 🐛 0 | 🌐 JavaScript | 📅 2017-09-14
* [QUnit](https://github.com/platinumazure/eslint-plugin-qunit) ⭐ 31 | 🐛 30 | 🌐 JavaScript | 📅 2026-02-09 - Linting rules for QUnit.
* [Cucumber](https://github.com/darrinholst/eslint-plugin-cucumber) ⭐ 8 | 🐛 5 | 🌐 JavaScript | 📅 2023-05-07 - Linting rules for Cucumber.
* [TestCafe-Community](https://github.com/testcafe-community/eslint-plugin-testcafe-community) ⭐ 4 | 🐛 34 | 🌐 TypeScript | 📅 2025-11-18 - TestCafe linting rules with env globals (fork from [TestCafe globals](https://github.com/miherlosev/eslint-plugin-testcafe) ⭐ 15 | 🐛 3 | 🌐 JavaScript | 📅 2020-05-12).

## Parsers

* [babel-eslint-parser](https://github.com/babel/babel/tree/main/eslint/babel-eslint-parser) ⭐ 43,875 | 🐛 750 | 🌐 TypeScript | 📅 2026-02-15 - Allows you to lint ALL valid Babel code with the fantastic ESLint.
* [GraphQL](https://github.com/dotansimha/graphql-eslint) ⭐ 833 | 🐛 67 | 🌐 TypeScript | 📅 2026-02-14 - Parser for the GraphQL AST. Includes parser, plugin, processor (for non-graphql files) and rules.
* [BrightScript](https://github.com/RokuRoad/eslint-plugin-roku) ⭐ 49 | 🐛 31 | 🌐 TypeScript | 📅 2022-12-07 - BrightScript plugin for Roku development. Includes Parser and Rules.
* [TypeScript](https://typescript-eslint.io/packages/parser) - A TypeScript parser that produces output compatible with ESLint.

## Formatters

<!-- ignore is to keep "github" lower-case -->

<!--lint ignore awesome-spell-check-->

* [mo](https://github.com/fengzilong/eslint-formatter-mo) ⭐ 136 | 🐛 0 | 🌐 JavaScript | 📅 2025-11-14 - Good-lookin' ESLint formatter and also for delightful reading experience.
* [github](https://github.com/hipstersmoothie/eslint-formatter-github) ⭐ 109 | 🐛 15 | 🌐 TypeScript | 📅 2025-08-10 - See ESLint errors and warnings directly in pull requests.
* [git-log](https://github.com/JamieMason/eslint-formatter-git-log) ⭐ 42 | 🐛 0 | 🌐 TypeScript | 📅 2022-05-02 - ESLint Formatter featuring Git Author, Date, and Hash.
* [html](https://github.com/shuoshubao/eslint-formatter-html) ⭐ 39 | 🐛 1 | 🌐 JavaScript | 📅 2025-04-03 - A enhanced ESLint formatter.
* [summary-chart](https://github.com/davidjbradshaw/eslint-formatter-summary-chart) ⭐ 13 | 🐛 1 | 🌐 JavaScript | 📅 2024-06-18 - Format ESLint output into a bar chart.
* [badger](https://github.com/brettz9/eslint-formatter-badger) ⭐ 7 | 🐛 0 | 🌐 JavaScript | 📅 2025-08-23 - Make SVG-based badges summarizing ESLint results (e.g., for use on a README).
* [gitlab](https://gitlab.com/remcohaszing/eslint-formatter-gitlab) - Output ESLint results in the GitLab code quality results.
* [SARIF](https://www.npmjs.com/package/@microsoft/eslint-formatter-sarif) - Generate a results in a SARIF format so it can be imported into tools like GitHub Advanced Security.

## Globals

* [confusing-browser-globals](https://github.com/facebook/create-react-app/tree/main/packages/confusing-browser-globals) ⭐ 103,931 | 🐛 2,367 | 🌐 JavaScript | 📅 2025-02-15 - A curated list of browser globals that commonly cause confusion and are not recommended to use without an explicit window. qualifier.
* [ES and browser globals](https://github.com/sindresorhus/globals) ⭐ 557 | 🐛 8 | 🌐 JavaScript | 📅 2026-02-01 (originally from ESLint)
* [TestCafe globals](https://github.com/miherlosev/eslint-plugin-testcafe) ⭐ 15 | 🐛 3 | 🌐 JavaScript | 📅 2020-05-12 - `fixture` & `test` globals for TestCafe.
* [chai globals](https://github.com/t-huth/eslint-plugin-chai-assert-bdd) ⭐ 2 | 🐛 0 | 🌐 JavaScript | 📅 2017-09-14

## Tools

* [eslint-nibble](https://github.com/IanVS/eslint-nibble) ⭐ 883 | 🐛 13 | 🌐 JavaScript | 📅 2025-11-21 - Ease into ESLint, by fixing one rule at a time.
* [esprint](https://github.com/pinterest/esprint) ⭐ 656 | 🐛 21 | 🌐 JavaScript | 📅 2025-06-13 - Run ESLint across multiple threads.
* [eslint-interactive](https://github.com/mizdra/eslint-interactive) ⭐ 444 | 🐛 13 | 🌐 TypeScript | 📅 2025-10-21 - The CLI tool to fix huge number of ESLint errors.
* [generator-eslint](https://github.com/eslint/generator-eslint) ⭐ 244 | 🐛 2 | 🌐 JavaScript | 📅 2026-02-07 - Generate ESLint
  plugin and rules with [Yeoman](http://yeoman.io/).
* [eslint-find-rules](https://github.com/sarbbottam/eslint-find-rules) ⭐ 213 | 🐛 14 | 🌐 JavaScript | 📅 2025-01-20 - Find built-in ESLint rules you don't have in your custom config.
* [eslint-watch](https://github.com/rizowski/eslint-watch) ⭐ 199 | 🐛 14 | 🌐 JavaScript | 📅 2023-03-04 - Run ESLint with watch mode.
* [eslint-remote-tester](https://github.com/AriPerkkio/eslint-remote-tester) ⭐ 130 | 🐛 5 | 🌐 TypeScript | 📅 2026-02-16 - CLI tool for testing given ESlint rules against multiple repositories at once.
* [eslint-rule-documentation](https://github.com/jfmengels/eslint-rule-documentation) ⭐ 31 | 🐛 3 | 🌐 JavaScript | 📅 2023-03-11 - Find the url for the documentation of an ESLint rule.
* [eslint-index](https://github.com/wagerfield/eslint-index) ⭐ 21 | 🐛 8 | 🌐 JavaScript | 📅 2021-08-10 - CLI for finding and managing rules in ESLint config files.
* [eslint-dashboard](https://github.com/fengzilong/eslint-dashboard) ⭐ 20 | 🐛 0 | 🌐 JavaScript | 📅 2021-09-17 - Interactive ESLint workflow that lives in your terminal.
* [codacy-eslint](https://github.com/codacy/codacy-eslint) ⭐ 16 | 🐛 44 | 🌐 TypeScript | 📅 2026-02-14 - Docker used at [Codacy](https://www.codacy.com) to run ESLint.
* [eslint-multiplexer](https://github.com/pimlie/eslint-multiplexer) ⭐ 7 | 🐛 11 | 🌐 JavaScript | 📅 2026-02-12 - Multiplex eslint results and merge results for common files.
* [editor-info](https://github.com/fisker/editor-info) ⭐ 7 | 🐛 15 | 🌐 JavaScript | 📅 2025-03-09 - Detect whether one is within an editor/IDE and which type, allowing one to tweak ESLint configuration accordingly.
* [es-file-traverse](https://github.com/brettz9/es-file-traverse) ⭐ 2 | 🐛 1 | 🌐 JavaScript | 📅 2025-11-22 - Obtain a list of only those files which are in use based on imports and/or requires from an entry file or files; list passable to ESLint. Intended esp. for linting 3rd party dependencies.
* [eslint-disable-autofix](https://github.com/MorevM/eslint-disable-autofix/) ⭐ 2 | 🐛 3 | 🌐 TypeScript | 📅 2026-02-14 - Utility to disable autofix for specific ESLint rules.
* [eslint-plugin-rule-adoption](https://github.com/Jugbot/eslint-plugin-rule-adoption) ⭐ 1 | 🐛 0 | 🌐 JavaScript | 📅 2025-04-25 - An eslint plugin for incremental rule adoption, when `--fix` and codemods don't cut it.

## Developing for ESLint

* [eslint-doc-generator](https://github.com/bmish/eslint-doc-generator) ⭐ 106 | 🐛 42 | 🌐 TypeScript | 📅 2026-02-15 - Generate documentation for your ESLint plugin including a rules table for your readme and header for your rule docs.
* [eslint-docgen](https://github.com/wikimedia/eslint-docgen) ⭐ 11 | 🐛 13 | 🌐 JavaScript | 📅 2024-05-16 - Automatically generate ESLint plugin documentation from rule metadata and test cases.

## Tutorials

* [Creating an ESLint Plugin](https://medium.com/tumblbug-engineering/creating-an-eslint-plugin-87f1cb42767f) - Article walking through the creation of an ESLint rule and plugin.
* [Lint Like It's 2015](https://medium.com/@dan_abramov/lint-like-it-s-2015-6987d44c5b48#.5p3yk0b03) - Article walking through the benefits of using ESLint.
* [Writing a rule to spot undeclared props hiding in plain sight](http://blog.cowchimp.com/writing-a-custom-eslint-rule-to-spot-undeclared-props/) - Article about creating rules that require scope analysis.
* [Dear Old ESLint](https://adropincalm.com/blog/dear-old-eslint/) - Quick intro article on ESLint.

## Installation and Setup

* [Lintier](https://github.com/josh-stillman/lintier) ⭐ 34 | 🐛 1 | 🌐 TypeScript | 📅 2026-02-02 - CLI to quickly scaffold an ESLint & Prettier setup in a TypeScript project.
