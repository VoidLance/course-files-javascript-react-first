# JavaScript React First

[![React](https://img.shields.io/badge/React-19-61DAFB?logo=react&logoColor=white)](https://react.dev/)

JavaScript React First is a small Create React App project for learning the fundamentals of React and modern JavaScript. It includes a starter `App` component, reusable functions and components, Tailwind CSS utility classes, and a basic React Testing Library test.

## Why this project is useful

- Provides a minimal React application that is easy to run and modify.
- Demonstrates component rendering, event handlers, and `useEffect`.
- Includes examples of JavaScript functions and ES module exports in [`first-project/src/test.js`](first-project/src/test.js).
- Includes a ready-to-use development server, test runner, and production build workflow.

## Getting started

### Prerequisites

- Node.js and npm
- A modern web browser

### Install

From the repository root, install the application dependencies:

```bash
cd first-project
npm install
```

### Run the app

Start the development server:

```bash
npm start
```

Then open <http://localhost:3000>. The browser reloads as source files change.

The main example is implemented in [`first-project/src/App.js`](first-project/src/App.js). Edit that file or the supporting styles and functions in `first-project/src/` to experiment with React.

## Available commands

Run these commands from `first-project/`:

| Command | Description |
| --- | --- |
| `npm start` | Starts the development server. |
| `npm test` | Runs the test suite in watch mode. |
| `npm run build` | Creates an optimized production build in `build/`. |

To run the tests once in a non-interactive environment:

```bash
npm test -- --watchAll=false
```

## Project structure

```text
first-project/
├── public/       Static files and the HTML entry point
├── src/          React components, styles, functions, and tests
├── package.json  Dependencies and npm scripts
└── tailwind.config.js
```

The repository root also contains a standalone `index.html` used as an early HTML exercise; the React application is located in `first-project/`.

## Help and documentation

For project-specific questions or bug reports, [open an issue](https://github.com/VoidLance/course-files-javascript-react-first/issues) with steps to reproduce the problem and relevant command output.

Useful documentation:

- [React documentation](https://react.dev/learn)
- [Create React App documentation](https://create-react-app.dev/docs/getting-started/)
- [Tailwind CSS documentation](https://tailwindcss.com/docs)
- [React Testing Library documentation](https://testing-library.com/docs/react-testing-library/intro/)

## Contributing

Contributions and learning-focused improvements are welcome. Before opening a pull request:

1. Create a branch for your change.
2. Keep changes focused and explain what was learned or improved.
3. Run `npm test -- --watchAll=false` and `npm run build` from `first-project/`.
4. Describe the change and validation results in the pull request.

Please use the issue tracker for questions, proposed improvements, and bug reports. The project is maintained by [VoidLance](https://github.com/VoidLance) with contributions from the community.

## License

No license file is currently included in this repository. Add a license before distributing the project for reuse.
