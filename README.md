# PlaywrightTest

This is a project for playing with [Playwright](https://playwright.dev/).

I am using it mainly to allow me to develop for webkit browsers (e.g. safari) by running the playwright cli with webkit set as the browser.

This can be done by running `npm install` and then running:

```bash
npm run webkit
```

This is effectively just an alias for the following playwright cli command:

```bash
npx playwright open google.com -b webkit
```

There are scripts for firefox and chromium too:

```bash
npm run firefox
npm run chromium
```
