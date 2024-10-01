Here's the complete tree structure for the `Node` interface, including all properties, methods, and events with short descriptions:

```js
Node
├── Properties
│   ├── baseURI: string                                // Absolute base URI of the node
│   ├── childNodes: NodeList                           // List of child nodes
│   ├── firstChild: Node | null                        // First child of the node
│   ├── isConnected: boolean                           // Indicates if the node is connected to the document
│   ├── lastChild: Node | null                         // Last child of the node
│   ├── nextSibling: Node | null                       // Next sibling of the node
│   ├── nodeName: string                               // Name of the node
│   ├── nodeType: number                               // Type of the node
│   ├── nodeValue: string | null                       // Value of the node
│   ├── ownerDocument: Document | null                 // Document that owns this node
│   ├── parentElement: Element | null                  // Parent element of the node
│   ├── parentNode: Node | null                        // Parent node of the node
│   ├── previousSibling: Node | null                   // Previous sibling of the node
│   ├── textContent: string | null                     // Text content of the node and its descendants
├── Methods
│   ├── appendChild(newChild: Node): Node                      // Appends a node as the last child
│   ├── cloneNode(deep?: boolean): Node                        // Clones the node
│   ├── compareDocumentPosition(otherNode: Node): number       // Compares document position of two nodes
│   ├── contains(otherNode: Node): boolean                     // Checks if the node contains another node
│   ├── getRootNode(options?: GetRootNodeOptions): Node        // Returns the root node of the current node
│   ├── hasChildNodes(): boolean                               // Checks if the node has any child nodes
│   ├── insertBefore(newNode: Node, referenceNode: Node | null): Node  // Inserts a node before a reference node
│   ├── isDefaultNamespace(namespace: string | null): boolean  // Checks if the namespace is default
│   ├── isEqualNode(otherNode: Node): boolean                  // Checks if two nodes are equal
│   ├── isSameNode(otherNode: Node): boolean                   // Checks if two nodes are the same
│   ├── lookupNamespaceURI(prefix: string | null): string | null  // Looks up the namespace URI by prefix
│   ├── lookupPrefix(namespace: string | null): string | null   // Looks up the prefix by namespace URI
│   ├── normalize(): void                                      // Normalizes text nodes by merging adjacent nodes
│   ├── removeChild(oldChild: Node): Node                      // Removes a child node
│   ├── replaceChild(newChild: Node, oldChild: Node): Node     // Replaces a child node with a new node
│   └── toString(): string                                     // Returns a string representation of the node
└── Events
    ├── DOMNodeInserted             // Fired when a node is added to the DOM
    ├── DOMNodeRemoved              // Fired when a node is removed from the DOM
    ├── DOMNodeInsertedIntoDocument // Fired when a node is inserted into a document
    ├── DOMNodeRemovedFromDocument  // Fired when a node is removed from a document
    ├── DOMSubtreeModified          // Fired when the structure of the DOM is modified
    ├── DOMCharacterDataModified    // Fired when the character data of a node is modified
    ├── DOMAttrModified             // Fired when an attribute of a node is modified
```

