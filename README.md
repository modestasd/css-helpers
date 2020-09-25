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

## Image/Background

### Blend mode 

#### Adds cool blending mode to background image 

.element {
    background-image: url(backgroundImage);
    background-color: green;
    background-blend-mode: hard-light;
}

### Clip-path

#### Allows to make custom shapes(online generator https://bennettfeely.com/clippy/)

.element {
    clip-path: polygon(0 0, 100% 0, 100% 53%, 0 86%);
}

### Gradient

#### Adds custom transition between two or more colors

.element {
    background-image:linear-gradient(to right bottom,
        rgba(218, 120, 102, 0.8),
        rgba(255, 99, 71, 0.7)),
        url(${backgroundImage});
}
