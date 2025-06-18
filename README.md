# 🚀 Website Template Starter

<div align="center">

![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)
![SCSS](https://img.shields.io/badge/SCSS-FF69B4.svg?logo=sass&logoColor=white)
![Responsive](https://img.shields.io/badge/responsive-✓-brightgreen.svg)

*Ready-to-use website template with modern SCSS architecture*

[Demo](#demo) • [Quick Start](#-quick-start) • [Documentation](#-documentation) • [Contributing](#-contributing)

</div>

---

## ✨ Features

- 🎨 **Modern SCSS Architecture** - Clean, organized stylesheet structure
- 📱 **Responsive Design** - Fluid typography and adaptive layouts
- ⚡ **Fast Setup** - Get started in minutes, not hours
- 🔧 **Highly Customizable** - Easy to adapt to any design
- 📐 **Fluid Typography System** - Automatic font scaling across devices
- 🎯 **Developer Friendly** - Clear workflow and documentation

## 🚀 Quick Start

```bash
# Clone the repository
git clone https://github.com/mlndlrdp/web-site-template.git

# Navigate to project directory
cd web-site-template

# Initialize npm project (creates package.json)
npm init -y

# Install SCSS compiler
npm install -g sass

# Start development
npm run sass-watch
```

## 📋 Setup Guide

Follow these steps to customize the template for your project:

### Step 1: 🎬 Setup SCSS Compilation
First, initialize your npm project and install SCSS:

```bash
# Initialize npm project
npm init -y

# Install SCSS compiler globally
npm install -g sass
```

Then add the SCSS watch command to your `package.json` file:

Open `package.json` and add this line to the `"scripts"` section:
```json
{
  "scripts": {
    "sass-watch": "sass --watch ."
  }
}
```

Now start the SCSS watcher to automatically compile your styles:
```bash
npm run sass-watch
```

### Step 2: 📏 Configure Fluid Typography
- Open your design mockup/Figma
- Find the minimum and maximum viewport widths from your design
- Update the fluid-text function parameters in `styles/helpers/_functions.scss`

### Step 3: 📱 Set Media Query Breakpoints
- Analyze your design's responsive breakpoints
- Define your media query ranges in `styles/helpers/_media.scss`
- Set up breakpoint variables based on your mockup

### Step 4: 🎨 Define Design Variables
Configure your project's design tokens in `styles/helpers/_variables.scss`:
- **Colors**: Extract color palette from your design
- **Typography**: Set font families from your mockup
- **Layout**: Define container width and padding from design specs

### Step 5: 🌐 Add Global Styles
- Set up base styles in `styles/helpers/_globals.scss`
- Configure global elements that apply across your entire site
- Add any custom global behaviors you need

### Step 6: ✏️ Style Typography
Configure body and heading styles in `styles/helpers/_globals.scss`:
- **Body**: Set font-family, use fluid-text mixin for font-size, letter-spacing, and color
- **Headings**: Style each heading tag (h1-h6) and their corresponding classes
- Use the fluid-text mixin for responsive font sizes
- Set appropriate font-weights and colors for each heading level

## 🏗️ Project Structure

```
web-site-template/
├── 📁 fonts/                   # Web fonts
├── 📁 icons/                   # Icon assets
├── 📁 images/                  # Image assets
├── 📁 scripts/
│   └── main.js                 # JavaScript functionality
├── 📁 styles/
│   ├── 📁 blocks/              # Component/block styles
│   └── 📁 helpers/
│       ├── _functions.scss     # Fluid typography functions (Step 2)
│       ├── _index.scss         # Helper imports
│       ├── _media.scss         # Media queries (Step 3)
│       ├── _mixins.scss        # SCSS mixins
│       ├── _fonts.scss         # Font declarations
│       ├── _globals.scss       # Global styles (Step 5)
│       ├── _normalize.scss     # CSS normalize
│       ├── _utils.scss         # Utility classes
│       └── _variables.scss     # Design variables (Step 4)
│   └── main.scss               # Main SCSS entry point
├── index.html                  # Main HTML file
├── package.json                # NPM dependencies
└── package-lock.json           # Dependency lock file
```

## 🛠️ Available Commands

Before you start, make sure to add the SCSS compilation script to your `package.json`:

```json
{
  "scripts": {
    "sass-watch": "sass --watch ."
  }
}
```

| Command | Description |
|---------|-------------|
| `npm run sass-watch` | Watch and auto-compile SCSS files during development |

## 💡 Key Benefits

### ⚡ Fast Development
No need to set up the same boilerplate code for every new project. Everything is ready to go.

### 🎯 Design-Driven Workflow
The setup process is designed to work directly with your design mockups - just extract the values and plug them in.

### 📱 Automatic Responsiveness
The fluid typography system automatically creates smooth scaling between your design breakpoints.

### 🔄 Reusable
Once configured, the template provides a solid foundation that can be extended for any type of website.

## 🎨 What You'll Customize

- **Design Values**: Colors, fonts, spacing from your mockup
- **Typography Scale**: Responsive font sizes for all text elements  
- **Breakpoints**: Media query ranges matching your design
- **Layout**: Container widths and spacing based on your grid
- **Components**: Add your specific UI components as needed

## 📱 Browser Support

- ✅ All modern browsers
- ✅ Mobile devices
- ✅ Tablet devices
- ✅ Desktop screens

## 🤝 Contributing

Feel free to submit issues and enhancement requests!

## 📄 License

MIT License - feel free to use in personal and commercial projects.

---

<div align="center">

**Save time on every new project with this flexible starter template**

[⭐ Star this repo](https://github.com/mlndlrdp/web-site-template) if it helps you build faster!

</div>
