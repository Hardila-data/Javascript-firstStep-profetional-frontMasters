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

<ul>Different ways to find elements:</ul>
    <li>document.getElementById()</li>
    <li>document.querySelector()</li>
    <li>document.getElementsByClassName</li>
    <li>document.getElementsByTagName</li>
    <li>document.querySelectorAll()</li>
In the following image, there is an example of the different methods to find the elements. one of them give us HTMLCollections another like .getElementById() give us an specific element.

![image](https://github.com/Hardila-data/skills-introduction-to-github/assets/67773921/2612281f-804e-46e1-ba09-973bc5180cf3)

## .length & .textContent
Using the methods getElementsByClassName() or getElementsByTagName() can give us a HTMLCollections(multiple tags in a file could have the same class) to know the number of elements with an especific class name, we can use .length
![image](https://github.com/Hardila-data/skills-introduction-to-github/assets/67773921/7b7b602d-9037-4c83-87e4-5425714fea95)f3)

## Modify the web page
To modify text in the web page, we can use the assigment operator(=) or .appened()
![image](https://github.com/Hardila-data/skills-introduction-to-github/assets/67773921/c88aff06-1b72-4419-afea-7cf7a431fb21)


    
    
