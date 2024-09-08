# Cascading Style Sheet
- Maintained by `World Wide Web Consortium` 
- CSS1 - 1996, CSS2 - 1998, CSS2.1 - 2011
- CSS rule consists of a Selector and a declaration block
- Specifity of `id > class`
- if #aaa, #222, #333 #bbb .... all are the gray color

## Units
- em is relative unit to the font size of its nearest parent
- `1em = 16px`
- for 1rem = we can specify the font size of our will
- we need 1rem = 10px, it makes our life easy
- for making the responsive website we tackel the media query in root element `font-size`

## Padding
- space between the border and content

## Margin
- Adjacent sibling margins consider only larger

## selectors
- child selctor `>`
- adjacent sibling `+`
- general sibling selector `~`
- descendent selector ` `
- universal selector `*`

## Flex Box
### Parent properties
- `flex-direction: row;` the horizontal will be the main-axis
- items display in a row (flex direction property`s default is row)
- Justify content (justify-content): justify-content aligns flex items along the main axis
- included `flex-start, flex-end, flex-center, flex-stretch` and `flex-baseline`
- flex-wrap :- included `nowrap (default), wrap, wrap-reverse`
- align-content :- included `flex-start, flex-end, center, space-between, space-around`
- align-items
- align-self
### Child properties
- flex-grow
- flex-shrink
- flex-basis
- flex (Shorthand for flex-grow, flex-shrink and flex-basis)

### NOTE 
> justify-content :- for row
> align-tems :- for column

## Level Of Specificcity
- 0.0.0.0.0
> `Element < Class < Id < Inline < !Important` 

# Useful Websites
- Color Hunt
- Google Fonts
- Da Fonts
- pixcap for images
- Font Awesome