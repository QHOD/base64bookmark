# base64bookmark

So, let’s assume you need to save a base64 encoded image that has been embedded into a website. That website may be using spans of a certain `id` attribute for referencing that image. You want to save the contents of the base64 stream as a JPG.

Time to create a JavaScript Bookmarklet (cf. https://www.freecodecamp.org/news/what-are-bookmarklets/) for that purpose.

![Screenshot](screenshot.png "Screenshot of how to use this bookmarklet")

## Usage

1. Import base64bookmark.html in your browser’s bookmark manager

![import bookmark](https://github.com/QHOD/base64bookmark/assets/37441365/497447d5-bf00-4f7d-a19f-cee97f22a14d)
![imported bookmark](https://github.com/QHOD/base64bookmark/assets/37441365/b0d9b3c0-9bd3-4e1b-8f7c-7e8ff2d28aec)

2. Load the HTML page for each image
3. Click your bookmarklet to save the jpg, which has been loaded
4. Tested with Chrome (appends a sequential number to your downloaded jpgs) and Firefox
