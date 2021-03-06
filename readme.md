# CSS Cheat Sheet
A quick go to guide for CSS goodness. Checkout the [pretty version](http://adam-marsden.co.uk/css-cheat-sheet).

## Contributing
If you have a bug to report about the [pretty CSS Cheat Sheet](http://adam-marsden.co.uk/css-cheat-sheet) or something to add onto the CSS Cheat Sheet follow the [contribution guidelines](https://github.com/AdamMarsden/css-cheat-sheet/blob/master/CONTRIBUTING.md).

## CSSCS Nav

  * [Selectors](https://github.com/AdamMarsden/css-cheat-sheet#selectors)
  * [Pseudo Selectors](https://github.com/AdamMarsden/css-cheat-sheet#pseudo-selectors)
  * [Font Styling](https://github.com/AdamMarsden/css-cheat-sheet#font-styling)
  * [Position](https://github.com/AdamMarsden/css-cheat-sheet#position)
  * [Background](https://github.com/AdamMarsden/css-cheat-sheet#background)
  * [Box properties](https://github.com/AdamMarsden/css-cheat-sheet#box-properties)
  * [List Styling](https://github.com/AdamMarsden/css-cheat-sheet#list-styling)
  * [Flexbox](https://github.com/AdamMarsden/css-cheat-sheet#flexbox)
  * [CSS Grid](https://github.com/AdamMarsden/css-cheat-sheet#css-grid)


### Selectors

Universal Selector `* {}`

Type Selector `h1, h2 ,h3 {}`

Child Selector `ul > li {}`

Descendant Selector `p a {}`

Class Selector `.class {}`

ID Selector `#id {}`

Adjacent Sibling Selector `h1 + p {}`

General Sibling Selector `h1 ~ p {}`

Attribute Selector `[attribute="SomeValue"] {}`

### Pseudo Selectors

Mouse Over Selector `a:hover {}`

Active Link Selector `a:active {}`

Focus Selector `input:focus {}`

Visited Links Selector `a:visited {}`

Link Selector `.class:link {}`

First Line Selector `p::first-line {}`

First Letter Selector `p::first-letter {}`

First Child Selector `p:first-child {}`

Last Child Selector `p:last-child {}`

:nth-child Selector `p:nth-child() {}`

First Element of its Parent Selector `p:first-of-type {}`

Checked elements selector  `input:checked {}`

Disabled elements selector `input:disabled {}`

Enabled elements selector `input:enabled {}`

Elements that have no Children Selector (including text nodes) `p:empty {}`

Not a Specified Element Selector `:not(p) {}`

### Font Styling

Font style `font-style: normal | italic | oblique`

Font Variant `font-variant: normal | small-caps`

Font Weight `font-weight: normal | bold | bolder | lighter | 100 - 900`

Vertical Alignment `vertical-align: baseline | 10px | sub | super | top | text-top | middle | bottom | text-bottom | initial`

Font Size `font-size: 12px | 0.8em | 80%`

Text Transform `text-transform: capitalise | lowercase | uppercase`

Space Between Characters `letter-spacing: normal | 4px`

Line Height `line-height: normal | 3em | 34%`

Horizontal Alignment `text-align: left | right | center | justify`

Text Decoration `text-decoration: none | underline | overline | line-through`

Indent First Line `text-indent: 25px`

Font Family `font-family: 'Open Sans', sans-serif`

### Position

Position `position: static | relative | absolute | fixed | sticky`

Position Properties `top | right | bottom | left`

Float Element `float: left | right | none`

Clear Floating Elements `clear: none | left | right | both`

Z Index `z-index: 3 | auto | inherit`

### Background

Background Image `background-image: url()`

Background Repeat `background-repeat: repeat-x | repeat-y | repeat | space | round | no-repeat`

Background Color `background-color: #2AA9E0`

Background Position `background-position: top | right | bottom | left | center`

Background Attachment `background-attachment: scroll | fixed | local | initial | inherit`

### Box properties

Box Sizing `box-sizing: border-box | content-box`

Margin `margin: 2px 4px 6px 8px | 0 auto`

Padding `padding: 2px 4px 6px 8px`

Border Color `border-color: #2AA9E0`

Border Style `border-style: none | hidden | dotted | dashed | solid | double | groove | ridge | inset | outset`

Border Width `border-width: 10px`

### List Styling

List Type `list-style-type: disc | circle | square | none`

List Position `list-style-position: inside | outside`

List Image `list-style-image: url()`

### Flexbox

Flex Direction `flex-direction: row | row-reverse | column | column-reverse`

Flex Wrap `flex-wrap: nowrap | wrap | wrap-reverse`

Justify Content `justify-content: flex-start | flex-end | center | space-between | space-around | space-evenly`

Align Items `align-items: flex-start | flex-end | center | baseline | stretch`

Align Content `align-content: flex-start | flex-end | center | space-between | space-around | stretch`

Order `order: 0`

Flex Grow `flex-grow: 0`

Flex Shrink `flex-shrink: 1`

Flex Basis `flex-basis: 3px | auto`

Align Self `align-self: auto | flex-start | flex-end | center | baseline | stretch`

### CSS Grid

Grid Template Columns `grid-template-columns: 40px 50px auto 50px 40px`

Grid Template Rows `grid-template-rows: 25% 100px auto`

Grid Template Areas `lgrid-template-areas: "a b c" | none`

Grid Template `grid-template: "a a a" 20% "b b b" auto | 100px 1fr / 50px 1fr`

Grid Column Gap `grid-column-gap: 10px`

Grid Row Gap `grid-row-gap: 10px`

Justify Items `justify-items: start | end | center | stretch`

Align Items `align-items: start | end | center | stretch`

Justify Content `justify-content: flex-start | flex-end | center | space-between | space-around | space-evenly`

Align Content `align-content: flex-start | flex-end | center | space-between | space-around | stretch`

Grid Auto Columns `grid-auto-columns: 100px | max-content | min-content`

Grid Auto Rows `grid-auto-rows: 100px | max-content | min-content`

Grid Auto Flow `grid-auto-flow: row | column | row dense | column dense`

Grid Column Start `grid-column-start: 2 | areaname | span 2 | span areaname | auto`

Grid Column End `grid-column-end: 2 | areaname | span 2 | span areaname | auto`

Grid Row Start `grid-row-start: 2 | areaname | span 2 | span areaname | auto`

Grid Row End `grid-row-end: 2 | areaname | span 2 | span areaname | auto`

Grid Column `grid-column: 3 / span 2`

Grid Row `grid-row: 3 / span 2`

Justify Self `justify-self: start | end | center | stretch`

Align Self `align-self: start | end | center | stretch`

## Credits

Built & Maintained by [Adam Marsden](https://twitter.com/AdamMarsdenUK)

## License

[Creative Commons Attribution-ShareAlike](https://creativecommons.org/licenses/by-sa/4.0/)
