### HTML Structure

- `<!DOCTYPE html>`: This tells the browser that the document is an HTML5 document.
- `<html lang="en">`: This is the root element of the HTML document, and `lang="en"` specifies that the language is English.
- `<head>`: This section contains meta-information about the document, like the character set and the title.
- `<meta charset="UTF-8">`: This sets the character encoding for the document.
- `<meta name="viewport" content="width=device-width, initial-scale=1.0">`: This helps in making the webpage responsive on different devices.
- `<title>Document</title>`: This sets the title of the webpage, which appears in the browser tab.
- `<style>`: This section contains CSS (Cascading Style Sheets) code that styles the webpage.
- `<body>`: This is where the main content of the webpage is placed.

### Content

- `<h1>My dream vacation</h1>`: This is a big, red heading that says "My dream vacation."
- `<img src="..." alt="hand scrolling">`: This is an image that shows a hand scrolling. The `src` attribute tells the browser where to find the image, and `alt` provides a text description of the image.
- `<h2>Things I want to do</h2>`: This is a smaller, green heading that says "Things I want to do."
- `<ul class="activity-list">`: This is an unordered list (bullet points) that contains the activities.
  - `<li>Visit the Eiffel Tower</li>`: This is a list item that says "Visit the Eiffel Tower."
  - `<li>Go to the beach</li>`: This is a list item that says "Go to the beach."
  - `<li>Try new foods</li>`: This is a list item that says "Try new foods."
  - `<li>Learn a new language</li>`: This is a list item that says "Learn a new language."

### CSS Styling

- `body {font-family: sans-serif;}`: This sets the font of the entire webpage to a sans-serif font.
- `img {width: 50%; display: block; margin: 20px auto;}`: This makes the image take up half the width of the page, centers it, and adds some space around it.
- `.activity-list {list-style-type: none; margin: 20px auto; width: 50%; text-align: center;}`: This removes the bullet points from the list, centers the list, and makes it take up half the width of the page.
- `.activity-list li {padding: 10px; margin-bottom: 5px; border-radius: 5px; cursor: pointer; border: 1px solid black;}`: This styles each list item with padding, a border, rounded corners, and changes the cursor to a pointer when hovering over it.
- `.activity-list li:hover {background-color: lightgreen;}`: This changes the background color of the list item to light green when you hover over it.
- `h1 {text-align: center; color: red;}`: This centers the heading and makes it red.
- `h2 {text-align: center; color: green;}`: This centers the subheading and makes it green.
