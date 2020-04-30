# IonicSsrErrors

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 9.1.1.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Prerender errors

Run `ng run prerender` to generate the prerender. You can see the following error by the end:


Issue [21138](https://github.com/ionic-team/ionic/issues/21138)

```

Prerendering 1 route(s) to <path-to-project>/dist/ionic-ssr-errors/browser
TypeError: Cannot read property 'width' of undefined
    at Device (<path-to-project>/dist/ionic-ssr-errors/server/main.js:1:3026748)
    at hydrateAppClosure (<path-to-project>/dist/ionic-ssr-errors/server/main.js:1:3028625)
    at hydrateFactory (<path-to-project>/dist/ionic-ssr-errors/server/main.js:1:3107878)
    at render (<path-to-project>/dist/ionic-ssr-errors/server/main.js:1:3128770)
    at <path-to-project>/dist/ionic-ssr-errors/server/main.js:1:3133854
    at new ZoneAwarePromise (<path-to-project>/dist/ionic-ssr-errors/server/main.js:1:3206236)
    at hydrateDocument (<path-to-project>/dist/ionic-ssr-errors/server/main.js:1:3133500)
    at <path-to-project>/dist/ionic-ssr-errors/server/main.js:1:1287139
    at <path-to-project>/dist/ionic-ssr-errors/server/main.js:1:1212014
    at ZoneDelegate.invoke (<path-to-project>/dist/ionic-ssr-errors/server/main.js:1:3194265)
CREATE <path-to-project>/dist/ionic-ssr-errors/browser/index.html (3471 bytes)
```

Issue [21063](https://github.com/ionic-team/ionic/issues/21063) - CLOSED

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
