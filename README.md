# base64bookmark

So, let’s assume you need to save a base64 encoded image that has been embedded into a website. That website may be using spans of a certain `id` attribute for referencing that image. You want to save the contents of the base64 stream as a JPG.

Time to create a JavaScript Bookmarklet (cf. https://www.freecodecamp.org/news/what-are-bookmarklets/) for that purpose.

## Usage

- Import base64bookmark.html in your browser’s bookmark manager
- Tested with Chrome (appends a sequential number to your downloaded jpgs) and Firefox
