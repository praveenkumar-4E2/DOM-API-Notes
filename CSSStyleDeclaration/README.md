```js

CSSStyleDeclaration
├── Properties
│   ├── length: number                                         // The number of CSS properties in the declaration
│   ├── [index: number]: string                               // Accesses a CSS property by its index
│   ├── cssText: string                                       // The CSS text of the style declaration
│   ├── display: string                                       // The display property
│   ├── color: string                                         // The color property
│   ├── backgroundColor: string                               // The background color property
│   ├── fontSize: string                                      // The font size property
│   ├── [propertyName: string]: string                       // Accesses a CSS property by its name
│
├── Methods
│   ├── getPropertyValue(property: string): string           // Returns the value of the specified CSS property
│   ├── setProperty(property: string, value: string, priority?: string): void // Sets a CSS property to a specified value
│   ├── removeProperty(property: string): string             // Removes a specified CSS property
│   ├── item(index: number): string                           // Returns the CSS property name at the specified index

```