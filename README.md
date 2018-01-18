# QIO Demo

## Install Dependencies

```bash
npm install
```

## Running Application

```bash
npm start
```

## Browser Compatiblity Issues

This demo currently works file in Chrome, FireFox, Edge, and Safari. It is not working in IE. However, the key to making it work in IE seems to be with getting the `custom-elements-es5-adapter.js` polyfill to work correctly with this build. More info about this can be found at https://www.polymer-project.org/2.0/docs/polyfills.

## UX Design

- Should not convey what something represents with only color, a symbol should be used as well
- Add tooltips to better describe what elements mean
    * I would probably use a better looking tooltip than I have (i.e. paper-tooltip)
- aria labels for upload time, warning counts, and error counts to describe what they represent for screen readers

## UI Design

- Group together warnings and errors with the appropriate file info
- Place buttons at the bottom of the form
- Add box shaddow around box to make it stand out a little better

### TEST AGAIN

One more test
Test again
