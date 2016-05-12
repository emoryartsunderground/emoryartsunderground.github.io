# Emory Arts Underground Website

## Making changes
 - Log in using the username `emoryartsunderground` and the provided password
 - Download Github Desktop from [here](https://desktop.github.com/)
 - Once logged in, clone this project (instructions may vary, done on a Mac)
   - Click the `+` button in the upper left hand corner
   - Click the `clone` tab
   - Select the `emoryartsunderground.github.io` project
   - Choose a location on your computer to clone the project (if you forget, right-click on the project and open it in the computer's file browser)
 - Each post is housed in the `_posts` directory. Add or remove a post by adding or removing files from this directory. For each post, use the following template:

```
---
layout: post
title:  "Post Title"
date:   YYYY-MM-DD HH:MM:SS
preview: /pictures/image-name.extension (e.g. my-picture.jpg)
excerpt: Short excerpt about the post
---

Text for the post

Can add a picture:

![Picture](/path/to/picture)

```

A cheatsheet for writing stuff in Jekyll can be found [here](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet).

 - HTML and CSS files can be edited as well, although this is a bit more complicated.
 - To view the changes as you make them, without uploading to the web, either
   1. Install Jekyll from the command line (instructions are [here](https://jekyllrb.com/docs/installation/), could be technically difficult)
   2. Go to the post on Github and click the pencil in the top right corner to edit it. The preview won't appear exactly the same way as the post on the website, but it will give a good idea.
 - If you made changes on the Github site, go to the bottom and click "commit changes". Otherwise, once you're done making changes on your computer, go back to the Github application and commit the change
   - Make sure you're not in the `History` tab
   - Write a summary in the summary box describing the change (don't worry about writing a description)
   - Click "commit to master"
   - To push all your changes to the website, click "sync" in the top right corner.
   - Note! Click "sync" to update the version on your computer with the website version. If someone else makes changes, syncing will get their changes on your computer. You may have to resolve these changes if you both edited the same thing.
 - Done! Your updates should be visible on the website. Try reloading a few times if they're not, or check to make sure your commit message shows up on the Github website.
