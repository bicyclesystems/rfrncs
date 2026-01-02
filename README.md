# rfrncs

a collection of csv files containing reference data for html elements, attributes, css selectors and more. designed as a quick resource for designers and developers.

## usage

fetch csv files directly from:

```
https://bicyclesystems.github.io/rfrncs/{filename}.csv
```

### available files

| file | url |
|------|-----|
| css pseudo classes | `https://bicyclesystems.github.io/rfrncs/css-pseudo-classes.csv` |
| css selectors | `https://bicyclesystems.github.io/rfrncs/css-selectors.csv` |
| files | `https://bicyclesystems.github.io/rfrncs/files.csv` |
| html attributes | `https://bicyclesystems.github.io/rfrncs/html-attributes.csv` |
| html elements | `https://bicyclesystems.github.io/rfrncs/html-elements.csv` |
| html global attributes | `https://bicyclesystems.github.io/rfrncs/html-global-attributes.csv` |

### example

```javascript
const response = await fetch('https://bicyclesystems.github.io/rfrncs/html-elements.csv');
const data = await response.text();
```
