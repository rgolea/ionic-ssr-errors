# IonicSsrErrors

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 9.1.1.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Prerender errors

Run `ng run prerender` to generate the prerender. You can see the following error by the end:

```
Prerendering 1 route(s) to <path-to-project>/ionic-ssr-errors/dist/ionic-ssr-errors/browser
CREATE <path-to-project>/ionic-ssr-errors/dist/ionic-ssr-errors/browser/index.html (113368 bytes)
unhandledRejection ReferenceError: MutationObserver is not defined
    at <path-to-project>/ionic-ssr-errors/dist/ionic-ssr-errors/server/main.js:1:2789887
    at constructor.connectedCallback (<path-to-project>/ionic-ssr-errors/dist/ionic-ssr-errors/server/main.js:1:2790048)
    at safeCall (<path-to-project>/ionic-ssr-errors/dist/ionic-ssr-errors/server/main.js:1:2058830)
    at fireConnectedCallback (<path-to-project>/ionic-ssr-errors/dist/ionic-ssr-errors/server/main.js:1:2065851)
    at initializeComponent (<path-to-project>/ionic-ssr-errors/dist/ionic-ssr-errors/server/main.js:1:2065215)
    at connectedCallback (<path-to-project>/ionic-ssr-errors/dist/ionic-ssr-errors/server/main.js:1:2067599)
    at hydrateComponent (<path-to-project>/ionic-ssr-errors/dist/ionic-ssr-errors/server/main.js:1:2073412)
    at connectElement (<path-to-project>/ionic-ssr-errors/dist/ionic-ssr-errors/server/main.js:1:2073723)
    at Array.map (<anonymous>)
    at waitLoop (<path-to-project>/ionic-ssr-errors/dist/ionic-ssr-errors/server/main.js:1:2074636)
```
