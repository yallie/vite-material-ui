# React + TypeScript + MUI v5

A Vite template for React, TypeScript and the latest major version of MUI.

## Highlights

- React w/ TypeScript
- Takes 8-10 seconds to build prod bundle at 198kb
- v5 ( latest ) version of Material UI, `@mui/material`
- Enables the `@emotion/babel-plugin` to work with MUI (see [features](https://github.com/emotion-js/emotion/tree/main/packages/babel-plugin#features))
- Dark mode toggle
- Aliased imports
- Vitest integration

## Demo

<img src='./screen-shots/demo.png' />

## Getting Started

- Clone the repo, `git clone https://github.com/yallie/vite-vitest-ts-mui5`, or use the "Use this template" button at the top of this page.
- Or copy via `degit https://github.com/yallie/vite-vitest-ts-mui5` and init new git repository via `git init`
- Install dependencies using `yarn`
- Start the server with `yarn dev`

## MUI

To learn more about the newest ways to use MUI, checkout [the docs](https://mui.com/getting-started/usage/).

### What's Included

- Custom theming
- Using that theme from within a `styled` component
- Dark mode toggle with React Context
- Aliased imports with `@/` mapping to the `src/`
- Rollup bundle analyzer
  - To use, run `yarn analyze`
