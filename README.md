# Project Template

This repository serves as a project template for starting new JavaScript projects. It includes essential configuration files for linting, formatting, and managing code quality.

## Files Included

- **`package.json`**: Manages project dependencies and task runner scripts.
- **`.eslintrc.json`**: ESLint configuration for enforcing consistent JavaScript style.
- **`.editorconfig`**: Defines coding styles (e.g., indentation, line breaks) across different editors.
- **`.stylelintrc.json`**: Configuration for StyleLint, ensuring CSS/SCSS code consistency.

## Usage

1. Clone this repository for a new project.
2. Customize task runner and dependencies as needed for your specific project.

## Installation

Run the following to install project dependencies:

```bash
npm install

```

## Getting Started

1. Clone the repository
2. Install dependencies:
```bash
npm install
```

3. Start development server:
```bash
npm run watch
```

## Development

The project uses:
- SASS for CSS preprocessing
- Browser-sync for live reloading
- npm scripts for task automation

Available commands:
- `npm run watch` - Start development server with live reload
- `npm run build` - Build production version
- `npm test` - Run tests

## Building

To build for production:
```bash
npm run build
```

This will:
- Compile SASS to CSS
- Minify CSS
- Add vendor prefixes
- Optimize images
- Run tests

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Customization

To customize the portfolio:
1. Update personal information in index.html
2. Replace profile photo in images folder
3. Modify styles in SASS files
4. Update project screenshots and descriptions

## License

This project is licensed under the MIT License.

## Author

[Your Name]
- Website: [your-website]
- GitHub: [your-github]
- Email: [your-email]
