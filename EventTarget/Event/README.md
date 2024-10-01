```js

Event
├── Constructor
│   └── Event(type: string, eventInitDict?: EventInit): Event  // Creates a new event
│
├── Properties
│   ├── bubbles: boolean                                       // Whether the event bubbles up through the DOM
│   ├── cancelable: boolean                                    // Whether the event is cancelable
│   ├── composed: boolean                                      // Whether the event propagates across the shadow DOM
│   ├── currentTarget: EventTarget                             // The target actively processing the event
│   ├── defaultPrevented: boolean                              // Whether the default action is prevented
│   ├── eventPhase: number                                     // The current phase of the event flow (capturing, target, or bubbling)
│   ├── isTrusted: boolean                                     // Whether the event is trusted (triggered by a user action)
│   ├── target: EventTarget                                    // The target to which the event is dispatched
│   ├── timeStamp: number                                      // The timestamp when the event was created
│   ├── type: string                                           // The name of the event
│
├── Methods
│   ├── composedPath(): EventTarget[]                          // Returns the path through which the event is propagated
│   ├── initEvent(type: string, bubbles?: boolean, cancelable?: boolean): void  // Initializes an event (deprecated)
│   ├── preventDefault(): void                                 // Cancels the event’s default action
│   ├── stopImmediatePropagation(): void                       // Stops further listeners of the same event from being called
│   ├── stopPropagation(): void                                // Stops the event from bubbling up through the DOM
│
├── Static Methods
│   └── NONE                                                   // Represents an event with no significant meaning (used for constants)
│
└── Event Phases
    ├── CAPTURING_PHASE: 1                                     // Event is in the capturing phase
    ├── AT_TARGET: 2                                           // Event is at the target phase
    └── BUBBLING_PHASE: 3                                      // Event is in the bubbling phase

```