# prism-vizhub-theme
A theme for Prism.js with [VizHub](https://vizhub.com/) code colors.

![image](https://user-images.githubusercontent.com/68416/98449847-72d44880-2105-11eb-88ee-c02e0a18eb14.png)

## Usage

This repository contains a single [`prism-theme.css`](prism-theme.css) stylesheet and a license. It is **not** an npm library or a source for the current VizHub app's complete design system.

Copy the CSS file into a page that already loads [Prism.js](https://prismjs.com/) and include it after Prism's base styles, adapting the URL to where you host the file:

```html
<link rel="stylesheet" href="/styles/prism-theme.css">
```

The path above is an **example consumer path**, not a hosted asset URL provided by this repository. Adjust it to the consuming application. Review token colors and contrast visually for your syntax-highlighted themes. There is no `package.json`, build script, or automated test suite in this repository.

