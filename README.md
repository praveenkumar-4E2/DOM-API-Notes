```js
DOM API
│
├── Node (Interface)
│   ├── Element (Interface)
│   │   ├── HTMLElement (Class)
│   │   ├── SVGElement (Class)
│   │   └── ShadowRoot (Interface) ─ inherits from DocumentFragment
│   ├── Document (Interface)
│   │   ├── HTMLDocument (Interface) ─ inherits from Document
│   │   ├── SVGDocument (Interface) ─ inherits from Document
│   │   └── DocumentFragment (Interface)
│   │       └── ShadowRoot (Interface)
│   ├── Text (Class)
│   ├── Comment (Class)
│   ├── DocumentType (Interface)
│   └── Attr (Interface)
│
├── EventTarget (Interface)
│   ├── Event (Class)
│   │   ├── CustomEvent (Class)
│   │   ├── UIEvent (Class)
│   │   │   ├── KeyboardEvent (Class)
│   │   │   ├── MouseEvent (Class)
│   │   │   │   └── PointerEvent (Class) ─ inherits from MouseEvent
│   │   │   ├── FocusEvent (Class)
│   │   │   └── TouchEvent (Class)
│   │   └── MutationEvent (Deprecated Class)
│   ├── MutationObserver (Class)
│   └── MutationRecord (Interface)
│
├── NamedNodeMap (Interface)
├── NodeList (Interface)
├── HTMLCollection (Interface)
├── Range (Interface)
├── CSSStyleDeclaration (Interface)
├── StyleSheet (Interface)
│   └── CSSStyleSheet (Interface) ─ inherits from StyleSheet
├── DOMTokenList (Interface)
├── DOMStringList (Interface)
├── DOMRect (Interface)
└── DOMMatrix (Interface)
```
