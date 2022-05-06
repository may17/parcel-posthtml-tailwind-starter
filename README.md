# Server Side generator with parcel, posthtml and tailwind

This repository is a starter kit to create simple static websites with parcel bundler, posthtml plugins and tailwind.

## Getting started

- Install with `npm i`
- Start dev server with `npm run dev`

## Production build

Run `npm run build`. You will find the final artifact in a dist folder inside the project.

## Create components

To avoid to repeat yourself to often the `posthtml-modules` plugin is preconfigured. Components are alocated to the `src/_components` directory.

### src/\_components/myTeaser.html

```html
<h2>{{ Title }}</h2>
<div><content></content></div>
```

### myTeaser component usage

```html
<component use="/myTeaser.html" title="My Headline">
  Some text goes here
</component>
```
