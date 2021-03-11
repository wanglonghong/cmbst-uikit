# Combust UIkit

Combust UIkit is a set of React components and hooks used to build pages on Combust's apps. It also contains a theme file for dark and light mode.

## Install

`yarn add @zealous4467/cmbstswapuikit`

## Setup

### Theme

Before using Combust UIkit, you need to provide the theme file to styled-component.

```
import { ThemeProvider } from 'styled-components'
import { light, dark } from '@zealous4467/cmbstswapuikit'
...
<ThemeProvider theme={isDark}>...</ThemeProvider>
```

### Reset

A reset CSS is available as a global styled component.

```
import { ResetCSS } from '@zealous4467/cmbstswapuikit'
...
<ResetCSS />
```

### Types

This project is built with Typescript and export all the relevant types.



