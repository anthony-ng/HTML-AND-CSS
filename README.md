# HTML AND CSS

## Learning Competencies

* Use [Semantic HTML](http://www.webstyleguide.com/wsg3/5-site-structure/2-semantic-markup.html) to structure a website
* Use CSS selectors to efficiently select any DOM element #p2
* Explain the tradeoffs of different CSS selectors and CSS specificity and design your CSS to optimize these
* Change basic CSS appearance: colors, widths, padding, margin
* Position elements using CSS positioning, display and float

## Summary
HTML is used to create the general structure of a page.  CSS is used to add styles to this page.  In this challenge you will use HTML and CSS to recreate an existing web site.

## Releases
Work through each release completely before moving on.  When you finish a release, make sure you UNDERSTAND the code.

###Release 0: Choose your poison
Find a web page that represents a topic / item you are interested in (like bicycles).  The page should be relatively simple but have some images and some text. If you don't want to choose your own site, you may use the `sample.png` image provided.

* Take a screenshot of the website.  You will use this screenshot for your recreation (you should NOT look at the html or styles from the original site - base all your work off the screenshot.)  Add this screenshot to your source forder

* Create an `image` directory and download a subset of the images from the page to this folder. (Your page does not need to have exact images - if there are a lot of similar images you can use one to represent them all).

### Release 1 : The HTML
Create the HTML using HTML 5.
*  Create the `<head>` tag with links to a `normalize.css` and your style sheet `styles.css`.
* Create the `<body>` with a `<header>`, `<nav>` and content.
* You can duplicate the text of your site exactly, or if there is a lot of text you can use [lorem ipsum](http://www.lipsum.com/) text.
* Add all the images.
* Make sure your page is [validated](http://validator.w3.org/).

Your HTML should contain as little formatting as possible.

### Release 2 : Add the CSS

Your CSS should recreate the format of your original page.  At a minimum your page should contain the following CSS elements and styles:

* Basic selectors like id, class and  element
* Two advanced selectors like sibling, psuedo, child, etc.
* Box model styles like margin, border, and padding
* Position styles like fixed, absolute, relative and static
* Background styles for color or image
* Font styles
* CSS3 styles like rounded border if required in your image.
* Use a color picker to get the correct colors.

Save your HTML and CSS files to the source folder and submit a pull request to turn in this challenge.

### Release 3 SASS or SCSS (optional)

Once you have a solid representation of your site, see if you can reimplement your CSS using [SASS][sass].  SASS allows you to write compilable CSS which allows you to use lots of cool features like variables, nesting and math. You will have to use the `sass gem` and compile your sass page into css from the command line.

## Optimize your learning
Make sure you are **learning CSS** not just getting caught in the **try and see** cycle.

* Can you explain how you created each effect?
* Can you explain why you made choices of particular css properties (like display, float, positioning)?
* Is your CSS well factored for change? If the main navigation were to move from the top to the left side, how hard would it be to implement?

## Resources

* [Semantic HTML](http://www.webstyleguide.com/wsg3/5-site-structure/2-semantic-markup.html)
* the [box model](http://css-tricks.com/the-css-box-model/)
* [positioning](http://alistapart.com/article/css-positioning-101)
* [display](http://reference.sitepoint.com/css/display)
* [float](http://alistapart.com/article/css-floats-101)
* [normalize.css](http://necolas.github.io/normalize.css/)
* [CSS Zen Garden](http://www.csszengarden.com/)
* [SASS][sass]

[sass]:http://www.sass-lang.com/install
