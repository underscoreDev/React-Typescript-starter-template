** add any badgets for the project (CI, code quality, etc.) **

# DX Marketing Website

## What is the DX Marketing Website?

DX Marketing Website

## About the project

- Website: <a href="#" target="_blank">example.com</a>
- Authors: <a href="https://www.zimmerman.team/" target="_blank">Zimmerman</a>

## Installing

### Manual installation

| Name | Recommended version |
| ---- | ------------------- |
| Node | 16.13               |
| Yarn | latest              |

#### Install dependencies

From the root folder:

`yarn install`

#### Configuration

In the root folder:

- create `.env` file
- add:

```
  NODE_PATH=src/app/
  <any other environment variables needed>
```

#### Run the app

For development:

`yarn start`

App should be running on <http://localhost:3000>

#### Build

For production build:

`yarn build`

Build files should be in `build`

#### E2E Tests

Run e2e tests: `yarn cy:open`

## Docker

| Name           | Recommended version |
| -------------- | ------------------- |
| Docker         | latest              |
| docker-compose | latest              |

In the root folder:

- create `.env` file
- add:

```
  NODE_PATH=src/app/
  REACT_APP_MAPBOX_TOKEN=<mapbox_token>
  REACT_APP_ODATA_API_URL=<TGF_API_url>
```

`docker-compose build`

`docker-compose up`

App should be running on <http://localhost:3000>

---

## Methodologies

### component-based development

Component-based software engineering (CBSE), also called as component-based development (CBD), is a branch of software engineering that emphasizes the separation of concerns with respect to the wide-ranging functionality available throughout a given software system.

### behavior driven development

Behavior Driven Development (BDD) is an Agile process designed to keep focus on stakeholder's value throughout the whole project. It is a way to do Test Driven Development (TDD) with clarity that can not be accomplished with Unit Testing. It is a way to describe and test functionality in (almost) natural language.

## Core

### react

A JavaScript library for building declarative component-based user interfaces

### redux

Redux is a predictable state container for JavaScript apps. It helps you write applications that behave consistently, run in different environments (client, server, and native), and are easy to test

## Styling

### styled components

styled-components utilises tagged template literals to style your components. It removes the mapping between components and styles. This means that when you're defining your styles, you're actually creating a normal React component, that has your styles attached to it.

### storybook

Storybook is a UI development environment and playground for UI components. The tool enables users to create components independently and showcase components interactively in an isolated development environment.

## Code quality

### eslint

### stylelint

A linter that helps you avoid errors and enforce conventions in your styles.

## Testing

### cypress

Cypress is a next generation front end testing tool built for the modern web.

## CI/CD

### circle ci

CircleCI's continuous integration and delivery platform makes it easy for teams of all sizes to rapidly build and release quality software at scale.

## Performance

### lighthouse

Lighthouse is an open-source, automated tool for improving the quality of web pages. You can run it against any web page, public or requiring authentication. It has audits for performance, accessibility, progressive web apps, and more.

## Can I contribute?

Yes! We are mainly looking for coders to help on the project. If you are a coder feel free to _Fork_ the repository and send us Pull requests!
