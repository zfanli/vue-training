# vue-training

## Project setup

```
yarn install
```

### Compiles and hot-reloads for development

```
yarn run serve
```

### Compiles and minifies for production

```
yarn run build
```

### Run your tests

```
yarn run test
```

### Lints and fixes files

```
yarn run lint
```

## About code styles

> Formatter: prettier. The default formatter integrated by Vetur, a plug-in of VSCode.

| Key           | Value   | Description                       |
| ------------- | ------- | --------------------------------- |
| singleQuote   | `true`  | Use single quotes                 |
| trailingComma | `es5`   | Tailing commas where valid in ES5 |
| semi          | `false` | No semicolons generally           |

## Why this repo?

For reasons list below, I created this repo to do some practices for be familiar with Vue.js.

- interested in Vue.js
- try to build blog base on VuePress and was not familiar with Vue.js
- an alternative choice to React.js

## So do what?

As usual, build a blog site with Vue.js.

It'll be a pretty lot of works.

Let's begin from the simplest step, just a list and a article viewer.

## Todo

- [x] homepage for show post list
- [x] article page, parse and display markdown posts
- [ ] article comment support, with gitalk
- [ ] homepage pagination
- [ ] tags page
- [ ] theme settings, for change color themes

## Dependencies

- `vue` - base
- `vue-router` - router
- `vuex` - state management
- `markdown-it` - parse markdown into html
- `prismjs` - syntax highlight
- `github-markdown-css` - styling like github
