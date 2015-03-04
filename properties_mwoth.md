# Here's a list of *all* CSS3 properties and their preferred order:

So this is a fairly simple list of CSS properties, categorized and sorted
by pure personal preference. There's a few justifications for odd ordering,
and whenever there's none it's alphabetical.

## Justifications
* All directional properties are sorted just like CSS does it (clockwise
  from top: top, right, bottom, left).
* Any properties that also have a shorthand are sorted in the same way they
  would be in the shorthand property.
* Categories (or subcategories) may be further categorized to prevent the
  fallback alphabetical sorting from confusing the final order.


## Box
* content
* will-change

### Generic styling
* all
* display
* box-sizing
* box-decoration-break
* break-before
* page-break-before
* break-inside
* page-break-inside
* break-after
* page-break-after
* isolation
* object-fit
* object-position
* widows
* orphans
* overflow
    * overflow-wrap
    * overflow-x
    * overflow-y
* visibility

### Flex
* flex
    * flex-basis
    * flex-direction
    * flex-flow
    * flex-grow
    * flex-shrink
    * flex-wrap
* order
* justify-content
* align-content
* align-items
* align-self

### Float
* float
* clear

### Location
* position
* top
* right
* bottom
* left
* offset-inline-start
* offset-inline-end
* offset-block-start
* offset-block-end
* vertical-align
* clip-path
* z-index

### Size
* height
* min-height
* max-height

* width
* min-width
* max-width

* inline-size
* min-inline-size
* max-inline-size

* block-size
* min-block-size
* max-block-size

### Padding
* padding
    * padding-top
    * padding-right
    * padding-bottom
    * padding-left

    * padding-inline-start
    * padding-inline-end
    * padding-block-start
    * padding-block-end

### Border
* border
    * border-style
    * border-width
    * border-color
    * border-collapse
    * border-spacing

    * border-top
        * border-top-color
        * border-top-style
        * border-top-width
    * border-right
        * border-right-color
        * border-right-style
        * border-right-width
    * border-bottom
        * border-bottom-color
        * border-bottom-style
        * border-bottom-width
    * border-left
        * border-left-color
        * border-left-style
        * border-left-width

    * border-inline-start
        * border-inline-start-color
        * border-inline-start-style
        * border-inline-start-width
    * border-inline-end
        * border-inline-end-color
        * border-inline-end-style
        * border-inline-end-width
    * border-block-start
        * border-block-start-color
        * border-block-start-style
        * border-block-start-width
    * border-block-end
        * border-block-end-color
        * border-block-end-style
        * border-block-end-width

    * border-radius
        * border-top-right-radius
        * border-bottom-right-radius
        * border-bottom-left-radius
        * border-top-left-radius

    * border-image
        * border-image-outset
        * border-image-repeat
        * border-image-slice
        * border-image-source
        * border-image-width

* outline
* outline-color
* outline-offset
* outline-style
* outline-width


### Margin
* margin
    * margin-top
    * margin-right
    * margin-bottom
    * margin-left

    * margin-inline-start
    * margin-inline-end
    * margin-block-start
    * margin-block-end


## Text
* color
* font
    * font-style
    * font-variant
        * font-variant-alternates
        * font-variant-caps
        * font-variant-east-asian
        * font-variant-ligatures
        * font-variant-numeric
        * font-variant-position
    * font-weight
    * font-stretch
    * font-size
    * font-size-adjust
    * line-height
    * font-family

    * font-kerning
    * font-feature-settings
    * font-language-override
    * font-synthesis

* direction
* writing-mode
* text-align
* text-align-last
* text-combine-upright
* text-decoration
    * text-decoration-color
    * text-decoration-line
    * text-decoration-style
* text-indent
* text-orientation
* text-overflow
* text-rendering
* text-shadow
* text-transform
* text-underline-position
* quotes

* shape-image-threshold
* shape-margin
* shape-outside

* hyphens
* letter-spacing
* line-break
* tab-size
* white-space
* word-break
* word-spacing
* word-wrap

* columns
* column-count
* column-fill
* column-gap
* column-rule
* column-rule-color
* column-rule-style
* column-rule-width
* column-span
* column-width


## Element specific
### Forms
* ime-mode

### Images
* image-rendering
* image-resolution
* image-orientation

### Lists
* list-style
* list-style-image
* list-style-position
* list-style-type

### Rubies
* ruby-align
* ruby-merge
* ruby-position

### Tables
* caption-side
* empty-cells
* table-layout


## Background
* background
    * background-image
    * background-position
    * background-size
    * background-repeat
    * background-origin
    * background-clip
    * background-color
    * background-attachment
    * background-blend-mode


## Visual effects
* backface-visibility
* box-shadow
* filter
* mask
* mask-type
* mix-blend-mode
* opacity
* perspective
* perspective-origin
* transform
* transform-origin
* transform-style


## Dynamic
* cursor
* pointer-events
* resize
* scroll-behavior
* touch-action

* counter-increment
* counter-reset

* animation
    * animation-name
    * animation-duration
    * animation-timing-function
    * animation-delay
    * animation-iteration-count
    * animation-direction
    * animation-fill-mode
    * animation-play-state
* transition
    * transition-delay
    * transition-duration
    * transition-property
    * transition-timing-function
