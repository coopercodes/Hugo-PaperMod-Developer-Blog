---
title: "Learn JavaScript In 30 Minutes"
date: 2023-12-06T11:42:11-08:00
tags: ["HTML", "CSS"]
author: "Cooper Codes"
# author: ["Me", "You"] # multiple authors
showToc: true
TocOpen: false
draft: false
hidemeta: false
comments: false
description: "A complete beginners guide to JavaScript, covering variables, loops, and other JavaScript syntax."
summary: "A complete beginners guide to JavaScript, covering variables, loops, and other JavaScript syntax." # Summary is what shows on the homepage
canonicalURL: "https://canonical.url/to/page"
disableHLJS: false # to disable highlightjs
disableShare: false
disableHLJS: false
hideSummary: false
searchHidden: true
ShowReadingTime: true
ShowBreadCrumbs: true
ShowPostNavLinks: true
ShowWordCount: true
ShowRssButtonInSectionTermList: true
UseHugoToc: true
#cover:
#    image: "<image path/url>" # image path/url
#    alt: "<alt text>" # alt text
#    caption: "<text>" # display caption under cover
#    relative: false # when using page bundles set this to true
#    hidden: true # only hide on current single page
#editPost:
#    URL: "https://github.com/<path_to_repo>/content"
#    Text: "Suggest Changes" # edit text
#    appendFilePath: true # to append file path to Edit link
---

## Getting Started With HTML and CSS

### Creating Your First HTML File

The first thing we need to do when building out first website is create the index.html file. This requires us to open up an empty index.html file. The first thing we need to do when building out first website is create the index.html file. This requires us to open up an empty index.html file.

##### index.html

```html
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="utf-8">
        <title>Example HTML5 Document</title>
    </head>
    <body>
        <p>Test</p>
    </body>
</html>
```


### Creating Your First JavaScript Script

Then we need to create a script.js file outside of our HTML file! This allows us to add JavaScript functionality to our application.

##### script.js

```javascript
let text = "";

for (let i = 0; i < 5; i++) {
  text += "The number is " + i + "<br>";
}

console.log(text);
```
