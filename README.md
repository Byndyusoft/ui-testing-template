# ui-testing-template
Base template for UI test with Cypress

## Prerequisites
Make sure you have installed all the following prerequisites on your development machine:

- [Git](https://git-scm.com)
- [Node.js](https://nodejs.org) (version 14.16.0 LTS or higher)
- [Yarn 2+](https://yarnpkg.com/) package manager

## Contributing

To contribute, you will need to setup your local environment, see [running locally](#running-locally).

### Code conventions

Some code conventions are enforced automatically by ESLint + Prettier + markdownlint + husky + lint-staged stack.

### General folders layout

- `cypress/integration/` - UI tests folder
- `cypress/fixtures/` - fixture files
- `cypress/plagins/` - plugins file can be used to load plugins

### Usage

See [Cypress documentation](https://docs.cypress.io/guides/overview/why-cypress)

### Running locally

```bash
yarn install
yarn cypress:open
```

## Maintainers

- [@Byndyusoft/owners](https://github.com/orgs/Byndyusoft/teams/owners)
- [@Byndyusoft/team](https://github.com/orgs/Byndyusoft/teams/team)

## License

This repository is released under version 2.0 of the
[Apache License](https://www.apache.org/licenses/LICENSE-2.0).
