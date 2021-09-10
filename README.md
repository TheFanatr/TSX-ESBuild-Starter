# TSX-ESBuild-Starter

Starter template for React and Typescript, using NPM. Based on https://github.com/belaczek/react-esbuild-starter

It provides minimal yet 🔥 blazing fast ™ development boilerplate for rapid React prototyping.

- `npm run dev` Starts typescript typechecking and esbuild in watch mode, and serves web page at localhost:5000.
- `npm run start` Runs build, and opens the outputted index.html with the default browser.
- `npm run build` Builds production bundle for browser, outputs bundle to dist/bundle.js with source map.
- `npm clean` Clean up assets produced by esbuild.

All code bundling and transpilation is handled by ESBuild. Its configuration is kept inside `bundler.mjs`. Follow [ESBuild docs](https://esbuild.github.io/getting-started/) to see all supported options. The code for the development test server is also available in `test-server.mjs`.

### Caveats

- No output file hashing
- No test runner
