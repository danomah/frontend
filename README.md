<a href="https://zonedigital.com"><img src="./assets/logo.svg" height="50" alt="Zone Logo" aria-label="zonedigital.com" /></a>

# Zone: Frontend

[![Travis][img-travis]][url-travis] [![lerna][img-lerna]][url-lerna] [![License][img-license]][url-license]

Mono repo for Zone's frontend setup and tooling.

## Packages

See `./packages/*` for individual package installation details.

| Package                 | Description                     |
| ----------------------- | ------------------------------- |
| [eslint-config-vue]     | Base+Vue JavaScript style guide |
| [eslint-config-zone]    | Base JavaScript style guide     |
| [stylelint-config-zone] | Base CSS style guide            |

## Maintenance

This repo is managed with [Lerna][url-lerna] and [Yarn workspaces][url-yarn-workspaces]. Be sure to read up before editing.

This repo has been setup with fixed verisoning, in other words, all packages have the same version number. Bump a major release on one package will cause a major bump on all other packages.

Be sure to check that all the [Travis CI][url-travis] build jobs have passed.

[eslint-config-vue]: https://github.com/zone/frontend/tree/master/packages/eslint-config-vue
[eslint-config-zone]: https://github.com/zone/frontend/tree/master/packages/eslint-config-zone
[stylelint-config-zone]: https://github.com/zone/frontend/tree/master/packages/stylelint-config-zone
[img-lerna]: https://img.shields.io/badge/maintained%20with-lerna-cc00ff.svg?style=flat-square
[img-license]: https://img.shields.io/badge/license-MIT-blue.svg?style=flat-square
[img-travis]: https://img.shields.io/travis/zone/frontend.svg?style=flat-square
[url-lerna]: https://lernajs.io/
[url-license]: https://github.com/zonedigital/frontend/blob/master/LICENSE
[url-travis]: https://travis-ci.org/zone/frontend
[url-yarn-workspaces]: https://yarnpkg.com/lang/en/docs/workspaces/
