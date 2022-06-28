# 🥞 Fitswap UIkit

[![Version](https://img.shields.io/npm/v/@fitswap/uikit)](https://www.npmjs.com/package/@fitswap/uikit) [![Size](https://img.shields.io/bundlephobia/min/@fitswap/uikit)](https://www.npmjs.com/package/@fitswap/uikit)

Fitswap UIkit is a set of React components and hooks used to build pages on Fitswap's apps. It also contains a theme file for dark and light mode.

## Install

`yarn add @fitswap/uikit`

## Setup

### Theme

Before using Fitswap UIkit, you need to provide the theme file to styled-component.

```
import { ThemeProvider } from 'styled-components'
import { light, dark } from '@fitswap/uikit'
...
<ThemeProvider theme={isDark}>...</ThemeProvider>
```

### Reset

A reset CSS is available as a global styled component.

```
import { ResetCSS } from '@fitswap/uikit'
...
<ResetCSS />
```
