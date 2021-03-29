# A minimalist theme

A minimalist theme for [Hexo](http://hexo.io/) based on the [Apollo](https://github.com/pinggod/hexo-theme-apollo) and [artemis](https://github.com/Dreyer/hexo-theme-artemis).

Without tags, comments, 3rd JS, fonts. Hight load speed, and simple interface.

## Installation

```
npm i --save hexo-renderer-pug hexo-renderer-sass
git clone https://github.com/Mirtlez/hexo-theme-Simple.git themes/Simple
```
Modify `theme` setting in `_config.yml` to `Simple`.

If you don't want to generate tags & category pages, run `npm uninstall hexo-generator-category hexo-generator-tags`

## CSS

Modify files in `\source\scss\_partial` to change css.

After finished, `hexo g` to generate theme.css and put it into 📂source/scss/. Then delete 📂theme/Simple/scss.

## Credits

This theme is largely based on the efforts of  [Apollo](https://github.com/pinggod/hexo-theme-apollo) and [artemis](https://github.com/Dreyer/hexo-theme-artemis).
