<h1 align="center">CodeNest</h1>

This project uses Nx.

<img src="https://raw.githubusercontent.com/nrwl/nx/master/images/nx-logo.png" width="200">

Nx supports many plugins which add capabilities for developing different types of applications and different tools.

These capabilities include generating applications, libraries, etc as well as the devtools to test, and build projects as well.

There are also many [community plugins](https://nx.dev/community) you could add.

## Development server

Run `nx serve main` for a dev server. Navigate to http://localhost:4200/.

## Build

Run `nx build main` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

## Running unit tests

Run `nx test main` to execute the unit tests via [Jest](https://jestjs.io).

Run `nx affected:test` to execute the unit tests affected by a change.

## Understand your workspace

Run `nx dep-graph` to see a diagram of the dependencies of your projects.
