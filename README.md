# Sober CSS
CSS in JS via template strings

## Experimental (Just playing around with some API ideas)
I want to experiment with an approach to css in js that I think has a lot of potential. I'm wanting to start a conversation around the idea and see what the broader community thinks of it to make sure I havn't overlooked anything vital.

## Motivation
### What I want from a CSS solution
* Flexible
* Composable
* CSS (I want to use the CSS language to write CSS)
* Extendible
* IDE support (Syntax Highlighting, Autocomplete, etc)

## Overview
What if we just use ES6 template strings.

```javascript
import { css } from 'sober-css'

// language=css
const styles = css`
    body {
        background-color: blue;
    }
`
```

## Usage
