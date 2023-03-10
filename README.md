## React.JS Typescript with ReduxToolkit

This repo contains an example of a development setup with React, Redux Toolkit, TypeScript and Firebase. 

## Overview

This repository provides a basic but dynamic demo & reference for React.JS with Redux Toolkit that performs CRUD (Create, Read, Update & Delete) operations. The project is also using typescript as part of the react template.

### Redux Toolkit:
- **Simple** - Provides good defaults for store setup out of the box, and includes the most commonly used Redux addons built-in.
- **Opinionated** -
  Provides good defaults for store setup out of the box, and includes the most commonly used Redux addons built-in.
- **Powerful** - Takes inspiration from libraries like Immer and Autodux to let you write "mutative" immutable update logic, and even create entire "slices" of state automatically.
- **Effective** - Lets you focus on the core logic your app needs, so you can do more work with less code.

You can read more from the official documentation: [https://redux-toolkit.js.org/](https://redux-toolkit.js.org/)

### Getting Started
1. Restore the package by running the `npm i` inside the directory where [package.json](package.json) is stored.
2. Connect to the web api endpoint. You can use the deployed endpoint or use your local. This can be modified inside the [api.ts](./src/api.ts)
3. Run the app using: `npm run start`
4. To build: `npm run build`
