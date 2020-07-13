# Nyxo UI library

[![Live Demo](https://img.shields.io/badge/netlify-live_demo-1e9498.svg)](https://ui.nyxo.app/)

## Credits

This repo was bootstrapped with [gatsby-typescript-storybook-starter](https://gatsby-typescript-storybook-starter.netlify.com)

## Features

- [Gatsby MDX](https://github.com/ChristopherBiscardi/gatsby-mdx) for JSX in Markdown loading, parsing, and rendering of pages
- [Storybook](https://storybook.js.org/) for isolated component development
- [styled-components](https://www.styled-components.com/) for CSS-in-JS
- [ESLint](https://eslint.org/) with [Airbnb's config](https://www.npmjs.com/package/eslint-config-airbnb)
- [Prettier](https://prettier.io/) integrated into ESLint
- [Typescript]() integrations and validation

## Development

[`Node.js`](https://nodejs.org/) v8.0.0 or above is required and using [`Yarn`](https://yarnpkg.com) is recommended.

```bash
# install dependencies
yarn

# ...or with npm
npm install

# serve with hot reload for development (localhost:8000)
yarn develop

# serve storybook with hot reload for development (localhost:9000)
yarn storybook

# lint project
yarn lint

# format project source
yarn format

# run tests
yarn test

# build for production
yarn build

# build static storybook (outputs to `public/docs` folder)
yarn storybook:build

# serve locally (after building)
yarn serve

# clean the local build
yarn clean
```

## License

This project is licensed under [MIT](https://github.com/South-Paw/awesome-gatsby-starter/blob/master/LICENSE)
