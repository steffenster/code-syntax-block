
# Code Syntax Highlighting Block

A WordPress plugin which extends Gutenberg by adding syntax highlighting to the core code block.


Example:

<img src="screenshot.png" title="Screenshot example in use" alt="screen shot" width="554" height="202" style="border:1px solid #333"/>


### Usage

Install code-syntax-block plugin to your WordPress plugins directory and activate. You can download a zip from the  [releases page](https://github.com/mkaz/code-syntax-block/releases).

When creating a new code block, select `Code` block, and then in the Inspector (Block Controls on the Right) select the language for the code. The code will not change within the editor, but you'll see a small label with the selected language.

On the front-end when the post is being viewed, the code will be color syntax highlighted.

### Customize

If you want to change the colors, the default color theme is based off [GHColors](https://github.com/PrismJS/prism-themes/blob/master/themes/prism-ghcolors.css). You can download a new theme from the link above, or from the [Prism themes repo](https://github.com/PrismJS/prism-themes). The easiest way to customize is to download and customize the new css and replace `assets/prism.css`.


### Colophon

- Uses PrismJS syntax highlighter, http://prismjs.com/

- Uses customized GH Colors theme, https://github.com/PrismJS/prism-themes


### License

Copyright (c) 2018 Marcus Kazmierczak.

Licensed under <a href="https://opensource.org/licenses/GPL-2.0"> GPL 2.0 or later </a>.

