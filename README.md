# hub-af

This template should help get you started developing with Vue 3 in Vite.

## Recommended IDE Setup

# Air Force Hub: Streamlining Processes and Enhancing Communication

Welcome to the Air Force Hub, a project born out of a deep respect and passion for creating a streamlined and efficient environment within the Air Force. This initiative is spearheaded by a hobbyist programmer and developer with a profound vision to revolutionize the current system through the development of a versatile Web-App. Through this initiative, we aim to garner support and collaboration from the leadership and the Department of Defense (DoD), thereby creating tools that facilitate smoother operations and clear lines of communication.

## Project Overview

The Air Force Hub is hosted on [hub.airforce](http://hub.airforce) and serves as a repository of tools and applications primarily designed to automate mundane processes and help individuals find the necessary resources effortlessly. We aspire to reduce the time spent on administrative tasks, thus allowing personnel to focus more on the mission at hand.

### Core Features

- **MARS (Military Automated Routing System)**
  - A tool designed for automated document handling and routing.
  - Streamlines the communication and coordination with leadership.
  - Aids in organizing and planning your career pathway in the Air Force.

- **Centralized Resource Links**
  - Easy access to vital resources such as pay information and OPR/EPR related content.
  - A portal to collate documents from multiple locations, automating the process of package generation and reducing manual intervention.

### Future Developments

- Development of custom applications to further enhance life in the Air Force.
- Creation of a comprehensive dashboard to offer a centralized view of various processes and tools.

## Get Involved

We are keen to foster a community of individuals who share a common passion for advancing the Air Force. We welcome contributions in the form of code, time, or suggestions to help improve this project. Your contributions not only make a difference in this project but also serve as a remarkable "bUlLeT" in fostering positive changes.

### Community Suggestions

- We are open to suggestions and feedback to further enhance the project.
- If you are a like-minded individual with coding skills or ideas, we invite you to collaborate and contribute to this project.

### Contact & Collaboration

- **Community Forum**: Join discussions, share ideas, and collaborate with other enthusiasts.
- **Contribution Guidelines**: Detailed guidelines for individuals interested in contributing to the project.
- **Issue Tracker**: A tool to report bugs and suggest new features.

### Support the Project

- **Donations**: Consider supporting the project financially to help foster its growth and development.
- **Sponsorship**: Opportunities for organizations to sponsor the project and contribute to a noble cause.

## Conclusion

Together, we can foster a community of innovation and collaboration, working towards making the Air Force a more efficient and responsive entity. Your support and contributions are invaluable in making this vision a reality.

Thank you for being a part of this remarkable journey!

*Note: This project is an independent initiative and not officially affiliated with the U.S. Air Force or the Department of Defense.*





[VSCode](https://code.visualstudio.com/) + [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar) (and disable Vetur) + [TypeScript Vue Plugin (Volar)](https://marketplace.visualstudio.com/items?itemName=Vue.vscode-typescript-vue-plugin).

## Type Support for `.vue` Imports in TS

TypeScript cannot handle type information for `.vue` imports by default, so we replace the `tsc` CLI with `vue-tsc` for type checking. In editors, we need [TypeScript Vue Plugin (Volar)](https://marketplace.visualstudio.com/items?itemName=Vue.vscode-typescript-vue-plugin) to make the TypeScript language service aware of `.vue` types.

If the standalone TypeScript plugin doesn't feel fast enough to you, Volar has also implemented a [Take Over Mode](https://github.com/johnsoncodehk/volar/discussions/471#discussioncomment-1361669) that is more performant. You can enable it by the following steps:

1. Disable the built-in TypeScript Extension
    1) Run `Extensions: Show Built-in Extensions` from VSCode's command palette
    2) Find `TypeScript and JavaScript Language Features`, right click and select `Disable (Workspace)`
2. Reload the VSCode window by running `Developer: Reload Window` from the command palette.

## Customize configuration

See [Vite Configuration Reference](https://vitejs.dev/config/).

## Project Setup

```sh
npm install
```

### Compile and Hot-Reload for Development

```sh
npm run dev
```

### Type-Check, Compile and Minify for Production

```sh
npm run build
```

### Run Unit Tests with [Vitest](https://vitest.dev/)

```sh
npm run test:unit
```

### Run End-to-End Tests with [Cypress](https://www.cypress.io/)

```sh
npm run test:e2e:dev
```

This runs the end-to-end tests against the Vite development server.
It is much faster than the production build.

But it's still recommended to test the production build with `test:e2e` before deploying (e.g. in CI environments):

```sh
npm run build
npm run test:e2e
```

### Lint with [ESLint](https://eslint.org/)

```sh
npm run lint
```
