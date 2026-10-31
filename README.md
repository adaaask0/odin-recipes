# odin-recipes
The Odin Project - HTML Basics - Recipes project

## About ##
The website will consist of main index page which will have links to a few recipes. It won't look pretty it will highlight the fundamentals I've learned in the HTML Fundamentals section of The Odin Project course. This project allows me to utilise the skills learned from the HTML Foundations course, provided by The Odin Projects. Mainly the setup and use of basic HTML syntaxes and elements, such as:
- index.html setup
- use of `<a href>` for linking pages
- use of `<ul>` (unordered) and `<ol>` (ordered) lists
- use of `<img src=" " />` to render pages

I've also been able to apply element parameters, specifically to things like links and images where I can define alt text that would support the accessibility for those who are visually impaired or when images are unable to load. Also, the use of width and height which, as per TOP recommendations should be utilised, as often as possible to avoid any re-sizing issues during loading between `HTML` and `CSS`.

More importantly, I'm also applying the learning about GIT Basics whereby utilising my repo in GitHub, I am able to present and in practice fetch, analyse, and review my work in a structured approach with full trace of changes applied.

## The Assignment ##

### Iteration 1: initial structure ###
- [x] Within the `odin-recipes directory`, create an `index.html` file.
- [x] Fill it out with the usual boilerplate HTML and add an `h1` heading “Odin Recipes” to the body.

### Iteration 2: recipe page ###
- [x] Create a new directory within the `odin-recipes` directory and name it `recipes`.
- [x] Create a new HTML file within the `recipes` directory and name it after the recipe it will contain. For example `lasagna.html`. You can use the name of your favorite dish or, if you need some inspiration, you can find a recipe to use at [Allrecipes](https://www.allrecipes.com/). Be sure to include the usual boilerplate HTML. This boilerplate code should be in every `.html` file you create.
- [x] For now, just include an `h1` heading with the recipe’s name as its content.
- [x] Back in the `index.html` file, add a link to the recipe page you just created. Example: Under the `<h1>Odin Recipes</h1>` heading, write out the link like so: `<a href="recipes/recipename.html">Recipe Title</a>`. The text of the link should again be the recipe name.
- [x] Add a link back to the index page on your recipe page for easier navigation. You can place this link at the top or bottom of your recipe page (e.g., `lasagna.html`). This allows users to quickly return to the home page after viewing the recipe.

### Iteration 3: recipe page content ###
- [] A free image of the finished dish under the `h1` heading that you added earlier.
- [] Under the image, it should have an appropriately sized “Description” heading followed by a paragraph or two describing the recipe.
- [] Under the description, add an “Ingredients” heading followed by an unordered list of the ingredients needed for the recipe.
- [] Finally, under the ingredients list, add a “Steps” heading followed by an ordered list of the steps needed for making the dish.

### Iteration 4: add more recipes ###
- [] Create two more recipe pages. Make sure they have the exact same layout as your first recipe page.
- [] Don’t forget to link to the new recipes on the index page. Also, consider putting all the links in an unordered list so they aren’t all on one line.
