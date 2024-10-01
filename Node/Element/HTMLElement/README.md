```js

HTMLElement
├── Properties
│   ├── accessKey: string                                  // The access key assigned to the element
│   ├── accessKeyLabel: string                             // The label of the access key
│   ├── contentEditable: string                            // Whether the element's content is editable
│   ├── dataset: DOMStringMap                              // Provides access to custom data attributes (data-*)
│   ├── dir: string                                        // Text direction of the element
│   ├── draggable: boolean                                 // Whether the element is draggable
│   ├── hidden: boolean                                    // Whether the element is hidden
│   ├── inert: boolean                                     // Prevents interaction with the element
│   ├── innerText: string                                  // The rendered text content of the element
│   ├── isContentEditable: boolean                         // Indicates whether the content is editable
│   ├── lang: string                                       // Language of the element's content
│   ├── nonce: string                                      // Cryptographic nonce for inline scripts
│   ├── offsetHeight: number                               // Element's height including padding, border, and scroll bar
│   ├── offsetLeft: number                                 // Distance of the element's left border relative to the offset parent
│   ├── offsetParent: Element | null                       // The element's offset container
│   ├── offsetTop: number                                  // Distance of the element's top border relative to the offset parent
│   ├── offsetWidth: number                                // Element's width including padding, border, and scroll bar
│   ├── spellcheck: boolean                                // Whether spellchecking is enabled for the element
│   ├── style: CSSStyleDeclaration                         // Inline styles applied to the element
│   ├── tabIndex: number                                   // The tab order of the element
│   ├── title: string                                      // The title of the element
│   ├── translate: boolean                                 // Whether to translate the element's content
├── Methods
│   ├── click(): void                                      // Simulates a click on the element
│   ├── focus(options?: FocusOptions): void                // Sets focus on the element
│   ├── blur(): void                                       // Removes focus from the element
│   ├── forceSpellCheck(): void                            // Forces a spell check on the element
├── Events
│   ├── blur                                               // Fired when the element loses focus
│   ├── click                                              // Fired when the element is clicked
│   ├── focus                                              // Fired when the element receives focus
│   ├── focusin                                            // Fired when the element is focused, before focus event
│   ├── focusout                                           // Fired when the element loses focus, before blur event
│   ├── fullscreenchange                                   // Fired when the element enters/exits fullscreen
│   ├── fullscreenerror                                    // Fired when an error occurs with fullscreen
│   ├── keydown                                            // Fired when a key is pressed down while the element is focused
│   ├── keypress                                           // Fired when a key is pressed while the element is focused (deprecated)
│   ├── keyup                                              // Fired when a key is released while the element is focused
│   ├── mousedown                                          // Fired when a mouse button is pressed on the element
│   ├── mouseup                                            // Fired when a mouse button is released on the element
│   ├── pointerdown                                        // Fired when a pointer is pressed on the element
│   ├── pointerup                                          // Fired when a pointer is released on the element
│   ├── scroll                                             // Fired when the element is scrolled
│   ├── touchstart                                         // Fired when a touch point is placed on the element
│   ├── touchend                                           // Fired when a touch point is removed from the element
│   └── touchmove                                          // Fired when a touch point is moved along the element



```