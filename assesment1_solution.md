**Part 1: Multiple Choice Questions**

1. Which HTML tag is used to define an internal style sheet?
   - `<style>` ✔️

2. Which HTML attribute is used to define inline styles?
   - `style` ✔️

3. Which property is used to change the background color?
   - `background-color` ✔️

4. How do you select an element with id "demo" in CSS?
   - `#demo` ✔️

5. What does CSS stand for?
   - Cascading Style Sheets ✔️

**Part 2: True or False**

6. HTML comments start with `<!--` and end with `-->`.
   - True ✔️

7. CSS `id` selectors are used to select elements with a specific class.
   - False ✔️ (ID selectors are used to select elements with a specific ID)

8. In HTML, inline elements are normally displayed without starting a new line.
   - True ✔️

9. The CSS `display` property specifies the display behavior of an element.
   - True ✔️

10. External CSS are defined within the `<html>` tag.
   - False ✔️ (External CSS is linked to the HTML document with a `<link>` tag in the `<head>` section)

**Part 3: Practical Questions**

11. Write the HTML code to create a webpage with a heading, a paragraph, and an image.
```html
<!DOCTYPE html>
<html>
  <head>
    <title>Webpage</title>
  </head>
  <body>
    <h1>A Heading</h1>
    <p>This is a paragraph.</p>
    <img src="image.jpg" alt="A descriptive alt text">
  </body>
</html>
```

12. Create a CSS rule that selects all paragraph elements on a page and sets the font-family to "Arial".
```css
p {
  font-family: Arial;
}
```

13. Write HTML and CSS code to create a div with a class name "box" that has a width of 200px, a height of 200px, and a solid border of 2px.
```html
<div class="box"></div>
```
```css
.box {
  width: 200px;
  height: 200px;
  border: 2px solid black;
}
```

14. What is the difference between "class" and "id" in CSS? Give an example of when you would use each one.
- The "class" selector is used for elements with the same style. It can be used on multiple elements. For example, if you want to style all paragraphs the same way, you would use a class.
- The "id" selector is used for a single, unique element. It should be used when you want to style one specific element differently from others. For example, you may want to style the title of a page differently from other headings, in this case, you'd use an id.

15. Write HTML and CSS code to create a link that is styled as a button (use your own color and styling preferences).
```html
<a href="#" class="button">Button Link</a>
```
```css
.button {
  display: inline-block;
  padding: 10px 20px;
  background-color: blue;
  color: white;
  text-decoration: none;
  border-radius: 5px;
}
.button:hover {
  background-color: darkblue;
}
```
Please note that this is a simplified button style. For a production site, you may want to add more styles like transitions, focus and active states, etc.
