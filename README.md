# css-helpers

## Positioning elements

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


## Responsive design

### rem/em

#### Sets default 1rem=10px
html {
	box-sizing: border-box;
	font-size: 62.5%;
}

@media only screen and (max-width: 75em) {
	html {
		font-size: 56.25%;
	}
}

@media only screen and (max-width: 56.25em) {
	html {
		font-size: 50%;
	}
}

@media only screen and (min-width: 112.5em) {
	html {
		font-size: 75%;
	}
}
