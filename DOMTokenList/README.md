
```js
DOMTokenList
├── Properties
│   ├── length: number                                         // The number of tokens in the list
│   ├── [index: number]: string                               // Accesses a token by its index
│
├── Methods
│   ├── add(...tokens: string[]): void                        // Adds one or more tokens to the list
│   ├── remove(...tokens: string[]): void                     // Removes one or more tokens from the list
│   ├── item(index: number): string | null                   // Returns the token at the specified index or null if out of range
│   ├── contains(token: string): boolean                      // Checks if the list contains the specified token
│   ├── toggle(token: string, force?: boolean): boolean      // Adds or removes a token based on its presence; returns true if added, false if removed
│   ├── replace(oldToken: string, newToken: string): boolean  // Replaces an existing token with a new token
│   ├── forEach(callback: (token: string, index?: number) => void): void // Executes a provided function once for each token
```