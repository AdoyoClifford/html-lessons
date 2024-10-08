# Teaching HTML: Creating a Kids' Restaurant Website

## Introduction
Explain to the children that we're going to create a fun website for a kids' restaurant using HTML. HTML is like a set of instructions that tells a web browser how to display a webpage.

## Step 1: Setting Up the Document
1. Start by explaining the basic structure of an HTML document:
   ```html
   <!DOCTYPE html>
   <html lang="en">
   <head>
     <!-- Information about our webpage goes here -->
   </head>
   <body>
     <!-- The content of our webpage goes here -->
   </body>
   </html>
   ```
2. Explain that `<head>` contains information about the webpage, while `<body>` contains what we actually see on the page.

## Step 2: Adding the Page Title
1. Inside the `<head>` section, add:
   ```html
   <meta charset="UTF-8">
   <meta name="viewport" content="width=device-width, initial-scale=1.0">
   <title>Yummy Tummy Kids' Restaurant</title>
   ```
2. Explain that the `<title>` tag sets the name of the webpage, which appears in the browser tab.

## Step 3: Creating the Main Heading
1. In the `<body>` section, add:
   ```html
   <h1>Welcome to Yummy Tummy Kids' Restaurant!</h1>
   ```
2. Explain that `<h1>` is used for the main heading of the page.

## Step 4: Adding an Image
1. Add the chef image:
   ```html
   <img src="https://media.tenor.com/QQx0-63k7rIAAAAM/mytona-cooking-diary.gif" alt="Happy chef cartoon" />
   ```
2. Explain that `<img>` is used to add images, `src` tells where to find the image, and `alt` provides a description for people who can't see the image.

## Step 5: Creating a List for the Menu
1. Add a subheading and start the list:
   ```html
   <h2>Our Yummy Menu:</h2>
   <ul>
     <li>Smiley Face Pizza</li>
     <li>Colorful Veggie Sticks</li>
     <li>Funny Shaped Chicken Nuggets</li>
     <li>Rainbow Fruit Salad</li>
     <li>Chocolate Chip Pancakes</li>
   </ul>
   ```
2. Explain that `<ul>` creates an unordered list, and each `<li>` is a list item.

## Step 6: Creating a Table for Special Meals
1. Add another subheading and create the table:
   ```html
   <h2>Today's Special Meals:</h2>
   <table border="1">
     <tr>
       <th>Meal</th>
       <th>Price</th>
     </tr>
     <tr>
       <td>Dinosaur Shaped Sandwich</td>
       <td>$5</td>
     </tr>
     <tr>
       <td>Magic Wand French Fries</td>
       <td>$3</td>
     </tr>
     <tr>
       <td>Unicorn Milkshake</td>
       <td>$4</td>
     </tr>
   </table>
   ```
2. Explain that `<table>` creates a table, `<tr>` is a table row, `<th>` is a table header, and `<td>` is a table cell.

## Step 7: Adding Another Image and Closing Message
1. Add the final elements:
   ```html
   <h2>Meet our Chef:</h2>
   <img src="https://media0.giphy.com/media/6jnKmSpBoJLaw/giphy.gif?cid=6c09b952ozly3mjp2g0rj7vfjw8tq6z0psb0hw513i9sf5pl&ep=v1_gifs_search&rid=giphy.gif&ct=g" alt="Cute animal mascot" />
   <p>Come visit us for a yummy and fun time!</p>
   ```
2. Explain that `<p>` is used for paragraphs of text.


## Extension Activities for Fast Finishers

If some students finish early or are looking for extra challenges, here are some additional activities they can try:

1. **Create a Daily Special**: 
   - Add a new section for a "Daily Special" dish.
   - Include a description of the dish and its price.
   - Challenge: Can they find and add a GIF image that represents this special dish?

2. **Design a Kids' Activity Section**:
   - Create a new section called "Fun Zone" or "Kids' Corner".
   - Add a list of activities available at the restaurant (e.g., coloring, puzzles, mini-games).
   - Challenge: Can they create a simple form where kids can vote for their favorite activity?

3. **Build a Simple Navigation Menu**:
   - Introduce the concept of links using the `<a>` tag.
   - Create a menu at the top of the page with links to different sections (e.g., "Menu", "Specials", "Fun Zone").
   - Challenge: Can they make the links jump to the correct sections on the page using ID attributes?

4. **Add a Footer**:
   - Create a footer section at the bottom of the page.
   - Include fictional restaurant information like address, phone number, and opening hours.
   - Challenge: Can they add social media icons (using emoji or text) that link to fictional social media pages?

5. **Customize with Inline Styles**:
   - Introduce the concept of inline CSS using the `style` attribute.
   - Let them experiment with changing colors of text, backgrounds, or borders.
   - Challenge: Can they create a colorful, rainbow-themed heading for the restaurant name?

6. **Create a 'Meet the Staff' Section**:
   - Add a new section introducing fictional restaurant staff.
   - Include fun character names and job titles.
   - Challenge: Can they create a simple table to organize this information?

