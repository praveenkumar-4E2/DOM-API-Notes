``` js

Element
├── Properties
│   ├── attributes: NamedNodeMap                          // A collection of all attributes of the element
│   ├── classList: DOMTokenList                           // Accesses the list of classes on the element
│   ├── className: string                                 // Represents the value of the element's class attribute
│   ├── clientHeight: number                              // Height of the element, including padding
│   ├── clientLeft: number                                // Width of the left border of the element
│   ├── clientTop: number                                 // Width of the top border of the element
│   ├── clientWidth: number                               // Width of the element, including padding
│   ├── id: string                                        // Represents the element's unique identifier
│   ├── innerHTML: string                                 // Gets or sets the HTML content of the element
│   ├── localName: string                                 // Returns the local name of the element
│   ├── namespaceURI: string | null                       // The namespace URI of the element
│   ├── outerHTML: string                                 // Gets or sets the entire HTML of the element
│   ├── part: DOMTokenList                                // A set of strings for shadow DOM styling
│   ├── prefix: string | null                             // The namespace prefix of the element
│   ├── scrollHeight: number                              // Total height of the element's content, including overflow
│   ├── scrollLeft: number                                // Number of pixels the content is scrolled from the left
│   ├── scrollTop: number                                 // Number of pixels the content is scrolled from the top
│   ├── scrollWidth: number                               // Total width of the element's content, including overflow
│   ├── shadowRoot: ShadowRoot | null                     // Represents the shadow root of the element
│   ├── slot: string                                      // Name of the slot where the element is assigned
│   ├── tagName: string                                   // Tag name of the element
├── Methods
│   ├── attachShadow(init: ShadowRootInit): ShadowRoot      // Attaches a shadow root to the element
│   ├── closest(selector: string): Element | null           // Returns the closest ancestor matching the selector
│   ├── getAttribute(name: string): string | null           // Returns the value of an attribute
│   ├── getAttributeNames(): string[]                       // Returns an array of attribute names
│   ├── getAttributeNS(namespace: string | null, name: string): string | null  // Returns the value of a namespaced attribute
│   ├── getBoundingClientRect(): DOMRect                    // Returns the element's size and position
│   ├── getClientRects(): DOMRectList                       // Returns all client rects of the element
│   ├── getElementsByClassName(names: string): HTMLCollection  // Returns elements with the specified class
│   ├── getElementsByTagName(tagName: string): HTMLCollection  // Returns elements with the specified tag name
│   ├── getElementsByTagNameNS(namespace: string, tagName: string): HTMLCollection  // Returns elements with the specified namespace and tag name
│   ├── hasAttribute(name: string): boolean                 // Checks if the element has a specific attribute
│   ├── hasAttributeNS(namespace: string | null, name: string): boolean  // Checks if the element has a namespaced attribute
│   ├── hasAttributes(): boolean                            // Checks if the element has any attributes
│   ├── hasPointerCapture(pointerId: number): boolean        // Checks if the element has captured a pointer
│   ├── insertAdjacentElement(position: string, element: Element): Element | null  // Inserts an element in the specified position
│   ├── insertAdjacentHTML(position: string, text: string): void  // Parses the text as HTML and inserts it
│   ├── insertAdjacentText(position: string, text: string): void  // Inserts text in the specified position
│   ├── matches(selector: string): boolean                  // Checks if the element matches the selector
│   ├── removeAttribute(name: string): void                 // Removes an attribute
│   ├── removeAttributeNS(namespace: string | null, name: string): void  // Removes a namespaced attribute
│   ├── requestFullscreen(options?: FullscreenOptions): Promise<void>  // Requests to make the element fullscreen
│   ├── requestPointerLock(): void                          // Locks the pointer to the element
│   ├── scroll(options?: ScrollToOptions): void             // Scrolls the element to a position
│   ├── scroll(x: number, y: number): void                  // Scrolls the element by given x and y coordinates
│   ├── scrollBy(options?: ScrollToOptions): void           // Scrolls the element by a certain amount
│   ├── scrollBy(x: number, y: number): void                // Scrolls the element by given x and y coordinates
│   ├── scrollIntoView(arg?: boolean | ScrollIntoViewOptions): void  // Scrolls the element into view
│   ├── scrollTo(options?: ScrollToOptions): void           // Scrolls to a specific position
│   ├── scrollTo(x: number, y: number): void                // Scrolls to a specific x and y position
│   ├── setAttribute(name: string, value: string): void     // Sets an attribute with a given name and value
│   ├── setAttributeNS(namespace: string | null, name: string, value: string): void  // Sets a namespaced attribute
│   ├── toggleAttribute(name: string, force?: boolean): boolean  // Toggles the presence of an attribute
│   ├── webkitMatchesSelector(selector: string): boolean    // Checks if the element matches the selector (deprecated)
│   ├── releasePointerCapture(pointerId: number): void      // Releases pointer capture
│   ├── remove(): void                                      // Removes the element from the DOM
│   └── replaceWith(...nodes: (Node | string)[]): void      // Replaces the element with new nodes
└── Events
    ├── fullscreenchange               // Fired when the element enters or exits fullscreen
    ├── fullscreenerror                // Fired when an error occurs while changing fullscreen state
    ├── pointerlockchange              // Fired when the pointer lock state changes
    ├── pointerlockerror               // Fired when an error occurs in pointer lock request
    └── slotchange                     // Fired when assigned nodes change in a shadow DOM slot



```