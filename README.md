## Intl.StringFormat API Specification [draft]

### Status

__Stage 0__

Implementation Progress

 * Polyfill: https://github.com/zbraniecki/IntlStringFormat

Backpointers

* https://groups.google.com/forum/#!topic/javascript-globalization/3nFDf5al5hU

### Authors

 * Zibi Braniecki (@zbraniecki)

### Reviewers

TBD

### Informative

This proposal is based on the LDML spec, C.11 Language Plural Rules:


### Prior Art


### Usage

```javascript
let o = new Intl.StringFormat("en", {
    style: "regular" // default style
});
console.log(o.truncate('Lorem ipsum dolor sit amet', {
  maxLength: 10
}); // "Lorem ips…"
```

### Render Spec

```bash
npm install
npm run build
open index.html
```
