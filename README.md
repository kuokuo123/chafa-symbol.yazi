# chafa-symbol.yazi

A yazi plugin to deliberately preview images with chafa symbols. Yazi's image previewer cannot fallback to chafa properly in some use cases. For example, when running with alacritty and sway, only ueberzugpp preview is allowed.

## Installation

```
ya pack --add kuokuo123/chafa-symbol
```

## Usage

Append the below block to ~/.config/yazi/yazi.toml

```
[[plugin.prepend_previewers]]
mime = "image/*"
run = "chafa-symbol"
```
