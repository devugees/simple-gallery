# simple-gallery
An exercise to create a very simple gallery made with jQuery and AJAX.

## Goal

train the loading of data with AJAX, jQuery event handlers and CSS positioning.

## Steps

1. create a GitHub repository
	2. got to your GitHub profile
	3. click the "Repositories"
	4. in the field "Repository name" enter "simple-gallery" (exactly)
	5. pick the "MIT" license
	6. click the "Dowload or clone" button
	7. make sure you are using the "SSH" URL (should start with "git@github"
	8. open a terminal
	9. enter `git clone <the SSH URL of your repository>` 
1. basics (see [simple-slider-step-1.jpg](simple-slider-step-1.jpg))
	1. find (at least) 5 images licensed under creative common (https://unsplash.com/)
		1. create a file `data.json` consisting of an array of object with the keys
			- `author`
			- `src`
			- `link`
			- `title`
	1. load the `data.json` file using `$.getJSON()`
	1. create a "pager" at the bottom of the page, when one of the pager item is clicked
	- it changes the information (image, author name, author link and title) accordingly
	- the clicked item is set to "active" (visually different from other pager items
	  *Hint:* use `removeClass` and `addClass`
	1. create a "Next" and "Back" button which when clicked act like clicking on either the next or the previous pager item
