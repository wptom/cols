# cols
CSS grid and elements.

## Installation

1. `npm install`
2. `npm start`

## How to link to your project

Import `src/scss/main.scss` to your project's main.scss file.

OR

Link built main.css to your site.

`<link rel="stylesheet" href="/css/main.css">`

## Usage
### Columns and devices
`{COL}` is a number from 1 to 12.

`{DEVICE}` is a device: mobile, tablet, tablet-landscape, desktop, desktop-big.

These values can be changed in `src/scss/_variables.scss`

### Classes
`.container`

`.row`

`.col`

`.col-{COL}`

`.col-push-{COL}-{DEVICE}-up`

`.col-pull-{COL}-{DEVICE}-up`

### Mixins
`@include breakpoint({DEVICE}) {}`

### Examples
[URL](https://demo.wptom.com/cols)

