# gkjohnson-js-boilerplate
My set of minimal-config dev libraries for new Javascript projects

## Principles
- Support "download, install, and go" as much as possible to enable the project to be as easy to start and understand as possible.
- Bundling and specialized platform configuration (docker, environment variables) should be minimized or made optional as much as possible support a variety of dev strategies. Projects should not require global command line or special path setup. It should download what it needs.
- Support as many config-less platforms as possible to keep supporting a variety of dev strategies as painless as possible and starting a new project as quick as possible.
- Maintain consistent code style that enables broad read-ability and prevents mistakes.
- Make it easy to build to a static GitHub page to publish examples.

## Platforms

### Bundling

#### [Parcel.js](https://parceljs.org/)

A painless, nearly config-less build platform that can build staticly served html pages out of the box and supports a variety of transpiled languages and dev servers.

```sh
# Build a project and output urls with a relative path
parcel build <file.ext> --public-url ./ --no-cache --no-source-maps
```

### Testing

#### [Puppeteer](https://github.com/GoogleChrome/puppeteer)

For client side tests and html that can only be tested in the browser.

#### [Jest](https://jestjs.io/)

General javascript testing and assertion framework.

#### [Istanbul](https://istanbul.js.org/)

For code coverage awareness.

The `puppeteer-to-istanbul` package can help visualize the puppeteer code coverage.

### Code-Style

#### [ESLint](https://eslint.org/)

[.eslintrc](.eslintrc)

Requires a `eslint` and `eslint-plugin-html` packages to be installed to work.

#### [HTMLHint](https://github.com/yaniswang/HTMLHint)

[.htmlhintrc](.htmlhintrc)

Requires `htmlhint` packages to be installed.

#### [StyleLint](https://stylelint.io/)

[.stylelintrc](.stylelintrc)

TODO get familiar, document

#### [EditorConfig](https://editorconfig.org/)

[.editorconfig](.editorconfig)

Requires editor plugin sometimes

#### VSCode User Settings

[.vscodesettings](.vscodesettings)

Settings so ESLint works on HTML files.

### Continuous Integration

#### [LGTM](https://lgtm.com)

For code cleanliness and sanity.

#### [Travis-CI](https://travis-ci.org/)

For running tests against master and PRs.

#### To Consider

https://david-dm.org/

https://codecov.io/

### Editor

VSCode

#### Plugins

ESLint for VSCode

HTMLHint (for VSCode)

EditorConfig for VSCode

### Helper Packages

TODO document helper npm packages, provide basic `package.json`
