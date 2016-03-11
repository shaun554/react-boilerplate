<img src="https://cloud.githubusercontent.com/assets/5436686/13701007/0192aa9a-e785-11e5-962d-e239172cc763.jpg" alt="react boilerplate banner" align="center" />

<div align="center">
  <!-- Dependency Status -->
  <a href="https://david-dm.org/mxstbr/react-boilerplate/v3.0.0">
    <img src="https://david-dm.org/mxstbr/react-boilerplate/v3.0.0.svg" alt="Dependency Status" />
  </a>
  <!-- devDependency Status -->
  <a href="https://david-dm.org/mxstbr/react-boilerplate/v3.0.0#info=devDependencies">
    <img src="https://david-dm.org/mxstbr/react-boilerplate/v3.0.0/dev-status.svg" alt="devDependency Status" />
  </a>
  <!-- Build Status -->
  <a href="https://travis-ci.org/mxstbr/react-boilerplate?branch=v3.0.0">
    <img src="https://travis-ci.org/mxstbr/react-boilerplate.svg?branch=v3.0.0" alt="Build Status" />
  </a>
  <!-- Test Coverage -->
  <a href="https://coveralls.io/r/mxstbr/react-boilerplate?branch=v3.0.0">
    <img src="https://coveralls.io/repos/github/mxstbr/react-boilerplate/badge.svg?branch=v3.0.0" alt="Test Coverage" />
  </a>
</div>

Quick setup for new performance orientated, offline–first React.js applications featuring Redux, hot–reloading, PostCSS, react-router, ServiceWorker, AppCache, FontFaceObserver and Mocha.

Made with :heart: by [Max Stoiber](https://twitter.com/mxstbr) and [contributors](https://github.com/mxstbr/react-boilerplate/graphs/contributors). *If you're using this boilerplate, we'd love to [hear from you](https://github.com/mxstbr/react-boilerplate/issues/115)!*

## Features

- **Instant feedback** Enjoy the best DX and code your app at the speed of thought! Your saved changes to the CSS and JS are reflected instantaneously without refreshing the page. Preserve application state even when you update something in the underlying code!

- **Quick scaffolding** Automate the creation of components, containers, routes and sagas - and their tests - right from the CLI!

- **Predictable state management** Unidirectional data flow allows for change logging and time travel debugging.

- **Next generation JavaScript** Use template strings, object destructuring, arrow functions, JSX syntax and more, today.

- **Next generation CSS**. Write composable CSS that's co-located with your components for complete modularity. Unique generated class names keep the specificity low while eliminating style clashes. Ship only the styles that are on the page for the best performance.

- **Industry-standard routing** It's natural to want to add pages (e.g. `/about`) to your application, and routing makes this possible.

- **Offline-first** The next frontier in performant web apps: availability without a network connection from the instant your users load the app.

But wait... there's more!

  - **Built-in unit testing** Automatically guarantee code quality and non-breaking changes.
  - **Native web app** Your app's new home? The homescreen of your users' phones.
  - **The fastest fonts** Say goodbye to vacant text.

## Documentation

- [General](docs/general)
  - [**Getting started**](docs/general/getting-started.md)
  - [Prerequisites](docs/general/prerequisites.md)
  - [Features](docs/general/features.md)
  - [**Commands**](docs/general/commands.md)
  - [Files](docs/general/files.md)
  - [FAQ](docs/general/faq.md)
- [Testing](docs/testing)
  - [Unit Testing](docs/general/unit-testing.md)
  - [Component Testing](docs/general/component-testing.md)
  - [Remote Testing](docs/general/remote-testing.md)
- [CSS](docs/css)


## Quick start

> Note: You'll need Node, npm and git installed for this to work, see the [prerequisites](./docs/general/prerequisites.md)!

1. Clone this repo using `$ git clone git@github.com:mxstbr/react-boilerplate`.

2. Run `$ npm run setup` to install dependencies and clean the git repo.

At this point you can run `$ npm start` to see the example app at `http://localhost:3000`.

3. Run `$ npm run clean` to delete the example app.

Now you can go and start building your app!

## License

This project is licensed under the MIT license, Copyright (c) 2015 Maximilian Stoiber. For more information see `LICENSE.md`.
