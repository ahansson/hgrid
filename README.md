# hgrid-css

### ⚠️ WORK IN PROGRESS

_Documentation may be incomplete or inaccurate_

### **A Lightweight and Practical CSS Utility Kit.**

### Zero Config. Flat Learning Curve

Hgrid is a starting point intended to make HTML work out of the box, with very little effort. Ideal for fast prototyping without having to deal with browser quirks and unstyled elements. It's not a UI framework.

## Documentation

Website: [https://hgrid.io](https://hgrid.io)

## Versions

**0.3.0-alpha**. Default viewport [renamed](https://github.com/ahansson/hgrid-css/commit/0974b24299e8877eb34539d7934979f4955d276d) to 'laptop'. Buggy custom link underline [replaced](https://github.com/ahansson/hgrid-css/commit/81a12bdc87a75490535a3f8d557274772f36ae0e) with a better version of the default underline. [Remove](https://github.com/ahansson/hgrid-css/commit/4dfa56c664c306bb579f5cfd4b2b18c7420dea50) reset style for images that gave unwanted side effects. Changes in [width and height](https://github.com/ahansson/hgrid-css/commit/2eba0449584ec5e038087a857ccdbdea2de9cb9a) classes. Bugfixes.

* Breakpoint `$desktop` renamed to `$laptop`
* Breakpoint `$desktop-large` renamed to `$desktop`
* Breakpoint `$desktop-xl` renamed to `$desktop-large`
* `.full-width` replaced by `.width-100pct`.
* `.full-height`/`.full-height-vh` replaced by `.height-100pct`/`.height-100vh`.
* `.full-width-vw`, `.min-width-0`, `min-height-0` and `min-width-100` are gone.
* `.max-width-{ x }pct` added.
* width and height `auto` added
* `.pointer-events-none` and `-all` added
* [Margin auto](https://github.com/ahansson/hgrid-css/commit/4a1b0b08b46ade5f1fdc57cdda1a04f4231cbb41) added
<br><br>

**0.2.0-alpha**. Form input and focus outline styling. Responsive overrides for flex items. Theme colors. Media embed.
<br><br>

**0.1.0-alpha**. New version forked from a deprecated version (1.2.0). There are extensive changes, so let's start fresh.
<br><br>

## How to install

**As a packet:**

```bash
npm install hgrid-css --save-dev
```

```
yarn add hgrid-css --dev
```

**From local file or CDN:**

```html
<head>
  <link rel="stylesheet" href="/path/to/hgrid-css/hgrid.min.css">
  <!-- more css below -->
</head>
```
**@import into your stylesheet:**
```css
/* From node_modules */
@import './../etc./node_modules/hgrid-css/dist/hgrid.min.css';
```
```css
/* From CDN */
@import 'https://cdn.domain.com/dist/hgrid.min.css';
```

For detailed information on how to integrate **hgrid** in your frontend framework as `scss`, please refer to [the documentation](https://hgrid.io/documentation/integrate/).

## Local development

_Requires nodejs with npm installed on your system._

Start compiling `.scss` files to `.css` with the terminal command `npm run watch` from the root of the hgrid folder. Any changes you make to files in the `/sass` folder will result in css and map files being updated in the `/dist` folder.

To produce the minified **hgrid** file, use `npm run build`. It uses Autoprefixer to add some backwards compatibility before minifying the result as `hgrid.min.css`.

As always, see [hgrid.io](https://hgrid.io) for details on how to integrate **hgrid** as Sass or plain CSS in

## Author

Atle Hansson @ https://kubo.no