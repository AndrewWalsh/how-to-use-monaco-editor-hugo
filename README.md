# how-to-use-monaco-editor-hugo

A demonstration on how to use the [monaco editor](https://microsoft.github.io/monaco-editor/) with [Hugo shortcodes](https://gohugo.io/content-management/shortcodes/)

![demo](monaco-editor-demo.gif)

## How to Use It

- Add `monaco.html` as a shortcode
- Add code from `extend_footer.html` to the footer of your site (or bottom of the body)
- Use the shortcode as in `example_use.md`

## Shortcode Interface

*Mandatory*
- `id`: the HTML ID of the underlying div that the editor attaches to. This **must be unique**
- `language`: a valid language, e.g. from [here](https://microsoft.github.io/monaco-editor/api/modules/monaco.languages.html)

*Optional*
- `width`: the width of the editor
- `height`: the height of the editor

## Customisation

- [See the Monaco Editor Playground](https://microsoft.github.io/monaco-editor/playground.html#creating-the-editor-editor-basic-options)

## Adapting to Themes

The exact implementation will depend on the theme you use (e.g. [PaperMod](https://github.com/adityatelange/hugo-PaperMod))
