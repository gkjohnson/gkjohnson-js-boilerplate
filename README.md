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

[Parcel.js](https://parceljs.org/)

A painless, nearly config-less build platform that can build staticly served html pages out of the box and supports a variety of transpiled languages and dev servers.

```sh
# Build a project and output urls with a relative path
parcel-bundler build <file.ext> --public-url ./
```

### Tests

TODO document test procedure

### Code-Style

#### ESLint

TODO document `eslintrc`

#### HTMLHint

TODO document `htmlhintrc`

#### StyleLint

TODO get familiar, document

#### Auto-format

TODO figure out how to auto format

### Editor

VSCode

Sublime

#### Plugins

TODO document plugins

### Helper Packages

TODO document helper npm packages, provide basic `package.json`
