# chafa-symbol.yazi

A yazi plugin to preview images using chafa symbols. Yazi's image previewer cannot fallback to chafa properly in some use cases, which is no good to ascii art lovers. This plugin serves as a workaround.

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
