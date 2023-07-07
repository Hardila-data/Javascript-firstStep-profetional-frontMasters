## DOM
This is a basic default Document.html. When JavaScript is looking that document what it see is a representation called DOM
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    
</body>
</html>
```
This bunch of code has multiple tags,that could be shown in a tree:
Javascript create and entity that respresent all this structure 
![image](https://github.com/Hardila-data/skills-introduction-to-github/assets/67773921/6e0aa153-9ecd-41e7-8e7a-d0354c19bb85)


## Finding Elements
In Javascript we called the object **document** that represent the all page (Entire HMTL Document).
Some information from the page can be found directly with the tag name. For example: *title* and *body* tag. This example display 
title of the page and the content in the boby element.
![image](https://github.com/Hardila-data/skills-introduction-to-github/assets/67773921/281599b0-cdb8-4970-bad0-061336254454)

As describe in the images above we can consider the DOM as a tree representation of the page. We can access to the elements
inside an specific tag  *.children*. *.children* give us an HTMLCollection For instance: document.body.children
![image](https://github.com/Hardila-data/skills-introduction-to-github/assets/67773921/cfc89156-f434-47ef-ab22-f1ca552e61ce)
