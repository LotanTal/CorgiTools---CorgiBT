# CorgiBT

CorgiBT is a Behaviour Tree implementation for Unity, providing both runtime and editor functionality. 
It allows you to create, manage, and visualize complex AI behaviours in a structured and modular way.

## Features

- **Behaviour Tree Editor**: A custom editor window to design and manage behaviour trees.
- **Runtime Components**: Core behaviour tree nodes and execution logic.
- **Blackboard System**: Shared data storage for nodes to communicate and store state information.
- **Custom Controls**: Extendable UI elements for better editor experience.

## Installation

1. Clone or download the repository and place the `CorgiBT` folder in your `Assets/` directory.
2. Open Unity and navigate to the `Window` menu to find the CorgiBT editor tools.

## Usage

### Editor Window

To open the Behaviour Tree editor window, go to `Window` > `CorgiBT` > `Behaviour Tree Editor`. This will open a custom editor window where you can create and manage your behaviour trees.

### Creating a Behaviour Tree

1. Open the Behaviour Tree editor window.
2. Click on `Create New` to start a new behaviour tree.
3. Use the node search window to add nodes to your tree.
4. Connect nodes by dragging from the output port of one node to the input port of another.

### Node Types

- **Composite Nodes**: Control flow nodes that manage the execution of child nodes.
- **Decorator Nodes**: Single-child nodes that modify the behaviour of their child.
- **Action Nodes**: Leaf nodes that perform actions.

### Blackboard System

The blackboard is a shared data structure used by nodes to store and retrieve values. This allows for communication between nodes and the storage of state information.

