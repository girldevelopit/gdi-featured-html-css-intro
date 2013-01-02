# CORE  HTML/CSS

This is the official Girl Develop It Core HTML/CSS curriculum. It was developed through the contributions of Pamela Fox, Alexis Goldstein, Erin M. Kidwell, Izzy Johnston, and Jen Myers.

The course is meant to be taught in 4 two-hour sections. Each of the slides and practice files are customizable according to the needs of a given class or audience.

## Classes

### Class 1

Introduction to HTML. What is it? Why does it matter?
You will go through the basic history of HTML, including how it interacts with the browser and why that matters.
Then you will discuss the layout of an HTML page, including html, body, head and nesting.
Finally, you will go through many of the basic HTML elements.
Students will begin to make a personal portfolio page with HTML elements and no styling.

### Class 2
Introduction to CSS. Colors? Styles? What? It's all true. And you thought we are going to make you live your life in black and white.

You will go through most of the css styles, including font changes, layout, size, and color. You will show how to connect them to html selectors. The CSS file will be an external file.

Students will add CSS styling to their portfolio.

### Class 3

Introduction to divs, spans, ids and classes. You didn't think we would just leave you with paragraphs and lists did you? No, my friends. We are going to dive into these super valuable container elements. Then learn how to have id and class selectors in our CSS. Who wants all paragraphs to look the same.
Students will start customizing their portfolio with all sorts of goodies. 

### Class 4

Box model? Floating? Columns? What is this sorcery? You've brought people through the core of html and css. Now give them the next steps to be pros. Students will add columns, footers and headers to their portfolios.

## Theme customization

You can change theme colors by changing the theme css to any of the following options:
```html
  <link rel="stylesheet" href="css/theme/gdidefault.css" id="theme">
  <link rel="stylesheet" href="css/theme/gdilight.css" id="theme">
  <link rel="stylesheet" href="css/theme/gdisunny.css" id="theme">
  <link rel="stylesheet" href="css/theme/gdicool.css" id="theme">
```
You can change the text editor theme by changing the highlight.js css to the following options:
```html
  <link rel="stylesheet" href="lib/css/dark.css">
  <link rel="stylesheet" href="lib/css/light.css">
```
You can change transition by changing the reveal transition property in Reveal.initialize
```javascript
  Reveal.initialize({
  				transition:  'default', // default/cube/page/concave/zoom/linear/none
  			});
```
