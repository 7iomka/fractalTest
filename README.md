# I use "24 ways front-end component library" which is based on fractal

> **Note:** This project is in the early stages of (re-)development

## Requirements
This project is built upon [Fractal](https://github.com/frctl/fractal), a tool that enables the rapid development of components, templates and pages. Fractal uses a number of ES6 features, so this project requires [Node.js](https://nodejs.org/) v4.0+ to be installed locally. A global install of Gulp is also recommended.

## Installation
To get the project up and running, and view components in the browser, complete the following steps:

1. Download and install Node: <https://nodejs.org/>
2. Clone this repo: `git clone git@github.com/7iomka/fractalTest.git`
3. [Optional] Install Gulp globally: `npm install gulp -g`
4. [Optional] Install Fractal globally: `npm install fractal -g`
5. Install project dependancies: `npm install`
6. Start the development environment (for test problem): `npm run dev`
7. Open your browser and visit <http://localhost:3000>

## Development
When developing components, you may want assets automatically compiled and the browser to refresh automatically. To do this, run the following task:

* `npm run dev`


## Repo structure
Sometimes it’s helpful to know what all these different files are for…

```
/
├─ src/
│  ├─ assets/        # Static…
│  │  ├─ icons/      # Favicon and home screen icons
│  │  ├─ images/     # Raster images (used in component examples)
│  │  ├─ scripts/    # JavaScript files
│  │  ├─ styles/     # CSS files
│  │  └─ vectors/    # SVG images, icons and logos
|  |
│  ├─ components/    # Components…
│  │  ├─ _macros/    # Macros
│  │  ├─ common/     # Common components
│  │  └─ …           
|  |
│  └─ docs/          # Project documentation
│
├─ tmp/              # Files required for dynamic builds (ignored by Git)
├─ www/              # Public build (ignored by Git)
│
├─ .editorconfig     # Code style definitions
├─ .gitignore        # List of files and folders not tracked by Git
├─ .stylelintrc      # Linting preferences for CSS
├─ LICENSE           # License information for this project
├─ fractal.js        # Configuration for Fractal
├─ gulpfile.js       # Configuration for Gulp tasks
├─ webpack.config.js # Configuration for Webpack js build
├─ package.json      # Project manifest
└─ README.md         # This file
```
