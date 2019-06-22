## Use border to visualize how things are working

        border: 1px solid red;

## flex

flex: 1
means everything takes up the same amount of space.

flex: 5
means it takes up 5 times the amount of room as everything else.

## Transitions

// This makes the panel spread out
/_ Safari transitionend event.propertyName ==flex _/
/_ Chrome + FF transitionend event.propertyNam=== flex-grow _/
transition: font-size 0.7s cubic-bezier(0.61-0.19, 0.7, -0.11),
flex 0.7s cubic-bezier(0.61, -0.19, 0.7, -0.11 background 0.2s;

// This makes the things move down.
transition: transform 0.5s;

## addEventListener

It doesn't run the function so we don't use toggleOpen().
We just want to give reference to the function so we only have toggleOpen.

## CSS \*

This selects all elements
https://www.w3schools.com/cssref/sel_all.asp

## CSS >

This will target elements that are DIRECT children of that element.
Any elements within those elements will not be selected.

https://techbrij.com/css-selector-adjacent-child-sibling

## Vocabulary

this.classList
????

## flex

is a sub property for Flexible Box

flex: 0 1 auto is the default value

flex: auto = 11 auto

flex: none = flex: 0 0 auto

https://developer.mozilla.org/en-US/docs/Web/CSS/flex

https://css-tricks.com/almanac/properties/f/flex/

## justify-content

This deals with the horizontal alignment of elements in a boundary.

start will justify items from the left.
center will justify items to the center.
space-between will justify items so that elements fill the row from left to right with space in the middle between elements.
space-around will justify items so thst they are evenly spaced around on both sides of each item. So when two elements are beside each other. 1px element 1px 1px element 1px.
space-evenly will evenly space elements between
https://developer.mozilla.org/en-US/docs/Web/CSS/justify-content

## align-items

deals with the items. It could have 4 properties.
stretch, center, start, and end.

Stretch will stretch the element as wide as the border
center will center the item in the middle vertically.
start will align the item to the top of the boundary.
end will align items at the bottom of the boundary.

https://developer.mozilla.org/en-US/docs/Web/CSS/align-items

## :first-child

CSS Selector Reference
https://www.w3schools.com/cssref/sel_firstchild.asp

## transform

https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Transitions/Using_CSS_transitions

transitions only go from start to finish.

div {
transition: <property> <duration> <timing-function> <delay>;
}

translateY
https://www.w3schools.com/cssref/css3_pr_transform.asp

## animatable CSS properties

https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_animated_properties

## classList.add

to add a class to a element with Javascfript
https://www.w3schools.com/howto/howto_js_add_class.asp

## transitionend

https://developer.mozilla.org/en-US/docs/Web/API/HTMLElement/transitionend_event
