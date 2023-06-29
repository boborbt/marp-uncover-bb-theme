# marp-uncover-bb-theme

Slide theme for the Marp presentation ecosystem.

This theme is a modified version of the original `uncover` theme that is distributed with the [Marp](https://marp.app/) presentation ecosystem.

## Files provided

This repository consists of only two files:

- theme.scss: this it the main source for your theme, any change should be made to this file
- theme.css: this is the output of compiling the theme using sass. It is provided for convenience for anybody that would like to use the theme as is.

## How to generate theme.css

Generating `theme.css` is very easy (it requires [sass](https://sass-lang.com/)):

```bash
sass --no-source-map theme.scss theme.css
```





