# WGBH Front-end Test

# To Run
Download the repository. Open the terminal and run a server from the repository directory. I used python's SimplerServer to do this via `python -m SimpleHTTPServer 8000`. This is my preferred script for running a server locally. Please open in Chrome.

# Technology

## Styles
I used vanilla CSS for this project. For larger, more complex projects I would have used a CSS preprocessor like Sass or Less.
Instead of reinventing the wheel I used similar styles to the styles used on the [Masterpiece](https://www.pbs.org/wgbh/masterpiece/) website.
Styles are organized from a mobile first design, changing to a desktop layout at 960px with media queries.
Note: I started with an HTML Boilerplate that brought in normal.css which is my preferred css reset and main.css. The stylesheet I created is styles.css.

## Markup
I used HTML5 for semantic markup that provides basic accessibility. Some notable HTML5 elements are `<time>` and `<img srcset />`
### time
I like the `<time>` element for displaying this type of information on an HTML page. I built the `datetime` attribute with javascript.
### img srcset
This was a good place to demonstrate responsive images, especially since Tim, Mike and I talked about this technique. A simple refresh might be needed to display the correct image size.

## Javascript
The javascript is internal to the HTML page. If the script was longer or needed on other pages I would have made it external.
The JSON file has one edit, I added the image name to the `weekly_episode`. The JSON file is loaded with `XMLHttpRequest`. The `program` arrays are parsed with ES6 `.map()` method. Template strings are used to build the program template that is displayed with `innerHTML`.


<!-- # The Task
Please create a page for Masterpiece which highlights the content for the upcoming week.

# The Parameters
## Provided
We've provided a JSON data file, plus an SVG Masterpiece logo and a weekly episode for two programs, Downton Abbey and Les Miserables.

## What are the rules?

### Technology
- You are free to use whatever technology with which you feel comfortable and which you feel would be well suited to the task.  
- Please present your final product as either a github repo or a docker file/image with instructions on how to display locally.

### Assets
 - You are free to modify/add to the json file, keeping the basic structure the
   same.
 - You may get new assets via the web that you think would improve the experience.

### Usability
- The page should look good at desktop and mobile widths
- Good accessibility is appreciated.

### Time Limit
There is no specific time limit. However, you should shoot for 2 hours or under. -->
