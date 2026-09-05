# Droner

[![Droner — drone-news landing page](public/opengraph-1280x640.jpg)](https://droner.jstsamuel.dev)

[![Netlify Status](https://api.netlify.com/api/v1/badges/dbd63aa5-90b7-400d-af9d-65933675aae7/deploy-status)](https://app.netlify.com/sites/droner/deploys) [![LinkedIn Project](https://img.shields.io/badge/LinkedIn-Project%20Card-0A66C2)](https://www.linkedin.com/in/jstsamuel/details/projects/#:~:text=Droner)   

[Course - ITCSS](https://www.pluralsight.com/courses/inverted-triangle-css-intro)   

- [Specificity Calculator](https://specificity.keegan.st/)

## ITCSS

- settings (variables): variables, breakpoints
- tools: mixins, helper functions
---- css generation start here ----
- generic: reset.css, normalize.css, third-party (less/low specifity, no classes)
- elements: base layer, bare html elements, plain unclassed elements
---- class generation start here ----
- objects: reusable design patterns, layout, grid, media object
  - font awesome (in a non rigid way)
- components: specific UI components, buttons, cards, navbars
- trumps: utility classes, helpers, overrides, elements with high specificity, ID selectors and !important

## GitHub Pages deployment

```sh
  build:  npm run prod && git add public/ src/ && git commit -m "feat: demos"
  deploy: git subtree push --prefix public origin production 
```

## Netlify deploy

- Add and commit changes
- Push to master
