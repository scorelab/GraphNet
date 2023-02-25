## Graphnet

Graphnet is a JavaScript graph library that provides powerful tools for visualizing and interacting with graphs on the web. It is designed to be used as a module within the Semantic UI framework, and includes built-in modules for various node and edge positioning algorithms.

## Getting Started

To use Graphnet in your web project, you'll first need to install it using npm:

`npm install graphnet`

Once you've installed Graphnet, you can import it into your project using the following code:

`import Graphnet from 'graphnet';`

## Usage

Graphnet provides a flexible and customizable API for creating and manipulating graphs. Here are some examples of how to use Graphnet in your web project:

# Creating a Graph
`
const graph = new Graphnet.Graph();`

This will create a new empty graph that you can add nodes and edges to.

# Adding Nodes and Edges

To add a new node to the graph, you can use the `addNode()` method:

`const node = graph.addNode({ id: 1, label: 'Node 1' });`

This will create a new node with an ID of 1 and a label of "Node 1". You can also add edges between nodes using the `addEdge()` method:

`const edge = graph.addEdge({ source: 1, target: 2 });`

This will create a new edge between nodes with IDs 1 and 2.

# Rendering the Graph

To render the graph on a web page, you can create a new Graphnet visualization object and pass in the graph:

`const visualization = new Graphnet.Visualization({ container: '#graph-container' });
visualization.render(graph);`

# Node and Edge Positioning Algorithms

Graphnet includes built-in modules for various node and edge positioning algorithms. To use one of these algorithms, you can pass it in as an option when creating the visualization object:
`
const visualization = new Graphnet.Visualization({ container: '#graph-container', layout: 'force' });`

## Contributing

If you'd like to contribute to Graphnet, please fork the repository and create a new pull request with your changes. We welcome all contributions and feedback!
