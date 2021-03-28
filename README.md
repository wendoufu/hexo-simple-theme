# A minimalist theme

A minimalist theme for [Hexo](http://hexo.io/) based on the [Apollo](https://github.com/pinggod/hexo-theme-apollo) and [artemis](https://github.com/Dreyer/hexo-theme-artemis).

With No tags, No comments, No 3rd JS, No fonts, high load speed, and simple interface.

## Installation

```
npm install --save hexo-renderer-pug hexo-renderer-sass
git clone https://github.com/Mirtlez/hexo-theme-Simple.git themes/Simple
```
Modify `theme` setting in `_config.yml` to `Simple`.

To avoid tags & category generated, run `npm uninstall hexo-generator-category hexo-generator-tags`

## CSS

Modify files in `\source\scss\_partial` to change css.

After done with your css, `hexo g` to generate theme.css and put it into 📂source/scss/, delete 📂theme/Simple/scss. This can speed up your generation.

## Credits

This theme is largely based on the efforts of  [Apollo](https://github.com/pinggod/hexo-theme-apollo) and [artemis](https://github.com/Dreyer/hexo-theme-artemis).
