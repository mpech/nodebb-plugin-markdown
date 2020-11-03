# NodeBB Markdown Parser + katex

[original is from julianm](https://github.com/julianlam/nodebb-plugin-markdown)

Here, katex is added

This repo implements

- what's specified in [this post](https://community.nodebb.org/topic/14141/proper-way-to-add-latex-with-markdown-it-texmath-and-katex-to-nodebb-plugin-markdown)
- the support for the svg square root


## Installation

Install the plugin

    npm install nodebb-plugin-markdown-katex

Disable ```nodebb-plugin-markdown``` from administration panel (and check this one is active)

## Delivering

If uping katex remember to copy

- ```node_modules/katex/dist/katex.min.css``` to ```thisPlugin/public/less/katex.min.less```
- ```node_modules/katex/dist/fonts``` to ```thisPlugin/public/fonts```
