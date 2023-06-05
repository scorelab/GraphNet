<h1 align="center">
  GraphNet
</h1>
<h2 align="center">
  A dynamic Javascript graph library
</h2>

<p align="center">
  <img src="https://img.shields.io/github/v/release/scorelab/GraphNet?label=version">
  <img src="https://img.shields.io/github/actions/workflow/status/scorelab/GraphNet/build_and_test.yml">
  <img src="https://img.shields.io/badge/license-MIT-green">
  <img alt="Codecov branch" src="https://img.shields.io/codecov/c/github/scorelab/GraphNet/develop">
</p>

Graphnet is a javascript graph library that will be created as a module to the semantic UI framework. Whereas Graphnet dynamically renders all nodes and edges via websocket connections, node and edge positioning algorithms such as force, random, circular, and others must be provided within the Graphnet as builtin modules.

## Installation

```bash
npm i graphnet
```

## Usage

Just import the component,

```javascript
import { LineGraph } from 'graphnet';
```

and use it,

```jsx
<LineGraph xValues={xValues} yValues={yValues} />
```

## Props

| prop             | description                                                                                                                                 |
| ---------------- | ------------------------------------------------------------------------------------------------------------------------------------------- |
| xValues          | It is the array of x-axis values.                                                                                                           |
| yValues          | It is the array of corresponding y-axis values.                                                                                             |

## Structure

In the repository the entry point is `index.js` file and it renders the required graph. Remember, `testground` folder is a react-app in itself and it can be used for testing the components during development.

## Development

For development,

```bash
npm i
cd testground && npm i
npm run dev # at the root folder --> GraphNet

```

It will open up a testground react app at `http://localhost:5173`.
