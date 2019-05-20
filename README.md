## Bulma Theme Generator

This is a global CSS theme to be used in internal projects

To pull in required dependencies, run `npm install` in the root directory

Theme is built in SCSS and should be compiled to CSS using the `SASS` preprocessor
    `sass --watch assets/sass/main.scss:assets/css/main.css --style compressed` 

You can also use the `compile_css.sh` file included if running on a UNIX-like terminal

Once this is successful, you can check out the `examples` folder for examples of the color scheme in use and use it to tune any changes accordingly. The `color-palette.html` file is designed to display every main and derived color in this theme.

To change a color scheme, the only files that really need edits are `sass/variables/color-variables.scss` and `sass/variables/bulma-color-bindings.scss`