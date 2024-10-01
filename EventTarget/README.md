```js

EventTarget
├── Methods
│   ├── addEventListener(type: string, listener: EventListener, options?: boolean | AddEventListenerOptions): void
│   │    // Registers an event listener for the specified event type
│   ├── removeEventListener(type: string, listener: EventListener, options?: boolean | EventListenerOptions): void
│   │    // Removes an event listener that was previously registered
│   ├── dispatchEvent(event: Event): boolean
│   │    // Dispatches an event to the registered event listeners

```