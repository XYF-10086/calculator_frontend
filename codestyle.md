# Code Style

This project follows the standards below:

- Google JavaScript Style Guide: https://google.github.io/styleguide/jsguide.html
- Airbnb JavaScript Style Guide: https://github.com/airbnb/javascript
- MDN Web Docs style guidance: https://developer.mozilla.org/

## Conventions

### Naming

- Variables and functions: lowerCamelCase, e.g. `loadHistory`, `calc`
- Constants: UPPER_SNAKE_CASE, e.g. `API`
- Class names: UpperCamelCase (not used in this project)

### Indentation

- Use 2 spaces

### Quotes

- Use double quotes `"` for JavaScript strings

### Semicolons

- End each statement with a semicolon `;`

### Functions

- Use `async / await` for asynchronous requests
- Function names should reflect their purpose, e.g. `calc`, `loadHistory`, `del`

### HTML

- Lowercase tag names
- Double quotes for attributes
- Clear structure and consistent indentation

### CSS

- Keep selectors simple
- One property per line, ending with a semicolon

### Security

- Use `textContent` to output results to avoid XSS
- Do not directly concatenate user input into HTML for execution