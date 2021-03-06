Suitable Grid
=============

A simple grid system written in SASS using [Compass](http://compass-style.org).

A compiled version of the sass files is found in the included stylesheets folder. Check the included index.html for some more examples.

```html
<section class="section">
	<div class="container">
		<div class="row">
			<div class="column md12">
				<h1>This is a grid!</h1>
			</div>
			<div class="column md12">
				<h2>12 columns at md size</h2>
			</div>
		</div>
		<div class="row">
			<div class="column md6">
				<p>6 column at md size </p>
			</div>
			<div class="column md6">
				<p>6 columns at md size</p>
			</div>
			<div class="column md12">
				<div class="row">
					<div class="column md8">Columns in columns!</div>
					<div class="column md8">Columns in columns!</div>
					<div class="column md8">Columns in columns!</div>
				</div>
			</div>
		</div>
	</div>
</section>
<section class="section">
	<div class="container">
		<div class="row">
			<div class="column sm12">
				This fills out 50% even at small sizes
			</div>
			<div class="column sm12">
				This fills out 50% even at small sizes
			</div>
		</div>
	</div>
</section>
```

# Partials structure
Everything is put together in main.sass. Partials are provided to try and break it up a bit. Most of them are mostly empty and are just used as a suggestion. Feel free to remove and add more partials as the need arises.

A standalone [normalize.css](git.io/normalize) is included in the libraries folder. I find it a good starting point. Take it or leave it.

## _grid.scss
Contains the core of the grid classes.

## _variables.scss
Defines some default values of common things one wants to adjust. As a suggestion one can define the primary colors of the page and other repeatedly used variables for eased consistency.

## _input.scss
For styling input form fields

## _fonts.scss
Used to define the standard font sizes, line-heights and margins.

## _font_styling.scss
I sometimes split this out to define the standard header and subheader styles and fonts-family.

## _navigation.scss
I usually split out major sections if they are the same across multiple pages. A navigation section could be one.

## _transitions.scss
Define transitions and animations here.
