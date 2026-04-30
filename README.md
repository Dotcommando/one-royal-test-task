# A Client Portal

Front-End test task.

## Requirements

0. Do not use AI.
1. Create a single responsive HTML page.
2. In the `body`, there must be only one root element.
3. The ES6+ code must be placed at the end of the `body`.
4. No external libraries are allowed, except the one mentioned below.
5. All elements inside the root element must be created dynamically by code.
6. Light and dark styles must be supported.
7. SVG icons must be used.

## Conventions

### Naming

1. Element IDs should use snake_case:

```html
id="an_element_id"
```

2. CSS classes should use kebab-case:

```html
class="a-class-name"
```

3. Variables should use camelCase:

```js
let variableName
```

4. Functions should follow this style:

```js
const functionName = async (argumentName) => {
  const someData = await getSomeData(argumentName)
  return someData
}
```

## Task

1. Create a mobile-first user interface for the Client Portal.
2. Show the login form at the start.

Credentials:

```txt
login: testLogin
password: testPassword
```

3. Until the user logs out, page reloads should not show the login form.
4. Add the main left side menu with the following items:

- Profile
- Accounts
- Terminal

5. Add the top header navbar with the following elements:

- Logo
- Client Name
- LogOut

6. Clicking the left menu items should show the related content.
7. Terminal: use the free TradingView charting library and load it only when needed.
8. Emulate historical and real-time data to show daily candles and the current price.

## Plus

Not required, but appreciated:

- Perfect design of each element.
- Smooth and fast animations where possible.
- Ability to change the instrument in the terminal.
- Any other improvements that can make the result better.
