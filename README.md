# Template Node

[![Build](https://github.com/jdevelop-io/template-node/actions/workflows/build.yml/badge.svg)](https://github.com/jdevelop-io/template-node/actions/workflows/build.yml)
[![Test](https://github.com/jdevelop-io/template-node/actions/workflows/test.yml/badge.svg)](https://github.com/jdevelop-io/template-node/actions/workflows/test.yml)
[![Code Quality](https://github.com/jdevelop-io/template-node/actions/workflows/code_quality.yml/badge.svg)](https://github.com/jdevelop-io/template-node/actions/workflows/code_quality.yml)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](/LICENSE)
[![WakaTime](https://wakatime.com/badge/user/b5dd94a4-c0ea-4c12-9cb2-41f984e74fdc/project/55c0e52a-67db-4986-9f16-4c62c87dd799.svg)](https://wakatime.com/badge/user/b5dd94a4-c0ea-4c12-9cb2-41f984e74fdc/project/55c0e52a-67db-4986-9f16-4c62c87dd799)

**Template Node** is a Node.js project scaffolding tool designed to speed up the initial setup of Node.js applications.
This repository provides a solid foundation for building scalable and maintainable Node.js projects, with built-in best
practices and commonly used configurations.

## Features

- **TypeScript**: Use TypeScript for a better development experience and improved code quality.
- **ESLint**: Lint your code with ESLint to maintain consistent coding standards.
- **Prettier**: Format your code with Prettier to keep it clean and consistent.
- **Jest**: Test your code with Jest to ensure its correctness and reliability.
- **Husky**: Use Husky to run tasks on Git hooks and enforce code quality.
- **Lint-Staged**: Run ESLint and Prettier on staged files to catch errors before committing.
- **GitHub Actions**: Use GitHub Actions for continuous integration and automated testing.

## Getting Started

### Prerequisites

Make sure you have Node.js and pNPM installed on your machine before running the project.

- [Node.js](https://nodejs.org/) (20.18.0 or later)
- [pNPM](https://pnpm.io/) (9.12.0 or later)

### Installation

1. Clone the repository:

   ```bash
   git clone --depth 1 https://github.com/jdevelop-io/template-node.git
   cd template-node
   ```

2. Remove the `.git` directory to start with a clean git history:

   ```bash
   rm -rf .git
   ```

3. Initialize a new git repository:

   ```bash
   git init
   ```

4. Install the dependencies:
   ```bash
   pnpm install
   ```

### Scripts

- `pnpm build` : Build the project.
- `pnpm buid:watch` : Build the project in watch mode.
- `pnpm test` : Run the tests.
- `pnpm test:watch` : Run the tests in watch mode.
- `pnpm test:coverage` : Run the tests with coverage.
- `pnpm test:coverage:watch`: Run the tests with coverage in watch mode.
- `pnpm format` : Format the code and fix formatting errors.
- `pnpm format:check` : Check the code for formatting errors.
- `pnpm lint` : Lint the code and fix linting errors.
- `pnpm lint:check` : Check the code for linting errors.

### Project Structure

```plaintext
template-node
├── .github
│   ├── workflows
│   │   ├── build.yml
│   │   ├── code_quality.yml
│   │   └── tests.yml
├── .husky
│   └── pre-commit
├── coverage
├── dist
├── node_modules
├── src
├── test
│   └── unit
├── .editorconfig
├── .gitignore
├── .prettierignore
├── eslint.config.mjs
├── jest.config.ts
├── LICENSE
├── lint-staged.config.mjs
├── package.json
├── pnpm-lock.yaml
├── prettier.config.mjs
├── README.md
└── tsconfig.json
```

### Contributing

Contributions are welcome! If you have any ideas, suggestions, or issues, feel free to open an issue or submit a pull
request.

### License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
