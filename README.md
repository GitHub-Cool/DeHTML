# DeHTML - A starter HTML Template using Pug, Sass, Webpack, Gulp.

Start to build your next web page without extra configuration.

简单拼凑了下 Gulp 和 Webpack 的功能，开箱即用，无需多余配置...其实是配置简陋，请自行丰富 🤪。

## Quick Start

```bash
# copy to your local environment
git clone https://github.com/DezineLeo/DeHTML.git

# install dependencies
yarn install

# start dev
yarn dev
```

## Gulp Configration

+ Generate `*.pug` files
+ Concat vendor CSS into a single `plugins.min.css`
+ Concat vendor JS into a single `plugins.min.js`
+ Using Webpack 4 and Babel 7 to output `app.js`
+ HTML beautify enabled
+ Minimize images
+ Using **Browsersync**