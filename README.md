# light.css v0.0.1

![light.css Logo](https://raw.githubusercontent.com/devsimsek/light.css/main/logo.png)

light.css is a minimalistic CSS framework designed to make web development faster and easier. It provides a set of predefined styles and variables that you can use to create beautiful and responsive web applications.

## Table of Contents

- [Getting Started](#getting-started)
- [Usage](#usage)
- [Customization](#customization)
- [Contributing](#contributing)
- [License](#license)

## Getting Started

To get started with light.css, you can include it in your project using the following CDN link:

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/devsimsek/light.css@0.0.1/dist/light.min.css">
```

Alternatively, you can download the CSS file from the [GitHub repository](https://github.com/devsimsek/light.css) and include it in your project manually.

## Usage

light.css provides a set of CSS classes that you can apply to your HTML elements to style them. Here are some of the commonly used classes:

- `.button`: Style buttons and clickable elements.
- `.container`: Create a container with margins and padding.
- `.text-primary`, `.text-secondary`, `.text-accent`, etc.: Apply text color classes.
- `.bg-primary`, `.bg-secondary`, `.bg-accent`, etc.: Apply background color classes.
- `.rounded`, `.rounded-small`, `.rounded-medium`, `.rounded-large`, etc.: Add border radius to elements.
- `.border`, `.border-primary`, `.border-secondary`, `.border-accent`, etc.: Add borders to elements.
- `.p-1`, `.p-2`, `.p-3`, etc.: Add padding to elements.
- `.m-1`, `.m-2`, `.m-3`, etc.: Add margins to elements.
- `.d-flex`, `.d-inline-flex`: Control the display property and flex behavior.
- `.justify-content-start`, `.justify-content-end`, `.justify-content-center`, etc.: Control horizontal alignment.
- `.align-items-start`, `.align-items-end`, `.align-items-center`, etc.: Control vertical alignment.
- `.flex-row`, `.flex-column`, `.flex-wrap`, etc.: Control flex layout.
- `.fixed`, `.fixed-top`, `.fixed-bottom`, `.fixed-left`, `.fixed-right`, `.fixed-center`: Create fixed or sticky elements.

For more details on how to use these classes, you can refer to the [official documentation](https://github.com/devsimsek/light.css).

## Customization

light.css uses CSS variables to define its colors, fonts, spacing, and more. You can easily customize the framework by overriding these variables in your own CSS file. Here are some of the variables you can customize:

- `--primary-color`: The primary color used for buttons and links.
- `--secondary-color`: The secondary color used for hover effects.
- `--background-color`: The background color of the page.
- `--base-font-family`: The base font family for text.
- `--base-font-size`: The base font size for text.
- `--spacing-unit`: The base spacing unit used for margins and padding.
- `--border-radius-small`, `--border-radius-medium`, `--border-radius-large`: Border radius values.
- `--box-shadow-small`, `--box-shadow-medium`, `--box-shadow-large`: Box shadow values.
- And many more...

Simply define these variables in your CSS file before including light.css, and your custom styles will take precedence.

```css
/* Example customizations */
:root {
    --primary-color: #ff5733;
    --secondary-color: #33ff57;
    --background-color: #f0f0f0;
    --base-font-size: 18px;
    --spacing-unit: 10px;
}
```

## Contributing

If you would like to contribute to light.css, please check out the [GitHub repository](https://github.com/devsimsek/light.css) for the latest code and guidelines.

## License

light.css is released under the [MIT License](https://github.com/devsimsek/light.css/blob/main/LICENSE). You are free to use, modify, and distribute this framework in your projects.

---

[GitHub Repository](https://github.com/devsimsek/light.css) | [Documentation](https://github.com/devsimsek/light.css) | [Report Issues](https://github.com/devsimsek/light.css/issues)
