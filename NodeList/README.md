```js

NodeList
├── Properties
│   ├── length: number                                         // The number of nodes in the NodeList
│   ├── [index: number]: Node                                 // Accesses a node by its index
│
├── Methods
│   ├── item(index: number): Node                             // Returns the node at the specified index
│   ├── forEach(callback: (node: Node, index?: number) => void): void  // Executes a provided function once for each node
│   ├── entries(): Iterator<[number, Node]>                  // Returns an iterator of [index, node] pairs
│   ├── keys(): Iterator<number>                               // Returns an iterator for the keys (indices) of the NodeList
│   ├── values(): Iterator<Node>                               // Returns an iterator for the values (nodes) of the NodeList


```