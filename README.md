# Restaurant Page

A dynamic restaurant website built with vanilla JavaScript and bundled with Webpack. This project demonstrates DOM manipulation, modular JavaScript, and modern build tools.

## 🌟 Features

- **Dynamic Content Loading**: All page content is generated using JavaScript
- **Multi-Page Navigation**: Home, Menu, and Contact pages without page reloads
- **Responsive Design**: Clean, modern interface that works across devices
- **Modular Architecture**: Organized code structure with separate modules for each page
- **Webpack Bundle**: Optimized assets and code bundling for production

## 🛠️ Technologies Used

- **JavaScript (ES6+)**: Core functionality and DOM manipulation
- **HTML5 & CSS3**: Structure and styling
- **Webpack**: Module bundling and asset management
- **Git & GitHub**: Version control and deployment

## 📂 Project Structure

```
Odin_Project_Restaurant_Page/
├── src/
│   ├── index.js          # Entry point and navigation logic
│   ├── home.js           # Home page module
│   ├── menu.js           # Menu page module
│   ├── contact.js        # Contact page module
│   ├── style.css         # Styles
│   ├── template.html     # HTML template
│   └── images/           # Restaurant and food images
├── dist/                 # Compiled/bundled files (generated)
├── webpack.config.js     # Webpack configuration
└── package.json          # Project dependencies

```

## 🚀 Getting Started

### Prerequisites

- Node.js and npm installed on your machine

### Installation

1. Clone the repository:
```bash
git clone https://github.com/Sammorad/Odin_Project_Restaurant_Page.git
cd Odin_Project_Restaurant_Page
```

2. Install dependencies:
```bash
npm install
```

3. Run webpack to build the project:
```bash
npx webpack
```

4. Open `dist/index.html` in your browser to view the site

### Development

For development with automatic rebuilding:
```bash
npx webpack --watch
```

## 🌐 Live Demo

Visit the live site: [Restaurant Page](https://sammorad.github.io/Odin_Project_Restaurant_Page/)

## 📦 Deployment

This project is deployed to GitHub Pages. To deploy updates:

1. Ensure all changes are committed
2. Switch to gh-pages branch and merge main:
```bash
git checkout gh-pages && git merge main --no-edit
```

3. Build the project:
```bash
npx webpack
```

4. Deploy using git subtree:
```bash
git add dist -f && git commit -m "Deployment commit"
git subtree push --prefix dist origin gh-pages
git checkout main
```

## 📝 About This Project

This project is part of [The Odin Project](https://www.theodinproject.com/) curriculum, focusing on:
- Using JavaScript to dynamically render page content
- Working with ES6 modules
- Setting up and configuring Webpack
- Organizing code into reusable modules

## 👨‍💻 Author

**Sammorad**
- GitHub: [@Sammorad](https://github.com/Sammorad)

## 📄 License

This project is open source and available for educational purposes.

---

*Built as part of The Odin Project's Full Stack JavaScript curriculum*
