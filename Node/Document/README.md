```js

Document
├── Properties
│   ├── activeElement: Element | null                        // Currently focused element
│   ├── adoptedStyleSheets: StyleSheetList                  // List of adopted stylesheets
│   ├── alinkColor: string                                   // Color of active links
│   ├── all: HTMLCollection                                   // Collection of all elements in the document
│   ├── anchors: HTMLCollection                               // Collection of all <a> elements
│   ├── applets: HTMLCollection                               // Collection of <applet> elements
│   ├── bgColor: string                                      // Background color of the document
│   ├── body: HTMLElement | null                              // <body> element of the document
│   ├── characterSet: string                                 // Character encoding of the document
│   ├── childElementCount: number                             // Number of child elements
│   ├── children: HTMLCollection                              // Collection of child elements
│   ├── compatMode: string                                   // Document compatibility mode
│   ├── contentType: string                                   // MIME type of the document
│   ├── cookie: string                                        // Document's cookies
│   ├── currentScript: HTMLScriptElement | null              // Currently executing <script>
│   ├── defaultView: Window | null                           // Default view associated with the document
│   ├── designMode: string                                   // Document's design mode (edit mode)
│   ├── dir: string                                          // Document direction (ltr or rtl)
│   ├── doctype: DocumentType | null                         // Document type declaration
│   ├── documentElement: HTMLElement                          // Root <html> element
│   ├── documentURI: string                                  // Document's URI
│   ├── domain: string                                       // Domain of the document
│   ├── embeds: HTMLCollection                                // Collection of <embed> elements
│   ├── featurePolicy: FeaturePolicy                         // Feature policy of the document
│   ├── fgColor: string                                      // Foreground color of the document
│   ├── firstElementChild: Element | null                    // First child element
│   ├── fonts: FontFaceSet                                   // Collection of fonts used in the document
│   ├── forms: HTMLCollection                                 // Collection of <form> elements
│   ├── fragmentDirective: string                             // Fragment directive for prerendering
│   ├── fullscreenElement: Element | null                     // Element in fullscreen mode
│   ├── fullscreenEnabled: boolean                            // Indicates if fullscreen is supported
│   ├── head: HTMLHeadElement | null                          // <head> element of the document
│   ├── hidden: boolean                                       // Indicates if the document is hidden
│   ├── images: HTMLCollection                                // Collection of <img> elements
│   ├── implementation: DOMImplementation                     // DOM implementation details
│   ├── lastElementChild: Element | null                      // Last child element
│   ├── lastModified: string                                  // Last modified date of the document
│   ├── lastStyleSheetSet: string | null                     // Last active stylesheet set
│   ├── linkColor: string                                    // Color of links
│   ├── links: HTMLCollection                                 // Collection of <link> elements
│   ├── location: Location                                    // Location object of the document
│   ├── pictureInPictureElement: Element | null               // Currently active Picture-in-Picture element
│   ├── pictureInPictureEnabled: boolean                      // Indicates if Picture-in-Picture is supported
│   ├── plugins: Plugin[]                                    // Collection of installed plugins
│   ├── pointerLockElement: Element | null                   // Element currently locked to pointer
│   ├── preferredStyleSheetSet: string | null                // Preferred stylesheet set
│   ├── prerendering: boolean                                 // Indicates if the document is being prerendered
│   ├── readyState: string                                    // Current loading state of the document
│   ├── referrer: string                                      // Document's referrer URL
│   ├── rootElement: Element | null                           // Root element of the document (deprecated)
│   ├── scripts: HTMLCollection                               // Collection of <script> elements
│   ├── scrollingElement: Element | null                      // Element that scrolls
│   ├── selectedStyleSheetSet: string | null                 // Currently selected stylesheet set
│   ├── styleSheets: StyleSheetList                           // List of stylesheets
│   ├── styleSheetSets: string                                // Collection of style sheet sets
│   ├── timeline: PerformanceTimeline                         // Performance timeline for the document
│   ├── title: string                                         // Title of the document
│   ├── URL: string                                          // Document URL
│   ├── visibilityState: string                               // Current visibility state of the document
│   ├── vlinkColor: string                                    // Color of visited links
│   ├── xmlEncoding: string | null                           // XML encoding of the document
│   └── xmlVersion: string | null                            // XML version of the document
├── Methods
│   ├── adoptNode(node: Node): Node                          // Adopts a node from another document
│   ├── append(...nodes: Node[]): void                       // Appends nodes to the document
│   ├── browsingTopics(): string[]                            // Experimental method for browsing topics
│   ├── caretPositionFromPoint(x: number, y: number): CaretPosition | null  // Gets caret position from point
│   ├── caretRangeFromPoint(x: number, y: number): Range | null  // Gets caret range from point
│   ├── clear(): void                                         // Clears the document (deprecated)
│   ├── close(): void                                        // Closes the document for writing
│   ├── createAttribute(name: string): Attr                  // Creates a new attribute
│   ├── createAttributeNS(namespace: string, name: string): Attr  // Creates an attribute in a namespace
│   ├── createCDATASection(data: string): CDATASection       // Creates a CDATA section
│   ├── createComment(data: string): Comment                 // Creates a comment node
│   ├── createDocumentFragment(): DocumentFragment           // Creates a lightweight document fragment
│   ├── createElement(tagName: string): HTMLElement           // Creates a new element
│   ├── createElementNS(namespace: string, qualifiedName: string): Element  // Creates an element in a namespace
│   ├── createEvent(eventType: string): Event                // Creates a new event
│   ├── createExpression(expr: string, resolver: XPathNSResolver | null): XPathExpression  // Creates an XPath expression
│   ├── createNodeIterator(root: Node, whatToShow?: number, filter?: NodeFilter | null, entityReferenceExpansion?: boolean): NodeIterator  // Creates a node iterator
│   ├── createNSResolver(node: Node): XPathNSResolver        // Creates a namespace resolver
│   ├── createProcessingInstruction(target: string, data: string): ProcessingInstruction  // Creates a processing instruction
│   ├── createRange(): Range                                  // Creates a new range object
│   ├── createTextNode(data: string): Text                   // Creates a text node
│   ├── createTouch(touch: Touch): Touch                      // Creates a touch object (non-standard)
│   ├── createTouchList(touches: Touch[]): TouchList         // Creates a list of touches (non-standard)
│   ├── createTreeWalker(root: Node, whatToShow?: number, filter?: NodeFilter | null, entityReferenceExpansion?: boolean): TreeWalker  // Creates a tree walker
│   ├── elementFromPoint(x: number, y: number): Element | null  // Gets the element at specified coordinates
│   ├── elementsFromPoint(x: number, y: number): Element[]  // Gets all elements at specified coordinates
│   ├── enableStyleSheetsForSet(styleSheetSet: string): void  // Enables stylesheets for a specific set
│   ├── evaluate(expression: string, contextNode: Node, resolver: XPathNSResolver | null, type?: number, result: XPathResult | null): XPathResult  // Evaluates an XPath expression
│   ├── execCommand(command: string, showUI?: boolean, value?: string): boolean  // Executes a command
│   ├── exitFullscreen(): Promise<void>                       // Exits fullscreen mode
│   ├── exitPictureInPicture(): void                          // Exits Picture-in-Picture mode
│   ├── exitPointerLock(): void                               // Exits pointer lock mode
│   ├── getAnimations(): Animation[]                           // Gets all animations in the document
│   ├── getElementById(id: string): Element | null           // Gets an element by its ID
│   ├── getElementsByClassName(classNames: string): HTMLCollection  // Gets elements by their class name
│   ├── getElementsByName(name: string): NodeList            // Gets elements by their name attribute
│   ├── getElementsByTagName(tagName: string): HTMLCollection  // Gets elements by their tag name
│   ├── getElementsByTagNameNS(namespace: string, localName: string): NodeList  // Gets elements by their tag name in a namespace
│   ├── getSelection(): Selection                              // Gets the current selection
│   ├── hasFocus(): boolean                                    // Checks if the document has focus
│   ├── hasStorageAccess(): Promise<boolean>                  // Checks for storage access
│   ├── hasUnpartitionedCookieAccess(): Promise<boolean>      // Checks for unpartitioned cookie access
│   ├── importNode(node: Node, deep?: boolean): Node         // Imports a node from another document
│   ├── mozSetImageElement(imageElement: HTMLImageElement): void  // Sets an image element (non-standard)
│   ├── open(url?: string, name?: string, features?: string): Window | null  // Opens a new window
│   ├── prepend(...nodes: Node[]): void                       // Prepends nodes to the document
│   ├── queryCommandEnabled(command: string): boolean         // Checks if a command is enabled (non-standard)
│   ├── queryCommandState(command: string): boolean           // Checks the state of a command (non-standard)
│   ├── queryCommandSupported(command: string): boolean       // Checks if a command is supported (non-standard)
│   ├── querySelector(selectors: string): Element | null      // Gets the first element matching the selectors
│   ├── querySelectorAll(selectors: string): NodeList        // Gets all elements matching the selectors
│   ├── releaseCapture(): void                                 // Releases pointer capture (non-standard)
│   ├── replaceChildren(...nodes: Node[]): void               // Replaces children of the document
│   ├── requestStorageAccess(): Promise<void>                 // Requests access to storage
│   ├── requestStorageAccessFor(element: Element): Promise<void>  // Requests storage access for a specific element
│   ├── startViewTransition(): Promise<void>                  // Starts a view transition
│   ├── write(data: string): void                              // Writes data to the document
│   └── writeln(data: string): void                            // Writes a line of data to the document
└── Events
    ├── afterscriptexecute            // Fired after a script has executed
    ├── beforescriptexecute            // Fired before a script executes
    ├── copy                            // Fired when content is copied
    ├── cut                             // Fired when content is cut
    ├── DOMContentLoaded                // Fired when the initial HTML document has been completely loaded
    ├── fullscreenchange                 // Fired when the fullscreen state changes
    ├── fullscreenerror                  // Fired when an error occurs while entering/exiting fullscreen
    ├── paste                            // Fired when content is pasted
    ├── pointerlockchange                // Fired when the pointer lock state changes
    ├── pointerlockerror                 // Fired when a pointer lock error occurs
    ├── prerenderingchange               // Fired when the prerendering state changes
    ├── readystatechange                  // Fired when the document's ready state changes
    ├── scroll                           // Fired when the document is scrolled
    ├── scrollend                        // Fired when scrolling ends
    ├── securitypolicyviolation          // Fired when a security policy violation occurs
    ├── selectionchange                  // Fired when the selection changes
    └── visibilitychange                 // Fired when the visibility state changes



```