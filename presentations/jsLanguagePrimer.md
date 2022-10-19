---
# theme id or package name
# Learn more: https://sli.dev/themes/use.html
theme: 'default'
# title of your slide, will auto infer from the first header if not specified
title: 'Functional Programming'
# titleTemplate for the webpage, `%s` will be replaced by the page's title
titleTemplate: '%s - Slidev'
# information for your slides, can be a markdown string
info: false

# enabled pdf downloading in SPA build, can also be a custom url
download: false
# filename of the export file
exportFilename: 'functiona-programming-exported'
# syntax highlighter, can be 'prism' or 'shiki'
highlighter: 'prism'
# show line numbers in code blocks
lineNumbers: true
# enable monaco editor, can be boolean, 'dev' or 'build'
monaco: true
# download remote assets in local using vite-plugin-remote-assets, can be boolean, 'dev' or 'build'
remoteAssets: false
# controls whether texts in slides are selectable
selectable: true
# enable slide recording, can be boolean, 'dev' or 'build'
record: false

# force color schema for the slides, can be 'auto', 'light', or 'dark'
colorSchema: 'auto'
# router mode for vue-router, can be "history" or "hash"
routerMode: 'history'
# aspect ratio for the slides
aspectRatio: '16/9'
# real width of the canvas, unit in px
canvasWidth: 980
# used for theme customization, will inject root styles as `--slidev-theme-x` for attribute `x`
themeConfig:
  primary: '#5d8392'

# favicon, can be a local file path or URL
favicon: 'https://cdn.jsdelivr.net/gh/slidevjs/slidev/assets/favicon.png'
# URL of PlantUML server used to render diagrams
plantUmlServer: 'https://www.plantuml.com/plantuml'
# fonts will be auto imported from Google fonts
# Learn more: https://sli.dev/custom/fonts
fonts:
  sans: 'Roboto'
  serif: 'Roboto Slab'
  mono: 'Fira Code'

# default frontmatter applies to all slides
defaults:
  layout: 'default'
  # ...

# drawing options
# Learn more: https://sli.dev/guide/drawing.html
drawings:
  enabled: true
  persist: false
  presenterOnly: false
  syncAll: true


# First slide
layout: cover
src: ./decks/JS-Language-Primer/slides/LanguagePrimer.md
---

---
src: ./decks/JS-Language-Primer/slides/JSLogo.md
---

---
src: ./decks/JS-Language-Primer/slides/JSTranspilation.md
---

---
src: ./decks/JS-Language-Primer/slides/VarLetConst.md
---

---
src: ./decks/JS-Language-Primer/slides/EqualityInJS.md
---

---
src: ./decks/JS-Language-Primer/slides/EqualityExamples.md
---

---
src: ./decks/JS-Language-Primer/slides/ValuesAndReferences.md
---

---
src: ./decks/JS-Language-Primer/slides/ValueExamples.md
---

---
src: ./decks/JS-Language-Primer/slides/ReferenceExamples.md
---

---
src: ./decks/JS-Language-Primer/slides/ArrowFunctions.md
---

---
src: ./decks/JS-Language-Primer/slides/ArrowFunctionsOverview.md
---

---
src: ./decks/JS-Language-Primer/slides/TemplateLiterals.md
---

---
src: ./decks/JS-Language-Primer/slides/SpreadOperator.md
---

---
src: ./decks/JS-Language-Primer/slides/ArraySpread.md
---

---
src: ./decks/JS-Language-Primer/slides/ObjectSpread.md
---

---
src: ./decks/JS-Language-Primer/slides/ObjectSpreadQuiz.md
---

---
src: ./decks/JS-Language-Primer/slides/RestParameters.md
---

---
src: ./decks/JS-Language-Primer/slides/RestParametersExamples.md
---

---
src: ./decks/JS-Language-Primer/slides/Destructuring.md
---

---
src: ./decks/JS-Language-Primer/slides/ArrayDestructuring.md
---

---
src: ./decks/JS-Language-Primer/slides/ObjectDestructuring.md
---

---
src: ./decks/JS-Language-Primer/slides/OptionalChaining.md
---

---
src: ./decks/JS-Language-Primer/slides/NullishCoalescing.md
---