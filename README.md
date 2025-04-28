# New UI Foundations

#### What is New UI?
New UI is a modern, semantic UI framework for building beautiful, accessible websites and apps. It gives you everything you need—foundations, components, theming, and smart utilities—designed to grow with you, from first launch to millions of users. Thoughtfully made for makers, small teams, and anyone who cares about great design.

#### Install
To set up the project, open your terminal and run the following command:

```
npm i -D @new-ui/foundations
```

<strong>Note:</strong> This command installs all New UI foundation packages, which include reset, colors, effects, spacings, and typography. If you need to install only specific packages, refer to the foundations documentation for instructions.

#### Import
Import the New UI foundations by adding the following line at the top of your SCSS file:

```scss
@use '@new-ui/foundations';     // Use `@import` for CSS
```

#### Set the theme
Set the theme by adding the `data-new-ui-theme` attribute to your HTML wrapper element, for example:

```html
<html data-new-ui-theme="light">
```

|---
| Available themes | Value
|-|:-|:-
| Light (Default) | `light`
| Light warm | `light--warm`
| Light cold | `light--cold`
| Dark  (Default) | `dark`
| Dark warm | `dark--warm`
| Dark cold | `dark--cold`
|---


#### Usage guide
- All classes associated with the New UI are prefixed with a global namespace followed by a hyphen: `nu-`
- In addition to a global namespace, we added prefixes to each class to make it more apparent what job that class is doing using BEM syntax.
    - `c-` for UI components.
    - `l-` for layout-related styles.
    - `u-` for utilities.
    - `is-` and `has-` for state-based classes.
    - `js-` for targeting JavaScript-specific functionality.