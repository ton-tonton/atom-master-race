# Atom-Master-Race

### Packages
1. activate-power-mode
2. atom-beautify
3. atom-typescript
4. autocomplete-paths
5. autoprefixer
6. emmet
7. file-icons
8. glowing-cursor
9. highlight-line
10. highlight-selected
11. line-ending-converter
12. linter
13. linter-erb
14. linter-eslint
15. linter-htmlhint
16. linter-reek
17. linter-tslint
18. linter-write-good
19. minimap
20. pigments
21. quick-highlight
22. rails-snippets
23. set-syntax

### Themes
1. atom-material-ui
2. material-monokai-syntax

### Stylesheet
```CSS
@fontsize: 20px;

atom-text-editor {
  font-family: 'Fira Code';
  font-style: normal;
  text-rendering: optimizeLegibility;
}
atom-text-editor {
  .syntax--string.syntax--quoted,
  .syntax--string.syntax--regexp {
    -webkit-font-feature-settings: "liga" off, "calt" off;
  }
  .syntax--source.syntax--js > .syntax--keyword.syntax--control,
  .syntax--storage,
  .syntax--type .syntax--function {
    vertical-align: baseline;
    font-family: 'flottflott';
    height: inherit;
    font-size: 1.5 * @fontsize;
    line-height: @fontsize;
  }
  .syntax--source.syntax--js,
  .syntax--storage.syntax--type.syntax--function.syntax--arrow.syntax--js,
  .syntax--storage.syntax--type.syntax--class.syntax--todo,
  .indent-guide,
  .syntax--variable {
    font-family: 'Fira Code';
    font-style: normal;
    font-size: @fontsize;
    line-height: 1.5 * @fontsize;
  }
  .syntax--string.syntax--unquoted.syntax--js {
    color: #CDD3DE;
  }
  .syntax--entity.syntax--name {
    font-weight: bold;
  }
}
```
**ref**
1. [An alternative to Operator Mono font](https://medium.com/@docodemore/an-alternative-to-operator-mono-font-6e5d040e1c7e#.ero0varpr)
2. [MattMcFarland/styles.less](https://gist.github.com/MattMcFarland/e41ef709b1d82adea800563a86805559#gistcomment-1835618)
