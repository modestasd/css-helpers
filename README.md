# css-helpers

## Moving elements

### Margin
Use on block elements that have a defined width

#### Center element horizontally: 
.element {
    margin: 0 auto;
    width: 100px;
}

#### Move element to the end of the page 
.element {
    margin-left: auto;
    width: 100px;
}

### Grid 

#### Move element to center horizontally and vertically

.element {
	display: grid;
	place-items: start;
}
