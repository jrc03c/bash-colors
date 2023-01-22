# Intro

`bash-colors` is a little package for Node for printing text in colors. It's like [`chalk`](https://github.com/chalk/chalk), only less well-made.

# Installation

```bash
npm install --save @jrc03c/bash-colors
```

# Usage

```js
const color = require("@jrc03c/bash-colors")
console.log(color.fg.red("Hello, world!"))
```

# API

All of the following are callable as functions that take a single string argument and return that argument wrapped in [Bash color codes](https://gist.github.com/jrc03c/f7a05f2e14876707f5f78f280856da90). You'll usually want to `console.log` the return value.

**Text modifications:**

```
color.mods.reset
color.mods.bright
color.mods.dim
color.mods.underscore
color.mods.blink
color.mods.reverse
color.mods.hidden
```

**Foreground colors:**

```
color.fg.black
color.fg.red
color.fg.green
color.fg.yellow
color.fg.blue
color.fg.magenta
color.fg.cyan
color.fg.white
```

**Background colors:**

```
color.bg.black
color.bg.red
color.bg.green
color.bg.yellow
color.bg.blue
color.bg.magenta
color.bg.cyan
color.bg.white
```
