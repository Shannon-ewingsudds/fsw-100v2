# CSS Flexbox Layout Module

Before the Flexbox Layout module, there were four layout modes:

* Block, for sections in a webpage
* Inline, for text
* Table, for two-dimensional table data
* Positioned, for explicit position of an element

The Flexible Box Layout Module, makes it easier to design flexible responsive layout structure without using float or positioning.

_ The main idea behind the flex layout is to give the container the ability to alter its items’ width, height, and order to best fill the available space. A flex container expands items to fill available free space or shrinks them to prevent overflow.


## flex-direction: row (default):
    - justify-content: left to right (main axis)
    - align-items: top to bottom (cross axis)
    
## flex-direction: column
    - justify-content: top to bottom (cross axis)
    - align-items: left to right (main axis)

    display: flex;
    flex-direction: row;
    justify-content: center;
    align-items: center;

    height: 200px;
    margin: 20px;
    padding: 20px;

    .flex-container > div:nth-child(1){
    background-color: dodgerblue;
    height: 30px;
}

.flex-container > div:nth-child(2){
    background-color: firebrick;
    height: 30px;
}

.flex-container > div:nth-child(3){
    background-color: violet;
    height: 30px;
}