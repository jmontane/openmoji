OpenMoji
========

<img width="1157" alt="openmoji-github" src="https://user-images.githubusercontent.com/480224/39040408-7d21c018-4487-11e8-9aa9-c8ea64fc07f6.png">

Open-source emojis for designers, developers and everyone else! OpenMoji is an open-source project of the HfG Schwäbisch Gmünd by Benedikt Groß, Daniel Utz, 50+ students and external contributors.

👉 [OpenMoji.org/](http://openmoji.org/)

Interact, create, save, and share your work! 🌈`#openmoji`

This GitHub repository contains all of the source files and exported png/svg files of the OpenMoji project.

⚠️ Please note that the master branch is in active development, so if you're looking for stable production version please use one of the releases.


## Table of Contents

- [Styleguide](http://openmoji.org/styleguide) our beloved styleguide.
- [FAQ](FAQ.md) Check if your question has already been answered
- [Contributing](CONTRIBUTING.md) Pull Requests are welcome!
- [Developer Setup](CONTRIBUTING.md#developer-setup) how to setup node.js.
- [Font](font) infos on the OpenMoji-Color and OpenMoji-Black fonts.
- [Team](http://openmoji.org/about/#team) list of all authors and contributors.
- [Acknowledgements](http://openmoji.org/about/#acknowledgement) Thanks!


## Downloads & Distribution Channels
You can download, use and "consume" OpenMoji in various ways:

- [SVG](https://github.com/hfg-gmuend/openmoji/releases/latest): Color & Black (production ready)
- [Fonts](https://github.com/hfg-gmuend/openmoji/releases/latest): Color & Black (experimental)
- [PNG 618x618](https://github.com/hfg-gmuend/openmoji/releases/latest): Color & Black (production ready)
- [PNG 72x72](https://github.com/hfg-gmuend/openmoji/releases/latest): Color & Black (production ready)
- [OpenMoji app](https://itunes.apple.com/us/app/openmoji/id1462636288): for iOS with emoji picker
- [OpenMoji Stickers](https://itunes.apple.com/us/app/openmoji/id1462636288): for iOS Messages app
- [OpenMoji Github](https://github.com/hfg-gmuend/openmoji/): `git clone --dept 1 https://github.com/hfg-gmuend/openmoji.git` The OpenMoji repo is big! It is recommended to clone it without the entire history, note the --dept flag.
- [OpenMoji NPM Package](https://www.npmjs.com/package/openmoji): `npm install openmoji`
- [OpenMoji Jekyll Plugin](https://github.com/azadeh-afzar/OpenMoji-Jekyll-Plugin): `gem 'jekyll-openmoji'`


## Anatomy OpenMoji Repository

`black/` and `color/` Contains all exported .png and .svg files.

`data/` Contains the central openmoji.json with all meta informations for each emoji.

`font/` Contains the exported OpenMoji fonts.

`guidelines/` Contains various template files related to the styleguide.

`helpers/` Contains various helper scripts e.g. to export to .png and .svg, generate skintones variants, enforce the OpenMoji color palette ...

`src/` Contains all source .svg files of OpenMoji. The files are broken up into folders and files corresponding with the Unicode groups and sub-groups.

`test/` Automated unit tests to ensure consistency across all source .svg files.


## Attribution Requirements
As an open source project, attribution is critical from a legal, practical and motivational perspective. Please give us credits! Common places for attribution are for example: to mention us in your project README, the 'About' section or the footer on a website/in mobile apps.

Attribution suggestion:

> All emojis designed by [OpenMoji](https://openmoji.org/) – the open-source emoji and icon project. License: [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/#)


## License
OpenMoji graphics are licensed under the Creative Commons Share Alike License 4.0 ([CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/))

[![License: CC BY-SA 4.0](https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-sa/4.0/)

Code licensed under the GNU Lesser General Public License v3 ([LGPL-3.0](https://www.gnu.org/licenses/lgpl-3.0.en.html))

[![License: LGPL-3.0](https://img.shields.io/badge/License-LGPL%20v3-lightgrey.svg)](https://www.gnu.org/licenses/lgpl-3.0.en.html)
