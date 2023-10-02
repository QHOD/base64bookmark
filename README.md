# base64bookmark

So, let’s assume you need to save a base64 encoded image that has been embedded into a website. That website may be using spans of a certain `id` attribute for referencing that image. You want to save the contents of the base64 stream as a JPG.

Time to create a JavaScript Bookmarklet (cf. https://www.freecodecamp.org/news/what-are-bookmarklets/) for that purpose.

![Screenshot](screenshot.png "Screenshot of how to use this bookmarklet")

## Usage

- Import base64bookmark.html in your browser’s bookmark manager
- Load the HTML for each image
- Click your bookmarklet to save the jpg, which has been loaded
- Tested with Chrome (appends a sequential number to your downloaded jpgs) and Firefox
