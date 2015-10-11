A test runner for tape that utilizes babel in order to run test suites that include ESNext/Harmony features.

## install

Install globally or locally (for npm scripts):

```sh
npm install tape-babel-css-modules
```

## usage

Just run `tape-babel-css-modules` with the files to test (just like tape's bundled runner).  Store configuration in a `.babelrc` file.

```sh
tape-babel-css-modules my-es-next-test.js

tape-babel-css-modules lib/**/__tests__/*-test.js # or glob patterns
```

## licence

MIT
