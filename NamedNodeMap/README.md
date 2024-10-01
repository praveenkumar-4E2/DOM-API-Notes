```js

NamedNodeMap
├── Properties
│   ├── length: number                                         // The number of nodes in the map
│   ├── [index: number]: Node                                   // Accesses a node by its index
│   ├── [name: string]: Node                                   // Accesses a node by its name
│
├── Methods
│   ├── item(index: number): Node                             // Returns the node at the specified index
│   ├── getNamedItem(name: string): Node                     // Returns the node with the specified name
│   ├── setNamedItem(arg: Node): Node                        // Adds a new node with the specified name (overwrites if exists)
│   ├── removeNamedItem(name: string): Node                  // Removes the node with the specified name
│   ├── setNamedItemNS(arg: Node): Node                      // Adds a new node with the specified namespace (overwrites if exists)
│   ├── getNamedItemNS(namespace: string, localName: string): Node  // Returns the node with the specified namespace and local name
│   ├── removeNamedItemNS(namespace: string, localName: string): Node  // Removes the node with the specified namespace and local name

```