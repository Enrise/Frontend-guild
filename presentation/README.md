# Presentations in Reveal.js

All presentations in this folders are served with [RevealJS](http://lab.hakim.se/reveal-js/#/). This is a framework that accepts presentations in Markdown and serves them in a browser.

## Installation
```
npm install
```

## View presentation
```
npm run view [filename.md]

npm run view frontend-for-sales.md # for example
```

## Templating
Presentation sheets are separated by the markdown `hr`: `---`. RevealJS puts its slides in order from left to right, but also offers the opportunity for each slide to be placed below another slide.
This slide can then be seen as a child of its parent slide. Childs are created with `----` (four hyphens).

Example:

```md
# Presentation for frontend
## Second header

---

# Next sheet

---

# Good luck!
```
