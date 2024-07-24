# Carbon Helix Theme

This is a theme for the [Helix](https://helix-editor.com/) text-editor that is inspired by
the [Carbon Design System](https://carbondesignsystem.com/).

## Installation

Copy the `carbon.toml` file into the `themes` directory of your helix config. If the themes
directory doesn't exist create one with `mkdir -p ~/.config/helix/themes` and move the 
`carbon.toml` file to the directory.

In your helix config add
```toml
theme = "carbon"
```

### Variants
Based on some feedback I also created a non-italics version of the theme as it over-emphasizes
things. I personally like italics a lot but for folks who don't want the italics, you can use
the `carbon_dev` theme instead. Installation procedure is same as above, use the `carbon_dev.toml`
file instead of `carbon.toml`

## Screenshot
Below are a few screenshots for Python, Lua and svelte.

### Python
![python](screenshot-python.png)

### Lua
![Lua](screenshot-lua.png)

### Svelte
![svelte](screenshot-svelte.png)
