# CSS Pseudo-Class Selector

A CSS pseudo-class is a keyword added to a selector that specifies a special state of the selected element(s). For example, :hover can be used to change a button's color when the user's pointer hovers over it.

- Pseudo-classes let you apply a style to an element not only in relation to the content of the document tree, but also in relation to external factors like the history of the navigator (:visited, for example), the status of its content (like :checked on certain form elements), or the position of the mouse (like :hover, which lets you know if the mouse is over an element or not).

# CSS Transitions

CSS transitions allows you to change property values smoothly, over a given duration.

.box {
    width: 200px;
    height: 200px;
    border: 1px solid black;
    background-color: cornflowerblue;
    /* transition-property: background-color;
    transition-duration: 1s;
    transition-timing-function: ease-in-out;
    transition-delay: 4s; */
    transition: background-color 1s ease-in 2s, width 1s ease-in-out;
}

.box:hover {
    background-color: lightcoral;
    width: 350px;
}