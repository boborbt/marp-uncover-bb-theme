# marp-uncover-bb-theme

Slide theme for the Marp presentation ecosystem.

This theme is a modified version of the original `uncover` theme that is distributed with the [Marp](https://marp.app/) presentation ecosystem.

## Files provided

The theme itself can be found in the themes folder:

- theme.scss: this it the main source for your theme, any change should be made to this file
- theme.css: this is the output of compiling the theme using sass. It is provided for convenience for anybody that would like to use the theme as is.

An example of its usage can be found in the examples folder.

## Requirements

- [sass](https://sass-lang.com/): only required if you plan to change the theme.
- BM Hanna Air font: the theme switches to Palatino if BM Hanna Air is not installed.

## How to generate theme.css


```bash
cd themes
sass --no-source-map theme.scss theme.css
```






