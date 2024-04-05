# CSS-in-JS Autoprefixer

A simple utility to automatically add vendor prefixes to CSS properties in JavaScript styling solutions.

## Installation

```bash
npm install autoprefixer-css-js
```

## Usage

Import the `autoprefix_with_styles` function and use it to add prefixes to your style objects.

```javascript
import autoprefix_with_styles from 'css-in-js-autoprefixer';

const userStyles = {
  transition: 'all 0.3s ease',
  userSelect: 'none',
  boxSizing: 'border-box',
};

const prefixedStyles = autoprefix_with_styles(userStyles);
```

## Features

- Supports common CSS properties that require vendor prefixes.
- Easy to use with any CSS-in-JS library.

## Contributing

Contributions are welcome! Please feel free to submit a pull request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.
