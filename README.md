Example Monorepo
================

This is an example repository (considered a [monorepo](https://en.wikipedia.org/wiki/Monorepo)) containing multiple [Composer](https://getcomposer.org/) packages in sub-directories.

## Codebase 

Directory structure of an application:
```
📂/
┣ 📂app/
┃ ┣ 📂modules/
┃ ┃ ┗ 📂Example/
┃ ┃   ┣ 📂PrimaryFeature/
┃ ┃   ┃ ┗ 📜composer.json
┃ ┃   ┗ 📂SecondaryFeature/
┃ ┃     ┗ 📜composer.json
┃ ┗ 📂themes/
┃   ┣ 📂dark/
┃   ┃ ┗ 📜composer.json
┃   ┗ 📂light/
┃     ┗ 📜composer.json
┗ 📜composer.json
```

Here, modules are segregated by vendors whereas themes are global.
Namespace `Example` corresponds to a fictitious company that develops the code.
Modules of other vendors would reside in sibling directories.

**Package locations:**
- `app/modules/*/*`
- `app/themes/*`

## Usage

Publish package directories to [enpack.io](https://enpack.io/) for distribution via Composer.
See the [docs](https://docs.enpack.io/) for usage instructions.

## License

Copyright © Upscale Software. All rights reserved.

Licensed under the [Apache License, Version 2.0](https://github.com/enpack-io/example-monorepo/blob/master/LICENSE.txt).