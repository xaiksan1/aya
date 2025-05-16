# Contributing to AYA

Thank you for considering contributing to AYA! We welcome contributions from the community to help improve the project. Please follow the guidelines below to get started.

## Development Setup

### Prerequisites

- Node.js (version 18.x)
- npm (version 9.x)

### Cloning the Repository

1. **Clone the repository**:
   ```sh
   git clone https://github.com/liriliri/aya.git
   cd aya
   ```

2. **Install dependencies**:
   ```sh
   npm install
   ```

3. **Run the application in development mode**:
   ```sh
   npm run dev
   ```

4. **Build the application**:
   ```sh
   npm run build
   ```

5. **Package the application**:
   ```sh
   npm run pack
   ```

## Project Structure

The repository contains the following directories and files:

- `src/main`: Contains the main process code for the Electron application.
- `src/preload`: Contains the preload scripts for the Electron application.
- `src/renderer`: Contains the renderer process code for the Electron application.
- `package.json`: Lists the dependencies and scripts for the project.
- `tsconfig.json`: Contains the TypeScript configuration for the project.
- `vite.config.ts`: Contains the Vite configuration for the renderer process.
- `vite.main.ts`: Contains the Vite configuration for the main process.
- `vite.preload.ts`: Contains the Vite configuration for the preload process.

## Contribution Process

We appreciate your contributions! To contribute to the project, please follow these steps:

1. **Fork the repository**: Click the "Fork" button at the top right corner of the repository page to create a copy of the repository in your GitHub account.

2. **Create a new branch**: Create a new branch for your changes. Use a descriptive name for the branch, such as `feature/add-new-feature` or `bugfix/fix-issue`.
   ```sh
   git checkout -b feature/add-new-feature
   ```

3. **Make your changes**: Make the necessary changes to the codebase. Ensure that your code follows the project's coding conventions and style guidelines.

4. **Commit your changes**: Commit your changes with a descriptive commit message.
   ```sh
   git commit -m "Add new feature"
   ```

5. **Push your changes**: Push your changes to your forked repository.
   ```sh
   git push origin feature/add-new-feature
   ```

6. **Create a pull request**: Go to the original repository and create a pull request from your forked repository. Provide a clear and concise description of your changes and the problem they solve.

7. **Participate in the review process**: Be responsive to feedback and make any necessary changes requested by the reviewers.

8. **Merge your changes**: Once your pull request is approved, it will be merged into the main branch.

## Reporting Issues

If you encounter any issues or bugs, please report them by creating a new issue in the [issue tracker](https://github.com/liriliri/aya/issues). Provide as much detail as possible, including steps to reproduce the issue and any relevant error messages.

## Discussions

If you have any questions, ideas, or suggestions, feel free to participate in the [discussion forum](https://github.com/liriliri/aya/discussions). We welcome your input and look forward to collaborating with you!

Thank you for contributing to AYA! 😊
