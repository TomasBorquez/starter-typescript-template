# Starter TypeScript Template

## Overview

The `starter-typescript-template` repository serves as a comprehensive starting point for Node.js projects using TypeScript. This template includes a pre-configured setup to get your TypeScript project up and running quickly with best practices in mind. It integrates modern development tools to facilitate a smooth development workflow, allowing developers to focus on writing their application code right away.

## Features

- **TypeScript Configuration:** A base `tsconfig.json` for TypeScript compilation options.
- **Development Server:** Utilizing `ts-node-dev` for hot reloading during development, which significantly speeds up the development process by automatically restarting your server upon file changes.
- **Testing Framework:** Integrated with `vitest` for running tests in a Node.js environment, supporting TypeScript out of the box.
- **Code Linting:** ESLint configured with `@typescript-eslint/parser` and `@typescript-eslint/eslint-plugin` to enforce code style and catch syntax and logic errors.
- **Code Formatting:** Prettier set up for consistent code formatting.
- **Environment Variables:** Dotenv configured for managing environment variables, making it easy to customize your application for different development environments without changing your code.
- **Path Aliases:** `tsconfig-paths` and `tsc-alias` for simpler import paths, avoiding the complexity of relative paths in imports.

## Getting Started

1. **Clone the Repository**
```bash
git clone https://github.com/your-username/starter-typescript-template.git
cd starter-typescript-template
```

2. **Install Dependencies**
```bash
pnpm install
```

3. **Start Development Server**
```bash
npm run dev
```

4. **Run Tests** Executes your tests using Vitest.
```bash
npm test
```

## Scripts

- `start`: Launch your application with `ts-node`, suitable for production environments.
- `dev`: Start the development server with hot reload.
- `test`: Run your tests using Vitest.

## Customizing Your Setup

- **TypeScript Configuration:** Modify `tsconfig.json` to tweak compiler options.
- **Environment Variables:** Add custom environment variables in `.env` files. Make sure not to commit sensitive data to your version control.

## Contributing

Contributions are welcome! If you have suggestions for improving this template, please open an issue or a pull request.
