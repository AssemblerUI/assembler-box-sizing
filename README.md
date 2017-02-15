# Assembler Box Sizing

[![Greenkeeper badge](https://badges.greenkeeper.io/AssemblerUI/assembler-box-sizing.svg)](https://greenkeeper.io/)

A box sizing component built for the [Assembler framework](https://github.com/AssemblerUI/assembler).

## Table of contents

- [Quick start](#quick-start)
- [Bugs and feature requests](#bugs-and-feature-requests)
- [Documentation](#documentation)
- [Contributing](#contributing)
- [Copyright](#copyright)

## Quick Start

Five quick start options are available:

- [Download the latest release](https://github.com/AssemblerUI/assembler-box-sizing/archive/v0.2.2.zip).
- Clone the repo: `git clone https://github.com/AssemblerUI/assembler-box-sizing.git`.
- Install with [Bower](http://bower.io): `bower install assembler-box-sizing`.
- Install with [component(1)](https://github.com/componentjs/component): `component install assembler-box-sizing`.
- Install with [npm](https://www.npmjs.org): `npm install assembler-box-sizing`.

### What's included

Within the download you'll find the following directories and files, logically
grouping common assets and providing both compiled and minified variations.
You'll see something like this:

```
assembler-box-sizing/
├── dist/
│   ├── assembler-box-sizing.css
│   ├── assembler-box-sizing.css.map
│   ├── assembler-box-sizing.min.css
│   └── assembler-box-sizing.min.css.map
└── src/
    ├── assembler-box-sizing.scss
    ├── assembler-box-sizing.scss
    └── sass/
        └── _box-sizing.scss
```

Provided is the compiled CSS (`dist/assembler-box-sizing.*`), and the source files
written in SCSS (`src/assembler-box-sizing.*.scss`). CSS [source maps](https://developers.google.com/chrome-developer-tools/docs/css-preprocessors)
(`assembler-box-sizing.*.map`) are available for use with certain browsers' developer
tools.

### Picking a Version

If you want to:

- consume the library as-is, with no modifications, then include the CSS files
  in the `dist/` directory
- include the SCSS files as part of your build process, with no modifications,
  then include the SCSS files at the root of the `src/` directory choosing
  either the flexbox or fluid version.
- modify, then include the `src/sass/_box-sizing.scss` in your project as an 
  `@import`, then call the mixin.

## Bugs and feature requests

Have a bug or a feature request? Please first read the
[Contributing documentation](https://github.com/AssemblerUI/assembler-box-sizing/blob/master/CONTRIBUTING.md)
and search for existing and closed issues. If your problem or idea is not
addressed yet, [please open a new issue](https://github.com/AssemblerUI/assembler-box-sizing/issues/new).

## Contributing

Contribution is a perfect way to help advance the project.  Please read the
[contributing guidelines](https://github.com/AssemblerUI/assembler-box-sizing/blob/master/CONTRIBUTING.md).
before getting started.

Editor preferences are available in the [editor config](https://github.com/AssemblerUI/assembler-box-sizing/blob/master/.editorconfig)
for use in common text editors. Read more and download plugins at <http://editorconfig.org>.

### Getting Started

1. Clone the repo: `git clone https://github.com/AssemblerUI/assembler-box-sizing.git`.
2. `cd assembler-box-sizing`
4. Install grunt build dependencies: `npm install`
5. Start the build process: `grunt dev`

## Copyright

:copyright: 2015. See the [LICENSE](https://github.com/AssemblerUI/assembler-box-sizing/blob/master/LICENSE.md).
Maintained by [@chrisopedia](https://github.com/chrisopedia).
