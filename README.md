# scientific_web_components

A collection of reusable web components designed to simplify the development of scientific and data-focused web applications. These components prioritize accessibility, performance, and flexibility.

## Features
- **Reusable components**: Integrate components into various projects easily.
- **Customizable styles and functionality**: Customise your components to meet specific design of your choice.
- **Accessibility**: Built with accessibility standards to ensure cooperation with most of the frameworks.

## Prerequisites

- **Node.js** v14 or higher
- **npm** v6 or higher

## Installation

you can clone this repository with command:

```
git clone https://github.com/Snowskii/scientific_web_components.git
```

After cloning, install the necessary dependencies:

```
npm i
```

## Usage

Each component is designed to be plug-and-play. Here is a quick example to integrate a component in HTML:

```
<script type="module">
    import { ScientificSlider } from 'scientific_web_components';
</script>
```

## Development

While you develop, you can use these useful scripts:

### Build your code for production.

```
npm run build
```

If you want the compiler to always build after some changes you can use:

```
npm run build:watch
```

This is useful for active development.

### Start a local server for manual testing purposes.

```
npm run serve
```

### Run unit tests.

```
npm test
```

### Check your code for style and syntax errors.

```
npm run lint
```

## Contributing
1. Fork the repository.
2. Create a new branch: git checkout -b feature-name.
3. Commit your changes: git commit -am 'Add new feature'.
4. Push to the branch: git push origin feature-name.
5. Submit a pull request.

---

Adjust any sections according to the exact details of your repository! If you have specific components or features in mind, I can further personalize this README template.