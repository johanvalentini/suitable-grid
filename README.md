Suitable Grid
=============

A simple grid system written in SASS using [Compass](http://compass-style.org).

A compiled version of the sass files is found in the included stylesheets folder.

```html
<section class="section">
	<div class="container">
		<div class="row">
			<div class="column tablet12">
				<h1>This is a grid!</h1>
			</div>
			<div class="column tablet12">
				<h2>12 columns at tablet size</h2>
			</div>
		</div>
		<div class="row">
			<div class="column tablet6">
				<p>6 column at tablet size </p>
			</div>
			<div class="column tablet6">
				<p>6 columns at tablet size</p>
			</div>
			<div class="column tablet12">
				<div class="row">
					<div class="column tablet8">Columns in columns!</div>
					<div class="column tablet8">Columns in columns!</div>
					<div class="column tablet8">Columns in columns!$</div>
				</div>
			</div>
		</div>
	</div>
</section>
<section class="section">
	<div class="container">
		<div class="row">
			<div class="column mobile12">
				This fills out 50% even at small sizes
			</div>
			<div class="column mobile12">
				This fills out 50% even at small sizes
			</div>
		</div>
	</div>
</section>
```

# Partials structure
Everything is put together in main.scss. Partials are provided to try and break it up a bit. Most of them are mostly empty and are just used as a suggestion.

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


