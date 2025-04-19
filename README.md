# Cops and Robbers V Wiki
## Format
The wiki is written in the [Markdown](https://www.markdownguide.org/) format, with some HTML support.
You probably already know some Markdown, because many popular apps, including Discord, support writing in Markdown, for example, you can add `#` at the start of the sentence to mark it as a heading, and wrap words in `**` to make them bold.

Click [here](https://www.markdownguide.org/cheat-sheet/) for a cheat sheet so that you can quickly familiarize yourself with the format.

## Index file
There's an `index.md` file which is used by the CNRV website to automatically generate the navigation tree view. It's basically a simple bullet list with multiple levels of depth. It can be as deep as you want, but we recommend a maximum of 4 levels to keep the navigation tree easily readable.

## Paths
The full path of the file determines the URL of the page. For example the page located in `/basics/colors.md` will be viewable at https://gtacnr.net/wiki/basics/colors.

Page and folder names must be **lowercase**, only contain **alphanumeric** characters (a-z, 0-9) and dashes (no spaces or symbols). The best practice is to separate each word with a dash `-`.

## Images
In most cases, images should be hosted on the website directly, instead of linked from outside. 

Just send your images to Golfi or Sasino to get them reviewed and added to the content folder. 

Link an image with the following format: `![alt text](image.jpg)`

Content hosted on the server can be linked from the `/wiki-content` folder, for example: `![screenshot](/wiki-content/basics/money/screenshot-1.jpg)`.

Please, make sure that screenshots are saved in the .jpg format, and preferrably in the 16:9 format. Animated images should be in the GIF format. Icons and other small things can be in any format, PNG and SVG preferred for those.

## Comments
HTML-style comments are supported. It's useful sometimes to leave comments for other coders, or to leave certain things out of the wiki temporarily, for example:
```
<!--
This is a comment and it won't show up in the page.
-->
# This will show up
Because it's normal text
```

Keep in mind that people can view the comments with "View page source".
<!-- Yes, I knew you would try. -->