# Quantasy Carousel

## Markup Notes
* The only markup required is the '.q-carousel-wrapper' and '.q-carousel' div.
* The carousel will render itself inside of .q-carousel.
* All the other elements can be placed and styled anywhere you want, as long as it's inside of the .q-carousel-wrapper.
* .title, .desc, .credit will update itself per slide.

## Carousel Options
### Here are the parameters you can pass into the init function.
* elementId [string] - This is the ID of the element you want to place the carousel into. (required)
* endpoint [string] - The url of the endpoint we're requesting the json data from. (required)
* category [integer] - Category ID of the gallery we're requesting. (required)
* gridView [integer] - Specify how many images to show per slide in the grid view. You can set to false if you don't want to render a grid view.
* adFrequency [integer] - Inserts an ad in every (x) slot.
* updateInfo [boolean] - Set to true if you have title, desc, credit set for each image and you want it to update when you change slides.
