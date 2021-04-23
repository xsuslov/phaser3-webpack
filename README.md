# Phaser 3 Webpack Bundle

### Installation

```
npm install
```

### Start Dev Server

```
npm start
```

### Build Prod Version

```
npm run build
```

### Features:

* ES6 Support via [babel](https://babeljs.io/) (v7)
* SASS Support via [sass-loader](https://github.com/jtangelder/sass-loader)
* Linting via [eslint-loader](https://github.com/MoOx/eslint-loader)
* Phaser via [phaser](https://github.com/photonstorm/phaser)
* Phaser Matter Collision Plugin via [phaser-matter-collision-plugin](https://github.com/mikewesthad/phaser-matter-collision-plugin)

When you run `npm run build` we use the [mini-css-extract-plugin](https://github.com/webpack-contrib/mini-css-extract-plugin) to move the css to a separate file. The css file gets included in the head of the `index.html`.
