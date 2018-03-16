# Exercise 2

We're going to add some CSS to style the HTML we wrote for our home page, `index.html`

### Steps

1. First, let's add a `<main>` tag around all the content so we can give it some layout.
https://www.w3schools.com/tags/tag_main.asp
2. Now let's add some CSS. Open the file called `main.css` which is inside the `/css` folder.
3. Let's add a `max-width` to our `main` container, and then center it using `margin: auto`. Try different maximum widths (say 1200px, 500px, 100px), to see what happens to the layout. 
https://www.w3schools.com/css/css_max-width.asp
4. Now let's try changing the color of our `<h1>` tag. Pick a color from https://htmlcolorcodes.com/color-picker/. Apply that color using the `color` property:
https://www.w3schools.com/cssref/pr_text_color.asp
https://www.w3schools.com/cssref/css_colors.asp
5. You might want to try changing the background color of the `<body>` to see what happens! If you make it dark, you'll also want to change the text to be light so it shows up.
6. What else might you want to style? The color of your paragraph tags? Add a border to your image?

### Color models in web documents 
There are several methods to indicate the color you want to style your tag with, including hexadecimal, which looks like `#000000` and RGB / RGBA (which stands for Red, Green, Blue, Alpha) and looks like `rgba(0,0,0,0.5)`. With RGBA, the numbers in your parentheses stand for `(Red, Green, Blue, Alpha)` so `rgba(0,0,0,0.5)` means 0 Red, 0 Green, 0 Blue, and 50% opacity.

### Adding fonts to web documents.
You have a few options if you want to change the font used on your tags. One is to use a web-safe font stack. This provides instructions which tells your computer to look for fonts which are already installed, and if the first option isn't available on the client's hard-drive it moves down the list until it finds one that is available. 
https://www.cssfontstack.com/ 

Alternatively, you can host custom fonts yourself on your web server, or use a service like Google Fonts, or Adobe Typekit, which host and serve the fonts for you. https://typekit.com https://fonts.google.com 

### Code reference
Here's an example of what your CSS code could look like when you've completed the steps above: 
https://gist.github.com/summerscope/0711b00b2af189a4430a5bf1258de66e