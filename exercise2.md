# Exercise 2

We're going to add some CSS to style the HTML we wrote for our home page, `index.html`

### Steps

Don't forget: 
> Open VS Code
> File > Open - navigate to where you have the HTML5 Boilerplate files and select the root directory
> With your finder, navigate to `index.html`. Right click and open with Chrome. 
_(This lets you see the file rendered locally)_

1. First, let's add a `<main>` tag around all the content so we can give it some layout.
https://www.w3schools.com/tags/tag_main.asp
2. Now let's add some CSS. Open the file called `main.css` which is inside the `/css` folder.
3. Let's add a `max-width` to our `main` container, and then center it using `margin: auto`. Try different maximum widths (say 1200px, 500px, 100px), to see what happens to the layout. 
https://www.w3schools.com/css/css_max-width.asp
4. Now let's try changing the color of our `<h1>` tag. 
Pick a color from https://htmlcolorcodes.com/color-picker/
Apply that color using the `color` property.
https://www.w3schools.com/cssref/pr_text_color.asp
https://www.w3schools.com/cssref/css_colors.asp
5. You might want to try changing the background color of the `<body>` to see what happens! If you make it dark, you'll also want to change the text to be light so it shows up. 

### Color models in web documents 
There are several methods to indicate the color you want to style your tag with, including hexadecimal, which looks like `#000000` and RGB / RGBA (which stands for Red, Green, Blue, Alpha) and looks like `rgba(0,0,0,0.5)`. With RGBA, the numbers in your parentheses stand for `(Red, Green, Blue, Alpha)` so `rgba(0,0,0,0.5)` means 0 Red, 0 Green, 0 Blue, and 50% opacity.

Here's an example of what your CSS code could look like when you've completed the steps above: 
https://gist.github.com/summerscope/0711b00b2af189a4430a5bf1258de66e