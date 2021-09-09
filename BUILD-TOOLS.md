## FlowBite Documentation

These are the source files for the Flowbite Tailwind CSS components library.

### Getting started

1. Make sure you have Node and NPM installed
2. Run `yarn install`
3. Run `yarn start` to start developing

## Building the docs website

Run `yarn build` to build the static HTML files that will be uploaded to FlowBite. The static HTML files can be found in the `_gh_pages/` folder.

## Building for NPM registry

** Important! ** Test this with another package name because you can't delete a version! (eg. @themesberg/flowbite-test)

Run `npm run build:npm` and then `npm publish` to release a new version. Make sure you also change the version.