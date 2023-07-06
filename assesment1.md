## HTML & CSS Assessment (5th July)

**Part 1: Multiple Choice Questions**

1. Which HTML tag is used to define an internal style sheet?
   - `<script>`
   - `<css>`
   - `<style>`
   - `<html>`
  Ans: <style>

2. Which HTML attribute is used to define inline styles?
   - `class`
   - `style`
   - `font`
   - `styles`
   Ans:<style>


3. Which property is used to change the background color?
   - `color`
   - `bgcolor`
   - `background-color`
   - `bg-color
   Ans:<background-color>`

4. How do you select an element with id "demo" in CSS?
   - `#demo`
   - `.demo`
   - `demo`
   - `*demo`
Ans:<#Demo>
5. What does CSS stand for?
   - Computer Style Sheets
   - Cascading Style Sheets
   - Creative Style Sheets
   - Colorful Style Sheets
   Ans:Cascading style sheets

**Part 2: True or False**

6. HTML comments start with `<!--` and end with `-->`.
'''true''
7. CSS `id` selectors are used to select elements with a specific class.
false
8. In HTML, inline elements are normally displayed without starting a new line.
'''true'''
9. The CSS `display` property specifies the display behavior of an element.
'''true'''
10. External CSS are defined within the `<html>` tag.
'''false'''

**Part 3: Practical Questions**

11. Write the HTML code to create a webpage with a heading, a paragraph and an image.
'''<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <heading>First Assessment</heading>
    <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Omnis totam assumenda quia similique r</p>
    <img src="https://images.freeimages.com/images/previews/ac9/railway-hdr-1361893.jpg" alt="">
</body>
</html>'''


12. Create a CSS rule that selects all paragraph elements on a page and sets the font-family to "Arial".
'''p{
    font-family: Arial, Helvetica, sans-serif;
}'''

13. Write HTML and CSS code to create a div with a class name "box" that has a width of 200px, a height of 200px, and a solid border of 2px.
'''<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="./style.css">
</head>
<body>
    <div class="box">
    <h1>Html Css Javascript</h1>
    </div>
</body>
</html>'''
'''.box h1{
    width: 200px;
    height: 200px;
    border: solid;
}'''


14. What is the difference between "class" and "id" in CSS? Give an example of when you would use each one.
'''class can be used multiple times while id can be used once in the program'''
15. Write HTML and CSS code to create a link that is styled as a button (use your own color and styling preferences).
'''<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="./button.css">
</head>
<body>
    
    <button>
        <a href="#">submit</a>
    </button>
    
</body>
</html>''''
'''.button{
    color: blue;
    background-color: blueviolet;
    font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
}'''`