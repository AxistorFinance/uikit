# 🥞 Axistor UIkit

[![Version](https://img.shields.io/npm/v/@axistor/uikit)](https://www.npmjs.com/package/@axistor/uikit) [![Size](https://img.shields.io/bundlephobia/min/@axistor/uikit)](https://www.npmjs.com/package/@axistor/uikit)

Axistor UIkit is a set of React components and hooks used to build pages on Axistor's apps. It also contains a theme file for dark and light mode.

## Install

`yarn add @axistor/uikit`

## Setup

### Theme

Before using Axistor UIkit, you need to provide the theme file to styled-component.

```
import { ThemeProvider } from 'styled-components'
import { light, dark } from '@axistor/uikit'
...
<ThemeProvider theme={isDark}>...</ThemeProvider>
```

### Reset

A reset CSS is available as a global styled component.

```
import { ResetCSS } from '@axistor/uikit'
...
<ResetCSS />
```
