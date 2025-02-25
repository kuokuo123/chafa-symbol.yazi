# chafa-symbol.yazi

A yazi plugin to deliberately preview images with chafa symbols. Yazi's image previewer cannot fallback to chafa properly in some use cases. For example, when running with alacritty and sway, only ueberzugpp is allowed to be image previewer.

## installation

```
ya pack --add kuokuo123/chafa-symbol
```

## setup

Append the below block to ~/.config/yazi/init.lua

```
[[plugin.prepend_previewers]]
mime = "image/*"
run = "chafa-symbol"
```
