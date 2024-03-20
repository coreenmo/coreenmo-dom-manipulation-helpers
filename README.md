## 💾 Requirements

- `Web Browser` - Can be used as an emulator to build applications. Example [Chrome, Firefox, Safari & Opera].
- `Internet` - Because many use CDN and to make it easier to find solutions to all problems.

## 🎯 How To Use

#### Example Syntax

```javascript
// Import the functions
const {
  addClass,
  removeClass,
  toggleClass,
} = require("./src/domManipulationHelpers");

// Example usage
const element = document.getElementById("myElement");

// Add a class
addClass(element, "highlight");

// Remove a class
removeClass(element, "highlight");

// Toggle a class
toggleClass(element, "active");
```

#### Explanation

- `addClass(element, className)`: Adds a CSS class to the specified element.
- `removeClass(element, className)`: Removes a CSS class from the specified element.
- `toggleClass(element, className)`: Toggles a CSS class on the specified element.

#### Return Value

- All functions do not return any value. They directly manipulate the DOM.
